---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/concurrenthashtableinfobyptr
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `ConcurrentHashTableInfoByPtr` Class Template

<p>ConcurrentHashTable - is a resizeable concurrent hashtable. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;typename KeyTy, typename KeyDataTy, typename AllocatorTy&gt;
class llvm::ConcurrentHashTableInfoByPtr&lt;KeyTy, KeyDataTy, AllocatorTy&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/concurrenthashtable-h">llvm/ADT/ConcurrentHashtable.h</a>"
</div>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename KeyTy, typename KeyDataTy, typename AllocatorTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static uint64_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#abb20cdc9d073209d4c5c7ced28165d96">getHashValue</a> (const KeyTy &amp;Key)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename KeyTy, typename KeyDataTy, typename AllocatorTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a7aefc852266534710249a877d4e89a96">isEqual</a> (const KeyTy &amp;LHS, const KeyTy &amp;RHS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename KeyTy, typename KeyDataTy, typename AllocatorTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> KeyTy &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a3a77ca8506207a5a0751194113a265f5">getKey</a> (const KeyDataTy &amp;KeyData)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename KeyTy, typename KeyDataTy, typename AllocatorTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static KeyDataTy *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a3a4f4feeaa7367627785fa335b336c56">create</a> (const KeyTy &amp;Key, AllocatorTy &amp;Allocator)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>ConcurrentHashTable - is a resizeable concurrent hashtable.</p>


<p>The number of resizings limited up to x2^31. This hashtable is useful to have efficient access to aggregate <a href="/web-llvm/docs/api/files/lib/lib/codegen/staticdatasplitter-cpp/#ad2fefd8832b4b1ea3dbb1f621063bbff">data(like strings,
type descriptors...)</a> and to keep only single copy of such an aggregate. The hashtable allows only concurrent insertions:</p>


<p>KeyDataTy* = insert ( const KeyTy&amp; );</p>


<p>Data structure:</p>


<p>Inserted value KeyTy is mapped to 64-bit hash value -&gt;</p>



<pre><code>     [------- 64-bit Hash value --------]
     [  StartEntryIndex ][ Bucket Index ]
               |                |
         points to the     points to
         first probe       the bucket.
         position inside
         bucket entries
</code></pre>


<p>After initialization, all buckets have an initial size. During insertions, buckets might be extended to contain more entries. Each bucket can be independently resized and rehashed(no need to lock the whole table). Different buckets may have different sizes. If the single bucket is full then the bucket is resized.</p>


<p>BucketsArray keeps all buckets. Each bucket keeps an array of Entries (pointers to KeyDataTy) and another array of entries hashes:</p>


<p>BucketsArray[BucketIdx].Hashes[EntryIdx]: BucketsArray[BucketIdx].Entries[EntryIdx]:</p>


<p>[Bucket 0].Hashes -&gt; [uint32_t][uint32_t] [Bucket 0].Entries -&gt; [KeyDataTy*][KeyDataTy*]</p>


<p>[Bucket 1].Hashes -&gt; [uint32_t][uint32_t][uint32_t][uint32_t] [Bucket 1].Entries -&gt; [KeyDataTy*][KeyDataTy*][KeyDataTy*][KeyDataTy*] ......................... [Bucket N].Hashes -&gt; [uint32_t][uint32_t][uint32_t] [Bucket N].Entries -&gt; [KeyDataTy*][KeyDataTy*][KeyDataTy*]</p>


<p><a href="/web-llvm/docs/api/classes/llvm/concurrenthashtablebyptr">ConcurrentHashTableByPtr</a> uses an external thread-safe allocator to allocate KeyDataTy items.</p>


<p>Definition at line 76 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/concurrenthashtable-h">ConcurrentHashtable.h</a>.</p>


<div class="doxySectionDef">

## Public Static Functions

### create() {#a3a4f4feeaa7367627785fa335b336c56}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyTy, typename KeyDataTy, typename AllocatorTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">KeyDataTy * llvm::ConcurrentHashTableInfoByPtr&lt; KeyTy, KeyDataTy, AllocatorTy &gt;::create (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> KeyTy &amp; Key, AllocatorTy &amp; Allocator)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>newly created object of KeyDataTy type.</p></dd>
</dl>


<p>Definition at line 94 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/concurrenthashtable-h">ConcurrentHashtable.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocbasic-cpp/#ad5d00e1d77644d95847b9bf8da12b759">Allocator</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a98c6256d0644613c6b5b3e2ef06ef5ce">llvm::InnerAnalysisManagerProxy&lt; AnalysisManagerT, IRUnitT, ExtraArgTs... &gt;::Key</a>.</p>

</div>
</div>

### getHashValue() {#abb20cdc9d073209d4c5c7ced28165d96}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyTy, typename KeyDataTy, typename AllocatorTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::ConcurrentHashTableInfoByPtr&lt; KeyTy, KeyDataTy, AllocatorTy &gt;::getHashValue (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> KeyTy &amp; Key)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>Hash value for the specified <span class="doxyComputerOutput">Key</span>.</p></dd>
</dl>


<p>Definition at line 79 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/concurrenthashtable-h">ConcurrentHashtable.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a98c6256d0644613c6b5b3e2ef06ef5ce">llvm::InnerAnalysisManagerProxy&lt; AnalysisManagerT, IRUnitT, ExtraArgTs... &gt;::Key</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a23db35042db15bf83edbd2250ea0ee90">llvm::xxh3_64bits</a>.</p>

</div>
</div>

### getKey() {#a3a77ca8506207a5a0751194113a265f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyTy, typename KeyDataTy, typename AllocatorTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const KeyTy &amp; llvm::ConcurrentHashTableInfoByPtr&lt; KeyTy, KeyDataTy, AllocatorTy &gt;::getKey (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> KeyDataTy &amp; KeyData)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>key for the specified <span class="doxyComputerOutput">KeyData</span>.</p></dd>
</dl>


<p>Definition at line 89 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/concurrenthashtable-h">ConcurrentHashtable.h</a>.</p>

</div>
</div>

### isEqual() {#a7aefc852266534710249a877d4e89a96}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyTy, typename KeyDataTy, typename AllocatorTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ConcurrentHashTableInfoByPtr&lt; KeyTy, KeyDataTy, AllocatorTy &gt;::isEqual (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> KeyTy &amp; LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> KeyTy &amp; RHS)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if both <span class="doxyComputerOutput">LHS</span> and <span class="doxyComputerOutput">RHS</span> are equal.</p></dd>
</dl>


<p>Definition at line 84 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/concurrenthashtable-h">ConcurrentHashtable.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/concurrenthashtable-h">ConcurrentHashtable.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>

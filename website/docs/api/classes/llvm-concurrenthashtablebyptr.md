---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/concurrenthashtablebyptr
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `ConcurrentHashTableByPtr` Class Template



## Declaration

<div class="doxyDeclaration">
template &lt;typename KeyTy, typename KeyDataTy, typename AllocatorTy, typename Info = ConcurrentHashTableInfoByPtr&lt;KeyTy, KeyDataTy, AllocatorTy&gt;&gt;
class llvm::ConcurrentHashTableByPtr&lt;KeyTy, KeyDataTy, AllocatorTy, Info&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/concurrenthashtable-h">llvm/ADT/ConcurrentHashtable.h</a>"
</div>

## Protected Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aa3e778be998a13fea1fddd7272d378c9">ExtHashBitsTy</a> = uint32_t</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a6894f2cdd05844b8809e7e2039210fb7">EntryDataTy</a> = KeyDataTy *</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a76ae32da073683b2d4d166533619df7b">HashesPtr</a> = <a href="#aa3e778be998a13fea1fddd7272d378c9">ExtHashBitsTy</a> *</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a6aad12071c0bf07633da45ddffaacdb8">DataPtr</a> = <a href="#a6894f2cdd05844b8809e7e2039210fb7">EntryDataTy</a> *</td>
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

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#aedb1b2d838f24c81b5c649395e24ef08">ConcurrentHashTableByPtr</a> (AllocatorTy &amp;Allocator, uint64_t EstimatedSize=100000, size_t ThreadsNum=parallel::strategy.compute_thread_count(), size_t InitialNumberOfBuckets=128)</td>
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

## Public Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a2b0501783145a93d5caf9d61fac6c645">~ConcurrentHashTableByPtr</a> ()</td>
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

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a05f04083a96d1718f46e8f875425e636">insert</a> (const KeyTy &amp;NewValue) -&gt; std::pair&lt; KeyDataTy *, bool &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Insert new value <span class="doxyComputerOutput">NewValue</span> or return already existing entry. <a href="#a05f04083a96d1718f46e8f875425e636">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac62bbcb37f3fbd47a66763f0125e9829">printStatistic</a> (raw_ostream &amp;OS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Print information about current state of hash table structures. <a href="#ac62bbcb37f3fbd47a66763f0125e9829">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ade6907f5a5422e625635b35e22dfe10a">RehashBucket</a> (Bucket &amp;CurBucket)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a857ab9b7da763acc25c658249b28392b">getBucketIdx</a> (hash_code Hash)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ae8cffee93b5b0c062e8d97e379bb1ef1">getExtHashBits</a> (uint64_t Hash)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a168883c86f9ce8b870444e70b6764735">getStartIdx</a> (uint32_t ExtHashBits, uint32_t BucketSize)</td>
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

## Protected Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a3062279d7619a6e1e925718e7057ba38">HashBitsNum</a> = 0</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a88cae2ee8b5852e292ba945d9bf202ce">HashMask</a> = 0</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a79fe851e75611aa5b65b7b32a99ffb30">ExtHashMask</a> = 0</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a5452a8e46c9edbecda4976ddac1f0e38">MaxBucketSize</a> = 0</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#adefb4d96f9a87300048d14536cb53d57">InitialBucketSize</a> = 0</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aa62532a0a71ab55bbfc89fda24e23ed5">NumberOfBuckets</a> = 0</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/structs/llvm/concurrenthashtablebyptr/bucket">Bucket</a>[]&gt;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a45da1a667c220a2ac0fedb7909854fdd">BucketsArray</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">AllocatorTy &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af35139c2a8f5bac9ccaa8fbdf71f575b">MultiThreadAllocator</a></td>
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


<p>Definition at line 102 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/concurrenthashtable-h">ConcurrentHashtable.h</a>.</p>


<div class="doxySectionDef">

## Protected Member Typedefs

### DataPtr {#a6aad12071c0bf07633da45ddffaacdb8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyTy, typename KeyDataTy, typename AllocatorTy, typename Info = ConcurrentHashTableInfoByPtr&lt;KeyTy, KeyDataTy, AllocatorTy&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::ConcurrentHashTableByPtr&lt; KeyTy, KeyDataTy, AllocatorTy, Info &gt;::DataPtr =  EntryDataTy *</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 274 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/concurrenthashtable-h">ConcurrentHashtable.h</a>.</p>

</div>
</div>

### EntryDataTy {#a6894f2cdd05844b8809e7e2039210fb7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyTy, typename KeyDataTy, typename AllocatorTy, typename Info = ConcurrentHashTableInfoByPtr&lt;KeyTy, KeyDataTy, AllocatorTy&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::ConcurrentHashTableByPtr&lt; KeyTy, KeyDataTy, AllocatorTy, Info &gt;::EntryDataTy =  KeyDataTy *</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 271 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/concurrenthashtable-h">ConcurrentHashtable.h</a>.</p>

</div>
</div>

### ExtHashBitsTy {#aa3e778be998a13fea1fddd7272d378c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyTy, typename KeyDataTy, typename AllocatorTy, typename Info = ConcurrentHashTableInfoByPtr&lt;KeyTy, KeyDataTy, AllocatorTy&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::ConcurrentHashTableByPtr&lt; KeyTy, KeyDataTy, AllocatorTy, Info &gt;::ExtHashBitsTy =  uint32_t</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 270 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/concurrenthashtable-h">ConcurrentHashtable.h</a>.</p>

</div>
</div>

### HashesPtr {#a76ae32da073683b2d4d166533619df7b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyTy, typename KeyDataTy, typename AllocatorTy, typename Info = ConcurrentHashTableInfoByPtr&lt;KeyTy, KeyDataTy, AllocatorTy&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::ConcurrentHashTableByPtr&lt; KeyTy, KeyDataTy, AllocatorTy, Info &gt;::HashesPtr =  ExtHashBitsTy *</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 273 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/concurrenthashtable-h">ConcurrentHashtable.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### ConcurrentHashTableByPtr() {#aedb1b2d838f24c81b5c649395e24ef08}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyTy, typename KeyDataTy, typename AllocatorTy, typename Info = ConcurrentHashTableInfoByPtr&lt;KeyTy, KeyDataTy, AllocatorTy&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ConcurrentHashTableByPtr&lt; KeyTy, KeyDataTy, AllocatorTy, Info &gt;::ConcurrentHashTableByPtr (AllocatorTy &amp; Allocator, uint64_t EstimatedSize=100000, size_t ThreadsNum=parallel::strategy.compute_thread_count(), size_t InitialNumberOfBuckets=128)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 104 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/concurrenthashtable-h">ConcurrentHashtable.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocbasic-cpp/#ad5d00e1d77644d95847b9bf8da12b759">Allocator</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a45da1a667c220a2ac0fedb7909854fdd">llvm::ConcurrentHashTableByPtr&lt; KeyTy, KeyDataTy, AllocatorTy, Info &gt;::BucketsArray</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a66191f0bcc8c62b784819e9e96ceeba2">llvm::countl_zero</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a57d2f9ee99e9e68cff564d0d579c8163">llvm::countr_zero</a>, <a href="#a79fe851e75611aa5b65b7b32a99ffb30">llvm::ConcurrentHashTableByPtr&lt; KeyTy, KeyDataTy, AllocatorTy, Info &gt;::ExtHashMask</a>, <a href="#a3062279d7619a6e1e925718e7057ba38">llvm::ConcurrentHashTableByPtr&lt; KeyTy, KeyDataTy, AllocatorTy, Info &gt;::HashBitsNum</a>, <a href="#a88cae2ee8b5852e292ba945d9bf202ce">llvm::ConcurrentHashTableByPtr&lt; KeyTy, KeyDataTy, AllocatorTy, Info &gt;::HashMask</a>, <a href="#adefb4d96f9a87300048d14536cb53d57">llvm::ConcurrentHashTableByPtr&lt; KeyTy, KeyDataTy, AllocatorTy, Info &gt;::InitialBucketSize</a>, <a href="#a5452a8e46c9edbecda4976ddac1f0e38">llvm::ConcurrentHashTableByPtr&lt; KeyTy, KeyDataTy, AllocatorTy, Info &gt;::MaxBucketSize</a>, <a href="#af35139c2a8f5bac9ccaa8fbdf71f575b">llvm::ConcurrentHashTableByPtr&lt; KeyTy, KeyDataTy, AllocatorTy, Info &gt;::MultiThreadAllocator</a>, <a href="#aa62532a0a71ab55bbfc89fda24e23ed5">llvm::ConcurrentHashTableByPtr&lt; KeyTy, KeyDataTy, AllocatorTy, Info &gt;::NumberOfBuckets</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5542d44947f8d964b5ce3b20ea719b44">llvm::PowerOf2Ceil</a> and <a href="/web-llvm/docs/api/namespaces/llvm/parallel/#a68f04a4e2c26fa6b9cd7517dced50729">llvm::parallel::strategy</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~ConcurrentHashTableByPtr() {#a2b0501783145a93d5caf9d61fac6c645}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyTy, typename KeyDataTy, typename AllocatorTy, typename Info = ConcurrentHashTableInfoByPtr&lt;KeyTy, KeyDataTy, AllocatorTy&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual llvm::ConcurrentHashTableByPtr&lt; KeyTy, KeyDataTy, AllocatorTy, Info &gt;::~ConcurrentHashTableByPtr ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 160 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/concurrenthashtable-h">ConcurrentHashtable.h</a>.</p>


<p>References <a href="#a45da1a667c220a2ac0fedb7909854fdd">llvm::ConcurrentHashTableByPtr&lt; KeyTy, KeyDataTy, AllocatorTy, Info &gt;::BucketsArray</a> and <a href="#aa62532a0a71ab55bbfc89fda24e23ed5">llvm::ConcurrentHashTableByPtr&lt; KeyTy, KeyDataTy, AllocatorTy, Info &gt;::NumberOfBuckets</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### insert() {#a05f04083a96d1718f46e8f875425e636}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyTy, typename KeyDataTy, typename AllocatorTy, typename Info = ConcurrentHashTableInfoByPtr&lt;KeyTy, KeyDataTy, AllocatorTy&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; KeyDataTy *, bool &gt; llvm::ConcurrentHashTableByPtr&lt; KeyTy, KeyDataTy, AllocatorTy, Info &gt;::insert (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> KeyTy &amp; NewValue)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Insert new value <span class="doxyComputerOutput">NewValue</span> or return already existing entry.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>entry and "true" if an entry is just inserted or "false" if an entry already exists.</p></dd>
</dl>


<p>Definition at line 172 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/concurrenthashtable-h">ConcurrentHashtable.h</a>.</p>


<p>References <a href="#a45da1a667c220a2ac0fedb7909854fdd">llvm::ConcurrentHashTableByPtr&lt; KeyTy, KeyDataTy, AllocatorTy, Info &gt;::BucketsArray</a>, <a href="/web-llvm/docs/api/structs/llvm/concurrenthashtablebyptr/bucket/#a49298c812045349a99ae5d9c1f66f887">llvm::ConcurrentHashTableByPtr&lt; KeyTy, KeyDataTy, AllocatorTy, Info &gt;::Bucket::Entries</a>, <a href="#a857ab9b7da763acc25c658249b28392b">llvm::ConcurrentHashTableByPtr&lt; KeyTy, KeyDataTy, AllocatorTy, Info &gt;::getBucketIdx</a>, <a href="#ae8cffee93b5b0c062e8d97e379bb1ef1">llvm::ConcurrentHashTableByPtr&lt; KeyTy, KeyDataTy, AllocatorTy, Info &gt;::getExtHashBits</a>, <a href="#a168883c86f9ce8b870444e70b6764735">llvm::ConcurrentHashTableByPtr&lt; KeyTy, KeyDataTy, AllocatorTy, Info &gt;::getStartIdx</a>, <a href="/web-llvm/docs/api/structs/llvm/concurrenthashtablebyptr/bucket/#a7b75e8b63cf9b1849f0310f3d82acb28">llvm::ConcurrentHashTableByPtr&lt; KeyTy, KeyDataTy, AllocatorTy, Info &gt;::Bucket::Hashes</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="#af35139c2a8f5bac9ccaa8fbdf71f575b">llvm::ConcurrentHashTableByPtr&lt; KeyTy, KeyDataTy, AllocatorTy, Info &gt;::MultiThreadAllocator</a>, <a href="/web-llvm/docs/api/structs/llvm/concurrenthashtablebyptr/bucket/#ab2b0b6cb8e9ed68ff3a3ab5e5ed90548">llvm::ConcurrentHashTableByPtr&lt; KeyTy, KeyDataTy, AllocatorTy, Info &gt;::Bucket::NumberOfEntries</a>, <a href="#ade6907f5a5422e625635b35e22dfe10a">llvm::ConcurrentHashTableByPtr&lt; KeyTy, KeyDataTy, AllocatorTy, Info &gt;::RehashBucket</a> and <a href="/web-llvm/docs/api/structs/llvm/concurrenthashtablebyptr/bucket/#aa615b1ffd20a1385b4fa159a306d2b5e">llvm::ConcurrentHashTableByPtr&lt; KeyTy, KeyDataTy, AllocatorTy, Info &gt;::Bucket::Size</a>.</p>

</div>
</div>

### printStatistic() {#ac62bbcb37f3fbd47a66763f0125e9829}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyTy, typename KeyDataTy, typename AllocatorTy, typename Info = ConcurrentHashTableInfoByPtr&lt;KeyTy, KeyDataTy, AllocatorTy&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::ConcurrentHashTableByPtr&lt; KeyTy, KeyDataTy, AllocatorTy, Info &gt;::printStatistic (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Print information about current state of hash table structures.</p>

<p>Definition at line 228 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/concurrenthashtable-h">ConcurrentHashtable.h</a>.</p>


<p>References <a href="#a45da1a667c220a2ac0fedb7909854fdd">llvm::ConcurrentHashTableByPtr&lt; KeyTy, KeyDataTy, AllocatorTy, Info &gt;::BucketsArray</a>, <a href="#adefb4d96f9a87300048d14536cb53d57">llvm::ConcurrentHashTableByPtr&lt; KeyTy, KeyDataTy, AllocatorTy, Info &gt;::InitialBucketSize</a>, <a href="#aa62532a0a71ab55bbfc89fda24e23ed5">llvm::ConcurrentHashTableByPtr&lt; KeyTy, KeyDataTy, AllocatorTy, Info &gt;::NumberOfBuckets</a>, <a href="/web-llvm/docs/api/structs/llvm/concurrenthashtablebyptr/bucket/#ab2b0b6cb8e9ed68ff3a3ab5e5ed90548">llvm::ConcurrentHashTableByPtr&lt; KeyTy, KeyDataTy, AllocatorTy, Info &gt;::Bucket::NumberOfEntries</a> and <a href="/web-llvm/docs/api/structs/llvm/concurrenthashtablebyptr/bucket/#aa615b1ffd20a1385b4fa159a306d2b5e">llvm::ConcurrentHashTableByPtr&lt; KeyTy, KeyDataTy, AllocatorTy, Info &gt;::Bucket::Size</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### getBucketIdx() {#a857ab9b7da763acc25c658249b28392b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyTy, typename KeyDataTy, typename AllocatorTy, typename Info = ConcurrentHashTableInfoByPtr&lt;KeyTy, KeyDataTy, AllocatorTy&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::ConcurrentHashTableByPtr&lt; KeyTy, KeyDataTy, AllocatorTy, Info &gt;::getBucketIdx (<a href="/web-llvm/docs/api/classes/llvm/hash-code">hash_code</a> Hash)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 362 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/concurrenthashtable-h">ConcurrentHashtable.h</a>.</p>


<p>Reference <a href="#a88cae2ee8b5852e292ba945d9bf202ce">llvm::ConcurrentHashTableByPtr&lt; KeyTy, KeyDataTy, AllocatorTy, Info &gt;::HashMask</a>.</p>


<p>Referenced by <a href="#a05f04083a96d1718f46e8f875425e636">llvm::ConcurrentHashTableByPtr&lt; KeyTy, KeyDataTy, AllocatorTy, Info &gt;::insert</a>.</p>

</div>
</div>

### getExtHashBits() {#ae8cffee93b5b0c062e8d97e379bb1ef1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyTy, typename KeyDataTy, typename AllocatorTy, typename Info = ConcurrentHashTableInfoByPtr&lt;KeyTy, KeyDataTy, AllocatorTy&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::ConcurrentHashTableByPtr&lt; KeyTy, KeyDataTy, AllocatorTy, Info &gt;::getExtHashBits (uint64_t Hash)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 364 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/concurrenthashtable-h">ConcurrentHashtable.h</a>.</p>


<p>References <a href="#a79fe851e75611aa5b65b7b32a99ffb30">llvm::ConcurrentHashTableByPtr&lt; KeyTy, KeyDataTy, AllocatorTy, Info &gt;::ExtHashMask</a> and <a href="#a3062279d7619a6e1e925718e7057ba38">llvm::ConcurrentHashTableByPtr&lt; KeyTy, KeyDataTy, AllocatorTy, Info &gt;::HashBitsNum</a>.</p>


<p>Referenced by <a href="#a05f04083a96d1718f46e8f875425e636">llvm::ConcurrentHashTableByPtr&lt; KeyTy, KeyDataTy, AllocatorTy, Info &gt;::insert</a>.</p>

</div>
</div>

### getStartIdx() {#a168883c86f9ce8b870444e70b6764735}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyTy, typename KeyDataTy, typename AllocatorTy, typename Info = ConcurrentHashTableInfoByPtr&lt;KeyTy, KeyDataTy, AllocatorTy&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::ConcurrentHashTableByPtr&lt; KeyTy, KeyDataTy, AllocatorTy, Info &gt;::getStartIdx (uint32_t ExtHashBits, uint32_t BucketSize)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 368 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/concurrenthashtable-h">ConcurrentHashtable.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>


<p>Referenced by <a href="#a05f04083a96d1718f46e8f875425e636">llvm::ConcurrentHashTableByPtr&lt; KeyTy, KeyDataTy, AllocatorTy, Info &gt;::insert</a> and <a href="#ade6907f5a5422e625635b35e22dfe10a">llvm::ConcurrentHashTableByPtr&lt; KeyTy, KeyDataTy, AllocatorTy, Info &gt;::RehashBucket</a>.</p>

</div>
</div>

### RehashBucket() {#ade6907f5a5422e625635b35e22dfe10a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyTy, typename KeyDataTy, typename AllocatorTy, typename Info = ConcurrentHashTableInfoByPtr&lt;KeyTy, KeyDataTy, AllocatorTy&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::ConcurrentHashTableByPtr&lt; KeyTy, KeyDataTy, AllocatorTy, Info &gt;::RehashBucket (<a href="/web-llvm/docs/api/structs/llvm/concurrenthashtablebyptr/bucket">Bucket</a> &amp; CurBucket)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 299 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/concurrenthashtable-h">ConcurrentHashtable.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/structs/llvm/concurrenthashtablebyptr/bucket/#a49298c812045349a99ae5d9c1f66f887">llvm::ConcurrentHashTableByPtr&lt; KeyTy, KeyDataTy, AllocatorTy, Info &gt;::Bucket::Entries</a>, <a href="#a168883c86f9ce8b870444e70b6764735">llvm::ConcurrentHashTableByPtr&lt; KeyTy, KeyDataTy, AllocatorTy, Info &gt;::getStartIdx</a>, <a href="/web-llvm/docs/api/structs/llvm/concurrenthashtablebyptr/bucket/#a7b75e8b63cf9b1849f0310f3d82acb28">llvm::ConcurrentHashTableByPtr&lt; KeyTy, KeyDataTy, AllocatorTy, Info &gt;::Bucket::Hashes</a>, <a href="#a5452a8e46c9edbecda4976ddac1f0e38">llvm::ConcurrentHashTableByPtr&lt; KeyTy, KeyDataTy, AllocatorTy, Info &gt;::MaxBucketSize</a>, <a href="/web-llvm/docs/api/structs/llvm/concurrenthashtablebyptr/bucket/#ab2b0b6cb8e9ed68ff3a3ab5e5ed90548">llvm::ConcurrentHashTableByPtr&lt; KeyTy, KeyDataTy, AllocatorTy, Info &gt;::Bucket::NumberOfEntries</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a> and <a href="/web-llvm/docs/api/structs/llvm/concurrenthashtablebyptr/bucket/#aa615b1ffd20a1385b4fa159a306d2b5e">llvm::ConcurrentHashTableByPtr&lt; KeyTy, KeyDataTy, AllocatorTy, Info &gt;::Bucket::Size</a>.</p>


<p>Referenced by <a href="#a05f04083a96d1718f46e8f875425e636">llvm::ConcurrentHashTableByPtr&lt; KeyTy, KeyDataTy, AllocatorTy, Info &gt;::insert</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### BucketsArray {#a45da1a667c220a2ac0fedb7909854fdd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyTy, typename KeyDataTy, typename AllocatorTy, typename Info = ConcurrentHashTableInfoByPtr&lt;KeyTy, KeyDataTy, AllocatorTy&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;Bucket[]&gt; llvm::ConcurrentHashTableByPtr&lt; KeyTy, KeyDataTy, AllocatorTy, Info &gt;::BucketsArray</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 393 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/concurrenthashtable-h">ConcurrentHashtable.h</a>.</p>


<p>Referenced by <a href="#aedb1b2d838f24c81b5c649395e24ef08">llvm::ConcurrentHashTableByPtr&lt; KeyTy, KeyDataTy, AllocatorTy, Info &gt;::ConcurrentHashTableByPtr</a>, <a href="#a05f04083a96d1718f46e8f875425e636">llvm::ConcurrentHashTableByPtr&lt; KeyTy, KeyDataTy, AllocatorTy, Info &gt;::insert</a>, <a href="#ac62bbcb37f3fbd47a66763f0125e9829">llvm::ConcurrentHashTableByPtr&lt; KeyTy, KeyDataTy, AllocatorTy, Info &gt;::printStatistic</a> and <a href="#a2b0501783145a93d5caf9d61fac6c645">llvm::ConcurrentHashTableByPtr&lt; KeyTy, KeyDataTy, AllocatorTy, Info &gt;::~ConcurrentHashTableByPtr</a>.</p>

</div>
</div>

### ExtHashMask {#a79fe851e75611aa5b65b7b32a99ffb30}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyTy, typename KeyDataTy, typename AllocatorTy, typename Info = ConcurrentHashTableInfoByPtr&lt;KeyTy, KeyDataTy, AllocatorTy&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::ConcurrentHashTableByPtr&lt; KeyTy, KeyDataTy, AllocatorTy, Info &gt;::ExtHashMask = 0</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 381 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/concurrenthashtable-h">ConcurrentHashtable.h</a>.</p>


<p>Referenced by <a href="#aedb1b2d838f24c81b5c649395e24ef08">llvm::ConcurrentHashTableByPtr&lt; KeyTy, KeyDataTy, AllocatorTy, Info &gt;::ConcurrentHashTableByPtr</a> and <a href="#ae8cffee93b5b0c062e8d97e379bb1ef1">llvm::ConcurrentHashTableByPtr&lt; KeyTy, KeyDataTy, AllocatorTy, Info &gt;::getExtHashBits</a>.</p>

</div>
</div>

### HashBitsNum {#a3062279d7619a6e1e925718e7057ba38}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyTy, typename KeyDataTy, typename AllocatorTy, typename Info = ConcurrentHashTableInfoByPtr&lt;KeyTy, KeyDataTy, AllocatorTy&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::ConcurrentHashTableByPtr&lt; KeyTy, KeyDataTy, AllocatorTy, Info &gt;::HashBitsNum = 0</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 375 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/concurrenthashtable-h">ConcurrentHashtable.h</a>.</p>


<p>Referenced by <a href="#aedb1b2d838f24c81b5c649395e24ef08">llvm::ConcurrentHashTableByPtr&lt; KeyTy, KeyDataTy, AllocatorTy, Info &gt;::ConcurrentHashTableByPtr</a> and <a href="#ae8cffee93b5b0c062e8d97e379bb1ef1">llvm::ConcurrentHashTableByPtr&lt; KeyTy, KeyDataTy, AllocatorTy, Info &gt;::getExtHashBits</a>.</p>

</div>
</div>

### HashMask {#a88cae2ee8b5852e292ba945d9bf202ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyTy, typename KeyDataTy, typename AllocatorTy, typename Info = ConcurrentHashTableInfoByPtr&lt;KeyTy, KeyDataTy, AllocatorTy&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::ConcurrentHashTableByPtr&lt; KeyTy, KeyDataTy, AllocatorTy, Info &gt;::HashMask = 0</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 378 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/concurrenthashtable-h">ConcurrentHashtable.h</a>.</p>


<p>Referenced by <a href="#aedb1b2d838f24c81b5c649395e24ef08">llvm::ConcurrentHashTableByPtr&lt; KeyTy, KeyDataTy, AllocatorTy, Info &gt;::ConcurrentHashTableByPtr</a> and <a href="#a857ab9b7da763acc25c658249b28392b">llvm::ConcurrentHashTableByPtr&lt; KeyTy, KeyDataTy, AllocatorTy, Info &gt;::getBucketIdx</a>.</p>

</div>
</div>

### InitialBucketSize {#adefb4d96f9a87300048d14536cb53d57}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyTy, typename KeyDataTy, typename AllocatorTy, typename Info = ConcurrentHashTableInfoByPtr&lt;KeyTy, KeyDataTy, AllocatorTy&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::ConcurrentHashTableByPtr&lt; KeyTy, KeyDataTy, AllocatorTy, Info &gt;::InitialBucketSize = 0</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 387 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/concurrenthashtable-h">ConcurrentHashtable.h</a>.</p>


<p>Referenced by <a href="#aedb1b2d838f24c81b5c649395e24ef08">llvm::ConcurrentHashTableByPtr&lt; KeyTy, KeyDataTy, AllocatorTy, Info &gt;::ConcurrentHashTableByPtr</a> and <a href="#ac62bbcb37f3fbd47a66763f0125e9829">llvm::ConcurrentHashTableByPtr&lt; KeyTy, KeyDataTy, AllocatorTy, Info &gt;::printStatistic</a>.</p>

</div>
</div>

### MaxBucketSize {#a5452a8e46c9edbecda4976ddac1f0e38}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyTy, typename KeyDataTy, typename AllocatorTy, typename Info = ConcurrentHashTableInfoByPtr&lt;KeyTy, KeyDataTy, AllocatorTy&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::ConcurrentHashTableByPtr&lt; KeyTy, KeyDataTy, AllocatorTy, Info &gt;::MaxBucketSize = 0</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 384 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/concurrenthashtable-h">ConcurrentHashtable.h</a>.</p>


<p>Referenced by <a href="#aedb1b2d838f24c81b5c649395e24ef08">llvm::ConcurrentHashTableByPtr&lt; KeyTy, KeyDataTy, AllocatorTy, Info &gt;::ConcurrentHashTableByPtr</a> and <a href="#ade6907f5a5422e625635b35e22dfe10a">llvm::ConcurrentHashTableByPtr&lt; KeyTy, KeyDataTy, AllocatorTy, Info &gt;::RehashBucket</a>.</p>

</div>
</div>

### MultiThreadAllocator {#af35139c2a8f5bac9ccaa8fbdf71f575b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyTy, typename KeyDataTy, typename AllocatorTy, typename Info = ConcurrentHashTableInfoByPtr&lt;KeyTy, KeyDataTy, AllocatorTy&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AllocatorTy&amp; llvm::ConcurrentHashTableByPtr&lt; KeyTy, KeyDataTy, AllocatorTy, Info &gt;::MultiThreadAllocator</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 396 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/concurrenthashtable-h">ConcurrentHashtable.h</a>.</p>


<p>Referenced by <a href="#aedb1b2d838f24c81b5c649395e24ef08">llvm::ConcurrentHashTableByPtr&lt; KeyTy, KeyDataTy, AllocatorTy, Info &gt;::ConcurrentHashTableByPtr</a> and <a href="#a05f04083a96d1718f46e8f875425e636">llvm::ConcurrentHashTableByPtr&lt; KeyTy, KeyDataTy, AllocatorTy, Info &gt;::insert</a>.</p>

</div>
</div>

### NumberOfBuckets {#aa62532a0a71ab55bbfc89fda24e23ed5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyTy, typename KeyDataTy, typename AllocatorTy, typename Info = ConcurrentHashTableInfoByPtr&lt;KeyTy, KeyDataTy, AllocatorTy&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::ConcurrentHashTableByPtr&lt; KeyTy, KeyDataTy, AllocatorTy, Info &gt;::NumberOfBuckets = 0</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 390 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/concurrenthashtable-h">ConcurrentHashtable.h</a>.</p>


<p>Referenced by <a href="#aedb1b2d838f24c81b5c649395e24ef08">llvm::ConcurrentHashTableByPtr&lt; KeyTy, KeyDataTy, AllocatorTy, Info &gt;::ConcurrentHashTableByPtr</a>, <a href="#ac62bbcb37f3fbd47a66763f0125e9829">llvm::ConcurrentHashTableByPtr&lt; KeyTy, KeyDataTy, AllocatorTy, Info &gt;::printStatistic</a> and <a href="#a2b0501783145a93d5caf9d61fac6c645">llvm::ConcurrentHashTableByPtr&lt; KeyTy, KeyDataTy, AllocatorTy, Info &gt;::~ConcurrentHashTableByPtr</a>.</p>

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

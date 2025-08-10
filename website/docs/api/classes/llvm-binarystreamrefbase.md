---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/binarystreamrefbase
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `BinaryStreamRefBase` Class Template

<p>Common stuff for mutable and immutable StreamRefs. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;class RefType, class StreamType&gt;
class llvm::BinaryStreamRefBase&lt;RefType, StreamType&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystreamref-h">llvm/Support/BinaryStreamRef.h</a>"
</div>

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class RefType, class StreamType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a0da014a7b04a4241267eab0bbe6b5a9e">operator==</a></td>
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

## Protected Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class RefType, class StreamType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a49a0d2084d0b02ccf53238b2683b04b8">BinaryStreamRefBase</a> ()=default</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class RefType, class StreamType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a982d0543f241ebcc64169520da758b26">BinaryStreamRefBase</a> (StreamType &amp;BorrowedImpl)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class RefType, class StreamType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a87016486754929bb9d85bcb0ef89ca60">BinaryStreamRefBase</a> (std::shared_ptr&lt; StreamType &gt; SharedImpl, uint64_t Offset, std::optional&lt; uint64_t &gt; Length)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class RefType, class StreamType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a4b4331727bbaf38cece88f3a87e6b25e">BinaryStreamRefBase</a> (StreamType &amp;BorrowedImpl, uint64_t Offset, std::optional&lt; uint64_t &gt; Length)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class RefType, class StreamType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#af72aaf7d3431e1c2c9f69e2b399335b7">BinaryStreamRefBase</a> (const BinaryStreamRefBase &amp;Other)=default</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class RefType, class StreamType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#af0ee5fac742ca42a54071494fe4c05e2">BinaryStreamRefBase</a> (BinaryStreamRefBase &amp;&amp;Other)=default</td>
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

## Protected Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class RefType, class StreamType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/binarystreamrefbase">BinaryStreamRefBase</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a3e242a71540b157b498828cb9ca2269a">operator=</a> (const BinaryStreamRefBase &amp;Other)=default</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class RefType, class StreamType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/binarystreamrefbase">BinaryStreamRefBase</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a4a829dd0cdd66b4b2edd06ca911b6bf5">operator=</a> (BinaryStreamRefBase &amp;&amp;Other)=default</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class RefType, class StreamType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#ae1e26e57357947b25e392fd18ab000db">llvm::endianness</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aa511da866bcf1a7d67cf081e036caef4">getEndian</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class RefType, class StreamType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af3f28458b55d3c2287703f1d631c8f23">getLength</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class RefType, class StreamType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">RefType</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a4232f2228987b39430e8d7a6b48d8188">drop_front</a> (uint64_t N) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a new <a href="/web-llvm/docs/api/classes/llvm/binarystreamref">BinaryStreamRef</a> with the first <span class="doxyComputerOutput">N</span> elements removed. <a href="#a4232f2228987b39430e8d7a6b48d8188">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class RefType, class StreamType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">RefType</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a25aa9ecfd327d418a3030cc648d751af">drop_back</a> (uint64_t N) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a new <a href="/web-llvm/docs/api/classes/llvm/binarystreamref">BinaryStreamRef</a> with the last <span class="doxyComputerOutput">N</span> elements removed. <a href="#a25aa9ecfd327d418a3030cc648d751af">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class RefType, class StreamType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">RefType</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ae8bb4476ed76bffa9f15addd0f98a34a">keep_front</a> (uint64_t N) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a new <a href="/web-llvm/docs/api/classes/llvm/binarystreamref">BinaryStreamRef</a> with only the first <span class="doxyComputerOutput">N</span> elements remaining. <a href="#ae8bb4476ed76bffa9f15addd0f98a34a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class RefType, class StreamType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">RefType</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aad877535f4e84769dc04ae7115c79bb1">keep_back</a> (uint64_t N) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a new <a href="/web-llvm/docs/api/classes/llvm/binarystreamref">BinaryStreamRef</a> with only the last <span class="doxyComputerOutput">N</span> elements remaining. <a href="#aad877535f4e84769dc04ae7115c79bb1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class RefType, class StreamType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">RefType</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a7f5b31b1a08588e0e76cc35f6eb280cf">drop_symmetric</a> (uint64_t N) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a new <a href="/web-llvm/docs/api/classes/llvm/binarystreamref">BinaryStreamRef</a> with the first and last <span class="doxyComputerOutput">N</span> elements removed. <a href="#a7f5b31b1a08588e0e76cc35f6eb280cf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class RefType, class StreamType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">RefType</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a93dce16d4682b7d529a84007070ffb9e">slice</a> (uint64_t Offset, uint64_t Len) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a new <a href="/web-llvm/docs/api/classes/llvm/binarystreamref">BinaryStreamRef</a> with the first <span class="doxyComputerOutput">Offset</span> elements removed, and retaining exactly <span class="doxyComputerOutput">Len</span> elements. <a href="#a93dce16d4682b7d529a84007070ffb9e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class RefType, class StreamType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#abb948bbc9ce8b17a558d21de2f8bc1eb">valid</a> () const</td>
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

## Protected Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class RefType, class StreamType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a7b0ea3513329432068f5cca7d33e207a">checkOffsetForRead</a> (uint64_t Offset, uint64_t DataSize) const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class RefType, class StreamType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">std::shared_ptr&lt; StreamType &gt;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a4c16e4f4ff110dc670abab045554162e">SharedImpl</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class RefType, class StreamType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">StreamType *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a57d4b980379fd31d3be943f4b66136c1">BorrowedImpl</a> = nullptr</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class RefType, class StreamType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a18d69c1ec33fe3424f1334fbc7eb2553">ViewOffset</a> = 0</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class RefType, class StreamType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">std::optional&lt; uint64_t &gt;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a21140b1c590fc1d8b27660316e725648">Length</a></td>
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

<p>Common stuff for mutable and immutable StreamRefs.</p>

<p>Definition at line 23 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystreamref-h">BinaryStreamRef.h</a>.</p>


<div class="doxySectionDef">

## Friends

### operator== {#a0da014a7b04a4241267eab0bbe6b5a9e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend bool <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> RefType &amp; LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> RefType &amp; RHS</td>
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


<p>Definition at line 121 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystreamref-h">BinaryStreamRef.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Constructors

### BinaryStreamRefBase() {#a49a0d2084d0b02ccf53238b2683b04b8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class RefType, class StreamType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::BinaryStreamRefBase&lt; RefType, StreamType &gt;::BinaryStreamRefBase ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 25 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystreamref-h">BinaryStreamRef.h</a>.</p>


<p>Referenced by <a href="#af0ee5fac742ca42a54071494fe4c05e2">llvm::BinaryStreamRefBase&lt; RefType, StreamType &gt;::BinaryStreamRefBase</a>, <a href="#af72aaf7d3431e1c2c9f69e2b399335b7">llvm::BinaryStreamRefBase&lt; RefType, StreamType &gt;::BinaryStreamRefBase</a>, <a href="#a4a829dd0cdd66b4b2edd06ca911b6bf5">llvm::BinaryStreamRefBase&lt; RefType, StreamType &gt;::operator=</a> and <a href="#a3e242a71540b157b498828cb9ca2269a">llvm::BinaryStreamRefBase&lt; RefType, StreamType &gt;::operator=</a>.</p>

</div>
</div>

### BinaryStreamRefBase() {#a982d0543f241ebcc64169520da758b26}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class RefType, class StreamType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::BinaryStreamRefBase&lt; RefType, StreamType &gt;::BinaryStreamRefBase (StreamType &amp; BorrowedImpl)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel explicit">explicit</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 26 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystreamref-h">BinaryStreamRef.h</a>.</p>


<p>References <a href="#a57d4b980379fd31d3be943f4b66136c1">llvm::BinaryStreamRefBase&lt; RefType, StreamType &gt;::BorrowedImpl</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2ef78585311fc208693b30e27c7f8af1a63b9fe189175224612d598cd657eba21">llvm::BSF_Append</a>, <a href="#a21140b1c590fc1d8b27660316e725648">llvm::BinaryStreamRefBase&lt; RefType, StreamType &gt;::Length</a> and <a href="#a18d69c1ec33fe3424f1334fbc7eb2553">llvm::BinaryStreamRefBase&lt; RefType, StreamType &gt;::ViewOffset</a>.</p>

</div>
</div>

### BinaryStreamRefBase() {#a87016486754929bb9d85bcb0ef89ca60}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class RefType, class StreamType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::BinaryStreamRefBase&lt; RefType, StreamType &gt;::BinaryStreamRefBase (std::shared_ptr&lt; StreamType &gt; SharedImpl, uint64_t Offset, std::optional&lt; uint64_t &gt; Length)</td>
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



<p>Definition at line 32 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystreamref-h">BinaryStreamRef.h</a>.</p>


<p>References <a href="#a57d4b980379fd31d3be943f4b66136c1">llvm::BinaryStreamRefBase&lt; RefType, StreamType &gt;::BorrowedImpl</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a73257f51950d9ea50955e3fb9c724a25">llvm::get</a>, <a href="#a21140b1c590fc1d8b27660316e725648">llvm::BinaryStreamRefBase&lt; RefType, StreamType &gt;::Length</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="#a4c16e4f4ff110dc670abab045554162e">llvm::BinaryStreamRefBase&lt; RefType, StreamType &gt;::SharedImpl</a> and <a href="#a18d69c1ec33fe3424f1334fbc7eb2553">llvm::BinaryStreamRefBase&lt; RefType, StreamType &gt;::ViewOffset</a>.</p>

</div>
</div>

### BinaryStreamRefBase() {#a4b4331727bbaf38cece88f3a87e6b25e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class RefType, class StreamType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::BinaryStreamRefBase&lt; RefType, StreamType &gt;::BinaryStreamRefBase (StreamType &amp; BorrowedImpl, uint64_t Offset, std::optional&lt; uint64_t &gt; Length)</td>
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



<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystreamref-h">BinaryStreamRef.h</a>.</p>


<p>References <a href="#a57d4b980379fd31d3be943f4b66136c1">llvm::BinaryStreamRefBase&lt; RefType, StreamType &gt;::BorrowedImpl</a>, <a href="#a21140b1c590fc1d8b27660316e725648">llvm::BinaryStreamRefBase&lt; RefType, StreamType &gt;::Length</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a> and <a href="#a18d69c1ec33fe3424f1334fbc7eb2553">llvm::BinaryStreamRefBase&lt; RefType, StreamType &gt;::ViewOffset</a>.</p>

</div>
</div>

### BinaryStreamRefBase() {#af72aaf7d3431e1c2c9f69e2b399335b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class RefType, class StreamType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::BinaryStreamRefBase&lt; RefType, StreamType &gt;::BinaryStreamRefBase (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/binarystreamrefbase">BinaryStreamRefBase</a> &amp; Other)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 39 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystreamref-h">BinaryStreamRef.h</a>.</p>


<p>References <a href="#a49a0d2084d0b02ccf53238b2683b04b8">llvm::BinaryStreamRefBase&lt; RefType, StreamType &gt;::BinaryStreamRefBase</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>.</p>

</div>
</div>

### BinaryStreamRefBase() {#af0ee5fac742ca42a54071494fe4c05e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class RefType, class StreamType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::BinaryStreamRefBase&lt; RefType, StreamType &gt;::BinaryStreamRefBase (<a href="/web-llvm/docs/api/classes/llvm/binarystreamrefbase">BinaryStreamRefBase</a> &amp;&amp; Other)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystreamref-h">BinaryStreamRef.h</a>.</p>


<p>References <a href="#a49a0d2084d0b02ccf53238b2683b04b8">llvm::BinaryStreamRefBase&lt; RefType, StreamType &gt;::BinaryStreamRefBase</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Operators

### operator=() {#a3e242a71540b157b498828cb9ca2269a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class RefType, class StreamType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BinaryStreamRefBase &amp; llvm::BinaryStreamRefBase&lt; RefType, StreamType &gt;::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/binarystreamrefbase">BinaryStreamRefBase</a> &amp; Other)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 40 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystreamref-h">BinaryStreamRef.h</a>.</p>


<p>References <a href="#a49a0d2084d0b02ccf53238b2683b04b8">llvm::BinaryStreamRefBase&lt; RefType, StreamType &gt;::BinaryStreamRefBase</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>.</p>

</div>
</div>

### operator=() {#a4a829dd0cdd66b4b2edd06ca911b6bf5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class RefType, class StreamType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BinaryStreamRefBase &amp; llvm::BinaryStreamRefBase&lt; RefType, StreamType &gt;::operator= (<a href="/web-llvm/docs/api/classes/llvm/binarystreamrefbase">BinaryStreamRefBase</a> &amp;&amp; Other)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystreamref-h">BinaryStreamRef.h</a>.</p>


<p>References <a href="#a49a0d2084d0b02ccf53238b2683b04b8">llvm::BinaryStreamRefBase&lt; RefType, StreamType &gt;::BinaryStreamRefBase</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### drop\_back() {#a25aa9ecfd327d418a3030cc648d751af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class RefType, class StreamType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RefType llvm::BinaryStreamRefBase&lt; RefType, StreamType &gt;::drop_back (uint64_t N)</td>
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

<p>Return a new <a href="/web-llvm/docs/api/classes/llvm/binarystreamref">BinaryStreamRef</a> with the last <span class="doxyComputerOutput">N</span> elements removed.</p>


<p>If this <a href="/web-llvm/docs/api/classes/llvm/binarystreamref">BinaryStreamRef</a> is length-tracking and <span class="doxyComputerOutput">N</span> is greater than 0, then this <a href="/web-llvm/docs/api/classes/llvm/binarystreamref">BinaryStreamRef</a> will no longer length-track.</p>


<p>Definition at line 76 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystreamref-h">BinaryStreamRef.h</a>.</p>


<p>References <a href="#a57d4b980379fd31d3be943f4b66136c1">llvm::BinaryStreamRefBase&lt; RefType, StreamType &gt;::BorrowedImpl</a>, <a href="#af3f28458b55d3c2287703f1d631c8f23">llvm::BinaryStreamRefBase&lt; RefType, StreamType &gt;::getLength</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>


<p>Referenced by <a href="#ae8bb4476ed76bffa9f15addd0f98a34a">llvm::BinaryStreamRefBase&lt; RefType, StreamType &gt;::keep_front</a>.</p>

</div>
</div>

### drop\_front() {#a4232f2228987b39430e8d7a6b48d8188}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class RefType, class StreamType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RefType llvm::BinaryStreamRefBase&lt; RefType, StreamType &gt;::drop_front (uint64_t N)</td>
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

<p>Return a new <a href="/web-llvm/docs/api/classes/llvm/binarystreamref">BinaryStreamRef</a> with the first <span class="doxyComputerOutput">N</span> elements removed.</p>


<p>If this <a href="/web-llvm/docs/api/classes/llvm/binarystreamref">BinaryStreamRef</a> is length-tracking, then the resulting one will be too.</p>


<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystreamref-h">BinaryStreamRef.h</a>.</p>


<p>References <a href="#a57d4b980379fd31d3be943f4b66136c1">llvm::BinaryStreamRefBase&lt; RefType, StreamType &gt;::BorrowedImpl</a>, <a href="#af3f28458b55d3c2287703f1d631c8f23">llvm::BinaryStreamRefBase&lt; RefType, StreamType &gt;::getLength</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>


<p>Referenced by <a href="#a7f5b31b1a08588e0e76cc35f6eb280cf">llvm::BinaryStreamRefBase&lt; RefType, StreamType &gt;::drop_symmetric</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/lineprinter/#a6060a150c1da2417e904c7ce98eb1297">llvm::pdb::LinePrinter::formatMsfStreamData</a>, <a href="#aad877535f4e84769dc04ae7115c79bb1">llvm::BinaryStreamRefBase&lt; RefType, StreamType &gt;::keep_back</a> and <a href="#a93dce16d4682b7d529a84007070ffb9e">llvm::BinaryStreamRefBase&lt; RefType, StreamType &gt;::slice</a>.</p>

</div>
</div>

### drop\_symmetric() {#a7f5b31b1a08588e0e76cc35f6eb280cf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class RefType, class StreamType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RefType llvm::BinaryStreamRefBase&lt; RefType, StreamType &gt;::drop_symmetric (uint64_t N)</td>
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

<p>Return a new <a href="/web-llvm/docs/api/classes/llvm/binarystreamref">BinaryStreamRef</a> with the first and last <span class="doxyComputerOutput">N</span> elements removed.</p>

<p>Definition at line 109 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystreamref-h">BinaryStreamRef.h</a>.</p>


<p>References <a href="#a4232f2228987b39430e8d7a6b48d8188">llvm::BinaryStreamRefBase&lt; RefType, StreamType &gt;::drop_front</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### getEndian() {#aa511da866bcf1a7d67cf081e036caef4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class RefType, class StreamType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::endianness llvm::BinaryStreamRefBase&lt; RefType, StreamType &gt;::getEndian ()</td>
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



<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystreamref-h">BinaryStreamRef.h</a>.</p>


<p>Reference <a href="#a57d4b980379fd31d3be943f4b66136c1">llvm::BinaryStreamRefBase&lt; RefType, StreamType &gt;::BorrowedImpl</a>.</p>

</div>
</div>

### getLength() {#af3f28458b55d3c2287703f1d631c8f23}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class RefType, class StreamType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::BinaryStreamRefBase&lt; RefType, StreamType &gt;::getLength ()</td>
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



<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystreamref-h">BinaryStreamRef.h</a>.</p>


<p>References <a href="#a57d4b980379fd31d3be943f4b66136c1">llvm::BinaryStreamRefBase&lt; RefType, StreamType &gt;::BorrowedImpl</a>, <a href="#a21140b1c590fc1d8b27660316e725648">llvm::BinaryStreamRefBase&lt; RefType, StreamType &gt;::Length</a> and <a href="#a18d69c1ec33fe3424f1334fbc7eb2553">llvm::BinaryStreamRefBase&lt; RefType, StreamType &gt;::ViewOffset</a>.</p>


<p>Referenced by <a href="#a7b0ea3513329432068f5cca7d33e207a">llvm::BinaryStreamRefBase&lt; RefType, StreamType &gt;::checkOffsetForRead</a>, <a href="#a25aa9ecfd327d418a3030cc648d751af">llvm::BinaryStreamRefBase&lt; RefType, StreamType &gt;::drop_back</a>, <a href="#a4232f2228987b39430e8d7a6b48d8188">llvm::BinaryStreamRefBase&lt; RefType, StreamType &gt;::drop_front</a>, <a href="#aad877535f4e84769dc04ae7115c79bb1">llvm::BinaryStreamRefBase&lt; RefType, StreamType &gt;::keep_back</a> and <a href="#ae8bb4476ed76bffa9f15addd0f98a34a">llvm::BinaryStreamRefBase&lt; RefType, StreamType &gt;::keep_front</a>.</p>

</div>
</div>

### keep\_back() {#aad877535f4e84769dc04ae7115c79bb1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class RefType, class StreamType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RefType llvm::BinaryStreamRefBase&lt; RefType, StreamType &gt;::keep_back (uint64_t N)</td>
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

<p>Return a new <a href="/web-llvm/docs/api/classes/llvm/binarystreamref">BinaryStreamRef</a> with only the last <span class="doxyComputerOutput">N</span> elements remaining.</p>

<p>Definition at line 102 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystreamref-h">BinaryStreamRef.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a4232f2228987b39430e8d7a6b48d8188">llvm::BinaryStreamRefBase&lt; RefType, StreamType &gt;::drop_front</a>, <a href="#af3f28458b55d3c2287703f1d631c8f23">llvm::BinaryStreamRefBase&lt; RefType, StreamType &gt;::getLength</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### keep\_front() {#ae8bb4476ed76bffa9f15addd0f98a34a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class RefType, class StreamType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RefType llvm::BinaryStreamRefBase&lt; RefType, StreamType &gt;::keep_front (uint64_t N)</td>
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

<p>Return a new <a href="/web-llvm/docs/api/classes/llvm/binarystreamref">BinaryStreamRef</a> with only the first <span class="doxyComputerOutput">N</span> elements remaining.</p>

<p>Definition at line 96 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystreamref-h">BinaryStreamRef.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a25aa9ecfd327d418a3030cc648d751af">llvm::BinaryStreamRefBase&lt; RefType, StreamType &gt;::drop_back</a>, <a href="#af3f28458b55d3c2287703f1d631c8f23">llvm::BinaryStreamRefBase&lt; RefType, StreamType &gt;::getLength</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/pdb/lineprinter/#a6060a150c1da2417e904c7ce98eb1297">llvm::pdb::LinePrinter::formatMsfStreamData</a>.</p>

</div>
</div>

### slice() {#a93dce16d4682b7d529a84007070ffb9e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class RefType, class StreamType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RefType llvm::BinaryStreamRefBase&lt; RefType, StreamType &gt;::slice (uint64_t Offset, uint64_t Len)</td>
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

<p>Return a new <a href="/web-llvm/docs/api/classes/llvm/binarystreamref">BinaryStreamRef</a> with the first <span class="doxyComputerOutput">Offset</span> elements removed, and retaining exactly <span class="doxyComputerOutput">Len</span> elements.</p>

<p>Definition at line 115 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystreamref-h">BinaryStreamRef.h</a>.</p>


<p>References <a href="#a4232f2228987b39430e8d7a6b48d8188">llvm::BinaryStreamRefBase&lt; RefType, StreamType &gt;::drop_front</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/varstreamarray/#ae8d8d4bcd0f2fc0edeebf50bb469a6b0">llvm::VarStreamArray&lt; CVSymbol &gt;::substream</a>.</p>

</div>
</div>

### valid() {#abb948bbc9ce8b17a558d21de2f8bc1eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class RefType, class StreamType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::BinaryStreamRefBase&lt; RefType, StreamType &gt;::valid ()</td>
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



<p>Definition at line 119 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystreamref-h">BinaryStreamRef.h</a>.</p>


<p>Reference <a href="#a57d4b980379fd31d3be943f4b66136c1">llvm::BinaryStreamRefBase&lt; RefType, StreamType &gt;::BorrowedImpl</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### checkOffsetForRead() {#a7b0ea3513329432068f5cca7d33e207a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class RefType, class StreamType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::BinaryStreamRefBase&lt; RefType, StreamType &gt;::checkOffsetForRead (uint64_t Offset, uint64_t DataSize)</td>
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



<p>Definition at line 132 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystreamref-h">BinaryStreamRef.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a3b9d675b34f20ba67f1f3213e63935d6">llvm::DataSize</a>, <a href="#af3f28458b55d3c2287703f1d631c8f23">llvm::BinaryStreamRefBase&lt; RefType, StreamType &gt;::getLength</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ace5dca6857eec227e4eddc4ce820b89daf6579f9fbeb5034d9165fe820866b23b">llvm::invalid_offset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ace5dca6857eec227e4eddc4ce820b89dad88b43968f2dd7eb3d9d40060fbacc98">llvm::stream_too_short</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### BorrowedImpl {#a57d4b980379fd31d3be943f4b66136c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class RefType, class StreamType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StreamType* llvm::BinaryStreamRefBase&lt; RefType, StreamType &gt;::BorrowedImpl = nullptr</td>
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



<p>Definition at line 141 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystreamref-h">BinaryStreamRef.h</a>.</p>


<p>Referenced by <a href="#a87016486754929bb9d85bcb0ef89ca60">llvm::BinaryStreamRefBase&lt; RefType, StreamType &gt;::BinaryStreamRefBase</a>, <a href="#a982d0543f241ebcc64169520da758b26">llvm::BinaryStreamRefBase&lt; RefType, StreamType &gt;::BinaryStreamRefBase</a>, <a href="#a4b4331727bbaf38cece88f3a87e6b25e">llvm::BinaryStreamRefBase&lt; RefType, StreamType &gt;::BinaryStreamRefBase</a>, <a href="#a25aa9ecfd327d418a3030cc648d751af">llvm::BinaryStreamRefBase&lt; RefType, StreamType &gt;::drop_back</a>, <a href="#a4232f2228987b39430e8d7a6b48d8188">llvm::BinaryStreamRefBase&lt; RefType, StreamType &gt;::drop_front</a>, <a href="#aa511da866bcf1a7d67cf081e036caef4">llvm::BinaryStreamRefBase&lt; RefType, StreamType &gt;::getEndian</a>, <a href="#af3f28458b55d3c2287703f1d631c8f23">llvm::BinaryStreamRefBase&lt; RefType, StreamType &gt;::getLength</a> and <a href="#abb948bbc9ce8b17a558d21de2f8bc1eb">llvm::BinaryStreamRefBase&lt; RefType, StreamType &gt;::valid</a>.</p>

</div>
</div>

### Length {#a21140b1c590fc1d8b27660316e725648}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class RefType, class StreamType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;uint64_t&gt; llvm::BinaryStreamRefBase&lt; RefType, StreamType &gt;::Length</td>
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



<p>Definition at line 143 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystreamref-h">BinaryStreamRef.h</a>.</p>


<p>Referenced by <a href="#a87016486754929bb9d85bcb0ef89ca60">llvm::BinaryStreamRefBase&lt; RefType, StreamType &gt;::BinaryStreamRefBase</a>, <a href="#a982d0543f241ebcc64169520da758b26">llvm::BinaryStreamRefBase&lt; RefType, StreamType &gt;::BinaryStreamRefBase</a>, <a href="#a4b4331727bbaf38cece88f3a87e6b25e">llvm::BinaryStreamRefBase&lt; RefType, StreamType &gt;::BinaryStreamRefBase</a> and <a href="#af3f28458b55d3c2287703f1d631c8f23">llvm::BinaryStreamRefBase&lt; RefType, StreamType &gt;::getLength</a>.</p>

</div>
</div>

### SharedImpl {#a4c16e4f4ff110dc670abab045554162e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class RefType, class StreamType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::shared_ptr&lt;StreamType&gt; llvm::BinaryStreamRefBase&lt; RefType, StreamType &gt;::SharedImpl</td>
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



<p>Definition at line 140 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystreamref-h">BinaryStreamRef.h</a>.</p>


<p>Referenced by <a href="#a87016486754929bb9d85bcb0ef89ca60">llvm::BinaryStreamRefBase&lt; RefType, StreamType &gt;::BinaryStreamRefBase</a>.</p>

</div>
</div>

### ViewOffset {#a18d69c1ec33fe3424f1334fbc7eb2553}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class RefType, class StreamType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::BinaryStreamRefBase&lt; RefType, StreamType &gt;::ViewOffset = 0</td>
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



<p>Definition at line 142 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystreamref-h">BinaryStreamRef.h</a>.</p>


<p>Referenced by <a href="#a87016486754929bb9d85bcb0ef89ca60">llvm::BinaryStreamRefBase&lt; RefType, StreamType &gt;::BinaryStreamRefBase</a>, <a href="#a982d0543f241ebcc64169520da758b26">llvm::BinaryStreamRefBase&lt; RefType, StreamType &gt;::BinaryStreamRefBase</a>, <a href="#a4b4331727bbaf38cece88f3a87e6b25e">llvm::BinaryStreamRefBase&lt; RefType, StreamType &gt;::BinaryStreamRefBase</a> and <a href="#af3f28458b55d3c2287703f1d631c8f23">llvm::BinaryStreamRefBase&lt; RefType, StreamType &gt;::getLength</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystreamref-h">BinaryStreamRef.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>

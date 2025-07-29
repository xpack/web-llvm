---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/mcencodedfragmentwithfixups
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `MCEncodedFragmentWithFixups` Class Template

<p>Interface implemented by fragments that contain encoded instructions and/or data and also have fixups registered. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;unsigned ContentsSize, unsigned FixupsSize&gt;
class llvm::MCEncodedFragmentWithFixups&lt;ContentsSize, FixupsSize&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcfragment-h">llvm/MC/MCFragment.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcencodedfragment">MCEncodedFragment</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Interface implemented by fragments that contain encoded instructions and/or data. <a href="/web-llvm/docs/api/classes/llvm/mcencodedfragment/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;unsigned ContentsSize, unsigned FixupsSize&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a7054d0d6cace5c185998fbcdcd5c2f0a">MCEncodedFragmentWithFixups</a> (MCFragment::FragmentType FType, bool HasInstructions)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;unsigned ContentsSize, unsigned FixupsSize&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#adeb8e72f8eb5703650627d39457436dd">getContents</a> () -&gt; <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; char &gt; &amp;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;unsigned ContentsSize, unsigned FixupsSize&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a90756318624221cd39bcd435d4810444">getContents</a> () const -&gt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; char &gt; &amp;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;unsigned ContentsSize, unsigned FixupsSize&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aad8972d8a7e105c703cb7e5d51b24e7b">appendContents</a> (ArrayRef&lt; char &gt; C)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;unsigned ContentsSize, unsigned FixupsSize&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad9c27f7d18aba73de2dd69dc7a5e25d4">appendContents</a> (size_t Num, char Elt)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;unsigned ContentsSize, unsigned FixupsSize&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a1574158cb7099ca0885c17e2a4c2d210">setContents</a> (ArrayRef&lt; char &gt; C)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;unsigned ContentsSize, unsigned FixupsSize&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a8a0daac469ed602d68174c8efae89b22">getFixups</a> () -&gt; <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/mcfixup">MCFixup</a> &gt; &amp;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;unsigned ContentsSize, unsigned FixupsSize&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a6fbe4f55d218a0809f50c7bf5fe693d6">getFixups</a> () const -&gt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/mcfixup">MCFixup</a> &gt; &amp;</td>
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

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;unsigned ContentsSize, unsigned FixupsSize&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; char, ContentsSize &gt;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a25ed218625cf71728d4a4bc8bab54ef0">Contents</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;unsigned ContentsSize, unsigned FixupsSize&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/mcfixup">MCFixup</a>, FixupsSize &gt;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aa25db5d7a6308f3566242dbceaef9931">Fixups</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The list of fixups in this fragment. <a href="#aa25db5d7a6308f3566242dbceaef9931">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;unsigned ContentsSize, unsigned FixupsSize&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a14fcbe38a8ba1c45c25cc82a6b8497e9">classof</a> (const MCFragment *F)</td>
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

<p>Interface implemented by fragments that contain encoded instructions and/or data and also have fixups registered.</p>

<p>Definition at line 181 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcfragment-h">MCFragment.h</a>.</p>


<div class="doxySectionDef">

## Protected Constructors

### MCEncodedFragmentWithFixups() {#a7054d0d6cace5c185998fbcdcd5c2f0a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;unsigned ContentsSize, unsigned FixupsSize&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MCEncodedFragmentWithFixups&lt; ContentsSize, FixupsSize &gt;::MCEncodedFragmentWithFixups (<a href="/web-llvm/docs/api/classes/llvm/mcfragment/#aebf48160a3995325c6d2465080bcab68">MCFragment::FragmentType</a> FType, bool HasInstructions)</td>
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



<p>Definition at line 188 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcfragment-h">MCFragment.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcfragment/#a47324e10b138f859b0fee6acf80bd979">llvm::MCFragment::HasInstructions</a> and <a href="/web-llvm/docs/api/classes/llvm/mcencodedfragment/#a17077f9e77e49104a7a6c08cc1a96cff">llvm::MCEncodedFragment::MCEncodedFragment</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### appendContents() {#aad8972d8a7e105c703cb7e5d51b24e7b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;unsigned ContentsSize, unsigned FixupsSize&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MCEncodedFragmentWithFixups&lt; ContentsSize, FixupsSize &gt;::appendContents (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; char &gt; C)</td>
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



<p>Definition at line 196 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcfragment-h">MCFragment.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>.</p>

</div>
</div>

### appendContents() {#ad9c27f7d18aba73de2dd69dc7a5e25d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;unsigned ContentsSize, unsigned FixupsSize&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MCEncodedFragmentWithFixups&lt; ContentsSize, FixupsSize &gt;::appendContents (size_t Num, char Elt)</td>
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



<p>Definition at line 197 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcfragment-h">MCFragment.h</a>.</p>

</div>
</div>

### getContents() {#adeb8e72f8eb5703650627d39457436dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;unsigned ContentsSize, unsigned FixupsSize&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVectorImpl&lt; char &gt; &amp; llvm::MCEncodedFragmentWithFixups&lt; ContentsSize, FixupsSize &gt;::getContents ()</td>
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



<p>Definition at line 193 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcfragment-h">MCFragment.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/codeviewcontext/#aea53ea050c3442abffd1c991f4c7213a">llvm::CodeViewContext::encodeDefRange</a>, <a href="/web-llvm/docs/api/classes/llvm/mcassembler/#a4172c40c16e915c478ab94311e76e1a8">llvm::MCAssembler::layout</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86asmbackend-cpp-/x86asmbackend/#aec5e1563ca339dbf7905cf069c364e39">anonymous{X86AsmBackend.cpp}::X86AsmBackend::padInstructionViaPrefix</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86asmbackend-cpp-/x86asmbackend/#a112639954fd036a8748791f74d0db6fb">anonymous{X86AsmBackend.cpp}::X86AsmBackend::padInstructionViaRelaxation</a> and <a href="/web-llvm/docs/api/files/lib/lib/mc/mcassembler-cpp/#a6ae6757140194100cc316df00b97773f">writeFragment</a>.</p>

</div>
</div>

### getContents() {#a90756318624221cd39bcd435d4810444}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;unsigned ContentsSize, unsigned FixupsSize&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SmallVectorImpl&lt; char &gt; &amp; llvm::MCEncodedFragmentWithFixups&lt; ContentsSize, FixupsSize &gt;::getContents ()</td>
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



<p>Definition at line 194 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcfragment-h">MCFragment.h</a>.</p>

</div>
</div>

### getFixups() {#a8a0daac469ed602d68174c8efae89b22}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;unsigned ContentsSize, unsigned FixupsSize&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVectorImpl&lt; MCFixup &gt; &amp; llvm::MCEncodedFragmentWithFixups&lt; ContentsSize, FixupsSize &gt;::getFixups ()</td>
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



<p>Definition at line 200 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcfragment-h">MCFragment.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/codeviewcontext/#aea53ea050c3442abffd1c991f4c7213a">llvm::CodeViewContext::encodeDefRange</a>, <a href="/web-llvm/docs/api/classes/llvm/mcassembler/#a4172c40c16e915c478ab94311e76e1a8">llvm::MCAssembler::layout</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86asmbackend-cpp-/x86asmbackend/#aec5e1563ca339dbf7905cf069c364e39">anonymous{X86AsmBackend.cpp}::X86AsmBackend::padInstructionViaPrefix</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86asmbackend-cpp-/x86asmbackend/#a112639954fd036a8748791f74d0db6fb">anonymous{X86AsmBackend.cpp}::X86AsmBackend::padInstructionViaRelaxation</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchasmbackend/#a6ffd2d1f64a9104fc1a62c1387fca16e">llvm::LoongArchAsmBackend::relaxLEB128</a> and <a href="/web-llvm/docs/api/classes/llvm/riscvasmbackend/#a0b10511c4a52fc282850610c648ba455">llvm::RISCVAsmBackend::relaxLEB128</a>.</p>

</div>
</div>

### getFixups() {#a6fbe4f55d218a0809f50c7bf5fe693d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;unsigned ContentsSize, unsigned FixupsSize&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SmallVectorImpl&lt; MCFixup &gt; &amp; llvm::MCEncodedFragmentWithFixups&lt; ContentsSize, FixupsSize &gt;::getFixups ()</td>
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



<p>Definition at line 201 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcfragment-h">MCFragment.h</a>.</p>

</div>
</div>

### setContents() {#a1574158cb7099ca0885c17e2a4c2d210}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;unsigned ContentsSize, unsigned FixupsSize&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MCEncodedFragmentWithFixups&lt; ContentsSize, FixupsSize &gt;::setContents (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; char &gt; C)</td>
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



<p>Definition at line 198 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcfragment-h">MCFragment.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-x86asmbackend-cpp-/x86asmbackend/#aec5e1563ca339dbf7905cf069c364e39">anonymous{X86AsmBackend.cpp}::X86AsmBackend::padInstructionViaPrefix</a> and <a href="/web-llvm/docs/api/classes/anonymous-x86asmbackend-cpp-/x86asmbackend/#a112639954fd036a8748791f74d0db6fb">anonymous{X86AsmBackend.cpp}::X86AsmBackend::padInstructionViaRelaxation</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Contents {#a25ed218625cf71728d4a4bc8bab54ef0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;unsigned ContentsSize, unsigned FixupsSize&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;char, ContentsSize&gt; llvm::MCEncodedFragmentWithFixups&lt; ContentsSize, FixupsSize &gt;::Contents</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 182 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcfragment-h">MCFragment.h</a>.</p>

</div>
</div>

### Fixups {#aa25db5d7a6308f3566242dbceaef9931}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;unsigned ContentsSize, unsigned FixupsSize&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;MCFixup, FixupsSize&gt; llvm::MCEncodedFragmentWithFixups&lt; ContentsSize, FixupsSize &gt;::Fixups</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The list of fixups in this fragment.</p>

<p>Definition at line 185 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcfragment-h">MCFragment.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### classof() {#a14fcbe38a8ba1c45c25cc82a6b8497e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;unsigned ContentsSize, unsigned FixupsSize&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCEncodedFragmentWithFixups&lt; ContentsSize, FixupsSize &gt;::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcfragment">MCFragment</a> * F)</td>
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



<p>Definition at line 203 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcfragment-h">MCFragment.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/mcfragment/#aebf48160a3995325c6d2465080bcab68a99243fc57a7beebaba062a013912846f">llvm::MCFragment::FT_CVDefRange</a>, <a href="/web-llvm/docs/api/classes/llvm/mcfragment/#aebf48160a3995325c6d2465080bcab68a31f0e4803273f2184e596c87e1e05f80">llvm::MCFragment::FT_Data</a>, <a href="/web-llvm/docs/api/classes/llvm/mcfragment/#aebf48160a3995325c6d2465080bcab68a01473d8036e353978ae750c8dace1a10">llvm::MCFragment::FT_Dwarf</a>, <a href="/web-llvm/docs/api/classes/llvm/mcfragment/#aebf48160a3995325c6d2465080bcab68a2f12197bbe6c6a91731b3828d033a212">llvm::MCFragment::FT_DwarfFrame</a> and <a href="/web-llvm/docs/api/classes/llvm/mcfragment/#aebf48160a3995325c6d2465080bcab68abe5194c45ead6aefe6b0882dcb6f2104">llvm::MCFragment::FT_Relaxable</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcfragment-h">MCFragment.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>

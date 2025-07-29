---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-avrshiftexpand-cpp-/avrshiftexpand
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `AVRShiftExpand` Class



## Declaration

<div class="doxyDeclaration">
class anonymous{AVRShiftExpand.cpp}::AVRShiftExpand { ... }
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/functionpass">FunctionPass</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/functionpass">FunctionPass</a> class - This class is used to implement most global optimizations. <a href="/web-llvm/docs/api/classes/llvm/functionpass/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade77a8b46e142e40fa32217135924bc1">AVRShiftExpand</a> ()</td>
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

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a25192a5e79d3f5ef39a4b3d4a7da9fd9">runOnFunction</a> (Function &amp;F) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>runOnFunction - Virtual method overriden by subclasses to do the per-function processing of the pass. <a href="#a25192a5e79d3f5ef39a4b3d4a7da9fd9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a09693f5eb1959958f3ed3c6dce786dbb">getPassName</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getPassName - Return a nice clean name for a pass. <a href="#a09693f5eb1959958f3ed3c6dce786dbb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e7e5bb8e7c1f7fea0902f1501acb6c1">expand</a> (BinaryOperator *BI)</td>
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

## Public Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade0d9abd7509246794db8dda58347e51">ID</a> = 0</td>
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


<p>Definition at line 25 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/avrshiftexpand-cpp">AVRShiftExpand.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### AVRShiftExpand() {#ade77a8b46e142e40fa32217135924bc1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{AVRShiftExpand.cpp}::AVRShiftExpand::AVRShiftExpand ()</td>
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



<p>Definition at line 29 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/avrshiftexpand-cpp">AVRShiftExpand.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/functionpass/#a7691d83e3561f781cae4ce4a01bdfa93">llvm::FunctionPass::FunctionPass</a> and <a href="#ade0d9abd7509246794db8dda58347e51">ID</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/avrshiftexpand-cpp/#a019fa63f5f129090768a5f61c378b542">INITIALIZE_PASS</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getPassName() {#a09693f5eb1959958f3ed3c6dce786dbb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef anonymous{AVRShiftExpand.cpp}::AVRShiftExpand::getPassName ()</td>
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

<p>getPassName - Return a nice clean name for a pass.</p>


<p>This usually implemented in terms of the name that is registered by one of the Registration templates, but can be overloaded directly.</p>


<p>Definition at line 33 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/avrshiftexpand-cpp">AVRShiftExpand.cpp</a>.</p>

</div>
</div>

### runOnFunction() {#a25192a5e79d3f5ef39a4b3d4a7da9fd9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AVRShiftExpand::runOnFunction (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>runOnFunction - Virtual method overriden by subclasses to do the per-function processing of the pass.</p>

<p>Definition at line 31 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/avrshiftexpand-cpp">AVRShiftExpand.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a87f56db834c58ca630624956ecf6972f">llvm::Type::getInt16Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a7ba5de75f50bb4a4ba920698edf39b28">llvm::Type::getInt8Ty</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/atomicexpandpass-cpp/#a1bcc06b1cb86bd0ea08f33323190bdaa">instructions</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### expand() {#a6e7e5bb8e7c1f7fea0902f1501acb6c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AVRShiftExpand::expand (<a href="/web-llvm/docs/api/classes/llvm/binaryoperator">BinaryOperator</a> * BI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/avrshiftexpand-cpp">AVRShiftExpand.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Attributes

### ID {#ade0d9abd7509246794db8dda58347e51}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">char AVRShiftExpand::ID = 0</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 27 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/avrshiftexpand-cpp">AVRShiftExpand.cpp</a>.</p>


<p>Referenced by <a href="#ade77a8b46e142e40fa32217135924bc1">AVRShiftExpand</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/avrshiftexpand-cpp">AVRShiftExpand.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>

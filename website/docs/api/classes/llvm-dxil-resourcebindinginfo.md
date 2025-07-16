---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/dxil/resourcebindinginfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `ResourceBindingInfo` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::dxil::ResourceBindingInfo { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dxilresource-h">llvm/Analysis/DXILResource.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a52c967a651ac05246a6c48ea46de5101">ResourceBindingInfo</a> (uint32_t RecordID, uint32_t Space, uint32_t LowerBound, uint32_t Size, TargetExtType *HandleTy, GlobalVariable *Symbol=nullptr)</td>
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

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a096ec18ed5481343090f565df763b2cd">operator==</a> (const ResourceBindingInfo &amp;RHS) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa3970f4c7053e9dc979d5f4e6c814ced">operator!=</a> (const ResourceBindingInfo &amp;RHS) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a27d1b6a7a0e6696fbe309a3a4979f335">operator&lt;</a> (const ResourceBindingInfo &amp;RHS) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a24fd03b52807a4987805a18f1a54b538">setBindingID</a> (unsigned ID)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/dxil/resourcebindinginfo/resourcebinding">ResourceBinding</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a811779ca98f865df201f6012fd217f1f">getBinding</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/targetexttype">TargetExtType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a47f93450ef17fba62a5182c8070230ee">getHandleTy</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0451570bda439cb30b5c090b1f65c488">getName</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2693ec5a9ce4463060e5c5442aa925ae">hasSymbol</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/globalvariable">GlobalVariable</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a30c4281194b7b732132df23551c499af">createSymbol</a> (Module &amp;M, StructType *Ty, StringRef Name="")</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mdtuple">MDTuple</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a49b774bba229107958382054969b49bc">getAsMetadata</a> (Module &amp;M, dxil::ResourceTypeInfo &amp;RTI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::pair&lt; uint32_t, uint32_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a43c26462d608e19ba26f5425e5435127">getAnnotateProps</a> (Module &amp;M, dxil::ResourceTypeInfo &amp;RTI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae91cb2487ec1305b31571bb8187dbf68">print</a> (raw_ostream &amp;OS, dxil::ResourceTypeInfo &amp;RTI, const DataLayout &amp;DL) const</td>
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

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/dxil/resourcebindinginfo/resourcebinding">ResourceBinding</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5dd12727640af7711912907a7c774914">Binding</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/targetexttype">TargetExtType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab83fcbbd843a719473d7555ebd06c66f">HandleTy</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/globalvariable">GlobalVariable</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a03c141ba5e04e2e757f8327d310d3ee8">Symbol</a> = nullptr</td>
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


<p>Definition at line 309 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dxilresource-h">DXILResource.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### ResourceBindingInfo() {#a52c967a651ac05246a6c48ea46de5101}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::dxil::ResourceBindingInfo::ResourceBindingInfo (uint32_t RecordID, uint32_t Space, uint32_t LowerBound, uint32_t Size, <a href="/web-llvm/docs/api/classes/llvm/targetexttype">TargetExtType</a> * HandleTy, <a href="/web-llvm/docs/api/classes/llvm/globalvariable">GlobalVariable</a> * Symbol=nullptr)</td>
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



<p>Definition at line 336 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dxilresource-h">DXILResource.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>


<p>Referenced by <a href="#aa3970f4c7053e9dc979d5f4e6c814ced">operator!=</a>, <a href="#a27d1b6a7a0e6696fbe309a3a4979f335">operator&lt;</a> and <a href="#a096ec18ed5481343090f565df763b2cd">operator==</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator!=() {#aa3970f4c7053e9dc979d5f4e6c814ced}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::dxil::ResourceBindingInfo::operator!= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dxil/resourcebindinginfo">ResourceBindingInfo</a> &amp; RHS)</td>
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



<p>Definition at line 359 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dxilresource-h">DXILResource.h</a>.</p>


<p>References <a href="#a52c967a651ac05246a6c48ea46de5101">ResourceBindingInfo</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### operator&lt;() {#a27d1b6a7a0e6696fbe309a3a4979f335}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::dxil::ResourceBindingInfo::operator&lt; (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dxil/resourcebindinginfo">ResourceBindingInfo</a> &amp; RHS)</td>
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



<p>Definition at line 362 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dxilresource-h">DXILResource.h</a>.</p>


<p>References <a href="#a52c967a651ac05246a6c48ea46de5101">ResourceBindingInfo</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### operator==() {#a096ec18ed5481343090f565df763b2cd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::dxil::ResourceBindingInfo::operator== (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dxil/resourcebindinginfo">ResourceBindingInfo</a> &amp; RHS)</td>
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



<p>Definition at line 355 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dxilresource-h">DXILResource.h</a>.</p>


<p>References <a href="#a52c967a651ac05246a6c48ea46de5101">ResourceBindingInfo</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### createSymbol() {#a30c4281194b7b732132df23551c499af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GlobalVariable * ResourceBindingInfo::createSymbol (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M, <a href="/web-llvm/docs/api/classes/llvm/structtype">StructType</a> * Ty, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name="")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 349 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dxilresource-h">DXILResource.h</a>, definition at line 527 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/dxilresource-cpp">DXILResource.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57ca6c93794d7b99cd433e96c53eadb15a6e">llvm::GlobalValue::ExternalLinkage</a>.</p>

</div>
</div>

### getAnnotateProps() {#a43c26462d608e19ba26f5425e5435127}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; uint32_t, uint32_t &gt; ResourceBindingInfo::getAnnotateProps (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M, <a href="/web-llvm/docs/api/classes/llvm/dxil/resourcetypeinfo">dxil::ResourceTypeInfo</a> &amp; RTI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 353 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dxilresource-h">DXILResource.h</a>, definition at line 606 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/dxilresource-cpp">DXILResource.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/dxil/resourcetypeinfo/structinfo/#a988e3ab0e654f172fa777d3f13bfe436">llvm::dxil::ResourceTypeInfo::StructInfo::AlignLog2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a3b63a4b583ba49e5fcbc73a7cfb3575baf6c0e3a1c3cfabd32ae8d3ae741fcf0a">llvm::dxil::Comparison</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/structs/llvm/dxil/resourcetypeinfo/typedinfo/#a4504b3a027b16534569d46afa637c1bb">llvm::dxil::ResourceTypeInfo::TypedInfo::ElementCount</a>, <a href="/web-llvm/docs/api/structs/llvm/dxil/resourcetypeinfo/typedinfo/#aece1edf692f952783c46dc7563b4f60d">llvm::dxil::ResourceTypeInfo::TypedInfo::ElementTy</a>, <a href="/web-llvm/docs/api/classes/llvm/dxil/resourcetypeinfo/#a13e3e0c36e81ef726cac1dabc009592e">llvm::dxil::ResourceTypeInfo::getCBufferSize</a>, <a href="/web-llvm/docs/api/classes/llvm/dxil/resourcetypeinfo/#ad7083f943b0d625ac39d20deaca1e863">llvm::dxil::ResourceTypeInfo::getFeedbackType</a>, <a href="/web-llvm/docs/api/classes/llvm/dxil/resourcetypeinfo/#a08e1d0d1e01c55065a6220f084512668">llvm::dxil::ResourceTypeInfo::getMultiSampleCount</a>, <a href="/web-llvm/docs/api/classes/llvm/dxil/resourcetypeinfo/#ae124b03835afbb3cabde8b8cc0bb9b70">llvm::dxil::ResourceTypeInfo::getResourceKind</a>, <a href="/web-llvm/docs/api/classes/llvm/dxil/resourcetypeinfo/#a213bbc1c7f27d2677965150f90ad5a02">llvm::dxil::ResourceTypeInfo::getSamplerType</a>, <a href="/web-llvm/docs/api/classes/llvm/dxil/resourcetypeinfo/#ab8224e6835e29d5e23c3b04a30dec18c">llvm::dxil::ResourceTypeInfo::getStruct</a>, <a href="/web-llvm/docs/api/classes/llvm/dxil/resourcetypeinfo/#a39e4b5d1b12d30d8c969d9171c55ef39">llvm::dxil::ResourceTypeInfo::getTyped</a>, <a href="/web-llvm/docs/api/classes/llvm/dxil/resourcetypeinfo/#aa803b031c7da886b70562ff8e2e69c8d">llvm::dxil::ResourceTypeInfo::getUAV</a>, <a href="/web-llvm/docs/api/structs/llvm/dxil/resourcetypeinfo/uavinfo/#a2ecfd4b2d178515321dc0e838733f9a5">llvm::dxil::ResourceTypeInfo::UAVInfo::GloballyCoherent</a>, <a href="/web-llvm/docs/api/structs/llvm/dxil/resourcetypeinfo/uavinfo/#acc42675a7ccc6a57238abf1373d0a8bc">llvm::dxil::ResourceTypeInfo::UAVInfo::HasCounter</a>, <a href="/web-llvm/docs/api/classes/llvm/dxil/resourcetypeinfo/#a2854da2d6e1e5a85f4abdae5319ddc35">llvm::dxil::ResourceTypeInfo::isCBuffer</a>, <a href="/web-llvm/docs/api/classes/llvm/dxil/resourcetypeinfo/#a66a5cab0c30ec1984c6ea9bdd405c289">llvm::dxil::ResourceTypeInfo::isFeedback</a>, <a href="/web-llvm/docs/api/classes/llvm/dxil/resourcetypeinfo/#a17adf49affc0de9924726dd25a7e3a0e">llvm::dxil::ResourceTypeInfo::isMultiSample</a>, <a href="/web-llvm/docs/api/structs/llvm/dxil/resourcetypeinfo/uavinfo/#a5aeeeaedc9cc6822700f491570ab6068">llvm::dxil::ResourceTypeInfo::UAVInfo::IsROV</a>, <a href="/web-llvm/docs/api/classes/llvm/dxil/resourcetypeinfo/#a1f38896d47f03dde9704d64b669c135e">llvm::dxil::ResourceTypeInfo::isSampler</a>, <a href="/web-llvm/docs/api/classes/llvm/dxil/resourcetypeinfo/#ad5ffe17eb014d8227e03af37547ebf39">llvm::dxil::ResourceTypeInfo::isStruct</a>, <a href="/web-llvm/docs/api/classes/llvm/dxil/resourcetypeinfo/#a20e1156c776fa816c593792d6c8ec269">llvm::dxil::ResourceTypeInfo::isTyped</a>, <a href="/web-llvm/docs/api/classes/llvm/dxil/resourcetypeinfo/#a15b9fe5fbc7cddb8c5bd3510a1fbec19">llvm::dxil::ResourceTypeInfo::isUAV</a>, <a href="/web-llvm/docs/api/structs/llvm/dxil/resourcetypeinfo/structinfo/#ab2080d1c08f0b0498c29d0ad83fc1dcb">llvm::dxil::ResourceTypeInfo::StructInfo::Stride</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a842e49a58fb3eba4e42a8dadad77745b">llvm::to_underlying</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-dxiloplowering-cpp-/oplowerer/#a4a42541fb66ae32c0c9f8deede2cc21e">anonymous{DXILOpLowering.cpp}::OpLowerer::lowerToBindAndAnnotateHandle</a>.</p>

</div>
</div>

### getAsMetadata() {#a49b774bba229107958382054969b49bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MDTuple * ResourceBindingInfo::getAsMetadata (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M, <a href="/web-llvm/docs/api/classes/llvm/dxil/resourcetypeinfo">dxil::ResourceTypeInfo</a> &amp; RTI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 350 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dxilresource-h">DXILResource.h</a>, definition at line 536 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/dxilresource-cpp">DXILResource.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/structs/llvm/dxil/resourcetypeinfo/typedinfo/#aece1edf692f952783c46dc7563b4f60d">llvm::dxil::ResourceTypeInfo::TypedInfo::ElementTy</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a37fde6623fb64eebc07fd093740df31aab8e935f13aaacb4f46f84268e9c15937">llvm::dxil::ElementType</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/constantasmetadata/#a4c720c398a263087e00d7358b05636d5">llvm::ConstantAsMetadata::get</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a7d10a7b9b7f40b04d27ed97c38ea1950">llvm::MDNode::get</a>, <a href="/web-llvm/docs/api/classes/llvm/mdstring/#affbb7e2e9ad8d18114816f2443d672b9">llvm::MDString::get</a>, <a href="/web-llvm/docs/api/classes/llvm/valueasmetadata/#a53fc78b63202142110d0e86dd1a71fbe">llvm::ValueAsMetadata::get</a>, <a href="/web-llvm/docs/api/classes/llvm/dxil/resourcetypeinfo/#a13e3e0c36e81ef726cac1dabc009592e">llvm::dxil::ResourceTypeInfo::getCBufferSize</a>, <a href="/web-llvm/docs/api/classes/llvm/dxil/resourcetypeinfo/#ad7083f943b0d625ac39d20deaca1e863">llvm::dxil::ResourceTypeInfo::getFeedbackType</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#aa75984a442f2379de0c66018201fa628">llvm::Type::getInt1Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a30dd396c5b40cd86c1591872e574ccdf">llvm::Type::getInt32Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/constant/#a0154da1d06b29a1d5649607ae2dfc389">llvm::Constant::getIntegerValue</a>, <a href="/web-llvm/docs/api/classes/llvm/dxil/resourcetypeinfo/#a08e1d0d1e01c55065a6220f084512668">llvm::dxil::ResourceTypeInfo::getMultiSampleCount</a>, <a href="/web-llvm/docs/api/classes/llvm/dxil/resourcetypeinfo/#ae124b03835afbb3cabde8b8cc0bb9b70">llvm::dxil::ResourceTypeInfo::getResourceKind</a>, <a href="/web-llvm/docs/api/classes/llvm/dxil/resourcetypeinfo/#a213bbc1c7f27d2677965150f90ad5a02">llvm::dxil::ResourceTypeInfo::getSamplerType</a>, <a href="/web-llvm/docs/api/classes/llvm/dxil/resourcetypeinfo/#ab8224e6835e29d5e23c3b04a30dec18c">llvm::dxil::ResourceTypeInfo::getStruct</a>, <a href="/web-llvm/docs/api/classes/llvm/dxil/resourcetypeinfo/#a39e4b5d1b12d30d8c969d9171c55ef39">llvm::dxil::ResourceTypeInfo::getTyped</a>, <a href="/web-llvm/docs/api/classes/llvm/dxil/resourcetypeinfo/#aa803b031c7da886b70562ff8e2e69c8d">llvm::dxil::ResourceTypeInfo::getUAV</a>, <a href="/web-llvm/docs/api/structs/llvm/dxil/resourcetypeinfo/uavinfo/#a2ecfd4b2d178515321dc0e838733f9a5">llvm::dxil::ResourceTypeInfo::UAVInfo::GloballyCoherent</a>, <a href="/web-llvm/docs/api/structs/llvm/dxil/resourcetypeinfo/uavinfo/#acc42675a7ccc6a57238abf1373d0a8bc">llvm::dxil::ResourceTypeInfo::UAVInfo::HasCounter</a>, <a href="/web-llvm/docs/api/classes/llvm/dxil/resourcetypeinfo/#a2854da2d6e1e5a85f4abdae5319ddc35">llvm::dxil::ResourceTypeInfo::isCBuffer</a>, <a href="/web-llvm/docs/api/classes/llvm/dxil/resourcetypeinfo/#a66a5cab0c30ec1984c6ea9bdd405c289">llvm::dxil::ResourceTypeInfo::isFeedback</a>, <a href="/web-llvm/docs/api/classes/llvm/dxil/resourcetypeinfo/#a17adf49affc0de9924726dd25a7e3a0e">llvm::dxil::ResourceTypeInfo::isMultiSample</a>, <a href="/web-llvm/docs/api/structs/llvm/dxil/resourcetypeinfo/uavinfo/#a5aeeeaedc9cc6822700f491570ab6068">llvm::dxil::ResourceTypeInfo::UAVInfo::IsROV</a>, <a href="/web-llvm/docs/api/classes/llvm/dxil/resourcetypeinfo/#a1f38896d47f03dde9704d64b669c135e">llvm::dxil::ResourceTypeInfo::isSampler</a>, <a href="/web-llvm/docs/api/classes/llvm/dxil/resourcetypeinfo/#ad5ffe17eb014d8227e03af37547ebf39">llvm::dxil::ResourceTypeInfo::isStruct</a>, <a href="/web-llvm/docs/api/classes/llvm/dxil/resourcetypeinfo/#a20e1156c776fa816c593792d6c8ec269">llvm::dxil::ResourceTypeInfo::isTyped</a>, <a href="/web-llvm/docs/api/classes/llvm/dxil/resourcetypeinfo/#a15b9fe5fbc7cddb8c5bd3510a1fbec19">llvm::dxil::ResourceTypeInfo::isUAV</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a37fde6623fb64eebc07fd093740df31aa45fc35c4a4153c62402203d7b3927155">llvm::dxil::SamplerFeedbackKind</a>, <a href="/web-llvm/docs/api/structs/llvm/dxil/resourcetypeinfo/structinfo/#ab2080d1c08f0b0498c29d0ad83fc1dcb">llvm::dxil::ResourceTypeInfo::StructInfo::Stride</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a37fde6623fb64eebc07fd093740df31aaec72828ae30313ef7efd5f7dbda1f962">llvm::dxil::StructuredBufferStride</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a842e49a58fb3eba4e42a8dadad77745b">llvm::to_underlying</a>.</p>

</div>
</div>

### getBinding() {#a811779ca98f865df201f6012fd217f1f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const ResourceBinding &amp; llvm::dxil::ResourceBindingInfo::getBinding ()</td>
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



<p>Definition at line 344 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dxilresource-h">DXILResource.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-dxiloplowering-cpp-/oplowerer/#a4a42541fb66ae32c0c9f8deede2cc21e">anonymous{DXILOpLowering.cpp}::OpLowerer::lowerToBindAndAnnotateHandle</a> and <a href="/web-llvm/docs/api/classes/anonymous-dxiloplowering-cpp-/oplowerer/#a230768916fc2abaf5fb0f563654d2cc8">anonymous{DXILOpLowering.cpp}::OpLowerer::lowerToCreateHandle</a>.</p>

</div>
</div>

### getHandleTy() {#a47f93450ef17fba62a5182c8070230ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TargetExtType * llvm::dxil::ResourceBindingInfo::getHandleTy ()</td>
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



<p>Definition at line 345 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dxilresource-h">DXILResource.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-dxiloplowering-cpp-/oplowerer/#a4a42541fb66ae32c0c9f8deede2cc21e">anonymous{DXILOpLowering.cpp}::OpLowerer::lowerToBindAndAnnotateHandle</a>, <a href="/web-llvm/docs/api/classes/anonymous-dxiloplowering-cpp-/oplowerer/#a230768916fc2abaf5fb0f563654d2cc8">anonymous{DXILOpLowering.cpp}::OpLowerer::lowerToCreateHandle</a> and <a href="/web-llvm/docs/api/classes/llvm/dxilbindingmap/#a42b1001c73526313afc7d8da2ccb937c">llvm::DXILBindingMap::print</a>.</p>

</div>
</div>

### getName() {#a0451570bda439cb30b5c090b1f65c488}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const StringRef llvm::dxil::ResourceBindingInfo::getName ()</td>
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



<p>Definition at line 346 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dxilresource-h">DXILResource.h</a>.</p>

</div>
</div>

### hasSymbol() {#a2693ec5a9ce4463060e5c5442aa925ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::dxil::ResourceBindingInfo::hasSymbol ()</td>
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



<p>Definition at line 348 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dxilresource-h">DXILResource.h</a>.</p>

</div>
</div>

### print() {#ae91cb2487ec1305b31571bb8187dbf68}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ResourceBindingInfo::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/classes/llvm/dxil/resourcetypeinfo">dxil::ResourceTypeInfo</a> &amp; RTI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 366 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dxilresource-h">DXILResource.h</a>, definition at line 654 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/dxilresource-cpp">DXILResource.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a> and <a href="/web-llvm/docs/api/classes/llvm/dxil/resourcetypeinfo/#af6519f459201ab6e1833c32363d02615">llvm::dxil::ResourceTypeInfo::print</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dxilbindingmap/#a42b1001c73526313afc7d8da2ccb937c">llvm::DXILBindingMap::print</a>.</p>

</div>
</div>

### setBindingID() {#a24fd03b52807a4987805a18f1a54b538}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::dxil::ResourceBindingInfo::setBindingID (unsigned ID)</td>
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



<p>Definition at line 342 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dxilresource-h">DXILResource.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Binding {#a5dd12727640af7711912907a7c774914}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ResourceBinding llvm::dxil::ResourceBindingInfo::Binding</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 331 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dxilresource-h">DXILResource.h</a>.</p>

</div>
</div>

### HandleTy {#ab83fcbbd843a719473d7555ebd06c66f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TargetExtType* llvm::dxil::ResourceBindingInfo::HandleTy</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 332 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dxilresource-h">DXILResource.h</a>.</p>

</div>
</div>

### Symbol {#a03c141ba5e04e2e757f8327d310d3ee8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GlobalVariable* llvm::dxil::ResourceBindingInfo::Symbol = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 333 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dxilresource-h">DXILResource.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dxilresource-h">DXILResource.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/analysis/dxilresource-cpp">DXILResource.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>

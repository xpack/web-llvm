---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/targetintrinsicinfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `TargetIntrinsicInfo` Class

<p><a href="/web-llvm/docs/api/classes/llvm/targetintrinsicinfo">TargetIntrinsicInfo</a> - Interface to description of machine instruction set. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::TargetIntrinsicInfo { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetintrinsicinfo-h">llvm/Target/TargetIntrinsicInfo.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a707ae08f39163bd8628752d206252db2">TargetIntrinsicInfo</a> ()</td>
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

## Private Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a607051fb476fe70572141abc598a4429">TargetIntrinsicInfo</a> (const TargetIntrinsicInfo &amp;)=delete</td>
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

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0e70a2658083b9a96f0da029490a8c1a">~TargetIntrinsicInfo</a> ()</td>
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

## Private Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aef8767202230070c250f52fc747907f5">operator=</a> (const TargetIntrinsicInfo &amp;)=delete</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8294593b54352497d463272d9c268fcd">getName</a> (unsigned IID, Type **Tys=nullptr, unsigned numTys=0) const =0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the name of a target intrinsic, e.g. <a href="#a8294593b54352497d463272d9c268fcd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a567167c8797f429ca7e8c2ca0fb502e0">lookupName</a> (const char *Name, unsigned Len) const =0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Look up target intrinsic by name. <a href="#a567167c8797f429ca7e8c2ca0fb502e0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ad9308dc3f7a1e88180b8e70fcd660d">lookupName</a> (StringRef Name) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab83719d8328f99cee031acfe4881a456">getIntrinsicID</a> (const Function *F) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the target intrinsic <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> of a function, or 0. <a href="#ab83719d8328f99cee031acfe4881a456">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a04aeb72fda87bffe6bc5ece9ae0e3bec">isOverloaded</a> (unsigned IID) const =0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the intrinsic can be overloaded. <a href="#a04aeb72fda87bffe6bc5ece9ae0e3bec">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a73dcb7f71995caabd3f022bb6489b8de">getDeclaration</a> (Module *M, unsigned ID, Type **Tys=nullptr, unsigned numTys=0) const =0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create or insert an LLVM <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> declaration for an intrinsic, and return it. <a href="#a73dcb7f71995caabd3f022bb6489b8de">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p><a href="/web-llvm/docs/api/classes/llvm/targetintrinsicinfo">TargetIntrinsicInfo</a> - Interface to description of machine instruction set.</p>

<p>Definition at line 29 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetintrinsicinfo-h">TargetIntrinsicInfo.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### TargetIntrinsicInfo() {#a707ae08f39163bd8628752d206252db2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TargetIntrinsicInfo::TargetIntrinsicInfo ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 33 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetintrinsicinfo-h">TargetIntrinsicInfo.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Constructors

### TargetIntrinsicInfo() {#a607051fb476fe70572141abc598a4429}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::TargetIntrinsicInfo::TargetIntrinsicInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetintrinsicinfo">TargetIntrinsicInfo</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 30 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetintrinsicinfo-h">TargetIntrinsicInfo.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~TargetIntrinsicInfo() {#a0e70a2658083b9a96f0da029490a8c1a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TargetIntrinsicInfo::~TargetIntrinsicInfo ()</td>
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



<p>Definition at line 34 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetintrinsicinfo-h">TargetIntrinsicInfo.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Operators

### operator=() {#aef8767202230070c250f52fc747907f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::TargetIntrinsicInfo::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetintrinsicinfo">TargetIntrinsicInfo</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 31 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetintrinsicinfo-h">TargetIntrinsicInfo.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getDeclaration() {#a73dcb7f71995caabd3f022bb6489b8de}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual Function * llvm::TargetIntrinsicInfo::getDeclaration (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> * M, unsigned ID, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> ** Tys=nullptr, unsigned numTys=0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create or insert an LLVM <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> declaration for an intrinsic, and return it.</p>


<p>The Tys and numTys are for intrinsics with overloaded types. See above for more information.</p>


<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetintrinsicinfo-h">TargetIntrinsicInfo.h</a>.</p>

</div>
</div>

### getIntrinsicID() {#ab83719d8328f99cee031acfe4881a456}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned TargetIntrinsicInfo::getIntrinsicID (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * F)</td>
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

<p>Return the target intrinsic <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> of a function, or 0.</p>

<p>Declaration at line 54 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetintrinsicinfo-h">TargetIntrinsicInfo.h</a>, definition at line 22 of file <a href="/web-llvm/docs/api/files/lib/lib/target/targetintrinsicinfo-cpp">TargetIntrinsicInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/stringmapentry/#af00ecfc79d7fe461d92e306db445a13f">llvm::StringMapEntry&lt; ValueTy &gt;::getKeyData</a>, <a href="/web-llvm/docs/api/classes/llvm/stringmapentrybase/#a6a2876e4244397f90ccb7ee6c89d9b8d">llvm::StringMapEntryBase::getKeyLength</a> and <a href="#a567167c8797f429ca7e8c2ca0fb502e0">lookupName</a>.</p>

</div>
</div>

### getName() {#a8294593b54352497d463272d9c268fcd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual std::string llvm::TargetIntrinsicInfo::getName (unsigned IID, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> ** Tys=nullptr, unsigned numTys=0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the name of a target intrinsic, e.g.</p>


<p>"llvm.bfin.ssync". The Tys and numTys parameters are for intrinsics with overloaded types (e.g., those using iAny or fAny). For a declaration for an overloaded intrinsic, Tys should point to an array of numTys pointers to <a href="/web-llvm/docs/api/classes/llvm/type">Type</a>, and must provide exactly one type for each overloaded type in the intrinsic.</p>


<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetintrinsicinfo-h">TargetIntrinsicInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a76123bb0e0b41f5dbae594726160db22">llvm::MachineOperand::print</a>.</p>

</div>
</div>

### isOverloaded() {#a04aeb72fda87bffe6bc5ece9ae0e3bec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::TargetIntrinsicInfo::isOverloaded (unsigned IID)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if the intrinsic can be overloaded.</p>

<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetintrinsicinfo-h">TargetIntrinsicInfo.h</a>.</p>

</div>
</div>

### lookupName() {#a567167c8797f429ca7e8c2ca0fb502e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual unsigned llvm::TargetIntrinsicInfo::lookupName (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Name, unsigned Len)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Look up target intrinsic by name.</p>


<p>Return intrinsic <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> or 0 for unknown names.</p>


<p>Definition at line 47 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetintrinsicinfo-h">TargetIntrinsicInfo.h</a>.</p>


<p>Referenced by <a href="#ab83719d8328f99cee031acfe4881a456">getIntrinsicID</a> and <a href="#a6ad9308dc3f7a1e88180b8e70fcd660d">lookupName</a>.</p>

</div>
</div>

### lookupName() {#a6ad9308dc3f7a1e88180b8e70fcd660d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::TargetIntrinsicInfo::lookupName (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name)</td>
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



<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetintrinsicinfo-h">TargetIntrinsicInfo.h</a>.</p>


<p>Reference <a href="#a567167c8797f429ca7e8c2ca0fb502e0">lookupName</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetintrinsicinfo-h">TargetIntrinsicInfo.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/targetintrinsicinfo-cpp">TargetIntrinsicInfo.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>

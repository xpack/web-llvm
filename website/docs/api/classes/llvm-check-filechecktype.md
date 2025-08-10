---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/check/filechecktype
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `FileCheckType` Class



## Declaration

<div class="doxyDeclaration">
class llvm::Check::FileCheckType { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/filecheck/filecheck-h">llvm/FileCheck/FileCheck.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2a4947cd2e57d206679931026b546c34">FileCheckType</a> (FileCheckKind Kind=CheckNone)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae6a29787459853aee90f3e508fac7887">FileCheckType</a> (const FileCheckType &amp;)=default</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/check/filechecktype">FileCheckType</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7922259bf1332f1c9fc8e4377773293b">operator=</a> (const FileCheckType &amp;)=default</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a50c193fe0d391f363221f1c7614c8226">operator FileCheckKind</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a511397f75441782625f94f0e93ca52b1">getCount</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/check/filechecktype">FileCheckType</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adc074eb68067d4d38018423166be1926">setCount</a> (int C)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a6bf97dd298b0d945dc397299bf5012">isLiteralMatch</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/check/filechecktype">FileCheckType</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad1f00eec67051e893a5adf6fe29e44ac">setLiteralMatch</a> (bool Literal=true)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a28c2d38b7ebdeb9e3046f013c8ffa8a4">getDescription</a> (StringRef Prefix) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab7cf540b51335002091691a5f7671c84">getModifiersDescription</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/check/#a61538d341f95c09113a9a0d0434d8dcc">FileCheckKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a699d7057bd091ec2ad53b597b2d229bb">Kind</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2b35a01d7b52bcba3538396f89f61697">Count</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>optional Count for some checks <a href="#a2b35a01d7b52bcba3538396f89f61697">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::bitset&lt; <a href="/web-llvm/docs/api/namespaces/llvm/check/#a067ee17412e800f03802fa9517685732a3450a9712780ac26b071f9da4288a396">FileCheckKindModifier::Size</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f6d83403e89d823630289dfe3bdfb8f">Modifiers</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Modifers for the check directive. <a href="#a3f6d83403e89d823630289dfe3bdfb8f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 80 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/filecheck/filecheck-h">FileCheck.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### FileCheckType() {#a2a4947cd2e57d206679931026b546c34}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::Check::FileCheckType::FileCheckType (<a href="/web-llvm/docs/api/namespaces/llvm/check/#a61538d341f95c09113a9a0d0434d8dcc">FileCheckKind</a> Kind=<a href="/web-llvm/docs/api/namespaces/llvm/check/#a61538d341f95c09113a9a0d0434d8dcca9852bebd673f9c43a584b08401e3197d">CheckNone</a>)</td>
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



<p>Definition at line 87 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/filecheck/filecheck-h">FileCheck.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/check/#a61538d341f95c09113a9a0d0434d8dcca9852bebd673f9c43a584b08401e3197d">llvm::Check::CheckNone</a>.</p>


<p>Referenced by <a href="#ae6a29787459853aee90f3e508fac7887">FileCheckType</a>, <a href="#a7922259bf1332f1c9fc8e4377773293b">operator=</a> and <a href="#ad1f00eec67051e893a5adf6fe29e44ac">setLiteralMatch</a>.</p>

</div>
</div>

### FileCheckType() {#ae6a29787459853aee90f3e508fac7887}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::Check::FileCheckType::FileCheckType (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/check/filechecktype">FileCheckType</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 88 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/filecheck/filecheck-h">FileCheck.h</a>.</p>


<p>Reference <a href="#a2a4947cd2e57d206679931026b546c34">FileCheckType</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator FileCheckKind() {#a50c193fe0d391f363221f1c7614c8226}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::Check::FileCheckType::operator FileCheckKind ()</td>
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



<p>Definition at line 91 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/filecheck/filecheck-h">FileCheck.h</a>.</p>

</div>
</div>

### operator=() {#a7922259bf1332f1c9fc8e4377773293b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FileCheckType &amp; llvm::Check::FileCheckType::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/check/filechecktype">FileCheckType</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 89 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/filecheck/filecheck-h">FileCheck.h</a>.</p>


<p>Reference <a href="#a2a4947cd2e57d206679931026b546c34">FileCheckType</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getCount() {#a511397f75441782625f94f0e93ca52b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::Check::FileCheckType::getCount ()</td>
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



<p>Definition at line 93 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/filecheck/filecheck-h">FileCheck.h</a>.</p>

</div>
</div>

### getDescription() {#a28c2d38b7ebdeb9e3046f013c8ffa8a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string Check::FileCheckType::getDescription (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Prefix)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 105 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/filecheck/filecheck-h">FileCheck.h</a>, definition at line 1494 of file <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheck-cpp">FileCheck.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/check/#a61538d341f95c09113a9a0d0434d8dccab74df0ffb39a8f2c0918324e23a899f2">llvm::Check::CheckBadCount</a>, <a href="/web-llvm/docs/api/namespaces/llvm/check/#a61538d341f95c09113a9a0d0434d8dcca8b26e2b469fdd62f96446d3299b4189e">llvm::Check::CheckBadNot</a>, <a href="/web-llvm/docs/api/namespaces/llvm/check/#a61538d341f95c09113a9a0d0434d8dccaf16a622382af4f7939c473b436c8f2ca">llvm::Check::CheckComment</a>, <a href="/web-llvm/docs/api/namespaces/llvm/check/#a61538d341f95c09113a9a0d0434d8dcca6e00b905236376d8aec56ad3351a45b0">llvm::Check::CheckDAG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/check/#a61538d341f95c09113a9a0d0434d8dcca80e33945f521f203f2a632bc0f2041e5">llvm::Check::CheckEmpty</a>, <a href="/web-llvm/docs/api/namespaces/llvm/check/#a61538d341f95c09113a9a0d0434d8dccaba2d525032487e7def52c8154b19e29c">llvm::Check::CheckEOF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/check/#a61538d341f95c09113a9a0d0434d8dccad88307ccd9067d72cfb0e62d19daa77d">llvm::Check::CheckLabel</a>, <a href="/web-llvm/docs/api/namespaces/llvm/check/#a61538d341f95c09113a9a0d0434d8dccabced3746e039f44b8e662be748fd4e17">llvm::Check::CheckMisspelled</a>, <a href="/web-llvm/docs/api/namespaces/llvm/check/#a61538d341f95c09113a9a0d0434d8dcca49f3a249a76b57b5659baae2c45dfb75">llvm::Check::CheckNext</a>, <a href="/web-llvm/docs/api/namespaces/llvm/check/#a61538d341f95c09113a9a0d0434d8dcca9852bebd673f9c43a584b08401e3197d">llvm::Check::CheckNone</a>, <a href="/web-llvm/docs/api/namespaces/llvm/check/#a61538d341f95c09113a9a0d0434d8dcca4f9655da5198915aff91bd25115d22fa">llvm::Check::CheckNot</a>, <a href="/web-llvm/docs/api/namespaces/llvm/check/#a61538d341f95c09113a9a0d0434d8dcca166f25ea09a5e0064149ae472c8d8f2e">llvm::Check::CheckPlain</a>, <a href="/web-llvm/docs/api/namespaces/llvm/check/#a61538d341f95c09113a9a0d0434d8dccaf738504ab1341813c0cda15fa68a6310">llvm::Check::CheckSame</a>, <a href="#ab7cf540b51335002091691a5f7671c84">getModifiersDescription</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheck-cpp/#adadd7e41a96b9e407d8e07cb45a0d6e2">printMatch</a> and <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheck-cpp/#a5d394830d4143542278afee43f527b48">printNoMatch</a>.</p>

</div>
</div>

### getModifiersDescription() {#ab7cf540b51335002091691a5f7671c84}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string Check::FileCheckType::getModifiersDescription ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 108 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/filecheck/filecheck-h">FileCheck.h</a>, definition at line 1482 of file <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheck-cpp">FileCheck.cpp</a>.</p>


<p>Reference <a href="#a9a6bf97dd298b0d945dc397299bf5012">isLiteralMatch</a>.</p>


<p>Referenced by <a href="#a28c2d38b7ebdeb9e3046f013c8ffa8a4">getDescription</a>.</p>

</div>
</div>

### isLiteralMatch() {#a9a6bf97dd298b0d945dc397299bf5012}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Check::FileCheckType::isLiteralMatch ()</td>
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



<p>Definition at line 96 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/filecheck/filecheck-h">FileCheck.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/check/#a067ee17412e800f03802fa9517685732a563a220961f1b2753b54ca54c648119e">llvm::Check::ModifierLiteral</a>.</p>


<p>Referenced by <a href="#ab7cf540b51335002091691a5f7671c84">getModifiersDescription</a>.</p>

</div>
</div>

### setCount() {#adc074eb68067d4d38018423166be1926}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Check::FileCheckType &amp; Check::FileCheckType::setCount (int C)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 94 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/filecheck/filecheck-h">FileCheck.h</a>, definition at line 1474 of file <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheck-cpp">FileCheck.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a> and <a href="/web-llvm/docs/api/namespaces/llvm/check/#a61538d341f95c09113a9a0d0434d8dcca166f25ea09a5e0064149ae472c8d8f2e">llvm::Check::CheckPlain</a>.</p>

</div>
</div>

### setLiteralMatch() {#ad1f00eec67051e893a5adf6fe29e44ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FileCheckType &amp; llvm::Check::FileCheckType::setLiteralMatch (bool Literal=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
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



<p>Definition at line 99 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/filecheck/filecheck-h">FileCheck.h</a>.</p>


<p>References <a href="#a2a4947cd2e57d206679931026b546c34">FileCheckType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab7530cd22b8952cb41774507dd40c6f3ad7da1b76e5799f53a399b7a96ba67437">llvm::Literal</a> and <a href="/web-llvm/docs/api/namespaces/llvm/check/#a067ee17412e800f03802fa9517685732a563a220961f1b2753b54ca54c648119e">llvm::Check::ModifierLiteral</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Count {#a2b35a01d7b52bcba3538396f89f61697}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::Check::FileCheckType::Count</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>optional Count for some checks</p>

<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/filecheck/filecheck-h">FileCheck.h</a>.</p>

</div>
</div>

### Kind {#a699d7057bd091ec2ad53b597b2d229bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FileCheckKind llvm::Check::FileCheckType::Kind</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 81 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/filecheck/filecheck-h">FileCheck.h</a>.</p>

</div>
</div>

### Modifiers {#a3f6d83403e89d823630289dfe3bdfb8f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::bitset&lt;FileCheckKindModifier::Size&gt; llvm::Check::FileCheckType::Modifiers</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Modifers for the check directive.</p>

<p>Definition at line 84 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/filecheck/filecheck-h">FileCheck.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/filecheck/filecheck-h">FileCheck.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheck-cpp">FileCheck.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>

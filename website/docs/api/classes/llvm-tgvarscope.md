---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/tgvarscope
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `TGVarScope` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::TGVarScope { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-h">TableGen/TGParser.h</a>"
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">ScopeKind { <a href="#a778c9209fc93c809b9ed91802592f8d9">...</a> }</td>
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

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af509279bcdf25054a35fdd0599c71f98">TGVarScope</a> (std::unique_ptr&lt; TGVarScope &gt; Parent)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b951404c5970a8c1f82f0d72e254dde">TGVarScope</a> (std::unique_ptr&lt; TGVarScope &gt; Parent, Record *Rec)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a872259820179265f73e65b0cc3efed55">TGVarScope</a> (std::unique_ptr&lt; TGVarScope &gt; Parent, ForeachLoop *Loop)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae90772e09a8bc848f6d952c3fa280878">TGVarScope</a> (std::unique_ptr&lt; TGVarScope &gt; Parent, MultiClass *Multiclass)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/tgvarscope">TGVarScope</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a693eefcce87e55923aa8d55fa44d2ec7">extractParent</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/init">Init</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae579c02468ab9307ae959877d8375ada">getVar</a> (RecordKeeper &amp;Records, MultiClass *ParsingMultiClass, const StringInit *Name, SMRange NameLoc, bool TrackReferenceLocs) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac17bc7fb99eaa245dae87d5c7f8a52c4">varAlreadyDefined</a> (StringRef Name) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac015aedf758fe51bbeea5c0ed178e0af">addVar</a> (StringRef Name, const Init *I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c16dd5034533f5e7f67c37e37bb05c1">isOutermost</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a778c9209fc93c809b9ed91802592f8d9">ScopeKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3aa85aee98a2ce0b8c88732f8b17bd38">Kind</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/tgvarscope">TGVarScope</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a94eea0f536c06a42d1d7e3e27b2a9171">Parent</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::map&lt; std::string, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/init">Init</a> *, std::less&lt;&gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aad93a06e77f03f912dbbea16bf5e1770">Vars</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/record">Record</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab38512f73b8bf9deed064c195cee722b">CurRec</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/foreachloop">ForeachLoop</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a670937035cf83a6abcbc45e00176ddd9">CurLoop</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/multiclass">MultiClass</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a69bbd0f13c0df55180412fe91137cddf">CurMultiClass</a> = nullptr</td>
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


<p>Definition at line 91 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-h">TGParser.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### ScopeKind {#a778c9209fc93c809b9ed91802592f8d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::TGVarScope::ScopeKind </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SK_Local<a id="a778c9209fc93c809b9ed91802592f8d9aa1b5e8d9fb57d00e1caf55f1212fdb2a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SK_Record<a id="a778c9209fc93c809b9ed91802592f8d9a507c5c2389f59021f103839e676ca0a5"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SK_ForeachLoop<a id="a778c9209fc93c809b9ed91802592f8d9ad7244b7d1afd2b7dd31fd174e4bcce68"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SK_MultiClass<a id="a778c9209fc93c809b9ed91802592f8d9a2ad06f6a59f9b7040038f59638f1e7ac"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 93 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-h">TGParser.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### TGVarScope() {#af509279bcdf25054a35fdd0599c71f98}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::TGVarScope::TGVarScope (std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/tgvarscope">TGVarScope</a> &gt; Parent)</td>
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



<p>Definition at line 105 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-h">TGParser.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a> and <a href="#a778c9209fc93c809b9ed91802592f8d9aa1b5e8d9fb57d00e1caf55f1212fdb2a">SK_Local</a>.</p>

</div>
</div>

### TGVarScope() {#a3b951404c5970a8c1f82f0d72e254dde}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::TGVarScope::TGVarScope (std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/tgvarscope">TGVarScope</a> &gt; Parent, <a href="/web-llvm/docs/api/classes/llvm/record">Record</a> * Rec)</td>
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



<p>Definition at line 107 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-h">TGParser.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a> and <a href="#a778c9209fc93c809b9ed91802592f8d9a507c5c2389f59021f103839e676ca0a5">SK_Record</a>.</p>

</div>
</div>

### TGVarScope() {#a872259820179265f73e65b0cc3efed55}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::TGVarScope::TGVarScope (std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/tgvarscope">TGVarScope</a> &gt; Parent, <a href="/web-llvm/docs/api/structs/llvm/foreachloop">ForeachLoop</a> * Loop)</td>
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



<p>Definition at line 109 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-h">TGParser.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a> and <a href="#a778c9209fc93c809b9ed91802592f8d9ad7244b7d1afd2b7dd31fd174e4bcce68">SK_ForeachLoop</a>.</p>

</div>
</div>

### TGVarScope() {#ae90772e09a8bc848f6d952c3fa280878}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::TGVarScope::TGVarScope (std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/tgvarscope">TGVarScope</a> &gt; Parent, <a href="/web-llvm/docs/api/structs/llvm/multiclass">MultiClass</a> * Multiclass)</td>
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



<p>Definition at line 111 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-h">TGParser.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a> and <a href="#a778c9209fc93c809b9ed91802592f8d9a2ad06f6a59f9b7040038f59638f1e7ac">SK_MultiClass</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addVar() {#ac015aedf758fe51bbeea5c0ed178e0af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::TGVarScope::addVar (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/init">Init</a> * I)</td>
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



<p>Definition at line 133 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-h">TGParser.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### extractParent() {#a693eefcce87e55923aa8d55fa44d2ec7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; TGVarScope &gt; llvm::TGVarScope::extractParent ()</td>
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



<p>Definition at line 115 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-h">TGParser.h</a>.</p>

</div>
</div>

### getVar() {#ae579c02468ab9307ae959877d8375ada}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Init * TGVarScope::getVar (<a href="/web-llvm/docs/api/classes/llvm/recordkeeper">RecordKeeper</a> &amp; Records, <a href="/web-llvm/docs/api/structs/llvm/multiclass">MultiClass</a> * ParsingMultiClass, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/stringinit">StringInit</a> * Name, <a href="/web-llvm/docs/api/classes/llvm/smrange">SMRange</a> NameLoc, bool TrackReferenceLocs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 121 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-h">TGParser.h</a>, definition at line 138 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-cpp">TGParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/recordval/#a6067cec0c34fc92709714d819d1ea799">llvm::RecordVal::addReferenceLoc</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/stringrecty/#ad4b14749b521864736b5f40898f0a43a">llvm::StringRecTy::get</a>, <a href="/web-llvm/docs/api/classes/llvm/varinit/#a23cd6b7f50eb1672ac5cf603115e6099">llvm::VarInit::get</a>, <a href="/web-llvm/docs/api/classes/llvm/recordval/#aef92c6dfcf94a1b8739b6672fdbb6900">llvm::RecordVal::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/record/#a5e084b9b417ae456b128ee1f6506b41d">llvm::Record::getValue</a>, <a href="/web-llvm/docs/api/classes/llvm/recordval/#a49242b28322ab4ecc5f2af6a43be2bdd">llvm::RecordVal::getValue</a>, <a href="/web-llvm/docs/api/classes/llvm/record/#a9a175c899ffaa6ddfc6c4ce2f823c042">llvm::Record::isTemplateArg</a>, <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-cpp/#a678066d868a6e0abb3151be33bb7232e">QualifyName</a>, <a href="/web-llvm/docs/api/classes/llvm/recordval/#a172dd84b794d6c96ac51f130ad541963">llvm::RecordVal::setUsed</a>, <a href="#a778c9209fc93c809b9ed91802592f8d9ad7244b7d1afd2b7dd31fd174e4bcce68">SK_ForeachLoop</a>, <a href="#a778c9209fc93c809b9ed91802592f8d9aa1b5e8d9fb57d00e1caf55f1212fdb2a">SK_Local</a>, <a href="#a778c9209fc93c809b9ed91802592f8d9a2ad06f6a59f9b7040038f59638f1e7ac">SK_MultiClass</a> and <a href="#a778c9209fc93c809b9ed91802592f8d9a507c5c2389f59021f103839e676ca0a5">SK_Record</a>.</p>

</div>
</div>

### isOutermost() {#a6c16dd5034533f5e7f67c37e37bb05c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::TGVarScope::isOutermost ()</td>
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



<p>Definition at line 139 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-h">TGParser.h</a>.</p>

</div>
</div>

### varAlreadyDefined() {#ac17bc7fb99eaa245dae87d5c7f8a52c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::TGVarScope::varAlreadyDefined (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name)</td>
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



<p>Definition at line 125 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-h">TGParser.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### CurLoop {#a670937035cf83a6abcbc45e00176ddd9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ForeachLoop* llvm::TGVarScope::CurLoop = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 101 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-h">TGParser.h</a>.</p>

</div>
</div>

### CurMultiClass {#a69bbd0f13c0df55180412fe91137cddf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MultiClass* llvm::TGVarScope::CurMultiClass = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 102 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-h">TGParser.h</a>.</p>

</div>
</div>

### CurRec {#ab38512f73b8bf9deed064c195cee722b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Record* llvm::TGVarScope::CurRec = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 100 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-h">TGParser.h</a>.</p>

</div>
</div>

### Kind {#a3aa85aee98a2ce0b8c88732f8b17bd38}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ScopeKind llvm::TGVarScope::Kind</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 96 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-h">TGParser.h</a>.</p>

</div>
</div>

### Parent {#a94eea0f536c06a42d1d7e3e27b2a9171}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;TGVarScope&gt; llvm::TGVarScope::Parent</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 97 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-h">TGParser.h</a>.</p>

</div>
</div>

### Vars {#aad93a06e77f03f912dbbea16bf5e1770}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::map&lt;std::string, const Init *, std::less&lt;&gt; &gt; llvm::TGVarScope::Vars</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 99 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-h">TGParser.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-cpp">TGParser.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-h">TGParser.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>

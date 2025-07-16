---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/sandboxir/globalalias
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `GlobalAlias` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::sandboxir::GlobalAlias { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/constant-h">llvm/SandboxIR/Constant.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sandboxir/globalwithnodeapi">GlobalWithNodeAPI&lt;GlobalT, LLVMGlobalT, ParentT, LLVMParentT&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Provides API functions, like <a href="/web-llvm/docs/api/classes/llvm/sandboxir/globalwithnodeapi/#a6ca3df0dddca4fe048a4bdb535362010">getIterator()</a> and <a href="/web-llvm/docs/api/classes/llvm/sandboxir/globalwithnodeapi/#ac80dadfb9db2288710b8d145fe27ad84">getReverseIterator()</a> to <a href="/web-llvm/docs/api/classes/llvm/sandboxir/globalifunc">GlobalIFunc</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/function">Function</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/globalvariable">GlobalVariable</a> and <a href="/web-llvm/docs/api/classes/llvm/sandboxir/globalalias">GlobalAlias</a>. <a href="/web-llvm/docs/api/classes/llvm/sandboxir/globalwithnodeapi/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac26c806e60ca4a0547680edb68f6e39b">Context</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa1d7b2e91f710966db225e10cada7415">GlobalAlias</a> (llvm::GlobalAlias *C, Context &amp;Ctx)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab1309f79334a271b4fa4d216dcc5e2f2">setAliasee</a> (Constant *Aliasee)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sandboxir/constant">Constant</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a158155f07514ae91ba76e5af2299527f">getAliasee</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sandboxir/globalobject">GlobalObject</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aabb0a4b74885241d72ea92604c3846c3">getAliaseeObject</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sandboxir/globalobject">GlobalObject</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad4a9e32edfd842e63b0f79b30283ce01">getAliaseeObject</a> ()</td>
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

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a27c9088f4451608a542ebe926883278d">classof</a> (const sandboxir::Value *From)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>For isa/dyn_cast. <a href="#a27c9088f4451608a542ebe926883278d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a12b24936a54e0a5f7c2e4f949a1d7da8">isValidLinkage</a> (LinkageTypes L)</td>
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


<p>Definition at line 1022 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/constant-h">Constant.h</a>.</p>


<div class="doxySectionDef">

## Friends

### Context {#ac26c806e60ca4a0547680edb68f6e39b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/sandboxir/context">Context</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 1027 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/constant-h">Constant.h</a>.</p>


<p>Reference <a href="#ac26c806e60ca4a0547680edb68f6e39b">Context</a>.</p>


<p>Referenced by <a href="#ac26c806e60ca4a0547680edb68f6e39b">Context</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Constructors

### GlobalAlias() {#aa1d7b2e91f710966db225e10cada7415}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::sandboxir::GlobalAlias::GlobalAlias (<a href="/web-llvm/docs/api/classes/llvm/globalalias">llvm::GlobalAlias</a> * C, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/context">Context</a> &amp; Ctx)</td>
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



<p>Definition at line 1025 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/constant-h">Constant.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getAliasee() {#a158155f07514ae91ba76e5af2299527f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Constant * llvm::sandboxir::GlobalAlias::getAliasee ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1041 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/constant-h">Constant.h</a>, definition at line 385 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/constant-cpp">Constant.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/value/#a4705ee51ec0da1ba978f2353d2c47f27">llvm::sandboxir::Value::Ctx</a> and <a href="/web-llvm/docs/api/classes/llvm/sandboxir/value/#a0c4530f3c64d8c2eafac20fb87105d8a">llvm::sandboxir::Value::Val</a>.</p>

</div>
</div>

### getAliaseeObject() {#aabb0a4b74885241d72ea92604c3846c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const GlobalObject * llvm::sandboxir::GlobalAlias::getAliaseeObject ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1043 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/constant-h">Constant.h</a>, definition at line 390 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/constant-cpp">Constant.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/value/#a4705ee51ec0da1ba978f2353d2c47f27">llvm::sandboxir::Value::Ctx</a> and <a href="/web-llvm/docs/api/classes/llvm/sandboxir/value/#a0c4530f3c64d8c2eafac20fb87105d8a">llvm::sandboxir::Value::Val</a>.</p>

</div>
</div>

### getAliaseeObject() {#ad4a9e32edfd842e63b0f79b30283ce01}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GlobalObject * llvm::sandboxir::GlobalAlias::getAliaseeObject ()</td>
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



<p>Definition at line 1044 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/constant-h">Constant.h</a>.</p>

</div>
</div>

### setAliasee() {#ab1309f79334a271b4fa4d216dcc5e2f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::sandboxir::GlobalAlias::setAliasee (<a href="/web-llvm/docs/api/classes/llvm/sandboxir/constant">Constant</a> * Aliasee)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1040 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/constant-h">Constant.h</a>, definition at line 377 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/constant-cpp">Constant.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/value/#a4705ee51ec0da1ba978f2353d2c47f27">llvm::sandboxir::Value::Ctx</a> and <a href="/web-llvm/docs/api/classes/llvm/sandboxir/value/#a0c4530f3c64d8c2eafac20fb87105d8a">llvm::sandboxir::Value::Val</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### classof() {#a27c9088f4451608a542ebe926883278d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sandboxir::GlobalAlias::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sandboxir/value">sandboxir::Value</a> * From)</td>
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

<p>For isa/dyn_cast.</p>

<p>Definition at line 1031 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/constant-h">Constant.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/sandboxir/value/#a27b9af008c6420f3340805e50297f9fb">llvm::sandboxir::Value::getSubclassID</a>.</p>

</div>
</div>

### isValidLinkage() {#a12b24936a54e0a5f7c2e4f949a1d7da8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sandboxir::GlobalAlias::isValidLinkage (<a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57c">LinkageTypes</a> L)</td>
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



<p>Definition at line 1049 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/constant-h">Constant.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/globalalias/#a0dc1071ac8fdde2dc10ba6c7700598f4">llvm::GlobalAlias::isValidLinkage</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/constant-h">Constant.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/sandboxir/constant-cpp">Constant.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>

---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/mdnodekeyimpl-633cc5d3b8e0834f084fa6ef9da68de8
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `MDNodeKeyImpl` Struct Template Reference



## Declaration

<div class="doxyDeclaration">
struct llvm::MDNodeKeyImpl&lt;DIGlobalVariable&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">IR/LLVMContextImpl.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa57fde8c76036c875f262f50f37b1a67">MDNodeKeyImpl</a> (Metadata *Scope, MDString *Name, MDString *LinkageName, Metadata *File, unsigned Line, Metadata *Type, bool IsLocalToUnit, bool IsDefinition, Metadata *StaticDataMemberDeclaration, Metadata *TemplateParams, uint32_t AlignInBits, Metadata *Annotations)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab332f9d2f6fb953b3090477a0a5d30d1">MDNodeKeyImpl</a> (const DIGlobalVariable *N)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a530ff5f1c95d9a06172a875dd401bc40">isKeyOf</a> (const DIGlobalVariable *RHS) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac46adc0df0d92d4d54d4711a0d5f2a2e">getHashValue</a> () const</td>
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

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a542f1d054282167867ba94de57b9b4cf">Scope</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5101d356db9b35567e2fac05a879e6d8">Name</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3dfa8fa5f24c6037d7dcfc0925dcfd10">LinkageName</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad2b9f478903971fe37039875e2bd604c">File</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a800c2820f4a56ecbf67cb684cb6ddefb">Line</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ec5509d26a316c37b6927cf6ce89242">Type</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a39fbc427432bee8a137772d77c5ed954">IsLocalToUnit</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a51239438a7ac84edc6af7f3518d9af52">IsDefinition</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a15f08a035b08ff0c2bcbe671e28ce722">StaticDataMemberDeclaration</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a753c39ef5571d20f25d541d8cf27acfd">TemplateParams</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac13b761ee298a1e37098b9ca7c0a89a9">AlignInBits</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8bd04b1359f3c3769de5613edf2871a1">Annotations</a></td>
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


<p>Definition at line 1074 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### MDNodeKeyImpl() {#aa57fde8c76036c875f262f50f37b1a67}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MDNodeKeyImpl&lt; DIGlobalVariable &gt;::MDNodeKeyImpl (<a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> * Scope, <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> * Name, <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> * LinkageName, <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> * File, unsigned Line, <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> * Type, bool IsLocalToUnit, bool IsDefinition, <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> * StaticDataMemberDeclaration, <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> * TemplateParams, uint32_t AlignInBits, <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> * Annotations)</td>
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



<p>Definition at line 1088 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>


<p>References <a href="#ac13b761ee298a1e37098b9ca7c0a89a9">AlignInBits</a>, <a href="#a8bd04b1359f3c3769de5613edf2871a1">Annotations</a>, <a href="#ad2b9f478903971fe37039875e2bd604c">File</a>, <a href="#a51239438a7ac84edc6af7f3518d9af52">IsDefinition</a>, <a href="#a39fbc427432bee8a137772d77c5ed954">IsLocalToUnit</a>, <a href="#a800c2820f4a56ecbf67cb684cb6ddefb">Line</a>, <a href="#a3dfa8fa5f24c6037d7dcfc0925dcfd10">LinkageName</a>, <a href="#a5101d356db9b35567e2fac05a879e6d8">Name</a>, <a href="#a542f1d054282167867ba94de57b9b4cf">Scope</a>, <a href="#a15f08a035b08ff0c2bcbe671e28ce722">StaticDataMemberDeclaration</a>, <a href="#a753c39ef5571d20f25d541d8cf27acfd">TemplateParams</a> and <a href="#a1ec5509d26a316c37b6927cf6ce89242">Type</a>.</p>

</div>
</div>

### MDNodeKeyImpl() {#ab332f9d2f6fb953b3090477a0a5d30d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MDNodeKeyImpl&lt; DIGlobalVariable &gt;::MDNodeKeyImpl (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/diglobalvariable">DIGlobalVariable</a> * N)</td>
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



<p>Definition at line 1099 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>


<p>References <a href="#ac13b761ee298a1e37098b9ca7c0a89a9">AlignInBits</a>, <a href="#a8bd04b1359f3c3769de5613edf2871a1">Annotations</a>, <a href="#ad2b9f478903971fe37039875e2bd604c">File</a>, <a href="#a51239438a7ac84edc6af7f3518d9af52">IsDefinition</a>, <a href="#a39fbc427432bee8a137772d77c5ed954">IsLocalToUnit</a>, <a href="#a800c2820f4a56ecbf67cb684cb6ddefb">Line</a>, <a href="#a3dfa8fa5f24c6037d7dcfc0925dcfd10">LinkageName</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="#a5101d356db9b35567e2fac05a879e6d8">Name</a>, <a href="#a542f1d054282167867ba94de57b9b4cf">Scope</a>, <a href="#a15f08a035b08ff0c2bcbe671e28ce722">StaticDataMemberDeclaration</a>, <a href="#a753c39ef5571d20f25d541d8cf27acfd">TemplateParams</a> and <a href="#a1ec5509d26a316c37b6927cf6ce89242">Type</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getHashValue() {#ac46adc0df0d92d4d54d4711a0d5f2a2e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MDNodeKeyImpl&lt; DIGlobalVariable &gt;::getHashValue ()</td>
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



<p>Definition at line 1121 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>


<p>References <a href="#a8bd04b1359f3c3769de5613edf2871a1">Annotations</a>, <a href="#ad2b9f478903971fe37039875e2bd604c">File</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#add71474638430694c84640146383fc44">llvm::hash_combine</a>, <a href="#a51239438a7ac84edc6af7f3518d9af52">IsDefinition</a>, <a href="#a39fbc427432bee8a137772d77c5ed954">IsLocalToUnit</a>, <a href="#a800c2820f4a56ecbf67cb684cb6ddefb">Line</a>, <a href="#a3dfa8fa5f24c6037d7dcfc0925dcfd10">LinkageName</a>, <a href="#a5101d356db9b35567e2fac05a879e6d8">Name</a>, <a href="#a542f1d054282167867ba94de57b9b4cf">Scope</a>, <a href="#a15f08a035b08ff0c2bcbe671e28ce722">StaticDataMemberDeclaration</a> and <a href="#a1ec5509d26a316c37b6927cf6ce89242">Type</a>.</p>

</div>
</div>

### isKeyOf() {#a530ff5f1c95d9a06172a875dd401bc40}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MDNodeKeyImpl&lt; DIGlobalVariable &gt;::isKeyOf (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/diglobalvariable">DIGlobalVariable</a> * RHS)</td>
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



<p>Definition at line 1108 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>


<p>References <a href="#ac13b761ee298a1e37098b9ca7c0a89a9">AlignInBits</a>, <a href="#a8bd04b1359f3c3769de5613edf2871a1">Annotations</a>, <a href="#ad2b9f478903971fe37039875e2bd604c">File</a>, <a href="#a51239438a7ac84edc6af7f3518d9af52">IsDefinition</a>, <a href="#a39fbc427432bee8a137772d77c5ed954">IsLocalToUnit</a>, <a href="#a800c2820f4a56ecbf67cb684cb6ddefb">Line</a>, <a href="#a3dfa8fa5f24c6037d7dcfc0925dcfd10">LinkageName</a>, <a href="#a5101d356db9b35567e2fac05a879e6d8">Name</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>, <a href="#a542f1d054282167867ba94de57b9b4cf">Scope</a>, <a href="#a15f08a035b08ff0c2bcbe671e28ce722">StaticDataMemberDeclaration</a>, <a href="#a753c39ef5571d20f25d541d8cf27acfd">TemplateParams</a> and <a href="#a1ec5509d26a316c37b6927cf6ce89242">Type</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### AlignInBits {#ac13b761ee298a1e37098b9ca7c0a89a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::MDNodeKeyImpl&lt; DIGlobalVariable &gt;::AlignInBits</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1085 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>


<p>Referenced by <a href="#a530ff5f1c95d9a06172a875dd401bc40">isKeyOf</a>, <a href="#ab332f9d2f6fb953b3090477a0a5d30d1">MDNodeKeyImpl</a> and <a href="#aa57fde8c76036c875f262f50f37b1a67">MDNodeKeyImpl</a>.</p>

</div>
</div>

### Annotations {#a8bd04b1359f3c3769de5613edf2871a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Metadata* llvm::MDNodeKeyImpl&lt; DIGlobalVariable &gt;::Annotations</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1086 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>


<p>Referenced by <a href="#ac46adc0df0d92d4d54d4711a0d5f2a2e">getHashValue</a>, <a href="#a530ff5f1c95d9a06172a875dd401bc40">isKeyOf</a>, <a href="#ab332f9d2f6fb953b3090477a0a5d30d1">MDNodeKeyImpl</a> and <a href="#aa57fde8c76036c875f262f50f37b1a67">MDNodeKeyImpl</a>.</p>

</div>
</div>

### File {#ad2b9f478903971fe37039875e2bd604c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Metadata* llvm::MDNodeKeyImpl&lt; DIGlobalVariable &gt;::File</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1078 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>


<p>Referenced by <a href="#ac46adc0df0d92d4d54d4711a0d5f2a2e">getHashValue</a>, <a href="#a530ff5f1c95d9a06172a875dd401bc40">isKeyOf</a>, <a href="#ab332f9d2f6fb953b3090477a0a5d30d1">MDNodeKeyImpl</a> and <a href="#aa57fde8c76036c875f262f50f37b1a67">MDNodeKeyImpl</a>.</p>

</div>
</div>

### IsDefinition {#a51239438a7ac84edc6af7f3518d9af52}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MDNodeKeyImpl&lt; DIGlobalVariable &gt;::IsDefinition</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1082 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>


<p>Referenced by <a href="#ac46adc0df0d92d4d54d4711a0d5f2a2e">getHashValue</a>, <a href="#a530ff5f1c95d9a06172a875dd401bc40">isKeyOf</a>, <a href="#ab332f9d2f6fb953b3090477a0a5d30d1">MDNodeKeyImpl</a> and <a href="#aa57fde8c76036c875f262f50f37b1a67">MDNodeKeyImpl</a>.</p>

</div>
</div>

### IsLocalToUnit {#a39fbc427432bee8a137772d77c5ed954}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MDNodeKeyImpl&lt; DIGlobalVariable &gt;::IsLocalToUnit</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1081 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>


<p>Referenced by <a href="#ac46adc0df0d92d4d54d4711a0d5f2a2e">getHashValue</a>, <a href="#a530ff5f1c95d9a06172a875dd401bc40">isKeyOf</a>, <a href="#ab332f9d2f6fb953b3090477a0a5d30d1">MDNodeKeyImpl</a> and <a href="#aa57fde8c76036c875f262f50f37b1a67">MDNodeKeyImpl</a>.</p>

</div>
</div>

### Line {#a800c2820f4a56ecbf67cb684cb6ddefb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MDNodeKeyImpl&lt; DIGlobalVariable &gt;::Line</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1079 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>


<p>Referenced by <a href="#ac46adc0df0d92d4d54d4711a0d5f2a2e">getHashValue</a>, <a href="#a530ff5f1c95d9a06172a875dd401bc40">isKeyOf</a>, <a href="#ab332f9d2f6fb953b3090477a0a5d30d1">MDNodeKeyImpl</a> and <a href="#aa57fde8c76036c875f262f50f37b1a67">MDNodeKeyImpl</a>.</p>

</div>
</div>

### LinkageName {#a3dfa8fa5f24c6037d7dcfc0925dcfd10}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MDString* llvm::MDNodeKeyImpl&lt; DIGlobalVariable &gt;::LinkageName</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1077 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>


<p>Referenced by <a href="#ac46adc0df0d92d4d54d4711a0d5f2a2e">getHashValue</a>, <a href="#a530ff5f1c95d9a06172a875dd401bc40">isKeyOf</a>, <a href="#ab332f9d2f6fb953b3090477a0a5d30d1">MDNodeKeyImpl</a> and <a href="#aa57fde8c76036c875f262f50f37b1a67">MDNodeKeyImpl</a>.</p>

</div>
</div>

### Name {#a5101d356db9b35567e2fac05a879e6d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MDString* llvm::MDNodeKeyImpl&lt; DIGlobalVariable &gt;::Name</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1076 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>


<p>Referenced by <a href="#ac46adc0df0d92d4d54d4711a0d5f2a2e">getHashValue</a>, <a href="#a530ff5f1c95d9a06172a875dd401bc40">isKeyOf</a>, <a href="#ab332f9d2f6fb953b3090477a0a5d30d1">MDNodeKeyImpl</a> and <a href="#aa57fde8c76036c875f262f50f37b1a67">MDNodeKeyImpl</a>.</p>

</div>
</div>

### Scope {#a542f1d054282167867ba94de57b9b4cf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Metadata* llvm::MDNodeKeyImpl&lt; DIGlobalVariable &gt;::Scope</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1075 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>


<p>Referenced by <a href="#ac46adc0df0d92d4d54d4711a0d5f2a2e">getHashValue</a>, <a href="#a530ff5f1c95d9a06172a875dd401bc40">isKeyOf</a>, <a href="#ab332f9d2f6fb953b3090477a0a5d30d1">MDNodeKeyImpl</a> and <a href="#aa57fde8c76036c875f262f50f37b1a67">MDNodeKeyImpl</a>.</p>

</div>
</div>

### StaticDataMemberDeclaration {#a15f08a035b08ff0c2bcbe671e28ce722}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Metadata* llvm::MDNodeKeyImpl&lt; DIGlobalVariable &gt;::StaticDataMemberDeclaration</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1083 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>


<p>Referenced by <a href="#ac46adc0df0d92d4d54d4711a0d5f2a2e">getHashValue</a>, <a href="#a530ff5f1c95d9a06172a875dd401bc40">isKeyOf</a>, <a href="#ab332f9d2f6fb953b3090477a0a5d30d1">MDNodeKeyImpl</a> and <a href="#aa57fde8c76036c875f262f50f37b1a67">MDNodeKeyImpl</a>.</p>

</div>
</div>

### TemplateParams {#a753c39ef5571d20f25d541d8cf27acfd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Metadata* llvm::MDNodeKeyImpl&lt; DIGlobalVariable &gt;::TemplateParams</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1084 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>


<p>Referenced by <a href="#a530ff5f1c95d9a06172a875dd401bc40">isKeyOf</a>, <a href="#ab332f9d2f6fb953b3090477a0a5d30d1">MDNodeKeyImpl</a> and <a href="#aa57fde8c76036c875f262f50f37b1a67">MDNodeKeyImpl</a>.</p>

</div>
</div>

### Type {#a1ec5509d26a316c37b6927cf6ce89242}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Metadata* llvm::MDNodeKeyImpl&lt; DIGlobalVariable &gt;::Type</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1080 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>


<p>Referenced by <a href="#ac46adc0df0d92d4d54d4711a0d5f2a2e">getHashValue</a>, <a href="#a530ff5f1c95d9a06172a875dd401bc40">isKeyOf</a>, <a href="#ab332f9d2f6fb953b3090477a0a5d30d1">MDNodeKeyImpl</a> and <a href="#aa57fde8c76036c875f262f50f37b1a67">MDNodeKeyImpl</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>

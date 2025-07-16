---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/groups/llvmcsupporttypes
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - group

---

<div class="doxyPage">

# The Types and Enumerations Reference



## Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">int <a href="#ga209de0bceb13179a973c6a45211617bd">LLVMBool</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">struct LLVMOpaqueMemoryBuffer * <a href="#ga9867eaa7b17ba17405cdf2539bedb108">LLVMMemoryBufferRef</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>LLVM uses a polymorphic type hierarchy which C cannot represent, therefore parameters must be passed as base types. <a href="#ga9867eaa7b17ba17405cdf2539bedb108">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">struct LLVMOpaqueContext * <a href="#ga9c43e01525516ff6b4feab5166c5b1da">LLVMContextRef</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The top-level container for all LLVM global data. <a href="#ga9c43e01525516ff6b4feab5166c5b1da">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">struct LLVMOpaqueModule * <a href="#gad1d1bb5f901c903a0cf09c5a053c9c56">LLVMModuleRef</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The top-level container for all other LLVM Intermediate Representation (IR) objects. <a href="#gad1d1bb5f901c903a0cf09c5a053c9c56">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">struct LLVMOpaqueType * <a href="#gab81b4df33167d47174f9b86a75e3be88">LLVMTypeRef</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Each value in the LLVM IR has a type, an <a href="#gab81b4df33167d47174f9b86a75e3be88">LLVMTypeRef</a>. <a href="#gab81b4df33167d47174f9b86a75e3be88">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">struct LLVMOpaqueValue * <a href="#ga113ce952344691b8304a43a314f8be17">LLVMValueRef</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Represents an individual value in LLVM IR. <a href="#ga113ce952344691b8304a43a314f8be17">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">struct LLVMOpaqueBasicBlock * <a href="#gab57bd16a0147aad5c492a0d97e0df8a9">LLVMBasicBlockRef</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Represents a basic block of instructions in LLVM IR. <a href="#gab57bd16a0147aad5c492a0d97e0df8a9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">struct LLVMOpaqueMetadata * <a href="#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Represents an LLVM Metadata. <a href="#gab9f52d9777af781812e7bffdd491d01e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">struct LLVMOpaqueNamedMDNode * <a href="#ga348dc6ce48243a524ee3937ef2d8ca29">LLVMNamedMDNodeRef</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Represents an LLVM Named Metadata <a href="/web-llvm/docs/api/classes/node">Node</a>. <a href="#ga348dc6ce48243a524ee3937ef2d8ca29">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">struct <a href="/web-llvm/docs/api/structs/llvmopaquevaluemetadataentry">LLVMOpaqueValueMetadataEntry</a> <a href="#ga90f27fb45c9b3bee49f90809035a2ab9">LLVMValueMetadataEntry</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Represents an entry in a Global Object's metadata attachments. <a href="#ga90f27fb45c9b3bee49f90809035a2ab9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">struct LLVMOpaqueBuilder * <a href="#gab13eecdec39366f9974f865d68011775">LLVMBuilderRef</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Represents an LLVM basic block builder. <a href="#gab13eecdec39366f9974f865d68011775">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">struct LLVMOpaqueDIBuilder * <a href="#gae7276221889549b4cf3b3f2297a8333e">LLVMDIBuilderRef</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Represents an LLVM debug info builder. <a href="#gae7276221889549b4cf3b3f2297a8333e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">struct LLVMOpaqueModuleProvider * <a href="#gad77f13d71e9aebc385324cde314d9ac6">LLVMModuleProviderRef</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Interface used to provide a module to JIT or interpreter. <a href="#gad77f13d71e9aebc385324cde314d9ac6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">struct LLVMOpaquePassManager * <a href="#ga45fccfac9832f829c5e12a8915e85f4c">LLVMPassManagerRef</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">struct LLVMOpaqueUse * <a href="#gab30423fe4582af30d65061fddc7398d7">LLVMUseRef</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Used to get the users and usees of a Value. <a href="#gab30423fe4582af30d65061fddc7398d7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">struct LLVMOpaqueOperandBundle * <a href="#gafe96c433ce9154bebe8fd83e0616d495">LLVMOperandBundleRef</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">struct LLVMOpaqueAttributeRef * <a href="#ga17bcea87da25c658e082bec6009c6f88">LLVMAttributeRef</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Used to represent an attributes. <a href="#ga17bcea87da25c658e082bec6009c6f88">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">struct LLVMOpaqueDiagnosticInfo * <a href="#ga85de47e6bca94e27592f9161dd38dff5">LLVMDiagnosticInfoRef</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">struct LLVMComdat * <a href="#gaa91542000fd23d2eeebf64a25bdc66b3">LLVMComdatRef</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">struct <a href="/web-llvm/docs/api/structs/llvmopaquemoduleflagentry">LLVMOpaqueModuleFlagEntry</a> <a href="#ga2582ca8c28f123476fb606097b475ed6">LLVMModuleFlagEntry</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">struct LLVMOpaqueJITEventListener * <a href="#gad4bf262b53178061f7b936e3d1ff43bf">LLVMJITEventListenerRef</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">struct LLVMOpaqueBinary * <a href="#ga7b146c3251529961e8eeda888adac209">LLVMBinaryRef</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">struct LLVMOpaqueDbgRecord * <a href="#ga54eadb23779a7b2538b9a7b03d9c2630">LLVMDbgRecordRef</a></td>
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


<div class="doxySectionDef">

## Typedefs

### LLVMAttributeRef {#ga17bcea87da25c658e082bec6009c6f88}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef struct LLVMOpaqueAttributeRef* LLVMAttributeRef</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Used to represent an attributes.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="/web-llvm/docs/api/classes/llvm/attribute">llvm::Attribute</a></p></dd>
</dl>


<p>Definition at line 145 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/types-h">Types.h</a>.</p>

</div>
</div>

### LLVMBasicBlockRef {#gab57bd16a0147aad5c492a0d97e0df8a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef struct LLVMOpaqueBasicBlock* LLVMBasicBlockRef</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Represents a basic block of instructions in LLVM IR.</p>


<p>This models <a href="/web-llvm/docs/api/classes/llvm/basicblock">llvm::BasicBlock</a>.</p>


<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/types-h">Types.h</a>.</p>

</div>
</div>

### LLVMBinaryRef {#ga7b146c3251529961e8eeda888adac209}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef struct LLVMOpaqueBinary* LLVMBinaryRef</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="/web-llvm/docs/api/classes/llvm/object/binary">llvm::object::Binary</a></p></dd>
</dl>


<p>Definition at line 170 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/types-h">Types.h</a>.</p>

</div>
</div>

### LLVMBool {#ga209de0bceb13179a973c6a45211617bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef int LLVMBool</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 28 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/types-h">Types.h</a>.</p>

</div>
</div>

### LLVMBuilderRef {#gab13eecdec39366f9974f865d68011775}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef struct LLVMOpaqueBuilder* LLVMBuilderRef</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Represents an LLVM basic block builder.</p>


<p>This models <a href="/web-llvm/docs/api/classes/llvm/irbuilder">llvm::IRBuilder</a>.</p>


<p>Definition at line 110 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/types-h">Types.h</a>.</p>

</div>
</div>

### LLVMComdatRef {#gaa91542000fd23d2eeebf64a25bdc66b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef struct LLVMComdat* LLVMComdatRef</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="/web-llvm/docs/api/classes/llvm/comdat">llvm::Comdat</a></p></dd>
</dl>


<p>Definition at line 155 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/types-h">Types.h</a>.</p>

</div>
</div>

### LLVMContextRef {#ga9c43e01525516ff6b4feab5166c5b1da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef struct LLVMOpaqueContext* LLVMContextRef</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The top-level container for all LLVM global data.</p>


<p>See the LLVMContext class.</p>


<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/types-h">Types.h</a>.</p>

</div>
</div>

### LLVMDbgRecordRef {#ga54eadb23779a7b2538b9a7b03d9c2630}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef struct LLVMOpaqueDbgRecord* LLVMDbgRecordRef</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="/web-llvm/docs/api/classes/llvm/dbgrecord">llvm::DbgRecord</a></p></dd>
</dl>


<p>Definition at line 175 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/types-h">Types.h</a>.</p>

</div>
</div>

### LLVMDiagnosticInfoRef {#ga85de47e6bca94e27592f9161dd38dff5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef struct LLVMOpaqueDiagnosticInfo* LLVMDiagnosticInfoRef</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="/web-llvm/docs/api/classes/llvm/diagnosticinfo">llvm::DiagnosticInfo</a></p></dd>
</dl>


<p>Definition at line 150 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/types-h">Types.h</a>.</p>

</div>
</div>

### LLVMDIBuilderRef {#gae7276221889549b4cf3b3f2297a8333e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef struct LLVMOpaqueDIBuilder* LLVMDIBuilderRef</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Represents an LLVM debug info builder.</p>


<p>This models <a href="/web-llvm/docs/api/classes/llvm/dibuilder">llvm::DIBuilder</a>.</p>


<p>Definition at line 117 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/types-h">Types.h</a>.</p>

</div>
</div>

### LLVMJITEventListenerRef {#gad4bf262b53178061f7b936e3d1ff43bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef struct LLVMOpaqueJITEventListener* LLVMJITEventListenerRef</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="/web-llvm/docs/api/classes/llvm/jiteventlistener">llvm::JITEventListener</a></p></dd>
</dl>


<p>Definition at line 165 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/types-h">Types.h</a>.</p>

</div>
</div>

### LLVMMemoryBufferRef {#ga9867eaa7b17ba17405cdf2539bedb108}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef struct LLVMOpaqueMemoryBuffer* LLVMMemoryBufferRef</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>LLVM uses a polymorphic type hierarchy which C cannot represent, therefore parameters must be passed as base types.</p>


<p>Despite the declared types, most of the functions provided operate only on branches of the type hierarchy. The declared parameter names are descriptive and specify which type is required. Additionally, each type hierarchy is documented along with the functions that operate upon it. For more detail, refer to LLVM's C++ code. If in doubt, refer to Core.cpp, which performs parameter downcasts in the form unwrap&lt;RequiredType&gt;(Param). Used to pass regions of memory through LLVM interfaces.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="/web-llvm/docs/api/classes/llvm/memorybuffer">llvm::MemoryBuffer</a></p></dd>
</dl>


<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/types-h">Types.h</a>.</p>

</div>
</div>

### LLVMMetadataRef {#gab9f52d9777af781812e7bffdd491d01e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef struct LLVMOpaqueMetadata* LLVMMetadataRef</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Represents an LLVM Metadata.</p>


<p>This models <a href="/web-llvm/docs/api/classes/llvm/metadata">llvm::Metadata</a>.</p>


<p>Definition at line 89 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/types-h">Types.h</a>.</p>

</div>
</div>

### LLVMModuleFlagEntry {#ga2582ca8c28f123476fb606097b475ed6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef struct LLVMOpaqueModuleFlagEntry LLVMModuleFlagEntry</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="/web-llvm/docs/api/structs/llvm/module/moduleflagentry">llvm::Module::ModuleFlagEntry</a></p></dd>
</dl>


<p>Definition at line 160 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/types-h">Types.h</a>.</p>

</div>
</div>

### LLVMModuleProviderRef {#gad77f13d71e9aebc385324cde314d9ac6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef struct LLVMOpaqueModuleProvider* LLVMModuleProviderRef</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Interface used to provide a module to JIT or interpreter.</p>


<p>This is now just a synonym for <a href="/web-llvm/docs/api/classes/llvm/module">llvm::Module</a>, but we have to keep using the different type to keep binary compatibility.</p>


<p>Definition at line 124 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/types-h">Types.h</a>.</p>

</div>
</div>

### LLVMModuleRef {#gad1d1bb5f901c903a0cf09c5a053c9c56}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef struct LLVMOpaqueModule* LLVMModuleRef</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The top-level container for all other LLVM Intermediate Representation (IR) objects.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="/web-llvm/docs/api/classes/llvm/module">llvm::Module</a></p></dd>
</dl>


<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/types-h">Types.h</a>.</p>

</div>
</div>

### LLVMNamedMDNodeRef {#ga348dc6ce48243a524ee3937ef2d8ca29}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef struct LLVMOpaqueNamedMDNode* LLVMNamedMDNodeRef</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Represents an LLVM Named Metadata <a href="/web-llvm/docs/api/classes/node">Node</a>.</p>


<p>This models <a href="/web-llvm/docs/api/classes/llvm/namedmdnode">llvm::NamedMDNode</a>.</p>


<p>Definition at line 96 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/types-h">Types.h</a>.</p>

</div>
</div>

### LLVMOperandBundleRef {#gafe96c433ce9154bebe8fd83e0616d495}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef struct LLVMOpaqueOperandBundle* LLVMOperandBundleRef</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="/web-llvm/docs/api/namespaces/llvm/#aa97c65466bdd34abda6772dd32eb5d19">llvm::OperandBundleDef</a></p></dd>
</dl>


<p>Definition at line 138 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/types-h">Types.h</a>.</p>

</div>
</div>

### LLVMPassManagerRef {#ga45fccfac9832f829c5e12a8915e85f4c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef struct LLVMOpaquePassManager* LLVMPassManagerRef</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="/web-llvm/docs/api/classes/llvm/passmanagerbase">llvm::PassManagerBase</a></p></dd>
</dl>


<p>Definition at line 127 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/types-h">Types.h</a>.</p>

</div>
</div>

### LLVMTypeRef {#gab81b4df33167d47174f9b86a75e3be88}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef struct LLVMOpaqueType* LLVMTypeRef</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Each value in the LLVM IR has a type, an <a href="#gab81b4df33167d47174f9b86a75e3be88">LLVMTypeRef</a>.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="/web-llvm/docs/api/classes/llvm/type">llvm::Type</a></p></dd>
</dl>


<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/types-h">Types.h</a>.</p>

</div>
</div>

### LLVMUseRef {#gab30423fe4582af30d65061fddc7398d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef struct LLVMOpaqueUse* LLVMUseRef</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Used to get the users and usees of a Value.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="/web-llvm/docs/api/classes/llvm/use">llvm::Use</a></p></dd>
</dl>


<p>Definition at line 133 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/types-h">Types.h</a>.</p>

</div>
</div>

### LLVMValueMetadataEntry {#ga90f27fb45c9b3bee49f90809035a2ab9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef struct LLVMOpaqueValueMetadataEntry LLVMValueMetadataEntry</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Represents an entry in a Global Object's metadata attachments.</p>


<p>This models std::pair&lt;unsigned, MDNode *&gt;</p>


<p>Definition at line 103 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/types-h">Types.h</a>.</p>

</div>
</div>

### LLVMValueRef {#ga113ce952344691b8304a43a314f8be17}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef struct LLVMOpaqueValue* LLVMValueRef</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Represents an individual value in LLVM IR.</p>


<p>This models <a href="/web-llvm/docs/api/classes/llvm/value">llvm::Value</a>.</p>


<p>Definition at line 75 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/types-h">Types.h</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>

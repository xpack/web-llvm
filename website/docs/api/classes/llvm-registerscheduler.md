---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/registerscheduler
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `RegisterScheduler` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::RegisterScheduler { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/schedulerregistry-h">llvm/CodeGen/SchedulerRegistry.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinepassregistrynode">MachinePassRegistryNode&lt;PassCtorTy&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/machinepassregistrynode">MachinePassRegistryNode</a> - Machine pass node stored in registration list. <a href="/web-llvm/docs/api/classes/llvm/machinepassregistrynode/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8fdd27818bcec505142aad630a5f05bf">FunctionPassCtor</a> = <a href="/web-llvm/docs/api/classes/llvm/scheduledagsdnodes">ScheduleDAGSDNodes</a> *(*)(<a href="/web-llvm/docs/api/classes/llvm/selectiondagisel">SelectionDAGISel</a> *, <a href="/web-llvm/docs/api/namespaces/llvm/#a8ec1bf8d7b792ca9fac56f8514db18d2">CodeGenOptLevel</a>)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa896a0f8a4e3c9084fd9bd98577ef34b">RegisterScheduler</a> (const char *N, const char *D, FunctionPassCtor C)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a15382ff57fe459b11d1c08073177622c">~RegisterScheduler</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/registerscheduler">RegisterScheduler</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf7a3932d58cacc49d521b6e2f4153d7">getNext</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/registerscheduler">RegisterScheduler</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4ccf5daacea1f1cc1f0fe3d3233695e2">getList</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a945757e1ca1efe9fe46628e4efe97f41">setListener</a> (MachinePassRegistryListener&lt; FunctionPassCtor &gt; *L)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/machinepassregistry">MachinePassRegistry</a>&lt; <a href="#a8fdd27818bcec505142aad630a5f05bf">FunctionPassCtor</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac631c78e715470b5dc24f873d2829a9b">Registry</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/registerscheduler">RegisterScheduler</a> class - Track the registration of instruction schedulers. <a href="#ac631c78e715470b5dc24f873d2829a9b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 31 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/schedulerregistry-h">SchedulerRegistry.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### FunctionPassCtor {#a8fdd27818bcec505142aad630a5f05bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::RegisterScheduler::FunctionPassCtor =  ScheduleDAGSDNodes *(*)(SelectionDAGISel *,
                                                   CodeGenOptLevel)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/schedulerregistry-h">SchedulerRegistry.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### RegisterScheduler() {#aa896a0f8a4e3c9084fd9bd98577ef34b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::RegisterScheduler::RegisterScheduler (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * N, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * D, <a href="#a8fdd27818bcec505142aad630a5f05bf">FunctionPassCtor</a> C)</td>
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



<p>Definition at line 40 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/schedulerregistry-h">SchedulerRegistry.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a6a9f043784cf87001c84980afa76da82">D</a>, <a href="/web-llvm/docs/api/classes/llvm/machinepassregistrynode/#a8587f6cac52094711e570462f5fc659d">llvm::MachinePassRegistryNode&lt; ScheduleDAGSDNodes *(*)(SelectionDAGISel *, CodeGenOptLevel)&gt;::MachinePassRegistryNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="#ac631c78e715470b5dc24f873d2829a9b">Registry</a>.</p>


<p>Referenced by <a href="#a4ccf5daacea1f1cc1f0fe3d3233695e2">getList</a> and <a href="#adf7a3932d58cacc49d521b6e2f4153d7">getNext</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~RegisterScheduler() {#a15382ff57fe459b11d1c08073177622c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::RegisterScheduler::~RegisterScheduler ()</td>
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



<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/schedulerregistry-h">SchedulerRegistry.h</a>.</p>


<p>Reference <a href="#ac631c78e715470b5dc24f873d2829a9b">Registry</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getNext() {#adf7a3932d58cacc49d521b6e2f4153d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RegisterScheduler * llvm::RegisterScheduler::getNext ()</td>
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



<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/schedulerregistry-h">SchedulerRegistry.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machinepassregistrynode/#a9230c536c8593b8158fa1d786eb20f9e">llvm::MachinePassRegistryNode&lt; PassCtorTy &gt;::getNext</a> and <a href="#aa896a0f8a4e3c9084fd9bd98577ef34b">RegisterScheduler</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### getList() {#a4ccf5daacea1f1cc1f0fe3d3233695e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RegisterScheduler * llvm::RegisterScheduler::getList ()</td>
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



<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/schedulerregistry-h">SchedulerRegistry.h</a>.</p>


<p>References <a href="#aa896a0f8a4e3c9084fd9bd98577ef34b">RegisterScheduler</a> and <a href="#ac631c78e715470b5dc24f873d2829a9b">Registry</a>.</p>

</div>
</div>

### setListener() {#a945757e1ca1efe9fe46628e4efe97f41}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::RegisterScheduler::setListener (<a href="/web-llvm/docs/api/classes/llvm/machinepassregistrylistener">MachinePassRegistryListener</a>&lt; <a href="#a8fdd27818bcec505142aad630a5f05bf">FunctionPassCtor</a> &gt; * L)</td>
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



<p>Definition at line 56 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/schedulerregistry-h">SchedulerRegistry.h</a>.</p>


<p>Reference <a href="#ac631c78e715470b5dc24f873d2829a9b">Registry</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Attributes

### Registry {#ac631c78e715470b5dc24f873d2829a9b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachinePassRegistry&lt; RegisterScheduler::FunctionPassCtor &gt; RegisterScheduler::Registry</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/registerscheduler">RegisterScheduler</a> class - Track the registration of instruction schedulers.</p>

<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/schedulerregistry-h">SchedulerRegistry.h</a>.</p>


<p>Referenced by <a href="#a4ccf5daacea1f1cc1f0fe3d3233695e2">getList</a>, <a href="#aa896a0f8a4e3c9084fd9bd98577ef34b">RegisterScheduler</a>, <a href="#a945757e1ca1efe9fe46628e4efe97f41">setListener</a> and <a href="#a15382ff57fe459b11d1c08073177622c">~RegisterScheduler</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/schedulerregistry-h">SchedulerRegistry.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>

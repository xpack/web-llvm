---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/moduleslottracker
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `ModuleSlotTracker` Class Reference

<p>Manage lifetime of a slot tracker for printing IR. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::ModuleSlotTracker { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/moduleslottracker-h">llvm/IR/ModuleSlotTracker.h</a>"
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinemoduleslottracker">MachineModuleSlotTracker</a></td>
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

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6aef0029425988cbe468cf78bf898bdb">MachineMDNodeListType</a> = std::vector&lt; std::pair&lt; unsigned, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> * &gt; &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2151720842982c4facf057f92f5ec500">ModuleSlotTracker</a> (SlotTracker &amp;Machine, const Module *M, const Function *F=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Wrap a preinitialized <a href="/web-llvm/docs/api/classes/llvm/slottracker">SlotTracker</a>. <a href="#a2151720842982c4facf057f92f5ec500">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3a3c5926b6c7c2143f52447c7ab857c0">ModuleSlotTracker</a> (const Module *M, bool ShouldInitializeAllMetadata=true)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct a slot tracker from a module. <a href="#a3a3c5926b6c7c2143f52447c7ab857c0">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4cc0ed33b85b9be27c95187d1473be9c">~ModuleSlotTracker</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Destructor to clean up storage. <a href="#a4cc0ed33b85b9be27c95187d1473be9c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/slottracker">SlotTracker</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a802b848d702c132a97b3da454c1e68c1">getMachine</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Lazily creates a slot tracker. <a href="#a802b848d702c132a97b3da454c1e68c1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a12bf76af836ffe2d2e00435a3f0861e9">getModule</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8d3ee14bd6234e0fa0b97c19df3882ce">getCurrentFunction</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ace93d877ff9298d25a15e2a32f765653">incorporateFunction</a> (const Function &amp;F)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Incorporate the given function. <a href="#ace93d877ff9298d25a15e2a32f765653">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6d82623735b3bd2208170d379913f2e1">getLocalSlot</a> (const Value *V)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the slot number of the specified local value. <a href="#a6d82623735b3bd2208170d379913f2e1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa61b8a507ee7183bce9f0656efd5d492">setProcessHook</a> (std::function&lt; void(AbstractSlotTrackerStorage *, const Module *, bool)&gt;)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae7d8cde0e0627fbb4cfbebd0592d5b37">setProcessHook</a> (std::function&lt; void(AbstractSlotTrackerStorage *, const Function *, bool)&gt;)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ee16368586349a8a3d889fd848a0a39">collectMDNodes</a> (MachineMDNodeListType &amp;L, unsigned LB, unsigned UB) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/slottracker">SlotTracker</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aad2da497dc003e57f75e0cf524710288">MachineStorage</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Storage for a slot tracker. <a href="#aad2da497dc003e57f75e0cf524710288">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abea76c04f95ea50b3d523461ba05d1bf">ShouldCreateStorage</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad31eee7107990653064392bac62cd49a">ShouldInitializeAllMetadata</a> = false</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af4cc5cfca3dd35a2357986c1fd347acd">M</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c2f795c67e1c979681085ccdbdabc08">F</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/slottracker">SlotTracker</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaae71ff7948f284e6f90b0560233352d">Machine</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::function&lt; void(<a href="/web-llvm/docs/api/classes/llvm/abstractslottrackerstorage">AbstractSlotTrackerStorage</a> *, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> *, bool)&gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae4a5b5b9bb4554296b46066df8483b93">ProcessModuleHookFn</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::function&lt; void(<a href="/web-llvm/docs/api/classes/llvm/abstractslottrackerstorage">AbstractSlotTrackerStorage</a> *, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *, bool)&gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a81db38e3805dbaedbbecaf53ad6d2dc7">ProcessFunctionHookFn</a></td>
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

<p>Manage lifetime of a slot tracker for printing IR.</p>


<p>Wrapper around the <em><a href="/web-llvm/docs/api/classes/llvm/slottracker">SlotTracker</a></em> used internally by <em>AsmWriter</em>. This class allows callers to share the cost of incorporating the metadata in a module or a function.</p>


<p>If the IR changes from underneath <em><a href="/web-llvm/docs/api/classes/llvm/moduleslottracker">ModuleSlotTracker</a></em>, strings like "&lt;badref&gt;" will be printed, or, worse, the wrong slots entirely.</p>


<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/moduleslottracker-h">ModuleSlotTracker.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### MachineMDNodeListType {#a6aef0029425988cbe468cf78bf898bdb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::ModuleSlotTracker::MachineMDNodeListType = 
      std::vector&lt;std::pair&lt;unsigned, const MDNode *&gt;&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 101 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/moduleslottracker-h">ModuleSlotTracker.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### ModuleSlotTracker() {#a2151720842982c4facf057f92f5ec500}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ModuleSlotTracker::ModuleSlotTracker (<a href="/web-llvm/docs/api/classes/llvm/slottracker">SlotTracker</a> &amp; Machine, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> * M, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * F=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Wrap a preinitialized <a href="/web-llvm/docs/api/classes/llvm/slottracker">SlotTracker</a>.</p>

<p>Declaration at line 61 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/moduleslottracker-h">ModuleSlotTracker.h</a>, definition at line 878 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/machinemoduleslottracker/#ad46f7561b1384a882cfabf8ef2b7326c">llvm::MachineModuleSlotTracker::MachineModuleSlotTracker</a>.</p>

</div>
</div>

### ModuleSlotTracker() {#a3a3c5926b6c7c2143f52447c7ab857c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ModuleSlotTracker::ModuleSlotTracker (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> * M, bool ShouldInitializeAllMetadata=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel explicit">explicit</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Construct a slot tracker from a module.</p>


<p>If <em>M</em> is <span class="doxyComputerOutput">nullptr</span>, uses a null slot tracker. Otherwise, initializes a slot tracker, and initializes all metadata slots. <span class="doxyComputerOutput">ShouldInitializeAllMetadata</span> defaults to true because this is expected to be shared between multiple callers, and otherwise <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> references will not match up.</p>


<p>Declaration at line 71 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/moduleslottracker-h">ModuleSlotTracker.h</a>, definition at line 882 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~ModuleSlotTracker() {#a4cc0ed33b85b9be27c95187d1473be9c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ModuleSlotTracker::~ModuleSlotTracker ()</td>
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

<p>Destructor to clean up storage.</p>

<p>Definition at line 75 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/moduleslottracker-h">ModuleSlotTracker.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### collectMDNodes() {#a7ee16368586349a8a3d889fd848a0a39}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ModuleSlotTracker::collectMDNodes (<a href="#a6aef0029425988cbe468cf78bf898bdb">MachineMDNodeListType</a> &amp; L, unsigned LB, unsigned UB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 104 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/moduleslottracker-h">ModuleSlotTracker.h</a>, definition at line 5290 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/machinemoduleslottracker/#aac196d286114a87387bcd505f13c5d6b">llvm::MachineModuleSlotTracker::collectMachineMDNodes</a>.</p>

</div>
</div>

### getCurrentFunction() {#a8d3ee14bd6234e0fa0b97c19df3882ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Function * llvm::ModuleSlotTracker::getCurrentFunction ()</td>
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



<p>Definition at line 81 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/moduleslottracker-h">ModuleSlotTracker.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineoperand-cpp/#a39e0c396e9ae881eddc29a02ebc40956">printIRBlockReference</a> and <a href="/web-llvm/docs/api/classes/llvm/mirformatter/#afe314b6a6d04121d7d8bf9f8ad80605b">llvm::MIRFormatter::printIRValue</a>.</p>

</div>
</div>

### getLocalSlot() {#a6d82623735b3bd2208170d379913f2e1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int ModuleSlotTracker::getLocalSlot (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the slot number of the specified local value.</p>


<p>A function that defines this value should be incorporated prior to calling this method. Return -1 if the value is not in the function's <a href="/web-llvm/docs/api/classes/llvm/slottracker">SlotTracker</a>.</p>


<p>Declaration at line 94 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/moduleslottracker-h">ModuleSlotTracker.h</a>, definition at line 918 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-materializationutils-cpp-/rematgraph/#a336028d6f8b409a071169b09e0b5e666">anonymous{MaterializationUtils.cpp}::RematGraph::dumpBasicBlockLabel</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3fa67a76e6081ca187d962c197c6445d">llvm::dumpBasicBlockLabel</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp/#a7f576cc3f7bb44e5805aeeb0d82164b5">initSlots2BasicBlocks</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp/#a66351a01a19b57477b3754c3b19015e4">mapValueToSlot</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineoperand-cpp/#a39e0c396e9ae881eddc29a02ebc40956">printIRBlockReference</a>, <a href="/web-llvm/docs/api/classes/llvm/mirformatter/#afe314b6a6d04121d7d8bf9f8ad80605b">llvm::MIRFormatter::printIRValue</a> and <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#adad68dd11c1995cc4f63e51986f50ce0">llvm::MachineBasicBlock::printName</a>.</p>

</div>
</div>

### getMachine() {#a802b848d702c132a97b3da454c1e68c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SlotTracker * ModuleSlotTracker::getMachine ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Lazily creates a slot tracker.</p>

<p>Declaration at line 78 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/moduleslottracker-h">ModuleSlotTracker.h</a>, definition at line 889 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>Referenced by <a href="#ace93d877ff9298d25a15e2a32f765653">incorporateFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/dbglabelrecord/#af01d77795bb3f385853944a0fb4dbc40">llvm::DbgLabelRecord::print</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgmarker/#ad24a1b510b43c0dc48de0d37e6fff061">llvm::DbgMarker::print</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgvariablerecord/#ad64862991023c01b0515a7d29716e6ad">llvm::DbgVariableRecord::print</a>, <a href="/web-llvm/docs/api/classes/llvm/namedmdnode/#a267435660ce6b53b9d83d84f8f257241">llvm::NamedMDNode::print</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a7ba690234245eaba66ec19c429aaa7b3">llvm::Value::print</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a71c852fe821d8efa8a9cb0c359380ac7">llvm::Value::printAsOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#a7cb3001e93d2e932542f82696da1ca4e">printAsOperandImpl</a> and <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#a2c3485cc2e63a9ea902dccf6dc02a555">printMetadataImpl</a>.</p>

</div>
</div>

### getModule() {#a12bf76af836ffe2d2e00435a3f0861e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Module * llvm::ModuleSlotTracker::getModule ()</td>
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



<p>Definition at line 80 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/moduleslottracker-h">ModuleSlotTracker.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/value/#a71c852fe821d8efa8a9cb0c359380ac7">llvm::Value::printAsOperand</a> and <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#a7cb3001e93d2e932542f82696da1ca4e">printAsOperandImpl</a>.</p>

</div>
</div>

### incorporateFunction() {#ace93d877ff9298d25a15e2a32f765653}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ModuleSlotTracker::incorporateFunction (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Incorporate the given function.</p>


<p>Purge the currently incorporated function and incorporate <span class="doxyComputerOutput">F</span>. If <span class="doxyComputerOutput">F</span> is currently incorporated, this is a no-op.</p>


<p>Declaration at line 87 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/moduleslottracker-h">ModuleSlotTracker.h</a>, definition at line 904 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>Reference <a href="#a802b848d702c132a97b3da454c1e68c1">getMachine</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-materializationutils-cpp-/rematgraph/#ad14f78f54885b535974264a556bcfa05">anonymous{MaterializationUtils.cpp}::RematGraph::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/suspendcrossinginfo/#ae0841bca835cfc99fa124abaca92ea47">llvm::SuspendCrossingInfo::dump</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp/#a7f576cc3f7bb44e5805aeeb0d82164b5">initSlots2BasicBlocks</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp/#a2845d82e260f8f8c9e8d5bc349214fec">initSlots2Values</a>, <a href="/web-llvm/docs/api/classes/llvm/dbglabelrecord/#af01d77795bb3f385853944a0fb4dbc40">llvm::DbgLabelRecord::print</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgmarker/#ad24a1b510b43c0dc48de0d37e6fff061">llvm::DbgMarker::print</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgvariablerecord/#ad64862991023c01b0515a7d29716e6ad">llvm::DbgVariableRecord::print</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ab3b62258d9bd41595674de878f37f8d8">llvm::MachineBasicBlock::print</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ad9c9c8915579c517eff56e638c1a643c">llvm::MachineFunction::print</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ab419785650ef9728b5305d220179017c">llvm::MachineInstr::print</a>, <a href="/web-llvm/docs/api/classes/llvm/mirprinter/#aad72f291464c14665189a84050f38376">llvm::MIRPrinter::print</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a7ba690234245eaba66ec19c429aaa7b3">llvm::Value::print</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineoperand-cpp/#a39e0c396e9ae881eddc29a02ebc40956">printIRBlockReference</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagdumper-cpp/#ace21909c26dd090286cc93b20b5a3cc4">printMemOperand</a> and <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#adad68dd11c1995cc4f63e51986f50ce0">llvm::MachineBasicBlock::printName</a>.</p>

</div>
</div>

### setProcessHook() {#aa61b8a507ee7183bce9f0656efd5d492}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ModuleSlotTracker::setProcessHook (std::function&lt; void(<a href="/web-llvm/docs/api/classes/llvm/abstractslottrackerstorage">AbstractSlotTrackerStorage</a> *, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> *, bool)&gt; Fn)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 96 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/moduleslottracker-h">ModuleSlotTracker.h</a>, definition at line 923 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/machinemoduleslottracker/#ad46f7561b1384a882cfabf8ef2b7326c">llvm::MachineModuleSlotTracker::MachineModuleSlotTracker</a>.</p>

</div>
</div>

### setProcessHook() {#ae7d8cde0e0627fbb4cfbebd0592d5b37}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ModuleSlotTracker::setProcessHook (std::function&lt; void(<a href="/web-llvm/docs/api/classes/llvm/abstractslottrackerstorage">AbstractSlotTrackerStorage</a> *, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *, bool)&gt; Fn)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 98 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/moduleslottracker-h">ModuleSlotTracker.h</a>, definition at line 929 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### F {#a0c2f795c67e1c979681085ccdbdabc08}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Function* llvm::ModuleSlotTracker::F = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/moduleslottracker-h">ModuleSlotTracker.h</a>.</p>

</div>
</div>

### M {#af4cc5cfca3dd35a2357986c1fd347acd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Module* llvm::ModuleSlotTracker::M = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/moduleslottracker-h">ModuleSlotTracker.h</a>.</p>

</div>
</div>

### Machine {#aaae71ff7948f284e6f90b0560233352d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SlotTracker* llvm::ModuleSlotTracker::Machine = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/moduleslottracker-h">ModuleSlotTracker.h</a>.</p>

</div>
</div>

### MachineStorage {#aad2da497dc003e57f75e0cf524710288}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;SlotTracker&gt; llvm::ModuleSlotTracker::MachineStorage</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Storage for a slot tracker.</p>

<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/moduleslottracker-h">ModuleSlotTracker.h</a>.</p>

</div>
</div>

### ProcessFunctionHookFn {#a81db38e3805dbaedbbecaf53ad6d2dc7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::function&lt;void(AbstractSlotTrackerStorage *, const Function *, bool)&gt; llvm::ModuleSlotTracker::ProcessFunctionHookFn</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/moduleslottracker-h">ModuleSlotTracker.h</a>.</p>

</div>
</div>

### ProcessModuleHookFn {#ae4a5b5b9bb4554296b46066df8483b93}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::function&lt;void(AbstractSlotTrackerStorage *, const Module *, bool)&gt; llvm::ModuleSlotTracker::ProcessModuleHookFn</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 55 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/moduleslottracker-h">ModuleSlotTracker.h</a>.</p>

</div>
</div>

### ShouldCreateStorage {#abea76c04f95ea50b3d523461ba05d1bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ModuleSlotTracker::ShouldCreateStorage = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 47 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/moduleslottracker-h">ModuleSlotTracker.h</a>.</p>

</div>
</div>

### ShouldInitializeAllMetadata {#ad31eee7107990653064392bac62cd49a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ModuleSlotTracker::ShouldInitializeAllMetadata = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/moduleslottracker-h">ModuleSlotTracker.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/moduleslottracker-h">ModuleSlotTracker.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>

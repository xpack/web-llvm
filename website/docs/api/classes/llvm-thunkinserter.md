---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/thunkinserter
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `ThunkInserter` Class Template Reference

<p>This class assists in inserting MI thunk functions into the module and rewriting the existing machine functions to call these thunks. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;typename Derived, typename InsertedThunksTy = bool&gt;
class llvm::ThunkInserter&lt;Derived, InsertedThunksTy&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/indirectthunks-h">llvm/CodeGen/IndirectThunks.h</a>"
</div>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Derived, typename InsertedThunksTy = bool&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad580754b469f950b5e7cb2a453f41768">init</a> (Module &amp;M)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Derived, typename InsertedThunksTy = bool&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a547880d64e46c0d922e0bb0f0d7f5fb9">run</a> (MachineModuleInfo &amp;MMI, MachineFunction &amp;MF)</td>
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

## Protected Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Derived, typename InsertedThunksTy = bool&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a1a95b72d4c28ba76251171967da03b01">createThunkFunction</a> (MachineModuleInfo &amp;MMI, StringRef Name, bool Comdat=true, StringRef TargetAttrs="")</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create an empty thunk function. <a href="#a1a95b72d4c28ba76251171967da03b01">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Derived, typename InsertedThunksTy = bool&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a740bcd15c5627326e077787331b1d60a">doInitialization</a> (Module &amp;M)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Initializes thunk inserter. <a href="#a740bcd15c5627326e077787331b1d60a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Derived, typename InsertedThunksTy = bool&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a7d87c609ee113d729a15013e29da1030">getThunkPrefix</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns common prefix for thunk function's names. <a href="#a7d87c609ee113d729a15013e29da1030">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Derived, typename InsertedThunksTy = bool&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a0e76d9a11bcf2f5bb6b8842ae88ebf9e">mayUseThunk</a> (const MachineFunction &amp;MF)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Checks if MF may use thunks (true - maybe, false - definitely not). <a href="#a0e76d9a11bcf2f5bb6b8842ae88ebf9e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Derived, typename InsertedThunksTy = bool&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">InsertedThunksTy</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a1f77fc3ad826da7fc3c13df75da3c8ff">insertThunks</a> (MachineModuleInfo &amp;MMI, MachineFunction &amp;MF, InsertedThunksTy ExistingThunks)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Rewrites the function if necessary, returns the set of thunks added. <a href="#a1f77fc3ad826da7fc3c13df75da3c8ff">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Derived, typename InsertedThunksTy = bool&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad70655ccbb3ff3439dfe9fabddd15625">populateThunk</a> (MachineFunction &amp;MF)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Populate the thunk function with instructions. <a href="#ad70655ccbb3ff3439dfe9fabddd15625">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Derived, typename InsertedThunksTy = bool&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">Derived &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#afe63ca4ad74420bebf6cadbb92b6c327">getDerived</a> ()</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Derived, typename InsertedThunksTy = bool&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">InsertedThunksTy</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af1ca178a0ee2f220f7a8e4b6a1a1209c">InsertedThunks</a></td>
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

<p>This class assists in inserting MI thunk functions into the module and rewriting the existing machine functions to call these thunks.</p>


<p>One of the common cases is implementing security mitigations that involve replacing some machine code patterns with calls to special thunk functions.</p>


<p>Inserting a module pass late in the codegen pipeline may increase memory usage, as it serializes the transformations and forces preceding passes to produce machine code for all functions before running the module pass. For that reason, <a href="/web-llvm/docs/api/classes/llvm/thunkinserter">ThunkInserter</a> can be driven by a <a href="/web-llvm/docs/api/classes/llvm/machinefunctionpass">MachineFunctionPass</a> by passing one <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> at a time to its <span class="doxyComputerOutput">run(MMI, MF)</span> method. Then, the derived class should</p>


<ul class="doxyList ">
<li>call createThunkFunction from its insertThunks method exactly once for each of the thunk functions to be inserted</li>
<li>populate the thunk in its populateThunk method</li>
</ul>

<p>Note that if some other pass is responsible for rewriting the functions, the insertThunks method may simply create all possible thunks at once, probably postponed until the first occurrence of possibly affected MF.</p>


<p>Alternatively, insertThunks method can rewrite MF by itself and only insert the thunks being called. In that case InsertedThunks variable can be used to track which thunks were already inserted.</p>


<p>In any case, the thunk function has to be inserted on behalf of some other function and then populated on its own "iteration" later - this is because <a href="/web-llvm/docs/api/classes/llvm/machinefunctionpass">MachineFunctionPass</a> will see the newly created functions, but they first have to go through the preceding passes from the same pass manager, possibly even through the instruction selector.</p>


<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/indirectthunks-h">IndirectThunks.h</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### init() {#ad580754b469f950b5e7cb2a453f41768}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Derived, typename InsertedThunksTy = bool&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::ThunkInserter&lt; Derived, InsertedThunksTy &gt;::init (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M)</td>
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



<p>Definition at line 110 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/indirectthunks-h">IndirectThunks.h</a>.</p>

</div>
</div>

### run() {#a547880d64e46c0d922e0bb0f0d7f5fb9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Derived, typename InsertedThunksTy = bool&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ThunkInserter&lt; Derived, InsertedThunksTy &gt;::run (<a href="/web-llvm/docs/api/classes/llvm/machinemoduleinfo">MachineModuleInfo</a> &amp; MMI, <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 115 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/indirectthunks-h">IndirectThunks.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3d142c9e7c066059e15232c56dec9e2e">llvm::MachineFunction::getName</a>, <a href="#a7d87c609ee113d729a15013e29da1030">llvm::ThunkInserter&lt; Derived, InsertedThunksTy &gt;::getThunkPrefix</a>, <a href="#a0e76d9a11bcf2f5bb6b8842ae88ebf9e">llvm::ThunkInserter&lt; Derived, InsertedThunksTy &gt;::mayUseThunk</a> and <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2cd8968ff703aaeb395dcd63f6805ff1">llvm::StringRef::starts_with</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### createThunkFunction() {#a1a95b72d4c28ba76251171967da03b01}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Derived, typename InsertedThunksTy = bool&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::ThunkInserter&lt; Derived, InsertedThunksTy &gt;::createThunkFunction (<a href="/web-llvm/docs/api/classes/llvm/machinemoduleinfo">MachineModuleInfo</a> &amp; MMI, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, bool Comdat=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> TargetAttrs="")</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create an empty thunk function.</p>


<p>The new function will eventually be passed to populateThunk. If multiple thunks are created, populateThunk can distinguish them by their names.</p>


<p>Definition at line 77 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/indirectthunks-h">IndirectThunks.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a4a5b798214be930cf8e133c032ba0129">llvm::BasicBlock::Create</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a05d7aedbbdc0fd24e8bc27edfe9c603f">llvm::Function::Create</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aa6536556982b7e6e2e5884e471f3ce6b">llvm::IRBuilderBase::CreateRetVoid</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/functiontype/#af8be7844c269f201ebcee1e15048c378">llvm::FunctionType::get</a>, <a href="/web-llvm/docs/api/classes/llvm/machinemoduleinfo/#a6a05f73ad80e58a532ea879ccc166b66">llvm::MachineModuleInfo::getModule</a>, <a href="/web-llvm/docs/api/classes/llvm/machinemoduleinfo/#a89ccc89e9bd5881953bd1524a0d29f84">llvm::MachineModuleInfo::getOrCreateMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ac1f888bba00f32cb4f9a0010c958f397">llvm::MachineFunction::getProperties</a>, <a href="#a7d87c609ee113d729a15013e29da1030">llvm::ThunkInserter&lt; Derived, InsertedThunksTy &gt;::getThunkPrefix</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a6e20e76960d952de088354cbcd14c3ab">llvm::Type::getVoidTy</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a9141f967188383108a69cc1b8ed3c195a7eade123587a08e674f2ca72e2443771">llvm::GlobalValue::HiddenVisibility</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57ca1511edd03e02d1f3dd277a3c6abf6ad5">llvm::GlobalValue::InternalLinkage</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57caf2b592edf18170e7aff4e8f3bae3360c">llvm::GlobalValue::LinkOnceODRLinkage</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunctionproperties/#ad85237c6c667e4713efe8921e9c32ac1a72f7d830dd5ddb30f06d8e9639558ac3">llvm::MachineFunctionProperties::NoVRegs</a> and <a href="/web-llvm/docs/api/classes/llvm/machinefunctionproperties/#aa7780563d7ca260d0ae67d957b56427f">llvm::MachineFunctionProperties::set</a>.</p>

</div>
</div>

### doInitialization() {#a740bcd15c5627326e077787331b1d60a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Derived, typename InsertedThunksTy = bool&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::ThunkInserter&lt; Derived, InsertedThunksTy &gt;::doInitialization (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Initializes thunk inserter.</p>

<p>Definition at line 87 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/indirectthunks-h">IndirectThunks.h</a>.</p>

</div>
</div>

### getThunkPrefix() {#a7d87c609ee113d729a15013e29da1030}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Derived, typename InsertedThunksTy = bool&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * llvm::ThunkInserter&lt; Derived, InsertedThunksTy &gt;::getThunkPrefix ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns common prefix for thunk function's names.</p>

<p>Definition at line 90 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/indirectthunks-h">IndirectThunks.h</a>.</p>


<p>Referenced by <a href="#a1a95b72d4c28ba76251171967da03b01">llvm::ThunkInserter&lt; Derived, InsertedThunksTy &gt;::createThunkFunction</a> and <a href="#a547880d64e46c0d922e0bb0f0d7f5fb9">llvm::ThunkInserter&lt; Derived, InsertedThunksTy &gt;::run</a>.</p>

</div>
</div>

### insertThunks() {#a1f77fc3ad826da7fc3c13df75da3c8ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Derived, typename InsertedThunksTy = bool&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InsertedThunksTy llvm::ThunkInserter&lt; Derived, InsertedThunksTy &gt;::insertThunks (<a href="/web-llvm/docs/api/classes/llvm/machinemoduleinfo">MachineModuleInfo</a> &amp; MMI, <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, InsertedThunksTy ExistingThunks)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Rewrites the function if necessary, returns the set of thunks added.</p>

<p>Definition at line 96 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/indirectthunks-h">IndirectThunks.h</a>.</p>

</div>
</div>

### mayUseThunk() {#a0e76d9a11bcf2f5bb6b8842ae88ebf9e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Derived, typename InsertedThunksTy = bool&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ThunkInserter&lt; Derived, InsertedThunksTy &gt;::mayUseThunk (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Checks if MF may use thunks (true - maybe, false - definitely not).</p>

<p>Definition at line 93 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/indirectthunks-h">IndirectThunks.h</a>.</p>


<p>Referenced by <a href="#a547880d64e46c0d922e0bb0f0d7f5fb9">llvm::ThunkInserter&lt; Derived, InsertedThunksTy &gt;::run</a>.</p>

</div>
</div>

### populateThunk() {#ad70655ccbb3ff3439dfe9fabddd15625}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Derived, typename InsertedThunksTy = bool&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::ThunkInserter&lt; Derived, InsertedThunksTy &gt;::populateThunk (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Populate the thunk function with instructions.</p>


<p>If multiple thunks are created, the content that must be inserted in the thunk function body should be derived from the MF's name.</p>


<p>Depending on the preceding passes in the pass manager, by the time populateThunk is called, MF may have a few target-specific instructions (such as a single MBB containing the return instruction).</p>


<p>Definition at line 107 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/indirectthunks-h">IndirectThunks.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### getDerived() {#afe63ca4ad74420bebf6cadbb92b6c327}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Derived, typename InsertedThunksTy = bool&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Derived &amp; llvm::ThunkInserter&lt; Derived, InsertedThunksTy &gt;::getDerived ()</td>
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



<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/indirectthunks-h">IndirectThunks.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### InsertedThunks {#af1ca178a0ee2f220f7a8e4b6a1a1209c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Derived, typename InsertedThunksTy = bool&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InsertedThunksTy llvm::ThunkInserter&lt; Derived, InsertedThunksTy &gt;::InsertedThunks</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/indirectthunks-h">IndirectThunks.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/indirectthunks-h">IndirectThunks.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>

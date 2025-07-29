---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-siinserthardclauses-cpp-/siinserthardclauses
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `SIInsertHardClauses` Class



## Declaration

<div class="doxyDeclaration">
class anonymous{SIInsertHardClauses.cpp}::SIInsertHardClauses { ... }
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinefunctionpass">MachineFunctionPass</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/machinefunctionpass">MachineFunctionPass</a> - This class adapts the <a href="/web-llvm/docs/api/classes/llvm/functionpass">FunctionPass</a> interface to allow convenient creation of passes that operate on the <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> representation. <a href="/web-llvm/docs/api/classes/llvm/machinefunctionpass/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf3ebefc71e2c76b471b71ec7ef5d2e7">SIInsertHardClauses</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7bb312e7b09ff030930708b97628fa7f">getAnalysisUsage</a> (AnalysisUsage &amp;AU) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getAnalysisUsage - Subclasses that override getAnalysisUsage must call this. <a href="#a7bb312e7b09ff030930708b97628fa7f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-siinserthardclauses-cpp-/#a05f3bd1f05d10f71d36966379038c069">HardClauseType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a10d3dc29c5b795204cec9fe33433f1cc">getHardClauseType</a> (const MachineInstr &amp;MI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afea2f73a2971b1c2238c0996efdb1201">emitClause</a> (const ClauseInfo &amp;CI, const SIInstrInfo *SII)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a014ee381e519aa7b2b38d66744faa5bb">runOnMachineFunction</a> (MachineFunction &amp;MF) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>runOnMachineFunction - This method must be overloaded to perform the desired machine code transformation or analysis. <a href="#a014ee381e519aa7b2b38d66744faa5bb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/gcnsubtarget">GCNSubtarget</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afdd1c4e7a7b1c4becde4df5ca8fd424f">ST</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a04b2541bf242d9ab3c96bf2b02544880">ID</a> = 0</td>
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


<p>Definition at line 92 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinserthardclauses-cpp">SIInsertHardClauses.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### SIInsertHardClauses() {#adf3ebefc71e2c76b471b71ec7ef5d2e7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{SIInsertHardClauses.cpp}::SIInsertHardClauses::SIInsertHardClauses ()</td>
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



<p>Definition at line 97 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinserthardclauses-cpp">SIInsertHardClauses.cpp</a>.</p>


<p>References <a href="#a04b2541bf242d9ab3c96bf2b02544880">ID</a> and <a href="/web-llvm/docs/api/classes/llvm/machinefunctionpass/#a29c81d2386f4a727c6d33413807530c8">llvm::MachineFunctionPass::MachineFunctionPass</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### emitClause() {#afea2f73a2971b1c2238c0996efdb1201}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{SIInsertHardClauses.cpp}::SIInsertHardClauses::emitClause (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-siinserthardclauses-cpp-/siinserthardclauses/clauseinfo">ClauseInfo</a> &amp; CI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo">SIInstrInfo</a> * SII)</td>
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



<p>Definition at line 177 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinserthardclauses-cpp">SIInsertHardClauses.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a6c1f959947905135c7dd215b64957654">llvm::MachineInstrBuilder::addImm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a077981b5798a5d7a95cec16ece863aeb">llvm::finalizeBundle</a>, <a href="/web-llvm/docs/api/structs/anonymous-siinserthardclauses-cpp-/siinserthardclauses/clauseinfo/#aedcb208b69428c3f1d6aeed2150d46bc">anonymous{SIInsertHardClauses.cpp}::SIInsertHardClauses::ClauseInfo::First</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-node-impl/#af719fc783be6589465137d997701a432">llvm::ilist_node_impl&lt; OptionsT &gt;::getIterator</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a1e855100f407ca4be098d0050be403b0">llvm::MachineInstr::getParent</a>, <a href="/web-llvm/docs/api/structs/anonymous-siinserthardclauses-cpp-/siinserthardclauses/clauseinfo/#a8b2c54a90de8f029d4331b5048522bd4">anonymous{SIInsertHardClauses.cpp}::SIInsertHardClauses::ClauseInfo::Last</a>, <a href="/web-llvm/docs/api/structs/anonymous-siinserthardclauses-cpp-/siinserthardclauses/clauseinfo/#a8a2fbbe5c31e2244394c38df2453fd4b">anonymous{SIInsertHardClauses.cpp}::SIInsertHardClauses::ClauseInfo::Length</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a> and <a href="#afdd1c4e7a7b1c4becde4df5ca8fd424f">ST</a>.</p>


<p>Referenced by <a href="#a014ee381e519aa7b2b38d66744faa5bb">runOnMachineFunction</a>.</p>

</div>
</div>

### getAnalysisUsage() {#a7bb312e7b09ff030930708b97628fa7f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{SIInsertHardClauses.cpp}::SIInsertHardClauses::getAnalysisUsage (<a href="/web-llvm/docs/api/classes/llvm/analysisusage">AnalysisUsage</a> &amp; AU)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>getAnalysisUsage - Subclasses that override getAnalysisUsage must call this.</p>


<p>For MachineFunctionPasses, calling AU.preservesCFG() indicates that the pass does not modify the MachineBasicBlock CFG.</p>


<p>Definition at line 99 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinserthardclauses-cpp">SIInsertHardClauses.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machinefunctionpass/#a864fd57b4304ef933b3281d0ef85a88e">llvm::MachineFunctionPass::getAnalysisUsage</a> and <a href="/web-llvm/docs/api/classes/llvm/analysisusage/#af11a6ebf7ab3c388234cb6d5378439a3">llvm::AnalysisUsage::setPreservesCFG</a>.</p>

</div>
</div>

### getHardClauseType() {#a10d3dc29c5b795204cec9fe33433f1cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">HardClauseType anonymous{SIInsertHardClauses.cpp}::SIInsertHardClauses::getHardClauseType (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
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



<p>Definition at line 104 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinserthardclauses-cpp">SIInsertHardClauses.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/structs/llvm/amdgpu/mimgbaseopcodeinfo/#ae568e3885ff86491cfec37106f83d1c7">llvm::AMDGPU::MIMGBaseOpcodeInfo::BVH</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ae1884e3318cb1f8a4465b1b4bd4d9827">llvm::AMDGPU::getMIMGBaseOpcodeInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a0b5b29d1275f84b9e530fd2419cc03ac">llvm::AMDGPU::getMIMGInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpusubtarget/#a53c0ee4138bfbf9e0410a65e0eaa36e2a0a29519a2da61e1cf78d898e26fef446">llvm::AMDGPUSubtarget::GFX10</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpusubtarget/#a53c0ee4138bfbf9e0410a65e0eaa36e2afee0105d2e947dda0884cc47a33c93b7">llvm::AMDGPUSubtarget::GFX11</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-siinserthardclauses-cpp-/#a05f3bd1f05d10f71d36966379038c069a297f1ff83f801be031a1ae6ed417b24c">anonymous{SIInsertHardClauses.cpp}::HARDCLAUSE_BVH</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-siinserthardclauses-cpp-/#a05f3bd1f05d10f71d36966379038c069a2048a0d417f5ca118585aa677108a1f6">anonymous{SIInsertHardClauses.cpp}::HARDCLAUSE_FLAT</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-siinserthardclauses-cpp-/#a05f3bd1f05d10f71d36966379038c069a31e12b3d5d143c73c795c28ee862455e">anonymous{SIInsertHardClauses.cpp}::HARDCLAUSE_FLAT_ATOMIC</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-siinserthardclauses-cpp-/#a05f3bd1f05d10f71d36966379038c069ad7f93e83f48b8eff8cc5034211751168">anonymous{SIInsertHardClauses.cpp}::HARDCLAUSE_FLAT_LOAD</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-siinserthardclauses-cpp-/#a05f3bd1f05d10f71d36966379038c069abbb43b3b8e5e6bb7e44ddf57e1479ee8">anonymous{SIInsertHardClauses.cpp}::HARDCLAUSE_FLAT_STORE</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-siinserthardclauses-cpp-/#a05f3bd1f05d10f71d36966379038c069a161c9387aef0690f84572531f07239bd">anonymous{SIInsertHardClauses.cpp}::HARDCLAUSE_IGNORE</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-siinserthardclauses-cpp-/#a05f3bd1f05d10f71d36966379038c069aa5be04416de1c7632343fd7d93b37d4d">anonymous{SIInsertHardClauses.cpp}::HARDCLAUSE_ILLEGAL</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-siinserthardclauses-cpp-/#a05f3bd1f05d10f71d36966379038c069ab10feb7cd6ab6000a34957e10296bd8c">anonymous{SIInsertHardClauses.cpp}::HARDCLAUSE_INTERNAL</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-siinserthardclauses-cpp-/#a05f3bd1f05d10f71d36966379038c069ae21a976d427e10ea065829c3f536c159">anonymous{SIInsertHardClauses.cpp}::HARDCLAUSE_MIMG_ATOMIC</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-siinserthardclauses-cpp-/#a05f3bd1f05d10f71d36966379038c069a87e689d02037e6e22319a88e6cf48630">anonymous{SIInsertHardClauses.cpp}::HARDCLAUSE_MIMG_LOAD</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-siinserthardclauses-cpp-/#a05f3bd1f05d10f71d36966379038c069a9dbe1ee4adb05da41676cbdcb2bd839c">anonymous{SIInsertHardClauses.cpp}::HARDCLAUSE_MIMG_SAMPLE</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-siinserthardclauses-cpp-/#a05f3bd1f05d10f71d36966379038c069ad64067111248180877730cbba70fb666">anonymous{SIInsertHardClauses.cpp}::HARDCLAUSE_MIMG_STORE</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-siinserthardclauses-cpp-/#a05f3bd1f05d10f71d36966379038c069acacf443c4f72d8ee8fdf0b1c52b771f0">anonymous{SIInsertHardClauses.cpp}::HARDCLAUSE_SMEM</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-siinserthardclauses-cpp-/#a05f3bd1f05d10f71d36966379038c069a83b1919d3ea219e494e166eed0a62507">anonymous{SIInsertHardClauses.cpp}::HARDCLAUSE_VMEM</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-siinserthardclauses-cpp-/#a05f3bd1f05d10f71d36966379038c069acc5b88fae0184e29515afa49857aea0b">anonymous{SIInsertHardClauses.cpp}::HARDCLAUSE_VMEM_ATOMIC</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-siinserthardclauses-cpp-/#a05f3bd1f05d10f71d36966379038c069aba6f61d790b25012f8962eaf02b58828">anonymous{SIInsertHardClauses.cpp}::HARDCLAUSE_VMEM_LOAD</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-siinserthardclauses-cpp-/#a05f3bd1f05d10f71d36966379038c069a640c5815611ac5e01e14c7756e400dc4">anonymous{SIInsertHardClauses.cpp}::HARDCLAUSE_VMEM_STORE</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#adc3333d2d5974f4068df84f8706fc7d2">llvm::SIInstrInfo::isFLAT</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#abdcf600002fd489c76924f2ec4f4fc0f">llvm::SIInstrInfo::isMIMG</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a8ed947ddafde5421d3f771f43f9c04d1">llvm::SIInstrInfo::isSegmentSpecificFLAT</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a1c990a34866f377751f50f112cef61bc">llvm::SIInstrInfo::isSMRD</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a08b830059090a1bb27b14e1e524fdb46">llvm::SIInstrInfo::isVMEM</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/structs/llvm/amdgpu/mimgbaseopcodeinfo/#a48ae3b8db545c374ea470b0d856e302f">llvm::AMDGPU::MIMGBaseOpcodeInfo::Sampler</a> and <a href="#afdd1c4e7a7b1c4becde4df5ca8fd424f">ST</a>.</p>


<p>Referenced by <a href="#a014ee381e519aa7b2b38d66744faa5bb">runOnMachineFunction</a>.</p>

</div>
</div>

### runOnMachineFunction() {#a014ee381e519aa7b2b38d66744faa5bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{SIInsertHardClauses.cpp}::SIInsertHardClauses::runOnMachineFunction (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>runOnMachineFunction - This method must be overloaded to perform the desired machine code transformation or analysis.</p>

<p>Definition at line 192 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinserthardclauses-cpp">SIInsertHardClauses.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/anonymous-siinserthardclauses-cpp-/siinserthardclauses/clauseinfo/#ad49bf054ec85b06fe8908221b28ec038">anonymous{SIInsertHardClauses.cpp}::SIInsertHardClauses::ClauseInfo::BaseOps</a>, <a href="#afea2f73a2971b1c2238c0996efdb1201">emitClause</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a>, <a href="#a10d3dc29c5b795204cec9fe33433f1cc">getHardClauseType</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a0c826f5192676a1dfa8468a38b9ce1c3">llvm::SIInstrInfo::getMemOperandsWithOffsetWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-siinserthardclauses-cpp-/#a05f3bd1f05d10f71d36966379038c069a161c9387aef0690f84572531f07239bd">anonymous{SIInsertHardClauses.cpp}::HARDCLAUSE_IGNORE</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-siinserthardclauses-cpp-/#a05f3bd1f05d10f71d36966379038c069aa5be04416de1c7632343fd7d93b37d4d">anonymous{SIInsertHardClauses.cpp}::HARDCLAUSE_ILLEGAL</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-siinserthardclauses-cpp-/#a05f3bd1f05d10f71d36966379038c069ab10feb7cd6ab6000a34957e10296bd8c">anonymous{SIInsertHardClauses.cpp}::HARDCLAUSE_INTERNAL</a>, <a href="/web-llvm/docs/api/structs/anonymous-siinserthardclauses-cpp-/siinserthardclauses/clauseinfo/#a8b2c54a90de8f029d4331b5048522bd4">anonymous{SIInsertHardClauses.cpp}::SIInsertHardClauses::ClauseInfo::Last</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-siinserthardclauses-cpp-/#a05f3bd1f05d10f71d36966379038c069a864a2b458251ad286c4eb3769fe46efa">anonymous{SIInsertHardClauses.cpp}::LAST_REAL_HARDCLAUSE_TYPE</a>, <a href="/web-llvm/docs/api/structs/anonymous-siinserthardclauses-cpp-/siinserthardclauses/clauseinfo/#a8a2fbbe5c31e2244394c38df2453fd4b">anonymous{SIInsertHardClauses.cpp}::SIInsertHardClauses::ClauseInfo::Length</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a48560701bbaa0465f8ef8d92874caaf0">llvm::SIInstrInfo::shouldClusterMemOps</a>, <a href="/web-llvm/docs/api/classes/llvm/functionpass/#af9f5f511d75e16f09a5520cb9444cfa8">llvm::FunctionPass::skipFunction</a>, <a href="#afdd1c4e7a7b1c4becde4df5ca8fd424f">ST</a>, <a href="/web-llvm/docs/api/structs/anonymous-siinserthardclauses-cpp-/siinserthardclauses/clauseinfo/#a1fdbda7fa9415f7ed59027fc5ed9fb03">anonymous{SIInsertHardClauses.cpp}::SIInsertHardClauses::ClauseInfo::TrailingInternalLength</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a> and <a href="/web-llvm/docs/api/structs/anonymous-siinserthardclauses-cpp-/siinserthardclauses/clauseinfo/#a8756be0eec6dd68e52f250497ce43aa0">anonymous{SIInsertHardClauses.cpp}::SIInsertHardClauses::ClauseInfo::Type</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### ST {#afdd1c4e7a7b1c4becde4df5ca8fd424f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const GCNSubtarget* anonymous{SIInsertHardClauses.cpp}::SIInsertHardClauses::ST = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 95 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinserthardclauses-cpp">SIInsertHardClauses.cpp</a>.</p>


<p>Referenced by <a href="#afea2f73a2971b1c2238c0996efdb1201">emitClause</a>, <a href="#a10d3dc29c5b795204cec9fe33433f1cc">getHardClauseType</a> and <a href="#a014ee381e519aa7b2b38d66744faa5bb">runOnMachineFunction</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Attributes

### ID {#a04b2541bf242d9ab3c96bf2b02544880}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">char SIInsertHardClauses::ID = 0</td>
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



<p>Definition at line 94 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinserthardclauses-cpp">SIInsertHardClauses.cpp</a>.</p>


<p>Referenced by <a href="#adf3ebefc71e2c76b471b71ec7ef5d2e7">SIInsertHardClauses</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinserthardclauses-cpp">SIInsertHardClauses.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>

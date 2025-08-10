---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-siinsertwaitcnts-cpp-/waitcntgeneratorpregfx12
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `WaitcntGeneratorPreGFX12` Class



## Declaration

<div class="doxyDeclaration">
class anonymous{SIInsertWaitcnts.cpp}::WaitcntGeneratorPreGFX12 { ... }
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/waitcntgenerator">WaitcntGenerator</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb495e3090f7a7adbb6d855117b3b433">WaitcntGeneratorPreGFX12</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aee649d245ffa48ab0160926f8c942459">WaitcntGeneratorPreGFX12</a> (const MachineFunction &amp;MF)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a83153660927a017cef8d173e5917f3a4">applyPreexistingWaitcnt</a> (WaitcntBrackets &amp;ScoreBrackets, MachineInstr &amp;OldWaitcntInstr, AMDGPU::Waitcnt &amp;Wait, MachineBasicBlock::instr_iterator It) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Combine consecutive S_WAITCNT and S_WAITCNT_VSCNT instructions that precede <span class="doxyComputerOutput">It</span> and follow <span class="doxyComputerOutput">OldWaitcntInstr</span> and apply any extra waits from <span class="doxyComputerOutput">Wait</span> that were added by previous passes. <a href="#a83153660927a017cef8d173e5917f3a4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b8a0415e101fcd1f76e5f8ee95172ee">createNewWaitcnt</a> (MachineBasicBlock &amp;Block, MachineBasicBlock::instr_iterator It, AMDGPU::Waitcnt Wait) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Generate S_WAITCNT and/or S_WAITCNT_VSCNT instructions for any required counters in <span class="doxyComputerOutput">Wait</span>. <a href="#a1b8a0415e101fcd1f76e5f8ee95172ee">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac08d76aba821fabbc04aab913230e09f">getWaitEventMask</a> () const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/amdgpu/waitcnt">AMDGPU::Waitcnt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7f4e5e1ef77d730ea4b18e99d97c62b0">getAllZeroWaitcnt</a> (bool IncludeVSCnt) const override</td>
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


<p>Definition at line 522 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinsertwaitcnts-cpp">SIInsertWaitcnts.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### WaitcntGeneratorPreGFX12() {#afb495e3090f7a7adbb6d855117b3b433}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{SIInsertWaitcnts.cpp}::WaitcntGeneratorPreGFX12::WaitcntGeneratorPreGFX12 ()</td>
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



<p>Definition at line 524 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinsertwaitcnts-cpp">SIInsertWaitcnts.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/siinsertwaitcnts/#aab6a5b3788b7384e1928f2ccd79f26b7">anonymous{SIInsertWaitcnts.cpp}::SIInsertWaitcnts::runOnMachineFunction</a>.</p>

</div>
</div>

### WaitcntGeneratorPreGFX12() {#aee649d245ffa48ab0160926f8c942459}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{SIInsertWaitcnts.cpp}::WaitcntGeneratorPreGFX12::WaitcntGeneratorPreGFX12 (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
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



<p>Definition at line 525 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinsertwaitcnts-cpp">SIInsertWaitcnts.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#a871adff9f76dede83762790959bc8e7ba6bce6243a580981ed0a55d0ac3fb5f2c">anonymous{SIInsertWaitcnts.cpp}::NUM_NORMAL_INST_CNTS</a> and <a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/waitcntgenerator/#a1755d27320084b6dc603439381b6057a">anonymous{SIInsertWaitcnts.cpp}::WaitcntGenerator::WaitcntGenerator</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### applyPreexistingWaitcnt() {#a83153660927a017cef8d173e5917f3a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool WaitcntGeneratorPreGFX12::applyPreexistingWaitcnt (<a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/waitcntbrackets">WaitcntBrackets</a> &amp; ScoreBrackets, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; OldWaitcntInstr, <a href="/web-llvm/docs/api/structs/llvm/amdgpu/waitcnt">AMDGPU::Waitcnt</a> &amp; Wait, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ab6395548cae73865213e279ae461db54">MachineBasicBlock::instr_iterator</a> It)</td>
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

<p>Combine consecutive S_WAITCNT and S_WAITCNT_VSCNT instructions that precede <span class="doxyComputerOutput">It</span> and follow <span class="doxyComputerOutput">OldWaitcntInstr</span> and apply any extra waits from <span class="doxyComputerOutput">Wait</span> that were added by previous passes.</p>


<p>Currently this pass conservatively assumes that these preexisting waits are required for correctness.</p>


<p>Definition at line 529 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinsertwaitcnts-cpp">SIInsertWaitcnts.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/waitcntbrackets/#a0e968fc970599ceab59ecb968132e6d0">anonymous{SIInsertWaitcnts.cpp}::WaitcntBrackets::applyWaitcnt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a0d3e0a75774a86f6c8302eee2dfe1326">llvm::AMDGPU::decodeWaitcnt</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#a871adff9f76dede83762790959bc8e7bad2dc0db90fa9cebb27684f1f2e9416a4">anonymous{SIInsertWaitcnts.cpp}::DS_CNT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a538a5f491696e8b8ef0987e3aaedbb37">llvm::AMDGPU::encodeWaitcnt</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#acbc921830578e2741be6549db716c0ce">llvm::MachineBasicBlock::end</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#a871adff9f76dede83762790959bc8e7bae9718b54520e280d35e9e0268e726ca6">anonymous{SIInsertWaitcnts.cpp}::EXP_CNT</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-node-impl/#af719fc783be6589465137d997701a432">llvm::ilist_node_impl&lt; OptionsT &gt;::getIterator</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a81793225c0abc2a358b3710ed81189ec">llvm::SIInstrInfo::getNonSoftWaitcntOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a1e855100f407ca4be098d0050be403b0">llvm::MachineInstr::getParent</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#ac5804672fc0850438d63caec770647f8">II</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#a9a26bbfc1523426a16825ff6687dcc82">anonymous{SIInsertWaitcnts.cpp}::isNormalMode</a>, <a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/waitcntgenerator/#aa6275ae3aee38841f61e642d6bdbc0f8">anonymous{SIInsertWaitcnts.cpp}::WaitcntGenerator::IV</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#a871adff9f76dede83762790959bc8e7ba70f203972ebeec43ef1971db7a1ed063">anonymous{SIInsertWaitcnts.cpp}::LOAD_CNT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3d2cdc4a0db233678e7141c9d6ea3419">llvm::make_early_inc_range</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>, <a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/waitcntgenerator/#a07238d8070f6317ff8ec1a0106fbd5fb">anonymous{SIInsertWaitcnts.cpp}::WaitcntGenerator::MaxCounter</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopdeletion-cpp/#a0f1c83c3d08d80b12c424962a5e94ce8a35e0c8c0b180c95d4e122e55ed62cc64">Modified</a>, <a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/waitcntgenerator/#a6372b63391a683c0c9598de1b16875dc">anonymous{SIInsertWaitcnts.cpp}::WaitcntGenerator::OptNone</a>, <a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/waitcntgenerator/#a8ca037899f2fcee956e635f6f5c0cb2c">anonymous{SIInsertWaitcnts.cpp}::WaitcntGenerator::promoteSoftWaitCnt</a>, <a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/waitcntbrackets/#a812aeb1ae1957923c10677d13d53d98f">anonymous{SIInsertWaitcnts.cpp}::WaitcntBrackets::simplifyWaitcnt</a>, <a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/waitcntgenerator/#afa1cc29553ae6456421ce1f8b1985d23">anonymous{SIInsertWaitcnts.cpp}::WaitcntGenerator::ST</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#a871adff9f76dede83762790959bc8e7ba0c4deee3d74fa3bd8a894f25581de266">anonymous{SIInsertWaitcnts.cpp}::STORE_CNT</a>, <a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/waitcntgenerator/#afdaae07409c62be8355ef9eec693ddab">anonymous{SIInsertWaitcnts.cpp}::WaitcntGenerator::TII</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinsertwaitcnts-cpp/#a76c206acce516598d664c520bf1223a9">updateOperandIfDifferent</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a233737223c9a3dba810df5b91bc91d1fa49bfe5e1e40e44e387a5e03c6ca759c5">llvm::Wait</a>.</p>

</div>
</div>

### createNewWaitcnt() {#a1b8a0415e101fcd1f76e5f8ee95172ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool WaitcntGeneratorPreGFX12::createNewWaitcnt (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; Block, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ab6395548cae73865213e279ae461db54">MachineBasicBlock::instr_iterator</a> It, <a href="/web-llvm/docs/api/structs/llvm/amdgpu/waitcnt">AMDGPU::Waitcnt</a> Wait)</td>
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

<p>Generate S_WAITCNT and/or S_WAITCNT_VSCNT instructions for any required counters in <span class="doxyComputerOutput">Wait</span>.</p>

<p>Definition at line 533 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinsertwaitcnts-cpp">SIInsertWaitcnts.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a6c1f959947905135c7dd215b64957654">llvm::MachineInstrBuilder::addImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a927857fc69e4b4f0cde307f86f180df5">llvm::MachineInstrBuilder::addReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0e00fad9c34de40b1e31f3aa6f8e024cae1e4c8c9ccd9fc39c391da4bcd093fb2">llvm::Block</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a538a5f491696e8b8ef0987e3aaedbb37">llvm::AMDGPU::encodeWaitcnt</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#a9a26bbfc1523426a16825ff6687dcc82">anonymous{SIInsertWaitcnts.cpp}::isNormalMode</a>, <a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/waitcntgenerator/#aa6275ae3aee38841f61e642d6bdbc0f8">anonymous{SIInsertWaitcnts.cpp}::WaitcntGenerator::IV</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/waitcntgenerator/#a07238d8070f6317ff8ec1a0106fbd5fb">anonymous{SIInsertWaitcnts.cpp}::WaitcntGenerator::MaxCounter</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopdeletion-cpp/#a0f1c83c3d08d80b12c424962a5e94ce8a35e0c8c0b180c95d4e122e55ed62cc64">Modified</a>, <a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/waitcntgenerator/#afa1cc29553ae6456421ce1f8b1985d23">anonymous{SIInsertWaitcnts.cpp}::WaitcntGenerator::ST</a>, <a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/waitcntgenerator/#afdaae07409c62be8355ef9eec693ddab">anonymous{SIInsertWaitcnts.cpp}::WaitcntGenerator::TII</a>, <a href="/web-llvm/docs/api/namespaces/llvm/regstate/#ade26fe5c9b3fe6948def36f7ca12dfc5ab502f975742e9bff6d6dd7b49439b806">llvm::RegState::Undef</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a233737223c9a3dba810df5b91bc91d1fa49bfe5e1e40e44e387a5e03c6ca759c5">llvm::Wait</a>.</p>

</div>
</div>

### getAllZeroWaitcnt() {#a7f4e5e1ef77d730ea4b18e99d97c62b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AMDGPU::Waitcnt WaitcntGeneratorPreGFX12::getAllZeroWaitcnt (bool IncludeVSCnt)</td>
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



<p>Definition at line 554 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinsertwaitcnts-cpp">SIInsertWaitcnts.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/waitcntgenerator/#afa1cc29553ae6456421ce1f8b1985d23">anonymous{SIInsertWaitcnts.cpp}::WaitcntGenerator::ST</a>.</p>

</div>
</div>

### getWaitEventMask() {#ac08d76aba821fabbc04aab913230e09f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned * anonymous{SIInsertWaitcnts.cpp}::WaitcntGeneratorPreGFX12::getWaitEventMask ()</td>
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



<p>Definition at line 537 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinsertwaitcnts-cpp">SIInsertWaitcnts.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/waitcntgenerator/#a76154026ad95c68169ea7c30b8ddc2b2">anonymous{SIInsertWaitcnts.cpp}::WaitcntGenerator::eventMask</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#a7fa7c35bfc5ff0d3fd25401b3b2e86daa3d3a2918b4a8d46587a46104973a0fbb">anonymous{SIInsertWaitcnts.cpp}::EXP_GPR_LOCK</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#a7fa7c35bfc5ff0d3fd25401b3b2e86daa29adb0a7716bd8776a15d8e48236b226">anonymous{SIInsertWaitcnts.cpp}::EXP_LDS_ACCESS</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#a7fa7c35bfc5ff0d3fd25401b3b2e86daac5112e1f3b27e352669978def9632a96">anonymous{SIInsertWaitcnts.cpp}::EXP_PARAM_ACCESS</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#a7fa7c35bfc5ff0d3fd25401b3b2e86daad6945119665d190abd3262800abbf1b8">anonymous{SIInsertWaitcnts.cpp}::EXP_POS_ACCESS</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#a7fa7c35bfc5ff0d3fd25401b3b2e86daa495d00b9909551a28dd47651ca5abd6b">anonymous{SIInsertWaitcnts.cpp}::GDS_ACCESS</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#a7fa7c35bfc5ff0d3fd25401b3b2e86daa7cabdbd2bae66ba4d0a4af5e95148024">anonymous{SIInsertWaitcnts.cpp}::GDS_GPR_LOCK</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#a7fa7c35bfc5ff0d3fd25401b3b2e86daaa8971543f4c4ff4e747224697d45f0f6">anonymous{SIInsertWaitcnts.cpp}::LDS_ACCESS</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#a871adff9f76dede83762790959bc8e7baba718cf45e306a2491c209604bd44763">anonymous{SIInsertWaitcnts.cpp}::NUM_INST_CNTS</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#a7fa7c35bfc5ff0d3fd25401b3b2e86daadee683fb94c4b2131a4d3b2cc23c4ea3">anonymous{SIInsertWaitcnts.cpp}::SCRATCH_WRITE_ACCESS</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#a7fa7c35bfc5ff0d3fd25401b3b2e86daaf3cac1cd357193995b108d6d73781a32">anonymous{SIInsertWaitcnts.cpp}::SMEM_ACCESS</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#a7fa7c35bfc5ff0d3fd25401b3b2e86daa33b8619729a53d2b671fae55f77a626a">anonymous{SIInsertWaitcnts.cpp}::SQ_MESSAGE</a>, <a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/waitcntgenerator/#afa1cc29553ae6456421ce1f8b1985d23">anonymous{SIInsertWaitcnts.cpp}::WaitcntGenerator::ST</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#a7fa7c35bfc5ff0d3fd25401b3b2e86daa21de8177a6f3abd11c6c077c5d7ea476">anonymous{SIInsertWaitcnts.cpp}::VMEM_ACCESS</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#a7fa7c35bfc5ff0d3fd25401b3b2e86daa7d81d39ce1e8450d43d9559acbe42dd1">anonymous{SIInsertWaitcnts.cpp}::VMEM_BVH_READ_ACCESS</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#a7fa7c35bfc5ff0d3fd25401b3b2e86daa1d154e87495ad512bb7d4358ae701f5d">anonymous{SIInsertWaitcnts.cpp}::VMEM_READ_ACCESS</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#a7fa7c35bfc5ff0d3fd25401b3b2e86daa67397bffb67b25a842216f7d121c4da8">anonymous{SIInsertWaitcnts.cpp}::VMEM_SAMPLER_READ_ACCESS</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#a7fa7c35bfc5ff0d3fd25401b3b2e86daa178c35ca811b8695e008c8a293276134">anonymous{SIInsertWaitcnts.cpp}::VMEM_WRITE_ACCESS</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#a7fa7c35bfc5ff0d3fd25401b3b2e86daa66da40a072eb0d08160551b7cfd8846e">anonymous{SIInsertWaitcnts.cpp}::VMW_GPR_LOCK</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinsertwaitcnts-cpp">SIInsertWaitcnts.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>

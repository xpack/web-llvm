---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-siinsertwaitcnts-cpp-/waitcntgenerator
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `WaitcntGenerator` Class Reference



## Declaration

<div class="doxyDeclaration">
class anonymous{SIInsertWaitcnts.cpp}::WaitcntGenerator { ... }
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/waitcntgeneratorgfx12plus">WaitcntGeneratorGFX12Plus</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/waitcntgeneratorpregfx12">WaitcntGeneratorPreGFX12</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1755d27320084b6dc603439381b6057a">WaitcntGenerator</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acbbbbc7e381ed0f9d0aaa35c51d4882a">WaitcntGenerator</a> (const MachineFunction &amp;MF, InstCounterType MaxCounter)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b1896d9db1cbaef3c15fe01811fc8ef">~WaitcntGenerator</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a62d565f43c51f26a52037172c2bbd1f6">isOptNone</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a42f29b7c6db47c9f6c0e90b036ab2dca">applyPreexistingWaitcnt</a> (WaitcntBrackets &amp;ScoreBrackets, MachineInstr &amp;OldWaitcntInstr, AMDGPU::Waitcnt &amp;Wait, MachineBasicBlock::instr_iterator It) const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ca037899f2fcee956e635f6f5c0cb2c">promoteSoftWaitCnt</a> (MachineInstr *Waitcnt) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a31304f59f3fdc58c0218c9bed68845cd">createNewWaitcnt</a> (MachineBasicBlock &amp;Block, MachineBasicBlock::instr_iterator It, AMDGPU::Waitcnt Wait)=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a78ab6e9e4d221141f7a870e229213285">getWaitEventMask</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac8b4485336a1b1e158757245e8c767af">getAllZeroWaitcnt</a> (bool IncludeVSCnt) const =0</td>
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

## Protected Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/gcnsubtarget">GCNSubtarget</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa1cc29553ae6456421ce1f8b1985d23">ST</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo">SIInstrInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afdaae07409c62be8355ef9eec693ddab">TII</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/amdgpu/isaversion">AMDGPU::IsaVersion</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa6275ae3aee38841f61e642d6bdbc0f8">IV</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#a871adff9f76dede83762790959bc8e7b">InstCounterType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a07238d8070f6317ff8ec1a0106fbd5fb">MaxCounter</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6372b63391a683c0c9598de1b16875dc">OptNone</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a76154026ad95c68169ea7c30b8ddc2b2">eventMask</a> (std::initializer_list&lt; WaitEventType &gt; Events)</td>
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


<p>Definition at line 456 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinsertwaitcnts-cpp">SIInsertWaitcnts.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### WaitcntGenerator() {#a1755d27320084b6dc603439381b6057a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{SIInsertWaitcnts.cpp}::WaitcntGenerator::WaitcntGenerator ()</td>
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



<p>Definition at line 465 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinsertwaitcnts-cpp">SIInsertWaitcnts.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/waitcntgeneratorgfx12plus/#aef7f933114476390a96d0a435c0da5e0">anonymous{SIInsertWaitcnts.cpp}::WaitcntGeneratorGFX12Plus::WaitcntGeneratorGFX12Plus</a> and <a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/waitcntgeneratorpregfx12/#aee649d245ffa48ab0160926f8c942459">anonymous{SIInsertWaitcnts.cpp}::WaitcntGeneratorPreGFX12::WaitcntGeneratorPreGFX12</a>.</p>

</div>
</div>

### WaitcntGenerator() {#acbbbbc7e381ed0f9d0aaa35c51d4882a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{SIInsertWaitcnts.cpp}::WaitcntGenerator::WaitcntGenerator (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#a871adff9f76dede83762790959bc8e7b">InstCounterType</a> MaxCounter)</td>
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



<p>Definition at line 466 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinsertwaitcnts-cpp">SIInsertWaitcnts.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a2c346c56fb9021d994675d1710d2d551">llvm::getCPU</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/evaluator-cpp/#a92efb02157b6836e1232c577d34678d6">getFunction</a>, <a href="#aa6275ae3aee38841f61e642d6bdbc0f8">IV</a>, <a href="#a07238d8070f6317ff8ec1a0106fbd5fb">MaxCounter</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7a24c2247bd546fc56e2de6cfd04a3d7a116ebf2078ffd98178ffbdd2f544ebb7">llvm::None</a>, <a href="#a6372b63391a683c0c9598de1b16875dc">OptNone</a>, <a href="#afa1cc29553ae6456421ce1f8b1985d23">ST</a> and <a href="#afdaae07409c62be8355ef9eec693ddab">TII</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~WaitcntGenerator() {#a3b1896d9db1cbaef3c15fe01811fc8ef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual anonymous{SIInsertWaitcnts.cpp}::WaitcntGenerator::~WaitcntGenerator ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 509 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinsertwaitcnts-cpp">SIInsertWaitcnts.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### applyPreexistingWaitcnt() {#a42f29b7c6db47c9f6c0e90b036ab2dca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool anonymous{SIInsertWaitcnts.cpp}::WaitcntGenerator::applyPreexistingWaitcnt (<a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/waitcntbrackets">WaitcntBrackets</a> &amp; ScoreBrackets, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; OldWaitcntInstr, <a href="/web-llvm/docs/api/structs/llvm/amdgpu/waitcnt">AMDGPU::Waitcnt</a> &amp; Wait, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ab6395548cae73865213e279ae461db54">MachineBasicBlock::instr_iterator</a> It)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 488 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinsertwaitcnts-cpp">SIInsertWaitcnts.cpp</a>.</p>


<p>References <a href="#a8ca037899f2fcee956e635f6f5c0cb2c">promoteSoftWaitCnt</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a233737223c9a3dba810df5b91bc91d1fa49bfe5e1e40e44e387a5e03c6ca759c5">llvm::Wait</a>.</p>

</div>
</div>

### createNewWaitcnt() {#a31304f59f3fdc58c0218c9bed68845cd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool anonymous{SIInsertWaitcnts.cpp}::WaitcntGenerator::createNewWaitcnt (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; Block, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ab6395548cae73865213e279ae461db54">MachineBasicBlock::instr_iterator</a> It, <a href="/web-llvm/docs/api/structs/llvm/amdgpu/waitcnt">AMDGPU::Waitcnt</a> Wait)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 497 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinsertwaitcnts-cpp">SIInsertWaitcnts.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a0e00fad9c34de40b1e31f3aa6f8e024cae1e4c8c9ccd9fc39c391da4bcd093fb2">llvm::Block</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a233737223c9a3dba810df5b91bc91d1fa49bfe5e1e40e44e387a5e03c6ca759c5">llvm::Wait</a>.</p>

</div>
</div>

### getAllZeroWaitcnt() {#ac8b4485336a1b1e158757245e8c767af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual AMDGPU::Waitcnt anonymous{SIInsertWaitcnts.cpp}::WaitcntGenerator::getAllZeroWaitcnt (bool IncludeVSCnt)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 507 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinsertwaitcnts-cpp">SIInsertWaitcnts.cpp</a>.</p>

</div>
</div>

### getWaitEventMask() {#a78ab6e9e4d221141f7a870e229213285}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual const unsigned * anonymous{SIInsertWaitcnts.cpp}::WaitcntGenerator::getWaitEventMask ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 503 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinsertwaitcnts-cpp">SIInsertWaitcnts.cpp</a>.</p>

</div>
</div>

### isOptNone() {#a62d565f43c51f26a52037172c2bbd1f6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{SIInsertWaitcnts.cpp}::WaitcntGenerator::isOptNone ()</td>
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



<p>Definition at line 474 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinsertwaitcnts-cpp">SIInsertWaitcnts.cpp</a>.</p>


<p>Reference <a href="#a6372b63391a683c0c9598de1b16875dc">OptNone</a>.</p>

</div>
</div>

### promoteSoftWaitCnt() {#a8ca037899f2fcee956e635f6f5c0cb2c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool WaitcntGenerator::promoteSoftWaitCnt (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * Waitcnt)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 493 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinsertwaitcnts-cpp">SIInsertWaitcnts.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a81793225c0abc2a358b3710ed81189ec">llvm::SIInstrInfo::getNonSoftWaitcntOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a0363204b5fbab08a46f5a7cd7f376f78">llvm::MachineInstr::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a9117508fb00fda14207e7f968389544c">llvm::MachineInstr::setDesc</a> and <a href="#afdaae07409c62be8355ef9eec693ddab">TII</a>.</p>


<p>Referenced by <a href="#a42f29b7c6db47c9f6c0e90b036ab2dca">applyPreexistingWaitcnt</a>, <a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/waitcntgeneratorgfx12plus/#a30a7745f58a481ca6495b35e202e4cce">anonymous{SIInsertWaitcnts.cpp}::WaitcntGeneratorGFX12Plus::applyPreexistingWaitcnt</a> and <a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/waitcntgeneratorpregfx12/#a83153660927a017cef8d173e5917f3a4">anonymous{SIInsertWaitcnts.cpp}::WaitcntGeneratorPreGFX12::applyPreexistingWaitcnt</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### IV {#aa6275ae3aee38841f61e642d6bdbc0f8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AMDGPU::IsaVersion anonymous{SIInsertWaitcnts.cpp}::WaitcntGenerator::IV</td>
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



<p>Definition at line 460 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinsertwaitcnts-cpp">SIInsertWaitcnts.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/waitcntgeneratorgfx12plus/#a30a7745f58a481ca6495b35e202e4cce">anonymous{SIInsertWaitcnts.cpp}::WaitcntGeneratorGFX12Plus::applyPreexistingWaitcnt</a>, <a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/waitcntgeneratorpregfx12/#a83153660927a017cef8d173e5917f3a4">anonymous{SIInsertWaitcnts.cpp}::WaitcntGeneratorPreGFX12::applyPreexistingWaitcnt</a>, <a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/waitcntgeneratorgfx12plus/#a7e1b709b5200ebfeeb1feff10a572fe9">anonymous{SIInsertWaitcnts.cpp}::WaitcntGeneratorGFX12Plus::createNewWaitcnt</a>, <a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/waitcntgeneratorpregfx12/#a1b8a0415e101fcd1f76e5f8ee95172ee">anonymous{SIInsertWaitcnts.cpp}::WaitcntGeneratorPreGFX12::createNewWaitcnt</a> and <a href="#acbbbbc7e381ed0f9d0aaa35c51d4882a">WaitcntGenerator</a>.</p>

</div>
</div>

### MaxCounter {#a07238d8070f6317ff8ec1a0106fbd5fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstCounterType anonymous{SIInsertWaitcnts.cpp}::WaitcntGenerator::MaxCounter</td>
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



<p>Definition at line 461 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinsertwaitcnts-cpp">SIInsertWaitcnts.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/waitcntgeneratorgfx12plus/#a30a7745f58a481ca6495b35e202e4cce">anonymous{SIInsertWaitcnts.cpp}::WaitcntGeneratorGFX12Plus::applyPreexistingWaitcnt</a>, <a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/waitcntgeneratorpregfx12/#a83153660927a017cef8d173e5917f3a4">anonymous{SIInsertWaitcnts.cpp}::WaitcntGeneratorPreGFX12::applyPreexistingWaitcnt</a>, <a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/waitcntgeneratorgfx12plus/#a7e1b709b5200ebfeeb1feff10a572fe9">anonymous{SIInsertWaitcnts.cpp}::WaitcntGeneratorGFX12Plus::createNewWaitcnt</a>, <a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/waitcntgeneratorpregfx12/#a1b8a0415e101fcd1f76e5f8ee95172ee">anonymous{SIInsertWaitcnts.cpp}::WaitcntGeneratorPreGFX12::createNewWaitcnt</a>, <a href="#acbbbbc7e381ed0f9d0aaa35c51d4882a">WaitcntGenerator</a> and <a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/waitcntgeneratorgfx12plus/#aef7f933114476390a96d0a435c0da5e0">anonymous{SIInsertWaitcnts.cpp}::WaitcntGeneratorGFX12Plus::WaitcntGeneratorGFX12Plus</a>.</p>

</div>
</div>

### OptNone {#a6372b63391a683c0c9598de1b16875dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{SIInsertWaitcnts.cpp}::WaitcntGenerator::OptNone</td>
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



<p>Definition at line 462 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinsertwaitcnts-cpp">SIInsertWaitcnts.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/waitcntgeneratorgfx12plus/#a30a7745f58a481ca6495b35e202e4cce">anonymous{SIInsertWaitcnts.cpp}::WaitcntGeneratorGFX12Plus::applyPreexistingWaitcnt</a>, <a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/waitcntgeneratorpregfx12/#a83153660927a017cef8d173e5917f3a4">anonymous{SIInsertWaitcnts.cpp}::WaitcntGeneratorPreGFX12::applyPreexistingWaitcnt</a>, <a href="#a62d565f43c51f26a52037172c2bbd1f6">isOptNone</a> and <a href="#acbbbbc7e381ed0f9d0aaa35c51d4882a">WaitcntGenerator</a>.</p>

</div>
</div>

### ST {#afa1cc29553ae6456421ce1f8b1985d23}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const GCNSubtarget* anonymous{SIInsertWaitcnts.cpp}::WaitcntGenerator::ST = nullptr</td>
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



<p>Definition at line 458 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinsertwaitcnts-cpp">SIInsertWaitcnts.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/waitcntgeneratorgfx12plus/#a30a7745f58a481ca6495b35e202e4cce">anonymous{SIInsertWaitcnts.cpp}::WaitcntGeneratorGFX12Plus::applyPreexistingWaitcnt</a>, <a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/waitcntgeneratorpregfx12/#a83153660927a017cef8d173e5917f3a4">anonymous{SIInsertWaitcnts.cpp}::WaitcntGeneratorPreGFX12::applyPreexistingWaitcnt</a>, <a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/waitcntgeneratorgfx12plus/#a7e1b709b5200ebfeeb1feff10a572fe9">anonymous{SIInsertWaitcnts.cpp}::WaitcntGeneratorGFX12Plus::createNewWaitcnt</a>, <a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/waitcntgeneratorpregfx12/#a1b8a0415e101fcd1f76e5f8ee95172ee">anonymous{SIInsertWaitcnts.cpp}::WaitcntGeneratorPreGFX12::createNewWaitcnt</a>, <a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/waitcntgeneratorpregfx12/#a7f4e5e1ef77d730ea4b18e99d97c62b0">anonymous{SIInsertWaitcnts.cpp}::WaitcntGeneratorPreGFX12::getAllZeroWaitcnt</a>, <a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/waitcntgeneratorgfx12plus/#a275bd53ce58e251bc5d5140c6ef80b78">anonymous{SIInsertWaitcnts.cpp}::WaitcntGeneratorGFX12Plus::getWaitEventMask</a>, <a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/waitcntgeneratorpregfx12/#ac08d76aba821fabbc04aab913230e09f">anonymous{SIInsertWaitcnts.cpp}::WaitcntGeneratorPreGFX12::getWaitEventMask</a> and <a href="#acbbbbc7e381ed0f9d0aaa35c51d4882a">WaitcntGenerator</a>.</p>

</div>
</div>

### TII {#afdaae07409c62be8355ef9eec693ddab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SIInstrInfo* anonymous{SIInsertWaitcnts.cpp}::WaitcntGenerator::TII = nullptr</td>
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



<p>Definition at line 459 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinsertwaitcnts-cpp">SIInsertWaitcnts.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/waitcntgeneratorgfx12plus/#a30a7745f58a481ca6495b35e202e4cce">anonymous{SIInsertWaitcnts.cpp}::WaitcntGeneratorGFX12Plus::applyPreexistingWaitcnt</a>, <a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/waitcntgeneratorpregfx12/#a83153660927a017cef8d173e5917f3a4">anonymous{SIInsertWaitcnts.cpp}::WaitcntGeneratorPreGFX12::applyPreexistingWaitcnt</a>, <a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/waitcntgeneratorgfx12plus/#a7e1b709b5200ebfeeb1feff10a572fe9">anonymous{SIInsertWaitcnts.cpp}::WaitcntGeneratorGFX12Plus::createNewWaitcnt</a>, <a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/waitcntgeneratorpregfx12/#a1b8a0415e101fcd1f76e5f8ee95172ee">anonymous{SIInsertWaitcnts.cpp}::WaitcntGeneratorPreGFX12::createNewWaitcnt</a>, <a href="#a8ca037899f2fcee956e635f6f5c0cb2c">promoteSoftWaitCnt</a> and <a href="#acbbbbc7e381ed0f9d0aaa35c51d4882a">WaitcntGenerator</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### eventMask() {#a76154026ad95c68169ea7c30b8ddc2b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">constexpr unsigned anonymous{SIInsertWaitcnts.cpp}::WaitcntGenerator::eventMask (std::initializer_list&lt; <a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#a7fa7c35bfc5ff0d3fd25401b3b2e86da">WaitEventType</a> &gt; Events)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 513 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinsertwaitcnts-cpp">SIInsertWaitcnts.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/waitcntgeneratorgfx12plus/#a275bd53ce58e251bc5d5140c6ef80b78">anonymous{SIInsertWaitcnts.cpp}::WaitcntGeneratorGFX12Plus::getWaitEventMask</a> and <a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/waitcntgeneratorpregfx12/#ac08d76aba821fabbc04aab913230e09f">anonymous{SIInsertWaitcnts.cpp}::WaitcntGeneratorPreGFX12::getWaitEventMask</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinsertwaitcnts-cpp">SIInsertWaitcnts.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>

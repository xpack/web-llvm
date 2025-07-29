---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-cfiinstrinserter-cpp-/cfiinstrinserter
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `CFIInstrInserter` Class



## Declaration

<div class="doxyDeclaration">
class anonymous{CFIInstrInserter.cpp}::CFIInstrInserter { ... }
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac7e514de1dcee523358111d416cc6c9a">CFIInstrInserter</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a401fddeacac222c9da6d8f079df1ae73">getAnalysisUsage</a> (AnalysisUsage &amp;AU) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getAnalysisUsage - This function should be overriden by passes that need analysis information to do their job. <a href="#a401fddeacac222c9da6d8f079df1ae73">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb6123b2fb2967969ac1a43ffe98d0d5">runOnMachineFunction</a> (MachineFunction &amp;MF) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>runOnMachineFunction - This method must be overloaded to perform the desired machine code transformation or analysis. <a href="#abb6123b2fb2967969ac1a43ffe98d0d5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac3115616e54d82d9f2bf7acdff1f457d">calculateCFAInfo</a> (MachineFunction &amp;MF)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Calculate cfa offset and register values valid at entry and exit for all basic blocks in a function. <a href="#ac3115616e54d82d9f2bf7acdff1f457d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af0c1fd4e752079ccf6a04deea586b33f">calculateOutgoingCFAInfo</a> (MBBCFAInfo &amp;MBBInfo)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Calculate cfa offset and register values valid at basic block exit by checking the block for CFI instructions. <a href="#af0c1fd4e752079ccf6a04deea586b33f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abad87ca87eef40e3c91ae2fa9c8784a5">updateSuccCFAInfo</a> (MBBCFAInfo &amp;MBBInfo)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Update in/out cfa offset and register values for successors of the basic block. <a href="#abad87ca87eef40e3c91ae2fa9c8784a5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a34ace752189f35b070c84a28845cab">insertCFIInstrs</a> (MachineFunction &amp;MF)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Check if incoming CFA information of a basic block matches outgoing CFA information of the previous block. <a href="#a6a34ace752189f35b070c84a28845cab">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a08478df876e525ecaf28eec6f59d546a">getCorrectCFAOffset</a> (MachineBasicBlock *MBB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the cfa offset value that should be set at the beginning of a MBB if needed. <a href="#a08478df876e525ecaf28eec6f59d546a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade8f752c8e015cc3ee27e132fd0475ce">reportCFAError</a> (const MBBCFAInfo &amp;Pred, const MBBCFAInfo &amp;Succ)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2af5c9f0ee948299366801714b4bc109">reportCSRError</a> (const MBBCFAInfo &amp;Pred, const MBBCFAInfo &amp;Succ)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b9cd4620c0f5d861a244a04a2f5e769">verify</a> (MachineFunction &amp;MF)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Go through each MBB in a function and check that outgoing offset and register of its predecessors match incoming offset and register of that MBB, as well as that incoming offset and register of its successors match outgoing offset and register of the MBB. <a href="#a5b9cd4620c0f5d861a244a04a2f5e769">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; MBBCFAInfo &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5ade73a79c381650a7862fcad36522d4">MBBVector</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Contains cfa offset and register values valid at entry and exit of basic blocks. <a href="#a5ade73a79c381650a7862fcad36522d4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smalldensemap">SmallDenseMap</a>&lt; unsigned, CSRSavedLocation, 16 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5e99310de318c8baf2ad7a77aed2adf0">CSRLocMap</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Map the callee save registers to the locations where they are saved. <a href="#a5e99310de318c8baf2ad7a77aed2adf0">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9701cda36f054fc30b4871cc4ca2bd43">ID</a> = 0</td>
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


<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/cfiinstrinserter-cpp">CFIInstrInserter.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### CFIInstrInserter() {#ac7e514de1dcee523358111d416cc6c9a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{CFIInstrInserter.cpp}::CFIInstrInserter::CFIInstrInserter ()</td>
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



<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/cfiinstrinserter-cpp">CFIInstrInserter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/passregistry/#a05a729900b76c89e808c6c3094921b2f">llvm::PassRegistry::getPassRegistry</a>, <a href="#a9701cda36f054fc30b4871cc4ca2bd43">ID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae64f6a0f5bc534cc09a2aee41fba1702">llvm::initializeCFIInstrInserterPass</a> and <a href="/web-llvm/docs/api/classes/llvm/machinefunctionpass/#a29c81d2386f4a727c6d33413807530c8">llvm::MachineFunctionPass::MachineFunctionPass</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/cfiinstrinserter-cpp/#a7e90696f0af26bc1a4c8dc8dfa1dfb60">INITIALIZE_PASS</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getAnalysisUsage() {#a401fddeacac222c9da6d8f079df1ae73}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{CFIInstrInserter.cpp}::CFIInstrInserter::getAnalysisUsage (<a href="/web-llvm/docs/api/classes/llvm/analysisusage">AnalysisUsage</a> &amp;)</td>
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

<p>getAnalysisUsage - This function should be overriden by passes that need analysis information to do their job.</p>


<p>If a pass specifies that it uses a particular analysis result to this function, it can then use the <a href="/web-llvm/docs/api/classes/llvm/pass/#a4863e5e463fb79955269fbf7fbf52b80">getAnalysis&lt;AnalysisType&gt;()</a> function, below.</p>


<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/cfiinstrinserter-cpp">CFIInstrInserter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machinefunctionpass/#a864fd57b4304ef933b3281d0ef85a88e">llvm::MachineFunctionPass::getAnalysisUsage</a> and <a href="/web-llvm/docs/api/classes/llvm/analysisusage/#af22b06a6a4f9df80454071685a0d6a02">llvm::AnalysisUsage::setPreservesAll</a>.</p>

</div>
</div>

### runOnMachineFunction() {#abb6123b2fb2967969ac1a43ffe98d0d5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{CFIInstrInserter.cpp}::CFIInstrInserter::runOnMachineFunction (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
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

<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/cfiinstrinserter-cpp">CFIInstrInserter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#aa22424ba23740b6a748e8d0c239b7e4c">llvm::MachineFunction::getNumBlockIDs</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a4f117e439113383ea819a6f7beb8ff0b">llvm::MachineFunction::needsFrameMoves</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcctrloopsverify-cpp/#a593cc2f204f7b2edc16ee222c37c3196">verify</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/cfiinstrinserter-cpp/#ae4389128d6cce605579bcee1c659e064">VerifyCFI</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### calculateCFAInfo() {#ac3115616e54d82d9f2bf7acdff1f457d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CFIInstrInserter::calculateCFAInfo (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Calculate cfa offset and register values valid at entry and exit for all basic blocks in a function.</p>

<p>Definition at line 107 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/cfiinstrinserter-cpp">CFIInstrInserter.cpp</a>.</p>

</div>
</div>

### calculateOutgoingCFAInfo() {#af0c1fd4e752079ccf6a04deea586b33f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CFIInstrInserter::calculateOutgoingCFAInfo (MBBCFAInfo &amp; MBBInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Calculate cfa offset and register values valid at basic block exit by checking the block for CFI instructions.</p>


<p>Block's incoming CFA info remains the same.</p>


<p>Definition at line 111 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/cfiinstrinserter-cpp">CFIInstrInserter.cpp</a>.</p>

</div>
</div>

### getCorrectCFAOffset() {#a08478df876e525ecaf28eec6f59d546a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t anonymous{CFIInstrInserter.cpp}::CFIInstrInserter::getCorrectCFAOffset (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB)</td>
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

<p>Return the cfa offset value that should be set at the beginning of a MBB if needed.</p>


<p>The negated value is needed when creating CFI instructions that set absolute offset.</p>


<p>Definition at line 124 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/cfiinstrinserter-cpp">CFIInstrInserter.cpp</a>.</p>

</div>
</div>

### insertCFIInstrs() {#a6a34ace752189f35b070c84a28845cab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CFIInstrInserter::insertCFIInstrs (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Check if incoming CFA information of a basic block matches outgoing CFA information of the previous block.</p>


<p>If it doesn't, insert CFI instruction at the beginning of the block that corrects the CFA calculation rule for that block.</p>


<p>Definition at line 120 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/cfiinstrinserter-cpp">CFIInstrInserter.cpp</a>.</p>

</div>
</div>

### reportCFAError() {#ade8f752c8e015cc3ee27e132fd0475ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CFIInstrInserter::reportCFAError (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> MBBCFAInfo &amp; Pred, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> MBBCFAInfo &amp; Succ)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 128 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/cfiinstrinserter-cpp">CFIInstrInserter.cpp</a>.</p>

</div>
</div>

### reportCSRError() {#a2af5c9f0ee948299366801714b4bc109}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CFIInstrInserter::reportCSRError (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> MBBCFAInfo &amp; Pred, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> MBBCFAInfo &amp; Succ)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 129 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/cfiinstrinserter-cpp">CFIInstrInserter.cpp</a>.</p>

</div>
</div>

### updateSuccCFAInfo() {#abad87ca87eef40e3c91ae2fa9c8784a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CFIInstrInserter::updateSuccCFAInfo (MBBCFAInfo &amp; MBBInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Update in/out cfa offset and register values for successors of the basic block.</p>

<p>Definition at line 114 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/cfiinstrinserter-cpp">CFIInstrInserter.cpp</a>.</p>

</div>
</div>

### verify() {#a5b9cd4620c0f5d861a244a04a2f5e769}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned CFIInstrInserter::verify (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Go through each MBB in a function and check that outgoing offset and register of its predecessors match incoming offset and register of that MBB, as well as that incoming offset and register of its successors match outgoing offset and register of the MBB.</p>

<p>Definition at line 134 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/cfiinstrinserter-cpp">CFIInstrInserter.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### CSRLocMap {#a5e99310de318c8baf2ad7a77aed2adf0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallDenseMap&lt;unsigned, CSRSavedLocation, 16&gt; anonymous{CFIInstrInserter.cpp}::CFIInstrInserter::CSRLocMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Map the callee save registers to the locations where they are saved.</p>

<p>Definition at line 103 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/cfiinstrinserter-cpp">CFIInstrInserter.cpp</a>.</p>

</div>
</div>

### MBBVector {#a5ade73a79c381650a7862fcad36522d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;MBBCFAInfo&gt; anonymous{CFIInstrInserter.cpp}::CFIInstrInserter::MBBVector</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Contains cfa offset and register values valid at entry and exit of basic blocks.</p>

<p>Definition at line 100 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/cfiinstrinserter-cpp">CFIInstrInserter.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Attributes

### ID {#a9701cda36f054fc30b4871cc4ca2bd43}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">char CFIInstrInserter::ID = 0</td>
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



<p>Definition at line 40 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/cfiinstrinserter-cpp">CFIInstrInserter.cpp</a>.</p>


<p>Referenced by <a href="#ac7e514de1dcee523358111d416cc6c9a">CFIInstrInserter</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/cfiinstrinserter-cpp">CFIInstrInserter.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>

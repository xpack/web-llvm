---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/mirprofileloader
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `MIRProfileLoader` Class



## Declaration

<div class="doxyDeclaration">
class llvm::MIRProfileLoader { ... }
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sampleprofileloaderbaseimpl">SampleProfileLoaderBaseImpl&lt;FT&gt;</a></td>
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

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac7b0d41f41bd4959483f76524e705bc7">SampleCoverageTracker</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0545a44b85524b238e9ca6e42437b827">MIRProfileLoader</a> (StringRef Name, StringRef RemapName, IntrusiveRefCntPtr&lt; vfs::FileSystem &gt; FS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ada46e031da560591716a22f4ef0d3a74">setInitVals</a> (MachineDominatorTree *MDT, MachinePostDominatorTree *MPDT, MachineLoopInfo *MLI, MachineBlockFrequencyInfo *MBFI, MachineOptimizationRemarkEmitter *MORE)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af54224c53b1eb4ca2e3ed18ecf90b5b3">setFSPass</a> (FSDiscriminatorPass Pass)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a31f2c5f323ca8742d0588171e0c33b49">setBranchProbs</a> (MachineFunction &amp;F)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4582acc682e4769b7c2f57d38a153f8d">runOnFunction</a> (MachineFunction &amp;F)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7cba8042f5f0daa198a43912b9bb3aa9">doInitialization</a> (Module &amp;M)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a059bc3bbf771ba306ca5a1d9005cd4c5">isValid</a> () const</td>
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

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/erroror">ErrorOr</a>&lt; uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a36557101a2fc2a308a4f6c5b51c6a739">getInstWeight</a> (const MachineInstr &amp;MI) override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineblockfrequencyinfo">MachineBlockFrequencyInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a63af5d890418b5b116bf949091615e8e">BFI</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Hold the information of the basic block frequency. <a href="#a63af5d890418b5b116bf949091615e8e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a702f69807459cc25db5754a5f179d3fc">FSDiscriminatorPass</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c3c5313c79acf26e6ff9dd9e41280a1">P</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>PassNum is the sequence number this pass is called, start from 1. <a href="#a7c3c5313c79acf26e6ff9dd9e41280a1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8e1223542cb18835ac238d7743697e8f">LowBit</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a47a26fe71892b312aa080ab7d04b1926">HighBit</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af36d9dd90a28138156ff4ddbee79d710">ProfileIsValid</a> = <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a></td>
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


<p>Definition at line 147 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirsampleprofile-cpp">MIRSampleProfile.cpp</a>.</p>


<div class="doxySectionDef">

## Friends

### SampleCoverageTracker {#ac7b0d41f41bd4959483f76524e705bc7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/sampleprofutil/samplecoveragetracker">SampleCoverageTracker</a></td>
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


<p>Definition at line 177 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirsampleprofile-cpp">MIRSampleProfile.cpp</a>.</p>


<p>Reference <a href="#ac7b0d41f41bd4959483f76524e705bc7">SampleCoverageTracker</a>.</p>


<p>Referenced by <a href="#ac7b0d41f41bd4959483f76524e705bc7">SampleCoverageTracker</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### MIRProfileLoader() {#a0545a44b85524b238e9ca6e42437b827}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MIRProfileLoader::MIRProfileLoader (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> RemapName, <a href="/web-llvm/docs/api/classes/llvm/intrusiverefcntptr">IntrusiveRefCntPtr</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/vfs/filesystem">vfs::FileSystem</a> &gt; FS)</td>
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



<p>Definition at line 166 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirsampleprofile-cpp">MIRSampleProfile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/sampleprofileloaderbaseimpl/#a12022aa707c271f81eae8ec0eebfae29">llvm::SampleProfileLoaderBaseImpl&lt; MachineFunction &gt;::FS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a> and <a href="/web-llvm/docs/api/classes/llvm/sampleprofileloaderbaseimpl/#a8914bae43b683a78d971e5954d781331">llvm::SampleProfileLoaderBaseImpl&lt; MachineFunction &gt;::SampleProfileLoaderBaseImpl</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### doInitialization() {#a7cba8042f5f0daa198a43912b9bb3aa9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MIRProfileLoader::doInitialization (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 173 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirsampleprofile-cpp">MIRSampleProfile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereader/#a1f2d1c30eab01a2f5ae485d3c3cbf5b4">llvm::sampleprof::SampleProfileReader::create</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprofileloaderbaseimpl/#aa25c9c0884c2fc1dc621c881c00485f8">llvm::SampleProfileLoaderBaseImpl&lt; MachineFunction &gt;::Filename</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprofileloaderbaseimpl/#a12022aa707c271f81eae8ec0eebfae29">llvm::SampleProfileLoaderBaseImpl&lt; MachineFunction &gt;::FS</a>, <a href="#a7c3c5313c79acf26e6ff9dd9e41280a1">P</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprofileloaderbaseimpl/#a8a061b4f421152b76653f15e18bec185">llvm::SampleProfileLoaderBaseImpl&lt; MachineFunction &gt;::ProbeManager</a>, <a href="#af36d9dd90a28138156ff4ddbee79d710">ProfileIsValid</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprofileloaderbaseimpl/#a6cda1f8872cce456c1ec260c8ef7aa24">llvm::SampleProfileLoaderBaseImpl&lt; MachineFunction &gt;::Reader</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprofileloaderbaseimpl/#ad0b57e56868a6c60929c62f1494628af">llvm::SampleProfileLoaderBaseImpl&lt; MachineFunction &gt;::RemappingFilename</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a748f2fd08e59530b1373ed304c04ffbea260ca9dd8a4577fc00b7bd5810298076">llvm::success</a>.</p>

</div>
</div>

### isValid() {#a059bc3bbf771ba306ca5a1d9005cd4c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MIRProfileLoader::isValid ()</td>
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



<p>Definition at line 174 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirsampleprofile-cpp">MIRSampleProfile.cpp</a>.</p>


<p>Reference <a href="#af36d9dd90a28138156ff4ddbee79d710">ProfileIsValid</a>.</p>

</div>
</div>

### runOnFunction() {#a4582acc682e4769b7c2f57d38a153f8d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MIRProfileLoader::runOnFunction (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; F)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 172 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirsampleprofile-cpp">MIRSampleProfile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/sampleprofileloaderbaseimpl/#ae9bae46af4ef474d7f244e4f9b67e188">llvm::SampleProfileLoaderBaseImpl&lt; MachineFunction &gt;::clearFunctionData</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprofileloaderbaseimpl/#a040b98a945772423eab83d2ce02f984a">llvm::SampleProfileLoaderBaseImpl&lt; MachineFunction &gt;::computeAndPropagateWeights</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprofileloaderbaseimpl/#a3bb6939c9a307a2d7a2bc20363b5433c">llvm::SampleProfileLoaderBaseImpl&lt; MachineFunction &gt;::getFunctionLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprofileloaderbaseimpl/#a8a061b4f421152b76653f15e18bec185">llvm::SampleProfileLoaderBaseImpl&lt; MachineFunction &gt;::ProbeManager</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples/#aa37fe7429ffcf70c306c27a55d714d31">llvm::sampleprof::FunctionSamples::ProfileIsProbeBased</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprofileloaderbaseimpl/#a6cda1f8872cce456c1ec260c8ef7aa24">llvm::SampleProfileLoaderBaseImpl&lt; MachineFunction &gt;::Reader</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprofileloaderbaseimpl/#ad9ec5be72117476a75c7dd1cc59d03f1">llvm::SampleProfileLoaderBaseImpl&lt; MachineFunction &gt;::Samples</a> and <a href="#a31f2c5f323ca8742d0588171e0c33b49">setBranchProbs</a>.</p>

</div>
</div>

### setBranchProbs() {#a31f2c5f323ca8742d0588171e0c33b49}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MIRProfileLoader::setBranchProbs (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; F)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 171 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirsampleprofile-cpp">MIRSampleProfile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a63af5d890418b5b116bf949091615e8e">BFI</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprofileloaderbaseimpl/#afd962f6862c0fa756bc3d8e2e751a955">llvm::SampleProfileLoaderBaseImpl&lt; MachineFunction &gt;::BlockWeights</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprofileloaderbaseimpl/#a25b4d69386a27e339e802ac43d47fe33">llvm::SampleProfileLoaderBaseImpl&lt; MachineFunction &gt;::EdgeWeights</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprofileloaderbaseimpl/#a4a4a260ea818b3bfe7ae4f0da463dbb9">llvm::SampleProfileLoaderBaseImpl&lt; MachineFunction &gt;::EquivalenceClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ad81901d0d8b768b240e78bf357999f34">llvm::MachineBasicBlock::findBranchDebugLoc</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirsampleprofile-cpp/#a434084fe9cf90de730f5ad17a0e202c7">FSProfileDebugBWThreshold</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirsampleprofile-cpp/#a66907e76909d974e5d55bafb49361efd">FSProfileDebugProbDiffThreshold</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a3aa22d521bd6a7e6b9f35545dc7b0f1e">llvm::MachineBasicBlock::getNumber</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a6171d209616c58347dea44a49d7675c0">llvm::MachineBasicBlock::setSuccProbability</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirsampleprofile-cpp/#a01f60d560cc6f90bd309c52be6ee51e6">ShowFSBranchProb</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a6321b189ea8fd5058663f8a87d6c23e9">llvm::MachineBasicBlock::succ_begin</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a3ddd708642d60c1661992ff8ba1b215d">llvm::MachineBasicBlock::succ_end</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a81626de817a0cb021ff8e915cf1942ed">llvm::MachineBasicBlock::succ_size</a> and <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ad88ff1529541fb4e243cc8ed90b11131">llvm::MachineBasicBlock::successors</a>.</p>


<p>Referenced by <a href="#a4582acc682e4769b7c2f57d38a153f8d">runOnFunction</a>.</p>

</div>
</div>

### setFSPass() {#af54224c53b1eb4ca2e3ed18ecf90b5b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MIRProfileLoader::setFSPass (<a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a702f69807459cc25db5754a5f179d3fc">FSDiscriminatorPass</a> Pass)</td>
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



<p>Definition at line 159 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirsampleprofile-cpp">MIRSampleProfile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a08ea26e634dcb06e8416fab025c91ffd">llvm::getFSPassBitBegin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a54f635dae16f504eb603ff2842f39d97">llvm::getFSPassBitEnd</a>, <a href="#a47a26fe71892b312aa080ab7d04b1926">HighBit</a>, <a href="#a8e1223542cb18835ac238d7743697e8f">LowBit</a> and <a href="#a7c3c5313c79acf26e6ff9dd9e41280a1">P</a>.</p>

</div>
</div>

### setInitVals() {#ada46e031da560591716a22f4ef0d3a74}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MIRProfileLoader::setInitVals (<a href="/web-llvm/docs/api/classes/llvm/machinedominatortree">MachineDominatorTree</a> * MDT, <a href="/web-llvm/docs/api/classes/llvm/machinepostdominatortree">MachinePostDominatorTree</a> * MPDT, <a href="/web-llvm/docs/api/classes/llvm/machineloopinfo">MachineLoopInfo</a> * MLI, <a href="/web-llvm/docs/api/classes/llvm/machineblockfrequencyinfo">MachineBlockFrequencyInfo</a> * MBFI, <a href="/web-llvm/docs/api/classes/llvm/machineoptimizationremarkemitter">MachineOptimizationRemarkEmitter</a> * MORE)</td>
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



<p>Definition at line 150 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirsampleprofile-cpp">MIRSampleProfile.cpp</a>.</p>


<p>References <a href="#a63af5d890418b5b116bf949091615e8e">BFI</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprofileloaderbaseimpl/#a726028c50f8c9cea16a85ffa721a78b4">llvm::SampleProfileLoaderBaseImpl&lt; MachineFunction &gt;::DT</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprofileloaderbaseimpl/#ae5efdc714ce4789b9a1ffe59bb055cc7">llvm::SampleProfileLoaderBaseImpl&lt; MachineFunction &gt;::LI</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#ace441594c4bd8da94fd64b1c612ca948">MORE</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprofileloaderbaseimpl/#a293c85647f9dcb78f29ad5ab31e5a7f9">llvm::SampleProfileLoaderBaseImpl&lt; MachineFunction &gt;::ORE</a> and <a href="/web-llvm/docs/api/classes/llvm/sampleprofileloaderbaseimpl/#aa48c470371fe9507bec17abd3333fd1f">llvm::SampleProfileLoaderBaseImpl&lt; MachineFunction &gt;::PDT</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### getInstWeight() {#a36557101a2fc2a308a4f6c5b51c6a739}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ErrorOr&lt; uint64_t &gt; llvm::MIRProfileLoader::getInstWeight (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
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



<p>Definition at line 193 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirsampleprofile-cpp">MIRSampleProfile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/sampleprofileloaderbaseimpl/#a3fd239026aba79e9aaf5b81578f4198c">llvm::SampleProfileLoaderBaseImpl&lt; MachineFunction &gt;::getInstWeightImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprofileloaderbaseimpl/#acdcff307bede233f8221f618d262b6df">llvm::SampleProfileLoaderBaseImpl&lt; MachineFunction &gt;::getProbeWeight</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a90b03a5ed7ead5551ff645caf7804633">llvm::ImprovedFSDiscriminator</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples/#aa37fe7429ffcf70c306c27a55d714d31">llvm::sampleprof::FunctionSamples::ProfileIsProbeBased</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### BFI {#a63af5d890418b5b116bf949091615e8e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBlockFrequencyInfo* llvm::MIRProfileLoader::BFI</td>
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

<p>Hold the information of the basic block frequency.</p>

<p>Definition at line 180 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirsampleprofile-cpp">MIRSampleProfile.cpp</a>.</p>


<p>Referenced by <a href="#a31f2c5f323ca8742d0588171e0c33b49">setBranchProbs</a> and <a href="#ada46e031da560591716a22f4ef0d3a74">setInitVals</a>.</p>

</div>
</div>

### HighBit {#a47a26fe71892b312aa080ab7d04b1926}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MIRProfileLoader::HighBit</td>
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



<p>Definition at line 190 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirsampleprofile-cpp">MIRSampleProfile.cpp</a>.</p>


<p>Referenced by <a href="#af54224c53b1eb4ca2e3ed18ecf90b5b3">setFSPass</a>.</p>

</div>
</div>

### LowBit {#a8e1223542cb18835ac238d7743697e8f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MIRProfileLoader::LowBit</td>
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



<p>Definition at line 187 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirsampleprofile-cpp">MIRSampleProfile.cpp</a>.</p>


<p>Referenced by <a href="#af54224c53b1eb4ca2e3ed18ecf90b5b3">setFSPass</a>.</p>

</div>
</div>

### P {#a7c3c5313c79acf26e6ff9dd9e41280a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FSDiscriminatorPass llvm::MIRProfileLoader::P</td>
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

<p>PassNum is the sequence number this pass is called, start from 1.</p>

<p>Definition at line 183 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirsampleprofile-cpp">MIRSampleProfile.cpp</a>.</p>


<p>Referenced by <a href="#a7cba8042f5f0daa198a43912b9bb3aa9">doInitialization</a> and <a href="#af54224c53b1eb4ca2e3ed18ecf90b5b3">setFSPass</a>.</p>

</div>
</div>

### ProfileIsValid {#af36d9dd90a28138156ff4ddbee79d710}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MIRProfileLoader::ProfileIsValid = <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a></td>
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



<p>Definition at line 192 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirsampleprofile-cpp">MIRSampleProfile.cpp</a>.</p>


<p>Referenced by <a href="#a7cba8042f5f0daa198a43912b9bb3aa9">doInitialization</a> and <a href="#a059bc3bbf771ba306ca5a1d9005cd4c5">isValid</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/mirsampleprofile-cpp">MIRSampleProfile.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>

---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-hexagonrdfopt-cpp-/hexagondce
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `HexagonDCE` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct anonymous{HexagonRDFOpt.cpp}::HexagonDCE { ... }
</div>

## Base struct

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/rdf/deadcodeelimination">DeadCodeElimination</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ace9ef8ab5670788c6b10bdadfc43fe61">HexagonDCE</a> (DataFlowGraph &amp;G, MachineRegisterInfo &amp;MRI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3c29fb0e6cda6fc8b1839501e9b63529">rewrite</a> (NodeAddr&lt; InstrNode * &gt; IA, SetVector&lt; NodeId &gt; &amp;Remove)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af147b385bf71cd50563c0d23b0f9baf7">removeOperand</a> (NodeAddr&lt; InstrNode * &gt; IA, unsigned OpNum)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2fdc22ba5c1d80ca60c2adcd35b3cd41">run</a> ()</td>
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


<p>Definition at line 96 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonrdfopt-cpp">HexagonRDFOpt.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### HexagonDCE() {#ace9ef8ab5670788c6b10bdadfc43fe61}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{HexagonRDFOpt.cpp}::HexagonDCE::HexagonDCE (<a href="/web-llvm/docs/api/structs/llvm/rdf/dataflowgraph">DataFlowGraph</a> &amp; G, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI)</td>
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



<p>Definition at line 97 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonrdfopt-cpp">HexagonRDFOpt.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/rdf/deadcodeelimination/#aa6d5a6946206dc321fe3a47988a3f213">llvm::rdf::DeadCodeElimination::DeadCodeElimination</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ad96b7cf3182ce2ba85e5a7a93b12c441">G</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### removeOperand() {#af147b385bf71cd50563c0d23b0f9baf7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HexagonDCE::removeOperand (<a href="/web-llvm/docs/api/structs/llvm/rdf/nodeaddr">NodeAddr</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/rdf/instrnode">InstrNode</a> * &gt; IA, unsigned OpNum)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 101 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonrdfopt-cpp">HexagonRDFOpt.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/rdf/nodeaddr/#a150c10db309dcfa7a1093dc0c698d663">llvm::rdf::NodeAddr&lt; T &gt;::Addr</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/deadcodeelimination/#a4a48f3770514abec1ab3ef56e1ab8070">llvm::rdf::DeadCodeElimination::getDFG</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#adb33f3ede2f5bfc9b3ee658aaf648492">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::insert</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sioptimizeexecmaskingprera-cpp/#a3e47bdb3e296b00df96eff7896fa57bf">RA</a>.</p>


<p>Referenced by <a href="#a3c29fb0e6cda6fc8b1839501e9b63529">rewrite</a>.</p>

</div>
</div>

### rewrite() {#a3c29fb0e6cda6fc8b1839501e9b63529}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool HexagonDCE::rewrite (<a href="/web-llvm/docs/api/structs/llvm/rdf/nodeaddr">NodeAddr</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/rdf/instrnode">InstrNode</a> * &gt; IA, <a href="/web-llvm/docs/api/classes/llvm/setvector">SetVector</a>&lt; NodeId &gt; &amp; Remove)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 100 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonrdfopt-cpp">HexagonRDFOpt.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/rdf/nodeaddr/#a150c10db309dcfa7a1093dc0c698d663">llvm::rdf::NodeAddr&lt; T &gt;::Addr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0d10fe510ced2849a8074fe81e5d04ce">llvm::all_of</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a6a9f043784cf87001c84980afa76da82">D</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/deadcodeelimination/#a0342efb029e23ad0521814134f16d71a">llvm::rdf::DeadCodeElimination::getDeadNodes</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/deadcodeelimination/#a4a48f3770514abec1ab3ef56e1ab8070">llvm::rdf::DeadCodeElimination::getDFG</a>, <a href="/web-llvm/docs/api/classes/llvm/setvector/#af34eb71cc483e84d2eca80575cb9ccde">llvm::SetVector&lt; T, Vector, Set, N &gt;::insert</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a979659ec464cee64a84df219494fc2ea">IsDead</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonii/#aee75e70da0fb5b84ea847ab7daf9429ba7740d7bab51111fc9a73b550c5002e67">llvm::HexagonII::PostInc</a>, <a href="#af147b385bf71cd50563c0d23b0f9baf7">removeOperand</a> and <a href="/web-llvm/docs/api/structs/llvm/rdf/deadcodeelimination/#a3489a989f719ff09485f7947cd58647d">llvm::rdf::DeadCodeElimination::trace</a>.</p>


<p>Referenced by <a href="#a2fdc22ba5c1d80ca60c2adcd35b3cd41">run</a>.</p>

</div>
</div>

### run() {#a2fdc22ba5c1d80ca60c2adcd35b3cd41}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool HexagonDCE::run ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 103 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonrdfopt-cpp">HexagonRDFOpt.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/rdf/nodeaddr/#a150c10db309dcfa7a1093dc0c698d663">llvm::rdf::NodeAddr&lt; T &gt;::Addr</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/deadcodeelimination/#a4c7ab56ddc8e8b9a4f7903e9268c10e9">llvm::rdf::DeadCodeElimination::collect</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a60a348350395aef11d68f58111bcf499">llvm::erase</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/deadcodeelimination/#ab8d2a4f384a62322a138c343714c0fa5">llvm::rdf::DeadCodeElimination::getDeadInstrs</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/deadcodeelimination/#a0342efb029e23ad0521814134f16d71a">llvm::rdf::DeadCodeElimination::getDeadNodes</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/deadcodeelimination/#a4a48f3770514abec1ab3ef56e1ab8070">llvm::rdf::DeadCodeElimination::getDFG</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/nodeaddr/#a7e398d2285d22a33c3358ed7904725d7">llvm::rdf::NodeAddr&lt; T &gt;::Id</a>, <a href="/web-llvm/docs/api/classes/llvm/setvector/#af34eb71cc483e84d2eca80575cb9ccde">llvm::SetVector&lt; T, Vector, Set, N &gt;::insert</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sioptimizeexecmaskingprera-cpp/#a3e47bdb3e296b00df96eff7896fa57bf">RA</a>, <a href="#a3c29fb0e6cda6fc8b1839501e9b63529">rewrite</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/nodeattrs/#a96730c2fe7aaa0b753e7483d1e6a121da91376b865b14d172148590ff1c69e403">llvm::rdf::NodeAttrs::Stmt</a> and <a href="/web-llvm/docs/api/structs/llvm/rdf/deadcodeelimination/#a3489a989f719ff09485f7947cd58647d">llvm::rdf::DeadCodeElimination::trace</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-hexagonrdfopt-cpp-/hexagonrdfopt/#acb675de67baa3aed372fdf62b440c866">anonymous{HexagonRDFOpt.cpp}::HexagonRDFOpt::runOnMachineFunction</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonrdfopt-cpp">HexagonRDFOpt.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>

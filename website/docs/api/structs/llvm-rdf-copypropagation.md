---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/rdf/copypropagation
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `CopyPropagation` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct llvm::rdf::CopyPropagation { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/rdfcopy-h">Target/Hexagon/RDFCopy.h</a>"
</div>

## Derived Structs

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-hexagonrdfopt-cpp-/hexagoncp">HexagonCP</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a980980454ebf2bdb48750179e760779a">EqualityMap</a> = std::map&lt; <a href="/web-llvm/docs/api/structs/llvm/rdf/registerref">RegisterRef</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/registerref">RegisterRef</a> &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0e7a6c1543a19810b46b9b7cb5a61e6d">CopyPropagation</a> (DataFlowGraph &amp;dfg)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abdb2fd2eb0466be1d69dbcf2fac72f4b">~CopyPropagation</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab5cc393f3a921f0a6fe0505561a80e23">run</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeefba1692bb068b29ec3ddbbfaa11916">trace</a> (bool On)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0ce243e4d5f1161290acedf54233b43c">trace</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/rdf/dataflowgraph">DataFlowGraph</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab829066c284b79c6cf7a7f9c3327529d">getDFG</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab12951430f2984b5f0b26e265ccb8ac7">interpretAsCopy</a> (const MachineInstr *MI, EqualityMap &amp;EM)</td>
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

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af716d8ee7115ab445794c6fc22d5fcd3">recordCopy</a> (NodeAddr&lt; StmtNode * &gt; SA, EqualityMap &amp;EM)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4dcd238951413792e0b96d489ad5698e">updateMap</a> (NodeAddr&lt; InstrNode * &gt; IA)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a92735b6b81465a408fee528d884481cd">scanBlock</a> (MachineBasicBlock *B)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinedominatortree">MachineDominatorTree</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a68024e6fbaa46f59ecd337f02c3b779c">MDT</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/rdf/dataflowgraph">DataFlowGraph</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b863f59be0c9e1e79a61dfdef2247b9">DFG</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/rdf/dataflowgraph/#af9ba4adb1171c03b53e7c67ab59825ab">DataFlowGraph::DefStackMap</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae258e560f2bbce5c247581ce7e62fe04">DefM</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ada35d256150fff175aaabb4a3965a129">Trace</a> = false</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::map&lt; <a href="/web-llvm/docs/api/structs/llvm/rdf/registerref">RegisterRef</a>, std::map&lt; <a href="/web-llvm/docs/api/namespaces/llvm/rdf/#a9c5c1abf54c7f5aaf8add770214aba5d">NodeId</a>, <a href="/web-llvm/docs/api/namespaces/llvm/rdf/#a9c5c1abf54c7f5aaf8add770214aba5d">NodeId</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af422574c2d98e0d25a3f9a8e5d486108">RDefMap</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::map&lt; <a href="/web-llvm/docs/api/namespaces/llvm/rdf/#a9c5c1abf54c7f5aaf8add770214aba5d">NodeId</a>, <a href="#a980980454ebf2bdb48750179e760779a">EqualityMap</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac94fdac00d734a9ca2e58f400deaa89a">CopyMap</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/namespaces/llvm/rdf/#a9c5c1abf54c7f5aaf8add770214aba5d">NodeId</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9bc5e97d193ce27ac1fdb9fef9647574">Copies</a></td>
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


<p>Definition at line 27 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/rdfcopy-h">RDFCopy.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### EqualityMap {#a980980454ebf2bdb48750179e760779a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::rdf::CopyPropagation::EqualityMap =  std::map&lt;RegisterRef, RegisterRef&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/rdfcopy-h">RDFCopy.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### CopyPropagation() {#a0e7a6c1543a19810b46b9b7cb5a61e6d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::rdf::CopyPropagation::CopyPropagation (<a href="/web-llvm/docs/api/structs/llvm/rdf/dataflowgraph">DataFlowGraph</a> &amp; dfg)</td>
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



<p>Definition at line 28 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/rdfcopy-h">RDFCopy.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-hexagonrdfopt-cpp-/hexagoncp/#a7f9efca12e0615268c2951652697d93b">anonymous{HexagonRDFOpt.cpp}::HexagonCP::HexagonCP</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~CopyPropagation() {#abdb2fd2eb0466be1d69dbcf2fac72f4b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual llvm::rdf::CopyPropagation::~CopyPropagation ()</td>
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



<p>Definition at line 31 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/rdfcopy-h">RDFCopy.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getDFG() {#ab829066c284b79c6cf7a7f9c3327529d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DataFlowGraph &amp; llvm::rdf::CopyPropagation::getDFG ()</td>
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



<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/rdfcopy-h">RDFCopy.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-hexagonrdfopt-cpp-/hexagoncp/#afbd23f1436bf2680a83324a63b37dbe4">anonymous{HexagonRDFOpt.cpp}::HexagonCP::interpretAsCopy</a>.</p>

</div>
</div>

### interpretAsCopy() {#ab12951430f2984b5f0b26e265ccb8ac7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CopyPropagation::interpretAsCopy (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI, <a href="#a980980454ebf2bdb48750179e760779a">EqualityMap</a> &amp; EM)</td>
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



<p>Declaration at line 39 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/rdfcopy-h">RDFCopy.h</a>, definition at line 39 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/rdfcopy-cpp">RDFCopy.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ab12951430f2984b5f0b26e265ccb8ac7">interpretAsCopy</a>, <a href="/web-llvm/docs/api/classes/llvm/register/#afacc26f29d80e10be4785a96ed6444dc">llvm::Register::isPhysicalRegister</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/registerref/#aff344ef4b411a5f449ef8839d98f1750">llvm::rdf::RegisterRef::Reg</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-hexagonrdfopt-cpp-/hexagoncp/#afbd23f1436bf2680a83324a63b37dbe4">anonymous{HexagonRDFOpt.cpp}::HexagonCP::interpretAsCopy</a> and <a href="#ab12951430f2984b5f0b26e265ccb8ac7">interpretAsCopy</a>.</p>

</div>
</div>

### run() {#ab5cc393f3a921f0a6fe0505561a80e23}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CopyPropagation::run ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 33 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/rdfcopy-h">RDFCopy.h</a>, definition at line 128 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/rdfcopy-cpp">RDFCopy.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/rdf/nodeaddr/#a150c10db309dcfa7a1093dc0c698d663">llvm::rdf::NodeAddr&lt; T &gt;::Addr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/groups/arcopt/#gaa57b1a4e6a1c79233913139635169cf1">Changed</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/rdfcopy-cpp/#a8340a1059f51d378627d58e2c0907eb8">CpCount</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/rdfcopy-cpp/#a4331c27a862ca8bb0a9494193bb4a456">CpLimit</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/physicalregisterinfo/#a8bc3d5451e079cf6bcbb2df76f71f293">llvm::rdf::PhysicalRegisterInfo::equal_to</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/nodeattrs/#a96730c2fe7aaa0b753e7483d1e6a121dab376783962985abbe49aaecaf1e44d3f">llvm::rdf::NodeAttrs::Fixed</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/stmtnode/#ae16b26d08408d8aec231bbe13bc9e9f9">llvm::rdf::StmtNode::getCode</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/refnode/#a37650e1cbcdcbae779a3b0b09367d067">llvm::rdf::RefNode::getSibling</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/nodeaddr/#a7e398d2285d22a33c3358ed7904725d7">llvm::rdf::NodeAddr&lt; T &gt;::Id</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsubregindexiterator/#a4bc33f765fada85ad09c4910d122832d">llvm::MCSubRegIndexIterator::isValid</a>, <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass/#a0363c6cc08fe464f66f9e53239bb35e3">llvm::TargetRegisterClass::LaneMask</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/nodeattrs/#a96730c2fe7aaa0b753e7483d1e6a121da1ec381406c0c91aef4a414bdba131112">llvm::rdf::NodeAttrs::PhiRef</a>, <a href="/web-llvm/docs/api/namespaces/llvm/rdf/#a51d767cf7aced5470bd37a0ff02545a7">llvm::rdf::Print</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/nodeattrs/#a96730c2fe7aaa0b753e7483d1e6a121da91376b865b14d172148590ff1c69e403">llvm::rdf::NodeAttrs::Stmt</a>, <a href="#a0ce243e4d5f1161290acedf54233b43c">trace</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>

</div>
</div>

### trace() {#aeefba1692bb068b29ec3ddbbfaa11916}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::rdf::CopyPropagation::trace (bool On)</td>
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



<p>Definition at line 34 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/rdfcopy-h">RDFCopy.h</a>.</p>

</div>
</div>

### trace() {#a0ce243e4d5f1161290acedf54233b43c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::rdf::CopyPropagation::trace ()</td>
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



<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/rdfcopy-h">RDFCopy.h</a>.</p>


<p>Referenced by <a href="#ab5cc393f3a921f0a6fe0505561a80e23">run</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### recordCopy() {#af716d8ee7115ab445794c6fc22d5fcd3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CopyPropagation::recordCopy (<a href="/web-llvm/docs/api/structs/llvm/rdf/nodeaddr">NodeAddr</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/rdf/stmtnode">StmtNode</a> * &gt; SA, <a href="#a980980454ebf2bdb48750179e760779a">EqualityMap</a> &amp; EM)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 53 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/rdfcopy-h">RDFCopy.h</a>, definition at line 64 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/rdfcopy-cpp">RDFCopy.cpp</a>.</p>

</div>
</div>

### scanBlock() {#a92735b6b81465a408fee528d884481cd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CopyPropagation::scanBlock (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * B)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 55 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/rdfcopy-h">RDFCopy.h</a>, definition at line 103 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/rdfcopy-cpp">RDFCopy.cpp</a>.</p>

</div>
</div>

### updateMap() {#a4dcd238951413792e0b96d489ad5698e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CopyPropagation::updateMap (<a href="/web-llvm/docs/api/structs/llvm/rdf/nodeaddr">NodeAddr</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/rdf/instrnode">InstrNode</a> * &gt; IA)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 54 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/rdfcopy-h">RDFCopy.h</a>, definition at line 79 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/rdfcopy-cpp">RDFCopy.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Copies {#a9bc5e97d193ce27ac1fdb9fef9647574}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;NodeId&gt; llvm::rdf::CopyPropagation::Copies</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/rdfcopy-h">RDFCopy.h</a>.</p>

</div>
</div>

### CopyMap {#ac94fdac00d734a9ca2e58f400deaa89a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::map&lt;NodeId, EqualityMap&gt; llvm::rdf::CopyPropagation::CopyMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/rdfcopy-h">RDFCopy.h</a>.</p>

</div>
</div>

### DefM {#ae258e560f2bbce5c247581ce7e62fe04}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DataFlowGraph::DefStackMap llvm::rdf::CopyPropagation::DefM</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/rdfcopy-h">RDFCopy.h</a>.</p>

</div>
</div>

### DFG {#a6b863f59be0c9e1e79a61dfdef2247b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DataFlowGraph&amp; llvm::rdf::CopyPropagation::DFG</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/rdfcopy-h">RDFCopy.h</a>.</p>

</div>
</div>

### MDT {#a68024e6fbaa46f59ecd337f02c3b779c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachineDominatorTree&amp; llvm::rdf::CopyPropagation::MDT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/rdfcopy-h">RDFCopy.h</a>.</p>

</div>
</div>

### RDefMap {#af422574c2d98e0d25a3f9a8e5d486108}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::map&lt;RegisterRef,std::map&lt;NodeId,NodeId&gt; &gt; llvm::rdf::CopyPropagation::RDefMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/rdfcopy-h">RDFCopy.h</a>.</p>

</div>
</div>

### Trace {#ada35d256150fff175aaabb4a3965a129}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::rdf::CopyPropagation::Trace = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 45 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/rdfcopy-h">RDFCopy.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/rdfcopy-cpp">RDFCopy.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/rdfcopy-h">RDFCopy.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>

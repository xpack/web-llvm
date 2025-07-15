---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-codegenprepare-cpp-/addressingmodecombiner
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `AddressingModeCombiner` Class Reference

<p>A helper class for combining addressing modes. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class anonymous{CodeGenPrepare.cpp}::AddressingModeCombiner { ... }
</div>

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; <a href="#a1b28ecf9179667dc73d11453929c71e1">FoldAddrToValueMapping</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a> *, <a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a> * &gt; <a href="#a3e916b59cafed070b30cbd8614712d5e">PHIPair</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a12d7bf62cc9469dcc8776c045ad91169">AddressingModeCombiner</a> (const SimplifyQuery &amp;_SQ, Value *OriginalValue)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a11b3fca9e6b5a0a86f833919280c8d6d">~AddressingModeCombiner</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-codegenprepare-cpp-/extaddrmode">ExtAddrMode</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad554dafe341161df27c6e4762ce5ac82">getAddrMode</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the combined <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/msp430/lib/target/msp430/disassembler/msp430disassembler-cpp/#abf132b4ad93f3557cd3956577592ba68">AddrMode</a>. <a href="#ad554dafe341161df27c6e4762ce5ac82">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a68677e52356488f3516d001f127588a5">addNewAddrMode</a> (ExtAddrMode &amp;NewAddrMode)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add a new <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/msp430/lib/target/msp430/disassembler/msp430disassembler-cpp/#abf132b4ad93f3557cd3956577592ba68">AddrMode</a> if it's compatible with the AddrModes we already have. <a href="#a68677e52356488f3516d001f127588a5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a063d1fe1021fb19338b10705adb5f075">combineAddrModes</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Combine the addressing modes we've collected into a single addressing mode. <a href="#a063d1fe1021fb19338b10705adb5f075">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4d66e18ef90b94b6d6df3902353e9e23">eraseCommonValueIfDead</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><span class="doxyComputerOutput">CommonValue</span> may be a placeholder inserted by us. <a href="#a4d66e18ef90b94b6d6df3902353e9e23">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7f19775e63e43977f53d7e586d82bc2b">initializeMap</a> (FoldAddrToValueMapping &amp;Map)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Initialize Map with anchor values. <a href="#a7f19775e63e43977f53d7e586d82bc2b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a892ca606369f593fecbb6a459d55feef">findCommon</a> (FoldAddrToValueMapping &amp;Map)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>We have mapping between value A and other value B where B was a field in addressing mode represented by A. <a href="#a892ca606369f593fecbb6a459d55feef">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac861197af1708f2e86f42c3b993344d">MatchPhiNode</a> (PHINode *PHI, PHINode *Candidate, SmallSetVector&lt; PHIPair, 8 &gt; &amp;Matcher, PhiNodeSet &amp;PhiNodesToMatch)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Try to match PHI node to Candidate. <a href="#aac861197af1708f2e86f42c3b993344d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae695cf315e4383c36383d0b46650ceac">MatchPhiSet</a> (SimplificationTracker &amp;ST, bool AllowNewPhiNodes, unsigned &amp;PhiNotMatchedCount)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>For the given set of PHI nodes (in the <a href="/web-llvm/docs/api/classes/anonymous-codegenprepare-cpp-/simplificationtracker">SimplificationTracker</a>) try to find their equivalents. <a href="#ae695cf315e4383c36383d0b46650ceac">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e7310590b72a93cf2b01b3fef16e8dc">FillPlaceholders</a> (FoldAddrToValueMapping &amp;Map, SmallVectorImpl&lt; Value * &gt; &amp;TraverseOrder, SimplificationTracker &amp;ST)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Fill the placeholders with values from predecessors and simplify them. <a href="#a2e7310590b72a93cf2b01b3fef16e8dc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a712660a2483aec5a62591f70ae98b7e8">InsertPlaceholders</a> (FoldAddrToValueMapping &amp;Map, SmallVectorImpl&lt; Value * &gt; &amp;TraverseOrder, SimplificationTracker &amp;ST)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Starting from original value recursively iterates over def-use chain up to known ending values represented in a map. <a href="#a712660a2483aec5a62591f70ae98b7e8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a651750639f76e3c6f9173e4ee5b31a8e">addrModeCombiningAllowed</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/structs/anonymous-codegenprepare-cpp-/extaddrmode">ExtAddrMode</a>, 16 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8303dbf9f0483b7f0a950ff1038cf65e">AddrModes</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The addressing modes we've collected. <a href="#a8303dbf9f0483b7f0a950ff1038cf65e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-codegenprepare-cpp-/extaddrmode/#a10aef7c4018bbcd7beefca2dcf4e3c3b">ExtAddrMode::FieldName</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54fa444e173b68e7ab0d38366b6c1935">DifferentField</a> = <a href="/web-llvm/docs/api/structs/anonymous-codegenprepare-cpp-/extaddrmode/#a10aef7c4018bbcd7beefca2dcf4e3c3bade3fdafc2a520488937de65060546976">ExtAddrMode::NoField</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The field in which the AddrModes differ, when we have more than one. <a href="#a54fa444e173b68e7ab0d38366b6c1935">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a36ce47b3102dc454305f24d6c1dd3746">AllAddrModesTrivial</a> = <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Are the AddrModes that we have all just equal to their original values? <a href="#a36ce47b3102dc454305f24d6c1dd3746">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae4f34793b9517138b8da263f8a8919dd">CommonType</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Common <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> for all different fields in addressing modes. <a href="#ae4f34793b9517138b8da263f8a8919dd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/simplifyquery">SimplifyQuery</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1c5f80fa986b1a15fabbfb4653847af0">SQ</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/structs/llvm/simplifyquery">SimplifyQuery</a> for simplifyInstruction utility. <a href="#a1c5f80fa986b1a15fabbfb4653847af0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a93d365101ee4c4352162cb59af079a56">Original</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Original Address. <a href="#a93d365101ee4c4352162cb59af079a56">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#affc9fddac9f3760872a8a2a6d566912e">CommonValue</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Common value among addresses. <a href="#affc9fddac9f3760872a8a2a6d566912e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>A helper class for combining addressing modes.</p>

<p>Definition at line 4072 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### FoldAddrToValueMapping {#a1b28ecf9179667dc73d11453929c71e1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef DenseMap&lt;Value *, Value *&gt; anonymous{CodeGenPrepare.cpp}::AddressingModeCombiner::FoldAddrToValueMapping</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 4073 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

### PHIPair {#a3e916b59cafed070b30cbd8614712d5e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef std::pair&lt;PHINode *, PHINode *&gt; anonymous{CodeGenPrepare.cpp}::AddressingModeCombiner::PHIPair</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 4074 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### AddressingModeCombiner() {#a12d7bf62cc9469dcc8776c045ad91169}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{CodeGenPrepare.cpp}::AddressingModeCombiner::AddressingModeCombiner (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/simplifyquery">SimplifyQuery</a> &amp; _SQ, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * OriginalValue)</td>
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



<p>Definition at line 4099 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~AddressingModeCombiner() {#a11b3fca9e6b5a0a86f833919280c8d6d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{CodeGenPrepare.cpp}::AddressingModeCombiner::~AddressingModeCombiner ()</td>
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



<p>Definition at line 4102 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addNewAddrMode() {#a68677e52356488f3516d001f127588a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{CodeGenPrepare.cpp}::AddressingModeCombiner::addNewAddrMode (<a href="/web-llvm/docs/api/structs/anonymous-codegenprepare-cpp-/extaddrmode">ExtAddrMode</a> &amp; NewAddrMode)</td>
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

<p>Add a new <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/msp430/lib/target/msp430/disassembler/msp430disassembler-cpp/#abf132b4ad93f3557cd3956577592ba68">AddrMode</a> if it's compatible with the AddrModes we already have.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>True iff we succeeded in doing so.</p></dd>
</dl>


<p>Definition at line 4110 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/anonymous-codegenprepare-cpp-/extaddrmode/#a10aef7c4018bbcd7beefca2dcf4e3c3baf4d9622b8e7495cb65099c1333085a24">anonymous{CodeGenPrepare.cpp}::ExtAddrMode::BaseGVField</a>, <a href="/web-llvm/docs/api/structs/anonymous-codegenprepare-cpp-/extaddrmode/#a10aef7c4018bbcd7beefca2dcf4e3c3ba00291a866d6acfad336e7606f1c17c92">anonymous{CodeGenPrepare.cpp}::ExtAddrMode::BaseOffsField</a>, <a href="/web-llvm/docs/api/structs/anonymous-codegenprepare-cpp-/extaddrmode/#af16961a6894c56bc7f08641a2538167d">anonymous{CodeGenPrepare.cpp}::ExtAddrMode::isTrivial</a>, <a href="/web-llvm/docs/api/structs/anonymous-codegenprepare-cpp-/extaddrmode/#a10aef7c4018bbcd7beefca2dcf4e3c3ba487a1fc3c02e9df7cb63a01968499611">anonymous{CodeGenPrepare.cpp}::ExtAddrMode::MultipleFields</a>, <a href="/web-llvm/docs/api/structs/anonymous-codegenprepare-cpp-/extaddrmode/#a10aef7c4018bbcd7beefca2dcf4e3c3bade3fdafc2a520488937de65060546976">anonymous{CodeGenPrepare.cpp}::ExtAddrMode::NoField</a>, <a href="/web-llvm/docs/api/structs/anonymous-codegenprepare-cpp-/extaddrmode/#ab3efdd9ffd185b09958bdb0f6697c3eb">anonymous{CodeGenPrepare.cpp}::ExtAddrMode::ScaledReg</a> and <a href="/web-llvm/docs/api/structs/anonymous-codegenprepare-cpp-/extaddrmode/#a10aef7c4018bbcd7beefca2dcf4e3c3bad9eaab024b6516aae7cd2912a8ed4101">anonymous{CodeGenPrepare.cpp}::ExtAddrMode::ScaleField</a>.</p>

</div>
</div>

### combineAddrModes() {#a063d1fe1021fb19338b10705adb5f075}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{CodeGenPrepare.cpp}::AddressingModeCombiner::combineAddrModes ()</td>
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

<p>Combine the addressing modes we've collected into a single addressing mode.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>True iff we successfully combined them or we only had one so didn't need to combine them anyway.</p></dd>
</dl>


<p>Definition at line 4164 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/structs/anonymous-codegenprepare-cpp-/extaddrmode/#a10aef7c4018bbcd7beefca2dcf4e3c3bade3fdafc2a520488937de65060546976">anonymous{CodeGenPrepare.cpp}::ExtAddrMode::NoField</a>.</p>

</div>
</div>

### getAddrMode() {#ad554dafe341161df27c6e4762ce5ac82}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const ExtAddrMode &amp; anonymous{CodeGenPrepare.cpp}::AddressingModeCombiner::getAddrMode ()</td>
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

<p>Get the combined <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/msp430/lib/target/msp430/disassembler/msp430disassembler-cpp/#abf132b4ad93f3557cd3956577592ba68">AddrMode</a>.</p>

<p>Definition at line 4105 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### addrModeCombiningAllowed() {#a651750639f76e3c6f9173e4ee5b31a8e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{CodeGenPrepare.cpp}::AddressingModeCombiner::addrModeCombiningAllowed ()</td>
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



<p>Definition at line 4473 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

### eraseCommonValueIfDead() {#a4d66e18ef90b94b6d6df3902353e9e23}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{CodeGenPrepare.cpp}::AddressingModeCombiner::eraseCommonValueIfDead ()</td>
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

<p><span class="doxyComputerOutput">CommonValue</span> may be a placeholder inserted by us.</p>


<p>If the placeholder is not used, we should remove this dead instruction.</p>


<p>Definition at line 4197 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

### FillPlaceholders() {#a2e7310590b72a93cf2b01b3fef16e8dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{CodeGenPrepare.cpp}::AddressingModeCombiner::FillPlaceholders (<a href="/web-llvm/docs/api/classes/llvm/densemap">FoldAddrToValueMapping</a> &amp; Map, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; &amp; TraverseOrder, <a href="/web-llvm/docs/api/classes/anonymous-codegenprepare-cpp-/simplificationtracker">SimplificationTracker</a> &amp; ST)</td>
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

<p>Fill the placeholders with values from predecessors and simplify them.</p>

<p>Definition at line 4395 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

### findCommon() {#a892ca606369f593fecbb6a459d55feef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * anonymous{CodeGenPrepare.cpp}::AddressingModeCombiner::findCommon (<a href="/web-llvm/docs/api/classes/llvm/densemap">FoldAddrToValueMapping</a> &amp; Map)</td>
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

<p>We have mapping between value A and other value B where B was a field in addressing mode represented by A.</p>


<p>Also we have an original value C representing an address we start with. Traversing from C through phi and selects we ended up with A's in a map. This utility function tries to find a value V which is a field in addressing mode C and traversing through phi nodes and selects we will end up in corresponded values B in a map. The utility will create a new Phi/Selects if needed.</p>


<p>Definition at line 4254 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

### initializeMap() {#a7f19775e63e43977f53d7e586d82bc2b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{CodeGenPrepare.cpp}::AddressingModeCombiner::initializeMap (<a href="/web-llvm/docs/api/classes/llvm/densemap">FoldAddrToValueMapping</a> &amp; Map)</td>
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

<p>Initialize Map with anchor values.</p>


<p>For address seen we set the value of different field saw in this address. At the same time we find a common type for different field we will use to create new Phi/Select nodes. Keep it in CommonType field. Return false if there is no common type found.</p>


<p>Definition at line 4208 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

### InsertPlaceholders() {#a712660a2483aec5a62591f70ae98b7e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{CodeGenPrepare.cpp}::AddressingModeCombiner::InsertPlaceholders (<a href="/web-llvm/docs/api/classes/llvm/densemap">FoldAddrToValueMapping</a> &amp; Map, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; &amp; TraverseOrder, <a href="/web-llvm/docs/api/classes/anonymous-codegenprepare-cpp-/simplificationtracker">SimplificationTracker</a> &amp; ST)</td>
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

<p>Starting from original value recursively iterates over def-use chain up to known ending values represented in a map.</p>


<p>For each traversed phi/select inserts a placeholder Phi or Select. Reports all new created Phi/Select nodes by adding them to set. Also reports and order in what values have been traversed.</p>


<p>Definition at line 4431 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

### MatchPhiNode() {#aac861197af1708f2e86f42c3b993344d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{CodeGenPrepare.cpp}::AddressingModeCombiner::MatchPhiNode (<a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a> * PHI, <a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a> * Candidate, <a href="/web-llvm/docs/api/classes/llvm/smallsetvector">SmallSetVector</a>&lt; PHIPair, 8 &gt; &amp; Matcher, <a href="/web-llvm/docs/api/classes/anonymous-codegenprepare-cpp-/phinodeset">PhiNodeSet</a> &amp; PhiNodesToMatch)</td>
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

<p>Try to match PHI node to Candidate.</p>


<p>Matcher tracks the matched Phi nodes.</p>


<p>Definition at line 4294 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

### MatchPhiSet() {#ae695cf315e4383c36383d0b46650ceac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{CodeGenPrepare.cpp}::AddressingModeCombiner::MatchPhiSet (<a href="/web-llvm/docs/api/classes/anonymous-codegenprepare-cpp-/simplificationtracker">SimplificationTracker</a> &amp; ST, bool AllowNewPhiNodes, unsigned &amp; PhiNotMatchedCount)</td>
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

<p>For the given set of PHI nodes (in the <a href="/web-llvm/docs/api/classes/anonymous-codegenprepare-cpp-/simplificationtracker">SimplificationTracker</a>) try to find their equivalents.</p>


<p>Returns false if this matching fails and creation of new Phi is disabled.</p>


<p>Definition at line 4347 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### AddrModes {#a8303dbf9f0483b7f0a950ff1038cf65e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;ExtAddrMode, 16&gt; anonymous{CodeGenPrepare.cpp}::AddressingModeCombiner::AddrModes</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The addressing modes we've collected.</p>

<p>Definition at line 4078 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

### AllAddrModesTrivial {#a36ce47b3102dc454305f24d6c1dd3746}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{CodeGenPrepare.cpp}::AddressingModeCombiner::AllAddrModesTrivial = <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Are the AddrModes that we have all just equal to their original values?</p>

<p>Definition at line 4084 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

### CommonType {#ae4f34793b9517138b8da263f8a8919dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type* anonymous{CodeGenPrepare.cpp}::AddressingModeCombiner::CommonType = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Common <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> for all different fields in addressing modes.</p>

<p>Definition at line 4087 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

### CommonValue {#affc9fddac9f3760872a8a2a6d566912e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value* anonymous{CodeGenPrepare.cpp}::AddressingModeCombiner::CommonValue = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Common value among addresses.</p>

<p>Definition at line 4096 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

### DifferentField {#a54fa444e173b68e7ab0d38366b6c1935}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ExtAddrMode::FieldName anonymous{CodeGenPrepare.cpp}::AddressingModeCombiner::DifferentField = <a href="/web-llvm/docs/api/structs/anonymous-codegenprepare-cpp-/extaddrmode/#a10aef7c4018bbcd7beefca2dcf4e3c3bade3fdafc2a520488937de65060546976">ExtAddrMode::NoField</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The field in which the AddrModes differ, when we have more than one.</p>

<p>Definition at line 4081 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

### Original {#a93d365101ee4c4352162cb59af079a56}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value* anonymous{CodeGenPrepare.cpp}::AddressingModeCombiner::Original</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Original Address.</p>

<p>Definition at line 4093 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

### SQ {#a1c5f80fa986b1a15fabbfb4653847af0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SimplifyQuery&amp; anonymous{CodeGenPrepare.cpp}::AddressingModeCombiner::SQ</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/structs/llvm/simplifyquery">SimplifyQuery</a> for simplifyInstruction utility.</p>

<p>Definition at line 4090 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>

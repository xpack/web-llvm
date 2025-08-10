---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-systemzisellowering-cpp-/generalshuffle
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `GeneralShuffle` Struct



## Declaration

<div class="doxyDeclaration">
struct anonymous{SystemZISelLowering.cpp}::GeneralShuffle { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abac6ffecac4e31a369b6b949a0b2bba2">GeneralShuffle</a> (EVT vt)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b2aceb5c8270f33ce6746bfed19b9a9">addUndef</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aae881b014fee000d713159f7464f860e">add</a> (SDValue, unsigned)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab94f3858d30f3e1f5259e94182ed196d">getNode</a> (SelectionDAG &amp;, const SDLoc &amp;)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a00bde9b9e580aea387c2e0456964dbbf">tryPrepareForUnpack</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4fbe1a7e131dc072fc01ed74bce6f538">unpackWasPrepared</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e4169d05285368e8908c5f7bc86c87b">insertUnpackIfPrepared</a> (SelectionDAG &amp;DAG, const SDLoc &amp;DL, SDValue Op)</td>
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

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a>, SystemZ::VectorBytes &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a02befed8e456f8073a3ff2f16eb4b9c3">Ops</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; int, SystemZ::VectorBytes &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ada1294e9843211cff1005266e2db694b">Bytes</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa72950c9546a522bbd86e1b1f178e563">VT</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a23ce7beecea468b1ae5384cbeac8fbab">UnpackFromEltSize</a></td>
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


<p>Definition at line 5658 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp">SystemZISelLowering.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### GeneralShuffle() {#abac6ffecac4e31a369b6b949a0b2bba2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{SystemZISelLowering.cpp}::GeneralShuffle::GeneralShuffle (<a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> vt)</td>
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



<p>Definition at line 5659 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp">SystemZISelLowering.cpp</a>.</p>


<p>References <a href="#a23ce7beecea468b1ae5384cbeac8fbab">UnpackFromEltSize</a> and <a href="#aa72950c9546a522bbd86e1b1f178e563">VT</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### add() {#aae881b014fee000d713159f7464f860e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool GeneralShuffle::add (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, unsigned Elem)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 5661 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp">SystemZISelLowering.cpp</a>.</p>


<p>References <a href="#a9b2aceb5c8270f33ce6746bfed19b9a9">addUndef</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a702f69807459cc25db5754a5f179d3fcaf6fbeb8fa9f451468611536b00878d41">llvm::sampleprof::Base</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a412ddf522b53f07690a86bffba1278e7">llvm::ISD::BITCAST</a>, <a href="#ada1294e9843211cff1005266e2db694b">Bytes</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#afbd7d98aac4140ad6a3343443bed5d9b">getShuffleInput</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a1572b31fadbd0d758314b8d35a050410">llvm::EVT::getStoreSize</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#abc4c6365ade17ad4443ad0e381e7479d">llvm::EVT::getVectorElementType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#a6dfe0c9c0080f43b8e889d93c3248b3b">getVPermMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a02befed8e456f8073a3ff2f16eb4b9c3">Ops</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a8d8773b28111d8898663d4a0f6223d68">llvm::ISD::VECTOR_SHUFFLE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/systemz/#a8100b30b39f455a1b99d9d421a5b8f3b">llvm::SystemZ::VectorBytes</a> and <a href="#aa72950c9546a522bbd86e1b1f178e563">VT</a>.</p>

</div>
</div>

### addUndef() {#a9b2aceb5c8270f33ce6746bfed19b9a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void GeneralShuffle::addUndef ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 5660 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp">SystemZISelLowering.cpp</a>.</p>


<p>References <a href="#ada1294e9843211cff1005266e2db694b">Bytes</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="#aa72950c9546a522bbd86e1b1f178e563">VT</a>.</p>


<p>Referenced by <a href="#aae881b014fee000d713159f7464f860e">add</a>.</p>

</div>
</div>

### getNode() {#ab94f3858d30f3e1f5259e94182ed196d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue GeneralShuffle::getNode (<a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp; DL)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 5662 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp">SystemZISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a412ddf522b53f07690a86bffba1278e7">llvm::ISD::BITCAST</a>, <a href="#ada1294e9843211cff1005266e2db694b">Bytes</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#a3f608529746b57d9dfbb1a3f5fa3dd6c">getGeneralPermuteNode</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#abad5b17501ce8972fb04a149611e7177">llvm::SelectionDAG::getNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#a2f58e015c7d03ed60ac5170bcf8aced9">getPermuteNode</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a5b0e59823444a55c295af279611a9d24">llvm::SelectionDAG::getUNDEF</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a7e4169d05285368e8908c5f7bc86c87b">insertUnpackIfPrepared</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinessacontext-cpp/#a31d3975d3ebe3475aef26122625d5b59">isUndef</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#ad7c9b7d5d48d1e1960fd813e6820ab9c">matchDoublePermute</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#a57d318b65d3aefdda0babe2508402d55">matchPermute</a>, <a href="#a02befed8e456f8073a3ff2f16eb4b9c3">Ops</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>, <a href="#a00bde9b9e580aea387c2e0456964dbbf">tryPrepareForUnpack</a>, <a href="#a4fbe1a7e131dc072fc01ed74bce6f538">unpackWasPrepared</a>, <a href="/web-llvm/docs/api/namespaces/llvm/systemz/#a8100b30b39f455a1b99d9d421a5b8f3b">llvm::SystemZ::VectorBytes</a> and <a href="#aa72950c9546a522bbd86e1b1f178e563">VT</a>.</p>

</div>
</div>

### insertUnpackIfPrepared() {#a7e4169d05285368e8908c5f7bc86c87b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue GeneralShuffle::insertUnpackIfPrepared (<a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp; DL, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 5665 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp">SystemZISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a412ddf522b53f07690a86bffba1278e7">llvm::ISD::BITCAST</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#aded931e298cfa08b5038ca2b63c06bb8">llvm::MVT::getIntegerVT</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#abad5b17501ce8972fb04a149611e7177">llvm::SelectionDAG::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#abf8d0055af4879a302268d3f834b2be5">llvm::MVT::getVectorVT</a>, <a href="#a23ce7beecea468b1ae5384cbeac8fbab">UnpackFromEltSize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/systemzisd/#a24fe7decb4ebdd8b4c7a774d65fcaa7ea74190ce96d6b42555298672988c10aec">llvm::SystemZISD::UNPACKL_HIGH</a>, <a href="#a4fbe1a7e131dc072fc01ed74bce6f538">unpackWasPrepared</a> and <a href="/web-llvm/docs/api/namespaces/llvm/systemz/#a5e2f6288a79b32c4bc9f22fe3f3222b2">llvm::SystemZ::VectorBits</a>.</p>


<p>Referenced by <a href="#ab94f3858d30f3e1f5259e94182ed196d">getNode</a>.</p>

</div>
</div>

### tryPrepareForUnpack() {#a00bde9b9e580aea387c2e0456964dbbf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void GeneralShuffle::tryPrepareForUnpack ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 5663 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp">SystemZISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="#ada1294e9843211cff1005266e2db694b">Bytes</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4070eb5356f2cb072322e3d62059e316">llvm::dumpBytes</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#a27514aac009b4036eaa63c9b4a63e25b">findZeroVectorIdx</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a058782b98991f0719657d9008d3df41b">llvm::Log2_32_Ceil</a>, <a href="#a02befed8e456f8073a3ff2f16eb4b9c3">Ops</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="#a23ce7beecea468b1ae5384cbeac8fbab">UnpackFromEltSize</a> and <a href="/web-llvm/docs/api/namespaces/llvm/systemz/#a8100b30b39f455a1b99d9d421a5b8f3b">llvm::SystemZ::VectorBytes</a>.</p>


<p>Referenced by <a href="#ab94f3858d30f3e1f5259e94182ed196d">getNode</a>.</p>

</div>
</div>

### unpackWasPrepared() {#a4fbe1a7e131dc072fc01ed74bce6f538}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{SystemZISelLowering.cpp}::GeneralShuffle::unpackWasPrepared ()</td>
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



<p>Definition at line 5664 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp">SystemZISelLowering.cpp</a>.</p>


<p>Reference <a href="#a23ce7beecea468b1ae5384cbeac8fbab">UnpackFromEltSize</a>.</p>


<p>Referenced by <a href="#ab94f3858d30f3e1f5259e94182ed196d">getNode</a> and <a href="#a7e4169d05285368e8908c5f7bc86c87b">insertUnpackIfPrepared</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Bytes {#ada1294e9843211cff1005266e2db694b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;int, SystemZ::VectorBytes&gt; anonymous{SystemZISelLowering.cpp}::GeneralShuffle::Bytes</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 5673 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp">SystemZISelLowering.cpp</a>.</p>


<p>Referenced by <a href="#aae881b014fee000d713159f7464f860e">add</a>, <a href="#a9b2aceb5c8270f33ce6746bfed19b9a9">addUndef</a>, <a href="#ab94f3858d30f3e1f5259e94182ed196d">getNode</a> and <a href="#a00bde9b9e580aea387c2e0456964dbbf">tryPrepareForUnpack</a>.</p>

</div>
</div>

### Ops {#a02befed8e456f8073a3ff2f16eb4b9c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;SDValue, SystemZ::VectorBytes&gt; anonymous{SystemZISelLowering.cpp}::GeneralShuffle::Ops</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 5668 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp">SystemZISelLowering.cpp</a>.</p>


<p>Referenced by <a href="#aae881b014fee000d713159f7464f860e">add</a>, <a href="#ab94f3858d30f3e1f5259e94182ed196d">getNode</a> and <a href="#a00bde9b9e580aea387c2e0456964dbbf">tryPrepareForUnpack</a>.</p>

</div>
</div>

### UnpackFromEltSize {#a23ce7beecea468b1ae5384cbeac8fbab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{SystemZISelLowering.cpp}::GeneralShuffle::UnpackFromEltSize</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 5679 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp">SystemZISelLowering.cpp</a>.</p>


<p>Referenced by <a href="#abac6ffecac4e31a369b6b949a0b2bba2">GeneralShuffle</a>, <a href="#a7e4169d05285368e8908c5f7bc86c87b">insertUnpackIfPrepared</a>, <a href="#a00bde9b9e580aea387c2e0456964dbbf">tryPrepareForUnpack</a> and <a href="#a4fbe1a7e131dc072fc01ed74bce6f538">unpackWasPrepared</a>.</p>

</div>
</div>

### VT {#aa72950c9546a522bbd86e1b1f178e563}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">EVT anonymous{SystemZISelLowering.cpp}::GeneralShuffle::VT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 5676 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp">SystemZISelLowering.cpp</a>.</p>


<p>Referenced by <a href="#aae881b014fee000d713159f7464f860e">add</a>, <a href="#a9b2aceb5c8270f33ce6746bfed19b9a9">addUndef</a>, <a href="#abac6ffecac4e31a369b6b949a0b2bba2">GeneralShuffle</a> and <a href="#ab94f3858d30f3e1f5259e94182ed196d">getNode</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp">SystemZISelLowering.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>

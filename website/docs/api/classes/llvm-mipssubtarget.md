---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/mipssubtarget
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `MipsSubtarget` Class



## Declaration

<div class="doxyDeclaration">
class llvm::MipsSubtarget { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-h">Target/Mips/MipsSubtarget.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/mipsgensubtargetinfo">MipsGenSubtargetInfo</a></td>
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

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">MipsArchEnum { <a href="#ad6d9532afb3ec2f97c2b3400f38b23e3">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">enum class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">CPU { <a href="#a5d1b936aa13ed144b43eb19ddfcba79e">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">anonymous enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"> { <a href="#a5de8b98039557743ffd22367bdaad811">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae7b263db1194beb382f8ebc755238b77">MipsSubtarget</a> (const Triple &amp;TT, StringRef CPU, StringRef FS, bool little, const MipsTargetMachine &amp;TM, MaybeAlign StackAlignOverride)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This constructor initializes the data members to match that of the specified triple. <a href="#ae7b263db1194beb382f8ebc755238b77">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6bbd8a3146ec60677dbf6086412f9acb">~MipsSubtarget</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a98180cb9502db31783e9610b9afdf6a4">isPositionIndependent</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0ce4eccace977487a102fde5bd673fe7">enablePostRAScheduler</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This overrides the PostRAScheduler bit in the SchedModel for each CPU. <a href="#a0ce4eccace977487a102fde5bd673fe7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acf29f2a58775e014e7e798ef8d4078aa">getCriticalPathRCs</a> (RegClassVector &amp;CriticalPathRCs) const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a8ec1bf8d7b792ca9fac56f8514db18d2">CodeGenOptLevel</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af891a417063d13008027aa7c9f202484">getOptLevelToEnablePostRAScheduler</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4fea8a54127e89dd0e6aec5afba826a1">isABI_N64</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac02bea8ca73149f8cc190e33553a8dec">isABI_N32</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab590cd4af22d8898397715814cf3bdd7">isABI_O32</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mipsabiinfo">MipsABIInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af93bc0064abe6e9327c9843946c9c658">getABI</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c3259b8d9942f4dcd6a171b435246ee">isABI_FPXX</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8cb93358a2bc808bd636f5e2cc906e4e">ParseSubtargetFeatures</a> (StringRef CPU, StringRef TuneCPU, StringRef FS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ParseSubtargetFeatures - Parses features string setting specified subtarget options. <a href="#a8cb93358a2bc808bd636f5e2cc906e4e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aef5913f57718e2e4ca6d61e0f0575fdd">hasMips1</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af31d52be15975435bae4811fa082519d">hasMips2</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aed99be60ebbcaae183cc25df79d1cf5c">hasMips3</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a064c2575d49c4902674326719c0de738">hasMips4</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6709172c1e9c3deca20041dad9b39dbf">hasMips5</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2c2a87b68328139d9d5539168b83f9ce">hasMips4_32</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa8ebe3f0af9bf547ff6a401eaf50c8bd">hasMips4_32r2</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c595885100ac9cf852be70151cc51d6">hasMips32</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa225d65026d63bc4a90f91a57ac705df">hasMips32r2</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3cf5610ecf4df7bfcae79dc4b3ac270e">hasMips32r3</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a108b5c98377ac15eb6b1b2d423e1808f">hasMips32r5</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a00fc7567082e1f37e03204a7c619d87e">hasMips32r6</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a685938c15d608493edc6a06191042ea3">hasMips64</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0923b731e7f389c4f1b9d0428bf129aa">hasMips64r2</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af3ad0e2ad34109a5c9d424802e36dde8">hasMips64r3</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adb50ef5630bc839a820317169e002016">hasMips64r5</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a53196bab025b7327f8469ae9e3aa412f">hasMips64r6</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a90bb46b34212accb22cfa850b50cabae">hasCnMips</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac77ee7c75cdd8b178fd08d7cbf742295">hasCnMipsP</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f2915eb956ce94ea0fd4a194dac24e1">isLittle</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a86a38d27500447408085bf13ef73cea7">isABICalls</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af12582b8591c7665d801330f3ba614c3">isFPXX</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0abbd953996acada93c1609744afaa88">isFP64bit</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5494959f8945d509cb143ebabcc9f3c8">useOddSPReg</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a83080e9a860cb80126ed1d142476b763">noOddSPReg</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a545182303fb7b5b50d3ff65006ed9263">isNaN2008</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a814d09d0448d8ebe3d64744bb221cec1">inAbs2008Mode</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b50ba1092e9b3e6d57c4170d739133e">isGP64bit</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2fa92ba21c318dedacf2b3497ce40641">isGP32bit</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac052de3ee550e1dca1c71e6021d32e9b">getGPRSizeInBytes</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af2685456833bb936c5a7ce7f85d1a405">isPTR64bit</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a733bd521aa3c58f4c7aae3a009db5c44">isPTR32bit</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a767bbaf46ecf142dc608b77a69ffca2d">hasSym32</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab433146b1864babd91f6017fae56dd50">isSingleFloat</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa586b2c43b384525cc14462210688af4">isTargetCOFF</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b1a490ffae2b318cd63983aac82a5ac">isTargetELF</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a637dbc87a9670a4b2de30ceca1427a88">hasVFPU</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a665e2ef3a476d2de4052b40756af0976">inMips16Mode</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab791e3581e4e931933745076de5b41cd">inMips16ModeDefault</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac77c16f733d57892503f227844026d5e">inMips16HardFloat</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a102ee3949228f2c8c1902c3ab7b70efc">inMicroMipsMode</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa1f7337fee0dd9434aead825eab6ba58">inMicroMips32r6Mode</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa75fb36988c3ab7c97a9651471fbd487">hasDSP</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3ef0cdcde470eb39afa0f15315695096">hasDSPR2</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af7c85df3a19d66aebdc909c673af215d">hasDSPR3</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#accf7fc173d14a6eb7934ed17c2e7d90e">has3D</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab042d4cff6de998047eddaba9ed25a06">hasMSA</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8d13a42777145389deaa5badaff05f38">disableMadd4</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9125c1252d0cec74de93a4c78803dc56">hasEVA</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2c934c225110ef46d10dcb64fc8d49a8">hasMT</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac077da9277c34e260fdda34ed54f4270">hasCRC</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a39ed159bebcfc2232175baeca130bbe5">hasVirt</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab60eee269b7f8562d25e8b41e3bc5dd9">hasGINV</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a524791d1032e1a9e65b0c43ee4b2859c">useIndirectJumpsHazard</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac39000d549551360d4a1f23659162878">useSmallSection</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd8a67f4bcda85d4e861fc11cf0c49d6">hasStandardEncoding</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3ec2bbbdcfbc738f451f0b7aaa85584d">useSoftFloat</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aba475652437691d8a20fccc8df6839bb">useLongCalls</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a808b6c33b6dfbaee71a7ac5d86108f02">useXGOT</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9ba9fcfab91c1e464efa881fcf47e607">enableLongBranchPass</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b8326862ae7ce49518000abc157d094">hasExtractInsert</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Features related to the presence of specific instructions. <a href="#a9b8326862ae7ce49518000abc157d094">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acad59be25c017c562ef9bfcd94800e74">hasMTHC1</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a62f3e08f89b830c7ba194a8aad8794f1">allowMixed16_32</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a876e8fceab3b87595bb00188950665a7">os16</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade22344fec068aba4bd0d1109d98140d">isTargetNaCl</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac397824ac11b8375f102c428bb54ee7">isTargetWindows</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0291cacff322d690e5c89ba3a7c29394">isXRaySupported</a> () const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/align">Align</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaa355ba7d64c2138f8fb62668852e8e0">getStackAlignment</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/reloc/#af59f6dc86e80aaf56f1afd155eebf568">Reloc::Model</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aef6810c5b5a969e7e9f06ccecbb8a683">getRelocationModel</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mipssubtarget">MipsSubtarget</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b37851d4a9eb9835f16b127b83ccf9e">initializeSubtargetDependencies</a> (StringRef CPU, StringRef FS, const TargetMachine &amp;TM)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9787dc07213aa611bd508f5333b609f7">systemSupportsUnalignedAccess</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Does the system support unaligned memory access. <a href="#a9787dc07213aa611bd508f5333b609f7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a81fcf9b949e1a296eee42e0e0f182cd8">setHelperClassesMips16</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9bf60a9627bfee7d88f9f59dfad23681">setHelperClassesMipsSE</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/selectiondagtargetinfo">SelectionDAGTargetInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaecc74da149c830dbbc41201b1c09d27">getSelectionDAGInfo</a> () const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mipsinstrinfo">MipsInstrInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4870c381b12fc206ac1aee9b705325b7">getInstrInfo</a> () const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetframelowering">TargetFrameLowering</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb4ba42b3c347f99f8a3916470f67acd">getFrameLowering</a> () const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mipsregisterinfo">MipsRegisterInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a856ec36e844545656044c24f78dbcbbd">getRegisterInfo</a> () const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mipstargetlowering">MipsTargetLowering</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac53adcbc0eef07e24dda7a5bbdc54238">getTargetLowering</a> () const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instritinerarydata">InstrItineraryData</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac4b2b35c0a9c9b0f505069f89e9d8e9">getInstrItineraryData</a> () const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/calllowering">CallLowering</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b4325d736b4f1e92fb930939abc74e1">getCallLowering</a> () const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/legalizerinfo">LegalizerInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a04e22d0a7e2ff0b3b26a5940f90f1c5a">getLegalizerInfo</a> () const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo">RegisterBankInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8d2cdab8e2580db4f5df4e77c814c781">getRegBankInfo</a> () const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instructionselector">InstructionSelector</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac661a4addb01d46a2850ba9269a0a29">getInstructionSelector</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9812b285685d106fa1a8a5c26b27b460">anchor</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/calllowering">CallLowering</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a81dc3806052d69678e8fbfea8d9476ff">CallLoweringInfo</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/legalizerinfo">LegalizerInfo</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab58aa66844773792a635ff42ba45c0ff">Legalizer</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo">RegisterBankInfo</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5eab98d9ea4f0371975931c7b7a64ee8">RegBankInfo</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/instructionselector">InstructionSelector</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a357413e9cd61b004b4cc87dc35c9154c">InstSelector</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">MipsArchEnum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab1e7f8ec863b1240c370f7393e5a4a06">MipsArchVersion</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">CPU</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b6da9063a58f578a86dc06c087c7e66">ProcImpl</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2d1d2774a2e91a1e2adf593ef457e3af">IsLittle</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad2dde4a558ba4e8b98c8d4597d2d1e42">IsSoftFloat</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aefad903f44a0eb8b1df7e8046ff70503">IsSingleFloat</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9df2942829be387a4e22b89787e2e09b">IsFPXX</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0db6c4a2f269f21136062d4eeb8be58f">NoABICalls</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe7e7bf69bbc668c44d16f628c4271ce">Abs2008</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9124a458304b75bf91c3117725e3efc5">IsFP64bit</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f8eab64d891970dc1845e626125f81d">UseOddSPReg</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Are odd single-precision registers permitted? <a href="#a0f8eab64d891970dc1845e626125f81d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad8952ddce1bfa21ea965e78a0d6e50e9">IsNaN2008bit</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e0aa6a67426a08c884ad2bc8d49efb7">IsGP64bit</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a42949c3dafe4cfd10c416b9764e72a">IsPTR64bit</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a50db89d241a9a9c9b5fc20ce74735fc5">HasVFPU</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae6bbe8e77e07ebfd73deab49999b31a8">HasCnMips</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a68ed3d73baaccab32b8d7314abc693c6">HasCnMipsP</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a425ea9d861bc45b218cec6772ad24f71">IsLinux</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a293ad777017ebe443c94cc53d306b372">UseSmallSection</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa2b591ce422e3b82b8704c7e1c179437">HasMips3_32</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Features related to the presence of specific instructions. <a href="#aa2b591ce422e3b82b8704c7e1c179437">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5fe8b5f1ca47e282e136afea3458bc14">HasMips3_32r2</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6fcbabfc37937fd745759d68a0a550cc">HasMips4_32</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8014457bb4d58a2113e1df94ae3fe8e0">HasMips4_32r2</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7709ee417f8b3b09c1ed46c17af80eac">HasMips5_32r2</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab3afe59e2d82ba4845a2249c6c68322e">InMips16Mode</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6245e1446b13a3f8e220de3fd52ed567">InMips16HardFloat</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8c73f35ae5210d0e705de77a01f08f72">InMicroMipsMode</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af953493a4f0c96be9943cab2fefd9c80">HasDSP</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2156927151241af76a3357f1c6d5717e">HasDSPR2</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2fee268082bab583fbd277335165eec8">HasDSPR3</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b6e42c8019f001f77ba9795864ab317">Has3D</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aff1ad8e1fdad53b3464c0a07b25961b6">AllowMixed16_32</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae1fce71e61e5f71a3504c96f619eec41">Os16</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a90e478432db3bab986e0f65b19923bb4">HasMSA</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1f1992a5da4e0c642ccf0d950c1f6d95">UseTCCInDIV</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0bd1db58d1d845f771786e7e8fe0462d">HasSym32</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6158547e1fdb920d3946eb5200cc0204">HasEVA</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af507db1e10f04a5fc6521b789dadf653">DisableMadd4</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ace1fa367e9b3f8772de3e8219a5c6e58">HasMT</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adc3c123c97fa1d4878a4dd1053456e5a">HasCRC</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ea9dd61f2202ab28555af25e43e3b66">HasVirt</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4b040d4a13d766e2870b4f0bfaafd41e">HasGINV</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab7fa6d31b3035d0197cfce877f86ab11">UseIndirectJumpsHazard</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a61943dde4d23d152bb989a1d2cd79fb6">UseLongCalls</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5306bd7d2395907f7312345fcfaa3e48">UseXGOT</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6aaaf1f48b12912212111c1abe0b65e5">StrictAlign</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/align">Align</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac78027b75f10fd1dc8e47a4047d942e">stackAlignment</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The minimum alignment known to hold of the stack frame on entry to the function and which must be maintained by every function. <a href="#aac78027b75f10fd1dc8e47a4047d942e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/maybealign">MaybeAlign</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a60592d7ce04b851b2dbe5988280b2937">StackAlignOverride</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The overridden stack alignment. <a href="#a60592d7ce04b851b2dbe5988280b2937">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instritinerarydata">InstrItineraryData</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4b46179ddb974a2ecad00186d3aa3e3c">InstrItins</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">enum <a href="/web-llvm/docs/api/classes/llvm/mipssubtarget">llvm::MipsSubtarget</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a688367debf40c9142b39681bbe9b5893">OverrideMode</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mipstargetmachine">MipsTargetMachine</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acf59a1f4f5528909c818de7522ed9970">TM</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af428e68f6384904fe17cda10a5a77697">TargetTriple</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/selectiondagtargetinfo">SelectionDAGTargetInfo</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af931fbefb9d80305517f218f8166a537">TSInfo</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mipsinstrinfo">MipsInstrInfo</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa19954ee4d61638f238528cf810ea266">InstrInfo</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mipsframelowering">MipsFrameLowering</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a778b77e453bce62d19b9586a98d9c751">FrameLowering</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mipstargetlowering">MipsTargetLowering</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8aee5e7318b26da4ecc136b66119b8da">TLInfo</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a056776ea56d64939bb6cf447b0e24e3c">useConstantIslands</a> ()</td>
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

## Private Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a66ba28c2dad9cc8f28c0704c873a7205">DspWarningPrinted</a> = false</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad85047a29ef43117f4dd4c110f661650">MSAWarningPrinted</a> = false</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a48e631557778f1cbb6e1ffb3e6e55be9">CRCWarningPrinted</a> = false</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ae7d3830ab6dc1b8a6c6d884b0eec9e">GINVWarningPrinted</a> = false</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a88c101964bfb123391b8fddcfb9a9241">MIPS1WarningPrinted</a> = false</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#accba0065d7d6938038dcbd3e81882da3">VirtWarningPrinted</a> = false</td>
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


<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-h">MipsSubtarget.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### anonymous enum  {#a5de8b98039557743ffd22367bdaad811}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous enum </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NoOverride<a id="a5de8b98039557743ffd22367bdaad811a56b8d3fae0ec95b0c2cb60b5e56160b0"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Mips16Override<a id="a5de8b98039557743ffd22367bdaad811a54a6a0b648f20397c860e6a6d4a34792"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NoMips16Override<a id="a5de8b98039557743ffd22367bdaad811afce0471899531bedea5bd5056b7d5361"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 216 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-h">MipsSubtarget.h</a>.</p>

</div>
</div>

### CPU {#a5d1b936aa13ed144b43eb19ddfcba79e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum class llvm::MipsSubtarget::CPU </td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel strong">strong</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">P5600<a id="a5d1b936aa13ed144b43eb19ddfcba79eae511b89b9c879d15d3e88a92d0f1d2d6"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-h">MipsSubtarget.h</a>.</p>

</div>
</div>

### MipsArchEnum {#ad6d9532afb3ec2f97c2b3400f38b23e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::MipsSubtarget::MipsArchEnum </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MipsDefault<a id="ad6d9532afb3ec2f97c2b3400f38b23e3ac2cea1b88e55ed3d23db9ed72ba8fc02"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Mips1<a id="ad6d9532afb3ec2f97c2b3400f38b23e3a03f960715cac159ffa6981085a8f6af1"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Mips2<a id="ad6d9532afb3ec2f97c2b3400f38b23e3abf115ad1663b77557a4f517a0cb8b3e8"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Mips32<a id="ad6d9532afb3ec2f97c2b3400f38b23e3aebcae4368d24e74bda2134db44e938f8"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Mips32r2<a id="ad6d9532afb3ec2f97c2b3400f38b23e3a87aed1f8aeef1c46f15aff12824d917c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Mips32r3<a id="ad6d9532afb3ec2f97c2b3400f38b23e3a6bb97a830db2904f38f20170cd45815f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Mips32r5<a id="ad6d9532afb3ec2f97c2b3400f38b23e3a479424a431c921ec9fa5febc96576e7a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Mips32r6<a id="ad6d9532afb3ec2f97c2b3400f38b23e3a0294528dbd20a657fdaca726f21f2602"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Mips32Max<a id="ad6d9532afb3ec2f97c2b3400f38b23e3aebd3d350a653b3a72044ff9ee259f14a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Mips3<a id="ad6d9532afb3ec2f97c2b3400f38b23e3a6fcc1676d6e4b6327de819978c88d1e2"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Mips4<a id="ad6d9532afb3ec2f97c2b3400f38b23e3a2c1dfe58e6a7413d90d06f73ab6017b7"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Mips5<a id="ad6d9532afb3ec2f97c2b3400f38b23e3a990d58dabd8310893f6f5046ac0744c5"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Mips64<a id="ad6d9532afb3ec2f97c2b3400f38b23e3ad52a2e7581cc5d30406036c07647d86c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Mips64r2<a id="ad6d9532afb3ec2f97c2b3400f38b23e3aa562fb7eaf3a25b79191c0d646f7ca0c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Mips64r3<a id="ad6d9532afb3ec2f97c2b3400f38b23e3a417862054185527805255d0866e67781"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Mips64r5<a id="ad6d9532afb3ec2f97c2b3400f38b23e3aa0f0718ac5adf6611db021dffdb0db56"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Mips64r6<a id="ad6d9532afb3ec2f97c2b3400f38b23e3ae73a9af556a3fa7e9e91c9d71050d9c1"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 40 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-h">MipsSubtarget.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### MipsSubtarget() {#ae7b263db1194beb382f8ebc755238b77}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MipsSubtarget::MipsSubtarget (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> &amp; TT, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> CPU, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> FS, bool little, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mipstargetmachine">MipsTargetMachine</a> &amp; TM, <a href="/web-llvm/docs/api/structs/llvm/maybealign">MaybeAlign</a> StackAlignOverride)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This constructor initializes the data members to match that of the specified triple.</p>

<p>Declaration at line 242 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-h">MipsSubtarget.h</a>, definition at line 71 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-cpp">MipsSubtarget.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a81dc3806052d69678e8fbfea8d9476ff">CallLoweringInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5cb3975dacdbd6c7a27ac5b544ca067e">llvm::createMipsInstructionSelector</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9a7b5c68c90f85baaedaa854cc5002cc">llvm::errs</a>, <a href="#a856ec36e844545656044c24f78dbcbbd">getRegisterInfo</a>, <a href="#ac53adcbc0eef07e24dda7a5bbdc54238">getTargetLowering</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-cpp/#ae5366d0f6591d0b7b823f11953338e6c">GPOpt</a>, <a href="#ac077da9277c34e260fdda34ed54f4270">hasCRC</a>, <a href="#aa75fb36988c3ab7c97a9651471fbd487">hasDSP</a>, <a href="#a3ef0cdcde470eb39afa0f15315695096">hasDSPR2</a>, <a href="#ab60eee269b7f8562d25e8b41e3bc5dd9">hasGINV</a>, <a href="#a6c595885100ac9cf852be70151cc51d6">hasMips32</a>, <a href="#aa225d65026d63bc4a90f91a57ac705df">hasMips32r2</a>, <a href="#a108b5c98377ac15eb6b1b2d423e1808f">hasMips32r5</a>, <a href="#a00fc7567082e1f37e03204a7c619d87e">hasMips32r6</a>, <a href="#a685938c15d608493edc6a06191042ea3">hasMips64</a>, <a href="#a0923b731e7f389c4f1b9d0428bf129aa">hasMips64r2</a>, <a href="#a53196bab025b7327f8469ae9e3aa412f">hasMips64r6</a>, <a href="#ab042d4cff6de998047eddaba9ed25a06">hasMSA</a>, <a href="#a767bbaf46ecf142dc608b77a69ffca2d">hasSym32</a>, <a href="#a39ed159bebcfc2232175baeca130bbe5">hasVirt</a>, <a href="#a814d09d0448d8ebe3d64744bb221cec1">inAbs2008Mode</a>, <a href="#a5b37851d4a9eb9835f16b127b83ccf9e">initializeSubtargetDependencies</a>, <a href="#a357413e9cd61b004b4cc87dc35c9154c">InstSelector</a>, <a href="#ac02bea8ca73149f8cc190e33553a8dec">isABI_N32</a>, <a href="#a4fea8a54127e89dd0e6aec5afba826a1">isABI_N64</a>, <a href="#ab590cd4af22d8898397715814cf3bdd7">isABI_O32</a>, <a href="#a0abbd953996acada93c1609744afaa88">isFP64bit</a>, <a href="#a9b50ba1092e9b3e6d57c4170d739133e">isGP64bit</a>, <a href="#a545182303fb7b5b50d3ff65006ed9263">isNaN2008</a>, <a href="#ab58aa66844773792a635ff42ba45c0ff">Legalizer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae1e26e57357947b25e392fd18ab000dbaaae6635e044ac56046b2893a529b5114">llvm::little</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-cpp/#a5da40348b3cca308c846d9f9c0132c5a">Mips16HardFloat</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-cpp/#a75b6b4ed787bd639f0f74d61916e7289">Mips_Os16</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-cpp/#a3057403bee6ceb966f4b0e9be0616a1e">Mixed16_32</a>, <a href="#a5eab98d9ea4f0371975931c7b7a64ee8">RegBankInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a> and <a href="#a5494959f8945d509cb143ebabcc9f3c8">useOddSPReg</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~MipsSubtarget() {#a6bbd8a3146ec60677dbf6086412f9acb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MipsSubtarget::~MipsSubtarget ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 245 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-h">MipsSubtarget.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### allowMixed16\_32() {#a62f3e08f89b830c7ba194a8aad8794f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MipsSubtarget::allowMixed16_32 ()</td>
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



<p>Definition at line 354 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-h">MipsSubtarget.h</a>.</p>


<p>Reference <a href="#ab791e3581e4e931933745076de5b41cd">inMips16ModeDefault</a>.</p>


<p>Referenced by <a href="#a9ba9fcfab91c1e464efa881fcf47e607">enableLongBranchPass</a>.</p>

</div>
</div>

### disableMadd4() {#a8d13a42777145389deaa5badaff05f38}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MipsSubtarget::disableMadd4 ()</td>
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



<p>Definition at line 327 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-h">MipsSubtarget.h</a>.</p>

</div>
</div>

### enableLongBranchPass() {#a9ba9fcfab91c1e464efa881fcf47e607}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MipsSubtarget::enableLongBranchPass ()</td>
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



<p>Definition at line 346 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-h">MipsSubtarget.h</a>.</p>


<p>References <a href="#a62f3e08f89b830c7ba194a8aad8794f1">allowMixed16_32</a>, <a href="#acd8a67f4bcda85d4e861fc11cf0c49d6">hasStandardEncoding</a> and <a href="#a102ee3949228f2c8c1902c3ab7b70efc">inMicroMipsMode</a>.</p>

</div>
</div>

### enablePostRAScheduler() {#a0ce4eccace977487a102fde5bd673fe7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsSubtarget::enablePostRAScheduler ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This overrides the PostRAScheduler bit in the SchedModel for each CPU.</p>


<p>This overrides the PostRAScheduler bit in the SchedModel for any CPU.</p>


<p>Declaration at line 230 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-h">MipsSubtarget.h</a>, definition at line 233 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-cpp">MipsSubtarget.cpp</a>.</p>

</div>
</div>

### getABI() {#af93bc0064abe6e9327c9843946c9c658}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MipsABIInfo &amp; MipsSubtarget::getABI ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 237 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-h">MipsSubtarget.h</a>, definition at line 287 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-cpp">MipsSubtarget.cpp</a>.</p>


<p>Referenced by <a href="#ac02bea8ca73149f8cc190e33553a8dec">isABI_N32</a>, <a href="#a4fea8a54127e89dd0e6aec5afba826a1">isABI_N64</a> and <a href="#ab590cd4af22d8898397715814cf3bdd7">isABI_O32</a>.</p>

</div>
</div>

### getCallLowering() {#a5b4325d736b4f1e92fb930939abc74e1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const CallLowering * MipsSubtarget::getCallLowering ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 413 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-h">MipsSubtarget.h</a>, definition at line 293 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-cpp">MipsSubtarget.cpp</a>.</p>


<p>Reference <a href="#a81dc3806052d69678e8fbfea8d9476ff">CallLoweringInfo</a>.</p>

</div>
</div>

### getCriticalPathRCs() {#acf29f2a58775e014e7e798ef8d4078aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MipsSubtarget::getCriticalPathRCs (RegClassVector &amp; CriticalPathRCs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 231 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-h">MipsSubtarget.h</a>, definition at line 235 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-cpp">MipsSubtarget.cpp</a>.</p>


<p>Reference <a href="#a9b50ba1092e9b3e6d57c4170d739133e">isGP64bit</a>.</p>

</div>
</div>

### getFrameLowering() {#afb4ba42b3c347f99f8a3916470f67acd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetFrameLowering * llvm::MipsSubtarget::getFrameLowering ()</td>
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



<p>Definition at line 392 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-h">MipsSubtarget.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mipsregisterinfo/#a6e2d4106e3ee3d0463f29dea987d698f">llvm::MipsRegisterInfo::canRealignStack</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsregisterinfo/#a233e4dd01a9c98f407775d1061ec5d97">llvm::MipsRegisterInfo::getFrameRegister</a> and <a href="/web-llvm/docs/api/classes/llvm/mipsregisterinfo/#ab03f0084e766f3636a1eb7832061fd94">llvm::MipsRegisterInfo::getReservedRegs</a>.</p>

</div>
</div>

### getGPRSizeInBytes() {#ac052de3ee550e1dca1c71e6021d32e9b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MipsSubtarget::getGPRSizeInBytes ()</td>
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



<p>Definition at line 297 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-h">MipsSubtarget.h</a>.</p>


<p>Reference <a href="#a9b50ba1092e9b3e6d57c4170d739133e">isGP64bit</a>.</p>

</div>
</div>

### getInstrInfo() {#a4870c381b12fc206ac1aee9b705325b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MipsInstrInfo * llvm::MipsSubtarget::getInstrInfo ()</td>
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



<p>Definition at line 391 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-h">MipsSubtarget.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-mipsdelayslotfiller-cpp-/mipsdelayslotfiller/#a12bbaf2ff79b0813af362fb00de513b2">anonymous{MipsDelaySlotFiller.cpp}::MipsDelaySlotFiller::searchRange</a>.</p>

</div>
</div>

### getInstrItineraryData() {#aac4b2b35c0a9c9b0f505069f89e9d8e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const InstrItineraryData * llvm::MipsSubtarget::getInstrItineraryData ()</td>
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



<p>Definition at line 401 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-h">MipsSubtarget.h</a>.</p>

</div>
</div>

### getInstructionSelector() {#aac661a4addb01d46a2850ba9269a0a29}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstructionSelector * MipsSubtarget::getInstructionSelector ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 416 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-h">MipsSubtarget.h</a>, definition at line 305 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-cpp">MipsSubtarget.cpp</a>.</p>


<p>Reference <a href="#a357413e9cd61b004b4cc87dc35c9154c">InstSelector</a>.</p>

</div>
</div>

### getLegalizerInfo() {#a04e22d0a7e2ff0b3b26a5940f90f1c5a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const LegalizerInfo * MipsSubtarget::getLegalizerInfo ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 414 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-h">MipsSubtarget.h</a>, definition at line 297 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-cpp">MipsSubtarget.cpp</a>.</p>


<p>Reference <a href="#ab58aa66844773792a635ff42ba45c0ff">Legalizer</a>.</p>

</div>
</div>

### getOptLevelToEnablePostRAScheduler() {#af891a417063d13008027aa7c9f202484}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CodeGenOptLevel MipsSubtarget::getOptLevelToEnablePostRAScheduler ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 232 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-h">MipsSubtarget.h</a>, definition at line 241 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-cpp">MipsSubtarget.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a8ec1bf8d7b792ca9fac56f8514db18d2a389a96d0d9b3feb46b8c9d941566a4ae">llvm::Aggressive</a>.</p>

</div>
</div>

### getRegBankInfo() {#a8d2cdab8e2580db4f5df4e77c814c781}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const RegisterBankInfo * MipsSubtarget::getRegBankInfo ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 415 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-h">MipsSubtarget.h</a>, definition at line 301 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-cpp">MipsSubtarget.cpp</a>.</p>


<p>Reference <a href="#a5eab98d9ea4f0371975931c7b7a64ee8">RegBankInfo</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mipscalllowering/#a5344895d462c34e2c90e930471d8e4d9">llvm::MipsCallLowering::lowerCall</a>.</p>

</div>
</div>

### getRegisterInfo() {#a856ec36e844545656044c24f78dbcbbd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MipsRegisterInfo * llvm::MipsSubtarget::getRegisterInfo ()</td>
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



<p>Definition at line 395 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-h">MipsSubtarget.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mipscalllowering/#a5344895d462c34e2c90e930471d8e4d9">llvm::MipsCallLowering::lowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/mips16targetlowering/#a97b896b6b94b563138613746e46e053e">llvm::Mips16TargetLowering::Mips16TargetLowering</a>, <a href="#ae7b263db1194beb382f8ebc755238b77">MipsSubtarget</a> and <a href="/web-llvm/docs/api/classes/anonymous-mipsdelayslotfiller-cpp-/mipsdelayslotfiller/#a12bbaf2ff79b0813af362fb00de513b2">anonymous{MipsDelaySlotFiller.cpp}::MipsDelaySlotFiller::searchRange</a>.</p>

</div>
</div>

### getRelocationModel() {#aef6810c5b5a969e7e9f06ccecbb8a683}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Reloc::Model MipsSubtarget::getRelocationModel ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 371 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-h">MipsSubtarget.h</a>, definition at line 280 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-cpp">MipsSubtarget.cpp</a>.</p>

</div>
</div>

### getSelectionDAGInfo() {#aaecc74da149c830dbbc41201b1c09d27}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SelectionDAGTargetInfo * MipsSubtarget::getSelectionDAGInfo ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 389 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-h">MipsSubtarget.h</a>, definition at line 289 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-cpp">MipsSubtarget.cpp</a>.</p>

</div>
</div>

### getStackAlignment() {#aaa355ba7d64c2138f8fb62668852e8e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Align llvm::MipsSubtarget::getStackAlignment ()</td>
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



<p>Definition at line 368 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-h">MipsSubtarget.h</a>.</p>

</div>
</div>

### getTargetLowering() {#ac53adcbc0eef07e24dda7a5bbdc54238}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MipsTargetLowering * llvm::MipsSubtarget::getTargetLowering ()</td>
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



<p>Definition at line 398 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-h">MipsSubtarget.h</a>.</p>


<p>Referenced by <a href="#ae7b263db1194beb382f8ebc755238b77">MipsSubtarget</a>.</p>

</div>
</div>

### has3D() {#accf7fc173d14a6eb7934ed17c2e7d90e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MipsSubtarget::has3D ()</td>
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



<p>Definition at line 325 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-h">MipsSubtarget.h</a>.</p>

</div>
</div>

### hasCnMips() {#a90bb46b34212accb22cfa850b50cabae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MipsSubtarget::hasCnMips ()</td>
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



<p>Definition at line 284 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-h">MipsSubtarget.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-cpp/#aa20249b0c2be4c3930493f53d8d4a5e5">performANDCombine</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-cpp/#a6d21a959b41eb8c9bf28105d72fdbd43">performSHLCombine</a>.</p>

</div>
</div>

### hasCnMipsP() {#ac77ee7c75cdd8b178fd08d7cbf742295}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MipsSubtarget::hasCnMipsP ()</td>
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



<p>Definition at line 285 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-h">MipsSubtarget.h</a>.</p>

</div>
</div>

### hasCRC() {#ac077da9277c34e260fdda34ed54f4270}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MipsSubtarget::hasCRC ()</td>
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



<p>Definition at line 330 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-h">MipsSubtarget.h</a>.</p>


<p>Referenced by <a href="#ae7b263db1194beb382f8ebc755238b77">MipsSubtarget</a>.</p>

</div>
</div>

### hasDSP() {#aa75fb36988c3ab7c97a9651471fbd487}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MipsSubtarget::hasDSP ()</td>
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



<p>Definition at line 322 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-h">MipsSubtarget.h</a>.</p>


<p>Referenced by <a href="#ae7b263db1194beb382f8ebc755238b77">MipsSubtarget</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsseisellowering-cpp/#a1cb3d0ba0717491c0c28dcc2e4b3d152">performDSPShiftCombine</a>.</p>

</div>
</div>

### hasDSPR2() {#a3ef0cdcde470eb39afa0f15315695096}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MipsSubtarget::hasDSPR2 ()</td>
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



<p>Definition at line 323 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-h">MipsSubtarget.h</a>.</p>


<p>Referenced by <a href="#ae7b263db1194beb382f8ebc755238b77">MipsSubtarget</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsseisellowering-cpp/#a56ba18b7bb062d32ea351c6349a415c6">performSRACombine</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsseisellowering-cpp/#ab2fc845ce9d296eb2a7532f49d236b0c">performSRLCombine</a>.</p>

</div>
</div>

### hasDSPR3() {#af7c85df3a19d66aebdc909c673af215d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MipsSubtarget::hasDSPR3 ()</td>
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



<p>Definition at line 324 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-h">MipsSubtarget.h</a>.</p>

</div>
</div>

### hasEVA() {#a9125c1252d0cec74de93a4c78803dc56}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MipsSubtarget::hasEVA ()</td>
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



<p>Definition at line 328 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-h">MipsSubtarget.h</a>.</p>

</div>
</div>

### hasExtractInsert() {#a9b8326862ae7ce49518000abc157d094}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MipsSubtarget::hasExtractInsert ()</td>
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

<p>Features related to the presence of specific instructions.</p>

<p>Definition at line 351 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-h">MipsSubtarget.h</a>.</p>


<p>References <a href="#aa225d65026d63bc4a90f91a57ac705df">hasMips32r2</a> and <a href="#a665e2ef3a476d2de4052b40756af0976">inMips16Mode</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-cpp/#aa20249b0c2be4c3930493f53d8d4a5e5">performANDCombine</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-cpp/#abcb6ebd6de53d9ed63cd065dd4128261">performORCombine</a>.</p>

</div>
</div>

### hasGINV() {#ab60eee269b7f8562d25e8b41e3bc5dd9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MipsSubtarget::hasGINV ()</td>
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



<p>Definition at line 332 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-h">MipsSubtarget.h</a>.</p>


<p>Referenced by <a href="#ae7b263db1194beb382f8ebc755238b77">MipsSubtarget</a>.</p>

</div>
</div>

### hasMips1() {#aef5913f57718e2e4ca6d61e0f0575fdd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MipsSubtarget::hasMips1 ()</td>
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



<p>Definition at line 251 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-h">MipsSubtarget.h</a>.</p>

</div>
</div>

### hasMips2() {#af31d52be15975435bae4811fa082519d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MipsSubtarget::hasMips2 ()</td>
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



<p>Definition at line 252 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-h">MipsSubtarget.h</a>.</p>

</div>
</div>

### hasMips3() {#aed99be60ebbcaae183cc25df79d1cf5c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MipsSubtarget::hasMips3 ()</td>
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



<p>Definition at line 253 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-h">MipsSubtarget.h</a>.</p>

</div>
</div>

### hasMips32() {#a6c595885100ac9cf852be70151cc51d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MipsSubtarget::hasMips32 ()</td>
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



<p>Definition at line 258 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-h">MipsSubtarget.h</a>.</p>


<p>Reference <a href="#a685938c15d608493edc6a06191042ea3">hasMips64</a>.</p>


<p>Referenced by <a href="#ae7b263db1194beb382f8ebc755238b77">MipsSubtarget</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-cpp/#a830e51b63befaa067f822c088dd8833b">performADDCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-cpp/#a9a5205b95660638f4c7d889f588251e7">performSUBCombine</a> and <a href="/web-llvm/docs/api/classes/anonymous-mipsdelayslotfiller-cpp-/mipsdelayslotfiller/#a12bbaf2ff79b0813af362fb00de513b2">anonymous{MipsDelaySlotFiller.cpp}::MipsDelaySlotFiller::searchRange</a>.</p>

</div>
</div>

### hasMips32r2() {#aa225d65026d63bc4a90f91a57ac705df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MipsSubtarget::hasMips32r2 ()</td>
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



<p>Definition at line 262 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-h">MipsSubtarget.h</a>.</p>


<p>Reference <a href="#a0923b731e7f389c4f1b9d0428bf129aa">hasMips64r2</a>.</p>


<p>Referenced by <a href="#a9b8326862ae7ce49518000abc157d094">hasExtractInsert</a>, <a href="#acad59be25c017c562ef9bfcd94800e74">hasMTHC1</a>, <a href="#ae7b263db1194beb382f8ebc755238b77">MipsSubtarget</a> and <a href="#a524791d1032e1a9e65b0c43ee4b2859c">useIndirectJumpsHazard</a>.</p>

</div>
</div>

### hasMips32r3() {#a3cf5610ecf4df7bfcae79dc4b3ac270e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MipsSubtarget::hasMips32r3 ()</td>
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



<p>Definition at line 266 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-h">MipsSubtarget.h</a>.</p>


<p>Reference <a href="#a0923b731e7f389c4f1b9d0428bf129aa">hasMips64r2</a>.</p>

</div>
</div>

### hasMips32r5() {#a108b5c98377ac15eb6b1b2d423e1808f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MipsSubtarget::hasMips32r5 ()</td>
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



<p>Definition at line 270 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-h">MipsSubtarget.h</a>.</p>


<p>Reference <a href="#adb50ef5630bc839a820317169e002016">hasMips64r5</a>.</p>


<p>Referenced by <a href="#ae7b263db1194beb382f8ebc755238b77">MipsSubtarget</a>.</p>

</div>
</div>

### hasMips32r6() {#a00fc7567082e1f37e03204a7c619d87e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MipsSubtarget::hasMips32r6 ()</td>
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



<p>Definition at line 274 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-h">MipsSubtarget.h</a>.</p>


<p>Reference <a href="#a53196bab025b7327f8469ae9e3aa412f">hasMips64r6</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mipsregisterinfo/#adaa5e0accb1116b3b1395ac79842e955">llvm::MipsRegisterInfo::getCalleeSavedRegs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsseregisterinfo-cpp/#ae4f8119e930e450734d4903391aca1fa">getLoadStoreOffsetSizeInBits</a>, <a href="#aa1f7337fee0dd9434aead825eab6ba58">inMicroMips32r6Mode</a>, <a href="#ae7b263db1194beb382f8ebc755238b77">MipsSubtarget</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-cpp/#a830e51b63befaa067f822c088dd8833b">performADDCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-cpp/#a9a5205b95660638f4c7d889f588251e7">performSUBCombine</a> and <a href="#a9787dc07213aa611bd508f5333b609f7">systemSupportsUnalignedAccess</a>.</p>

</div>
</div>

### hasMips4() {#a064c2575d49c4902674326719c0de738}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MipsSubtarget::hasMips4 ()</td>
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



<p>Definition at line 254 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-h">MipsSubtarget.h</a>.</p>

</div>
</div>

### hasMips4\_32() {#a2c2a87b68328139d9d5539168b83f9ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MipsSubtarget::hasMips4_32 ()</td>
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



<p>Definition at line 256 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-h">MipsSubtarget.h</a>.</p>

</div>
</div>

### hasMips4\_32r2() {#aa8ebe3f0af9bf547ff6a401eaf50c8bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MipsSubtarget::hasMips4_32r2 ()</td>
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



<p>Definition at line 257 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-h">MipsSubtarget.h</a>.</p>

</div>
</div>

### hasMips5() {#a6709172c1e9c3deca20041dad9b39dbf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MipsSubtarget::hasMips5 ()</td>
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



<p>Definition at line 255 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-h">MipsSubtarget.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-mipsdelayslotfiller-cpp-/mipsdelayslotfiller/#a12bbaf2ff79b0813af362fb00de513b2">anonymous{MipsDelaySlotFiller.cpp}::MipsDelaySlotFiller::searchRange</a>.</p>

</div>
</div>

### hasMips64() {#a685938c15d608493edc6a06191042ea3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MipsSubtarget::hasMips64 ()</td>
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



<p>Definition at line 278 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-h">MipsSubtarget.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mipsregisterinfo/#adaa5e0accb1116b3b1395ac79842e955">llvm::MipsRegisterInfo::getCalleeSavedRegs</a>, <a href="#a6c595885100ac9cf852be70151cc51d6">hasMips32</a>, <a href="#ae7b263db1194beb382f8ebc755238b77">MipsSubtarget</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-cpp/#a313d642b3a7b838825ec80b84909b9ce">performMADD_MSUBCombine</a>.</p>

</div>
</div>

### hasMips64r2() {#a0923b731e7f389c4f1b9d0428bf129aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MipsSubtarget::hasMips64r2 ()</td>
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



<p>Definition at line 279 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-h">MipsSubtarget.h</a>.</p>


<p>Referenced by <a href="#aa225d65026d63bc4a90f91a57ac705df">hasMips32r2</a>, <a href="#a3cf5610ecf4df7bfcae79dc4b3ac270e">hasMips32r3</a>, <a href="#ae7b263db1194beb382f8ebc755238b77">MipsSubtarget</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-cpp/#abcb6ebd6de53d9ed63cd065dd4128261">performORCombine</a>.</p>

</div>
</div>

### hasMips64r3() {#af3ad0e2ad34109a5c9d424802e36dde8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MipsSubtarget::hasMips64r3 ()</td>
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



<p>Definition at line 280 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-h">MipsSubtarget.h</a>.</p>

</div>
</div>

### hasMips64r5() {#adb50ef5630bc839a820317169e002016}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MipsSubtarget::hasMips64r5 ()</td>
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



<p>Definition at line 281 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-h">MipsSubtarget.h</a>.</p>


<p>Referenced by <a href="#a108b5c98377ac15eb6b1b2d423e1808f">hasMips32r5</a>.</p>

</div>
</div>

### hasMips64r6() {#a53196bab025b7327f8469ae9e3aa412f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MipsSubtarget::hasMips64r6 ()</td>
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



<p>Definition at line 282 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-h">MipsSubtarget.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mipsregisterinfo/#adaa5e0accb1116b3b1395ac79842e955">llvm::MipsRegisterInfo::getCalleeSavedRegs</a>, <a href="#a00fc7567082e1f37e03204a7c619d87e">hasMips32r6</a> and <a href="#ae7b263db1194beb382f8ebc755238b77">MipsSubtarget</a>.</p>

</div>
</div>

### hasMSA() {#ab042d4cff6de998047eddaba9ed25a06}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MipsSubtarget::hasMSA ()</td>
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



<p>Definition at line 326 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-h">MipsSubtarget.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsregisterbankinfo-cpp/#a266eeca30be14882336c5b3df06bd770">getMSAMapping</a>, <a href="#ae7b263db1194beb382f8ebc755238b77">MipsSubtarget</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsseisellowering-cpp/#aa20249b0c2be4c3930493f53d8d4a5e5">performANDCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsseisellowering-cpp/#abcb6ebd6de53d9ed63cd065dd4128261">performORCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsseisellowering-cpp/#a56ba18b7bb062d32ea351c6349a415c6">performSRACombine</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsseisellowering-cpp/#a14fe6050fa67f0e7b01314d5c7586b8e">performXORCombine</a>.</p>

</div>
</div>

### hasMT() {#a2c934c225110ef46d10dcb64fc8d49a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MipsSubtarget::hasMT ()</td>
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



<p>Definition at line 329 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-h">MipsSubtarget.h</a>.</p>

</div>
</div>

### hasMTHC1() {#acad59be25c017c562ef9bfcd94800e74}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MipsSubtarget::hasMTHC1 ()</td>
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



<p>Definition at line 352 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-h">MipsSubtarget.h</a>.</p>


<p>Reference <a href="#aa225d65026d63bc4a90f91a57ac705df">hasMips32r2</a>.</p>

</div>
</div>

### hasStandardEncoding() {#acd8a67f4bcda85d4e861fc11cf0c49d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MipsSubtarget::hasStandardEncoding ()</td>
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



<p>Definition at line 338 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-h">MipsSubtarget.h</a>.</p>


<p>Referenced by <a href="#a9ba9fcfab91c1e464efa881fcf47e607">enableLongBranchPass</a>.</p>

</div>
</div>

### hasSym32() {#a767bbaf46ecf142dc608b77a69ffca2d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MipsSubtarget::hasSym32 ()</td>
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



<p>Definition at line 300 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-h">MipsSubtarget.h</a>.</p>


<p>References <a href="#ac02bea8ca73149f8cc190e33553a8dec">isABI_N32</a>, <a href="#a4fea8a54127e89dd0e6aec5afba826a1">isABI_N64</a> and <a href="#ab590cd4af22d8898397715814cf3bdd7">isABI_O32</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mipsasmprinter/#ab6c19f9c58c4900d034813254d2336aa">llvm::MipsAsmPrinter::emitStartOfAsmFile</a> and <a href="#ae7b263db1194beb382f8ebc755238b77">MipsSubtarget</a>.</p>

</div>
</div>

### hasVFPU() {#a637dbc87a9670a4b2de30ceca1427a88}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MipsSubtarget::hasVFPU ()</td>
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



<p>Definition at line 306 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-h">MipsSubtarget.h</a>.</p>

</div>
</div>

### hasVirt() {#a39ed159bebcfc2232175baeca130bbe5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MipsSubtarget::hasVirt ()</td>
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



<p>Definition at line 331 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-h">MipsSubtarget.h</a>.</p>


<p>Referenced by <a href="#ae7b263db1194beb382f8ebc755238b77">MipsSubtarget</a>.</p>

</div>
</div>

### inAbs2008Mode() {#a814d09d0448d8ebe3d64744bb221cec1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MipsSubtarget::inAbs2008Mode ()</td>
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



<p>Definition at line 294 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-h">MipsSubtarget.h</a>.</p>


<p>Referenced by <a href="#ae7b263db1194beb382f8ebc755238b77">MipsSubtarget</a>.</p>

</div>
</div>

### initializeSubtargetDependencies() {#a5b37851d4a9eb9835f16b127b83ccf9e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MipsSubtarget &amp; MipsSubtarget::initializeSubtargetDependencies (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> CPU, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> FS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetmachine">TargetMachine</a> &amp; TM)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 373 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-h">MipsSubtarget.h</a>, definition at line 246 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-cpp">MipsSubtarget.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ac02bea8ca73149f8cc190e33553a8dec">isABI_N32</a>, <a href="#a4fea8a54127e89dd0e6aec5afba826a1">isABI_N64</a>, <a href="#ab590cd4af22d8898397715814cf3bdd7">isABI_O32</a>, <a href="#a9b50ba1092e9b3e6d57c4170d739133e">isGP64bit</a>, <a href="#a8cb93358a2bc808bd636f5e2cc906e4e">ParseSubtargetFeatures</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a> and <a href="/web-llvm/docs/api/namespaces/llvm/mips-mc/#a3b7894a609c75844e531ceee963dea57">llvm::MIPS_MC::selectMipsCPU</a>.</p>


<p>Referenced by <a href="#ae7b263db1194beb382f8ebc755238b77">MipsSubtarget</a>.</p>

</div>
</div>

### inMicroMips32r6Mode() {#aa1f7337fee0dd9434aead825eab6ba58}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MipsSubtarget::inMicroMips32r6Mode ()</td>
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



<p>Definition at line 319 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-h">MipsSubtarget.h</a>.</p>


<p>References <a href="#a00fc7567082e1f37e03204a7c619d87e">hasMips32r6</a> and <a href="#a102ee3949228f2c8c1902c3ab7b70efc">inMicroMipsMode</a>.</p>

</div>
</div>

### inMicroMipsMode() {#a102ee3949228f2c8c1902c3ab7b70efc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MipsSubtarget::inMicroMipsMode ()</td>
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



<p>Definition at line 318 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-h">MipsSubtarget.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsasmprinter-cpp/#a487192753b68b0e4380e9d999a5b1549">emitDirectiveRelocJalr</a>, <a href="#a9ba9fcfab91c1e464efa881fcf47e607">enableLongBranchPass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsseregisterinfo-cpp/#ae4f8119e930e450734d4903391aca1fa">getLoadStoreOffsetSizeInBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsseinstrinfo-cpp/#a3c6c29487dd368344af8aa71893cfea5">getUnconditionalBranch</a>, <a href="#aa1f7337fee0dd9434aead825eab6ba58">inMicroMips32r6Mode</a> and <a href="/web-llvm/docs/api/classes/anonymous-mipsdelayslotfiller-cpp-/mipsdelayslotfiller/#a12bbaf2ff79b0813af362fb00de513b2">anonymous{MipsDelaySlotFiller.cpp}::MipsDelaySlotFiller::searchRange</a>.</p>

</div>
</div>

### inMips16HardFloat() {#ac77c16f733d57892503f227844026d5e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MipsSubtarget::inMips16HardFloat ()</td>
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



<p>Definition at line 315 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-h">MipsSubtarget.h</a>.</p>


<p>Reference <a href="#a665e2ef3a476d2de4052b40756af0976">inMips16Mode</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mipsccstate/#adffd27d3c37f8d01edff0e86ec3ff644">llvm::MipsCCState::getSpecialCallingConvForCallee</a>.</p>

</div>
</div>

### inMips16Mode() {#a665e2ef3a476d2de4052b40756af0976}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MipsSubtarget::inMips16Mode ()</td>
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



<p>Definition at line 307 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-h">MipsSubtarget.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mipsregisterinfo/#a6e2d4106e3ee3d0463f29dea987d698f">llvm::MipsRegisterInfo::canRealignStack</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsinstrinfo/#ab1cad5af795eb63d2436bc3a946f82bf">llvm::MipsInstrInfo::create</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetlowering/#a15f65769a3b8f609efbdc7eba633c1cc">llvm::MipsTargetLowering::create</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsregisterinfo/#a233e4dd01a9c98f407775d1061ec5d97">llvm::MipsRegisterInfo::getFrameRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsregisterinfo/#ab03f0084e766f3636a1eb7832061fd94">llvm::MipsRegisterInfo::getReservedRegs</a>, <a href="#a9b8326862ae7ce49518000abc157d094">hasExtractInsert</a>, <a href="#ac77c16f733d57892503f227844026d5e">inMips16HardFloat</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-cpp/#a830e51b63befaa067f822c088dd8833b">performADDCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-cpp/#a9a5205b95660638f4c7d889f588251e7">performSUBCombine</a> and <a href="/web-llvm/docs/api/classes/anonymous-mipsoptimizepiccall-cpp-/optimizepiccall/#af8fb60c334fa1c7571459b115762b09e">anonymous{MipsOptimizePICCall.cpp}::OptimizePICCall::runOnMachineFunction</a>.</p>

</div>
</div>

### inMips16ModeDefault() {#ab791e3581e4e931933745076de5b41cd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MipsSubtarget::inMips16ModeDefault ()</td>
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



<p>Definition at line 308 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-h">MipsSubtarget.h</a>.</p>


<p>Referenced by <a href="#a62f3e08f89b830c7ba194a8aad8794f1">allowMixed16_32</a>.</p>

</div>
</div>

### isABI\_FPXX() {#a7c3259b8d9942f4dcd6a171b435246ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MipsSubtarget::isABI_FPXX ()</td>
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



<p>Definition at line 238 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-h">MipsSubtarget.h</a>.</p>


<p>Reference <a href="#ab590cd4af22d8898397715814cf3bdd7">isABI_O32</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mipsasmprinter/#ab6c19f9c58c4900d034813254d2336aa">llvm::MipsAsmPrinter::emitStartOfAsmFile</a>.</p>

</div>
</div>

### isABI\_N32() {#ac02bea8ca73149f8cc190e33553a8dec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsSubtarget::isABI_N32 ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 235 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-h">MipsSubtarget.h</a>, definition at line 285 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-cpp">MipsSubtarget.cpp</a>.</p>


<p>References <a href="#af93bc0064abe6e9327c9843946c9c658">getABI</a> and <a href="/web-llvm/docs/api/classes/llvm/mipsabiinfo/#ac59352a7ddd52db0dabe853439909dc6">llvm::MipsABIInfo::IsN32</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mipsregisterinfo/#adaa5e0accb1116b3b1395ac79842e955">llvm::MipsRegisterInfo::getCalleeSavedRegs</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsregisterinfo/#a1d2b464302a40c788aa57242b5b199c9">llvm::MipsRegisterInfo::getCallPreservedMask</a>, <a href="#a767bbaf46ecf142dc608b77a69ffca2d">hasSym32</a>, <a href="#a5b37851d4a9eb9835f16b127b83ccf9e">initializeSubtargetDependencies</a> and <a href="#ae7b263db1194beb382f8ebc755238b77">MipsSubtarget</a>.</p>

</div>
</div>

### isABI\_N64() {#a4fea8a54127e89dd0e6aec5afba826a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsSubtarget::isABI_N64 ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 234 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-h">MipsSubtarget.h</a>, definition at line 284 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-cpp">MipsSubtarget.cpp</a>.</p>


<p>References <a href="#af93bc0064abe6e9327c9843946c9c658">getABI</a> and <a href="/web-llvm/docs/api/classes/llvm/mipsabiinfo/#a0630cff2e64996376ddcaa94211c4eac">llvm::MipsABIInfo::IsN64</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mipsregisterinfo/#adaa5e0accb1116b3b1395ac79842e955">llvm::MipsRegisterInfo::getCalleeSavedRegs</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsregisterinfo/#a1d2b464302a40c788aa57242b5b199c9">llvm::MipsRegisterInfo::getCallPreservedMask</a>, <a href="#a767bbaf46ecf142dc608b77a69ffca2d">hasSym32</a>, <a href="#a5b37851d4a9eb9835f16b127b83ccf9e">initializeSubtargetDependencies</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsseinstrinfo/#aa40f4913df15aca03301144b7f1673df">llvm::MipsSEInstrInfo::loadImmediate</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsseisellowering-cpp/#aeb20a43b07e1349fa2a4b5a0bf9e0f70">lowerMSALoadIntr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsseisellowering-cpp/#a482f3c559608a1d6280070b682876bae">lowerMSAStoreIntr</a> and <a href="#ae7b263db1194beb382f8ebc755238b77">MipsSubtarget</a>.</p>

</div>
</div>

### isABI\_O32() {#ab590cd4af22d8898397715814cf3bdd7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsSubtarget::isABI_O32 ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 236 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-h">MipsSubtarget.h</a>, definition at line 286 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-cpp">MipsSubtarget.cpp</a>.</p>


<p>References <a href="#af93bc0064abe6e9327c9843946c9c658">getABI</a> and <a href="/web-llvm/docs/api/classes/llvm/mipsabiinfo/#aefb3a7a1d98e9fbb76e87a71aafdbc6d">llvm::MipsABIInfo::IsO32</a>.</p>


<p>Referenced by <a href="#a767bbaf46ecf142dc608b77a69ffca2d">hasSym32</a>, <a href="#a5b37851d4a9eb9835f16b127b83ccf9e">initializeSubtargetDependencies</a>, <a href="#a7c3259b8d9942f4dcd6a171b435246ee">isABI_FPXX</a>, <a href="#ae7b263db1194beb382f8ebc755238b77">MipsSubtarget</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsseisellowering-cpp/#ac326b52d617d41f386c715d297f96a72">shouldTransformMulToShiftsAddsSubs</a>.</p>

</div>
</div>

### isABICalls() {#a86a38d27500447408085bf13ef73cea7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MipsSubtarget::isABICalls ()</td>
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



<p>Definition at line 288 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-h">MipsSubtarget.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mipsasmprinter/#ab6c19f9c58c4900d034813254d2336aa">llvm::MipsAsmPrinter::emitStartOfAsmFile</a> and <a href="/web-llvm/docs/api/classes/llvm/mipsregisterinfo/#ab03f0084e766f3636a1eb7832061fd94">llvm::MipsRegisterInfo::getReservedRegs</a>.</p>

</div>
</div>

### isFP64bit() {#a0abbd953996acada93c1609744afaa88}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MipsSubtarget::isFP64bit ()</td>
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



<p>Definition at line 290 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-h">MipsSubtarget.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mipsasmprinter/#ab6c19f9c58c4900d034813254d2336aa">llvm::MipsAsmPrinter::emitStartOfAsmFile</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsregisterinfo/#adaa5e0accb1116b3b1395ac79842e955">llvm::MipsRegisterInfo::getCalleeSavedRegs</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsregisterinfo/#a1d2b464302a40c788aa57242b5b199c9">llvm::MipsRegisterInfo::getCallPreservedMask</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsregisterinfo/#ab03f0084e766f3636a1eb7832061fd94">llvm::MipsRegisterInfo::getReservedRegs</a> and <a href="#ae7b263db1194beb382f8ebc755238b77">MipsSubtarget</a>.</p>

</div>
</div>

### isFPXX() {#af12582b8591c7665d801330f3ba614c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MipsSubtarget::isFPXX ()</td>
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



<p>Definition at line 289 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-h">MipsSubtarget.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mipsregisterinfo/#adaa5e0accb1116b3b1395ac79842e955">llvm::MipsRegisterInfo::getCalleeSavedRegs</a> and <a href="/web-llvm/docs/api/classes/llvm/mipsregisterinfo/#a1d2b464302a40c788aa57242b5b199c9">llvm::MipsRegisterInfo::getCallPreservedMask</a>.</p>

</div>
</div>

### isGP32bit() {#a2fa92ba21c318dedacf2b3497ce40641}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MipsSubtarget::isGP32bit ()</td>
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



<p>Definition at line 296 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-h">MipsSubtarget.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mipsregisterinfo/#a6e2d4106e3ee3d0463f29dea987d698f">llvm::MipsRegisterInfo::canRealignStack</a>.</p>

</div>
</div>

### isGP64bit() {#a9b50ba1092e9b3e6d57c4170d739133e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MipsSubtarget::isGP64bit ()</td>
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



<p>Definition at line 295 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-h">MipsSubtarget.h</a>.</p>


<p>Referenced by <a href="#acf29f2a58775e014e7e798ef8d4078aa">getCriticalPathRCs</a>, <a href="#ac052de3ee550e1dca1c71e6021d32e9b">getGPRSizeInBytes</a>, <a href="#a5b37851d4a9eb9835f16b127b83ccf9e">initializeSubtargetDependencies</a> and <a href="#ae7b263db1194beb382f8ebc755238b77">MipsSubtarget</a>.</p>

</div>
</div>

### isLittle() {#a0f2915eb956ce94ea0fd4a194dac24e1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MipsSubtarget::isLittle ()</td>
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



<p>Definition at line 287 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-h">MipsSubtarget.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-cpp/#a169d373fe5dc70c88b2a47ff825e3203">CC_MipsO32</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsseisellowering-cpp/#a1cb3d0ba0717491c0c28dcc2e4b3d152">performDSPShiftCombine</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsseisellowering-cpp/#abcb6ebd6de53d9ed63cd065dd4128261">performORCombine</a>.</p>

</div>
</div>

### isNaN2008() {#a545182303fb7b5b50d3ff65006ed9263}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MipsSubtarget::isNaN2008 ()</td>
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



<p>Definition at line 293 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-h">MipsSubtarget.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mipsasmprinter/#ab6c19f9c58c4900d034813254d2336aa">llvm::MipsAsmPrinter::emitStartOfAsmFile</a> and <a href="#ae7b263db1194beb382f8ebc755238b77">MipsSubtarget</a>.</p>

</div>
</div>

### isPositionIndependent() {#a98180cb9502db31783e9610b9afdf6a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsSubtarget::isPositionIndependent ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 228 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-h">MipsSubtarget.h</a>, definition at line 228 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-cpp">MipsSubtarget.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsseinstrinfo-cpp/#a3c6c29487dd368344af8aa71893cfea5">getUnconditionalBranch</a>.</p>

</div>
</div>

### isPTR32bit() {#a733bd521aa3c58f4c7aae3a009db5c44}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MipsSubtarget::isPTR32bit ()</td>
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



<p>Definition at line 299 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-h">MipsSubtarget.h</a>.</p>

</div>
</div>

### isPTR64bit() {#af2685456833bb936c5a7ce7f85d1a405}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MipsSubtarget::isPTR64bit ()</td>
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



<p>Definition at line 298 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-h">MipsSubtarget.h</a>.</p>

</div>
</div>

### isSingleFloat() {#ab433146b1864babd91f6017fae56dd50}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MipsSubtarget::isSingleFloat ()</td>
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



<p>Definition at line 303 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-h">MipsSubtarget.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mipsregisterinfo/#adaa5e0accb1116b3b1395ac79842e955">llvm::MipsRegisterInfo::getCalleeSavedRegs</a> and <a href="/web-llvm/docs/api/classes/llvm/mipsregisterinfo/#a1d2b464302a40c788aa57242b5b199c9">llvm::MipsRegisterInfo::getCallPreservedMask</a>.</p>

</div>
</div>

### isTargetCOFF() {#aa586b2c43b384525cc14462210688af4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MipsSubtarget::isTargetCOFF ()</td>
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



<p>Definition at line 304 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-h">MipsSubtarget.h</a>.</p>

</div>
</div>

### isTargetELF() {#a0b1a490ffae2b318cd63983aac82a5ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MipsSubtarget::isTargetELF ()</td>
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



<p>Definition at line 305 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-h">MipsSubtarget.h</a>.</p>

</div>
</div>

### isTargetNaCl() {#ade22344fec068aba4bd0d1109d98140d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MipsSubtarget::isTargetNaCl ()</td>
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



<p>Definition at line 359 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-h">MipsSubtarget.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mipsregisterinfo/#ab03f0084e766f3636a1eb7832061fd94">llvm::MipsRegisterInfo::getReservedRegs</a> and <a href="/web-llvm/docs/api/classes/anonymous-mipsdelayslotfiller-cpp-/mipsdelayslotfiller/#a12bbaf2ff79b0813af362fb00de513b2">anonymous{MipsDelaySlotFiller.cpp}::MipsDelaySlotFiller::searchRange</a>.</p>

</div>
</div>

### isTargetWindows() {#aac397824ac11b8375f102c428bb54ee7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MipsSubtarget::isTargetWindows ()</td>
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



<p>Definition at line 360 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-h">MipsSubtarget.h</a>.</p>

</div>
</div>

### isXRaySupported() {#a0291cacff322d690e5c89ba3a7c29394}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MipsSubtarget::isXRaySupported ()</td>
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



<p>Definition at line 362 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-h">MipsSubtarget.h</a>.</p>

</div>
</div>

### noOddSPReg() {#a83080e9a860cb80126ed1d142476b763}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MipsSubtarget::noOddSPReg ()</td>
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



<p>Definition at line 292 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-h">MipsSubtarget.h</a>.</p>

</div>
</div>

### os16() {#a876e8fceab3b87595bb00188950665a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MipsSubtarget::os16 ()</td>
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



<p>Definition at line 357 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-h">MipsSubtarget.h</a>.</p>

</div>
</div>

### ParseSubtargetFeatures() {#a8cb93358a2bc808bd636f5e2cc906e4e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MipsSubtarget::ParseSubtargetFeatures (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> CPU, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> TuneCPU, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> FS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>ParseSubtargetFeatures - Parses features string setting specified subtarget options.</p>


<p>Definition of function is auto generated by tblgen.</p>


<p>Definition at line 249 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-h">MipsSubtarget.h</a>.</p>


<p>Referenced by <a href="#a5b37851d4a9eb9835f16b127b83ccf9e">initializeSubtargetDependencies</a>.</p>

</div>
</div>

### setHelperClassesMips16() {#a81fcf9b949e1a296eee42e0e0f182cd8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MipsSubtarget::setHelperClassesMips16 ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 386 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-h">MipsSubtarget.h</a>.</p>

</div>
</div>

### setHelperClassesMipsSE() {#a9bf60a9627bfee7d88f9f59dfad23681}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MipsSubtarget::setHelperClassesMipsSE ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 387 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-h">MipsSubtarget.h</a>.</p>

</div>
</div>

### systemSupportsUnalignedAccess() {#a9787dc07213aa611bd508f5333b609f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MipsSubtarget::systemSupportsUnalignedAccess ()</td>
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

<p>Does the system support unaligned memory access.</p>


<p>MIPS32r6/MIPS64r6 require full unaligned access support but does not specify which component of the system provides it. Hardware, software, and hybrid implementations are all valid.</p>


<p>Definition at line 381 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-h">MipsSubtarget.h</a>.</p>


<p>Reference <a href="#a00fc7567082e1f37e03204a7c619d87e">hasMips32r6</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsregisterbankinfo-cpp/#a4c0189cb020c7eb65987eebfd1712038">isGprbTwoInstrUnalignedLoadOrStore</a>.</p>

</div>
</div>

### useIndirectJumpsHazard() {#a524791d1032e1a9e65b0c43ee4b2859c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MipsSubtarget::useIndirectJumpsHazard ()</td>
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



<p>Definition at line 333 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-h">MipsSubtarget.h</a>.</p>


<p>Reference <a href="#aa225d65026d63bc4a90f91a57ac705df">hasMips32r2</a>.</p>

</div>
</div>

### useLongCalls() {#aba475652437691d8a20fccc8df6839bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MipsSubtarget::useLongCalls ()</td>
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



<p>Definition at line 342 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-h">MipsSubtarget.h</a>.</p>

</div>
</div>

### useOddSPReg() {#a5494959f8945d509cb143ebabcc9f3c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MipsSubtarget::useOddSPReg ()</td>
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



<p>Definition at line 291 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-h">MipsSubtarget.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mipsasmprinter/#ab6c19f9c58c4900d034813254d2336aa">llvm::MipsAsmPrinter::emitStartOfAsmFile</a> and <a href="#ae7b263db1194beb382f8ebc755238b77">MipsSubtarget</a>.</p>

</div>
</div>

### useSmallSection() {#ac39000d549551360d4a1f23659162878}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MipsSubtarget::useSmallSection ()</td>
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



<p>Definition at line 336 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-h">MipsSubtarget.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mipsregisterinfo/#ab03f0084e766f3636a1eb7832061fd94">llvm::MipsRegisterInfo::getReservedRegs</a>.</p>

</div>
</div>

### useSoftFloat() {#a3ec2bbbdcfbc738f451f0b7aaa85584d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MipsSubtarget::useSoftFloat ()</td>
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



<p>Definition at line 340 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-h">MipsSubtarget.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mipsasmprinter/#ab6c19f9c58c4900d034813254d2336aa">llvm::MipsAsmPrinter::emitStartOfAsmFile</a>.</p>

</div>
</div>

### useXGOT() {#a808b6c33b6dfbaee71a7ac5d86108f02}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MipsSubtarget::useXGOT ()</td>
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



<p>Definition at line 344 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-h">MipsSubtarget.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### anchor() {#a9812b285685d106fa1a8a5c26b27b460}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MipsSubtarget::anchor ()</td>
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



<p>Declaration at line 38 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-h">MipsSubtarget.h</a>, definition at line 69 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-cpp">MipsSubtarget.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### CallLoweringInfo {#a81dc3806052d69678e8fbfea8d9476ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;CallLowering&gt; llvm::MipsSubtarget::CallLoweringInfo</td>
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



<p>Definition at line 407 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-h">MipsSubtarget.h</a>.</p>


<p>Referenced by <a href="#a5b4325d736b4f1e92fb930939abc74e1">getCallLowering</a> and <a href="#ae7b263db1194beb382f8ebc755238b77">MipsSubtarget</a>.</p>

</div>
</div>

### InstSelector {#a357413e9cd61b004b4cc87dc35c9154c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;InstructionSelector&gt; llvm::MipsSubtarget::InstSelector</td>
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



<p>Definition at line 410 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-h">MipsSubtarget.h</a>.</p>


<p>Referenced by <a href="#aac661a4addb01d46a2850ba9269a0a29">getInstructionSelector</a> and <a href="#ae7b263db1194beb382f8ebc755238b77">MipsSubtarget</a>.</p>

</div>
</div>

### Legalizer {#ab58aa66844773792a635ff42ba45c0ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;LegalizerInfo&gt; llvm::MipsSubtarget::Legalizer</td>
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



<p>Definition at line 408 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-h">MipsSubtarget.h</a>.</p>


<p>Referenced by <a href="#a04e22d0a7e2ff0b3b26a5940f90f1c5a">getLegalizerInfo</a> and <a href="#ae7b263db1194beb382f8ebc755238b77">MipsSubtarget</a>.</p>

</div>
</div>

### RegBankInfo {#a5eab98d9ea4f0371975931c7b7a64ee8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;RegisterBankInfo&gt; llvm::MipsSubtarget::RegBankInfo</td>
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



<p>Definition at line 409 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-h">MipsSubtarget.h</a>.</p>


<p>Referenced by <a href="#a8d2cdab8e2580db4f5df4e77c814c781">getRegBankInfo</a> and <a href="#ae7b263db1194beb382f8ebc755238b77">MipsSubtarget</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Abs2008 {#abe7e7bf69bbc668c44d16f628c4271ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MipsSubtarget::Abs2008</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 91 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-h">MipsSubtarget.h</a>.</p>

</div>
</div>

### AllowMixed16\_32 {#aff1ad8e1fdad53b3464c0a07b25961b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MipsSubtarget::AllowMixed16_32</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 157 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-h">MipsSubtarget.h</a>.</p>

</div>
</div>

### DisableMadd4 {#af507db1e10f04a5fc6521b789dadf653}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MipsSubtarget::DisableMadd4</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 178 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-h">MipsSubtarget.h</a>.</p>

</div>
</div>

### FrameLowering {#a778b77e453bce62d19b9586a98d9c751}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;const MipsFrameLowering&gt; llvm::MipsSubtarget::FrameLowering</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 224 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-h">MipsSubtarget.h</a>.</p>

</div>
</div>

### Has3D {#a6b6e42c8019f001f77ba9795864ab317}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MipsSubtarget::Has3D</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 154 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-h">MipsSubtarget.h</a>.</p>

</div>
</div>

### HasCnMips {#ae6bbe8e77e07ebfd73deab49999b31a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MipsSubtarget::HasCnMips</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 113 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-h">MipsSubtarget.h</a>.</p>

</div>
</div>

### HasCnMipsP {#a68ed3d73baaccab32b8d7314abc693c6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MipsSubtarget::HasCnMipsP</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 116 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-h">MipsSubtarget.h</a>.</p>

</div>
</div>

### HasCRC {#adc3c123c97fa1d4878a4dd1053456e5a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MipsSubtarget::HasCRC</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 184 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-h">MipsSubtarget.h</a>.</p>

</div>
</div>

### HasDSP {#af953493a4f0c96be9943cab2fefd9c80}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MipsSubtarget::HasDSP</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 151 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-h">MipsSubtarget.h</a>.</p>

</div>
</div>

### HasDSPR2 {#a2156927151241af76a3357f1c6d5717e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MipsSubtarget::HasDSPR2</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 151 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-h">MipsSubtarget.h</a>.</p>

</div>
</div>

### HasDSPR3 {#a2fee268082bab583fbd277335165eec8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MipsSubtarget::HasDSPR3</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 151 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-h">MipsSubtarget.h</a>.</p>

</div>
</div>

### HasEVA {#a6158547e1fdb920d3946eb5200cc0204}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MipsSubtarget::HasEVA</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 174 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-h">MipsSubtarget.h</a>.</p>

</div>
</div>

### HasGINV {#a4b040d4a13d766e2870b4f0bfaafd41e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MipsSubtarget::HasGINV</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 190 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-h">MipsSubtarget.h</a>.</p>

</div>
</div>

### HasMips3\_32 {#aa2b591ce422e3b82b8704c7e1c179437}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MipsSubtarget::HasMips3_32</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Features related to the presence of specific instructions.</p>

<p>Definition at line 127 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-h">MipsSubtarget.h</a>.</p>

</div>
</div>

### HasMips3\_32r2 {#a5fe8b5f1ca47e282e136afea3458bc14}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MipsSubtarget::HasMips3_32r2</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 130 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-h">MipsSubtarget.h</a>.</p>

</div>
</div>

### HasMips4\_32 {#a6fcbabfc37937fd745759d68a0a550cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MipsSubtarget::HasMips4_32</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 133 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-h">MipsSubtarget.h</a>.</p>

</div>
</div>

### HasMips4\_32r2 {#a8014457bb4d58a2113e1df94ae3fe8e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MipsSubtarget::HasMips4_32r2</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 136 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-h">MipsSubtarget.h</a>.</p>

</div>
</div>

### HasMips5\_32r2 {#a7709ee417f8b3b09c1ed46c17af80eac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MipsSubtarget::HasMips5_32r2</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 139 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-h">MipsSubtarget.h</a>.</p>

</div>
</div>

### HasMSA {#a90e478432db3bab986e0f65b19923bb4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MipsSubtarget::HasMSA</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 165 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-h">MipsSubtarget.h</a>.</p>

</div>
</div>

### HasMT {#ace1fa367e9b3f8772de3e8219a5c6e58}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MipsSubtarget::HasMT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 181 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-h">MipsSubtarget.h</a>.</p>

</div>
</div>

### HasSym32 {#a0bd1db58d1d845f771786e7e8fe0462d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MipsSubtarget::HasSym32</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 171 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-h">MipsSubtarget.h</a>.</p>

</div>
</div>

### HasVFPU {#a50db89d241a9a9c9b5fc20ce74735fc5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MipsSubtarget::HasVFPU</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 110 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-h">MipsSubtarget.h</a>.</p>

</div>
</div>

### HasVirt {#a2ea9dd61f2202ab28555af25e43e3b66}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MipsSubtarget::HasVirt</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 187 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-h">MipsSubtarget.h</a>.</p>

</div>
</div>

### InMicroMipsMode {#a8c73f35ae5210d0e705de77a01f08f72}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MipsSubtarget::InMicroMipsMode</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 148 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-h">MipsSubtarget.h</a>.</p>

</div>
</div>

### InMips16HardFloat {#a6245e1446b13a3f8e220de3fd52ed567}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MipsSubtarget::InMips16HardFloat</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 145 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-h">MipsSubtarget.h</a>.</p>

</div>
</div>

### InMips16Mode {#ab3afe59e2d82ba4845a2249c6c68322e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MipsSubtarget::InMips16Mode</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 142 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-h">MipsSubtarget.h</a>.</p>

</div>
</div>

### InstrInfo {#aa19954ee4d61638f238528cf810ea266}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;const MipsInstrInfo&gt; llvm::MipsSubtarget::InstrInfo</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 223 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-h">MipsSubtarget.h</a>.</p>

</div>
</div>

### InstrItins {#a4b46179ddb974a2ecad00186d3aa3e3c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstrItineraryData llvm::MipsSubtarget::InstrItins</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 212 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-h">MipsSubtarget.h</a>.</p>

</div>
</div>

### IsFP64bit {#a9124a458304b75bf91c3117725e3efc5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MipsSubtarget::IsFP64bit</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 94 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-h">MipsSubtarget.h</a>.</p>

</div>
</div>

### IsFPXX {#a9df2942829be387a4e22b89787e2e09b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MipsSubtarget::IsFPXX</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 85 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-h">MipsSubtarget.h</a>.</p>

</div>
</div>

### IsGP64bit {#a7e0aa6a67426a08c884ad2bc8d49efb7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MipsSubtarget::IsGP64bit</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 104 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-h">MipsSubtarget.h</a>.</p>

</div>
</div>

### IsLinux {#a425ea9d861bc45b218cec6772ad24f71}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MipsSubtarget::IsLinux</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 119 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-h">MipsSubtarget.h</a>.</p>

</div>
</div>

### IsLittle {#a2d1d2774a2e91a1e2adf593ef457e3af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MipsSubtarget::IsLittle</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 74 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-h">MipsSubtarget.h</a>.</p>

</div>
</div>

### IsNaN2008bit {#ad8952ddce1bfa21ea965e78a0d6e50e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MipsSubtarget::IsNaN2008bit</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 101 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-h">MipsSubtarget.h</a>.</p>

</div>
</div>

### IsPTR64bit {#a9a42949c3dafe4cfd10c416b9764e72a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MipsSubtarget::IsPTR64bit</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 107 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-h">MipsSubtarget.h</a>.</p>

</div>
</div>

### IsSingleFloat {#aefad903f44a0eb8b1df7e8046ff70503}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MipsSubtarget::IsSingleFloat</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-h">MipsSubtarget.h</a>.</p>

</div>
</div>

### IsSoftFloat {#ad2dde4a558ba4e8b98c8d4597d2d1e42}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MipsSubtarget::IsSoftFloat</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 77 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-h">MipsSubtarget.h</a>.</p>

</div>
</div>

### MipsArchVersion {#ab1e7f8ec863b1240c370f7393e5a4a06}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MipsArchEnum llvm::MipsSubtarget::MipsArchVersion</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-h">MipsSubtarget.h</a>.</p>

</div>
</div>

### NoABICalls {#a0db6c4a2f269f21136062d4eeb8be58f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MipsSubtarget::NoABICalls</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 88 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-h">MipsSubtarget.h</a>.</p>

</div>
</div>

### Os16 {#ae1fce71e61e5f71a3504c96f619eec41}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MipsSubtarget::Os16</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 162 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-h">MipsSubtarget.h</a>.</p>

</div>
</div>

### OverrideMode {#a688367debf40c9142b39681bbe9b5893}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::MipsSubtarget llvm::MipsSubtarget::OverrideMode</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 216 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-h">MipsSubtarget.h</a>.</p>

</div>
</div>

### ProcImpl {#a0b6da9063a58f578a86dc06c087c7e66}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CPU llvm::MipsSubtarget::ProcImpl</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-h">MipsSubtarget.h</a>.</p>

</div>
</div>

### stackAlignment {#aac78027b75f10fd1dc8e47a4047d942e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Align llvm::MipsSubtarget::stackAlignment</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The minimum alignment known to hold of the stack frame on entry to the function and which must be maintained by every function.</p>

<p>Definition at line 207 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-h">MipsSubtarget.h</a>.</p>

</div>
</div>

### StackAlignOverride {#a60592d7ce04b851b2dbe5988280b2937}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MaybeAlign llvm::MipsSubtarget::StackAlignOverride</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The overridden stack alignment.</p>

<p>Definition at line 210 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-h">MipsSubtarget.h</a>.</p>

</div>
</div>

### StrictAlign {#a6aaaf1f48b12912212111c1abe0b65e5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MipsSubtarget::StrictAlign</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 203 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-h">MipsSubtarget.h</a>.</p>

</div>
</div>

### TargetTriple {#af428e68f6384904fe17cda10a5a77697}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Triple llvm::MipsSubtarget::TargetTriple</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 220 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-h">MipsSubtarget.h</a>.</p>

</div>
</div>

### TLInfo {#a8aee5e7318b26da4ecc136b66119b8da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;const MipsTargetLowering&gt; llvm::MipsSubtarget::TLInfo</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 225 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-h">MipsSubtarget.h</a>.</p>

</div>
</div>

### TM {#acf59a1f4f5528909c818de7522ed9970}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MipsTargetMachine&amp; llvm::MipsSubtarget::TM</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 218 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-h">MipsSubtarget.h</a>.</p>

</div>
</div>

### TSInfo {#af931fbefb9d80305517f218f8166a537}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;const SelectionDAGTargetInfo&gt; llvm::MipsSubtarget::TSInfo</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 222 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-h">MipsSubtarget.h</a>.</p>

</div>
</div>

### UseIndirectJumpsHazard {#ab7fa6d31b3035d0197cfce877f86ab11}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MipsSubtarget::UseIndirectJumpsHazard</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 194 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-h">MipsSubtarget.h</a>.</p>

</div>
</div>

### UseLongCalls {#a61943dde4d23d152bb989a1d2cd79fb6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MipsSubtarget::UseLongCalls = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 197 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-h">MipsSubtarget.h</a>.</p>

</div>
</div>

### UseOddSPReg {#a0f8eab64d891970dc1845e626125f81d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MipsSubtarget::UseOddSPReg</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Are odd single-precision registers permitted?</p>


<p>This corresponds to -modd-spreg and -mno-odd-spreg</p>


<p>Definition at line 98 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-h">MipsSubtarget.h</a>.</p>

</div>
</div>

### UseSmallSection {#a293ad777017ebe443c94cc53d306b372}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MipsSubtarget::UseSmallSection</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 122 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-h">MipsSubtarget.h</a>.</p>

</div>
</div>

### UseTCCInDIV {#a1f1992a5da4e0c642ccf0d950c1f6d95}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MipsSubtarget::UseTCCInDIV</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 168 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-h">MipsSubtarget.h</a>.</p>

</div>
</div>

### UseXGOT {#a5306bd7d2395907f7312345fcfaa3e48}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MipsSubtarget::UseXGOT = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 200 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-h">MipsSubtarget.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### useConstantIslands() {#a056776ea56d64939bb6cf447b0e24e3c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsSubtarget::useConstantIslands ()</td>
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



<p>Declaration at line 366 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-h">MipsSubtarget.h</a>, definition at line 274 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-cpp">MipsSubtarget.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-cpp/#a23799d552f362e8a74dc4d5ba084e1d0">Mips16ConstantIslands</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-mipsconstantislandpass-cpp-/mipsconstantislands/#a3bce3734199ffc400a2172acaaf616d0">anonymous{MipsConstantIslandPass.cpp}::MipsConstantIslands::runOnMachineFunction</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Attributes

### CRCWarningPrinted {#a48e631557778f1cbb6e1ffb3e6e55be9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsSubtarget::CRCWarningPrinted = false</td>
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



<p>Definition at line 55 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-h">MipsSubtarget.h</a>.</p>

</div>
</div>

### DspWarningPrinted {#a66ba28c2dad9cc8f28c0704c873a7205}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsSubtarget::DspWarningPrinted = false</td>
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



<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-h">MipsSubtarget.h</a>.</p>

</div>
</div>

### GINVWarningPrinted {#a1ae7d3830ab6dc1b8a6c6d884b0eec9e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsSubtarget::GINVWarningPrinted = false</td>
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



<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-h">MipsSubtarget.h</a>.</p>

</div>
</div>

### MIPS1WarningPrinted {#a88c101964bfb123391b8fddcfb9a9241}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsSubtarget::MIPS1WarningPrinted = false</td>
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



<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-h">MipsSubtarget.h</a>.</p>

</div>
</div>

### MSAWarningPrinted {#ad85047a29ef43117f4dd4c110f661650}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsSubtarget::MSAWarningPrinted = false</td>
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



<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-h">MipsSubtarget.h</a>.</p>

</div>
</div>

### VirtWarningPrinted {#accba0065d7d6938038dcbd3e81882da3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsSubtarget::VirtWarningPrinted = false</td>
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



<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-h">MipsSubtarget.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-cpp">MipsSubtarget.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipssubtarget-h">MipsSubtarget.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>

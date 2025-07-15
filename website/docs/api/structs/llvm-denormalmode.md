---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/denormalmode
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `DenormalMode` Struct Reference

<p>Represent subnormal handling kind for floating point instruction inputs and outputs. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::DenormalMode { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/floatingpointmode-h">llvm/ADT/FloatingPointMode.h</a>"
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">DenormalModeKind : int8_t { <a href="#a29b26e3ae30f3f6ec4106ff181282893">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Represent handled modes for denormal (aka subnormal) modes in the floating point environment. <a href="#a29b26e3ae30f3f6ec4106ff181282893">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad96de724aad364e26ee28cdf52fd6943">DenormalMode</a> ()=default</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4b202da837972c1d888800ddde783ecd">DenormalMode</a> (const DenormalMode &amp;)=default</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf884e500b6e13f208363e16bb8c01bf">DenormalMode</a> (DenormalModeKind Out, DenormalModeKind In)</td>
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

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/denormalmode">DenormalMode</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab57988ac0fc8592432171faf6c4b6cb5">operator=</a> (const DenormalMode &amp;)=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa855dc98825c2d5280daa12b8cb34949">operator==</a> (DenormalMode Other) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4ec7bc0edf1366472c4109dd76f8ce99">operator!=</a> (DenormalMode Other) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c4f83a3adadaf5324552427a9c239c3">isSimple</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad26d0c331e4714d8dc77cdd90d1d75d4">isValid</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a898bc0d2b24c32a5d732ae7a225c337c">inputsAreZero</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if input denormals must be implicitly treated as 0. <a href="#a898bc0d2b24c32a5d732ae7a225c337c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1cc624e88436331500750f5ffbef65e0">outputsAreZero</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if output denormals should be flushed to 0. <a href="#a1cc624e88436331500750f5ffbef65e0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/denormalmode">DenormalMode</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af397461b3c561d29aa674b4a4d3e5965">mergeCalleeMode</a> (DenormalMode Callee) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the effective denormal mode if the mode if this caller calls into a function with <span class="doxyComputerOutput">Callee</span>. <a href="#af397461b3c561d29aa674b4a4d3e5965">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4b4e3ec6987027fb07517701e7a0a1c2">print</a> (raw_ostream &amp;OS) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5bddda5caa6dff98255b45bf21144c3a">str</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a29b26e3ae30f3f6ec4106ff181282893">DenormalModeKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa1be940c9e7d0c7ed20dfdaf5731b082">Output</a> = <a href="#a29b26e3ae30f3f6ec4106ff181282893a72fe23f34a4f8005af6172748a69bc63">DenormalModeKind::Invalid</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Denormal flushing mode for floating point instruction results in the default floating point environment. <a href="#aa1be940c9e7d0c7ed20dfdaf5731b082">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a29b26e3ae30f3f6ec4106ff181282893">DenormalModeKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b79f1995991b0a757a4d04969c3717f">Input</a> = <a href="#a29b26e3ae30f3f6ec4106ff181282893a72fe23f34a4f8005af6172748a69bc63">DenormalModeKind::Invalid</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Denormal treatment kind for floating point instruction inputs in the default floating-point environment. <a href="#a1b79f1995991b0a757a4d04969c3717f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr <a href="/web-llvm/docs/api/structs/llvm/denormalmode">DenormalMode</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7326cc28954855133bd6efba8aa9724a">getInvalid</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr <a href="/web-llvm/docs/api/structs/llvm/denormalmode">DenormalMode</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5593567c266618b9001731accef54da8">getDefault</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the assumed default mode for a function without denormal-fp-math. <a href="#a5593567c266618b9001731accef54da8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr <a href="/web-llvm/docs/api/structs/llvm/denormalmode">DenormalMode</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afc06bc91a5873ec7efe616b733f2c5c8">getIEEE</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr <a href="/web-llvm/docs/api/structs/llvm/denormalmode">DenormalMode</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b25a485fab5c4ade966d2ad73bc2ccf">getPreserveSign</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr <a href="/web-llvm/docs/api/structs/llvm/denormalmode">DenormalMode</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3c136ee901a0b48c5bf4be4b29d58b58">getPositiveZero</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr <a href="/web-llvm/docs/api/structs/llvm/denormalmode">DenormalMode</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af51395b84b8db9baa750e7b9210eebb2">getDynamic</a> ()</td>
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

## Description {#details}

<p>Represent subnormal handling kind for floating point instruction inputs and outputs.</p>

<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/floatingpointmode-h">FloatingPointMode.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### DenormalModeKind {#a29b26e3ae30f3f6ec4106ff181282893}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::DenormalMode::DenormalModeKind : int8_t</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Represent handled modes for denormal (aka subnormal) modes in the floating point environment.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Invalid<a id="a29b26e3ae30f3f6ec4106ff181282893a72fe23f34a4f8005af6172748a69bc63"></a></td>
<td class="doxyEnumItemDescription"> (= -1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IEEE<a id="a29b26e3ae30f3f6ec4106ff181282893ad6fd23eb0b98a2d4551582753191b6da"></a></td>
<td class="doxyEnumItemDescription">IEEE-754 denormal numbers preserved</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PreserveSign<a id="a29b26e3ae30f3f6ec4106ff181282893a40bc80ae1d362a1461703637e946cbd8"></a></td>
<td class="doxyEnumItemDescription">The sign of a flushed-to-zero number is preserved in the sign of 0</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PositiveZero<a id="a29b26e3ae30f3f6ec4106ff181282893a7de61db082dcdc6e8d34d1c5fd2e9757"></a></td>
<td class="doxyEnumItemDescription">Denormals are flushed to positive zero</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Dynamic<a id="a29b26e3ae30f3f6ec4106ff181282893ab6083e266013055b6c2ef85b1e47444c"></a></td>
<td class="doxyEnumItemDescription">Denormals have unknown treatment</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/floatingpointmode-h">FloatingPointMode.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### DenormalMode() {#ad96de724aad364e26ee28cdf52fd6943}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DenormalMode::DenormalMode ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 98 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/floatingpointmode-h">FloatingPointMode.h</a>.</p>


<p>Referenced by <a href="#a4b202da837972c1d888800ddde783ecd">DenormalMode</a>, <a href="#a5593567c266618b9001731accef54da8">getDefault</a>, <a href="#af51395b84b8db9baa750e7b9210eebb2">getDynamic</a>, <a href="#afc06bc91a5873ec7efe616b733f2c5c8">getIEEE</a>, <a href="#a7326cc28954855133bd6efba8aa9724a">getInvalid</a>, <a href="#a3c136ee901a0b48c5bf4be4b29d58b58">getPositiveZero</a>, <a href="#a8b25a485fab5c4ade966d2ad73bc2ccf">getPreserveSign</a>, <a href="#af397461b3c561d29aa674b4a4d3e5965">mergeCalleeMode</a>, <a href="#a4ec7bc0edf1366472c4109dd76f8ce99">operator!=</a>, <a href="#ab57988ac0fc8592432171faf6c4b6cb5">operator=</a> and <a href="#aa855dc98825c2d5280daa12b8cb34949">operator==</a>.</p>

</div>
</div>

### DenormalMode() {#a4b202da837972c1d888800ddde783ecd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DenormalMode::DenormalMode (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/denormalmode">DenormalMode</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 99 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/floatingpointmode-h">FloatingPointMode.h</a>.</p>


<p>Reference <a href="#ad96de724aad364e26ee28cdf52fd6943">DenormalMode</a>.</p>

</div>
</div>

### DenormalMode() {#abf884e500b6e13f208363e16bb8c01bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DenormalMode::DenormalMode (<a href="#a29b26e3ae30f3f6ec4106ff181282893">DenormalModeKind</a> Out, <a href="#a29b26e3ae30f3f6ec4106ff181282893">DenormalModeKind</a> In)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 100 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/floatingpointmode-h">FloatingPointMode.h</a>.</p>


<p>References <a href="#a1b79f1995991b0a757a4d04969c3717f">Input</a> and <a href="#aa1be940c9e7d0c7ed20dfdaf5731b082">Output</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator!=() {#a4ec7bc0edf1366472c4109dd76f8ce99}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DenormalMode::operator!= (<a href="/web-llvm/docs/api/structs/llvm/denormalmode">DenormalMode</a> Other)</td>
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



<p>Definition at line 136 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/floatingpointmode-h">FloatingPointMode.h</a>.</p>


<p>References <a href="#ad96de724aad364e26ee28cdf52fd6943">DenormalMode</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>.</p>

</div>
</div>

### operator=() {#ab57988ac0fc8592432171faf6c4b6cb5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenormalMode &amp; llvm::DenormalMode::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/denormalmode">DenormalMode</a> &amp;)</td>
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



<p>Definition at line 103 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/floatingpointmode-h">FloatingPointMode.h</a>.</p>


<p>Reference <a href="#ad96de724aad364e26ee28cdf52fd6943">DenormalMode</a>.</p>

</div>
</div>

### operator==() {#aa855dc98825c2d5280daa12b8cb34949}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DenormalMode::operator== (<a href="/web-llvm/docs/api/structs/llvm/denormalmode">DenormalMode</a> Other)</td>
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



<p>Definition at line 132 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/floatingpointmode-h">FloatingPointMode.h</a>.</p>


<p>References <a href="#ad96de724aad364e26ee28cdf52fd6943">DenormalMode</a>, <a href="#a1b79f1995991b0a757a4d04969c3717f">Input</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a> and <a href="#aa1be940c9e7d0c7ed20dfdaf5731b082">Output</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### inputsAreZero() {#a898bc0d2b24c32a5d732ae7a225c337c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DenormalMode::inputsAreZero ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if input denormals must be implicitly treated as 0.</p>

<p>Definition at line 150 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/floatingpointmode-h">FloatingPointMode.h</a>.</p>


<p>References <a href="#a1b79f1995991b0a757a4d04969c3717f">Input</a>, <a href="#a29b26e3ae30f3f6ec4106ff181282893a7de61db082dcdc6e8d34d1c5fd2e9757">PositiveZero</a> and <a href="#a29b26e3ae30f3f6ec4106ff181282893a40bc80ae1d362a1461703637e946cbd8">PreserveSign</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#aff704e68e1a7f944f4a81ce9ef713ba4">computeKnownFPClass</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/targetlowering-cpp/#a939a9cb864b778eb29af330d62308ba4">isFCmpEqualZero</a>.</p>

</div>
</div>

### isSimple() {#a6c4f83a3adadaf5324552427a9c239c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DenormalMode::isSimple ()</td>
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



<p>Definition at line 140 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/floatingpointmode-h">FloatingPointMode.h</a>.</p>


<p>References <a href="#a1b79f1995991b0a757a4d04969c3717f">Input</a> and <a href="#aa1be940c9e7d0c7ed20dfdaf5731b082">Output</a>.</p>

</div>
</div>

### isValid() {#ad26d0c331e4714d8dc77cdd90d1d75d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DenormalMode::isValid ()</td>
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



<p>Definition at line 144 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/floatingpointmode-h">FloatingPointMode.h</a>.</p>


<p>References <a href="#a1b79f1995991b0a757a4d04969c3717f">Input</a>, <a href="#a29b26e3ae30f3f6ec4106ff181282893a72fe23f34a4f8005af6172748a69bc63">Invalid</a> and <a href="#aa1be940c9e7d0c7ed20dfdaf5731b082">Output</a>.</p>

</div>
</div>

### mergeCalleeMode() {#af397461b3c561d29aa674b4a4d3e5965}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenormalMode llvm::DenormalMode::mergeCalleeMode (<a href="/web-llvm/docs/api/structs/llvm/denormalmode">DenormalMode</a> Callee)</td>
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

<p>Get the effective denormal mode if the mode if this caller calls into a function with <span class="doxyComputerOutput">Callee</span>.</p>


<p>This promotes dynamic modes to the mode of the caller.</p>


<p>Definition at line 164 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/floatingpointmode-h">FloatingPointMode.h</a>.</p>


<p>References <a href="#ad96de724aad364e26ee28cdf52fd6943">DenormalMode</a>, <a href="#a29b26e3ae30f3f6ec4106ff181282893ab6083e266013055b6c2ef85b1e47444c">Dynamic</a>, <a href="#a1b79f1995991b0a757a4d04969c3717f">Input</a> and <a href="#aa1be940c9e7d0c7ed20dfdaf5731b082">Output</a>.</p>

</div>
</div>

### outputsAreZero() {#a1cc624e88436331500750f5ffbef65e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DenormalMode::outputsAreZero ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if output denormals should be flushed to 0.</p>

<p>Definition at line 156 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/floatingpointmode-h">FloatingPointMode.h</a>.</p>


<p>References <a href="#aa1be940c9e7d0c7ed20dfdaf5731b082">Output</a>, <a href="#a29b26e3ae30f3f6ec4106ff181282893a7de61db082dcdc6e8d34d1c5fd2e9757">PositiveZero</a> and <a href="#a29b26e3ae30f3f6ec4106ff181282893a40bc80ae1d362a1461703637e946cbd8">PreserveSign</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#aff704e68e1a7f944f4a81ce9ef713ba4">computeKnownFPClass</a>.</p>

</div>
</div>

### print() {#a4b4e3ec6987027fb07517701e7a0a1c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DenormalMode::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
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



<p>Definition at line 173 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/floatingpointmode-h">FloatingPointMode.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4cc99e81f7cfa524bf4bba0f0cc3362">llvm::denormalModeKindName</a>, <a href="#a1b79f1995991b0a757a4d04969c3717f">Input</a> and <a href="#aa1be940c9e7d0c7ed20dfdaf5731b082">Output</a>.</p>


<p>Referenced by <a href="#a5bddda5caa6dff98255b45bf21144c3a">str</a>.</p>

</div>
</div>

### str() {#a5bddda5caa6dff98255b45bf21144c3a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::DenormalMode::str ()</td>
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



<p>Definition at line 175 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/floatingpointmode-h">FloatingPointMode.h</a>.</p>


<p>Reference <a href="#a4b4e3ec6987027fb07517701e7a0a1c2">print</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Input {#a1b79f1995991b0a757a4d04969c3717f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenormalModeKind llvm::DenormalMode::Input = <a href="#a29b26e3ae30f3f6ec4106ff181282893a72fe23f34a4f8005af6172748a69bc63">DenormalModeKind::Invalid</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Denormal treatment kind for floating point instruction inputs in the default floating-point environment.</p>


<p>If this is not <a href="#a29b26e3ae30f3f6ec4106ff181282893ad6fd23eb0b98a2d4551582753191b6da">DenormalModeKind::IEEE</a>, floating-point instructions implicitly treat the input value as 0.</p>


<p>Definition at line 96 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/floatingpointmode-h">FloatingPointMode.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#aff704e68e1a7f944f4a81ce9ef713ba4">computeKnownFPClass</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#a28ddcf99fafe235217356e423dcdd084">anonymous{ConstantFolding.cpp}::constantFoldCanonicalize</a>, <a href="#abf884e500b6e13f208363e16bb8c01bf">DenormalMode</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp/#aa0220f9335f0692044178f634eae8152">denormModeCompatible</a>, <a href="#a898bc0d2b24c32a5d732ae7a225c337c">inputsAreZero</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/targetlowering-cpp/#a939a9cb864b778eb29af330d62308ba4">isFCmpEqualZero</a>, <a href="#a6c4f83a3adadaf5324552427a9c239c3">isSimple</a>, <a href="#ad26d0c331e4714d8dc77cdd90d1d75d4">isValid</a>, <a href="#af397461b3c561d29aa674b4a4d3e5965">mergeCalleeMode</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a58970668183d813014f564e59eafbef6">llvm::AMDGPUTargetLowering::needsDenormHandlingF32</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#a092571cd6865fc5f86e2a594265ff717">needsDenormHandlingF32</a>, <a href="#aa855dc98825c2d5280daa12b8cb34949">operator==</a>, <a href="/web-llvm/docs/api/classes/llvm/gcntargetmachine/#a546e4834a3dc92d96ef8b7598f552a45">llvm::GCNTargetMachine::parseMachineFunctionInfo</a> and <a href="#a4b4e3ec6987027fb07517701e7a0a1c2">print</a>.</p>

</div>
</div>

### Output {#aa1be940c9e7d0c7ed20dfdaf5731b082}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenormalModeKind llvm::DenormalMode::Output = <a href="#a29b26e3ae30f3f6ec4106ff181282893a72fe23f34a4f8005af6172748a69bc63">DenormalModeKind::Invalid</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Denormal flushing mode for floating point instruction results in the default floating point environment.</p>

<p>Definition at line 91 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/floatingpointmode-h">FloatingPointMode.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#aff704e68e1a7f944f4a81ce9ef713ba4">computeKnownFPClass</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#a28ddcf99fafe235217356e423dcdd084">anonymous{ConstantFolding.cpp}::constantFoldCanonicalize</a>, <a href="#abf884e500b6e13f208363e16bb8c01bf">DenormalMode</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp/#aa0220f9335f0692044178f634eae8152">denormModeCompatible</a>, <a href="#a6c4f83a3adadaf5324552427a9c239c3">isSimple</a>, <a href="#ad26d0c331e4714d8dc77cdd90d1d75d4">isValid</a>, <a href="#af397461b3c561d29aa674b4a4d3e5965">mergeCalleeMode</a>, <a href="#aa855dc98825c2d5280daa12b8cb34949">operator==</a>, <a href="#a1cc624e88436331500750f5ffbef65e0">outputsAreZero</a>, <a href="/web-llvm/docs/api/classes/llvm/gcntargetmachine/#a546e4834a3dc92d96ef8b7598f552a45">llvm::GCNTargetMachine::parseMachineFunctionInfo</a>, <a href="#a4b4e3ec6987027fb07517701e7a0a1c2">print</a> and <a href="/web-llvm/docs/api/classes/llvm/nvptxtargetlowering/#a4aa31e8cd18083599550e7203bc275fd">llvm::NVPTXTargetLowering::useF32FTZ</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### getDefault() {#a5593567c266618b9001731accef54da8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">constexpr DenormalMode llvm::DenormalMode::getDefault ()</td>
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

<p>Return the assumed default mode for a function without denormal-fp-math.</p>

<p>Definition at line 110 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/floatingpointmode-h">FloatingPointMode.h</a>.</p>


<p>References <a href="#ad96de724aad364e26ee28cdf52fd6943">DenormalMode</a> and <a href="#afc06bc91a5873ec7efe616b733f2c5c8">getIEEE</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aadenormalfpmathfunction/#a3930112816f97f9c7a92b22d4e332107">anonymous{AttributorAttributes.cpp}::AADenormalFPMathFunction::manifest</a>.</p>

</div>
</div>

### getDynamic() {#af51395b84b8db9baa750e7b9210eebb2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">constexpr DenormalMode llvm::DenormalMode::getDynamic ()</td>
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



<p>Definition at line 128 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/floatingpointmode-h">FloatingPointMode.h</a>.</p>


<p>References <a href="#ad96de724aad364e26ee28cdf52fd6943">DenormalMode</a> and <a href="#a29b26e3ae30f3f6ec4106ff181282893ab6083e266013055b6c2ef85b1e47444c">Dynamic</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp/#aa0220f9335f0692044178f634eae8152">denormModeCompatible</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/constantfolding-cpp/#af3c8f5caa60e75e0b9aaad6e11a88722">getInstrDenormalMode</a>.</p>

</div>
</div>

### getIEEE() {#afc06bc91a5873ec7efe616b733f2c5c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">constexpr DenormalMode llvm::DenormalMode::getIEEE ()</td>
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



<p>Definition at line 114 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/floatingpointmode-h">FloatingPointMode.h</a>.</p>


<p>References <a href="#ad96de724aad364e26ee28cdf52fd6943">DenormalMode</a> and <a href="#a29b26e3ae30f3f6ec4106ff181282893ad6fd23eb0b98a2d4551582753191b6da">IEEE</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#aff704e68e1a7f944f4a81ce9ef713ba4">computeKnownFPClass</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#a28ddcf99fafe235217356e423dcdd084">anonymous{ConstantFolding.cpp}::constantFoldCanonicalize</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#a48239fe2dd570dc10b58a6a89ce6dd72">foldFCmpFSubIntoFCmp</a>, <a href="#a5593567c266618b9001731accef54da8">getDefault</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#aa7f714d0bdade75514375f4730cadf0e">llvm::SITargetLowering::isCanonicalized</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a2f6b98def08062ba093a93bd2ca06ffe">llvm::SITargetLowering::isCanonicalized</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a464ac3e6051fb78eb3ee985975d17cb2">llvm::AMDGPULegalizerInfo::legalizeFDIV32</a> and <a href="/web-llvm/docs/api/structs/llvm/knownfpclass/#a832be183f243ae315e8bdd00b9d9acd0">llvm::KnownFPClass::propagateDenormal</a>.</p>

</div>
</div>

### getInvalid() {#a7326cc28954855133bd6efba8aa9724a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">constexpr DenormalMode llvm::DenormalMode::getInvalid ()</td>
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



<p>Definition at line 105 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/floatingpointmode-h">FloatingPointMode.h</a>.</p>


<p>References <a href="#ad96de724aad364e26ee28cdf52fd6943">DenormalMode</a> and <a href="#a29b26e3ae30f3f6ec4106ff181282893a72fe23f34a4f8005af6172748a69bc63">Invalid</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp/#ab7b23abced1fe9fc0068f73a3cb35c89">checkDenormMode</a> and <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aadenormalfpmathfunction/#ab9ac902089ba2b707e62211f6e6fb297">anonymous{AttributorAttributes.cpp}::AADenormalFPMathFunction::initialize</a>.</p>

</div>
</div>

### getPositiveZero() {#a3c136ee901a0b48c5bf4be4b29d58b58}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">constexpr DenormalMode llvm::DenormalMode::getPositiveZero ()</td>
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



<p>Definition at line 123 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/floatingpointmode-h">FloatingPointMode.h</a>.</p>


<p>References <a href="#ad96de724aad364e26ee28cdf52fd6943">DenormalMode</a> and <a href="#a29b26e3ae30f3f6ec4106ff181282893a7de61db082dcdc6e8d34d1c5fd2e9757">PositiveZero</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/knownfpclass/#a832be183f243ae315e8bdd00b9d9acd0">llvm::KnownFPClass::propagateDenormal</a>.</p>

</div>
</div>

### getPreserveSign() {#a8b25a485fab5c4ade966d2ad73bc2ccf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">constexpr DenormalMode llvm::DenormalMode::getPreserveSign ()</td>
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



<p>Definition at line 118 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/floatingpointmode-h">FloatingPointMode.h</a>.</p>


<p>References <a href="#ad96de724aad364e26ee28cdf52fd6943">DenormalMode</a> and <a href="#a29b26e3ae30f3f6ec4106ff181282893a40bc80ae1d362a1461703637e946cbd8">PreserveSign</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#aef9fe930d99fc1baf2a6ae99a59df09e">atomicIgnoresDenormalModeOrFPModeIsFTZ</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#a250dc58b73d94abe917ae8a5b2c45e1b">denormalModeIsFlushAllF32</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#a09757ceb0f121bda7fac53a54f1fab85">denormalModeIsFlushAllF64F16</a>, <a href="/web-llvm/docs/api/structs/llvm/simoderegisterdefaults/#a98055d81c972ca478d57d2b1a871ecd9">llvm::SIModeRegisterDefaults::fpDenormModeDPValue</a>, <a href="/web-llvm/docs/api/structs/llvm/simoderegisterdefaults/#a6590b6137a9fe659ad1ba3b2387b4cbd">llvm::SIModeRegisterDefaults::fpDenormModeSPValue</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnttiimpl/#a19dce49c9c18898b9f4ca348fa3c89ec">llvm::GCNTTIImpl::GCNTTIImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a049b3701010cdb5ffd40bf0f7a0eb0a8">llvm::SITargetLowering::isFMAFasterThanFMulAndFAdd</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a4774d239d20e55380840e775aed66efc">llvm::AMDGPULegalizerInfo::legalizeFMad</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a6f30e11353716cf175b1fb59b11cb6f4">llvm::AMDGPUTargetLowering::LowerDIVREM24</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#aec76b73c15365e949f7322e371e6471b">llvm::AMDGPUTargetLowering::LowerUDIVREM64</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/floatingpointmode-h">FloatingPointMode.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>

---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-attributorattributes-cpp-/aavaluesimplifyargument
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `AAValueSimplifyArgument` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct anonymous{AttributorAttributes.cpp}::AAValueSimplifyArgument { ... }
</div>

## Base struct

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aavaluesimplifyimpl">AAValueSimplifyImpl</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7752e10b2fd7e57210fe52d70800c121">AAValueSimplifyArgument</a> (const IRPosition &amp;IRP, Attributor &amp;A)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1f3d1dc8fc604a49c072019d874dd237">initialize</a> (Attributor &amp;A) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Initialize the state with the information in the Attributor <span class="doxyComputerOutput">A</span>. <a href="#a1f3d1dc8fc604a49c072019d874dd237">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#acd850975ae5042cacb64a9d0ea4715f3">ChangeStatus</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a04db9be64fd2281358f89ee3bebca79e">updateImpl</a> (Attributor &amp;A) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>See AbstractAttribute::updateImpl(...). <a href="#a04db9be64fd2281358f89ee3bebca79e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae67ab070a47732af338e399499785d39">trackStatistics</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>See <a href="/web-llvm/docs/api/structs/llvm/abstractattribute/#add85e4d78cefc67429904d7492aff9a4">AbstractAttribute::trackStatistics()</a> <a href="#ae67ab070a47732af338e399499785d39">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 6347 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp">AttributorAttributes.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### AAValueSimplifyArgument() {#a7752e10b2fd7e57210fe52d70800c121}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{AttributorAttributes.cpp}::AAValueSimplifyArgument::AAValueSimplifyArgument (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/irposition">IRPosition</a> &amp; IRP, <a href="/web-llvm/docs/api/structs/llvm/attributor">Attributor</a> &amp; A)</td>
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



<p>Definition at line 6348 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp">AttributorAttributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aavaluesimplifyimpl/#ac8bc88899bd4ec5c222c0195c108d41f">anonymous{AttributorAttributes.cpp}::AAValueSimplifyImpl::AAValueSimplifyImpl</a> and <a href="/web-llvm/docs/api/structs/llvm/aavaluesimplify/#a05f3b3169e1f6a561b0c38f0150b3867">llvm::AAValueSimplify::Attributor</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### initialize() {#a1f3d1dc8fc604a49c072019d874dd237}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AttributorAttributes.cpp}::AAValueSimplifyArgument::initialize (<a href="/web-llvm/docs/api/structs/llvm/attributor">Attributor</a> &amp; A)</td>
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

<p>Initialize the state with the information in the Attributor <span class="doxyComputerOutput">A</span>.</p>


<p>This function is called by the Attributor once all abstract attributes have been identified. It can and shall be used for task like:</p>


<ul class="doxyList ">
<li>identify existing knowledge in the IR and use it for the "known state"</li>
<li>perform any work that is not going to change over time, e.g., determine a subset of the IR, or attributes in-flight, that have to be looked at in the <span class="doxyComputerOutput">updateImpl</span> method.</li>
</ul>

<p>Definition at line 6351 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp">AttributorAttributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/structs/llvm/aavaluesimplify/#a05f3b3169e1f6a561b0c38f0150b3867">llvm::AAValueSimplify::Attributor</a>, <a href="/web-llvm/docs/api/structs/llvm/abstractattribute/#af5135f33d24ea71544db77941dab1e38">llvm::AbstractAttribute::getIRPosition</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aavaluesimplifyimpl/#ad277bd35b295f10501e8ead87d705599">anonymous{AttributorAttributes.cpp}::AAValueSimplifyImpl::indicatePessimisticFixpoint</a> and <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aavaluesimplifyimpl/#a5aaf0b4e889521266e9e87ec9a0511ce">anonymous{AttributorAttributes.cpp}::AAValueSimplifyImpl::initialize</a>.</p>

</div>
</div>

### trackStatistics() {#ae67ab070a47732af338e399499785d39}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AttributorAttributes.cpp}::AAValueSimplifyArgument::trackStatistics ()</td>
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

<p>See <a href="/web-llvm/docs/api/structs/llvm/abstractattribute/#add85e4d78cefc67429904d7492aff9a4">AbstractAttribute::trackStatistics()</a></p>

<p>Definition at line 6420 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp">AttributorAttributes.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp/#a791b84a34492c0706a2bc96efc9d2102">STATS_DECLTRACK_ARG_ATTR</a>.</p>

</div>
</div>

### updateImpl() {#a04db9be64fd2281358f89ee3bebca79e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ChangeStatus anonymous{AttributorAttributes.cpp}::AAValueSimplifyArgument::updateImpl (<a href="/web-llvm/docs/api/structs/llvm/attributor">Attributor</a> &amp; A)</td>
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

<p>See AbstractAttribute::updateImpl(...).</p>

<p>Definition at line 6361 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp">AttributorAttributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aavaluesimplifyimpl/#aa5c043f1337b0357c7bd606d01cfad9d">anonymous{AttributorAttributes.cpp}::AAValueSimplifyImpl::askSimplifiedValueForOtherAAs</a>, <a href="/web-llvm/docs/api/structs/llvm/aavaluesimplify/#a05f3b3169e1f6a561b0c38f0150b3867">llvm::AAValueSimplify::Attributor</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/standardinstrumentations-cpp/#a6f1bbcae7288f05872dcfe811d0388baa9060587edeb01a63e3d3edc959678d1e">Before</a>, <a href="/web-llvm/docs/api/structs/llvm/irposition/#a4c17a71e75898bbc42578a1c0b94c6b6">llvm::IRPosition::callsite_argument</a>, <a href="/web-llvm/docs/api/structs/llvm/irposition/#a265735d2c2edc0a1a03611e7aadd24cd">llvm::IRPosition::getAssociatedArgument</a>, <a href="/web-llvm/docs/api/structs/llvm/irposition/#a8e5f6784c446af664c5c0f6ab3c9fa26">llvm::IRPosition::getCallBaseContext</a>, <a href="/web-llvm/docs/api/structs/llvm/irposition/#ac74aa0fe9252fce4caabf80617085afa">llvm::IRPosition::getCallSiteArgNo</a>, <a href="/web-llvm/docs/api/structs/llvm/abstractattribute/#af5135f33d24ea71544db77941dab1e38">llvm::AbstractAttribute::getIRPosition</a>, <a href="/web-llvm/docs/api/classes/llvm/argument/#a862c73765000251be786c801260ba7c1">llvm::Argument::getParent</a>, <a href="/web-llvm/docs/api/structs/llvm/irposition/#aea16db681aa18f4eded0015e284fdfe5">llvm::IRPosition::getPositionKind</a>, <a href="/web-llvm/docs/api/classes/llvm/argument/#a736135f761e0d468c731ddc4327607e7">llvm::Argument::hasByValAttr</a>, <a href="/web-llvm/docs/api/structs/llvm/irposition/#a1e87ff0b4410e061ceac8ca9fc7e46b1">llvm::IRPosition::hasCallBaseContext</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aavaluesimplifyimpl/#ad277bd35b295f10501e8ead87d705599">anonymous{AttributorAttributes.cpp}::AAValueSimplifyImpl::indicatePessimisticFixpoint</a>, <a href="/web-llvm/docs/api/structs/llvm/irposition/#a53f576f97e0dfa8314afb16bd74a76d0afd1465681c30be50be67dcf938d73f5f">llvm::IRPosition::IRP_INVALID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aa/#a17d95a36815f9b2bb3441fd61ee328be">llvm::AA::isAssumedReadOnly</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aa/#a559168f78e20f2d3d0e1763ee6e751ef">llvm::AA::isDynamicallyUnique</a>, <a href="/web-llvm/docs/api/structs/llvm/valuesimplifystatetype/#aabe3cb56f76e6a223406ba8fd571f5f4">llvm::ValueSimplifyStateType::SimplifiedAssociatedValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/disassembler/aarch64disassembler-cpp/#abdb086b34295fb7aa09493c62d798465">Success</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acd850975ae5042cacb64a9d0ea4715f3a46335765005ff44b1fe1e38e5d2ddfcc">llvm::UNCHANGED</a> and <a href="/web-llvm/docs/api/structs/llvm/valuesimplifystatetype/#a3b30794202b9b3042b5567a270ea8735">llvm::ValueSimplifyStateType::unionAssumed</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp">AttributorAttributes.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>

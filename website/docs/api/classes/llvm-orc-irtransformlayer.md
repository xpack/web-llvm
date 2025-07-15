---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/orc/irtransformlayer
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `IRTransformLayer` Class Reference

<p>A layer that applies a transform to emitted modules. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::orc::IRTransformLayer { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/irtransformlayer-h">llvm/ExecutionEngine/Orc/IRTransformLayer.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/irlayer">IRLayer</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Interface for layers that accept LLVM IR. <a href="/web-llvm/docs/api/classes/llvm/orc/irlayer/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6bc9029b4c962d8705f85055d83cb56f">TransformFunction</a> = <a href="/web-llvm/docs/api/classes/llvm/unique-function">unique_function</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/threadsafemodule">ThreadSafeModule</a> &gt;( <a href="/web-llvm/docs/api/classes/llvm/orc/threadsafemodule">ThreadSafeModule</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/materializationresponsibility">MaterializationResponsibility</a> &amp;R)&gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad8fed5aecfe2723e59e80ecf65cbab2b">IRTransformLayer</a> (ExecutionSession &amp;ES, IRLayer &amp;BaseLayer, TransformFunction Transform=identityTransform)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4e213cd335afa376cb8ab5ef7c9b6358">setTransform</a> (TransformFunction Transform)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f4ae51591df573638504e97f54a5321">emit</a> (std::unique_ptr&lt; MaterializationResponsibility &gt; R, ThreadSafeModule TSM) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit should materialize the given IR. <a href="#a6f4ae51591df573638504e97f54a5321">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/irlayer">IRLayer</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a714c0a6a6b4ad246176665e677f55d75">BaseLayer</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a6bc9029b4c962d8705f85055d83cb56f">TransformFunction</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af9a06cdaa79bb163699c1b34dfd26bea">Transform</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/orc/threadsafemodule">ThreadSafeModule</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeafac83f03016539dfcc90708cf52747">identityTransform</a> (ThreadSafeModule TSM, MaterializationResponsibility &amp;R)</td>
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

<p>A layer that applies a transform to emitted modules.</p>


<p>The transform function is responsible for locking the <a href="/web-llvm/docs/api/classes/llvm/orc/threadsafecontext">ThreadSafeContext</a> before operating on the module.</p>


<p>Definition at line 27 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/irtransformlayer-h">IRTransformLayer.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### TransformFunction {#a6bc9029b4c962d8705f85055d83cb56f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::orc::IRTransformLayer::TransformFunction =  unique_function&lt;Expected&lt;ThreadSafeModule&gt;(
      ThreadSafeModule, MaterializationResponsibility &amp;R)&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 29 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/irtransformlayer-h">IRTransformLayer.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### IRTransformLayer() {#ad8fed5aecfe2723e59e80ecf65cbab2b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::orc::IRTransformLayer::IRTransformLayer (<a href="/web-llvm/docs/api/classes/llvm/orc/executionsession">ExecutionSession</a> &amp; ES, <a href="/web-llvm/docs/api/classes/llvm/orc/irlayer">IRLayer</a> &amp; BaseLayer, <a href="#a6bc9029b4c962d8705f85055d83cb56f">TransformFunction</a> Transform=<a href="#aeafac83f03016539dfcc90708cf52747">identityTransform</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 32 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/irtransformlayer-h">IRTransformLayer.h</a>, definition at line 14 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/irtransformlayer-cpp">IRTransformLayer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/orc/irlayer/#ae3cfe72cdaca15dbe4c360d8bcdb5207">llvm::orc::IRLayer::getManglingOptions</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/irlayer/#a1141609d9c7e4bdd205bc09698ff51b3">llvm::orc::IRLayer::IRLayer</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### emit() {#a6f4ae51591df573638504e97f54a5321}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::orc::IRTransformLayer::emit (std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/materializationresponsibility">MaterializationResponsibility</a> &gt; R, <a href="/web-llvm/docs/api/classes/llvm/orc/threadsafemodule">ThreadSafeModule</a> TSM)</td>
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

<p>Emit should materialize the given IR.</p>

<p>Declaration at line 39 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/irtransformlayer-h">IRTransformLayer.h</a>, definition at line 19 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/irtransformlayer-cpp">IRTransformLayer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/irlayer/#a88dfbca45a6353ce7c643414c0d945cf">llvm::orc::IRLayer::getExecutionSession</a> and <a href="/web-llvm/docs/api/classes/llvm/orc/executionsession/#a1c47ed6ddfb6770f1a432af1c9acdc44">llvm::orc::ExecutionSession::reportError</a>.</p>

</div>
</div>

### setTransform() {#a4e213cd335afa376cb8ab5ef7c9b6358}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::orc::IRTransformLayer::setTransform (<a href="#a6bc9029b4c962d8705f85055d83cb56f">TransformFunction</a> Transform)</td>
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



<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/irtransformlayer-h">IRTransformLayer.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### BaseLayer {#a714c0a6a6b4ad246176665e677f55d75}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IRLayer&amp; llvm::orc::IRTransformLayer::BaseLayer</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/irtransformlayer-h">IRTransformLayer.h</a>.</p>

</div>
</div>

### Transform {#af9a06cdaa79bb163699c1b34dfd26bea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TransformFunction llvm::orc::IRTransformLayer::Transform</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/irtransformlayer-h">IRTransformLayer.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### identityTransform() {#aeafac83f03016539dfcc90708cf52747}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ThreadSafeModule llvm::orc::IRTransformLayer::identityTransform (<a href="/web-llvm/docs/api/classes/llvm/orc/threadsafemodule">ThreadSafeModule</a> TSM, <a href="/web-llvm/docs/api/classes/llvm/orc/materializationresponsibility">MaterializationResponsibility</a> &amp; R)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/irtransformlayer-h">IRTransformLayer.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/irtransformlayer-h">IRTransformLayer.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/irtransformlayer-cpp">IRTransformLayer.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>

---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/orc/resourcetracker
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `ResourceTracker` Class Reference

<p>API to remove / transfer ownership of JIT resources. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::orc::ResourceTracker { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">llvm/ExecutionEngine/Orc/Core.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/threadsaferefcountedbase">ThreadSafeRefCountedBase&lt;Derived&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A thread-safe version of <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/refcountedbase">RefCountedBase</a></span>. <a href="/web-llvm/docs/api/classes/llvm/threadsaferefcountedbase/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae073d99ba71b23b530556f075655fc61">ExecutionSession</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a235f764fe0f700836f89667ef5a0033b">JITDylib</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c1590c98c2c00498468ad2f4bf8a86f">MaterializationResponsibility</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9aec83f598ff6a46ff717dce310b115c">ResourceTracker</a> (const ResourceTracker &amp;)=delete</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac23de49538f24b365eb452dcfc0971fe">ResourceTracker</a> (ResourceTracker &amp;&amp;)=delete</td>
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

## Private Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a81eab970f1e16e7d74fe28c597d21b63">ResourceTracker</a> (JITDylibSP JD)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7941320edde60605d48daba8e0980564">~ResourceTracker</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/resourcetracker">ResourceTracker</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a360172d995677a1670a2084a4466881b">operator=</a> (const ResourceTracker &amp;)=delete</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/resourcetracker">ResourceTracker</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7913899b798a05f623d92fc51df28d6f">operator=</a> (ResourceTracker &amp;&amp;)=delete</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a19b2c478815e45a7c78615959f5450a2">getJITDylib</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> targeted by this tracker. <a href="#a19b2c478815e45a7c78615959f5450a2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Func&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac946e909dda8f139167b7d28956f1e51">withResourceKeyDo</a> (Func &amp;&amp;F)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Runs the given callback under the session lock, passing in the associated <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a48eb648e96394270c69273c29bfad24e">ResourceKey</a>. <a href="#ac946e909dda8f139167b7d28956f1e51">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af9d739f7df392fbb3de4e22133a22976">remove</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remove all resources associated with this key. <a href="#af9d739f7df392fbb3de4e22133a22976">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6deaaff3ebd6ae3df2545cd06c0da0a4">transferTo</a> (ResourceTracker &amp;DstRT)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Transfer all resources associated with this key to the given tracker, which must target the same <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> as this one. <a href="#a6deaaff3ebd6ae3df2545cd06c0da0a4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa83eb91c330747ce754ef68027741d6c">isDefunct</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this tracker has become defunct. <a href="#aa83eb91c330747ce754ef68027741d6c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/orc/#a48eb648e96394270c69273c29bfad24e">ResourceKey</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4430532ccc500bed977b3f3ee9faa0aa">getKeyUnsafe</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the key associated with this tracker. <a href="#a4430532ccc500bed977b3f3ee9faa0aa">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1c0c04e33992361c79df121b18ce9251">makeDefunct</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::atomic_uintptr_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3acd447fdb05896512298615917d35a0">JDAndFlag</a></td>
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

<p>API to remove / transfer ownership of JIT resources.</p>

<p>Definition at line 77 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>.</p>


<div class="doxySectionDef">

## Friends

### ExecutionSession {#ae073d99ba71b23b530556f075655fc61}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/orc/executionsession">ExecutionSession</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 79 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>.</p>


<p>Reference <a href="#ae073d99ba71b23b530556f075655fc61">ExecutionSession</a>.</p>


<p>Referenced by <a href="#ae073d99ba71b23b530556f075655fc61">ExecutionSession</a>.</p>

</div>
</div>

### JITDylib {#a235f764fe0f700836f89667ef5a0033b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 80 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>.</p>


<p>Reference <a href="#a235f764fe0f700836f89667ef5a0033b">JITDylib</a>.</p>


<p>Referenced by <a href="#a19b2c478815e45a7c78615959f5450a2">getJITDylib</a> and <a href="#a235f764fe0f700836f89667ef5a0033b">JITDylib</a>.</p>

</div>
</div>

### MaterializationResponsibility {#a9c1590c98c2c00498468ad2f4bf8a86f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/orc/materializationresponsibility">MaterializationResponsibility</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 81 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>.</p>


<p>Reference <a href="#a9c1590c98c2c00498468ad2f4bf8a86f">MaterializationResponsibility</a>.</p>


<p>Referenced by <a href="#a9c1590c98c2c00498468ad2f4bf8a86f">MaterializationResponsibility</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### ResourceTracker() {#a9aec83f598ff6a46ff717dce310b115c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::orc::ResourceTracker::ResourceTracker (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/orc/resourcetracker">ResourceTracker</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 84 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>.</p>


<p>Reference <a href="#a9aec83f598ff6a46ff717dce310b115c">ResourceTracker</a>.</p>


<p>Referenced by <a href="#a360172d995677a1670a2084a4466881b">operator=</a>, <a href="#a7913899b798a05f623d92fc51df28d6f">operator=</a>, <a href="#a9aec83f598ff6a46ff717dce310b115c">ResourceTracker</a>, <a href="#ac23de49538f24b365eb452dcfc0971fe">ResourceTracker</a> and <a href="#a6deaaff3ebd6ae3df2545cd06c0da0a4">transferTo</a>.</p>

</div>
</div>

### ResourceTracker() {#ac23de49538f24b365eb452dcfc0971fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::orc::ResourceTracker::ResourceTracker (<a href="/web-llvm/docs/api/classes/llvm/orc/resourcetracker">ResourceTracker</a> &amp;&amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 86 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>.</p>


<p>Reference <a href="#a9aec83f598ff6a46ff717dce310b115c">ResourceTracker</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Constructors

### ResourceTracker() {#a81eab970f1e16e7d74fe28c597d21b63}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::orc::ResourceTracker::ResourceTracker (<a href="/web-llvm/docs/api/namespaces/llvm/orc/#a1baadbec01aced37be13a1b86c76397e">JITDylibSP</a> JD)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 117 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>, definition at line 43 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/core-cpp">Core.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~ResourceTracker() {#a7941320edde60605d48daba8e0980564}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::orc::ResourceTracker::~ResourceTracker ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 89 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>, definition at line 50 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/core-cpp">Core.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib/#a67fc014ddc6f09ff528b686fd7b1de20">llvm::orc::JITDylib::getExecutionSession</a>, <a href="#a19b2c478815e45a7c78615959f5450a2">getJITDylib</a> and <a href="/web-llvm/docs/api/classes/llvm/threadsaferefcountedbase/#aace72d8ed6b135fd20d71cad7727316b">llvm::ThreadSafeRefCountedBase&lt; Derived &gt;::Release</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#a360172d995677a1670a2084a4466881b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ResourceTracker &amp; llvm::orc::ResourceTracker::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/orc/resourcetracker">ResourceTracker</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 85 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>.</p>


<p>Reference <a href="#a9aec83f598ff6a46ff717dce310b115c">ResourceTracker</a>.</p>

</div>
</div>

### operator=() {#a7913899b798a05f623d92fc51df28d6f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ResourceTracker &amp; llvm::orc::ResourceTracker::operator= (<a href="/web-llvm/docs/api/classes/llvm/orc/resourcetracker">ResourceTracker</a> &amp;&amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 87 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>.</p>


<p>Reference <a href="#a9aec83f598ff6a46ff717dce310b115c">ResourceTracker</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getJITDylib() {#a19b2c478815e45a7c78615959f5450a2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">JITDylib &amp; llvm::orc::ResourceTracker::getJITDylib ()</td>
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

<p>Return the <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> targeted by this tracker.</p>

<p>Definition at line 92 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>.</p>


<p>Reference <a href="#a235f764fe0f700836f89667ef5a0033b">JITDylib</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/orc/redirectablesymbolmanager/#aa3bba6d1a7f84b8ead4d44a6788ee929">llvm::orc::RedirectableSymbolManager::createRedirectableSymbols</a>, <a href="/web-llvm/docs/api/classes/anonymous-lljit-cpp-/genericllvmirplatformsupport/#a7a6c3b4432af35ad1b0c9843105f5e4d">anonymous{LLJIT.cpp}::GenericLLVMIRPlatformSupport::notifyAdding</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/coffplatform/#a6ceb8793145f063bcb5e204c1251649e">llvm::orc::COFFPlatform::notifyAdding</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/elfnixplatform/#a454ad1d1eb28a3dfc9ed6383417df7bb">llvm::orc::ELFNixPlatform::notifyAdding</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/machoplatform/#a9933be5a0082912958e7328de0ca90e1">llvm::orc::MachOPlatform::notifyAdding</a>, <a href="#af9d739f7df392fbb3de4e22133a22976">remove</a>, <a href="#a6deaaff3ebd6ae3df2545cd06c0da0a4">transferTo</a>, <a href="#ac946e909dda8f139167b7d28956f1e51">withResourceKeyDo</a> and <a href="#a7941320edde60605d48daba8e0980564">~ResourceTracker</a>.</p>

</div>
</div>

### getKeyUnsafe() {#a4430532ccc500bed977b3f3ee9faa0aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ResourceKey llvm::orc::ResourceTracker::getKeyUnsafe ()</td>
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

<p>Returns the key associated with this tracker.</p>


<p>This method should not be used except for debug logging: there is no guarantee that the returned value will remain valid.</p>


<p>Definition at line 114 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>.</p>


<p>Referenced by <a href="#ac946e909dda8f139167b7d28956f1e51">withResourceKeyDo</a>.</p>

</div>
</div>

### isDefunct() {#aa83eb91c330747ce754ef68027741d6c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::orc::ResourceTracker::isDefunct ()</td>
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

<p>Return true if this tracker has become defunct.</p>

<p>Definition at line 109 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>.</p>


<p>Referenced by <a href="#ac946e909dda8f139167b7d28956f1e51">withResourceKeyDo</a>.</p>

</div>
</div>

### remove() {#af9d739f7df392fbb3de4e22133a22976}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::orc::ResourceTracker::remove ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Remove all resources associated with this key.</p>

<p>Declaration at line 102 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>, definition at line 55 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/core-cpp">Core.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib/#a67fc014ddc6f09ff528b686fd7b1de20">llvm::orc::JITDylib::getExecutionSession</a> and <a href="#a19b2c478815e45a7c78615959f5450a2">getJITDylib</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga32e62df5dab033d0866ab619c1352a49">LLVMOrcResourceTrackerRemove</a>.</p>

</div>
</div>

### transferTo() {#a6deaaff3ebd6ae3df2545cd06c0da0a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::orc::ResourceTracker::transferTo (<a href="/web-llvm/docs/api/classes/llvm/orc/resourcetracker">ResourceTracker</a> &amp; DstRT)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Transfer all resources associated with this key to the given tracker, which must target the same <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> as this one.</p>

<p>Declaration at line 106 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>, definition at line 59 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/core-cpp">Core.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib/#a67fc014ddc6f09ff528b686fd7b1de20">llvm::orc::JITDylib::getExecutionSession</a>, <a href="#a19b2c478815e45a7c78615959f5450a2">getJITDylib</a> and <a href="#a9aec83f598ff6a46ff717dce310b115c">ResourceTracker</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#gafec934cefd3892257d5f677605c28835">LLVMOrcResourceTrackerTransferTo</a>.</p>

</div>
</div>

### withResourceKeyDo() {#ac946e909dda8f139167b7d28956f1e51}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Func&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::orc::ResourceTracker::withResourceKeyDo (Func &amp;&amp; F)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Runs the given callback under the session lock, passing in the associated <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a48eb648e96394270c69273c29bfad24e">ResourceKey</a>.</p>


<p>This is the safe way to associate resources with trackers.</p>


<p>Definition at line 99 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib/#a67fc014ddc6f09ff528b686fd7b1de20">llvm::orc::JITDylib::getExecutionSession</a>, <a href="#a19b2c478815e45a7c78615959f5450a2">getJITDylib</a>, <a href="#a4430532ccc500bed977b3f3ee9faa0aa">getKeyUnsafe</a>, <a href="#aa83eb91c330747ce754ef68027741d6c">isDefunct</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/executionsession/#ab9ce518e73ce35d17cd88e873776d51e">llvm::orc::ExecutionSession::runSessionLocked</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### makeDefunct() {#a1c0c04e33992361c79df121b18ce9251}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::orc::ResourceTracker::makeDefunct ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 119 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>, definition at line 63 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/core-cpp">Core.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### JDAndFlag {#a3acd447fdb05896512298615917d35a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::atomic_uintptr_t llvm::orc::ResourceTracker::JDAndFlag</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 121 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/core-cpp">Core.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>

---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/orc/jitdylib
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `JITDylib` Class Reference

<p>Represents a JIT'd dynamic library. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::orc::JITDylib { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">llvm/ExecutionEngine/Orc/Core.h</a>"
</div>

## Base classes

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

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/jitlink/jitlinkdylib">JITLinkDylib</a></td>
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

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7512bf66174bcaf8f1243c6723df41e6">AsynchronousSymbolQuerySet</a> = std::set&lt; std::shared_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/asynchronoussymbolquery">AsynchronousSymbolQuery</a> &gt; &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa5b49553cfdec08b246bffc93ba72d89">AsynchronousSymbolQueryList</a> = std::vector&lt; std::shared_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/asynchronoussymbolquery">AsynchronousSymbolQuery</a> &gt; &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adcf6773ecae847ed298389c66c517ede">UnmaterializedInfosMap</a> = <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/symbolstringptr">SymbolStringPtr</a>, std::shared_ptr&lt; UnmaterializedInfo &gt; &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb9a65e5530f28a59977bc26ed257931">UnmaterializedInfosList</a> = std::vector&lt; std::shared_ptr&lt; UnmaterializedInfo &gt; &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9aab378a2141d50023300600fc003655">MaterializingInfosMap</a> = <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/symbolstringptr">SymbolStringPtr</a>, MaterializingInfo &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac4b235afb25b635699713f289aa2f749">SymbolTable</a> = <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/symbolstringptr">SymbolStringPtr</a>, SymbolTableEntry &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">anonymous enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"> { <a href="#a1a287843affb55dafd3ef8163002467c">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a595f3d213faee48086cd1c852718faff">AsynchronousSymbolQuery</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9def841f7cd75057805532dab4d0f459">Platform</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae9b82bdb8efb96cf82c7f3c31168c5e1">JITDylib</a> (const JITDylib &amp;)=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeed53fc13e88ef4fda4cc7ad22ef50a7">JITDylib</a> (JITDylib &amp;&amp;)=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a693e6868185790ed2210a4f64805595e">JITDylib</a> (ExecutionSession &amp;ES, std::string Name)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a17da04bffbd3264e771a59217f8e65a7">~JITDylib</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec5c137bfb82d29d40e2d73fc3321f07">operator=</a> (const JITDylib &amp;)=delete</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4bf27af7e11c3af9f8380591386f223c">operator=</a> (JITDylib &amp;&amp;)=delete</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/executionsession">ExecutionSession</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67fc014ddc6f09ff528b686fd7b1de20">getExecutionSession</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get a reference to the <a href="/web-llvm/docs/api/classes/llvm/orc/executionsession">ExecutionSession</a> for this <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a>. <a href="#a67fc014ddc6f09ff528b686fd7b1de20">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a574566a131a23ad62ff846ac8a7901f4">dump</a> (raw_ostream &amp;OS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Dump current <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> state to OS. <a href="#a574566a131a23ad62ff846ac8a7901f4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a25e558db9c4a9a9b6cbd5dc09a2b929b">clear</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Calls remove on all trackers currently associated with this <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a>. <a href="#a25e558db9c4a9a9b6cbd5dc09a2b929b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/orc/#a25b487d71ccd2a8f38131e2b21c5d612">ResourceTrackerSP</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae3cfc9a4e792646e7108ebae425804f0">getDefaultResourceTracker</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the default resource tracker for this <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a>. <a href="#ae3cfc9a4e792646e7108ebae425804f0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/orc/#a25b487d71ccd2a8f38131e2b21c5d612">ResourceTrackerSP</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8101c255dab4a5e953ba45c56cb091f7">createResourceTracker</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a resource tracker for this <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a>. <a href="#a8101c255dab4a5e953ba45c56cb091f7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename GeneratorT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">GeneratorT &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ae89dfebe97fc65907c1b9194aafe1ade">addGenerator</a> (std::unique_ptr&lt; GeneratorT &gt; DefGenerator)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Adds a definition generator to this <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> and returns a referenece to it. <a href="#ae89dfebe97fc65907c1b9194aafe1ade">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af1c180ec9ecf2c56f8e7a834aa161c8c">removeGenerator</a> (DefinitionGenerator &amp;G)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remove a definition generator from this <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a>. <a href="#af1c180ec9ecf2c56f8e7a834aa161c8c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab5c917be01faae33e9df9295e1dffdd7">setLinkOrder</a> (JITDylibSearchOrder NewSearchOrder, bool LinkAgainstThisJITDylibFirst=true)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the link order to be used when fixing up definitions in <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a>. <a href="#ab5c917be01faae33e9df9295e1dffdd7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6dfad3bd64c32a0f80f488fee7f637de">addToLinkOrder</a> (const JITDylibSearchOrder &amp;NewLinks)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Append the given <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a1a2b573da544cf233d62075a16146245">JITDylibSearchOrder</a> to the link order for this <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> (discarding any elements already present in this <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a>'s link order). <a href="#a6dfad3bd64c32a0f80f488fee7f637de">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acffa1bb37b73209e487e6ffc5d57c560">addToLinkOrder</a> (JITDylib &amp;JD, JITDylibLookupFlags JDLookupFlags=JITDylibLookupFlags::MatchExportedSymbolsOnly)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add the given <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> to the link order for definitions in this <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a>. <a href="#acffa1bb37b73209e487e6ffc5d57c560">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5dd08e5f273c8c5b6f25657b4a585d87">replaceInLinkOrder</a> (JITDylib &amp;OldJD, JITDylib &amp;NewJD, JITDylibLookupFlags JDLookupFlags=JITDylibLookupFlags::MatchExportedSymbolsOnly)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Replace OldJD with NewJD in the link order if OldJD is present. <a href="#a5dd08e5f273c8c5b6f25657b4a585d87">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa9eba60477c881a6e917ad183229ccb3">removeFromLinkOrder</a> (JITDylib &amp;JD)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remove the given <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> from the link order for this <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> if it is present. <a href="#aa9eba60477c881a6e917ad183229ccb3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Func&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a82001e6ef07752d7eb0843a693f90bd0">withLinkOrderDo</a> (Func &amp;&amp;F) -&gt; decltype(<a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>(std::declval&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a1a2b573da544cf233d62075a16146245">JITDylibSearchOrder</a> &amp; &gt;()))</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Do something with the link order (run under the session lock). <a href="#a82001e6ef07752d7eb0843a693f90bd0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename MaterializationUnitType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a5ec8631eb0c37168d6f85c4ecad77747">define</a> (std::unique_ptr&lt; MaterializationUnitType &gt; &amp;&amp;MU, ResourceTrackerSP RT=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Define all symbols provided by the materialization unit to be part of this <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a>. <a href="#a5ec8631eb0c37168d6f85c4ecad77747">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename MaterializationUnitType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a557549c7b7f504a9c5a585512bf28a57">define</a> (std::unique_ptr&lt; MaterializationUnitType &gt; &amp;MU, ResourceTrackerSP RT=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Define all symbols provided by the materialization unit to be part of this <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a>. <a href="#a557549c7b7f504a9c5a585512bf28a57">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a22901ece72bc281bb4690fad971c4eb5">remove</a> (const SymbolNameSet &amp;Names)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Tries to remove the given symbols. <a href="#a22901ece72bc281bb4690fad971c4eb5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; std::vector&lt; <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a1baadbec01aced37be13a1b86c76397e">JITDylibSP</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af36929f41ff61aa9c3524dd391d32ce5">getDFSLinkOrder</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return this <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> and its transitive dependencies in DFS order based on linkage relationships. <a href="#af36929f41ff61aa9c3524dd391d32ce5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; std::vector&lt; <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a1baadbec01aced37be13a1b86c76397e">JITDylibSP</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf4dc560f9baa4f9f4c21211cff5c420">getReverseDFSLinkOrder</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Rteurn this <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> and its transitive dependencies in reverse DFS order based on linkage relationships. <a href="#adf4dc560f9baa4f9f4c21211cff5c420">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">RemoveTrackerResult</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab590cdf4a7de040063a9799facfdf5a">IL_removeTracker</a> (ResourceTracker &amp;RT)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a074422712a02f337d4a8560bb17919d9">transferTracker</a> (ResourceTracker &amp;DstRT, ResourceTracker &amp;SrcRT)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab435c67516ada3549a05a69067afbe58">defineImpl</a> (MaterializationUnit &amp;MU)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae877d73f5b866854d9dded4ea9f8870e">installMaterializationUnit</a> (std::unique_ptr&lt; MaterializationUnit &gt; MU, ResourceTracker &amp;RT)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2d7110577dcd306e064822b725eed486">detachQueryHelper</a> (AsynchronousSymbolQuery &amp;Q, const SymbolNameSet &amp;QuerySymbols)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ef0b4b554cefef61d4848e29217aa70">transferEmittedNodeDependencies</a> (MaterializingInfo &amp;DependantMI, const SymbolStringPtr &amp;DependantName, MaterializingInfo &amp;EmittedMI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/orc/#afd6431981e7fdfd4b5d2794f04d7d913">SymbolFlagsMap</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a46e0c1dc477943744a5e89cbda90fb16">defineMaterializing</a> (MaterializationResponsibility &amp;FromMR, SymbolFlagsMap SymbolFlags)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5c84b29487afd02c8faa58670fe21285">replace</a> (MaterializationResponsibility &amp;FromMR, std::unique_ptr&lt; MaterializationUnit &gt; MU)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/materializationresponsibility">MaterializationResponsibility</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2760f7ab8c175f2b1d0fe3954f84fcd3">delegate</a> (MaterializationResponsibility &amp;FromMR, SymbolFlagsMap SymbolFlags, SymbolStringPtr InitSymbol)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/orc/#ada98b2ca88b7bc4b65b62e3269fdade7">SymbolNameSet</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9372f3811d90e32cbfc64aae6444e0ff">getRequestedSymbols</a> (const SymbolFlagsMap &amp;SymbolFlags) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac4973708749bfe2241ac333a0bf7b95f">addDependencies</a> (const SymbolStringPtr &amp;Name, const SymbolDependenceMap &amp;Dependants)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a57900c80595b9a036762f7ccff395371">resolve</a> (MaterializationResponsibility &amp;MR, const SymbolMap &amp;Resolved)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0dc1b104d38db9934141b0892a395fb4">unlinkMaterializationResponsibility</a> (MaterializationResponsibility &amp;MR)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a912f2d873fdcdf49c8acf8848d4fb8b6">shrinkMaterializationInfoMemory</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Attempt to reduce memory usage from empty <span class="doxyComputerOutput">UnmaterializedInfos</span> and <span class="doxyComputerOutput">MaterializingInfos</span> tables. <a href="#a912f2d873fdcdf49c8acf8848d4fb8b6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/executionsession">ExecutionSession</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a520683b5830d978f0249415a11d7cbd0">ES</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">enum <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">llvm::orc::JITDylib</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a548eb55f880fd3b0a6eb23b59510229e">State</a> = Open</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::mutex</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab4b782f8842b1bd91b0a821b85425388">GeneratorsMutex</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">SymbolTable</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c7c509024f4f2e81bea99ef79095d69">Symbols</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">UnmaterializedInfosMap</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a44a953279e7f56ca4824f54d262497fd">UnmaterializedInfos</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">MaterializingInfosMap</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae1485dee55f178ebcae3e139fca627af">MaterializingInfos</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; std::shared_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/definitiongenerator">DefinitionGenerator</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a022d5d2a58c24875ce72a4bd4c0a7b6d">DefGenerators</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/orc/#a1a2b573da544cf233d62075a16146245">JITDylibSearchOrder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8aa4be0d9b14623b58ce12c711317f0b">LinkOrder</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/orc/#a25b487d71ccd2a8f38131e2b21c5d612">ResourceTrackerSP</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9d4114dcae16169129166cb33b35732c">DefaultTracker</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/resourcetracker">ResourceTracker</a> *, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#ac98d5bff2f1ce6c3ce250c347f7b86ee">SymbolNameVector</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7af13a01157a5c5a10f094373ffce4bb">TrackerSymbols</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/resourcetracker">ResourceTracker</a> *, <a href="/web-llvm/docs/api/classes/llvm/denseset">DenseSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/materializationresponsibility">MaterializationResponsibility</a> * &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeb1c56c85e0f3bf965b7cae055c97889">TrackerMRs</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; std::vector&lt; <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a1baadbec01aced37be13a1b86c76397e">JITDylibSP</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a814ccfa400b06db7a01885ddcc21196a">getDFSLinkOrder</a> (ArrayRef&lt; JITDylibSP &gt; JDs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the given JITDylibs and all of their transitive dependencies in DFS order (based on linkage relationships). <a href="#a814ccfa400b06db7a01885ddcc21196a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; std::vector&lt; <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a1baadbec01aced37be13a1b86c76397e">JITDylibSP</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a095093bca58ff168e74cfa75cebf3865">getReverseDFSLinkOrder</a> (ArrayRef&lt; JITDylibSP &gt; JDs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the given JITDylibs and all of their transitive dependencies in reverse DFS order (based on linkage relationships). <a href="#a095093bca58ff168e74cfa75cebf3865">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Represents a JIT'd dynamic library.</p>


<p>This class aims to mimic the behavior of a regular dylib or shared object, but without requiring the contained program representations to be compiled up-front. The <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a>'s content is defined by adding MaterializationUnits, and contained MaterializationUnits will typically rely on the <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a>'s links-against order to resolve external references (similar to a regular dylib).</p>


<p>The <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> object is a thin wrapper that references state held by the <a href="/web-llvm/docs/api/classes/llvm/orc/executionsession">ExecutionSession</a>. JITDylibs can be removed, clearing this underlying state and leaving the <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> object in a defunct state. In this state the <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a>'s name is guaranteed to remain accessible. If the <a href="/web-llvm/docs/api/classes/llvm/orc/executionsession">ExecutionSession</a> is still alive then other operations are callable but will return an <a href="/web-llvm/docs/api/classes/llvm/error">Error</a> or null result (depending on the API). It is illegal to call any operation other than getName on a <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> after the <a href="/web-llvm/docs/api/classes/llvm/orc/executionsession">ExecutionSession</a> has been torn down.</p>


<p>JITDylibs cannot be moved or copied. Their address is stable, and useful as a key in some JIT data structures.</p>


<p>Definition at line 896 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### AsynchronousSymbolQueryList {#aa5b49553cfdec08b246bffc93ba72d89}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::orc::JITDylib::AsynchronousSymbolQueryList = 
      std::vector&lt;std::shared_ptr&lt;AsynchronousSymbolQuery&gt;&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1109 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>.</p>

</div>
</div>

### AsynchronousSymbolQuerySet {#a7512bf66174bcaf8f1243c6723df41e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::orc::JITDylib::AsynchronousSymbolQuerySet = 
    std::set&lt;std::shared_ptr&lt;AsynchronousSymbolQuery&gt;&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1106 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>.</p>

</div>
</div>

### MaterializingInfosMap {#a9aab378a2141d50023300600fc003655}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::orc::JITDylib::MaterializingInfosMap =  DenseMap&lt;SymbolStringPtr, MaterializingInfo&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1167 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>.</p>

</div>
</div>

### SymbolTable {#ac4b235afb25b635699713f289aa2f749}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::orc::JITDylib::SymbolTable =  DenseMap&lt;SymbolStringPtr, SymbolTableEntry&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1203 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>.</p>

</div>
</div>

### UnmaterializedInfosList {#abb9a65e5530f28a59977bc26ed257931}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::orc::JITDylib::UnmaterializedInfosList = 
      std::vector&lt;std::shared_ptr&lt;UnmaterializedInfo&gt;&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1124 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>.</p>

</div>
</div>

### UnmaterializedInfosMap {#adcf6773ecae847ed298389c66c517ede}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::orc::JITDylib::UnmaterializedInfosMap = 
      DenseMap&lt;SymbolStringPtr, std::shared_ptr&lt;UnmaterializedInfo&gt;&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1121 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Enumerations

### anonymous enum  {#a1a287843affb55dafd3ef8163002467c}

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
<td class="doxyEnumItemName">Open<a id="a1a287843affb55dafd3ef8163002467ca9affb5b710ca507f6e3292e8135f1098"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Closing<a id="a1a287843affb55dafd3ef8163002467ca961ec2af4c029393ab186b58751dea53"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Closed<a id="a1a287843affb55dafd3ef8163002467ca69f81d9b011c2c5e00f12384f5a114c3"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 1254 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Friends

### AsynchronousSymbolQuery {#a595f3d213faee48086cd1c852718faff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/orc/asynchronoussymbolquery">AsynchronousSymbolQuery</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 898 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>.</p>


<p>Reference <a href="#a595f3d213faee48086cd1c852718faff">AsynchronousSymbolQuery</a>.</p>


<p>Referenced by <a href="#a595f3d213faee48086cd1c852718faff">AsynchronousSymbolQuery</a>.</p>

</div>
</div>

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


<p>Definition at line 899 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>.</p>


<p>Reference <a href="#ae073d99ba71b23b530556f075655fc61">ExecutionSession</a>.</p>


<p>Referenced by <a href="#ae073d99ba71b23b530556f075655fc61">ExecutionSession</a> and <a href="#a67fc014ddc6f09ff528b686fd7b1de20">getExecutionSession</a>.</p>

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


<p>Definition at line 901 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>.</p>


<p>Reference <a href="#a9c1590c98c2c00498468ad2f4bf8a86f">MaterializationResponsibility</a>.</p>


<p>Referenced by <a href="#a9c1590c98c2c00498468ad2f4bf8a86f">MaterializationResponsibility</a>.</p>

</div>
</div>

### Platform {#a9def841f7cd75057805532dab4d0f459}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/orc/platform">Platform</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 900 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>.</p>


<p>Reference <a href="#a9def841f7cd75057805532dab4d0f459">Platform</a>.</p>


<p>Referenced by <a href="#a9def841f7cd75057805532dab4d0f459">Platform</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### JITDylib() {#ae9b82bdb8efb96cf82c7f3c31168c5e1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::orc::JITDylib::JITDylib (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> &amp;)</td>
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



<p>Definition at line 904 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>.</p>


<p>Reference <a href="#ae9b82bdb8efb96cf82c7f3c31168c5e1">JITDylib</a>.</p>


<p>Referenced by <a href="#acffa1bb37b73209e487e6ffc5d57c560">addToLinkOrder</a>, <a href="#ae9b82bdb8efb96cf82c7f3c31168c5e1">JITDylib</a>, <a href="#aeed53fc13e88ef4fda4cc7ad22ef50a7">JITDylib</a>, <a href="#aec5c137bfb82d29d40e2d73fc3321f07">operator=</a>, <a href="#a4bf27af7e11c3af9f8380591386f223c">operator=</a>, <a href="#aa9eba60477c881a6e917ad183229ccb3">removeFromLinkOrder</a> and <a href="#a5dd08e5f273c8c5b6f25657b4a585d87">replaceInLinkOrder</a>.</p>

</div>
</div>

### JITDylib() {#aeed53fc13e88ef4fda4cc7ad22ef50a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::orc::JITDylib::JITDylib (<a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> &amp;&amp;)</td>
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



<p>Definition at line 906 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>.</p>


<p>Reference <a href="#ae9b82bdb8efb96cf82c7f3c31168c5e1">JITDylib</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Constructors

### JITDylib() {#a693e6868185790ed2210a4f64805595e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::orc::JITDylib::JITDylib (<a href="/web-llvm/docs/api/classes/llvm/orc/executionsession">ExecutionSession</a> &amp; ES, std::string Name)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1205 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>, definition at line 1249 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/core-cpp">Core.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~JITDylib() {#a17da04bffbd3264e771a59217f8e65a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::orc::JITDylib::~JITDylib ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 908 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>, definition at line 653 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/core-cpp">Core.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/jitlink/jitlinkdylib/#a6e20a8eb914e9173e681d176e3171de4">llvm::jitlink::JITLinkDylib::getName</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#aec5c137bfb82d29d40e2d73fc3321f07}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">JITDylib &amp; llvm::orc::JITDylib::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> &amp;)</td>
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



<p>Definition at line 905 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>.</p>


<p>Reference <a href="#ae9b82bdb8efb96cf82c7f3c31168c5e1">JITDylib</a>.</p>

</div>
</div>

### operator=() {#a4bf27af7e11c3af9f8380591386f223c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">JITDylib &amp; llvm::orc::JITDylib::operator= (<a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> &amp;&amp;)</td>
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



<p>Definition at line 907 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>.</p>


<p>Reference <a href="#ae9b82bdb8efb96cf82c7f3c31168c5e1">JITDylib</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addGenerator() {#ae89dfebe97fc65907c1b9194aafe1ade}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename GeneratorT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GeneratorT &amp; llvm::orc::JITDylib::addGenerator (std::unique_ptr&lt; GeneratorT &gt; DefGenerator)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Adds a definition generator to this <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> and returns a referenece to it.</p>


<p>When JITDylibs are searched during lookup, if no existing definition of a symbol is found, then any generators that have been added are run (in the order that they were added) to potentially generate a definition.</p>


<p>It is illegal to call this method on a defunct <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> and the client is responsible for ensuring that they do not do so.</p>


<p>Definition at line 957 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ad96b7cf3182ce2ba85e5a7a93b12c441">G</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/orc/lljit/#aa7573528896e709770c5e31bdf597555">llvm::orc::LLJIT::linkStaticLibraryInto</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/lljit/#aaa681b188079626ba7d773d29128e3bf">llvm::orc::LLJIT::linkStaticLibraryInto</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/lljit/#a4ece82000ef0a7c6a9e9947cbdbbd1b9">llvm::orc::LLJIT::loadPlatformDynamicLibrary</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/lljitbuilderstate/#a18ff6139760982f4640e0ea26da81ba4">llvm::orc::LLJITBuilderState::prepareForConstruction</a> and <a href="/web-llvm/docs/api/classes/llvm/orc/coffplatform/#a0cd59afcda8972c7ffd9254da83b7d70">llvm::orc::COFFPlatform::setupJITDylib</a>.</p>

</div>
</div>

### addToLinkOrder() {#a6dfad3bd64c32a0f80f488fee7f637de}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::orc::JITDylib::addToLinkOrder (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a1a2b573da544cf233d62075a16146245">JITDylibSearchOrder</a> &amp; NewLinks)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Append the given <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a1a2b573da544cf233d62075a16146245">JITDylibSearchOrder</a> to the link order for this <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> (discarding any elements already present in this <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a>'s link order).</p>

<p>Declaration at line 995 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>, definition at line 1019 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/core-cpp">Core.cpp</a>.</p>


<p>References <a href="#a6dfad3bd64c32a0f80f488fee7f637de">addToLinkOrder</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#acd1cd968cb420c82d70926920fcdc7d7">llvm::is_contained</a>.</p>


<p>Referenced by <a href="#a6dfad3bd64c32a0f80f488fee7f637de">addToLinkOrder</a>, <a href="#acffa1bb37b73209e487e6ffc5d57c560">addToLinkOrder</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/coffplatform/#a0ff140ec3eee8b9a860f3626b5640c04">llvm::orc::COFFPlatform::Create</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/lljit/#a192875b831c7f43e8050fc5ba6345407">llvm::orc::LLJIT::createJITDylib</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/executornativeplatform/#aa1bd92add845031ceeaab24c2c25c275">llvm::orc::ExecutorNativePlatform::operator()</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/loadandlinkdynlibrary/#a4c217254abc9687da4cb2c93308f09a7">llvm::orc::LoadAndLinkDynLibrary::operator()</a> and <a href="/web-llvm/docs/api/classes/llvm/orc/lljit/#a392f906e72c6fa022d871e028e6f34b9">llvm::orc::LLJIT::setUpGenericLLVMIRPlatform</a>.</p>

</div>
</div>

### addToLinkOrder() {#acffa1bb37b73209e487e6ffc5d57c560}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::orc::JITDylib::addToLinkOrder (<a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> &amp; JD, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a7cb1d8cb0ab2329f032d69d79498c81d">JITDylibLookupFlags</a> JDLookupFlags=<a href="/web-llvm/docs/api/namespaces/llvm/orc/#a7cb1d8cb0ab2329f032d69d79498c81da77fe6095a7470a90a4ae2beafb42efa7">JITDylibLookupFlags::MatchExportedSymbolsOnly</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add the given <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> to the link order for definitions in this <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a>.</p>


<p>It is illegal to call this method on a defunct <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> and the client is responsible for ensuring that they do not do so.</p>


<p>Declaration at line 1002 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>, definition at line 1031 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/core-cpp">Core.cpp</a>.</p>


<p>References <a href="#a6dfad3bd64c32a0f80f488fee7f637de">addToLinkOrder</a> and <a href="#ae9b82bdb8efb96cf82c7f3c31168c5e1">JITDylib</a>.</p>

</div>
</div>

### clear() {#a25e558db9c4a9a9b6cbd5dc09a2b929b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::orc::JITDylib::clear ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Calls remove on all trackers currently associated with this <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a>.</p>


<p>Does not run static deinits.</p>


<p>Note that removal happens outside the session lock, so new code may be added concurrently while the clear is underway, and the newly added code will <em>not</em> be cleared. Adding new code concurrently with a clear is usually a bug and should be avoided.</p>


<p>It is illegal to call this method on a defunct <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> and the client is responsible for ensuring that they do not do so.</p>


<p>Declaration at line 933 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>, definition at line 657 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/core-cpp">Core.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ae3cfc9a4e792646e7108ebae425804f0">getDefaultResourceTracker</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a71210b99d2ef87236d8505c1771a7ab1">llvm::joinErrors</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

### createResourceTracker() {#a8101c255dab4a5e953ba45c56cb091f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ResourceTrackerSP llvm::orc::JITDylib::createResourceTracker ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create a resource tracker for this <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a>.</p>


<p>It is illegal to call this method on a defunct <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> and the client is responsible for ensuring that they do not do so.</p>


<p>Declaration at line 945 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>, definition at line 681 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/core-cpp">Core.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>

</div>
</div>

### define() {#a5ec8631eb0c37168d6f85c4ecad77747}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename MaterializationUnitType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::orc::JITDylib::define (std::unique_ptr&lt; MaterializationUnitType &gt; &amp;&amp; MU, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a25b487d71ccd2a8f38131e2b21c5d612">ResourceTrackerSP</a> RT=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Define all symbols provided by the materialization unit to be part of this <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a>.</p>


<p>If RT is not specified then the default resource tracker will be used.</p>


<p>This overload always takes ownership of the <a href="/web-llvm/docs/api/classes/llvm/orc/materializationunit">MaterializationUnit</a>. If any errors occur, the <a href="/web-llvm/docs/api/classes/llvm/orc/materializationunit">MaterializationUnit</a> consumed.</p>


<p>It is illegal to call this method on a defunct <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> and the client is responsible for ensuring that they do not do so.</p>


<p>Definition at line 1041 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a3fcdc9f30e5e8b9ea4da99868a8ae4a9">DEBUG_WITH_TYPE</a>, <a href="/web-llvm/docs/api/classes/llvm/intrusiverefcntptr/#ab7e9ba9766156c2b9877ba451e7e9a64">llvm::IntrusiveRefCntPtr&lt; T &gt;::get</a>, <a href="#ae3cfc9a4e792646e7108ebae425804f0">getDefaultResourceTracker</a>, <a href="/web-llvm/docs/api/classes/llvm/jitlink/jitlinkdylib/#a6e20a8eb914e9173e681d176e3171de4">llvm::jitlink::JITLinkDylib::getName</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/orc/objectlayer/#af3a14765d70bbf88934f2246fa3bf951">llvm::orc::ObjectLayer::add</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/speculator/#aa6a0f8e9226177178d049976fd7394be">llvm::orc::Speculator::addSpeculationRuntime</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/coffplatform/#a0ff140ec3eee8b9a860f3626b5640c04">llvm::orc::COFFPlatform::Create</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/redirectablesymbolmanager/#aa3bba6d1a7f84b8ead4d44a6788ee929">llvm::orc::RedirectableSymbolManager::createRedirectableSymbols</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/localcxxruntimeoverrides/#a64281bb2737cb8f10abe3b3ec40d23c4">llvm::orc::LocalCXXRuntimeOverrides::enable</a>, <a href="/web-llvm/docs/api/classes/anonymous-lljit-cpp-/genericllvmirplatformsupport/#add2269e99095cafef133d663ab4a3688">anonymous{LLJIT.cpp}::GenericLLVMIRPlatformSupport::GenericLLVMIRPlatformSupport</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/coffvcruntimebootstrapper/#ae44ab952b63e5c304c8ea532a7dd01b1">llvm::orc::COFFVCRuntimeBootstrapper::initializeStaticVCRuntime</a>, <a href="/web-llvm/docs/api/classes/anonymous-lljit-cpp-/genericllvmirplatformsupport/#a27bbd3687e81d99d0ad1333b8f5e7f08">anonymous{LLJIT.cpp}::GenericLLVMIRPlatformSupport::setupJITDylib</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/coffplatform/#a0cd59afcda8972c7ffd9254da83b7d70">llvm::orc::COFFPlatform::setupJITDylib</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/elfnixplatform/#a6c7127d538ced6f1908ebede62dfb6ae">llvm::orc::ELFNixPlatform::setupJITDylib</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/machoplatform/#a8be40bff13ac5d492bc1e7179ce12046">llvm::orc::MachOPlatform::setupJITDylib</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/dynamiclibrarysearchgenerator/#a6f48283edeff2b9dfa266043c7229d2f">llvm::orc::DynamicLibrarySearchGenerator::tryToGenerate</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/epcdynamiclibrarysearchgenerator/#acd769134fc784667d68b675ee79b609d">llvm::orc::EPCDynamicLibrarySearchGenerator::tryToGenerate</a> and <a href="/web-llvm/docs/api/classes/llvm/orc/reexportsgenerator/#a9b1cc5b369f4fd3e04b66035eea7c481">llvm::orc::ReexportsGenerator::tryToGenerate</a>.</p>

</div>
</div>

### define() {#a557549c7b7f504a9c5a585512bf28a57}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename MaterializationUnitType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::orc::JITDylib::define (std::unique_ptr&lt; MaterializationUnitType &gt; &amp; MU, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a25b487d71ccd2a8f38131e2b21c5d612">ResourceTrackerSP</a> RT=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Define all symbols provided by the materialization unit to be part of this <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a>.</p>


<p>This overload only takes ownership of the <a href="/web-llvm/docs/api/classes/llvm/orc/materializationunit">MaterializationUnit</a> no error is generated. If an error occurs, ownership remains with the caller. This may allow the caller to modify the <a href="/web-llvm/docs/api/classes/llvm/orc/materializationunit">MaterializationUnit</a> to correct the issue, then re-call define.</p>


<p>It is illegal to call this method on a defunct <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> and the client is responsible for ensuring that they do not do so.</p>


<p>Definition at line 1055 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a3fcdc9f30e5e8b9ea4da99868a8ae4a9">DEBUG_WITH_TYPE</a>, <a href="/web-llvm/docs/api/classes/llvm/intrusiverefcntptr/#ab7e9ba9766156c2b9877ba451e7e9a64">llvm::IntrusiveRefCntPtr&lt; T &gt;::get</a>, <a href="#ae3cfc9a4e792646e7108ebae425804f0">getDefaultResourceTracker</a>, <a href="/web-llvm/docs/api/classes/llvm/jitlink/jitlinkdylib/#a6e20a8eb914e9173e681d176e3171de4">llvm::jitlink::JITLinkDylib::getName</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

### dump() {#a574566a131a23ad62ff846ac8a7901f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::orc::JITDylib::dump (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Dump current <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> state to OS.</p>


<p>It is legal to call this method on a defunct <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a>.</p>


<p>Declaration at line 921 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>, definition at line 1120 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/core-cpp">Core.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a574566a131a23ad62ff846ac8a7901f4">dump</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a939bc2108d47080767f0c06ba56caec7">llvm::format</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/provenanceanalysisevaluator-cpp/#a2ee79648e8bce3ddbb26358ff10e3e82">getName</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/namespaces/llvm/orc/#adac25fca9fb14b1defe43d18a81c16e8ae7d31fc0602fb2ede144d18cdffd816b">llvm::orc::Ready</a>.</p>


<p>Referenced by <a href="#a574566a131a23ad62ff846ac8a7901f4">dump</a>.</p>

</div>
</div>

### getDefaultResourceTracker() {#ae3cfc9a4e792646e7108ebae425804f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ResourceTrackerSP llvm::orc::JITDylib::getDefaultResourceTracker ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the default resource tracker for this <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a>.</p>


<p>It is illegal to call this method on a defunct <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> and the client is responsible for ensuring that they do not do so.</p>


<p>Declaration at line 939 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>, definition at line 672 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/core-cpp">Core.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/orc/irlayer/#aad7763ba39a875c20de25ee9f47eba17">llvm::orc::IRLayer::add</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/linkgraphlayer/#aa8b8c181245131d2ad620fe11fdb47ad">llvm::orc::LinkGraphLayer::add</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/linkgraphlayer/#a645e7dc16b19043db73e13534780b159">llvm::orc::LinkGraphLayer::add</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/objectlayer/#a446313e5f05f661d0d6462ceed1541ca">llvm::orc::ObjectLayer::add</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/lljit/#a5d24430d7198c43adb4bcbb1b3a5040c">llvm::orc::LLJIT::addIRModule</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/lljit/#a2369a3a1c00d13978b3c71bdc133ba86">llvm::orc::LLJIT::addObjectFile</a>, <a href="#a25e558db9c4a9a9b6cbd5dc09a2b929b">clear</a>, <a href="#a5ec8631eb0c37168d6f85c4ecad77747">define</a> and <a href="#a557549c7b7f504a9c5a585512bf28a57">define</a>.</p>

</div>
</div>

### getDFSLinkOrder() {#af36929f41ff61aa9c3524dd391d32ce5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; std::vector&lt; JITDylibSP &gt; &gt; llvm::orc::JITDylib::getDFSLinkOrder ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return this <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> and its transitive dependencies in DFS order based on linkage relationships.</p>


<p>If any <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> in the order is defunct then this method will return an error, otherwise returns the order.</p>


<p>Declaration at line 1096 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>, definition at line 1771 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/core-cpp">Core.cpp</a>.</p>


<p>Reference <a href="#af36929f41ff61aa9c3524dd391d32ce5">getDFSLinkOrder</a>.</p>


<p>Referenced by <a href="#af36929f41ff61aa9c3524dd391d32ce5">getDFSLinkOrder</a> and <a href="#a095093bca58ff168e74cfa75cebf3865">getReverseDFSLinkOrder</a>.</p>

</div>
</div>

### getExecutionSession() {#a67fc014ddc6f09ff528b686fd7b1de20}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ExecutionSession &amp; llvm::orc::JITDylib::getExecutionSession ()</td>
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

<p>Get a reference to the <a href="/web-llvm/docs/api/classes/llvm/orc/executionsession">ExecutionSession</a> for this <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a>.</p>


<p>It is legal to call this method on a defunct <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a>, however the result will only usable if the <a href="/web-llvm/docs/api/classes/llvm/orc/executionsession">ExecutionSession</a> is still alive. If this <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> is held by an error that may have torn down the JIT then the result should not be used.</p>


<p>Definition at line 916 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>.</p>


<p>Reference <a href="#ae073d99ba71b23b530556f075655fc61">ExecutionSession</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/orc/#afbfe38269b7efe5437ce0b6b9dfea10e">llvm::orc::buildSimpleReexportsAliasMap</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/lazyreexportsmanager/#a8e035d19beaac11de143eeeec21f646b">llvm::orc::LazyReexportsManager::handleRemoveResources</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/lljitbuilderstate/#a18ff6139760982f4640e0ea26da81ba4">llvm::orc::LLJITBuilderState::prepareForConstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/resourcetracker/#af9d739f7df392fbb3de4e22133a22976">llvm::orc::ResourceTracker::remove</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/resourcetracker/#a6deaaff3ebd6ae3df2545cd06c0da0a4">llvm::orc::ResourceTracker::transferTo</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/reexportsgenerator/#a9b1cc5b369f4fd3e04b66035eea7c481">llvm::orc::ReexportsGenerator::tryToGenerate</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/resourcetracker/#ac946e909dda8f139167b7d28956f1e51">llvm::orc::ResourceTracker::withResourceKeyDo</a> and <a href="/web-llvm/docs/api/classes/llvm/orc/resourcetracker/#a7941320edde60605d48daba8e0980564">llvm::orc::ResourceTracker::~ResourceTracker</a>.</p>

</div>
</div>

### getReverseDFSLinkOrder() {#adf4dc560f9baa4f9f4c21211cff5c420}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; std::vector&lt; JITDylibSP &gt; &gt; llvm::orc::JITDylib::getReverseDFSLinkOrder ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Rteurn this <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> and its transitive dependencies in reverse DFS order based on linkage relationships.</p>


<p>If any <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> in the order is defunct then this method will return an error, otherwise returns the order.</p>


<p>Declaration at line 1103 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>, definition at line 1775 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/core-cpp">Core.cpp</a>.</p>


<p>Reference <a href="#adf4dc560f9baa4f9f4c21211cff5c420">getReverseDFSLinkOrder</a>.</p>


<p>Referenced by <a href="#adf4dc560f9baa4f9f4c21211cff5c420">getReverseDFSLinkOrder</a>.</p>

</div>
</div>

### remove() {#a22901ece72bc281bb4690fad971c4eb5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::orc::JITDylib::remove (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/orc/#ada98b2ca88b7bc4b65b62e3269fdade7">SymbolNameSet</a> &amp; Names)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Tries to remove the given symbols.</p>


<p>If any symbols are not defined in this <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> this method will return a <a href="/web-llvm/docs/api/classes/llvm/orc/symbolsnotfound">SymbolsNotFound</a> error covering the missing symbols.</p>


<p>If all symbols are found but some symbols are in the process of being materialized this method will return a <a href="/web-llvm/docs/api/classes/llvm/orc/symbolscouldnotberemoved">SymbolsCouldNotBeRemoved</a> error.</p>


<p>On success, all symbols are removed. On failure, the <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> state is left unmodified (no symbols are removed).</p>


<p>It is illegal to call this method on a defunct <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> and the client is responsible for ensuring that they do not do so.</p>


<p>Declaration at line 1071 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>, definition at line 1059 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/core-cpp">Core.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#adac25fca9fb14b1defe43d18a81c16e8a1a6115e6706af39aaa7c093df280b6a7">llvm::orc::Materializing</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#adac25fca9fb14b1defe43d18a81c16e8a8c4096beb487f83a7f87c29a0ddc3dd3">llvm::orc::NeverSearched</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#adac25fca9fb14b1defe43d18a81c16e8ae7d31fc0602fb2ede144d18cdffd816b">llvm::orc::Ready</a>, <a href="#a22901ece72bc281bb4690fad971c4eb5">remove</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>


<p>Referenced by <a href="#a22901ece72bc281bb4690fad971c4eb5">remove</a>.</p>

</div>
</div>

### removeFromLinkOrder() {#aa9eba60477c881a6e917ad183229ccb3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::orc::JITDylib::removeFromLinkOrder (<a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> &amp; JD)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Remove the given <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> from the link order for this <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> if it is present.</p>


<p>Otherwise this operation is a no-op.</p>


<p>It is illegal to call this method on a defunct <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> and the client is responsible for ensuring that they do not do so.</p>


<p>Declaration at line 1020 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>, definition at line 1047 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/core-cpp">Core.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac78c09ae232b2ce188ff590d51e3c268">llvm::find_if</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#ae9b82bdb8efb96cf82c7f3c31168c5e1">JITDylib</a> and <a href="#aa9eba60477c881a6e917ad183229ccb3">removeFromLinkOrder</a>.</p>


<p>Referenced by <a href="#aa9eba60477c881a6e917ad183229ccb3">removeFromLinkOrder</a>.</p>

</div>
</div>

### removeGenerator() {#af1c180ec9ecf2c56f8e7a834aa161c8c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::orc::JITDylib::removeGenerator (<a href="/web-llvm/docs/api/classes/llvm/orc/definitiongenerator">DefinitionGenerator</a> &amp; G)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Remove a definition generator from this <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a>.</p>


<p>The given generator must exist in this <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a>'s generators list (i.e. have been added and not yet removed).</p>


<p>It is illegal to call this method on a defunct <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> and the client is responsible for ensuring that they do not do so.</p>


<p>Declaration at line 966 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>, definition at line 689 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/core-cpp">Core.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac78c09ae232b2ce188ff590d51e3c268">llvm::find_if</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ad96b7cf3182ce2ba85e5a7a93b12c441">G</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ae42219072d798876e6b08e6b78614ff6">H</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### replaceInLinkOrder() {#a5dd08e5f273c8c5b6f25657b4a585d87}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::orc::JITDylib::replaceInLinkOrder (<a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> &amp; OldJD, <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> &amp; NewJD, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a7cb1d8cb0ab2329f032d69d79498c81d">JITDylibLookupFlags</a> JDLookupFlags=<a href="/web-llvm/docs/api/namespaces/llvm/orc/#a7cb1d8cb0ab2329f032d69d79498c81da77fe6095a7470a90a4ae2beafb42efa7">JITDylibLookupFlags::MatchExportedSymbolsOnly</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Replace OldJD with NewJD in the link order if OldJD is present.</p>


<p>Otherwise this operation is a no-op.</p>


<p>It is illegal to call this method on a defunct <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> and the client is responsible for ensuring that they do not do so.</p>


<p>Declaration at line 1011 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>, definition at line 1035 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/core-cpp">Core.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ae9b82bdb8efb96cf82c7f3c31168c5e1">JITDylib</a> and <a href="#a5dd08e5f273c8c5b6f25657b4a585d87">replaceInLinkOrder</a>.</p>


<p>Referenced by <a href="#a5dd08e5f273c8c5b6f25657b4a585d87">replaceInLinkOrder</a>.</p>

</div>
</div>

### setLinkOrder() {#ab5c917be01faae33e9df9295e1dffdd7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::orc::JITDylib::setLinkOrder (<a href="/web-llvm/docs/api/namespaces/llvm/orc/#a1a2b573da544cf233d62075a16146245">JITDylibSearchOrder</a> NewSearchOrder, bool LinkAgainstThisJITDylibFirst=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set the link order to be used when fixing up definitions in <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a>.</p>


<p>This will replace the previous link order, and apply to any symbol resolutions made for definitions in this <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> after the call to setLinkOrder (even if the definition itself was added before the call).</p>


<p>If LinkAgainstThisJITDylibFirst is true (the default) then this <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> will add itself to the beginning of the LinkOrder (Clients should not put this <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> in the list in this case, to avoid redundant lookups).</p>


<p>If LinkAgainstThisJITDylibFirst is false then the link order will be used as-is. The primary motivation for this feature is to support deliberate shadowing of symbols in this <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> by a facade <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a>. For example, the facade may resolve function names to stubs, and the stubs may compile lazily by looking up symbols in this dylib. Adding the facade dylib as the first in the link order (instead of this dylib) ensures that definitions within this dylib resolve to the lazy-compiling stubs, rather than immediately materializing the definitions in this dylib.</p>


<p>It is illegal to call this method on a defunct <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> and the client is responsible for ensuring that they do not do so.</p>


<p>Declaration at line 989 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>, definition at line 1004 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/core-cpp">Core.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a39d3d23a084c4544ee5903203db10e8a">llvm::append_range</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a7cb1d8cb0ab2329f032d69d79498c81da5fa8627bea3ff4b720673b9a298caf2d">llvm::orc::MatchAllSymbols</a> and <a href="#ab5c917be01faae33e9df9295e1dffdd7">setLinkOrder</a>.</p>


<p>Referenced by <a href="#ab5c917be01faae33e9df9295e1dffdd7">setLinkOrder</a>.</p>

</div>
</div>

### withLinkOrderDo() {#a82001e6ef07752d7eb0843a693f90bd0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Func&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">decltype(F(std::declval&lt; const JITDylibSearchOrder &amp; &gt;())) llvm::orc::JITDylib::withLinkOrderDo (Func &amp;&amp; F)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Do something with the link order (run under the session lock).</p>


<p>It is illegal to call this method on a defunct <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> and the client is responsible for ensuring that they do not do so.</p>


<p>Definition at line 1027 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/orc/dllimportdefinitiongenerator/#a28474a2103675aa30411c3cc01585b0c">llvm::orc::DLLImportDefinitionGenerator::tryToGenerate</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### addDependencies() {#ac4973708749bfe2241ac333a0bf7b95f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::orc::JITDylib::addDependencies (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/orc/symbolstringptr">SymbolStringPtr</a> &amp; Name, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/orc/#ad4c600dd1184757dace1280e114f5b15">SymbolDependenceMap</a> &amp; Dependants)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1242 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>.</p>

</div>
</div>

### defineImpl() {#ab435c67516ada3549a05a69067afbe58}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::orc::JITDylib::defineImpl (<a href="/web-llvm/docs/api/classes/llvm/orc/materializationunit">MaterializationUnit</a> &amp; MU)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1217 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>, definition at line 1401 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/core-cpp">Core.cpp</a>.</p>

</div>
</div>

### defineMaterializing() {#a46e0c1dc477943744a5e89cbda90fb16}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; SymbolFlagsMap &gt; llvm::orc::JITDylib::defineMaterializing (<a href="/web-llvm/docs/api/classes/llvm/orc/materializationresponsibility">MaterializationResponsibility</a> &amp; FromMR, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#afd6431981e7fdfd4b5d2794f04d7d913">SymbolFlagsMap</a> SymbolFlags)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1230 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>, definition at line 707 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/core-cpp">Core.cpp</a>.</p>

</div>
</div>

### delegate() {#a2760f7ab8c175f2b1d0fe3954f84fcd3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; std::unique_ptr&lt; MaterializationResponsibility &gt; &gt; llvm::orc::JITDylib::delegate (<a href="/web-llvm/docs/api/classes/llvm/orc/materializationresponsibility">MaterializationResponsibility</a> &amp; FromMR, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#afd6431981e7fdfd4b5d2794f04d7d913">SymbolFlagsMap</a> SymbolFlags, <a href="/web-llvm/docs/api/classes/llvm/orc/symbolstringptr">SymbolStringPtr</a> InitSymbol)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1237 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>, definition at line 838 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/core-cpp">Core.cpp</a>.</p>

</div>
</div>

### detachQueryHelper() {#a2d7110577dcd306e064822b725eed486}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::orc::JITDylib::detachQueryHelper (<a href="/web-llvm/docs/api/classes/llvm/orc/asynchronoussymbolquery">AsynchronousSymbolQuery</a> &amp; Q, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/orc/#ada98b2ca88b7bc4b65b62e3269fdade7">SymbolNameSet</a> &amp; QuerySymbols)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1222 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>, definition at line 1483 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/core-cpp">Core.cpp</a>.</p>

</div>
</div>

### getRequestedSymbols() {#a9372f3811d90e32cbfc64aae6444e0ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SymbolNameSet llvm::orc::JITDylib::getRequestedSymbols (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/orc/#afd6431981e7fdfd4b5d2794f04d7d913">SymbolFlagsMap</a> &amp; SymbolFlags)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1240 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>, definition at line 852 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/core-cpp">Core.cpp</a>.</p>

</div>
</div>

### IL\_removeTracker() {#aab590cdf4a7de040063a9799facfdf5a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">JITDylib::RemoveTrackerResult llvm::orc::JITDylib::IL_removeTracker (<a href="/web-llvm/docs/api/classes/llvm/orc/resourcetracker">ResourceTracker</a> &amp; RT)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1213 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>, definition at line 1254 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/core-cpp">Core.cpp</a>.</p>

</div>
</div>

### installMaterializationUnit() {#ae877d73f5b866854d9dded4ea9f8870e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::orc::JITDylib::installMaterializationUnit (std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/materializationunit">MaterializationUnit</a> &gt; MU, <a href="/web-llvm/docs/api/classes/llvm/orc/resourcetracker">ResourceTracker</a> &amp; RT)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1219 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>, definition at line 1467 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/core-cpp">Core.cpp</a>.</p>

</div>
</div>

### replace() {#a5c84b29487afd02c8faa58670fe21285}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::orc::JITDylib::replace (<a href="/web-llvm/docs/api/classes/llvm/orc/materializationresponsibility">MaterializationResponsibility</a> &amp; FromMR, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/materializationunit">MaterializationUnit</a> &gt; MU)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1233 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>, definition at line 759 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/core-cpp">Core.cpp</a>.</p>

</div>
</div>

### resolve() {#a57900c80595b9a036762f7ccff395371}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::orc::JITDylib::resolve (<a href="/web-llvm/docs/api/classes/llvm/orc/materializationresponsibility">MaterializationResponsibility</a> &amp; MR, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a8ab9a099de556e888c5f92a4fe49d2fa">SymbolMap</a> &amp; Resolved)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1245 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>, definition at line 875 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/core-cpp">Core.cpp</a>.</p>

</div>
</div>

### shrinkMaterializationInfoMemory() {#a912f2d873fdcdf49c8acf8848d4fb8b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::orc::JITDylib::shrinkMaterializationInfoMemory ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Attempt to reduce memory usage from empty <span class="doxyComputerOutput">UnmaterializedInfos</span> and <span class="doxyComputerOutput">MaterializingInfos</span> tables.</p>

<p>Declaration at line 1251 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>, definition at line 993 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/core-cpp">Core.cpp</a>.</p>

</div>
</div>

### transferEmittedNodeDependencies() {#a1ef0b4b554cefef61d4848e29217aa70}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::orc::JITDylib::transferEmittedNodeDependencies (MaterializingInfo &amp; DependantMI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/orc/symbolstringptr">SymbolStringPtr</a> &amp; DependantName, MaterializingInfo &amp; EmittedMI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1225 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>.</p>

</div>
</div>

### transferTracker() {#a074422712a02f337d4a8560bb17919d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::orc::JITDylib::transferTracker (<a href="/web-llvm/docs/api/classes/llvm/orc/resourcetracker">ResourceTracker</a> &amp; DstRT, <a href="/web-llvm/docs/api/classes/llvm/orc/resourcetracker">ResourceTracker</a> &amp; SrcRT)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1215 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>, definition at line 1326 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/core-cpp">Core.cpp</a>.</p>

</div>
</div>

### unlinkMaterializationResponsibility() {#a0dc1b104d38db9934141b0892a395fb4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::orc::JITDylib::unlinkMaterializationResponsibility (<a href="/web-llvm/docs/api/classes/llvm/orc/materializationresponsibility">MaterializationResponsibility</a> &amp; MR)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1247 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>, definition at line 981 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/core-cpp">Core.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### DefaultTracker {#a9d4114dcae16169129166cb33b35732c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ResourceTrackerSP llvm::orc::JITDylib::DefaultTracker</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1261 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>.</p>

</div>
</div>

### DefGenerators {#a022d5d2a58c24875ce72a4bd4c0a7b6d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;std::shared_ptr&lt;DefinitionGenerator&gt; &gt; llvm::orc::JITDylib::DefGenerators</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1259 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>.</p>

</div>
</div>

### ES {#a520683b5830d978f0249415a11d7cbd0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ExecutionSession&amp; llvm::orc::JITDylib::ES</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1253 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>.</p>

</div>
</div>

### GeneratorsMutex {#ab4b782f8842b1bd91b0a821b85425388}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::mutex llvm::orc::JITDylib::GeneratorsMutex</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1255 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>.</p>

</div>
</div>

### LinkOrder {#a8aa4be0d9b14623b58ce12c711317f0b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">JITDylibSearchOrder llvm::orc::JITDylib::LinkOrder</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1260 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>.</p>

</div>
</div>

### MaterializingInfos {#ae1485dee55f178ebcae3e139fca627af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MaterializingInfosMap llvm::orc::JITDylib::MaterializingInfos</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1258 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>.</p>

</div>
</div>

### State {#a548eb55f880fd3b0a6eb23b59510229e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::orc::JITDylib llvm::orc::JITDylib::State = Open</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1254 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>.</p>

</div>
</div>

### Symbols {#a6c7c509024f4f2e81bea99ef79095d69}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SymbolTable llvm::orc::JITDylib::Symbols</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1256 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>.</p>

</div>
</div>

### TrackerMRs {#aeb1c56c85e0f3bf965b7cae055c97889}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;ResourceTracker *, DenseSet&lt;MaterializationResponsibility *&gt; &gt; llvm::orc::JITDylib::TrackerMRs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1266 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>.</p>

</div>
</div>

### TrackerSymbols {#a7af13a01157a5c5a10f094373ffce4bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;ResourceTracker *, SymbolNameVector&gt; llvm::orc::JITDylib::TrackerSymbols</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1264 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>.</p>

</div>
</div>

### UnmaterializedInfos {#a44a953279e7f56ca4824f54d262497fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">UnmaterializedInfosMap llvm::orc::JITDylib::UnmaterializedInfos</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1257 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### getDFSLinkOrder() {#a814ccfa400b06db7a01885ddcc21196a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; std::vector&lt; JITDylibSP &gt; &gt; llvm::orc::JITDylib::getDFSLinkOrder (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a1baadbec01aced37be13a1b86c76397e">JITDylibSP</a> &gt; JDs)</td>
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

<p>Returns the given JITDylibs and all of their transitive dependencies in DFS order (based on linkage relationships).</p>


<p>Each <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> will appear only once.</p>


<p>If any <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> in the order is defunct then this method will return an error, otherwise returns the order.</p>


<p>Declaration at line 1080 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>, definition at line 1725 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/core-cpp">Core.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#acd9e771a3296c6b24146955754620557">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::back</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/densesetimpl/#afe504aa31a6a354cec13f5b32d0b1d9d">llvm::detail::DenseSetImpl&lt; ValueT, MapTy, ValueInfoT &gt;::count</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#ac835b8735b1b2faec0efdca236e37d94">llvm::ArrayRef&lt; T &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a721fc555cb3d8dc2a1a680dcc2ce69b2">llvm::ArrayRef&lt; T &gt;::front</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2b43c21951d0948b34bcf7019949032d">llvm::inconvertibleErrorCode</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/densesetimpl/#a1b0f3ebdced8fce4b22c6a63b25d9525">llvm::detail::DenseSetImpl&lt; ValueT, MapTy, ValueInfoT &gt;::insert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#ad97688dfe9cd802e2a0691cbe620218a">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::pop_back</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a1448b52253eb43f8f07b7f5d94336a47a8eea62084ca7e541d918e823422bd82e">llvm::orc::Result</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a6b0ac1fa4f05de76413c5e0ca6334035">llvm::reverse</a>.</p>

</div>
</div>

### getReverseDFSLinkOrder() {#a095093bca58ff168e74cfa75cebf3865}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; std::vector&lt; JITDylibSP &gt; &gt; llvm::orc::JITDylib::getReverseDFSLinkOrder (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a1baadbec01aced37be13a1b86c76397e">JITDylibSP</a> &gt; JDs)</td>
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

<p>Returns the given JITDylibs and all of their transitive dependencies in reverse DFS order (based on linkage relationships).</p>


<p>Each <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> will appear only once.</p>


<p>If any <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> in the order is defunct then this method will return an error, otherwise returns the order.</p>


<p>Declaration at line 1089 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>, definition at line 1764 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/core-cpp">Core.cpp</a>.</p>


<p>References <a href="#af36929f41ff61aa9c3524dd391d32ce5">getDFSLinkOrder</a> and <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a1448b52253eb43f8f07b7f5d94336a47a8eea62084ca7e541d918e823422bd82e">llvm::orc::Result</a>.</p>

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

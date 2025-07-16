---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/orc/lllazyjitbuildersetters
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `LLLazyJITBuilderSetters` Class Template Reference



## Declaration

<div class="doxyDeclaration">
template &lt;typename JITType, typename SetterImpl, typename State&gt;
class llvm::orc::LLLazyJITBuilderSetters&lt;JITType, SetterImpl, State&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/lljit-h">llvm/ExecutionEngine/Orc/LLJIT.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/lljitbuildersetters">LLJITBuilderSetters&lt;JITType, SetterImpl, State&gt;</a></td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename JITType, typename SetterImpl, typename State&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">SetterImpl &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a7a500f0480232138cffea2a70eb31dda">setLazyCompileFailureAddr</a> (ExecutorAddr Addr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the address in the target address to call if a lazy compile fails. <a href="#a7a500f0480232138cffea2a70eb31dda">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename JITType, typename SetterImpl, typename State&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">SetterImpl &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a82c042423f9eebda0fc46dee8e08bdbe">setLazyCallthroughManager</a> (std::unique_ptr&lt; LazyCallThroughManager &gt; LCTMgr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the lazy-callthrough manager. <a href="#a82c042423f9eebda0fc46dee8e08bdbe">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename JITType, typename SetterImpl, typename State&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">SetterImpl &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a9a821ccdd243900fb791319079728b2c">setIndirectStubsManagerBuilder</a> (LLLazyJITBuilderState::IndirectStubsManagerBuilderFunction ISMBuilder)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the <a href="/web-llvm/docs/api/classes/llvm/orc/indirectstubsmanager">IndirectStubsManager</a> builder function. <a href="#a9a821ccdd243900fb791319079728b2c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 531 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/lljit-h">LLJIT.h</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### setIndirectStubsManagerBuilder() {#a9a821ccdd243900fb791319079728b2c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename JITType, typename SetterImpl, typename State&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SetterImpl &amp; llvm::orc::LLLazyJITBuilderSetters&lt; JITType, SetterImpl, State &gt;::setIndirectStubsManagerBuilder (<a href="/web-llvm/docs/api/classes/llvm/orc/lllazyjitbuilderstate/#a5b3291d514ce24e1e70b30d9c7eeceae">LLLazyJITBuilderState::IndirectStubsManagerBuilderFunction</a> ISMBuilder)</td>
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

<p>Set the <a href="/web-llvm/docs/api/classes/llvm/orc/indirectstubsmanager">IndirectStubsManager</a> builder function.</p>


<p>If this method is not called then a default, in-process <a href="/web-llvm/docs/api/classes/llvm/orc/indirectstubsmanager">IndirectStubsManager</a> builder for the host platform will be used.</p>


<p>Definition at line 556 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/lljit-h">LLJIT.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/orc/lljitbuildersetters/#af3e62a93b72970945ba5723691d727b5">llvm::orc::LLJITBuilderSetters&lt; JITType, SetterImpl, State &gt;::impl</a>.</p>

</div>
</div>

### setLazyCallthroughManager() {#a82c042423f9eebda0fc46dee8e08bdbe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename JITType, typename SetterImpl, typename State&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SetterImpl &amp; llvm::orc::LLLazyJITBuilderSetters&lt; JITType, SetterImpl, State &gt;::setLazyCallthroughManager (std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/lazycallthroughmanager">LazyCallThroughManager</a> &gt; LCTMgr)</td>
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

<p>Set the lazy-callthrough manager.</p>


<p>If this method is not called then a default, in-process lazy callthrough manager for the host platform will be used.</p>


<p>Definition at line 547 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/lljit-h">LLJIT.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/orc/lljitbuildersetters/#af3e62a93b72970945ba5723691d727b5">llvm::orc::LLJITBuilderSetters&lt; JITType, SetterImpl, State &gt;::impl</a>.</p>

</div>
</div>

### setLazyCompileFailureAddr() {#a7a500f0480232138cffea2a70eb31dda}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename JITType, typename SetterImpl, typename State&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SetterImpl &amp; llvm::orc::LLLazyJITBuilderSetters&lt; JITType, SetterImpl, State &gt;::setLazyCompileFailureAddr (<a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">ExecutorAddr</a> Addr)</td>
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

<p>Set the address in the target address to call if a lazy compile fails.</p>


<p>If this method is not called then the value will default to 0.</p>


<p>Definition at line 537 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/lljit-h">LLJIT.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/orc/lljitbuildersetters/#af3e62a93b72970945ba5723691d727b5">llvm::orc::LLJITBuilderSetters&lt; JITType, SetterImpl, State &gt;::impl</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/lljit-h">LLJIT.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>

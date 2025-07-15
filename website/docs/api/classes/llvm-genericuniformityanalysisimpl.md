---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/genericuniformityanalysisimpl
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `GenericUniformityAnalysisImpl` Class Template Reference

<p>Analysis that identifies uniform values in a data-parallel execution. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;typename ContextT&gt;
class llvm::GenericUniformityAnalysisImpl&lt;ContextT&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericuniformityimpl-h">llvm/ADT/GenericUniformityImpl.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ContextT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a0faa946ae2887a288c0ca7147077548f">BlockT</a> = typename ContextT::BlockT</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ContextT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a9579df3a488ec98753624c45d17815df">FunctionT</a> = typename ContextT::FunctionT</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ContextT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a16c41f5100e1972f513bb1318d3bfc27">ValueRefT</a> = typename ContextT::ValueRefT</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ContextT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a73c6ab22f982fc536c1790e1ad6f45c7">ConstValueRefT</a> = typename ContextT::ConstValueRefT</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ContextT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a566a277cbde3bef8b3fe081c5b36efe6">UseT</a> = typename ContextT::UseT</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ContextT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a484916a520559a5fc26918abec93866c">InstructionT</a> = typename ContextT::InstructionT</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ContextT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a885a0fd555a128573c9766a7a289513b">DominatorTreeT</a> = typename ContextT::DominatorTreeT</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ContextT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad0098fc219e0117ae1ab272ca1b91535">CycleInfoT</a> = <a href="/web-llvm/docs/api/classes/llvm/genericcycleinfo">GenericCycleInfo</a>&lt; ContextT &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ContextT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af4314308817bd3f7c32666495a9376f3">CycleT</a> = typename CycleInfoT::CycleT</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ContextT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af5eac57024165c98818d3bb85fe2eeab">SyncDependenceAnalysisT</a> = <a href="/web-llvm/docs/api/classes/llvm/genericsyncdependenceanalysis">GenericSyncDependenceAnalysis</a>&lt; ContextT &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ContextT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af505a9bea5cded13e4c0a7b5a05cd8b1">DivergenceDescriptorT</a> = typename SyncDependenceAnalysisT::DivergenceDescriptor</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ContextT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a7e97852f3c5860d076ebd5de74143672">BlockLabelMapT</a> = typename SyncDependenceAnalysisT::BlockLabelMap</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ContextT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a8f11c5c31fb2010f681384cad9a510fc">GenericUniformityAnalysisImpl</a> (const DominatorTreeT &amp;DT, const CycleInfoT &amp;CI, const TargetTransformInfo *TTI)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ContextT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a9423db64ea6f4683ba1a616ef3d3996b">initialize</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ContextT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a9579df3a488ec98753624c45d17815df">FunctionT</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a2f9174ec80a44b447329950f38af2b1a">getFunction</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ContextT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad0294653387245dc39725f57be0ebdc9">addUniformOverride</a> (const InstructionT &amp;Instr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Mark <span class="doxyComputerOutput">UniVal</span> as a value that is always uniform. <a href="#ad0294653387245dc39725f57be0ebdc9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ContextT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aa41278b6c8e6fdf15cf66dc9e5a05d4f">markDivergent</a> (const InstructionT &amp;I)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Examine <span class="doxyComputerOutput">I</span> for divergent outputs and add to the worklist. <a href="#aa41278b6c8e6fdf15cf66dc9e5a05d4f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ContextT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af74c529d0e7d25b77cd16012f8ebeacf">markDivergent</a> (ConstValueRefT DivVal)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Mark <span class="doxyComputerOutput">DivVal</span> as a divergent value. <a href="#af74c529d0e7d25b77cd16012f8ebeacf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ContextT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a91dd910b8fa57e0818cc37ac9c4a0869">markDefsDivergent</a> (const InstructionT &amp;Instr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Mark outputs of <span class="doxyComputerOutput">Instr</span> as divergent. <a href="#a91dd910b8fa57e0818cc37ac9c4a0869">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ContextT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a8a2933649618ce6aa61c2591c9aeafd4">compute</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Propagate divergence to all instructions in the region. <a href="#a8a2933649618ce6aa61c2591c9aeafd4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ContextT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a7f4e180bdd99366555f00d3397e7241f">hasDivergence</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Whether any value was marked or analyzed to be divergent. <a href="#a7f4e180bdd99366555f00d3397e7241f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ContextT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a0de754ba9cc6a7415a49d0bc598480bb">isAlwaysUniform</a> (const InstructionT &amp;Instr) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Whether <span class="doxyComputerOutput">Val</span> will always return a uniform value regardless of its operands. <a href="#a0de754ba9cc6a7415a49d0bc598480bb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ContextT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a45909d92372eefe093c193491eb350bb">hasDivergentDefs</a> (const InstructionT &amp;I) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ContextT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a9618001af2b6f359c7910658de2b8a85">isDivergent</a> (const InstructionT &amp;I) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ContextT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a309f5325e740ba03b1cf4c9eeba19d36">isDivergent</a> (ConstValueRefT V) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Whether <span class="doxyComputerOutput">Val</span> is divergent at its definition. <a href="#a309f5325e740ba03b1cf4c9eeba19d36">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ContextT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a3d08d7328852a307816fe57f7ed37e0e">isDivergentUse</a> (const UseT &amp;U) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ContextT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a8b87e13b63421be1bbbd9ab4cf702112">hasDivergentTerminator</a> (const BlockT &amp;B) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ContextT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aaa981d51f7c517dff299c1aec5a433e9">print</a> (raw_ostream &amp;out) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ContextT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a984468fb5be6228062012e4196aa4b6c">hasDivergentDefs</a> (const Instruction &amp;I) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ContextT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ae3704a53450ecf30b8fd4c6e889b2e87">markDefsDivergent</a> (const Instruction &amp;Instr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ContextT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a54862d3efc343fea75e78d7a9908dfd9">initialize</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ContextT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ab88e785d8d26bbcb5c2b29255d55cb30">isDivergentUse</a> (const Use &amp;U) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ContextT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#acda7f859f08095376f8e49522a5d21b6">hasDivergentDefs</a> (const MachineInstr &amp;I) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ContextT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a7357d4d98f9741b2ede9180f437f7623">markDefsDivergent</a> (const MachineInstr &amp;Instr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ContextT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a9871d6f69d777f1be8a101e229dfdd6a">initialize</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ContextT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a3ceb169d1457b483d5fd0c03f437f10a">isDivergentUse</a> (const MachineOperand &amp;U) const</td>
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

## Protected Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ContextT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a171b9161ef5ed4af03f9f2c223ac5dea">analyzeControlDivergence</a> (const InstructionT &amp;Term)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Mark <span class="doxyComputerOutput">Term</span> as divergent and push all Instructions that become divergent as a result on the worklist. <a href="#a171b9161ef5ed4af03f9f2c223ac5dea">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ContextT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a3ccd9b854c99298230475e6ce9d59fc3">taintAndPushAllDefs</a> (const BlockT &amp;JoinBlock)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Mark all nodes in <span class="doxyComputerOutput">JoinBlock</span> as divergent and push them on the worklist. <a href="#a3ccd9b854c99298230475e6ce9d59fc3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ContextT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a0b1ccc42f9410cce0067dd7f15bdd4c7">taintAndPushPhiNodes</a> (const BlockT &amp;JoinBlock)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Mark all phi nodes in <span class="doxyComputerOutput">JoinBlock</span> as divergent and push them on the worklist. <a href="#a0b1ccc42f9410cce0067dd7f15bdd4c7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ContextT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a721d91b68ea132737fe0ee92fa0044db">propagateCycleExitDivergence</a> (const BlockT &amp;DivExit, const CycleT &amp;DivCycle)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Identify all Instructions that become divergent because <span class="doxyComputerOutput">DivExit</span> is a divergent cycle exit of <span class="doxyComputerOutput">DivCycle</span>. <a href="#a721d91b68ea132737fe0ee92fa0044db">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ContextT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aec0743efa2c776b7ee3e7b9ed836d99b">analyzeCycleExitDivergence</a> (const CycleT &amp;DefCycle)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Mark as divergent all external uses of values defined in <span class="doxyComputerOutput">DefCycle</span>. <a href="#aec0743efa2c776b7ee3e7b9ed836d99b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ContextT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aba1a7cf169d93ea4f5810f33a5ac8102">propagateTemporalDivergence</a> (const InstructionT &amp;I, const CycleT &amp;DefCycle)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Mark as divergent all uses of <span class="doxyComputerOutput">I</span> that are outside <span class="doxyComputerOutput">DefCycle</span>. <a href="#aba1a7cf169d93ea4f5810f33a5ac8102">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ContextT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#afbaab255049c877b511c21a052388f96">pushUsers</a> (const InstructionT &amp;I)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Push all users of <span class="doxyComputerOutput">Val</span> (in the region) to the worklist. <a href="#afbaab255049c877b511c21a052388f96">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ContextT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af8aad2ef899ed0ce294302bf54e18095">pushUsers</a> (ConstValueRefT V)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ContextT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#abfe26240778249a415bf703a8e29690f">usesValueFromCycle</a> (const InstructionT &amp;I, const CycleT &amp;DefCycle) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ContextT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a14e27346fdd48452ce82e76618915547">isTemporalDivergent</a> (const BlockT &amp;ObservingBlock, const InstructionT &amp;Def) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Whether <span class="doxyComputerOutput">Def</span> is divergent when read in <span class="doxyComputerOutput">ObservingBlock</span>. <a href="#a14e27346fdd48452ce82e76618915547">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ContextT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a3b24402f782f8021f100ffd8a34eeaf7">pushUsers</a> (const Value *V)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ContextT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a400d2b7e2a60bb0884c8fb9b21d3a114">pushUsers</a> (const Instruction &amp;Instr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ContextT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a5cc6cf519f419238a138e2ac9ce9a17d">usesValueFromCycle</a> (const Instruction &amp;I, const Cycle &amp;DefCycle) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ContextT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a15350eedcae2bb4eca7bb17e63b14913">propagateTemporalDivergence</a> (const Instruction &amp;I, const Cycle &amp;DefCycle)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ContextT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af0262ba4ced437afdffd682ff61106c4">pushUsers</a> (Register Reg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ContextT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a8b7ae4eaf52d9ec2e0bedb86bec443c0">pushUsers</a> (const MachineInstr &amp;Instr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ContextT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad0aa2bb75d3006e1147c704d12d2b861">usesValueFromCycle</a> (const MachineInstr &amp;I, const MachineCycle &amp;DefCycle) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ContextT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a365912527a4eb1bb459be749493cb60c">propagateTemporalDivergence</a> (const MachineInstr &amp;I, const MachineCycle &amp;DefCycle)</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ContextT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> ContextT &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a285a6f865ef6a909995bdbd02b97080d">Context</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ContextT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a9579df3a488ec98753624c45d17815df">FunctionT</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#afb62c40af8ce2a054dfe22ee1795089b">F</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ContextT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#ad0098fc219e0117ae1ab272ca1b91535">CycleInfoT</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a2ba4e80ec91181be08d2d90b4515ab7a">CI</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ContextT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo">TargetTransformInfo</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a9ad9bb9507fae8d9ddbd419d82412874">TTI</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ContextT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/denseset">DenseSet</a>&lt; <a href="#a73c6ab22f982fc536c1790e1ad6f45c7">ConstValueRefT</a> &gt;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a54be252c8c33571122a441b40cd7be2c">DivergentValues</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ContextT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallptrset">SmallPtrSet</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a0faa946ae2887a288c0ca7147077548f">BlockT</a> *, 32 &gt;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ab0461705ca08a0a39fc126042e627b0a">DivergentTermBlocks</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ContextT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a484916a520559a5fc26918abec93866c">InstructionT</a> * &gt;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a9fcfb620a671b2af547eb41f254473c8">Worklist</a></td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ContextT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a885a0fd555a128573c9766a7a289513b">DominatorTreeT</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aa8972c814136de8ed2e7166f42e21895">DT</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ContextT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallptrset">SmallPtrSet</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#af4314308817bd3f7c32666495a9376f3">CycleT</a> *, 16 &gt;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a3d7e0bbf16ea31c3439d2a7d46850461">DivergentExitCycles</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ContextT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#af4314308817bd3f7c32666495a9376f3">CycleT</a> * &gt;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ae655cac3b5bc9b081b50072266bb2ff2">AssumedDivergent</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ContextT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#af5eac57024165c98818d3bb85fe2eeab">SyncDependenceAnalysisT</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ab6653b51cf8b07d3bb5cd1fcb8209784">SDA</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ContextT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallptrset">SmallPtrSet</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a484916a520559a5fc26918abec93866c">InstructionT</a> *, 32 &gt;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a69d6aed02710d05d99dd0a070d5946e2">UniformOverrides</a></td>
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

<p>Analysis that identifies uniform values in a data-parallel execution.</p>


<p>This analysis propagates divergence in a data-parallel context from sources of divergence to all users. It can be instantiated for an IR that provides a suitable <a href="/web-llvm/docs/api/namespaces/llvm/#a18ba42e2b2b1ad11b1ffa7c21fb0756d">SSAContext</a>.</p>


<p>Definition at line 327 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericuniformityimpl-h">GenericUniformityImpl.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### BlockLabelMapT {#a7e97852f3c5860d076ebd5de74143672}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ContextT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::GenericUniformityAnalysisImpl&lt; ContextT &gt;::BlockLabelMapT =  typename SyncDependenceAnalysisT::BlockLabelMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 343 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericuniformityimpl-h">GenericUniformityImpl.h</a>.</p>

</div>
</div>

### BlockT {#a0faa946ae2887a288c0ca7147077548f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ContextT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::GenericUniformityAnalysisImpl&lt; ContextT &gt;::BlockT =  typename ContextT::BlockT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 329 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericuniformityimpl-h">GenericUniformityImpl.h</a>.</p>

</div>
</div>

### ConstValueRefT {#a73c6ab22f982fc536c1790e1ad6f45c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ContextT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::GenericUniformityAnalysisImpl&lt; ContextT &gt;::ConstValueRefT =  typename ContextT::ConstValueRefT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 332 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericuniformityimpl-h">GenericUniformityImpl.h</a>.</p>

</div>
</div>

### CycleInfoT {#ad0098fc219e0117ae1ab272ca1b91535}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ContextT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::GenericUniformityAnalysisImpl&lt; ContextT &gt;::CycleInfoT =  GenericCycleInfo&lt;ContextT&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 337 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericuniformityimpl-h">GenericUniformityImpl.h</a>.</p>

</div>
</div>

### CycleT {#af4314308817bd3f7c32666495a9376f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ContextT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::GenericUniformityAnalysisImpl&lt; ContextT &gt;::CycleT =  typename CycleInfoT::CycleT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 338 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericuniformityimpl-h">GenericUniformityImpl.h</a>.</p>

</div>
</div>

### DivergenceDescriptorT {#af505a9bea5cded13e4c0a7b5a05cd8b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ContextT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::GenericUniformityAnalysisImpl&lt; ContextT &gt;::DivergenceDescriptorT = 
      typename SyncDependenceAnalysisT::DivergenceDescriptor</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 341 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericuniformityimpl-h">GenericUniformityImpl.h</a>.</p>

</div>
</div>

### DominatorTreeT {#a885a0fd555a128573c9766a7a289513b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ContextT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::GenericUniformityAnalysisImpl&lt; ContextT &gt;::DominatorTreeT =  typename ContextT::DominatorTreeT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 335 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericuniformityimpl-h">GenericUniformityImpl.h</a>.</p>

</div>
</div>

### FunctionT {#a9579df3a488ec98753624c45d17815df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ContextT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::GenericUniformityAnalysisImpl&lt; ContextT &gt;::FunctionT =  typename ContextT::FunctionT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 330 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericuniformityimpl-h">GenericUniformityImpl.h</a>.</p>

</div>
</div>

### InstructionT {#a484916a520559a5fc26918abec93866c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ContextT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::GenericUniformityAnalysisImpl&lt; ContextT &gt;::InstructionT =  typename ContextT::InstructionT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 334 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericuniformityimpl-h">GenericUniformityImpl.h</a>.</p>

</div>
</div>

### SyncDependenceAnalysisT {#af5eac57024165c98818d3bb85fe2eeab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ContextT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::GenericUniformityAnalysisImpl&lt; ContextT &gt;::SyncDependenceAnalysisT =  GenericSyncDependenceAnalysis&lt;ContextT&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 340 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericuniformityimpl-h">GenericUniformityImpl.h</a>.</p>

</div>
</div>

### UseT {#a566a277cbde3bef8b3fe081c5b36efe6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ContextT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::GenericUniformityAnalysisImpl&lt; ContextT &gt;::UseT =  typename ContextT::UseT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 333 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericuniformityimpl-h">GenericUniformityImpl.h</a>.</p>

</div>
</div>

### ValueRefT {#a16c41f5100e1972f513bb1318d3bfc27}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ContextT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::GenericUniformityAnalysisImpl&lt; ContextT &gt;::ValueRefT =  typename ContextT::ValueRefT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 331 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericuniformityimpl-h">GenericUniformityImpl.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### GenericUniformityAnalysisImpl() {#a8f11c5c31fb2010f681384cad9a510fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ContextT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::GenericUniformityAnalysisImpl&lt; ContextT &gt;::GenericUniformityAnalysisImpl (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a885a0fd555a128573c9766a7a289513b">DominatorTreeT</a> &amp; DT, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#ad0098fc219e0117ae1ab272ca1b91535">CycleInfoT</a> &amp; CI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo">TargetTransformInfo</a> * TTI)</td>
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



<p>Definition at line 345 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericuniformityimpl-h">GenericUniformityImpl.h</a>.</p>


<p>References <a href="#a2ba4e80ec91181be08d2d90b4515ab7a">llvm::GenericUniformityAnalysisImpl&lt; ContextT &gt;::CI</a>, <a href="#a285a6f865ef6a909995bdbd02b97080d">llvm::GenericUniformityAnalysisImpl&lt; ContextT &gt;::Context</a>, <a href="#afb62c40af8ce2a054dfe22ee1795089b">llvm::GenericUniformityAnalysisImpl&lt; ContextT &gt;::F</a>, <a href="#a2f9174ec80a44b447329950f38af2b1a">llvm::GenericUniformityAnalysisImpl&lt; ContextT &gt;::getFunction</a> and <a href="#a9ad9bb9507fae8d9ddbd419d82412874">llvm::GenericUniformityAnalysisImpl&lt; ContextT &gt;::TTI</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addUniformOverride() {#ad0294653387245dc39725f57be0ebdc9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ContextT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::GenericUniformityAnalysisImpl&lt; ContextT &gt;::addUniformOverride (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a484916a520559a5fc26918abec93866c">InstructionT</a> &amp; Instr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Mark <span class="doxyComputerOutput">UniVal</span> as a value that is always uniform.</p>

<p>Definition at line 355 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericuniformityimpl-h">GenericUniformityImpl.h</a>.</p>


<p>Referenced by <a href="#a54862d3efc343fea75e78d7a9908dfd9">llvm::GenericUniformityAnalysisImpl&lt; ContextT &gt;::initialize</a>.</p>

</div>
</div>

### compute() {#a8a2933649618ce6aa61c2591c9aeafd4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ContextT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::GenericUniformityAnalysisImpl&lt; ContextT &gt;::compute ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Propagate divergence to all instructions in the region.</p>


<p>Divergence is seeded by calls to <span class="doxyComputerOutput">markDivergent</span>.</p>


<p>Definition at line 370 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericuniformityimpl-h">GenericUniformityImpl.h</a>.</p>


<p>References <a href="#a171b9161ef5ed4af03f9f2c223ac5dea">llvm::GenericUniformityAnalysisImpl&lt; ContextT &gt;::analyzeControlDivergence</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a285a6f865ef6a909995bdbd02b97080d">llvm::GenericUniformityAnalysisImpl&lt; ContextT &gt;::Context</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#a54be252c8c33571122a441b40cd7be2c">llvm::GenericUniformityAnalysisImpl&lt; ContextT &gt;::DivergentValues</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a9618001af2b6f359c7910658de2b8a85">llvm::GenericUniformityAnalysisImpl&lt; ContextT &gt;::isDivergent</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a> and <a href="#a9fcfb620a671b2af547eb41f254473c8">llvm::GenericUniformityAnalysisImpl&lt; ContextT &gt;::Worklist</a>.</p>

</div>
</div>

### getFunction() {#a2f9174ec80a44b447329950f38af2b1a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ContextT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const FunctionT &amp; llvm::GenericUniformityAnalysisImpl&lt; ContextT &gt;::getFunction ()</td>
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



<p>Definition at line 352 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericuniformityimpl-h">GenericUniformityImpl.h</a>.</p>


<p>Reference <a href="#afb62c40af8ce2a054dfe22ee1795089b">llvm::GenericUniformityAnalysisImpl&lt; ContextT &gt;::F</a>.</p>


<p>Referenced by <a href="#a8f11c5c31fb2010f681384cad9a510fc">llvm::GenericUniformityAnalysisImpl&lt; ContextT &gt;::GenericUniformityAnalysisImpl</a>.</p>

</div>
</div>

### hasDivergence() {#a7f4e180bdd99366555f00d3397e7241f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ContextT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GenericUniformityAnalysisImpl&lt; ContextT &gt;::hasDivergence ()</td>
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

<p>Whether any value was marked or analyzed to be divergent.</p>

<p>Definition at line 373 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericuniformityimpl-h">GenericUniformityImpl.h</a>.</p>


<p>Reference <a href="#a54be252c8c33571122a441b40cd7be2c">llvm::GenericUniformityAnalysisImpl&lt; ContextT &gt;::DivergentValues</a>.</p>

</div>
</div>

### hasDivergentDefs() {#a45909d92372eefe093c193491eb350bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ContextT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GenericUniformityAnalysisImpl&lt; ContextT &gt;::hasDivergentDefs (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a484916a520559a5fc26918abec93866c">InstructionT</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 379 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericuniformityimpl-h">GenericUniformityImpl.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>


<p>Referenced by <a href="#a9618001af2b6f359c7910658de2b8a85">llvm::GenericUniformityAnalysisImpl&lt; ContextT &gt;::isDivergent</a>.</p>

</div>
</div>

### hasDivergentDefs() {#a984468fb5be6228062012e4196aa4b6c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ContextT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GenericUniformityAnalysisImpl&lt; SSAContext &gt;::hasDivergentDefs (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 21 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/uniformityanalysis-cpp">UniformityAnalysis.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="#a9618001af2b6f359c7910658de2b8a85">llvm::GenericUniformityAnalysisImpl&lt; ContextT &gt;::isDivergent</a>.</p>

</div>
</div>

### hasDivergentDefs() {#acda7f859f08095376f8e49522a5d21b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ContextT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GenericUniformityAnalysisImpl&lt; MachineSSAContext &gt;::hasDivergentDefs (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 21 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineuniformityanalysis-cpp">MachineUniformityAnalysis.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a9618001af2b6f359c7910658de2b8a85">llvm::GenericUniformityAnalysisImpl&lt; ContextT &gt;::isDivergent</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonbittracker-cpp/#a0ee73ba17c3a2cb54752905e99d77357">op</a>.</p>

</div>
</div>

### hasDivergentTerminator() {#a8b87e13b63421be1bbbd9ab4cf702112}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ContextT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GenericUniformityAnalysisImpl&lt; ContextT &gt;::hasDivergentTerminator (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a0faa946ae2887a288c0ca7147077548f">BlockT</a> &amp; B)</td>
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



<p>Definition at line 393 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericuniformityimpl-h">GenericUniformityImpl.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a> and <a href="#ab0461705ca08a0a39fc126042e627b0a">llvm::GenericUniformityAnalysisImpl&lt; ContextT &gt;::DivergentTermBlocks</a>.</p>


<p>Referenced by <a href="#aaa981d51f7c517dff299c1aec5a433e9">llvm::GenericUniformityAnalysisImpl&lt; ContextT &gt;::print</a>.</p>

</div>
</div>

### initialize() {#a9423db64ea6f4683ba1a616ef3d3996b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ContextT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::GenericUniformityAnalysisImpl&lt; ContextT &gt;::initialize ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 350 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericuniformityimpl-h">GenericUniformityImpl.h</a>.</p>

</div>
</div>

### initialize() {#a54862d3efc343fea75e78d7a9908dfd9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ContextT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::GenericUniformityAnalysisImpl&lt; SSAContext &gt;::initialize ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 32 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/uniformityanalysis-cpp">UniformityAnalysis.cpp</a>.</p>


<p>References <a href="#ad0294653387245dc39725f57be0ebdc9">llvm::GenericUniformityAnalysisImpl&lt; ContextT &gt;::addUniformOverride</a>, <a href="#afb62c40af8ce2a054dfe22ee1795089b">llvm::GenericUniformityAnalysisImpl&lt; ContextT &gt;::F</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/atomicexpandpass-cpp/#a1bcc06b1cb86bd0ea08f33323190bdaa">instructions</a>, <a href="#aa41278b6c8e6fdf15cf66dc9e5a05d4f">llvm::GenericUniformityAnalysisImpl&lt; ContextT &gt;::markDivergent</a> and <a href="#a9ad9bb9507fae8d9ddbd419d82412874">llvm::GenericUniformityAnalysisImpl&lt; ContextT &gt;::TTI</a>.</p>

</div>
</div>

### initialize() {#a9871d6f69d777f1be8a101e229dfdd6a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ContextT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::GenericUniformityAnalysisImpl&lt; MachineSSAContext &gt;::initialize ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineuniformityanalysis-cpp">MachineUniformityAnalysis.cpp</a>.</p>


<p>References <a href="#ad0294653387245dc39725f57be0ebdc9">llvm::GenericUniformityAnalysisImpl&lt; ContextT &gt;::addUniformOverride</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae58c751054b01f206f9b9e34e461d25fa32c426b55435c648a805b1103c96dcdf">llvm::AlwaysUniform</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/unifyloopexits-cpp/#a4741a07a0e5675f89cfed122008e0a76">block</a>, <a href="#afb62c40af8ce2a054dfe22ee1795089b">llvm::GenericUniformityAnalysisImpl&lt; ContextT &gt;::F</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64stacktagging-cpp/#a8e818224d2d1de9b995783ff897b0083af12bc59169afda2918e9f23e3501c2b6">instr</a>, <a href="#aa41278b6c8e6fdf15cf66dc9e5a05d4f">llvm::GenericUniformityAnalysisImpl&lt; ContextT &gt;::markDivergent</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae58c751054b01f206f9b9e34e461d25fa45ca4337861caa0e5a6723c79b31e191">llvm::NeverUniform</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/uniformityanalysis-cpp/#a74a6da751cc46fd5850fd87977e959f1">uniformity</a>.</p>

</div>
</div>

### isAlwaysUniform() {#a0de754ba9cc6a7415a49d0bc598480bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ContextT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GenericUniformityAnalysisImpl&lt; ContextT &gt;::isAlwaysUniform (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a484916a520559a5fc26918abec93866c">InstructionT</a> &amp; Instr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Whether <span class="doxyComputerOutput">Val</span> will always return a uniform value regardless of its operands.</p>

<p>Definition at line 377 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericuniformityimpl-h">GenericUniformityImpl.h</a>.</p>


<p>Referenced by <a href="#aa41278b6c8e6fdf15cf66dc9e5a05d4f">llvm::GenericUniformityAnalysisImpl&lt; ContextT &gt;::markDivergent</a>.</p>

</div>
</div>

### isDivergent() {#a9618001af2b6f359c7910658de2b8a85}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ContextT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GenericUniformityAnalysisImpl&lt; ContextT &gt;::isDivergent (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a484916a520559a5fc26918abec93866c">InstructionT</a> &amp; I)</td>
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



<p>Definition at line 381 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericuniformityimpl-h">GenericUniformityImpl.h</a>.</p>


<p>References <a href="#ab0461705ca08a0a39fc126042e627b0a">llvm::GenericUniformityAnalysisImpl&lt; ContextT &gt;::DivergentTermBlocks</a>, <a href="#a45909d92372eefe093c193491eb350bb">llvm::GenericUniformityAnalysisImpl&lt; ContextT &gt;::hasDivergentDefs</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>


<p>Referenced by <a href="#a8a2933649618ce6aa61c2591c9aeafd4">llvm::GenericUniformityAnalysisImpl&lt; ContextT &gt;::compute</a>, <a href="#a984468fb5be6228062012e4196aa4b6c">llvm::GenericUniformityAnalysisImpl&lt; ContextT &gt;::hasDivergentDefs</a>, <a href="#acda7f859f08095376f8e49522a5d21b6">llvm::GenericUniformityAnalysisImpl&lt; ContextT &gt;::hasDivergentDefs</a>, <a href="#a3ceb169d1457b483d5fd0c03f437f10a">llvm::GenericUniformityAnalysisImpl&lt; ContextT &gt;::isDivergentUse</a>, <a href="#ab88e785d8d26bbcb5c2b29255d55cb30">llvm::GenericUniformityAnalysisImpl&lt; ContextT &gt;::isDivergentUse</a> and <a href="#aaa981d51f7c517dff299c1aec5a433e9">llvm::GenericUniformityAnalysisImpl&lt; ContextT &gt;::print</a>.</p>

</div>
</div>

### isDivergent() {#a309f5325e740ba03b1cf4c9eeba19d36}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ContextT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GenericUniformityAnalysisImpl&lt; ContextT &gt;::isDivergent (<a href="#a73c6ab22f982fc536c1790e1ad6f45c7">ConstValueRefT</a> V)</td>
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

<p>Whether <span class="doxyComputerOutput">Val</span> is divergent at its definition.</p>

<p>Definition at line 389 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericuniformityimpl-h">GenericUniformityImpl.h</a>.</p>


<p>Reference <a href="#a54be252c8c33571122a441b40cd7be2c">llvm::GenericUniformityAnalysisImpl&lt; ContextT &gt;::DivergentValues</a>.</p>

</div>
</div>

### isDivergentUse() {#a3d08d7328852a307816fe57f7ed37e0e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ContextT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GenericUniformityAnalysisImpl&lt; ContextT &gt;::isDivergentUse (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a566a277cbde3bef8b3fe081c5b36efe6">UseT</a> &amp; U)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 391 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericuniformityimpl-h">GenericUniformityImpl.h</a>.</p>

</div>
</div>

### isDivergentUse() {#ab88e785d8d26bbcb5c2b29255d55cb30}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ContextT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GenericUniformityAnalysisImpl&lt; SSAContext &gt;::isDivergentUse (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/use">Use</a> &amp; U)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 93 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/uniformityanalysis-cpp">UniformityAnalysis.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a> and <a href="#a9618001af2b6f359c7910658de2b8a85">llvm::GenericUniformityAnalysisImpl&lt; ContextT &gt;::isDivergent</a>.</p>

</div>
</div>

### isDivergentUse() {#a3ceb169d1457b483d5fd0c03f437f10a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ContextT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GenericUniformityAnalysisImpl&lt; MachineSSAContext &gt;::isDivergentUse (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; U)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 131 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineuniformityanalysis-cpp">MachineUniformityAnalysis.cpp</a>.</p>


<p>References <a href="#afb62c40af8ce2a054dfe22ee1795089b">llvm::GenericUniformityAnalysisImpl&lt; ContextT &gt;::F</a> and <a href="#a9618001af2b6f359c7910658de2b8a85">llvm::GenericUniformityAnalysisImpl&lt; ContextT &gt;::isDivergent</a>.</p>

</div>
</div>

### markDefsDivergent() {#a91dd910b8fa57e0818cc37ac9c4a0869}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ContextT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GenericUniformityAnalysisImpl&lt; ContextT &gt;::markDefsDivergent (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a484916a520559a5fc26918abec93866c">InstructionT</a> &amp; Instr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Mark outputs of <span class="doxyComputerOutput">Instr</span> as divergent.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>Whether the tracked divergence state of any output has changed.</p></dd>
</dl>


<p>Definition at line 366 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericuniformityimpl-h">GenericUniformityImpl.h</a>.</p>


<p>Referenced by <a href="#aa41278b6c8e6fdf15cf66dc9e5a05d4f">llvm::GenericUniformityAnalysisImpl&lt; ContextT &gt;::markDivergent</a>.</p>

</div>
</div>

### markDefsDivergent() {#ae3704a53450ecf30b8fd4c6e889b2e87}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ContextT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GenericUniformityAnalysisImpl&lt; SSAContext &gt;::markDefsDivergent (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; Instr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 27 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/uniformityanalysis-cpp">UniformityAnalysis.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a> and <a href="#aa41278b6c8e6fdf15cf66dc9e5a05d4f">llvm::GenericUniformityAnalysisImpl&lt; ContextT &gt;::markDivergent</a>.</p>

</div>
</div>

### markDefsDivergent() {#a7357d4d98f9741b2ede9180f437f7623}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ContextT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GenericUniformityAnalysisImpl&lt; MachineSSAContext &gt;::markDefsDivergent (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; Instr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 31 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineuniformityanalysis-cpp">MachineUniformityAnalysis.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#afb62c40af8ce2a054dfe22ee1795089b">llvm::GenericUniformityAnalysisImpl&lt; ContextT &gt;::F</a>, <a href="#aa41278b6c8e6fdf15cf66dc9e5a05d4f">llvm::GenericUniformityAnalysisImpl&lt; ContextT &gt;::markDivergent</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonbittracker-cpp/#a0ee73ba17c3a2cb54752905e99d77357">op</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>

</div>
</div>

### markDivergent() {#aa41278b6c8e6fdf15cf66dc9e5a05d4f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ContextT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::GenericUniformityAnalysisImpl&lt; ContextT &gt;::markDivergent (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a484916a520559a5fc26918abec93866c">InstructionT</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Examine <span class="doxyComputerOutput">I</span> for divergent outputs and add to the worklist.</p>

<p>Definition at line 358 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericuniformityimpl-h">GenericUniformityImpl.h</a>.</p>


<p>References <a href="#a285a6f865ef6a909995bdbd02b97080d">llvm::GenericUniformityAnalysisImpl&lt; ContextT &gt;::Context</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#ab0461705ca08a0a39fc126042e627b0a">llvm::GenericUniformityAnalysisImpl&lt; ContextT &gt;::DivergentTermBlocks</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a0de754ba9cc6a7415a49d0bc598480bb">llvm::GenericUniformityAnalysisImpl&lt; ContextT &gt;::isAlwaysUniform</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="#a91dd910b8fa57e0818cc37ac9c4a0869">llvm::GenericUniformityAnalysisImpl&lt; ContextT &gt;::markDefsDivergent</a> and <a href="#a9fcfb620a671b2af547eb41f254473c8">llvm::GenericUniformityAnalysisImpl&lt; ContextT &gt;::Worklist</a>.</p>


<p>Referenced by <a href="#a54862d3efc343fea75e78d7a9908dfd9">llvm::GenericUniformityAnalysisImpl&lt; ContextT &gt;::initialize</a>, <a href="#ae3704a53450ecf30b8fd4c6e889b2e87">llvm::GenericUniformityAnalysisImpl&lt; ContextT &gt;::markDefsDivergent</a> and <a href="#a7357d4d98f9741b2ede9180f437f7623">llvm::GenericUniformityAnalysisImpl&lt; ContextT &gt;::markDefsDivergent</a>.</p>

</div>
</div>

### markDivergent() {#af74c529d0e7d25b77cd16012f8ebeacf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ContextT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GenericUniformityAnalysisImpl&lt; ContextT &gt;::markDivergent (<a href="#a73c6ab22f982fc536c1790e1ad6f45c7">ConstValueRefT</a> DivVal)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Mark <span class="doxyComputerOutput">DivVal</span> as a divergent value.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>Whether the tracked divergence state of <span class="doxyComputerOutput">DivVal</span> changed.</p></dd>
</dl>


<p>Definition at line 362 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericuniformityimpl-h">GenericUniformityImpl.h</a>.</p>


<p>References <a href="#a285a6f865ef6a909995bdbd02b97080d">llvm::GenericUniformityAnalysisImpl&lt; ContextT &gt;::Context</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#a54be252c8c33571122a441b40cd7be2c">llvm::GenericUniformityAnalysisImpl&lt; ContextT &gt;::DivergentValues</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>.</p>

</div>
</div>

### print() {#aaa981d51f7c517dff299c1aec5a433e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ContextT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::GenericUniformityAnalysisImpl&lt; ContextT &gt;::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; out)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 397 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericuniformityimpl-h">GenericUniformityImpl.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/unifyloopexits-cpp/#a4741a07a0e5675f89cfed122008e0a76">block</a>, <a href="#a285a6f865ef6a909995bdbd02b97080d">llvm::GenericUniformityAnalysisImpl&lt; ContextT &gt;::Context</a>, <a href="#ab0461705ca08a0a39fc126042e627b0a">llvm::GenericUniformityAnalysisImpl&lt; ContextT &gt;::DivergentTermBlocks</a>, <a href="#a54be252c8c33571122a441b40cd7be2c">llvm::GenericUniformityAnalysisImpl&lt; ContextT &gt;::DivergentValues</a>, <a href="#afb62c40af8ce2a054dfe22ee1795089b">llvm::GenericUniformityAnalysisImpl&lt; ContextT &gt;::F</a>, <a href="#a8b87e13b63421be1bbbd9ab4cf702112">llvm::GenericUniformityAnalysisImpl&lt; ContextT &gt;::hasDivergentTerminator</a>, <a href="#a9618001af2b6f359c7910658de2b8a85">llvm::GenericUniformityAnalysisImpl&lt; ContextT &gt;::isDivergent</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### analyzeControlDivergence() {#a171b9161ef5ed4af03f9f2c223ac5dea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ContextT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::GenericUniformityAnalysisImpl&lt; ContextT &gt;::analyzeControlDivergence (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a484916a520559a5fc26918abec93866c">InstructionT</a> &amp; Term)</td>
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

<p>Mark <span class="doxyComputerOutput">Term</span> as divergent and push all Instructions that become divergent as a result on the worklist.</p>

<p>Definition at line 423 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericuniformityimpl-h">GenericUniformityImpl.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="#a2ba4e80ec91181be08d2d90b4515ab7a">llvm::GenericUniformityAnalysisImpl&lt; ContextT &gt;::CI</a>, <a href="#a285a6f865ef6a909995bdbd02b97080d">llvm::GenericUniformityAnalysisImpl&lt; ContextT &gt;::Context</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#ab0461705ca08a0a39fc126042e627b0a">llvm::GenericUniformityAnalysisImpl&lt; ContextT &gt;::DivergentTermBlocks</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae7ec4dba2af52f8cbb4465ea0f22b494">llvm::getOutermostDivergentCycle</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3041264cb7bbcc2793ec52c9829b892a">llvm::insertIfNotContained</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a74cdbd1e4f731e7d7cd83461b8b1de0b">llvm::sort</a>.</p>


<p>Referenced by <a href="#a8a2933649618ce6aa61c2591c9aeafd4">llvm::GenericUniformityAnalysisImpl&lt; ContextT &gt;::compute</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### analyzeCycleExitDivergence() {#aec0743efa2c776b7ee3e7b9ed836d99b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ContextT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::GenericUniformityAnalysisImpl&lt; ContextT &gt;::analyzeCycleExitDivergence (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#af4314308817bd3f7c32666495a9376f3">CycleT</a> &amp; DefCycle)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Mark as divergent all external uses of values defined in <span class="doxyComputerOutput">DefCycle</span>.</p>

<p>Definition at line 458 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericuniformityimpl-h">GenericUniformityImpl.h</a>.</p>

</div>
</div>

### isTemporalDivergent() {#a14e27346fdd48452ce82e76618915547}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ContextT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GenericUniformityAnalysisImpl&lt; ContextT &gt;::isTemporalDivergent (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a0faa946ae2887a288c0ca7147077548f">BlockT</a> &amp; ObservingBlock, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a484916a520559a5fc26918abec93866c">InstructionT</a> &amp; Def)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Whether <span class="doxyComputerOutput">Def</span> is divergent when read in <span class="doxyComputerOutput">ObservingBlock</span>.</p>

<p>Definition at line 471 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericuniformityimpl-h">GenericUniformityImpl.h</a>.</p>

</div>
</div>

### propagateCycleExitDivergence() {#a721d91b68ea132737fe0ee92fa0044db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ContextT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::GenericUniformityAnalysisImpl&lt; ContextT &gt;::propagateCycleExitDivergence (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a0faa946ae2887a288c0ca7147077548f">BlockT</a> &amp; DivExit, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#af4314308817bd3f7c32666495a9376f3">CycleT</a> &amp; DivCycle)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Identify all Instructions that become divergent because <span class="doxyComputerOutput">DivExit</span> is a divergent cycle exit of <span class="doxyComputerOutput">DivCycle</span>.</p>


<p>Mark those instructions as divergent and push them on the worklist.</p>


<p>Definition at line 454 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericuniformityimpl-h">GenericUniformityImpl.h</a>.</p>

</div>
</div>

### propagateTemporalDivergence() {#aba1a7cf169d93ea4f5810f33a5ac8102}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ContextT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::GenericUniformityAnalysisImpl&lt; ContextT &gt;::propagateTemporalDivergence (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a484916a520559a5fc26918abec93866c">InstructionT</a> &amp; I, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#af4314308817bd3f7c32666495a9376f3">CycleT</a> &amp; DefCycle)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Mark as divergent all uses of <span class="doxyComputerOutput">I</span> that are outside <span class="doxyComputerOutput">DefCycle</span>.</p>

<p>Definition at line 461 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericuniformityimpl-h">GenericUniformityImpl.h</a>.</p>

</div>
</div>

### propagateTemporalDivergence() {#a15350eedcae2bb4eca7bb17e63b14913}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ContextT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::GenericUniformityAnalysisImpl&lt; SSAContext &gt;::propagateTemporalDivergence (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; I, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a60dc5ae8be8d73033ce099677e645b9b">Cycle</a> &amp; DefCycle)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 80 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/uniformityanalysis-cpp">UniformityAnalysis.cpp</a>.</p>

</div>
</div>

### propagateTemporalDivergence() {#a365912527a4eb1bb459be749493cb60c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ContextT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::GenericUniformityAnalysisImpl&lt; MachineSSAContext &gt;::propagateTemporalDivergence (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; I, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#af2582bc073a57bab10916632073e24cd">MachineCycle</a> &amp; DefCycle)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 112 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineuniformityanalysis-cpp">MachineUniformityAnalysis.cpp</a>.</p>

</div>
</div>

### pushUsers() {#afbaab255049c877b511c21a052388f96}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ContextT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::GenericUniformityAnalysisImpl&lt; ContextT &gt;::pushUsers (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a484916a520559a5fc26918abec93866c">InstructionT</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Push all users of <span class="doxyComputerOutput">Val</span> (in the region) to the worklist.</p>

<p>Definition at line 465 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericuniformityimpl-h">GenericUniformityImpl.h</a>.</p>

</div>
</div>

### pushUsers() {#af8aad2ef899ed0ce294302bf54e18095}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ContextT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::GenericUniformityAnalysisImpl&lt; ContextT &gt;::pushUsers (<a href="#a73c6ab22f982fc536c1790e1ad6f45c7">ConstValueRefT</a> V)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 466 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericuniformityimpl-h">GenericUniformityImpl.h</a>.</p>

</div>
</div>

### pushUsers() {#a3b24402f782f8021f100ffd8a34eeaf7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ContextT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::GenericUniformityAnalysisImpl&lt; SSAContext &gt;::pushUsers (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 47 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/uniformityanalysis-cpp">UniformityAnalysis.cpp</a>.</p>

</div>
</div>

### pushUsers() {#a400d2b7e2a60bb0884c8fb9b21d3a114}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ContextT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::GenericUniformityAnalysisImpl&lt; SSAContext &gt;::pushUsers (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; Instr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/uniformityanalysis-cpp">UniformityAnalysis.cpp</a>.</p>

</div>
</div>

### pushUsers() {#af0262ba4ced437afdffd682ff61106c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ContextT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::GenericUniformityAnalysisImpl&lt; MachineSSAContext &gt;::pushUsers (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineuniformityanalysis-cpp">MachineUniformityAnalysis.cpp</a>.</p>

</div>
</div>

### pushUsers() {#a8b7ae4eaf52d9ec2e0bedb86bec443c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ContextT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::GenericUniformityAnalysisImpl&lt; MachineSSAContext &gt;::pushUsers (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; Instr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 78 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineuniformityanalysis-cpp">MachineUniformityAnalysis.cpp</a>.</p>

</div>
</div>

### taintAndPushAllDefs() {#a3ccd9b854c99298230475e6ce9d59fc3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ContextT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::GenericUniformityAnalysisImpl&lt; ContextT &gt;::taintAndPushAllDefs (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a0faa946ae2887a288c0ca7147077548f">BlockT</a> &amp; JoinBlock)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Mark all nodes in <span class="doxyComputerOutput">JoinBlock</span> as divergent and push them on the worklist.</p>

<p>Definition at line 445 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericuniformityimpl-h">GenericUniformityImpl.h</a>.</p>

</div>
</div>

### taintAndPushPhiNodes() {#a0b1ccc42f9410cce0067dd7f15bdd4c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ContextT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::GenericUniformityAnalysisImpl&lt; ContextT &gt;::taintAndPushPhiNodes (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a0faa946ae2887a288c0ca7147077548f">BlockT</a> &amp; JoinBlock)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Mark all phi nodes in <span class="doxyComputerOutput">JoinBlock</span> as divergent and push them on the worklist.</p>


<p>Mark divergent phi nodes in a join block.</p>


<p>Definition at line 449 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericuniformityimpl-h">GenericUniformityImpl.h</a>.</p>

</div>
</div>

### usesValueFromCycle() {#abfe26240778249a415bf703a8e29690f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ContextT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GenericUniformityAnalysisImpl&lt; ContextT &gt;::usesValueFromCycle (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a484916a520559a5fc26918abec93866c">InstructionT</a> &amp; I, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#af4314308817bd3f7c32666495a9376f3">CycleT</a> &amp; DefCycle)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 468 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericuniformityimpl-h">GenericUniformityImpl.h</a>.</p>

</div>
</div>

### usesValueFromCycle() {#a5cc6cf519f419238a138e2ac9ce9a17d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ContextT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GenericUniformityAnalysisImpl&lt; SSAContext &gt;::usesValueFromCycle (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; I, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a60dc5ae8be8d73033ce099677e645b9b">Cycle</a> &amp; DefCycle)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 66 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/uniformityanalysis-cpp">UniformityAnalysis.cpp</a>.</p>

</div>
</div>

### usesValueFromCycle() {#ad0aa2bb75d3006e1147c704d12d2b861}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ContextT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GenericUniformityAnalysisImpl&lt; MachineSSAContext &gt;::usesValueFromCycle (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; I, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#af2582bc073a57bab10916632073e24cd">MachineCycle</a> &amp; DefCycle)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 91 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineuniformityanalysis-cpp">MachineUniformityAnalysis.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### CI {#a2ba4e80ec91181be08d2d90b4515ab7a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ContextT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const CycleInfoT&amp; llvm::GenericUniformityAnalysisImpl&lt; ContextT &gt;::CI</td>
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



<p>Definition at line 411 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericuniformityimpl-h">GenericUniformityImpl.h</a>.</p>


<p>Referenced by <a href="#a171b9161ef5ed4af03f9f2c223ac5dea">llvm::GenericUniformityAnalysisImpl&lt; ContextT &gt;::analyzeControlDivergence</a> and <a href="#a8f11c5c31fb2010f681384cad9a510fc">llvm::GenericUniformityAnalysisImpl&lt; ContextT &gt;::GenericUniformityAnalysisImpl</a>.</p>

</div>
</div>

### Context {#a285a6f865ef6a909995bdbd02b97080d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ContextT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const ContextT&amp; llvm::GenericUniformityAnalysisImpl&lt; ContextT &gt;::Context</td>
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



<p>Definition at line 409 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericuniformityimpl-h">GenericUniformityImpl.h</a>.</p>


<p>Referenced by <a href="#a171b9161ef5ed4af03f9f2c223ac5dea">llvm::GenericUniformityAnalysisImpl&lt; ContextT &gt;::analyzeControlDivergence</a>, <a href="#a8a2933649618ce6aa61c2591c9aeafd4">llvm::GenericUniformityAnalysisImpl&lt; ContextT &gt;::compute</a>, <a href="#a8f11c5c31fb2010f681384cad9a510fc">llvm::GenericUniformityAnalysisImpl&lt; ContextT &gt;::GenericUniformityAnalysisImpl</a>, <a href="#aa41278b6c8e6fdf15cf66dc9e5a05d4f">llvm::GenericUniformityAnalysisImpl&lt; ContextT &gt;::markDivergent</a>, <a href="#af74c529d0e7d25b77cd16012f8ebeacf">llvm::GenericUniformityAnalysisImpl&lt; ContextT &gt;::markDivergent</a> and <a href="#aaa981d51f7c517dff299c1aec5a433e9">llvm::GenericUniformityAnalysisImpl&lt; ContextT &gt;::print</a>.</p>

</div>
</div>

### DivergentTermBlocks {#ab0461705ca08a0a39fc126042e627b0a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ContextT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallPtrSet&lt;const BlockT *, 32&gt; llvm::GenericUniformityAnalysisImpl&lt; ContextT &gt;::DivergentTermBlocks</td>
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



<p>Definition at line 416 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericuniformityimpl-h">GenericUniformityImpl.h</a>.</p>


<p>Referenced by <a href="#a171b9161ef5ed4af03f9f2c223ac5dea">llvm::GenericUniformityAnalysisImpl&lt; ContextT &gt;::analyzeControlDivergence</a>, <a href="#a8b87e13b63421be1bbbd9ab4cf702112">llvm::GenericUniformityAnalysisImpl&lt; ContextT &gt;::hasDivergentTerminator</a>, <a href="#a9618001af2b6f359c7910658de2b8a85">llvm::GenericUniformityAnalysisImpl&lt; ContextT &gt;::isDivergent</a>, <a href="#aa41278b6c8e6fdf15cf66dc9e5a05d4f">llvm::GenericUniformityAnalysisImpl&lt; ContextT &gt;::markDivergent</a> and <a href="#aaa981d51f7c517dff299c1aec5a433e9">llvm::GenericUniformityAnalysisImpl&lt; ContextT &gt;::print</a>.</p>

</div>
</div>

### DivergentValues {#a54be252c8c33571122a441b40cd7be2c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ContextT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseSet&lt;ConstValueRefT&gt; llvm::GenericUniformityAnalysisImpl&lt; ContextT &gt;::DivergentValues</td>
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



<p>Definition at line 415 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericuniformityimpl-h">GenericUniformityImpl.h</a>.</p>


<p>Referenced by <a href="#a8a2933649618ce6aa61c2591c9aeafd4">llvm::GenericUniformityAnalysisImpl&lt; ContextT &gt;::compute</a>, <a href="#a7f4e180bdd99366555f00d3397e7241f">llvm::GenericUniformityAnalysisImpl&lt; ContextT &gt;::hasDivergence</a>, <a href="#a309f5325e740ba03b1cf4c9eeba19d36">llvm::GenericUniformityAnalysisImpl&lt; ContextT &gt;::isDivergent</a>, <a href="#af74c529d0e7d25b77cd16012f8ebeacf">llvm::GenericUniformityAnalysisImpl&lt; ContextT &gt;::markDivergent</a> and <a href="#aaa981d51f7c517dff299c1aec5a433e9">llvm::GenericUniformityAnalysisImpl&lt; ContextT &gt;::print</a>.</p>

</div>
</div>

### F {#afb62c40af8ce2a054dfe22ee1795089b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ContextT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const FunctionT&amp; llvm::GenericUniformityAnalysisImpl&lt; ContextT &gt;::F</td>
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



<p>Definition at line 410 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericuniformityimpl-h">GenericUniformityImpl.h</a>.</p>


<p>Referenced by <a href="#a8f11c5c31fb2010f681384cad9a510fc">llvm::GenericUniformityAnalysisImpl&lt; ContextT &gt;::GenericUniformityAnalysisImpl</a>, <a href="#a2f9174ec80a44b447329950f38af2b1a">llvm::GenericUniformityAnalysisImpl&lt; ContextT &gt;::getFunction</a>, <a href="#a54862d3efc343fea75e78d7a9908dfd9">llvm::GenericUniformityAnalysisImpl&lt; ContextT &gt;::initialize</a>, <a href="#a3ceb169d1457b483d5fd0c03f437f10a">llvm::GenericUniformityAnalysisImpl&lt; ContextT &gt;::isDivergentUse</a>, <a href="#a7357d4d98f9741b2ede9180f437f7623">llvm::GenericUniformityAnalysisImpl&lt; ContextT &gt;::markDefsDivergent</a> and <a href="#aaa981d51f7c517dff299c1aec5a433e9">llvm::GenericUniformityAnalysisImpl&lt; ContextT &gt;::print</a>.</p>

</div>
</div>

### TTI {#a9ad9bb9507fae8d9ddbd419d82412874}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ContextT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetTransformInfo* llvm::GenericUniformityAnalysisImpl&lt; ContextT &gt;::TTI = nullptr</td>
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



<p>Definition at line 412 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericuniformityimpl-h">GenericUniformityImpl.h</a>.</p>


<p>Referenced by <a href="#a8f11c5c31fb2010f681384cad9a510fc">llvm::GenericUniformityAnalysisImpl&lt; ContextT &gt;::GenericUniformityAnalysisImpl</a> and <a href="#a54862d3efc343fea75e78d7a9908dfd9">llvm::GenericUniformityAnalysisImpl&lt; ContextT &gt;::initialize</a>.</p>

</div>
</div>

### Worklist {#a9fcfb620a671b2af547eb41f254473c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ContextT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;const InstructionT *&gt; llvm::GenericUniformityAnalysisImpl&lt; ContextT &gt;::Worklist</td>
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



<p>Definition at line 419 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericuniformityimpl-h">GenericUniformityImpl.h</a>.</p>


<p>Referenced by <a href="#a8a2933649618ce6aa61c2591c9aeafd4">llvm::GenericUniformityAnalysisImpl&lt; ContextT &gt;::compute</a> and <a href="#aa41278b6c8e6fdf15cf66dc9e5a05d4f">llvm::GenericUniformityAnalysisImpl&lt; ContextT &gt;::markDivergent</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### AssumedDivergent {#ae655cac3b5bc9b081b50072266bb2ff2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ContextT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;const CycleT *&gt; llvm::GenericUniformityAnalysisImpl&lt; ContextT &gt;::AssumedDivergent</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 435 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericuniformityimpl-h">GenericUniformityImpl.h</a>.</p>

</div>
</div>

### DivergentExitCycles {#a3d7e0bbf16ea31c3439d2a7d46850461}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ContextT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallPtrSet&lt;const CycleT *, 16&gt; llvm::GenericUniformityAnalysisImpl&lt; ContextT &gt;::DivergentExitCycles</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 429 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericuniformityimpl-h">GenericUniformityImpl.h</a>.</p>

</div>
</div>

### DT {#aa8972c814136de8ed2e7166f42e21895}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ContextT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DominatorTreeT&amp; llvm::GenericUniformityAnalysisImpl&lt; ContextT &gt;::DT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 426 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericuniformityimpl-h">GenericUniformityImpl.h</a>.</p>

</div>
</div>

### SDA {#ab6653b51cf8b07d3bb5cd1fcb8209784}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ContextT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SyncDependenceAnalysisT llvm::GenericUniformityAnalysisImpl&lt; ContextT &gt;::SDA</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 438 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericuniformityimpl-h">GenericUniformityImpl.h</a>.</p>

</div>
</div>

### UniformOverrides {#a69d6aed02710d05d99dd0a070d5946e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ContextT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallPtrSet&lt;const InstructionT *, 32&gt; llvm::GenericUniformityAnalysisImpl&lt; ContextT &gt;::UniformOverrides</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 441 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericuniformityimpl-h">GenericUniformityImpl.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericuniformityimpl-h">GenericUniformityImpl.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/analysis/uniformityanalysis-cpp">UniformityAnalysis.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/machineuniformityanalysis-cpp">MachineUniformityAnalysis.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>

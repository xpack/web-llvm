---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/detail/passmodel
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `PassModel` Struct Template Reference

<p>A template wrapper used to implement the polymorphic API. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;typename IRUnitT, typename PassT, typename AnalysisManagerT, typename... ExtraArgTs&gt;
struct llvm::detail::PassModel&lt;IRUnitT, PassT, AnalysisManagerT, ExtraArgTs&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/passmanagerinternal-h">llvm/IR/PassManagerInternal.h</a>"
</div>

## Base struct

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/detail/passconcept">PassConcept&lt;IRUnitT, AnalysisManagerT, ExtraArgTs&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Template for the abstract base class used to dispatch polymorphically over pass objects. <a href="/web-llvm/docs/api/structs/llvm/detail/passconcept/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a21bd9bead1be2218d54d7a29e266187a">has_required_t</a> = decltype(std::declval&lt; T &amp; &gt;().<a href="#a9630c2da082b26c54a8951b2d0980d4c">isRequired</a>())</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a0c0e85fcbeb300ef8f5e00b5e9231dac">swap</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a1748d09aa399e2b04f110f675ac5201e">PassModel</a> (PassT Pass)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#aa0331282de2d0d6bf26759be42d55969">PassModel</a> (const PassModel &amp;Arg)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#ac68661d1f7345fba3ec2bd1f578e0f6d">PassModel</a> (PassModel &amp;&amp;Arg)</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/detail/passmodel">PassModel</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a872d47d6709f2c291e8966c3d83d81c2">operator=</a> (PassModel RHS)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/preservedanalyses">PreservedAnalyses</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a75180e1269e5bc1ab15f89587ac1794c">run</a> (IRUnitT &amp;IR, AnalysisManagerT &amp;AM, ExtraArgTs... ExtraArgs) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The polymorphic API which runs the pass over a given IR entity. <a href="#a75180e1269e5bc1ab15f89587ac1794c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a48f82ca9d8724e5d9b87c623446cce00">printPipeline</a> (raw_ostream &amp;OS, function_ref&lt; StringRef(StringRef)&gt; MapClassName2PassName) override</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#acea2bce21dbe53713b7f001d381b0d43">name</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Polymorphic method to access the name of a pass. <a href="#acea2bce21dbe53713b7f001d381b0d43">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a9630c2da082b26c54a8951b2d0980d4c">isRequired</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Polymorphic method to let a pass optionally exempted from skipping by <a href="/web-llvm/docs/api/classes/llvm/passinstrumentation">PassInstrumentation</a>. <a href="#a9630c2da082b26c54a8951b2d0980d4c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">PassT</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af2dfc4d84adce1dad2933c4452836bb0">Pass</a></td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac34d37c3e23b5b922ce4757b4d483920">passIsRequiredImpl</a> () -&gt; std::enable_if_t&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#abf1ad174f29a434886594433ce8a787f">is_detected</a>&lt; <a href="#a21bd9bead1be2218d54d7a29e266187a">has_required_t</a>, T &gt;<a href="/web-llvm/docs/api/namespaces/llvm/detail/#a3fe429695b1d6a60635b1e490092037e">::value</a>, bool &gt;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a56243aef5efcb050db3ee7ef8cf287b6">passIsRequiredImpl</a> () -&gt; std::enable_if_t&lt;!<a href="/web-llvm/docs/api/namespaces/llvm/#abf1ad174f29a434886594433ce8a787f">is_detected</a>&lt; <a href="#a21bd9bead1be2218d54d7a29e266187a">has_required_t</a>, T &gt;<a href="/web-llvm/docs/api/namespaces/llvm/detail/#a3fe429695b1d6a60635b1e490092037e">::value</a>, bool &gt;</td>
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

<p>A template wrapper used to implement the polymorphic API.</p>


<p>Can be instantiated for any object which provides a <span class="doxyComputerOutput">run</span> method accepting an <span class="doxyComputerOutput">IRUnitT&amp;</span> and an <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/analysismanager">AnalysisManager&lt;IRUnit&gt;</a>&amp;</span>. It requires the pass to be a copyable object.</p>


<p>Definition at line 72 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/passmanagerinternal-h">PassManagerInternal.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### has\_required\_t {#a21bd9bead1be2218d54d7a29e266187a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::detail::PassModel&lt; IRUnitT, PassT, AnalysisManagerT, ExtraArgTs &gt;::has_required_t =  decltype(std::declval&lt;T &amp;&gt;().isRequired())</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 103 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/passmanagerinternal-h">PassManagerInternal.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Friends

### swap {#a0c0e85fcbeb300ef8f5e00b5e9231dac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend void <a href="/web-llvm/docs/api/structs/llvm/detail/passmodel">PassModel</a> &amp; LHS, <a href="/web-llvm/docs/api/structs/llvm/detail/passmodel">PassModel</a> &amp; RHS</td>
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


<p>Definition at line 79 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/passmanagerinternal-h">PassManagerInternal.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a>, <a href="#a1748d09aa399e2b04f110f675ac5201e">llvm::detail::PassModel&lt; IRUnitT, PassT, AnalysisManagerT, ExtraArgTs &gt;::PassModel</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>, <a href="#a0c0e85fcbeb300ef8f5e00b5e9231dac">llvm::detail::PassModel&lt; IRUnitT, PassT, AnalysisManagerT, ExtraArgTs &gt;::swap</a> and <a href="/web-llvm/docs/api/namespaces/std/#ab8424022895aee3e366fb9a32f2883cb">std::swap</a>.</p>


<p>Referenced by <a href="#a872d47d6709f2c291e8966c3d83d81c2">llvm::detail::PassModel&lt; IRUnitT, PassT, AnalysisManagerT, ExtraArgTs &gt;::operator=</a> and <a href="#a0c0e85fcbeb300ef8f5e00b5e9231dac">llvm::detail::PassModel&lt; IRUnitT, PassT, AnalysisManagerT, ExtraArgTs &gt;::swap</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### PassModel() {#a1748d09aa399e2b04f110f675ac5201e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename IRUnitT, typename PassT, typename AnalysisManagerT, typename... ExtraArgTs&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::detail::PassModel&lt; IRUnitT, PassT, AnalysisManagerT, ExtraArgTs &gt;::PassModel (PassT Pass)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel explicit">explicit</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/passmanagerinternal-h">PassManagerInternal.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a> and <a href="#af2dfc4d84adce1dad2933c4452836bb0">llvm::detail::PassModel&lt; IRUnitT, PassT, AnalysisManagerT, ExtraArgTs &gt;::Pass</a>.</p>


<p>Referenced by <a href="#a872d47d6709f2c291e8966c3d83d81c2">llvm::detail::PassModel&lt; IRUnitT, PassT, AnalysisManagerT, ExtraArgTs &gt;::operator=</a>, <a href="#aa0331282de2d0d6bf26759be42d55969">llvm::detail::PassModel&lt; IRUnitT, PassT, AnalysisManagerT, ExtraArgTs &gt;::PassModel</a>, <a href="#ac68661d1f7345fba3ec2bd1f578e0f6d">llvm::detail::PassModel&lt; IRUnitT, PassT, AnalysisManagerT, ExtraArgTs &gt;::PassModel</a> and <a href="#a0c0e85fcbeb300ef8f5e00b5e9231dac">llvm::detail::PassModel&lt; IRUnitT, PassT, AnalysisManagerT, ExtraArgTs &gt;::swap</a>.</p>

</div>
</div>

### PassModel() {#aa0331282de2d0d6bf26759be42d55969}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename IRUnitT, typename PassT, typename AnalysisManagerT, typename... ExtraArgTs&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::detail::PassModel&lt; IRUnitT, PassT, AnalysisManagerT, ExtraArgTs &gt;::PassModel (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/detail/passmodel">PassModel</a> &amp; Arg)</td>
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



<p>Definition at line 76 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/passmanagerinternal-h">PassManagerInternal.h</a>.</p>


<p>References <a href="#af2dfc4d84adce1dad2933c4452836bb0">llvm::detail::PassModel&lt; IRUnitT, PassT, AnalysisManagerT, ExtraArgTs &gt;::Pass</a> and <a href="#a1748d09aa399e2b04f110f675ac5201e">llvm::detail::PassModel&lt; IRUnitT, PassT, AnalysisManagerT, ExtraArgTs &gt;::PassModel</a>.</p>

</div>
</div>

### PassModel() {#ac68661d1f7345fba3ec2bd1f578e0f6d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename IRUnitT, typename PassT, typename AnalysisManagerT, typename... ExtraArgTs&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::detail::PassModel&lt; IRUnitT, PassT, AnalysisManagerT, ExtraArgTs &gt;::PassModel (<a href="/web-llvm/docs/api/structs/llvm/detail/passmodel">PassModel</a> &amp;&amp; Arg)</td>
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



<p>Definition at line 77 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/passmanagerinternal-h">PassManagerInternal.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a>, <a href="#af2dfc4d84adce1dad2933c4452836bb0">llvm::detail::PassModel&lt; IRUnitT, PassT, AnalysisManagerT, ExtraArgTs &gt;::Pass</a> and <a href="#a1748d09aa399e2b04f110f675ac5201e">llvm::detail::PassModel&lt; IRUnitT, PassT, AnalysisManagerT, ExtraArgTs &gt;::PassModel</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#a872d47d6709f2c291e8966c3d83d81c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename IRUnitT, typename PassT, typename AnalysisManagerT, typename... ExtraArgTs&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PassModel &amp; llvm::detail::PassModel&lt; IRUnitT, PassT, AnalysisManagerT, ExtraArgTs &gt;::operator= (<a href="/web-llvm/docs/api/structs/llvm/detail/passmodel">PassModel</a> RHS)</td>
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



<p>Definition at line 84 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/passmanagerinternal-h">PassManagerInternal.h</a>.</p>


<p>References <a href="#a1748d09aa399e2b04f110f675ac5201e">llvm::detail::PassModel&lt; IRUnitT, PassT, AnalysisManagerT, ExtraArgTs &gt;::PassModel</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a> and <a href="#a0c0e85fcbeb300ef8f5e00b5e9231dac">llvm::detail::PassModel&lt; IRUnitT, PassT, AnalysisManagerT, ExtraArgTs &gt;::swap</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### isRequired() {#a9630c2da082b26c54a8951b2d0980d4c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename IRUnitT, typename PassT, typename AnalysisManagerT, typename... ExtraArgTs&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::detail::PassModel&lt; IRUnitT, PassT, AnalysisManagerT, ExtraArgTs &gt;::isRequired ()</td>
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

<p>Polymorphic method to let a pass optionally exempted from skipping by <a href="/web-llvm/docs/api/classes/llvm/passinstrumentation">PassInstrumentation</a>.</p>


<p>To opt-in, pass should implement <span class="doxyComputerOutput">static bool <a href="#a9630c2da082b26c54a8951b2d0980d4c">isRequired()</a></span>. It's no-op to have <span class="doxyComputerOutput">isRequired</span> always return false since that is the default.</p>


<p>Definition at line 116 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/passmanagerinternal-h">PassManagerInternal.h</a>.</p>


<p>Reference <a href="#ac34d37c3e23b5b922ce4757b4d483920">llvm::detail::PassModel&lt; IRUnitT, PassT, AnalysisManagerT, ExtraArgTs &gt;::passIsRequiredImpl</a>.</p>

</div>
</div>

### name() {#acea2bce21dbe53713b7f001d381b0d43}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename IRUnitT, typename PassT, typename AnalysisManagerT, typename... ExtraArgTs&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::detail::PassModel&lt; IRUnitT, PassT, AnalysisManagerT, ExtraArgTs &gt;::name ()</td>
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

<p>Polymorphic method to access the name of a pass.</p>

<p>Definition at line 100 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/passmanagerinternal-h">PassManagerInternal.h</a>.</p>

</div>
</div>

### printPipeline() {#a48f82ca9d8724e5d9b87c623446cce00}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename IRUnitT, typename PassT, typename AnalysisManagerT, typename... ExtraArgTs&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::detail::PassModel&lt; IRUnitT, PassT, AnalysisManagerT, ExtraArgTs &gt;::printPipeline (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>(<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>)&gt; MapClassName2PassName)</td>
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



<p>Definition at line 94 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/passmanagerinternal-h">PassManagerInternal.h</a>.</p>


<p>Reference <a href="#af2dfc4d84adce1dad2933c4452836bb0">llvm::detail::PassModel&lt; IRUnitT, PassT, AnalysisManagerT, ExtraArgTs &gt;::Pass</a>.</p>

</div>
</div>

### run() {#a75180e1269e5bc1ab15f89587ac1794c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename IRUnitT, typename PassT, typename AnalysisManagerT, typename... ExtraArgTs&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PreservedAnalyses llvm::detail::PassModel&lt; IRUnitT, PassT, AnalysisManagerT, ExtraArgTs &gt;::run (IRUnitT &amp; IR, AnalysisManagerT &amp; AM, ExtraArgTs... ExtraArgs)</td>
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

<p>The polymorphic API which runs the pass over a given IR entity.</p>


<p>Note that actual pass object can omit the analysis manager argument if desired. Also that the analysis manager may be null if there is no analysis manager in the pass pipeline.</p>


<p>Definition at line 89 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/passmanagerinternal-h">PassManagerInternal.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizer-cpp/#a05ab4853f7153e537774d02580e761ec">IR</a> and <a href="#af2dfc4d84adce1dad2933c4452836bb0">llvm::detail::PassModel&lt; IRUnitT, PassT, AnalysisManagerT, ExtraArgTs &gt;::Pass</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Pass {#af2dfc4d84adce1dad2933c4452836bb0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename IRUnitT, typename PassT, typename AnalysisManagerT, typename... ExtraArgTs&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PassT llvm::detail::PassModel&lt; IRUnitT, PassT, AnalysisManagerT, ExtraArgTs &gt;::Pass</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 118 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/passmanagerinternal-h">PassManagerInternal.h</a>.</p>


<p>Referenced by <a href="#aa0331282de2d0d6bf26759be42d55969">llvm::detail::PassModel&lt; IRUnitT, PassT, AnalysisManagerT, ExtraArgTs &gt;::PassModel</a>, <a href="#ac68661d1f7345fba3ec2bd1f578e0f6d">llvm::detail::PassModel&lt; IRUnitT, PassT, AnalysisManagerT, ExtraArgTs &gt;::PassModel</a>, <a href="#a1748d09aa399e2b04f110f675ac5201e">llvm::detail::PassModel&lt; IRUnitT, PassT, AnalysisManagerT, ExtraArgTs &gt;::PassModel</a>, <a href="#a48f82ca9d8724e5d9b87c623446cce00">llvm::detail::PassModel&lt; IRUnitT, PassT, AnalysisManagerT, ExtraArgTs &gt;::printPipeline</a> and <a href="#a75180e1269e5bc1ab15f89587ac1794c">llvm::detail::PassModel&lt; IRUnitT, PassT, AnalysisManagerT, ExtraArgTs &gt;::run</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### passIsRequiredImpl() {#ac34d37c3e23b5b922ce4757b4d483920}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::enable_if_t&lt; is_detected&lt; has_required_t, T &gt;::value, bool &gt; llvm::detail::PassModel&lt; IRUnitT, PassT, AnalysisManagerT, ExtraArgTs &gt;::passIsRequiredImpl ()</td>
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



<p>Definition at line 107 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/passmanagerinternal-h">PassManagerInternal.h</a>.</p>


<p>Referenced by <a href="#a9630c2da082b26c54a8951b2d0980d4c">llvm::detail::PassModel&lt; IRUnitT, PassT, AnalysisManagerT, ExtraArgTs &gt;::isRequired</a>.</p>

</div>
</div>

### passIsRequiredImpl() {#a56243aef5efcb050db3ee7ef8cf287b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::enable_if_t&lt;!is_detected&lt; has_required_t, T &gt;::value, bool &gt; llvm::detail::PassModel&lt; IRUnitT, PassT, AnalysisManagerT, ExtraArgTs &gt;::passIsRequiredImpl ()</td>
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



<p>Definition at line 112 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/passmanagerinternal-h">PassManagerInternal.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/passmanagerinternal-h">PassManagerInternal.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>

---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/loopsinkpass
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `LoopSinkPass` Class Reference

<p>A pass that does profile-guided sinking of instructions into loops. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::LoopSinkPass { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/loopsink-h">llvm/Transforms/Scalar/LoopSink.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/passinfomixin">PassInfoMixin&lt;DerivedT&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A CRTP mix-in to automatically provide informational APIs needed for passes. <a href="/web-llvm/docs/api/structs/llvm/passinfomixin/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/preservedanalyses">PreservedAnalyses</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a11eda417d0372700a9b48e41f267ab92">run</a> (Function &amp;F, FunctionAnalysisManager &amp;FAM)</td>
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

<p>A pass that does profile-guided sinking of instructions into loops.</p>


<p>This is a function pass as it shouldn't be composed into any kind of unified loop pass pipeline. The goal of it is to sink code into loops that is loop invariant but only required within the loop body when doing so reduces the global expected dynamic frequency with which it executes. A classic example is an extremely cold branch within a loop body.</p>


<p>We do this as a separate pass so that during normal optimization all invariant operations can be held outside the loop body to simplify fundamental analyses and transforms of the loop.</p>


<p>Definition at line 33 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/loopsink-h">LoopSink.h</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### run() {#a11eda417d0372700a9b48e41f267ab92}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PreservedAnalyses LoopSinkPass::run (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, <a href="/web-llvm/docs/api/namespaces/llvm/#adce09a5a0de0e3177eb00e932734af2f">FunctionAnalysisManager</a> &amp; FAM)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 35 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/loopsink-h">LoopSink.h</a>, definition at line 357 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopsink-cpp">LoopSink.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/preservedanalyses/#a1258a1ff55557c27684010ebd7283712">llvm::PreservedAnalyses::all</a>, <a href="/web-llvm/docs/api/groups/arcopt/#gaa57b1a4e6a1c79233913139635169cf1">Changed</a>, <a href="/web-llvm/docs/api/classes/llvm/loopinfobase/#a83d8036930a033b196409ced5c9409e5">llvm::LoopInfoBase&lt; BlockT, LoopT &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#a83c7e5ca51099e4efa895791a02fb0ed">FAM</a>, <a href="/web-llvm/docs/api/classes/llvm/loopinfobase/#a8a10d542acf3418b2a5bfefb351829c0">llvm::LoopInfoBase&lt; BlockT, LoopT &gt;::getLoopsInPreorder</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a0c8ffe664a36e30d49c84d0aded2fe08">llvm::SmallVectorImpl&lt; T &gt;::pop_back_val</a>, <a href="/web-llvm/docs/api/classes/llvm/preservedanalyses/#ad966bea18aa62ffb9e040509adc7c99f">llvm::PreservedAnalyses::preserve</a>, <a href="/web-llvm/docs/api/classes/llvm/preservedanalyses/#a937c42f77e161349ce0f999e448c7027">llvm::PreservedAnalyses::preserveSet</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopsink-cpp/#a925d8eaf1d93c7d13870ae5948c48140">sinkLoopInvariantInstructions</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aa29fe161c408879ada30c90ebbf55dcf">llvm::VerifyMemorySSA</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/loopsink-h">LoopSink.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopsink-cpp">LoopSink.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>

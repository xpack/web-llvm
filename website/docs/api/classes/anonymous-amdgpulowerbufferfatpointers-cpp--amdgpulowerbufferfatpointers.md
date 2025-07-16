---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-amdgpulowerbufferfatpointers-cpp-/amdgpulowerbufferfatpointers
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `AMDGPULowerBufferFatPointers` Class Reference



## Declaration

<div class="doxyDeclaration">
class anonymous{AMDGPULowerBufferFatPointers.cpp}::AMDGPULowerBufferFatPointers { ... }
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/modulepass">ModulePass</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/modulepass">ModulePass</a> class - This class is used to implement unstructured interprocedural optimizations and analyses. <a href="/web-llvm/docs/api/classes/llvm/modulepass/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa9edf8aedc2f0167dbf3e9e475a86a99">AMDGPULowerBufferFatPointers</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a00d87849a4eb6524d910ab07f0fd968f">run</a> (Module &amp;M, const TargetMachine &amp;TM)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a47139b5ce0b433221df6d3598993d4ab">runOnModule</a> (Module &amp;M) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>runOnModule - Virtual method overriden by subclasses to process the module being operated on. <a href="#a47139b5ce0b433221df6d3598993d4ab">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7cb445b46f1664c10d876c3e8357b369">getAnalysisUsage</a> (AnalysisUsage &amp;AU) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getAnalysisUsage - This function should be overriden by passes that need analysis information to do their job. <a href="#a7cb445b46f1664c10d876c3e8357b369">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6bbf2c6847d42384053ecbfe24a9591a">ID</a> = 0</td>
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


<p>Definition at line 2176 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulowerbufferfatpointers-cpp">AMDGPULowerBufferFatPointers.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### AMDGPULowerBufferFatPointers() {#aa9edf8aedc2f0167dbf3e9e475a86a99}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{AMDGPULowerBufferFatPointers.cpp}::AMDGPULowerBufferFatPointers::AMDGPULowerBufferFatPointers ()</td>
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



<p>Definition at line 2180 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulowerbufferfatpointers-cpp">AMDGPULowerBufferFatPointers.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/passregistry/#a05a729900b76c89e808c6c3094921b2f">llvm::PassRegistry::getPassRegistry</a>, <a href="#a6bbf2c6847d42384053ecbfe24a9591a">ID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae18278849a41c64c46655e39e7b2d1be">llvm::initializeAMDGPULowerBufferFatPointersPass</a> and <a href="/web-llvm/docs/api/classes/llvm/modulepass/#a723659a08d210f4f566887bda3f9f976">llvm::ModulePass::ModulePass</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a1fbfe8967c85c848babf2f9296af7f7e">llvm::createAMDGPULowerBufferFatPointersPass</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getAnalysisUsage() {#a7cb445b46f1664c10d876c3e8357b369}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AMDGPULowerBufferFatPointers::getAnalysisUsage (<a href="/web-llvm/docs/api/classes/llvm/analysisusage">AnalysisUsage</a> &amp;)</td>
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

<p>getAnalysisUsage - This function should be overriden by passes that need analysis information to do their job.</p>


<p>If a pass specifies that it uses a particular analysis result to this function, it can then use the <a href="/web-llvm/docs/api/classes/llvm/pass/#a4863e5e463fb79955269fbf7fbf52b80">getAnalysis&lt;AnalysisType&gt;()</a> function, below.</p>


<p>Definition at line 2188 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulowerbufferfatpointers-cpp">AMDGPULowerBufferFatPointers.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/analysisusage/#ae0adcccca08fb686c9ce00f9397b660c">llvm::AnalysisUsage::addRequired</a>.</p>

</div>
</div>

### run() {#a00d87849a4eb6524d910ab07f0fd968f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPULowerBufferFatPointers::run (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetmachine">TargetMachine</a> &amp; TM)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2185 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulowerbufferfatpointers-cpp">AMDGPULowerBufferFatPointers.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/amdgpuas/#a899ad5bfccfc22965a6714929a3dfae1ae0523ec09f17ea21ac251db04f249f13">llvm::AMDGPUAS::BUFFER_FAT_POINTER</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpulowerbufferfatpointers-cpp-/bufferfatptrtypeloweringbase/#ad5fc9fc40723f0a3abff982e1175c9a2">anonymous{AMDGPULowerBufferFatPointers.cpp}::BufferFatPtrTypeLoweringBase::clear</a>, <a href="/web-llvm/docs/api/classes/llvm/valuemap/#a49dc44e6a66de10991ee34e1df0d8065">llvm::ValueMap&lt; KeyT, ValueT, Config &gt;::clear</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulowerbufferfatpointers-cpp/#aab1c3aad12284fa84e7736dce6cd1f19">containsBufferFatPointers</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a60cf4cd57355563164d053dd470ac00f">llvm::convertUsersOfConstantsToInstructions</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/setvector/#a0c7d0dae14eb8a5916fff9f72d8b46d2">llvm::SetVector&lt; T, Vector, Set, N &gt;::getArrayRef</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulowerbufferfatpointers-cpp/#a88ecd851f4c43d32f061efe79a9b47be">hasFatPointerInterface</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/setvector/#af34eb71cc483e84d2eca80575cb9ccde">llvm::SetVector&lt; T, Vector, Set, N &gt;::insert</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a9d834ae3da8c62c2b668dada51335eb0">llvm::SmallPtrSetImpl&lt; PtrType &gt;::insert</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/atomicexpandpass-cpp/#a1bcc06b1cb86bd0ea08f33323190bdaa">instructions</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulowerbufferfatpointers-cpp/#a4d39194b2fd1ab5159a120c6b76296db">isBufferFatPtrOrVector</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a900a32da3983469187b1848189681705">llvm::Function::isIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulowerbufferfatpointers-cpp/#aa8144f82574b2b364c5253cbd61e8f92">isRemovablePointerIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulowerbufferfatpointers-cpp/#a41de039d6a42afac6a86aead8d63fc23">makeCloneInPraceMap</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulowerbufferfatpointers-cpp/#a0c78bf7a0e55e7396a9e8ec7acf2dca5">moveFunctionAdaptingType</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a0c8ffe664a36e30d49c84d0aded2fe08">llvm::SmallVectorImpl&lt; T &gt;::pop_back_val</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpulowerbufferfatpointers-cpp-/legalizebuffercontenttypesvisitor/#a4f0d3bce52d233ad9bc73ee19c049119">anonymous{AMDGPULowerBufferFatPointers.cpp}::LegalizeBufferContentTypesVisitor::processFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpulowerbufferfatpointers-cpp-/splitptrstructs/#a55cdba34485b0a468674e0df377c8677">anonymous{AMDGPULowerBufferFatPointers.cpp}::SplitPtrStructs::processFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpulowerbufferfatpointers-cpp-/storefatptrsasintsvisitor/#aa3fda38fb3f6f474b98450eec17d480d">anonymous{AMDGPULowerBufferFatPointers.cpp}::StoreFatPtrsAsIntsVisitor::processFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#a3ce5fd3a8d74ecd38fdb5e27f85d2d61">llvm::Intrinsic::remangleIntrinsicFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/valuemapper/#abc0a2be8d6101a9ed7f565409fbe4151">llvm::ValueMapper::remapFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpulowerbufferfatpointers-cpp-/bufferfatptrtypeloweringbase/#ade2358b8d5378017e50c30d4d22835da">anonymous{AMDGPULowerBufferFatPointers.cpp}::BufferFatPtrTypeLoweringBase::remapType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a77724415203930efd07d7098cb1e437da89b60f3b4ad8c1e0ddb9a31b57cb13f9">llvm::RF_None</a>.</p>


<p>Referenced by <a href="#a47139b5ce0b433221df6d3598993d4ab">runOnModule</a>.</p>

</div>
</div>

### runOnModule() {#a47139b5ce0b433221df6d3598993d4ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPULowerBufferFatPointers::runOnModule (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M)</td>
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

<p>runOnModule - Virtual method overriden by subclasses to process the module being operated on.</p>

<p>Definition at line 2186 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulowerbufferfatpointers-cpp">AMDGPULowerBufferFatPointers.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/pass/#a4863e5e463fb79955269fbf7fbf52b80">llvm::Pass::getAnalysis</a>, <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#aca23623f476d3929484bdad4a5ce54d8">llvm::TargetPassConfig::getTM</a> and <a href="#a00d87849a4eb6524d910ab07f0fd968f">run</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Attributes

### ID {#a6bbf2c6847d42384053ecbfe24a9591a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">char AMDGPULowerBufferFatPointers::ID = 0</td>
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



<p>Definition at line 2178 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulowerbufferfatpointers-cpp">AMDGPULowerBufferFatPointers.cpp</a>.</p>


<p>Referenced by <a href="#aa9edf8aedc2f0167dbf3e9e475a86a99">AMDGPULowerBufferFatPointers</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulowerbufferfatpointers-cpp">AMDGPULowerBufferFatPointers.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>

---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/anonymous-debugify-cpp-
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# `anonymous{Debugify.cpp}` Namespace



## Definition

<div class="doxyDefinition">
namespace anonymous{Debugify.cpp} { ... }
</div>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-debugify-cpp-/debugifymodulepass">DebugifyModulePass</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ModulePass for attaching synthetic debug info to everything, used with the legacy module pass manager. <a href="/web-llvm/docs/api/structs/anonymous-debugify-cpp-/debugifymodulepass/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-debugify-cpp-/debugifyfunctionpass">DebugifyFunctionPass</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>FunctionPass for attaching synthetic debug info to instructions within a single function, used with the legacy module pass manager. <a href="/web-llvm/docs/api/structs/anonymous-debugify-cpp-/debugifyfunctionpass/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-debugify-cpp-/checkdebugifymodulepass">CheckDebugifyModulePass</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ModulePass for checking debug info inserted by -debugify, used with the legacy module pass manager. <a href="/web-llvm/docs/api/structs/anonymous-debugify-cpp-/checkdebugifymodulepass/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-debugify-cpp-/checkdebugifyfunctionpass">CheckDebugifyFunctionPass</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>FunctionPass for checking debug info inserted by -debugify-function, used with the legacy module pass manager. <a href="/web-llvm/docs/api/structs/anonymous-debugify-cpp-/checkdebugifyfunctionpass/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">Level { <a href="#ac05c068d65f9e7c6996a4dabd1014454">...</a> }</td>
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

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3ff8e589a3e97b6b7900e3594c0f89be">dbg</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acdd2cbc16f42bff3297b049d4d2b063d">getAllocSizeInBits</a> (Module &amp;M, Type *Ty)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab596c1cad372ae3c0fe13d835888630">isFunctionSkipped</a> (Function &amp;F)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9d5c5c93a898487fabe292e69b1b3c9e">findTerminatingInstruction</a> (BasicBlock &amp;BB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Find the basic block's terminating instruction. <a href="#a9d5c5c93a898487fabe292e69b1b3c9e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DbgValTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad75f7422c10b9e978f61d8230e576baf">diagnoseMisSizedDbgValue</a> (Module &amp;M, DbgValTy *DbgVal)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if a mis-sized diagnostic is issued for <span class="doxyComputerOutput">DbgVal</span>. <a href="#ad75f7422c10b9e978f61d8230e576baf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa39f65efac3a51f3001285439ea997be">checkDebugifyMetadata</a> (Module &amp;M, iterator_range&lt; Module::iterator &gt; Functions, StringRef NameOfWrappedPass, StringRef Banner, bool Strip, DebugifyStatsMap *StatsMap)</td>
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

## Variables Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1c466a31a4c85557713f48be8f1327e8">Quiet</a>("debugify-quiet", cl::desc("Suppress verbose debugify output"))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a63d1fba446d0db638d72f9be0c74c437">DebugifyFunctionsLimit</a>("debugify-func-limit", cl::desc("Set max number of processed functions per pass."), cl::init(UINT_MAX))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; <a href="#ac05c068d65f9e7c6996a4dabd1014454">Level</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8aa8bac286571270f2c3fca913fe664b">DebugifyLevel</a>("debugify-level", cl::desc("Kind of debug info to add"), cl::values(clEnumValN(Level::Locations, "locations", "Locations only"), clEnumValN(Level::LocationsAndVariables, "location+variables", "Locations and Variables")), cl::init(Level::LocationsAndVariables))</td>
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


<div class="doxySectionDef">

## Enumerations

### Level {#ac05c068d65f9e7c6996a4dabd1014454}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum class anonymous{Debugify.cpp}::Level </td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel strong">strong</span>
</span>
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
<td class="doxyEnumItemName">Locations<a id="ac05c068d65f9e7c6996a4dabd1014454aeebd338ddbd547e41e4a1296de82963a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LocationsAndVariables<a id="ac05c068d65f9e7c6996a4dabd1014454ac969836efc1e81ed37ccb4f323368223"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/debugify-cpp">Debugify.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### checkDebugifyMetadata() {#aa39f65efac3a51f3001285439ea997be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{Debugify.cpp}::checkDebugifyMetadata (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M, <a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; Module::iterator &gt; Functions, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> NameOfWrappedPass, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Banner, bool Strip, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/debugify-h/#a71d63972eed599c71843cc4fe51df0e4">DebugifyStatsMap</a> * StatsMap)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 714 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/debugify-cpp">Debugify.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/bitvector/#a568ff706b8c5991bd299c8c00b803897">llvm::BitVector::count</a>, <a href="#a3ff8e589a3e97b6b7900e3594c0f89be">dbg</a>, <a href="#ad75f7422c10b9e978f61d8230e576baf">diagnoseMisSizedDbgValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2dc80c585ad5882da8cae7b5968f7e74">llvm::StringRef::empty</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mdconst/#ad938857d6c6603847adf3a8cbe403d17">llvm::mdconst::extract</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae876eb96b89c1afcc3e9cd285cc3f08c">llvm::filterDbgVars</a>, <a href="/web-llvm/docs/api/classes/llvm/namedmdnode/#acde8007e0e69969423e2de52343b702f">llvm::NamedMDNode::getNumOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a42409838a49255a3770da1469872f20b">llvm::MDNode::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/namedmdnode/#aa24b566603d206b0e74bf63daf521078">llvm::NamedMDNode::getOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/atomicexpandpass-cpp/#a1bcc06b1cb86bd0ea08f33323190bdaa">instructions</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="#aab596c1cad372ae3c0fe13d835888630">isFunctionSkipped</a>, <a href="/web-llvm/docs/api/classes/llvm/bitvector/#a168122d6ac4ed2a8b722e01b592ad289">llvm::BitVector::reset</a>, <a href="/web-llvm/docs/api/classes/llvm/bitvector/#aa56c07cdb4f03ddef7dfdf460811d36e">llvm::BitVector::set_bits</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockplacement-cpp/#a086f939e29b718dc5a01e4bcfe6af2a1">Stats</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a484621a748732e2f39e7a2a0058b3b07">llvm::stripDebugifyMetadata</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-debugify-cpp-/checkdebugifyfunctionpass/#ab4f8de493c087b6b88c5ab5a088908f3">anonymous{Debugify.cpp}::CheckDebugifyFunctionPass::runOnFunction</a> and <a href="/web-llvm/docs/api/structs/anonymous-debugify-cpp-/checkdebugifymodulepass/#a6292ec1d5a5deab5b0f317fa00737841">anonymous{Debugify.cpp}::CheckDebugifyModulePass::runOnModule</a>.</p>

</div>
</div>

### dbg() {#a3ff8e589a3e97b6b7900e3594c0f89be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">raw_ostream &amp; anonymous{Debugify.cpp}::dbg ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/debugify-cpp">Debugify.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a9a7b5c68c90f85baaedaa854cc5002cc">llvm::errs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8ad4ae565ad87db4c534952e2c88f310">llvm::nulls</a> and <a href="#a1c466a31a4c85557713f48be8f1327e8">Quiet</a>.</p>


<p>Referenced by <a href="#aa39f65efac3a51f3001285439ea997be">checkDebugifyMetadata</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6b1daaa72630852c5b859e1410e69a55">llvm::checkDebugInfoMetadata</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/debugify-cpp/#ac398fa604fb57503d55fd556af91e41a">checkFunctions</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/debugify-cpp/#af718a7db460e96f14b7c380d841cbcd8">checkInstructions</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/debugify-cpp/#ae340f07c3f677f4518e4884b9043f5d8">checkVars</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5e556eb90cea56b01be517fbf549fd84">llvm::collectDebugInfoMetadata</a> and <a href="#ad75f7422c10b9e978f61d8230e576baf">diagnoseMisSizedDbgValue</a>.</p>

</div>
</div>

### diagnoseMisSizedDbgValue() {#ad75f7422c10b9e978f61d8230e576baf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DbgValTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{Debugify.cpp}::diagnoseMisSizedDbgValue (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M, DbgValTy * DbgVal)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if a mis-sized diagnostic is issued for <span class="doxyComputerOutput">DbgVal</span>.</p>

<p>Definition at line 674 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/debugify-cpp">Debugify.cpp</a>.</p>


<p>References <a href="#a3ff8e589a3e97b6b7900e3594c0f89be">dbg</a>, <a href="#acdd2cbc16f42bff3297b049d4d2b063d">getAllocSizeInBits</a> and <a href="/web-llvm/docs/api/classes/llvm/dibasictype/#a60f94cc0e71193b01ca24ef37de9845aa71fed0c3428bf1a2e19af257c4bac379">llvm::DIBasicType::Signed</a>.</p>


<p>Referenced by <a href="#aa39f65efac3a51f3001285439ea997be">checkDebugifyMetadata</a>.</p>

</div>
</div>

### findTerminatingInstruction() {#a9d5c5c93a898487fabe292e69b1b3c9e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Instruction * anonymous{Debugify.cpp}::findTerminatingInstruction (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> &amp; BB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Find the basic block's terminating instruction.</p>


<p>Special care is needed to handle musttail and deopt calls, as these behave like (but are in fact not) terminators.</p>


<p>Definition at line 72 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/debugify-cpp">Debugify.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a6796a84f02394ce6ebef227c866cd5eb">llvm::BasicBlock::getTerminatingDeoptimizeCall</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#ad7038933b96247814b611635abb9686c">llvm::BasicBlock::getTerminatingMustTailCall</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#acf3c3aa4880eb60d00963ba93082c298">llvm::BasicBlock::getTerminator</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### getAllocSizeInBits() {#acdd2cbc16f42bff3297b049d4d2b063d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t anonymous{Debugify.cpp}::getAllocSizeInBits (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/debugify-cpp">Debugify.cpp</a>.</p>


<p>Referenced by <a href="#ad75f7422c10b9e978f61d8230e576baf">diagnoseMisSizedDbgValue</a>.</p>

</div>
</div>

### isFunctionSkipped() {#aab596c1cad372ae3c0fe13d835888630}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{Debugify.cpp}::isFunctionSkipped (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/debugify-cpp">Debugify.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>.</p>


<p>Referenced by <a href="#aa39f65efac3a51f3001285439ea997be">checkDebugifyMetadata</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6b1daaa72630852c5b859e1410e69a55">llvm::checkDebugInfoMetadata</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a5e556eb90cea56b01be517fbf549fd84">llvm::collectDebugInfoMetadata</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### DebugifyFunctionsLimit {#a63d1fba446d0db638d72f9be0c74c437}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; uint64_t &gt; anonymous{Debugify.cpp}::DebugifyFunctionsLimit("debugify-func-limit", cl::desc("Set max number of processed functions per pass."), cl::init(UINT_MAX))</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 41 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/debugify-cpp">Debugify.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a5e556eb90cea56b01be517fbf549fd84">llvm::collectDebugInfoMetadata</a>.</p>

</div>
</div>

### DebugifyLevel {#a8aa8bac286571270f2c3fca913fe664b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; Level &gt; anonymous{Debugify.cpp}::DebugifyLevel("debugify-level", cl::desc("Kind of debug info to add"), cl::values(clEnumValN(Level::Locations, "locations", "Locations only"), clEnumValN(Level::LocationsAndVariables, "location+variables", "Locations and Variables")), cl::init(Level::LocationsAndVariables))</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/debugify-cpp">Debugify.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a6b1daaa72630852c5b859e1410e69a55">llvm::checkDebugInfoMetadata</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a5e556eb90cea56b01be517fbf549fd84">llvm::collectDebugInfoMetadata</a>.</p>

</div>
</div>

### Quiet {#a1c466a31a4c85557713f48be8f1327e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; anonymous{Debugify.cpp}::Quiet("debugify-quiet", cl::desc("Suppress verbose debugify output"))</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/debugify-cpp">Debugify.cpp</a>.</p>


<p>Referenced by <a href="#a3ff8e589a3e97b6b7900e3594c0f89be">dbg</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/debugify-cpp">Debugify.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>

---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-gvnsink-cpp-/valuetable
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `ValueTable` Class



## Declaration

<div class="doxyDeclaration">
class anonymous{GVNSink.cpp}::ValueTable { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad431b90d5da2e7dd043c72d9eefed9a9">ValueTable</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a718cb8936fc783fdd1706fa7f4a4a6a5">setReachableBBs</a> (const BasicBlocksSet &amp;ReachableBBs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set basic blocks reachable from entry block. <a href="#a718cb8936fc783fdd1706fa7f4a4a6a5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8e7a1f80b6a1b4eb63fcff1619fd4207">lookupOrAdd</a> (Value *V)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the value number for the specified value, assigning it a new number if it did not have one before. <a href="#a8e7a1f80b6a1b4eb63fcff1619fd4207">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a13da6163075a3bb48f31b83d79a4fe54">lookup</a> (Value *V) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the value number of the specified value. <a href="#a13da6163075a3bb48f31b83d79a4fe54">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acfdef247a5c87f5c377d10db4983ce85">clear</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Removes all value numberings and resets the value table. <a href="#acfdef247a5c87f5c377d10db4983ce85">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f202a9387b6d7a60044c0ea986e7cb4">getMemoryUseOrder</a> (Instruction *Inst)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><span class="doxyComputerOutput">Inst</span> uses or touches memory. <a href="#a0f202a9387b6d7a60044c0ea986e7cb4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-gvnsink-cpp-/instructionuseexpr">InstructionUseExpr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9f6ebb99afcfcfa05abe500e3898dc5a">createExpr</a> (Instruction *I)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create an expression for I based on its opcode and its uses. <a href="#a9f6ebb99afcfcfa05abe500e3898dc5a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Inst&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-gvnsink-cpp-/instructionuseexpr">InstructionUseExpr</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad0a8f1fd82eae5a8afd61ba277e12d4f">createMemoryExpr</a> (Inst *I)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper to compute the value number for a memory instruction (LoadInst/StoreInst), including checking the memory ordering and volatility. <a href="#ad0a8f1fd82eae5a8afd61ba277e12d4f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, uint32_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8e385dd8db230292ab4bc9c1e98a701f">ValueNumbering</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/gvnexpression/expression">GVNExpression::Expression</a> *, uint32_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a838d2e5bcea50e83e44752f016f55155">ExpressionNumbering</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; size_t, uint32_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0fbe44c28be0260b808b450df1aa2350">HashNumbering</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a8e612822d4ba7bb36c9c79582a567108">BumpPtrAllocator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7fa61ea6a64443a75c1cdf4728783620">Allocator</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayrecycler">ArrayRecycler</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a056cb9cef8cb1618eea2577ad5cdc666">Recycler</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a412271abefd6f2f595fb3f06704d84a0">nextValueNumber</a> = 1</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-gvnsink-cpp-/#ae392bfb5a30a6ff3655f1620fa6c86c2">BasicBlocksSet</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a880df0c7684879c1fe558d74aea7029f">ReachableBBs</a></td>
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


<p>Definition at line 413 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/gvnsink-cpp">GVNSink.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### ValueTable() {#ad431b90d5da2e7dd043c72d9eefed9a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{GVNSink.cpp}::ValueTable::ValueTable ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 450 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/gvnsink-cpp">GVNSink.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### clear() {#acfdef247a5c87f5c377d10db4983ce85}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{GVNSink.cpp}::ValueTable::clear ()</td>
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

<p>Removes all value numberings and resets the value table.</p>

<p>Definition at line 555 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/gvnsink-cpp">GVNSink.cpp</a>.</p>

</div>
</div>

### getMemoryUseOrder() {#a0f202a9387b6d7a60044c0ea986e7cb4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t anonymous{GVNSink.cpp}::ValueTable::getMemoryUseOrder (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * Inst)</td>
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

<p><span class="doxyComputerOutput">Inst</span> uses or touches memory.</p>


<p>Return an <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> describing the memory state at <span class="doxyComputerOutput">Inst</span> such that if getMemoryUseOrder(I1) == getMemoryUseOrder(I2), the exact same memory operations happen after I1 and I2.</p>


<p>This is a very hard problem in general, so we use domain-specific knowledge that we only ever check for equivalence between blocks sharing a single immediate successor that is common, and when determining if I1 == I2 we will have already determined that next(I1) == next(I2). This inductive property allows us to simply return the value number of the next instruction that defines memory.</p>


<p>Definition at line 573 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/gvnsink-cpp">GVNSink.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-node-impl/#af719fc783be6589465137d997701a432">llvm::ilist_node_impl&lt; OptionsT &gt;::getIterator</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-detail/node-parent-access/#a7e19e7508415378ad9523e0339b23e22">llvm::ilist_detail::node_parent_access&lt; NodeTy, ParentTy &gt;::getParent</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#ac5804672fc0850438d63caec770647f8">II</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-gvnsink-cpp-/#a9510235b7453e621fdb6e0f6bc725acb">anonymous{GVNSink.cpp}::isMemoryInst</a>, <a href="#a8e7a1f80b6a1b4eb63fcff1619fd4207">lookupOrAdd</a> and <a href="/web-llvm/docs/api/classes/llvm/callbase/#a857a8c38e4856efec047cc914c25b692">llvm::CallBase::onlyReadsMemory</a>.</p>

</div>
</div>

### lookup() {#a13da6163075a3bb48f31b83d79a4fe54}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t anonymous{GVNSink.cpp}::ValueTable::lookup (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
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

<p>Returns the value number of the specified value.</p>


<p>Fails if the value has not yet been numbered.</p>


<p>Definition at line 548 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/gvnsink-cpp">GVNSink.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>

</div>
</div>

### lookupOrAdd() {#a8e7a1f80b6a1b4eb63fcff1619fd4207}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t anonymous{GVNSink.cpp}::ValueTable::lookupOrAdd (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
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

<p>Returns the value number for the specified value, assigning it a new number if it did not have one before.</p>

<p>Definition at line 459 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/gvnsink-cpp">GVNSink.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/anonymous-gvnsink-cpp-/instructionuseexpr/#a20a441ccd5f66dd021f4878259b2c74f">anonymous{GVNSink.cpp}::InstructionUseExpr::getHashValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ae42219072d798876e6b08e6b78614ff6">H</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a> and <a href="#a8e7a1f80b6a1b4eb63fcff1619fd4207">lookupOrAdd</a>.</p>


<p>Referenced by <a href="#a0f202a9387b6d7a60044c0ea986e7cb4">getMemoryUseOrder</a> and <a href="#a8e7a1f80b6a1b4eb63fcff1619fd4207">lookupOrAdd</a>.</p>

</div>
</div>

### setReachableBBs() {#a718cb8936fc783fdd1706fa7f4a4a6a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{GVNSink.cpp}::ValueTable::setReachableBBs (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/anonymous-gvnsink-cpp-/#ae392bfb5a30a6ff3655f1620fa6c86c2">BasicBlocksSet</a> &amp; ReachableBBs)</td>
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

<p>Set basic blocks reachable from entry block.</p>

<p>Definition at line 453 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/gvnsink-cpp">GVNSink.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### createExpr() {#a9f6ebb99afcfcfa05abe500e3898dc5a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstructionUseExpr * anonymous{GVNSink.cpp}::ValueTable::createExpr (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I)</td>
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

<p>Create an expression for I based on its opcode and its uses.</p>


<p>If I touches or reads memory, the expression is also based upon its memory order - see <span class="doxyComputerOutput"><a href="#a0f202a9387b6d7a60044c0ea986e7cb4">getMemoryUseOrder()</a></span>.</p>


<p>Definition at line 425 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/gvnsink-cpp">GVNSink.cpp</a>.</p>

</div>
</div>

### createMemoryExpr() {#ad0a8f1fd82eae5a8afd61ba277e12d4f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Inst&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstructionUseExpr * anonymous{GVNSink.cpp}::ValueTable::createMemoryExpr (Inst * I)</td>
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

<p>Helper to compute the value number for a memory instruction (LoadInst/StoreInst), including checking the memory ordering and volatility.</p>

<p>Definition at line 441 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/gvnsink-cpp">GVNSink.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Allocator {#a7fa61ea6a64443a75c1cdf4728783620}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BumpPtrAllocator anonymous{GVNSink.cpp}::ValueTable::Allocator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 417 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/gvnsink-cpp">GVNSink.cpp</a>.</p>

</div>
</div>

### ExpressionNumbering {#a838d2e5bcea50e83e44752f016f55155}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;GVNExpression::Expression *, uint32_t&gt; anonymous{GVNSink.cpp}::ValueTable::ExpressionNumbering</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 415 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/gvnsink-cpp">GVNSink.cpp</a>.</p>

</div>
</div>

### HashNumbering {#a0fbe44c28be0260b808b450df1aa2350}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;size_t, uint32_t&gt; anonymous{GVNSink.cpp}::ValueTable::HashNumbering</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 416 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/gvnsink-cpp">GVNSink.cpp</a>.</p>

</div>
</div>

### nextValueNumber {#a412271abefd6f2f595fb3f06704d84a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t anonymous{GVNSink.cpp}::ValueTable::nextValueNumber = 1</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 419 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/gvnsink-cpp">GVNSink.cpp</a>.</p>

</div>
</div>

### ReachableBBs {#a880df0c7684879c1fe558d74aea7029f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BasicBlocksSet anonymous{GVNSink.cpp}::ValueTable::ReachableBBs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 420 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/gvnsink-cpp">GVNSink.cpp</a>.</p>

</div>
</div>

### Recycler {#a056cb9cef8cb1618eea2577ad5cdc666}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRecycler&lt;Value *&gt; anonymous{GVNSink.cpp}::ValueTable::Recycler</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 418 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/gvnsink-cpp">GVNSink.cpp</a>.</p>

</div>
</div>

### ValueNumbering {#a8e385dd8db230292ab4bc9c1e98a701f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;Value *, uint32_t&gt; anonymous{GVNSink.cpp}::ValueTable::ValueNumbering</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 414 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/gvnsink-cpp">GVNSink.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/gvnsink-cpp">GVNSink.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>

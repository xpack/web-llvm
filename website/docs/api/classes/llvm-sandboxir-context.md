---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/sandboxir/context
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `Context` Class



## Declaration

<div class="doxyDeclaration">
class llvm::sandboxir::Context { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/context-h">llvm/SandboxIR/Context.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f62affc82baaf733e44c5ca0f00cc9f">EraseInstrCallback</a> = std::function&lt; void(<a href="/web-llvm/docs/api/classes/llvm/sandboxir/instruction">Instruction</a> *)&gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a06bfbc81312ccda16a100c5ecdd5e61b">CreateInstrCallback</a> = std::function&lt; void(<a href="/web-llvm/docs/api/classes/llvm/sandboxir/instruction">Instruction</a> *)&gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac599f2016856411c44ff01c84dc9e62f">MoveInstrCallback</a> = std::function&lt; void(<a href="/web-llvm/docs/api/classes/llvm/sandboxir/instruction">Instruction</a> *, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> BBIterator &amp;)&gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a18dba29b4f3e91d6d2bc53472a6bb7cc">Type</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>MessagePack types as defined in the standard, with the exception of Integer being divided into a signed Int and unsigned UInt variant in order to map directly to C++ types. <a href="#a18dba29b4f3e91d6d2bc53472a6bb7cc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb7721cfea46ef9d51188ae7df27cf17">PointerType</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaa06efd1401ee152456eb22a467ddcb3">IntegerType</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae4d805ae7a1735765e14164b42b58cce">StructType</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aae6f9325706131f3b6fb8accb1508d76">Region</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3381efbbe99b7e9422599a34d1803e9d">IRSnapshotChecker</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a87273cb892a8182f137567e6b631695e">Instruction</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ba342032565c38739ecd8eff3c121c1">EraseFromParent</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc0f7da619e9e72510dc07ed7b5ff6d8">Utils</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af10fa975001cd000bc6aaa88267d970f">BasicBlock</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Various leaf nodes. <a href="#af10fa975001cd000bc6aaa88267d970f">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9bc6da7c6106e68fc33365a069590be7">Context</a> (LLVMContext &amp;LLVMCtx)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac9e6df5d708091ea52c804cddfa13e76">~Context</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa15843bad9969a3db23465cd9da678b0">clear</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Clears function-level state. <a href="#aa15843bad9969a3db23465cd9da678b0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sandboxir/tracker">Tracker</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af021d63b7832bc9cba10fdb5ccd7e925">getTracker</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acbf3fc5379cf327e9cdd7594a772be61">save</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Convenience function for <span class="doxyComputerOutput"><a href="#af021d63b7832bc9cba10fdb5ccd7e925">getTracker()</a>.<a href="#acbf3fc5379cf327e9cdd7594a772be61">save()</a></span> <a href="#acbf3fc5379cf327e9cdd7594a772be61">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab60fe9b3dff3878469ab487428930acb">revert</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Convenience function for <span class="doxyComputerOutput"><a href="#af021d63b7832bc9cba10fdb5ccd7e925">getTracker()</a>.<a href="#ab60fe9b3dff3878469ab487428930acb">revert()</a></span> <a href="#ab60fe9b3dff3878469ab487428930acb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b033605d86bddde04ddf62e47aea332">accept</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Convenience function for <span class="doxyComputerOutput"><a href="#af021d63b7832bc9cba10fdb5ccd7e925">getTracker()</a>.<a href="#a6b033605d86bddde04ddf62e47aea332">accept()</a></span> <a href="#a6b033605d86bddde04ddf62e47aea332">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sandboxir/value">sandboxir::Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2dee21c5ed6d922ac4567a4fcd58a412">getValue</a> (llvm::Value *V) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sandboxir/value">sandboxir::Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67b2e6dc3f689b0f00dcf30f2e6a9c40">getValue</a> (const llvm::Value *V) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sandboxir/module">Module</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4132ef295dfc5dc3e53cfb4c36ae8e7e">getModule</a> (llvm::Module *LLVMM) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sandboxir/module">Module</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b26362d79d2939a5341e36e20f3a13a">getOrCreateModule</a> (llvm::Module *LLVMM)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sandboxir/type">Type</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d72c7051da5356cbfbfa16ecb7dca8a">getType</a> (llvm::Type *LLVMTy)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sandboxir/function">Function</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae78048f8d05be4c2b2c20435114b4753">createFunction</a> (llvm::Function *F)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a <a href="/web-llvm/docs/api/classes/llvm/sandboxir/function">sandboxir::Function</a> for an existing LLVM IR <span class="doxyComputerOutput">F</span>, including all blocks and instructions. <a href="#ae78048f8d05be4c2b2c20435114b4753">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sandboxir/module">Module</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2604f458da0e7d0a33702d7d66d660dc">createModule</a> (llvm::Module *LLVMM)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a <a href="/web-llvm/docs/api/classes/llvm/sandboxir/module">sandboxir::Module</a> corresponding to <span class="doxyComputerOutput">LLVMM</span>. <a href="#a2604f458da0e7d0a33702d7d66d660dc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afaf17d4dff8ccecdf1614ade84b34083">getNumValues</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>\Returns the number of values registered with <a href="/web-llvm/docs/api/classes/llvm/sandboxir/context">Context</a>. <a href="#afaf17d4dff8ccecdf1614ade84b34083">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sandboxir/context/callbackid">CallbackID</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af6d2670f4ff31e843f297ce7d3f7e157">registerEraseInstrCallback</a> (EraseInstrCallback CB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/register">Register</a> a callback that gets called when a SandboxIR instruction is about to be removed from its parent. <a href="#af6d2670f4ff31e843f297ce7d3f7e157">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aee83fd7e06567cc8d42c29f899322e67">unregisterEraseInstrCallback</a> (CallbackID ID)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sandboxir/context/callbackid">CallbackID</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a98c73743a3ddaad3668316f0a60b5dc4">registerCreateInstrCallback</a> (CreateInstrCallback CB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/register">Register</a> a callback that gets called right after a SandboxIR instruction is created. <a href="#a98c73743a3ddaad3668316f0a60b5dc4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaf860dfa8b51917f45c740cdc3741acc">unregisterCreateInstrCallback</a> (CallbackID ID)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sandboxir/context/callbackid">CallbackID</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af134e2ec0c001e0137342f53b89db9dc">registerMoveInstrCallback</a> (MoveInstrCallback CB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/register">Register</a> a callback that gets called when a SandboxIR instruction is about to be moved. <a href="#af134e2ec0c001e0137342f53b89db9dc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acbd86cf965d05c6e57657855023213e1">unregisterMoveInstrCallback</a> (CallbackID ID)</td>
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

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/sandboxir/value">Value</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb5c0771d9a9a847440aad09836e1b91">detachLLVMValue</a> (llvm::Value *V)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remove <span class="doxyComputerOutput">V</span> from the maps and returns the unique_ptr. <a href="#afb5c0771d9a9a847440aad09836e1b91">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/sandboxir/value">Value</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaf57bef4561e6ae8cdd300ef312a2ea4">detach</a> (Value *V)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remove <span class="doxyComputerOutput">SBV</span> from all SandboxIR maps and stop owning it. <a href="#aaf57bef4561e6ae8cdd300ef312a2ea4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sandboxir/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#add6c98d077e2f344b4d49266a2692696">registerValue</a> (std::unique_ptr&lt; Value &gt; &amp;&amp;VPtr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Take ownership of VPtr and store it in <span class="doxyComputerOutput">LLVMValueToValueMap</span>. <a href="#add6c98d077e2f344b4d49266a2692696">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sandboxir/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adad27d8740783e65067b7c2ad286aa38">getOrCreateValueInternal</a> (llvm::Value *V, llvm::User *U=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is the actual function that creates sandboxir values for <span class="doxyComputerOutput">V</span>, and among others handles all instruction types. <a href="#adad27d8740783e65067b7c2ad286aa38">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sandboxir/argument">Argument</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a306a360f0d3259eb92660d80036b9b56">getOrCreateArgument</a> (llvm::Argument *LLVMArg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get or create a <a href="/web-llvm/docs/api/classes/llvm/sandboxir/argument">sandboxir::Argument</a> for an existing LLVM IR <span class="doxyComputerOutput">LLVMArg</span>. <a href="#a306a360f0d3259eb92660d80036b9b56">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sandboxir/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acfec3e7998ff90624e6f88e517464dd2">getOrCreateValue</a> (llvm::Value *LLVMV)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get or create a <a href="/web-llvm/docs/api/classes/llvm/sandboxir/value">sandboxir::Value</a> for an existing LLVM IR <span class="doxyComputerOutput">LLVMV</span>. <a href="#acfec3e7998ff90624e6f88e517464dd2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sandboxir/constant">Constant</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7bf97c49fc62d8d7b10f346d1887c727">getOrCreateConstant</a> (llvm::Constant *LLVMC)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get or create a <a href="/web-llvm/docs/api/classes/llvm/sandboxir/constant">sandboxir::Constant</a> from an existing LLVM IR <span class="doxyComputerOutput">LLVMC</span>. <a href="#a7bf97c49fc62d8d7b10f346d1887c727">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3bd7534254b9665d9a49781b169ba2f7">runEraseInstrCallbacks</a> (Instruction *I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a60377c60e9abe2602cd153de0c991ca4">runCreateInstrCallbacks</a> (Instruction *I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adacbde8e548ad9d7fb7681d21866cc29">runMoveInstrCallbacks</a> (Instruction *I, const BBIterator &amp;Where)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sandboxir/basicblock">BasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a008a32bf404093142fba745ed3ab0918">createBasicBlock</a> (llvm::BasicBlock *BB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a <a href="/web-llvm/docs/api/classes/llvm/sandboxir/basicblock">sandboxir::BasicBlock</a> for an existing LLVM IR <span class="doxyComputerOutput">BB</span>. <a href="#a008a32bf404093142fba745ed3ab0918">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">auto &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4cb8dee2d7485de19c8f2029b26507d7">getLLVMIRBuilder</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sandboxir/vaarginst">VAArgInst</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4ca2867d5a1f665c28b44561e0171446">createVAArgInst</a> (llvm::VAArgInst *SI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sandboxir/freezeinst">FreezeInst</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9474b2572efbad4c603f6f316c190960">createFreezeInst</a> (llvm::FreezeInst *SI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sandboxir/fenceinst">FenceInst</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad32b60707d80f6067a0ac52278b8f1f4">createFenceInst</a> (llvm::FenceInst *SI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sandboxir/selectinst">SelectInst</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae914556359efbcbcd9f90eca07f822ec">createSelectInst</a> (llvm::SelectInst *SI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sandboxir/insertelementinst">InsertElementInst</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae23e1112f3af74c9caf9ec9c147a99fa">createInsertElementInst</a> (llvm::InsertElementInst *IEI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sandboxir/extractelementinst">ExtractElementInst</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7951c687043d2620c902e9bfa5eac56f">createExtractElementInst</a> (llvm::ExtractElementInst *EEI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sandboxir/shufflevectorinst">ShuffleVectorInst</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8372a0db9a902956a6b93ba28739989f">createShuffleVectorInst</a> (llvm::ShuffleVectorInst *SVI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sandboxir/extractvalueinst">ExtractValueInst</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab02a987dcbbb52bd5ca013939320377a">createExtractValueInst</a> (llvm::ExtractValueInst *IVI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sandboxir/insertvalueinst">InsertValueInst</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a62816dedba2be083d1f90c92fa30857e">createInsertValueInst</a> (llvm::InsertValueInst *IVI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sandboxir/branchinst">BranchInst</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7f3d0f72956a57123d00a8d6b3854aae">createBranchInst</a> (llvm::BranchInst *I)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sandboxir/loadinst">LoadInst</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8f0aa5a68819eb79b24b6d39aa768105">createLoadInst</a> (llvm::LoadInst *LI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sandboxir/storeinst">StoreInst</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb92f16e9c77c403a302f721e6af7f28">createStoreInst</a> (llvm::StoreInst *SI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sandboxir/returninst">ReturnInst</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a39fd9f172fd1f91f62775e710cc5e1af">createReturnInst</a> (llvm::ReturnInst *I)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sandboxir/callinst">CallInst</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad6917b72e0fc9300687d07a77addb610">createCallInst</a> (llvm::CallInst *I)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sandboxir/invokeinst">InvokeInst</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adbf6b5b8d208e62c40f1db873ac4f695">createInvokeInst</a> (llvm::InvokeInst *I)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sandboxir/callbrinst">CallBrInst</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2458ac81cb773c5f611902e443dba72a">createCallBrInst</a> (llvm::CallBrInst *I)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sandboxir/landingpadinst">LandingPadInst</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adfb0b5c39ad248a5bdc11755e80cf4d9">createLandingPadInst</a> (llvm::LandingPadInst *I)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sandboxir/catchpadinst">CatchPadInst</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9fa2f280a391ec59ffde55f13982f705">createCatchPadInst</a> (llvm::CatchPadInst *I)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sandboxir/cleanuppadinst">CleanupPadInst</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc1515d9b18eacaa0259cf6910d2f10b">createCleanupPadInst</a> (llvm::CleanupPadInst *I)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sandboxir/catchreturninst">CatchReturnInst</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abd2d5f2181ea45bcc683738c0090e9de">createCatchReturnInst</a> (llvm::CatchReturnInst *I)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sandboxir/cleanupreturninst">CleanupReturnInst</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4d48e0c5e5e71b02f74919e213493b30">createCleanupReturnInst</a> (llvm::CleanupReturnInst *I)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sandboxir/getelementptrinst">GetElementPtrInst</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a13cdb8a5d527cb1d32c4a2a702956ff1">createGetElementPtrInst</a> (llvm::GetElementPtrInst *I)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sandboxir/catchswitchinst">CatchSwitchInst</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abde9ca05d3c36a4db633dd9329c4de7a">createCatchSwitchInst</a> (llvm::CatchSwitchInst *I)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sandboxir/resumeinst">ResumeInst</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aee320c8b43dc8aa050750db45f7debca">createResumeInst</a> (llvm::ResumeInst *I)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sandboxir/switchinst">SwitchInst</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad8686c9916cfd1debacae95485f75feb">createSwitchInst</a> (llvm::SwitchInst *I)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sandboxir/unaryoperator">UnaryOperator</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adacedc9fad9cf7172ff2c3dac0cf62c9">createUnaryOperator</a> (llvm::UnaryOperator *I)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sandboxir/binaryoperator">BinaryOperator</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a84f542b398fe0517fc1973bcf022500d">createBinaryOperator</a> (llvm::BinaryOperator *I)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sandboxir/atomicrmwinst">AtomicRMWInst</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6160a35b731fb9211dba3730f7c449b4">createAtomicRMWInst</a> (llvm::AtomicRMWInst *I)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sandboxir/atomiccmpxchginst">AtomicCmpXchgInst</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af3ea0b86a033cba8b1b853a84d9a3999">createAtomicCmpXchgInst</a> (llvm::AtomicCmpXchgInst *I)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sandboxir/allocainst">AllocaInst</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a56cfb0f39f439788ea2856c0b1e4ee4d">createAllocaInst</a> (llvm::AllocaInst *I)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sandboxir/castinst">CastInst</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab948f8007dc5f505859efec6e6925541">createCastInst</a> (llvm::CastInst *I)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sandboxir/phinode">PHINode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a96b0b98ca8bba81133d5d60453babfec">createPHINode</a> (llvm::PHINode *I)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sandboxir/unreachableinst">UnreachableInst</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af306103547e43fc5c0b0b388218f4e08">createUnreachableInst</a> (llvm::UnreachableInst *UI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sandboxir/cmpinst">CmpInst</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1cb8188a6775c87364591b658d45c27f">createCmpInst</a> (llvm::CmpInst *I)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sandboxir/icmpinst">ICmpInst</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac5cf217b197dfc91bb5e24eff8ec1a6">createICmpInst</a> (llvm::ICmpInst *I)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sandboxir/fcmpinst">FCmpInst</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f4742f92fa2e51ff7486abb938073c4">createFCmpInst</a> (llvm::FCmpInst *I)</td>
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

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aef9f3a49744b7209b0592dd5315a79be">LLVMCtx</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sandboxir/tracker">Tracker</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a86e4b065b61d613fd23434a2b80da629">IRTracker</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">llvm::Value</a> *, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/sandboxir/value">Value</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a91988130fe6107522da95b9796016deb">LLVMValueToValueMap</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Maps LLVM <a href="/web-llvm/docs/api/classes/llvm/sandboxir/value">Value</a> to the corresponding <a href="/web-llvm/docs/api/classes/llvm/sandboxir/value">sandboxir::Value</a>. <a href="#a91988130fe6107522da95b9796016deb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/module">llvm::Module</a> *, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/sandboxir/module">Module</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab97a411015236a1083cdbc4672024c99">LLVMModuleToModuleMap</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Maps an LLVM <a href="/web-llvm/docs/api/classes/llvm/sandboxir/module">Module</a> to the corresponding <a href="/web-llvm/docs/api/classes/llvm/sandboxir/module">sandboxir::Module</a>. <a href="#ab97a411015236a1083cdbc4672024c99">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/type">llvm::Type</a> *, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/sandboxir/type">Type</a>, <a href="/web-llvm/docs/api/structs/llvm/sandboxir/context/typedeleter">TypeDeleter</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6977d1878b8588984c79b6d940b1c2d4">LLVMTypeToTypeMap</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Maps LLVM <a href="/web-llvm/docs/api/classes/llvm/sandboxir/type">Type</a> to the corresonding <a href="/web-llvm/docs/api/classes/llvm/sandboxir/type">sandboxir::Type</a>. <a href="#a6977d1878b8588984c79b6d940b1c2d4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mapvector">MapVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sandboxir/context/callbackid">CallbackID</a>, <a href="#a6f62affc82baaf733e44c5ca0f00cc9f">EraseInstrCallback</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2bde7d17436eff7df25a72ba26e1aa2f">EraseInstrCallbacks</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Callbacks called when an IR instruction is about to get erased. <a href="#a2bde7d17436eff7df25a72ba26e1aa2f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mapvector">MapVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sandboxir/context/callbackid">CallbackID</a>, <a href="#a06bfbc81312ccda16a100c5ecdd5e61b">CreateInstrCallback</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1546108265ad8c465a33dff7b7454dd5">CreateInstrCallbacks</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Callbacks called when an IR instruction is about to get created. <a href="#a1546108265ad8c465a33dff7b7454dd5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mapvector">MapVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sandboxir/context/callbackid">CallbackID</a>, <a href="#ac599f2016856411c44ff01c84dc9e62f">MoveInstrCallback</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aae8fca181738a0996766c6a1dec68c50">MoveInstrCallbacks</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Callbacks called when an IR instruction is about to get moved. <a href="#aae8fca181738a0996766c6a1dec68c50">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sandboxir/context/callbackid/#a240e6c5e6937ebc398e90662020a62fa">CallbackID::ValTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7556f470daa8373b7f866517a684dc4e">NextCallbackID</a> = 1</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A counter used for assigning callback IDs during registration. <a href="#a7556f470daa8373b7f866517a684dc4e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/irbuilder">IRBuilder</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/constantfolder">ConstantFolder</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a26a7b32395ac524ee1bf2797f0461ebd">LLVMIRBuilder</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">friend</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aae6c786185b49400eea9f348cb08fae8">VAArgInst</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">friend</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac79c0b986194e0535feedaa98c1818d0">FreezeInst</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">friend</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac70ae476798a68bcc024ed1dc226b9ad">FenceInst</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">friend</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaed74093256ebc989231ae246c2a0bbf">SelectInst</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">friend</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aecacd2aeb779f0c15298390ed8556d82">InsertElementInst</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">friend</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4812224e74f991f4093975f54f5db90d">ExtractElementInst</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">friend</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aae53c4d91c893229f149bbad96f52bbd">ShuffleVectorInst</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">friend</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a64bb275e2ec1ce6ad350c8976dd89d1d">ExtractValueInst</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">friend</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a75e893f51915ab1413a9a1a32419de6e">InsertValueInst</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">friend</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abda2123fd114da11af7365d87c770349">BranchInst</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">friend</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec18de7f11e2bb7b92ccdac9ee939b8d">LoadInst</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">friend</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a30505b071682ba3d6a2d8c9e3a1873d4">StoreInst</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">friend</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab8e18f2b60b915a353326b5a71c45ece">ReturnInst</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">friend</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aad6bb4ce3959458d2ea354d18043f2a0">CallInst</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">friend</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a93d94c872010058a3f58409b0ac16be7">InvokeInst</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">friend</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af9d72d9dfe9616b96048e1ab97063b37">CallBrInst</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">friend</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a070f84e27810ea5314794b0e0728f98f">LandingPadInst</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">friend</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a85794a7f47276252a7548196a374b57e">CatchPadInst</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">friend</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab3135f4fdae98b5bbf5c7917fa290cd">CleanupPadInst</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">friend</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a28a160dd7f57a92556d0f95787850a81">CatchReturnInst</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">friend</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa4f9f21a8f7cf3ede8e6c8b674ddf134">CleanupReturnInst</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">friend</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af52100dcbd76cbca1304bc6df9e080b4">GetElementPtrInst</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">friend</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2a09fd32a1dc8482d4b36e4e62c9f0f4">CatchSwitchInst</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">friend</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab1b980fd1d7d17d1426067bdc7f23752">ResumeInst</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">friend</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac669814186e6e601ef4f340be89cb142">SwitchInst</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">friend</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a59c4491d55e6e3eb33f888e2446fabd0">UnaryOperator</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">friend</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad67b2d1be52ca8bafe68082d597db450">BinaryOperator</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">friend</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abfbbc21f9fc5067c81720ce1b1e652b5">AtomicRMWInst</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">friend</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aed4242bc859436c33432187864aa8c9e">AtomicCmpXchgInst</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">friend</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3d3f78c2a93cab58fca043571501e7e1">AllocaInst</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">friend</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7b3f8365e6296948cbe462d6fe0d3ca9">CastInst</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">friend</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0a456376211041199b96cb4c83b32b90">PHINode</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">friend</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a192f8faa22db79e377671ecc70defaa0">UnreachableInst</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">friend</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6d3b6192dfc396b5d5fcb06689a62bcf">CmpInst</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">friend</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a63e49cc3b84ac25b6367b215371ebe89">ICmpInst</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">friend</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adc2a63f70133eaf0b6aaa78a386b15b4">FCmpInst</a></td>
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


<p>Definition at line 30 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/context-h">Context.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### CreateInstrCallback {#a06bfbc81312ccda16a100c5ecdd5e61b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::sandboxir::Context::CreateInstrCallback =  std::function&lt;void(Instruction *)&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/context-h">Context.h</a>.</p>

</div>
</div>

### EraseInstrCallback {#a6f62affc82baaf733e44c5ca0f00cc9f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::sandboxir::Context::EraseInstrCallback =  std::function&lt;void(Instruction *)&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 33 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/context-h">Context.h</a>.</p>

</div>
</div>

### MoveInstrCallback {#ac599f2016856411c44ff01c84dc9e62f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::sandboxir::Context::MoveInstrCallback = 
      std::function&lt;void(Instruction *, const BBIterator &amp;)&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/context-h">Context.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Friends

### BasicBlock {#af10fa975001cd000bc6aaa88267d970f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/sandboxir/basicblock">BasicBlock</a></td>
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

<p>Various leaf nodes.</p>

<p>Definition at line 140 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/context-h">Context.h</a>.</p>


<p>Reference <a href="#af10fa975001cd000bc6aaa88267d970f">BasicBlock</a>.</p>


<p>Referenced by <a href="#af10fa975001cd000bc6aaa88267d970f">BasicBlock</a> and <a href="#a008a32bf404093142fba745ed3ab0918">createBasicBlock</a>.</p>

</div>
</div>

### EraseFromParent {#a1ba342032565c38739ecd8eff3c121c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/sandboxir/erasefromparent">EraseFromParent</a></td>
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


<p>Definition at line 115 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/context-h">Context.h</a>.</p>


<p>Reference <a href="#a1ba342032565c38739ecd8eff3c121c1">EraseFromParent</a>.</p>


<p>Referenced by <a href="#a1ba342032565c38739ecd8eff3c121c1">EraseFromParent</a>.</p>

</div>
</div>

### Instruction {#a87273cb892a8182f137567e6b631695e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/sandboxir/instruction">Instruction</a></td>
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


<p>Definition at line 112 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/context-h">Context.h</a>.</p>


<p>Reference <a href="#a87273cb892a8182f137567e6b631695e">Instruction</a>.</p>


<p>Referenced by <a href="#a87273cb892a8182f137567e6b631695e">Instruction</a>, <a href="#a60377c60e9abe2602cd153de0c991ca4">runCreateInstrCallbacks</a>, <a href="#a3bd7534254b9665d9a49781b169ba2f7">runEraseInstrCallbacks</a>, <a href="#adacbde8e548ad9d7fb7681d21866cc29">runMoveInstrCallbacks</a> and <a href="#abc0f7da619e9e72510dc07ed7b5ff6d8">Utils</a>.</p>

</div>
</div>

### IntegerType {#aaa06efd1401ee152456eb22a467ddcb3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/sandboxir/integertype">IntegerType</a></td>
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


<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/context-h">Context.h</a>.</p>


<p>Reference <a href="#aaa06efd1401ee152456eb22a467ddcb3">IntegerType</a>.</p>


<p>Referenced by <a href="#aaa06efd1401ee152456eb22a467ddcb3">IntegerType</a>.</p>

</div>
</div>

### IRSnapshotChecker {#a3381efbbe99b7e9422599a34d1803e9d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/sandboxir/irsnapshotchecker">IRSnapshotChecker</a></td>
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


<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/context-h">Context.h</a>.</p>


<p>Reference <a href="#a3381efbbe99b7e9422599a34d1803e9d">IRSnapshotChecker</a>.</p>


<p>Referenced by <a href="#a3381efbbe99b7e9422599a34d1803e9d">IRSnapshotChecker</a>.</p>

</div>
</div>

### PointerType {#abb7721cfea46ef9d51188ae7df27cf17}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/sandboxir/pointertype">PointerType</a></td>
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


<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/context-h">Context.h</a>.</p>


<p>Reference <a href="#abb7721cfea46ef9d51188ae7df27cf17">PointerType</a>.</p>


<p>Referenced by <a href="#abb7721cfea46ef9d51188ae7df27cf17">PointerType</a>.</p>

</div>
</div>

### Region {#aae6f9325706131f3b6fb8accb1508d76}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/sandboxir/region">Region</a></td>
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


<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/context-h">Context.h</a>.</p>


<p>Reference <a href="#aae6f9325706131f3b6fb8accb1508d76">Region</a>.</p>


<p>Referenced by <a href="#aae6f9325706131f3b6fb8accb1508d76">Region</a>.</p>

</div>
</div>

### StructType {#ae4d805ae7a1735765e14164b42b58cce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/sandboxir/structtype">StructType</a></td>
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


<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/context-h">Context.h</a>.</p>


<p>Reference <a href="#ae4d805ae7a1735765e14164b42b58cce">StructType</a>.</p>


<p>Referenced by <a href="#ae4d805ae7a1735765e14164b42b58cce">StructType</a>.</p>

</div>
</div>

### Type {#a18dba29b4f3e91d6d2bc53472a6bb7cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/sandboxir/type">Type</a></td>
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

<p>MessagePack types as defined in the standard, with the exception of Integer being divided into a signed Int and unsigned UInt variant in order to map directly to C++ types.</p>


<p>The types map onto corresponding union members of the <span class="doxyComputerOutput">Object</span> struct.</p>


<p>Definition at line 66 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/context-h">Context.h</a>.</p>


<p>Reference <a href="#a18dba29b4f3e91d6d2bc53472a6bb7cc">Type</a>.</p>


<p>Referenced by <a href="#a5d72c7051da5356cbfbfa16ecb7dca8a">getType</a>, <a href="/web-llvm/docs/api/structs/llvm/sandboxir/context/typedeleter/#a1b8c5479a004039c52b83410ca34f8a3">llvm::sandboxir::Context::TypeDeleter::operator()</a> and <a href="#a18dba29b4f3e91d6d2bc53472a6bb7cc">Type</a>.</p>

</div>
</div>

### Utils {#abc0f7da619e9e72510dc07ed7b5ff6d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/sandboxir/utils">Utils</a></td>
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


<p>Definition at line 127 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/context-h">Context.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a87273cb892a8182f137567e6b631695e">Instruction</a> and <a href="#abc0f7da619e9e72510dc07ed7b5ff6d8">Utils</a>.</p>


<p>Referenced by <a href="#abc0f7da619e9e72510dc07ed7b5ff6d8">Utils</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### Context() {#a9bc6da7c6106e68fc33365a069590be7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::sandboxir::Context::Context (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; LLVMCtx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 219 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/context-h">Context.h</a>, definition at line 608 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/context-cpp">Context.cpp</a>.</p>


<p>References <a href="#a86e4b065b61d613fd23434a2b80da629">IRTracker</a>, <a href="#aef9f3a49744b7209b0592dd5315a79be">LLVMCtx</a> and <a href="#a26a7b32395ac524ee1bf2797f0461ebd">LLVMIRBuilder</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~Context() {#ac9e6df5d708091ea52c804cddfa13e76}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::sandboxir::Context::~Context ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 220 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/context-h">Context.h</a>, definition at line 612 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/context-cpp">Context.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### accept() {#a6b033605d86bddde04ddf62e47aea332}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::sandboxir::Context::accept ()</td>
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

<p>Convenience function for <span class="doxyComputerOutput"><a href="#af021d63b7832bc9cba10fdb5ccd7e925">getTracker()</a>.<a href="#a6b033605d86bddde04ddf62e47aea332">accept()</a></span></p>

<p>Definition at line 230 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/context-h">Context.h</a>.</p>


<p>Reference <a href="#a86e4b065b61d613fd23434a2b80da629">IRTracker</a>.</p>

</div>
</div>

### clear() {#aa15843bad9969a3db23465cd9da678b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::sandboxir::Context::clear ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Clears function-level state.</p>

<p>Declaration at line 222 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/context-h">Context.h</a>, definition at line 614 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/context-cpp">Context.cpp</a>.</p>


<p>Reference <a href="#a91988130fe6107522da95b9796016deb">LLVMValueToValueMap</a>.</p>

</div>
</div>

### createFunction() {#ae78048f8d05be4c2b2c20435114b4753}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Function * llvm::sandboxir::Context::createFunction (<a href="/web-llvm/docs/api/classes/llvm/function">llvm::Function</a> * F)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create a <a href="/web-llvm/docs/api/classes/llvm/sandboxir/function">sandboxir::Function</a> for an existing LLVM IR <span class="doxyComputerOutput">F</span>, including all blocks and instructions.</p>


<p>This is the main API function for creating Sandbox IR. Note: this will not fully populate its parent module. The only globals that will be available are those used within the function.</p>


<p>Declaration at line 256 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/context-h">Context.h</a>, definition at line 636 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/context-cpp">Context.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3e627c32543ca70720c4270a8b11da3f">llvm::cast_or_null</a>, <a href="#a008a32bf404093142fba745ed3ab0918">createBasicBlock</a>, <a href="#aaf57bef4561e6ae8cdd300ef312a2ea4">detach</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="#a306a360f0d3259eb92660d80036b9b56">getOrCreateArgument</a>, <a href="#a8b26362d79d2939a5341e36e20f3a13a">getOrCreateModule</a>, <a href="#a2dee21c5ed6d922ac4567a4fcd58a412">getValue</a> and <a href="#add6c98d077e2f344b4d49266a2692696">registerValue</a>.</p>


<p>Referenced by <a href="#a2604f458da0e7d0a33702d7d66d660dc">createModule</a>.</p>

</div>
</div>

### createModule() {#a2604f458da0e7d0a33702d7d66d660dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Module * llvm::sandboxir::Context::createModule (<a href="/web-llvm/docs/api/classes/llvm/module">llvm::Module</a> * LLVMM)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create a <a href="/web-llvm/docs/api/classes/llvm/sandboxir/module">sandboxir::Module</a> corresponding to <span class="doxyComputerOutput">LLVMM</span>.</p>

<p>Declaration at line 259 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/context-h">Context.h</a>, definition at line 657 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/context-cpp">Context.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/module/#a696e00bbe45dcea703f433de7b38f699">llvm::Module::aliases</a>, <a href="#ae78048f8d05be4c2b2c20435114b4753">createFunction</a>, <a href="#a8b26362d79d2939a5341e36e20f3a13a">getOrCreateModule</a>, <a href="#acfec3e7998ff90624e6f88e517464dd2">getOrCreateValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9aa6dce3613309b3509522a00d6569bfa4cc6684df7b4a92b1dec6fce3264fac8">llvm::Global</a>, <a href="/web-llvm/docs/api/classes/llvm/module/#a8c41c9882546676724cb151c9ff8723e">llvm::Module::globals</a> and <a href="/web-llvm/docs/api/classes/llvm/module/#a336410508731bddd9add82863a37aaa0">llvm::Module::ifuncs</a>.</p>

</div>
</div>

### getModule() {#a4132ef295dfc5dc3e53cfb4c36ae8e7e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Module * llvm::sandboxir::Context::getModule (<a href="/web-llvm/docs/api/classes/llvm/module">llvm::Module</a> * LLVMM)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 237 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/context-h">Context.h</a>, definition at line 620 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/context-cpp">Context.cpp</a>.</p>


<p>Reference <a href="#ab97a411015236a1083cdbc4672024c99">LLVMModuleToModuleMap</a>.</p>

</div>
</div>

### getNumValues() {#afaf17d4dff8ccecdf1614ade84b34083}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::sandboxir::Context::getNumValues ()</td>
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

<p>\Returns the number of values registered with <a href="/web-llvm/docs/api/classes/llvm/sandboxir/context">Context</a>.</p>

<p>Definition at line 262 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/context-h">Context.h</a>.</p>


<p>Reference <a href="#a91988130fe6107522da95b9796016deb">LLVMValueToValueMap</a>.</p>

</div>
</div>

### getOrCreateModule() {#a8b26362d79d2939a5341e36e20f3a13a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Module * llvm::sandboxir::Context::getOrCreateModule (<a href="/web-llvm/docs/api/classes/llvm/module">llvm::Module</a> * LLVMM)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 239 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/context-h">Context.h</a>, definition at line 627 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/context-cpp">Context.cpp</a>.</p>


<p>References <a href="#ab97a411015236a1083cdbc4672024c99">LLVMModuleToModuleMap</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinecheckdebugify-cpp/#a85892acfa8970627e9bd9c9815f15c25">Module</a>.</p>


<p>Referenced by <a href="#ae78048f8d05be4c2b2c20435114b4753">createFunction</a> and <a href="#a2604f458da0e7d0a33702d7d66d660dc">createModule</a>.</p>

</div>
</div>

### getTracker() {#af021d63b7832bc9cba10fdb5ccd7e925}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Tracker &amp; llvm::sandboxir::Context::getTracker ()</td>
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



<p>Definition at line 224 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/context-h">Context.h</a>.</p>


<p>Reference <a href="#a86e4b065b61d613fd23434a2b80da629">IRTracker</a>.</p>


<p>Referenced by <a href="#add6c98d077e2f344b4d49266a2692696">registerValue</a>.</p>

</div>
</div>

### getType() {#a5d72c7051da5356cbfbfa16ecb7dca8a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type * llvm::sandboxir::Context::getType (<a href="/web-llvm/docs/api/classes/llvm/type">llvm::Type</a> * LLVMTy)</td>
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



<p>Definition at line 241 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/context-h">Context.h</a>.</p>


<p>References <a href="#a6977d1878b8588984c79b6d940b1c2d4">LLVMTypeToTypeMap</a> and <a href="#a18dba29b4f3e91d6d2bc53472a6bb7cc">Type</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/type/#a2f0388b8315300b55a8833caf090ef71">llvm::Type::containsNonLocalTargetExtType</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/vectortype/#ac96d755c768edd2cde7743330bbb6f5a">llvm::sandboxir::VectorType::getExtendedElementVectorType</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/vectortype/#a9cd3c5065659bc840e36b5a96ec94d96">llvm::sandboxir::VectorType::getHalfElementsVectorType</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/extractvalueinst/#a4e6ed8a1c14cfbc9d22aa336c96e4e0b">llvm::sandboxir::ExtractValueInst::getIndexedType</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/vectortype/#a78f34fdeeb7b2cc30adc895344d8df0f">llvm::sandboxir::VectorType::getInteger</a> and <a href="/web-llvm/docs/api/classes/llvm/sandboxir/cmpinst/#a7b33bd9843f6f96a4f390a9314692657">llvm::sandboxir::CmpInst::makeCmpResultType</a>.</p>

</div>
</div>

### getValue() {#a2dee21c5ed6d922ac4567a4fcd58a412}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * llvm::sandboxir::Context::getValue (<a href="/web-llvm/docs/api/classes/llvm/value">llvm::Value</a> * V)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 232 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/context-h">Context.h</a>, definition at line 601 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/context-cpp">Context.cpp</a>.</p>


<p>Reference <a href="#a91988130fe6107522da95b9796016deb">LLVMValueToValueMap</a>.</p>


<p>Referenced by <a href="#a008a32bf404093142fba745ed3ab0918">createBasicBlock</a>, <a href="#ae78048f8d05be4c2b2c20435114b4753">createFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/dsolocalequivalent/#a66f628a21e67b68d6ae93a9f80bb4067">llvm::sandboxir::DSOLocalEquivalent::get</a>, <a href="#adad27d8740783e65067b7c2ad286aa38">getOrCreateValueInternal</a>, <a href="#a67b2e6dc3f689b0f00dcf30f2e6a9c40">getValue</a> and <a href="/web-llvm/docs/api/classes/llvm/sandboxir/blockaddress/#a095a6dbd20e2611d899aa9f03380a573">llvm::sandboxir::BlockAddress::lookup</a>.</p>

</div>
</div>

### getValue() {#a67b2e6dc3f689b0f00dcf30f2e6a9c40}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const sandboxir::Value * llvm::sandboxir::Context::getValue (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">llvm::Value</a> * V)</td>
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



<p>Definition at line 233 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/context-h">Context.h</a>.</p>


<p>Reference <a href="#a2dee21c5ed6d922ac4567a4fcd58a412">getValue</a>.</p>

</div>
</div>

### registerCreateInstrCallback() {#a98c73743a3ddaad3668316f0a60b5dc4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Context::CallbackID llvm::sandboxir::Context::registerCreateInstrCallback (<a href="#a06bfbc81312ccda16a100c5ecdd5e61b">CreateInstrCallback</a> CB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/register">Register</a> a callback that gets called right after a SandboxIR instruction is created.</p>


<p>Note that this will also be called when reverting the removal of an instruction. \Returns a callback <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> for later deregistration.</p>


<p>Declaration at line 275 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/context-h">Context.h</a>, definition at line 709 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/context-cpp">Context.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a1546108265ad8c465a33dff7b7454dd5">CreateInstrCallbacks</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sandboxir/#a790678138246125c75a8fa558d129310">llvm::sandboxir::MaxRegisteredCallbacks</a> and <a href="#a7556f470daa8373b7f866517a684dc4e">NextCallbackID</a>.</p>

</div>
</div>

### registerEraseInstrCallback() {#af6d2670f4ff31e843f297ce7d3f7e157}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Context::CallbackID llvm::sandboxir::Context::registerEraseInstrCallback (<a href="#a6f62affc82baaf733e44c5ca0f00cc9f">EraseInstrCallback</a> CB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/register">Register</a> a callback that gets called when a SandboxIR instruction is about to be removed from its parent.</p>


<p>Note that this will also be called when reverting the creation of an instruction. \Returns a callback <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> for later deregistration.</p>


<p>Declaration at line 268 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/context-h">Context.h</a>, definition at line 695 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/context-cpp">Context.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a2bde7d17436eff7df25a72ba26e1aa2f">EraseInstrCallbacks</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sandboxir/#a790678138246125c75a8fa558d129310">llvm::sandboxir::MaxRegisteredCallbacks</a> and <a href="#a7556f470daa8373b7f866517a684dc4e">NextCallbackID</a>.</p>

</div>
</div>

### registerMoveInstrCallback() {#af134e2ec0c001e0137342f53b89db9dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Context::CallbackID llvm::sandboxir::Context::registerMoveInstrCallback (<a href="#ac599f2016856411c44ff01c84dc9e62f">MoveInstrCallback</a> CB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/register">Register</a> a callback that gets called when a SandboxIR instruction is about to be moved.</p>


<p>Note that this will also be called when reverting a move. \Returns a callback <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> for later deregistration.</p>


<p>Declaration at line 281 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/context-h">Context.h</a>, definition at line 722 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/context-cpp">Context.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sandboxir/#a790678138246125c75a8fa558d129310">llvm::sandboxir::MaxRegisteredCallbacks</a>, <a href="#aae8fca181738a0996766c6a1dec68c50">MoveInstrCallbacks</a> and <a href="#a7556f470daa8373b7f866517a684dc4e">NextCallbackID</a>.</p>

</div>
</div>

### revert() {#ab60fe9b3dff3878469ab487428930acb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::sandboxir::Context::revert ()</td>
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

<p>Convenience function for <span class="doxyComputerOutput"><a href="#af021d63b7832bc9cba10fdb5ccd7e925">getTracker()</a>.<a href="#ab60fe9b3dff3878469ab487428930acb">revert()</a></span></p>

<p>Definition at line 228 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/context-h">Context.h</a>.</p>


<p>Reference <a href="#a86e4b065b61d613fd23434a2b80da629">IRTracker</a>.</p>

</div>
</div>

### save() {#acbf3fc5379cf327e9cdd7594a772be61}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::sandboxir::Context::save ()</td>
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

<p>Convenience function for <span class="doxyComputerOutput"><a href="#af021d63b7832bc9cba10fdb5ccd7e925">getTracker()</a>.<a href="#acbf3fc5379cf327e9cdd7594a772be61">save()</a></span></p>

<p>Definition at line 226 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/context-h">Context.h</a>.</p>


<p>Reference <a href="#a86e4b065b61d613fd23434a2b80da629">IRTracker</a>.</p>

</div>
</div>

### unregisterCreateInstrCallback() {#aaf860dfa8b51917f45c740cdc3741acc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::sandboxir::Context::unregisterCreateInstrCallback (<a href="/web-llvm/docs/api/classes/llvm/sandboxir/context/callbackid">CallbackID</a> ID)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 276 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/context-h">Context.h</a>, definition at line 716 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/context-cpp">Context.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a1546108265ad8c465a33dff7b7454dd5">CreateInstrCallbacks</a>.</p>

</div>
</div>

### unregisterEraseInstrCallback() {#aee83fd7e06567cc8d42c29f899322e67}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::sandboxir::Context::unregisterEraseInstrCallback (<a href="/web-llvm/docs/api/classes/llvm/sandboxir/context/callbackid">CallbackID</a> ID)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 269 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/context-h">Context.h</a>, definition at line 702 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/context-cpp">Context.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a2bde7d17436eff7df25a72ba26e1aa2f">EraseInstrCallbacks</a>.</p>

</div>
</div>

### unregisterMoveInstrCallback() {#acbd86cf965d05c6e57657855023213e1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::sandboxir::Context::unregisterMoveInstrCallback (<a href="/web-llvm/docs/api/classes/llvm/sandboxir/context/callbackid">CallbackID</a> ID)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 282 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/context-h">Context.h</a>, definition at line 729 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/context-cpp">Context.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#aae8fca181738a0996766c6a1dec68c50">MoveInstrCallbacks</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### createAllocaInst() {#a56cfb0f39f439788ea2856c0b1e4ee4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AllocaInst * llvm::sandboxir::Context::createAllocaInst (<a href="/web-llvm/docs/api/classes/llvm/allocainst">llvm::AllocaInst</a> * I)</td>
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



<p>Declaration at line 203 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/context-h">Context.h</a>, definition at line 581 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/context-cpp">Context.cpp</a>.</p>


<p>References <a href="#a3d3f78c2a93cab58fca043571501e7e1">AllocaInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="#add6c98d077e2f344b4d49266a2692696">registerValue</a>.</p>

</div>
</div>

### createAtomicCmpXchgInst() {#af3ea0b86a033cba8b1b853a84d9a3999}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AtomicCmpXchgInst * llvm::sandboxir::Context::createAtomicCmpXchgInst (<a href="/web-llvm/docs/api/classes/llvm/atomiccmpxchginst">llvm::AtomicCmpXchgInst</a> * I)</td>
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



<p>Declaration at line 201 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/context-h">Context.h</a>, definition at line 576 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/context-cpp">Context.cpp</a>.</p>


<p>References <a href="#aed4242bc859436c33432187864aa8c9e">AtomicCmpXchgInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="#add6c98d077e2f344b4d49266a2692696">registerValue</a>.</p>

</div>
</div>

### createAtomicRMWInst() {#a6160a35b731fb9211dba3730f7c449b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AtomicRMWInst * llvm::sandboxir::Context::createAtomicRMWInst (<a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst">llvm::AtomicRMWInst</a> * I)</td>
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



<p>Declaration at line 199 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/context-h">Context.h</a>, definition at line 571 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/context-cpp">Context.cpp</a>.</p>


<p>References <a href="#abfbbc21f9fc5067c81720ce1b1e652b5">AtomicRMWInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="#add6c98d077e2f344b4d49266a2692696">registerValue</a>.</p>

</div>
</div>

### createBasicBlock() {#a008a32bf404093142fba745ed3ab0918}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BasicBlock * llvm::sandboxir::Context::createBasicBlock (<a href="/web-llvm/docs/api/classes/llvm/basicblock">llvm::BasicBlock</a> * BB)</td>
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

<p>Create a <a href="/web-llvm/docs/api/classes/llvm/sandboxir/basicblock">sandboxir::BasicBlock</a> for an existing LLVM IR <span class="doxyComputerOutput">BB</span>.</p>


<p>This will also create all contents of the block.</p>


<p>Declaration at line 139 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/context-h">Context.h</a>, definition at line 421 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/context-cpp">Context.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#af10fa975001cd000bc6aaa88267d970f">BasicBlock</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#a2dee21c5ed6d922ac4567a4fcd58a412">getValue</a> and <a href="#add6c98d077e2f344b4d49266a2692696">registerValue</a>.</p>


<p>Referenced by <a href="#ae78048f8d05be4c2b2c20435114b4753">createFunction</a>.</p>

</div>
</div>

### createBinaryOperator() {#a84f542b398fe0517fc1973bcf022500d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BinaryOperator * llvm::sandboxir::Context::createBinaryOperator (<a href="/web-llvm/docs/api/classes/llvm/binaryoperator">llvm::BinaryOperator</a> * I)</td>
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



<p>Declaration at line 197 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/context-h">Context.h</a>, definition at line 567 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/context-cpp">Context.cpp</a>.</p>


<p>References <a href="#ad67b2d1be52ca8bafe68082d597db450">BinaryOperator</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="#add6c98d077e2f344b4d49266a2692696">registerValue</a>.</p>

</div>
</div>

### createBranchInst() {#a7f3d0f72956a57123d00a8d6b3854aae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BranchInst * llvm::sandboxir::Context::createBranchInst (<a href="/web-llvm/docs/api/classes/llvm/branchinst">llvm::BranchInst</a> * I)</td>
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



<p>Declaration at line 163 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/context-h">Context.h</a>, definition at line 483 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/context-cpp">Context.cpp</a>.</p>


<p>References <a href="#abda2123fd114da11af7365d87c770349">BranchInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a> and <a href="#add6c98d077e2f344b4d49266a2692696">registerValue</a>.</p>

</div>
</div>

### createCallBrInst() {#a2458ac81cb773c5f611902e443dba72a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CallBrInst * llvm::sandboxir::Context::createCallBrInst (<a href="/web-llvm/docs/api/classes/llvm/callbrinst">llvm::CallBrInst</a> * I)</td>
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



<p>Declaration at line 175 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/context-h">Context.h</a>, definition at line 513 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/context-cpp">Context.cpp</a>.</p>


<p>References <a href="#af9d72d9dfe9616b96048e1ab97063b37">CallBrInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="#add6c98d077e2f344b4d49266a2692696">registerValue</a>.</p>

</div>
</div>

### createCallInst() {#ad6917b72e0fc9300687d07a77addb610}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CallInst * llvm::sandboxir::Context::createCallInst (<a href="/web-llvm/docs/api/classes/llvm/callinst">llvm::CallInst</a> * I)</td>
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



<p>Declaration at line 171 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/context-h">Context.h</a>, definition at line 503 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/context-cpp">Context.cpp</a>.</p>


<p>References <a href="#aad6bb4ce3959458d2ea354d18043f2a0">CallInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="#add6c98d077e2f344b4d49266a2692696">registerValue</a>.</p>

</div>
</div>

### createCastInst() {#ab948f8007dc5f505859efec6e6925541}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CastInst * llvm::sandboxir::Context::createCastInst (<a href="/web-llvm/docs/api/classes/llvm/castinst">llvm::CastInst</a> * I)</td>
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



<p>Declaration at line 205 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/context-h">Context.h</a>, definition at line 585 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/context-cpp">Context.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#a7b3f8365e6296948cbe462d6fe0d3ca9">CastInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="#add6c98d077e2f344b4d49266a2692696">registerValue</a>.</p>

</div>
</div>

### createCatchPadInst() {#a9fa2f280a391ec59ffde55f13982f705}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CatchPadInst * llvm::sandboxir::Context::createCatchPadInst (<a href="/web-llvm/docs/api/classes/llvm/catchpadinst">llvm::CatchPadInst</a> * I)</td>
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



<p>Declaration at line 179 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/context-h">Context.h</a>, definition at line 527 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/context-cpp">Context.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#a85794a7f47276252a7548196a374b57e">CatchPadInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="#add6c98d077e2f344b4d49266a2692696">registerValue</a>.</p>

</div>
</div>

### createCatchReturnInst() {#abd2d5f2181ea45bcc683738c0090e9de}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CatchReturnInst * llvm::sandboxir::Context::createCatchReturnInst (<a href="/web-llvm/docs/api/classes/llvm/catchreturninst">llvm::CatchReturnInst</a> * I)</td>
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



<p>Declaration at line 183 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/context-h">Context.h</a>, definition at line 535 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/context-cpp">Context.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#a28a160dd7f57a92556d0f95787850a81">CatchReturnInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="#add6c98d077e2f344b4d49266a2692696">registerValue</a>.</p>

</div>
</div>

### createCatchSwitchInst() {#abde9ca05d3c36a4db633dd9329c4de7a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CatchSwitchInst * llvm::sandboxir::Context::createCatchSwitchInst (<a href="/web-llvm/docs/api/classes/llvm/catchswitchinst">llvm::CatchSwitchInst</a> * I)</td>
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



<p>Declaration at line 189 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/context-h">Context.h</a>, definition at line 551 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/context-cpp">Context.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#a2a09fd32a1dc8482d4b36e4e62c9f0f4">CatchSwitchInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="#add6c98d077e2f344b4d49266a2692696">registerValue</a>.</p>

</div>
</div>

### createCleanupPadInst() {#acc1515d9b18eacaa0259cf6910d2f10b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CleanupPadInst * llvm::sandboxir::Context::createCleanupPadInst (<a href="/web-llvm/docs/api/classes/llvm/cleanuppadinst">llvm::CleanupPadInst</a> * I)</td>
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



<p>Declaration at line 181 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/context-h">Context.h</a>, definition at line 531 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/context-cpp">Context.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#aab3135f4fdae98b5bbf5c7917fa290cd">CleanupPadInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="#add6c98d077e2f344b4d49266a2692696">registerValue</a>.</p>

</div>
</div>

### createCleanupReturnInst() {#a4d48e0c5e5e71b02f74919e213493b30}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CleanupReturnInst * llvm::sandboxir::Context::createCleanupReturnInst (<a href="/web-llvm/docs/api/classes/llvm/cleanupreturninst">llvm::CleanupReturnInst</a> * I)</td>
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



<p>Declaration at line 185 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/context-h">Context.h</a>, definition at line 540 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/context-cpp">Context.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#aa4f9f21a8f7cf3ede8e6c8b674ddf134">CleanupReturnInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="#add6c98d077e2f344b4d49266a2692696">registerValue</a>.</p>

</div>
</div>

### createCmpInst() {#a1cb8188a6775c87364591b658d45c27f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CmpInst * llvm::sandboxir::Context::createCmpInst (<a href="/web-llvm/docs/api/classes/llvm/cmpinst">llvm::CmpInst</a> * I)</td>
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



<p>Definition at line 211 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/context-h">Context.h</a>.</p>


<p>References <a href="#a6d3b6192dfc396b5d5fcb06689a62bcf">CmpInst</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### createExtractElementInst() {#a7951c687043d2620c902e9bfa5eac56f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ExtractElementInst * llvm::sandboxir::Context::createExtractElementInst (<a href="/web-llvm/docs/api/classes/llvm/extractelementinst">llvm::ExtractElementInst</a> * EEI)</td>
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



<p>Declaration at line 155 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/context-h">Context.h</a>, definition at line 451 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/context-cpp">Context.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#a4812224e74f991f4093975f54f5db90d">ExtractElementInst</a> and <a href="#add6c98d077e2f344b4d49266a2692696">registerValue</a>.</p>

</div>
</div>

### createExtractValueInst() {#ab02a987dcbbb52bd5ca013939320377a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ExtractValueInst * llvm::sandboxir::Context::createExtractValueInst (<a href="/web-llvm/docs/api/classes/llvm/extractvalueinst">llvm::ExtractValueInst</a> * IVI)</td>
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



<p>Declaration at line 159 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/context-h">Context.h</a>, definition at line 471 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/context-cpp">Context.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#a64bb275e2ec1ce6ad350c8976dd89d1d">ExtractValueInst</a> and <a href="#add6c98d077e2f344b4d49266a2692696">registerValue</a>.</p>

</div>
</div>

### createFCmpInst() {#a6f4742f92fa2e51ff7486abb938073c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FCmpInst * llvm::sandboxir::Context::createFCmpInst (<a href="/web-llvm/docs/api/classes/llvm/fcmpinst">llvm::FCmpInst</a> * I)</td>
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



<p>Declaration at line 215 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/context-h">Context.h</a>, definition at line 597 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/context-cpp">Context.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#adc2a63f70133eaf0b6aaa78a386b15b4">FCmpInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="#add6c98d077e2f344b4d49266a2692696">registerValue</a>.</p>

</div>
</div>

### createFenceInst() {#ad32b60707d80f6067a0ac52278b8f1f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FenceInst * llvm::sandboxir::Context::createFenceInst (<a href="/web-llvm/docs/api/classes/llvm/fenceinst">llvm::FenceInst</a> * SI)</td>
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



<p>Declaration at line 149 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/context-h">Context.h</a>, definition at line 440 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/context-cpp">Context.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#ac70ae476798a68bcc024ed1dc226b9ad">FenceInst</a> and <a href="#add6c98d077e2f344b4d49266a2692696">registerValue</a>.</p>

</div>
</div>

### createFreezeInst() {#a9474b2572efbad4c603f6f316c190960}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FreezeInst * llvm::sandboxir::Context::createFreezeInst (<a href="/web-llvm/docs/api/classes/llvm/freezeinst">llvm::FreezeInst</a> * SI)</td>
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



<p>Declaration at line 147 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/context-h">Context.h</a>, definition at line 435 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/context-cpp">Context.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#ac79c0b986194e0535feedaa98c1818d0">FreezeInst</a> and <a href="#add6c98d077e2f344b4d49266a2692696">registerValue</a>.</p>

</div>
</div>

### createGetElementPtrInst() {#a13cdb8a5d527cb1d32c4a2a702956ff1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GetElementPtrInst * llvm::sandboxir::Context::createGetElementPtrInst (<a href="/web-llvm/docs/api/classes/llvm/getelementptrinst">llvm::GetElementPtrInst</a> * I)</td>
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



<p>Declaration at line 187 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/context-h">Context.h</a>, definition at line 546 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/context-cpp">Context.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#af52100dcbd76cbca1304bc6df9e080b4">GetElementPtrInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="#add6c98d077e2f344b4d49266a2692696">registerValue</a>.</p>

</div>
</div>

### createICmpInst() {#aac5cf217b197dfc91bb5e24eff8ec1a6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ICmpInst * llvm::sandboxir::Context::createICmpInst (<a href="/web-llvm/docs/api/classes/llvm/icmpinst">llvm::ICmpInst</a> * I)</td>
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



<p>Declaration at line 213 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/context-h">Context.h</a>, definition at line 593 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/context-cpp">Context.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a63e49cc3b84ac25b6367b215371ebe89">ICmpInst</a> and <a href="#add6c98d077e2f344b4d49266a2692696">registerValue</a>.</p>

</div>
</div>

### createInsertElementInst() {#ae23e1112f3af74c9caf9ec9c147a99fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InsertElementInst * llvm::sandboxir::Context::createInsertElementInst (<a href="/web-llvm/docs/api/classes/llvm/insertelementinst">llvm::InsertElementInst</a> * IEI)</td>
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



<p>Declaration at line 153 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/context-h">Context.h</a>, definition at line 458 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/context-cpp">Context.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#aecacd2aeb779f0c15298390ed8556d82">InsertElementInst</a> and <a href="#add6c98d077e2f344b4d49266a2692696">registerValue</a>.</p>

</div>
</div>

### createInsertValueInst() {#a62816dedba2be083d1f90c92fa30857e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InsertValueInst * llvm::sandboxir::Context::createInsertValueInst (<a href="/web-llvm/docs/api/classes/llvm/insertvalueinst">llvm::InsertValueInst</a> * IVI)</td>
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



<p>Declaration at line 161 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/context-h">Context.h</a>, definition at line 477 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/context-cpp">Context.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#a75e893f51915ab1413a9a1a32419de6e">InsertValueInst</a> and <a href="#add6c98d077e2f344b4d49266a2692696">registerValue</a>.</p>

</div>
</div>

### createInvokeInst() {#adbf6b5b8d208e62c40f1db873ac4f695}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InvokeInst * llvm::sandboxir::Context::createInvokeInst (<a href="/web-llvm/docs/api/classes/llvm/invokeinst">llvm::InvokeInst</a> * I)</td>
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



<p>Declaration at line 173 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/context-h">Context.h</a>, definition at line 508 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/context-cpp">Context.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a93d94c872010058a3f58409b0ac16be7">InvokeInst</a> and <a href="#add6c98d077e2f344b4d49266a2692696">registerValue</a>.</p>

</div>
</div>

### createLandingPadInst() {#adfb0b5c39ad248a5bdc11755e80cf4d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LandingPadInst * llvm::sandboxir::Context::createLandingPadInst (<a href="/web-llvm/docs/api/classes/llvm/landingpadinst">llvm::LandingPadInst</a> * I)</td>
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



<p>Declaration at line 177 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/context-h">Context.h</a>, definition at line 523 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/context-cpp">Context.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a070f84e27810ea5314794b0e0728f98f">LandingPadInst</a> and <a href="#add6c98d077e2f344b4d49266a2692696">registerValue</a>.</p>

</div>
</div>

### createLoadInst() {#a8f0aa5a68819eb79b24b6d39aa768105}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LoadInst * llvm::sandboxir::Context::createLoadInst (<a href="/web-llvm/docs/api/classes/llvm/loadinst">llvm::LoadInst</a> * LI)</td>
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



<p>Declaration at line 165 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/context-h">Context.h</a>, definition at line 488 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/context-cpp">Context.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#aec18de7f11e2bb7b92ccdac9ee939b8d">LoadInst</a> and <a href="#add6c98d077e2f344b4d49266a2692696">registerValue</a>.</p>

</div>
</div>

### createPHINode() {#a96b0b98ca8bba81133d5d60453babfec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PHINode * llvm::sandboxir::Context::createPHINode (<a href="/web-llvm/docs/api/classes/llvm/phinode">llvm::PHINode</a> * I)</td>
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



<p>Declaration at line 207 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/context-h">Context.h</a>, definition at line 589 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/context-cpp">Context.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a0a456376211041199b96cb4c83b32b90">PHINode</a> and <a href="#add6c98d077e2f344b4d49266a2692696">registerValue</a>.</p>

</div>
</div>

### createResumeInst() {#aee320c8b43dc8aa050750db45f7debca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ResumeInst * llvm::sandboxir::Context::createResumeInst (<a href="/web-llvm/docs/api/classes/llvm/resumeinst">llvm::ResumeInst</a> * I)</td>
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



<p>Declaration at line 191 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/context-h">Context.h</a>, definition at line 555 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/context-cpp">Context.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#add6c98d077e2f344b4d49266a2692696">registerValue</a> and <a href="#ab1b980fd1d7d17d1426067bdc7f23752">ResumeInst</a>.</p>

</div>
</div>

### createReturnInst() {#a39fd9f172fd1f91f62775e710cc5e1af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ReturnInst * llvm::sandboxir::Context::createReturnInst (<a href="/web-llvm/docs/api/classes/llvm/returninst">llvm::ReturnInst</a> * I)</td>
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



<p>Declaration at line 169 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/context-h">Context.h</a>, definition at line 498 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/context-cpp">Context.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#add6c98d077e2f344b4d49266a2692696">registerValue</a> and <a href="#ab8e18f2b60b915a353326b5a71c45ece">ReturnInst</a>.</p>

</div>
</div>

### createSelectInst() {#ae914556359efbcbcd9f90eca07f822ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SelectInst * llvm::sandboxir::Context::createSelectInst (<a href="/web-llvm/docs/api/classes/llvm/selectinst">llvm::SelectInst</a> * SI)</td>
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



<p>Declaration at line 151 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/context-h">Context.h</a>, definition at line 445 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/context-cpp">Context.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#add6c98d077e2f344b4d49266a2692696">registerValue</a> and <a href="#aaed74093256ebc989231ae246c2a0bbf">SelectInst</a>.</p>

</div>
</div>

### createShuffleVectorInst() {#a8372a0db9a902956a6b93ba28739989f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ShuffleVectorInst * llvm::sandboxir::Context::createShuffleVectorInst (<a href="/web-llvm/docs/api/classes/llvm/shufflevectorinst">llvm::ShuffleVectorInst</a> * SVI)</td>
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



<p>Declaration at line 157 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/context-h">Context.h</a>, definition at line 465 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/context-cpp">Context.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#add6c98d077e2f344b4d49266a2692696">registerValue</a> and <a href="#aae53c4d91c893229f149bbad96f52bbd">ShuffleVectorInst</a>.</p>

</div>
</div>

### createStoreInst() {#abb92f16e9c77c403a302f721e6af7f28}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StoreInst * llvm::sandboxir::Context::createStoreInst (<a href="/web-llvm/docs/api/classes/llvm/storeinst">llvm::StoreInst</a> * SI)</td>
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



<p>Declaration at line 167 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/context-h">Context.h</a>, definition at line 493 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/context-cpp">Context.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#add6c98d077e2f344b4d49266a2692696">registerValue</a> and <a href="#a30505b071682ba3d6a2d8c9e3a1873d4">StoreInst</a>.</p>

</div>
</div>

### createSwitchInst() {#ad8686c9916cfd1debacae95485f75feb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SwitchInst * llvm::sandboxir::Context::createSwitchInst (<a href="/web-llvm/docs/api/classes/llvm/switchinst">llvm::SwitchInst</a> * I)</td>
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



<p>Declaration at line 193 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/context-h">Context.h</a>, definition at line 559 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/context-cpp">Context.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#add6c98d077e2f344b4d49266a2692696">registerValue</a> and <a href="#ac669814186e6e601ef4f340be89cb142">SwitchInst</a>.</p>

</div>
</div>

### createUnaryOperator() {#adacedc9fad9cf7172ff2c3dac0cf62c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">UnaryOperator * llvm::sandboxir::Context::createUnaryOperator (<a href="/web-llvm/docs/api/classes/llvm/unaryoperator">llvm::UnaryOperator</a> * I)</td>
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



<p>Declaration at line 195 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/context-h">Context.h</a>, definition at line 563 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/context-cpp">Context.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#add6c98d077e2f344b4d49266a2692696">registerValue</a> and <a href="#a59c4491d55e6e3eb33f888e2446fabd0">UnaryOperator</a>.</p>

</div>
</div>

### createUnreachableInst() {#af306103547e43fc5c0b0b388218f4e08}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">UnreachableInst * llvm::sandboxir::Context::createUnreachableInst (<a href="/web-llvm/docs/api/classes/llvm/unreachableinst">llvm::UnreachableInst</a> * UI)</td>
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



<p>Declaration at line 209 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/context-h">Context.h</a>, definition at line 518 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/context-cpp">Context.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#add6c98d077e2f344b4d49266a2692696">registerValue</a> and <a href="#a192f8faa22db79e377671ecc70defaa0">UnreachableInst</a>.</p>

</div>
</div>

### createVAArgInst() {#a4ca2867d5a1f665c28b44561e0171446}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VAArgInst * llvm::sandboxir::Context::createVAArgInst (<a href="/web-llvm/docs/api/classes/llvm/vaarginst">llvm::VAArgInst</a> * SI)</td>
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



<p>Declaration at line 145 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/context-h">Context.h</a>, definition at line 430 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/context-cpp">Context.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#add6c98d077e2f344b4d49266a2692696">registerValue</a> and <a href="#aae6c786185b49400eea9f348cb08fae8">VAArgInst</a>.</p>

</div>
</div>

### detach() {#aaf57bef4561e6ae8cdd300ef312a2ea4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; Value &gt; llvm::sandboxir::Context::detach (<a href="/web-llvm/docs/api/classes/llvm/sandboxir/value">Value</a> * V)</td>
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

<p>Remove <span class="doxyComputerOutput">SBV</span> from all SandboxIR maps and stop owning it.</p>


<p>This effectively detaches <span class="doxyComputerOutput">V</span> from the underlying IR.</p>


<p>Declaration at line 111 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/context-h">Context.h</a>, definition at line 27 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/context-cpp">Context.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#afb5c0771d9a9a847440aad09836e1b91">detachLLVMValue</a>.</p>


<p>Referenced by <a href="#ae78048f8d05be4c2b2c20435114b4753">createFunction</a>.</p>

</div>
</div>

### detachLLVMValue() {#afb5c0771d9a9a847440aad09836e1b91}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; Value &gt; llvm::sandboxir::Context::detachLLVMValue (<a href="/web-llvm/docs/api/classes/llvm/value">llvm::Value</a> * V)</td>
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

<p>Remove <span class="doxyComputerOutput">V</span> from the maps and returns the unique_ptr.</p>

<p>Declaration at line 108 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/context-h">Context.h</a>, definition at line 16 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/context-cpp">Context.cpp</a>.</p>


<p>Reference <a href="#a91988130fe6107522da95b9796016deb">LLVMValueToValueMap</a>.</p>


<p>Referenced by <a href="#aaf57bef4561e6ae8cdd300ef312a2ea4">detach</a>.</p>

</div>
</div>

### getLLVMIRBuilder() {#a4cb8dee2d7485de19c8f2029b26507d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">auto &amp; llvm::sandboxir::Context::getLLVMIRBuilder ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 143 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/context-h">Context.h</a>.</p>


<p>Reference <a href="#a26a7b32395ac524ee1bf2797f0461ebd">LLVMIRBuilder</a>.</p>

</div>
</div>

### getOrCreateArgument() {#a306a360f0d3259eb92660d80036b9b56}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Argument * llvm::sandboxir::Context::getOrCreateArgument (<a href="/web-llvm/docs/api/classes/llvm/argument">llvm::Argument</a> * LLVMArg)</td>
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

<p>Get or create a <a href="/web-llvm/docs/api/classes/llvm/sandboxir/argument">sandboxir::Argument</a> for an existing LLVM IR <span class="doxyComputerOutput">LLVMArg</span>.</p>

<p>Declaration at line 120 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/context-h">Context.h</a>, definition at line 407 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/context-cpp">Context.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a> and <a href="#a91988130fe6107522da95b9796016deb">LLVMValueToValueMap</a>.</p>


<p>Referenced by <a href="#ae78048f8d05be4c2b2c20435114b4753">createFunction</a>.</p>

</div>
</div>

### getOrCreateConstant() {#a7bf97c49fc62d8d7b10f346d1887c727}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Constant * llvm::sandboxir::Context::getOrCreateConstant (<a href="/web-llvm/docs/api/classes/llvm/constant">llvm::Constant</a> * LLVMC)</td>
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

<p>Get or create a <a href="/web-llvm/docs/api/classes/llvm/sandboxir/constant">sandboxir::Constant</a> from an existing LLVM IR <span class="doxyComputerOutput">LLVMC</span>.</p>

<p>Declaration at line 126 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/context-h">Context.h</a>, definition at line 417 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/context-cpp">Context.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a> and <a href="#adad27d8740783e65067b7c2ad286aa38">getOrCreateValueInternal</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sandboxir/shufflevectorinst/#a6224f807d740562c873c036926d0dfd9">llvm::sandboxir::ShuffleVectorInst::convertShuffleMaskForBitcode</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/blockaddress/#ab92aa8e12ea15943c53deddbdea43eb7">llvm::sandboxir::BlockAddress::get</a> and <a href="/web-llvm/docs/api/classes/llvm/sandboxir/nocfivalue/#afa0e3ddd6a06a4f5de4142baad208a38">llvm::sandboxir::NoCFIValue::get</a>.</p>

</div>
</div>

### getOrCreateValue() {#acfec3e7998ff90624e6f88e517464dd2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * llvm::sandboxir::Context::getOrCreateValue (<a href="/web-llvm/docs/api/classes/llvm/value">llvm::Value</a> * LLVMV)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get or create a <a href="/web-llvm/docs/api/classes/llvm/sandboxir/value">sandboxir::Value</a> for an existing LLVM IR <span class="doxyComputerOutput">LLVMV</span>.</p>

<p>Definition at line 122 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/context-h">Context.h</a>.</p>


<p>Reference <a href="#adad27d8740783e65067b7c2ad286aa38">getOrCreateValueInternal</a>.</p>


<p>Referenced by <a href="#a2604f458da0e7d0a33702d7d66d660dc">createModule</a> and <a href="/web-llvm/docs/api/classes/llvm/sandboxir/utils/#ab0185a31c3cb2e873b3cf08093d18537">llvm::sandboxir::Utils::getMemInstructionBase</a>.</p>

</div>
</div>

### getOrCreateValueInternal() {#adad27d8740783e65067b7c2ad286aa38}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * llvm::sandboxir::Context::getOrCreateValueInternal (<a href="/web-llvm/docs/api/classes/llvm/value">llvm::Value</a> * V, <a href="/web-llvm/docs/api/classes/llvm/user">llvm::User</a> * U=nullptr)</td>
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

<p>This is the actual function that creates sandboxir values for <span class="doxyComputerOutput">V</span>, and among others handles all instruction types.</p>

<p>Declaration at line 118 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/context-h">Context.h</a>, definition at line 55 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/context-cpp">Context.cpp</a>.</p>


<p>References <a href="#a3d3f78c2a93cab58fca043571501e7e1">AllocaInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#aed4242bc859436c33432187864aa8c9e">AtomicCmpXchgInst</a>, <a href="#abfbbc21f9fc5067c81720ce1b1e652b5">AtomicRMWInst</a>, <a href="#ad67b2d1be52ca8bafe68082d597db450">BinaryOperator</a>, <a href="#abda2123fd114da11af7365d87c770349">BranchInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="#af9d72d9dfe9616b96048e1ab97063b37">CallBrInst</a>, <a href="#aad6bb4ce3959458d2ea354d18043f2a0">CallInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#a7b3f8365e6296948cbe462d6fe0d3ca9">CastInst</a>, <a href="#a85794a7f47276252a7548196a374b57e">CatchPadInst</a>, <a href="#a28a160dd7f57a92556d0f95787850a81">CatchReturnInst</a>, <a href="#a2a09fd32a1dc8482d4b36e4e62c9f0f4">CatchSwitchInst</a>, <a href="#aab3135f4fdae98b5bbf5c7917fa290cd">CleanupPadInst</a>, <a href="#aa4f9f21a8f7cf3ede8e6c8b674ddf134">CleanupReturnInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#a4812224e74f991f4093975f54f5db90d">ExtractElementInst</a>, <a href="#a64bb275e2ec1ce6ad350c8976dd89d1d">ExtractValueInst</a>, <a href="#adc2a63f70133eaf0b6aaa78a386b15b4">FCmpInst</a>, <a href="#ac70ae476798a68bcc024ed1dc226b9ad">FenceInst</a>, <a href="#ac79c0b986194e0535feedaa98c1818d0">FreezeInst</a>, <a href="#af52100dcbd76cbca1304bc6df9e080b4">GetElementPtrInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanslp-cpp/#a06b4f19004df11b338ccc7e73bf47ab4">getOpcode</a>, <a href="#adad27d8740783e65067b7c2ad286aa38">getOrCreateValueInternal</a>, <a href="#a2dee21c5ed6d922ac4567a4fcd58a412">getValue</a>, <a href="#a63e49cc3b84ac25b6367b215371ebe89">ICmpInst</a>, <a href="#aecacd2aeb779f0c15298390ed8556d82">InsertElementInst</a>, <a href="#a75e893f51915ab1413a9a1a32419de6e">InsertValueInst</a>, <a href="#a93d94c872010058a3f58409b0ac16be7">InvokeInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="#a070f84e27810ea5314794b0e0728f98f">LandingPadInst</a>, <a href="/web-llvm/docs/api/groups/llvmccoretypes/#gga17a137327ed1a49585a00c585313ec18afa8c2dd4e2a176e867e8c9b723bf4e9b">LLVMAlloca</a>, <a href="/web-llvm/docs/api/groups/llvmccoretypes/#gga17a137327ed1a49585a00c585313ec18afc6313cfc3e8ba2e0e4c03d27cd279cd">LLVMAtomicCmpXchg</a>, <a href="/web-llvm/docs/api/groups/llvmccoretypes/#gga17a137327ed1a49585a00c585313ec18a23c6e83673e9129aabab472592b272eb">LLVMAtomicRMW</a>, <a href="/web-llvm/docs/api/groups/llvmccoretypes/#gga17a137327ed1a49585a00c585313ec18a9b712fb832c4e53cfdd5211e6f09b836">LLVMBr</a>, <a href="/web-llvm/docs/api/groups/llvmccoretypes/#gga17a137327ed1a49585a00c585313ec18a3f12806fe98f3577580a348403271192">LLVMCall</a>, <a href="/web-llvm/docs/api/groups/llvmccoretypes/#gga17a137327ed1a49585a00c585313ec18a1b189777776ada06d177e8f970c0160b">LLVMCallBr</a>, <a href="/web-llvm/docs/api/groups/llvmccoretypes/#gga17a137327ed1a49585a00c585313ec18aef0e1fb7fc9b03ddbc937af69f2229f5">LLVMFCmp</a>, <a href="/web-llvm/docs/api/groups/llvmccoretypes/#gga17a137327ed1a49585a00c585313ec18a99cb5f84daad805079a40a4d693c20db">LLVMFence</a>, <a href="/web-llvm/docs/api/groups/llvmccoretypes/#gga17a137327ed1a49585a00c585313ec18a7e5dfaa96e4fe7b8d65f2dae2d060d77">LLVMFreeze</a>, <a href="/web-llvm/docs/api/groups/llvmccoretypes/#gga17a137327ed1a49585a00c585313ec18a6051051a59f185d407350c55cd391900">LLVMICmp</a>, <a href="/web-llvm/docs/api/groups/llvmccoretypes/#gga17a137327ed1a49585a00c585313ec18a8ef52474fa20ce7c61c365b85cef85d7">LLVMInvoke</a>, <a href="/web-llvm/docs/api/groups/llvmccoretypes/#gga17a137327ed1a49585a00c585313ec18a797afbcf7347e2c40eda0c4072f4325a">LLVMRet</a>, <a href="/web-llvm/docs/api/groups/llvmccoretypes/#gga17a137327ed1a49585a00c585313ec18a3c3054533f114c790e1c268b1e347be8">LLVMUnreachable</a>, <a href="/web-llvm/docs/api/groups/llvmccoretypes/#gga17a137327ed1a49585a00c585313ec18aa1eedcfe1826f674d30e8afded0f334e">LLVMVAArg</a>, <a href="#a91988130fe6107522da95b9796016deb">LLVMValueToValueMap</a>, <a href="#aec18de7f11e2bb7b92ccdac9ee939b8d">LoadInst</a>, <a href="#a0a456376211041199b96cb4c83b32b90">PHINode</a>, <a href="#ab1b980fd1d7d17d1426067bdc7f23752">ResumeInst</a>, <a href="#ab8e18f2b60b915a353326b5a71c45ece">ReturnInst</a>, <a href="#aaed74093256ebc989231ae246c2a0bbf">SelectInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#adc4eb8be6f7a12ede962987fb9cabb47">llvm::seq</a>, <a href="#aae53c4d91c893229f149bbad96f52bbd">ShuffleVectorInst</a>, <a href="#a30505b071682ba3d6a2d8c9e3a1873d4">StoreInst</a>, <a href="#ac669814186e6e601ef4f340be89cb142">SwitchInst</a>, <a href="#a59c4491d55e6e3eb33f888e2446fabd0">UnaryOperator</a>, <a href="#a192f8faa22db79e377671ecc70defaa0">UnreachableInst</a> and <a href="#aae6c786185b49400eea9f348cb08fae8">VAArgInst</a>.</p>


<p>Referenced by <a href="#a7bf97c49fc62d8d7b10f346d1887c727">getOrCreateConstant</a>, <a href="#acfec3e7998ff90624e6f88e517464dd2">getOrCreateValue</a> and <a href="#adad27d8740783e65067b7c2ad286aa38">getOrCreateValueInternal</a>.</p>

</div>
</div>

### registerValue() {#add6c98d077e2f344b4d49266a2692696}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * llvm::sandboxir::Context::registerValue (std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/sandboxir/value">Value</a> &gt; &amp;&amp; VPtr)</td>
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

<p>Take ownership of VPtr and store it in <span class="doxyComputerOutput">LLVMValueToValueMap</span>.</p>

<p>Declaration at line 114 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/context-h">Context.h</a>, definition at line 34 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/context-cpp">Context.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/tracker/#ae78b97b8ea9885d09219a569caff84b7">llvm::sandboxir::Tracker::emplaceIfTracking</a>, <a href="#af021d63b7832bc9cba10fdb5ccd7e925">getTracker</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a91988130fe6107522da95b9796016deb">LLVMValueToValueMap</a> and <a href="#a60377c60e9abe2602cd153de0c991ca4">runCreateInstrCallbacks</a>.</p>


<p>Referenced by <a href="#a56cfb0f39f439788ea2856c0b1e4ee4d">createAllocaInst</a>, <a href="#af3ea0b86a033cba8b1b853a84d9a3999">createAtomicCmpXchgInst</a>, <a href="#a6160a35b731fb9211dba3730f7c449b4">createAtomicRMWInst</a>, <a href="#a008a32bf404093142fba745ed3ab0918">createBasicBlock</a>, <a href="#a84f542b398fe0517fc1973bcf022500d">createBinaryOperator</a>, <a href="#a7f3d0f72956a57123d00a8d6b3854aae">createBranchInst</a>, <a href="#a2458ac81cb773c5f611902e443dba72a">createCallBrInst</a>, <a href="#ad6917b72e0fc9300687d07a77addb610">createCallInst</a>, <a href="#ab948f8007dc5f505859efec6e6925541">createCastInst</a>, <a href="#a9fa2f280a391ec59ffde55f13982f705">createCatchPadInst</a>, <a href="#abd2d5f2181ea45bcc683738c0090e9de">createCatchReturnInst</a>, <a href="#abde9ca05d3c36a4db633dd9329c4de7a">createCatchSwitchInst</a>, <a href="#acc1515d9b18eacaa0259cf6910d2f10b">createCleanupPadInst</a>, <a href="#a4d48e0c5e5e71b02f74919e213493b30">createCleanupReturnInst</a>, <a href="#a7951c687043d2620c902e9bfa5eac56f">createExtractElementInst</a>, <a href="#ab02a987dcbbb52bd5ca013939320377a">createExtractValueInst</a>, <a href="#a6f4742f92fa2e51ff7486abb938073c4">createFCmpInst</a>, <a href="#ad32b60707d80f6067a0ac52278b8f1f4">createFenceInst</a>, <a href="#a9474b2572efbad4c603f6f316c190960">createFreezeInst</a>, <a href="#ae78048f8d05be4c2b2c20435114b4753">createFunction</a>, <a href="#a13cdb8a5d527cb1d32c4a2a702956ff1">createGetElementPtrInst</a>, <a href="#aac5cf217b197dfc91bb5e24eff8ec1a6">createICmpInst</a>, <a href="#ae23e1112f3af74c9caf9ec9c147a99fa">createInsertElementInst</a>, <a href="#a62816dedba2be083d1f90c92fa30857e">createInsertValueInst</a>, <a href="#adbf6b5b8d208e62c40f1db873ac4f695">createInvokeInst</a>, <a href="#adfb0b5c39ad248a5bdc11755e80cf4d9">createLandingPadInst</a>, <a href="#a8f0aa5a68819eb79b24b6d39aa768105">createLoadInst</a>, <a href="#a96b0b98ca8bba81133d5d60453babfec">createPHINode</a>, <a href="#aee320c8b43dc8aa050750db45f7debca">createResumeInst</a>, <a href="#a39fd9f172fd1f91f62775e710cc5e1af">createReturnInst</a>, <a href="#ae914556359efbcbcd9f90eca07f822ec">createSelectInst</a>, <a href="#a8372a0db9a902956a6b93ba28739989f">createShuffleVectorInst</a>, <a href="#abb92f16e9c77c403a302f721e6af7f28">createStoreInst</a>, <a href="#ad8686c9916cfd1debacae95485f75feb">createSwitchInst</a>, <a href="#adacedc9fad9cf7172ff2c3dac0cf62c9">createUnaryOperator</a>, <a href="#af306103547e43fc5c0b0b388218f4e08">createUnreachableInst</a> and <a href="#a4ca2867d5a1f665c28b44561e0171446">createVAArgInst</a>.</p>

</div>
</div>

### runCreateInstrCallbacks() {#a60377c60e9abe2602cd153de0c991ca4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::sandboxir::Context::runCreateInstrCallbacks (<a href="/web-llvm/docs/api/classes/llvm/sandboxir/instruction">Instruction</a> * I)</td>
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



<p>Declaration at line 130 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/context-h">Context.h</a>, definition at line 680 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/context-cpp">Context.cpp</a>.</p>


<p>References <a href="#a1546108265ad8c465a33dff7b7454dd5">CreateInstrCallbacks</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="#a87273cb892a8182f137567e6b631695e">Instruction</a>.</p>


<p>Referenced by <a href="#add6c98d077e2f344b4d49266a2692696">registerValue</a>.</p>

</div>
</div>

### runEraseInstrCallbacks() {#a3bd7534254b9665d9a49781b169ba2f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::sandboxir::Context::runEraseInstrCallbacks (<a href="/web-llvm/docs/api/classes/llvm/sandboxir/instruction">Instruction</a> * I)</td>
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



<p>Declaration at line 129 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/context-h">Context.h</a>, definition at line 675 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/context-cpp">Context.cpp</a>.</p>


<p>References <a href="#a2bde7d17436eff7df25a72ba26e1aa2f">EraseInstrCallbacks</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="#a87273cb892a8182f137567e6b631695e">Instruction</a>.</p>

</div>
</div>

### runMoveInstrCallbacks() {#adacbde8e548ad9d7fb7681d21866cc29}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::sandboxir::Context::runMoveInstrCallbacks (<a href="/web-llvm/docs/api/classes/llvm/sandboxir/instruction">Instruction</a> * I, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> BBIterator &amp; Where)</td>
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



<p>Declaration at line 131 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/context-h">Context.h</a>, definition at line 685 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/context-cpp">Context.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a87273cb892a8182f137567e6b631695e">Instruction</a> and <a href="#aae8fca181738a0996766c6a1dec68c50">MoveInstrCallbacks</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### AllocaInst {#a3d3f78c2a93cab58fca043571501e7e1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend llvm::sandboxir::Context::AllocaInst</td>
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



<p>Definition at line 204 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/context-h">Context.h</a>.</p>


<p>Referenced by <a href="#a56cfb0f39f439788ea2856c0b1e4ee4d">createAllocaInst</a> and <a href="#adad27d8740783e65067b7c2ad286aa38">getOrCreateValueInternal</a>.</p>

</div>
</div>

### AtomicCmpXchgInst {#aed4242bc859436c33432187864aa8c9e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend llvm::sandboxir::Context::AtomicCmpXchgInst</td>
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



<p>Definition at line 202 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/context-h">Context.h</a>.</p>


<p>Referenced by <a href="#af3ea0b86a033cba8b1b853a84d9a3999">createAtomicCmpXchgInst</a> and <a href="#adad27d8740783e65067b7c2ad286aa38">getOrCreateValueInternal</a>.</p>

</div>
</div>

### AtomicRMWInst {#abfbbc21f9fc5067c81720ce1b1e652b5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend llvm::sandboxir::Context::AtomicRMWInst</td>
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



<p>Definition at line 200 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/context-h">Context.h</a>.</p>


<p>Referenced by <a href="#a6160a35b731fb9211dba3730f7c449b4">createAtomicRMWInst</a> and <a href="#adad27d8740783e65067b7c2ad286aa38">getOrCreateValueInternal</a>.</p>

</div>
</div>

### BinaryOperator {#ad67b2d1be52ca8bafe68082d597db450}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend llvm::sandboxir::Context::BinaryOperator</td>
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



<p>Definition at line 198 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/context-h">Context.h</a>.</p>


<p>Referenced by <a href="#a84f542b398fe0517fc1973bcf022500d">createBinaryOperator</a> and <a href="#adad27d8740783e65067b7c2ad286aa38">getOrCreateValueInternal</a>.</p>

</div>
</div>

### BranchInst {#abda2123fd114da11af7365d87c770349}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend llvm::sandboxir::Context::BranchInst</td>
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



<p>Definition at line 164 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/context-h">Context.h</a>.</p>


<p>Referenced by <a href="#a7f3d0f72956a57123d00a8d6b3854aae">createBranchInst</a> and <a href="#adad27d8740783e65067b7c2ad286aa38">getOrCreateValueInternal</a>.</p>

</div>
</div>

### CallBrInst {#af9d72d9dfe9616b96048e1ab97063b37}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend llvm::sandboxir::Context::CallBrInst</td>
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



<p>Definition at line 176 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/context-h">Context.h</a>.</p>


<p>Referenced by <a href="#a2458ac81cb773c5f611902e443dba72a">createCallBrInst</a> and <a href="#adad27d8740783e65067b7c2ad286aa38">getOrCreateValueInternal</a>.</p>

</div>
</div>

### CallInst {#aad6bb4ce3959458d2ea354d18043f2a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend llvm::sandboxir::Context::CallInst</td>
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



<p>Definition at line 172 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/context-h">Context.h</a>.</p>


<p>Referenced by <a href="#ad6917b72e0fc9300687d07a77addb610">createCallInst</a> and <a href="#adad27d8740783e65067b7c2ad286aa38">getOrCreateValueInternal</a>.</p>

</div>
</div>

### CastInst {#a7b3f8365e6296948cbe462d6fe0d3ca9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend llvm::sandboxir::Context::CastInst</td>
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



<p>Definition at line 206 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/context-h">Context.h</a>.</p>


<p>Referenced by <a href="#ab948f8007dc5f505859efec6e6925541">createCastInst</a> and <a href="#adad27d8740783e65067b7c2ad286aa38">getOrCreateValueInternal</a>.</p>

</div>
</div>

### CatchPadInst {#a85794a7f47276252a7548196a374b57e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend llvm::sandboxir::Context::CatchPadInst</td>
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



<p>Definition at line 180 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/context-h">Context.h</a>.</p>


<p>Referenced by <a href="#a9fa2f280a391ec59ffde55f13982f705">createCatchPadInst</a> and <a href="#adad27d8740783e65067b7c2ad286aa38">getOrCreateValueInternal</a>.</p>

</div>
</div>

### CatchReturnInst {#a28a160dd7f57a92556d0f95787850a81}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend llvm::sandboxir::Context::CatchReturnInst</td>
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



<p>Definition at line 184 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/context-h">Context.h</a>.</p>


<p>Referenced by <a href="#abd2d5f2181ea45bcc683738c0090e9de">createCatchReturnInst</a> and <a href="#adad27d8740783e65067b7c2ad286aa38">getOrCreateValueInternal</a>.</p>

</div>
</div>

### CatchSwitchInst {#a2a09fd32a1dc8482d4b36e4e62c9f0f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend llvm::sandboxir::Context::CatchSwitchInst</td>
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



<p>Definition at line 190 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/context-h">Context.h</a>.</p>


<p>Referenced by <a href="#abde9ca05d3c36a4db633dd9329c4de7a">createCatchSwitchInst</a> and <a href="#adad27d8740783e65067b7c2ad286aa38">getOrCreateValueInternal</a>.</p>

</div>
</div>

### CleanupPadInst {#aab3135f4fdae98b5bbf5c7917fa290cd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend llvm::sandboxir::Context::CleanupPadInst</td>
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



<p>Definition at line 182 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/context-h">Context.h</a>.</p>


<p>Referenced by <a href="#acc1515d9b18eacaa0259cf6910d2f10b">createCleanupPadInst</a> and <a href="#adad27d8740783e65067b7c2ad286aa38">getOrCreateValueInternal</a>.</p>

</div>
</div>

### CleanupReturnInst {#aa4f9f21a8f7cf3ede8e6c8b674ddf134}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend llvm::sandboxir::Context::CleanupReturnInst</td>
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



<p>Definition at line 186 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/context-h">Context.h</a>.</p>


<p>Referenced by <a href="#a4d48e0c5e5e71b02f74919e213493b30">createCleanupReturnInst</a> and <a href="#adad27d8740783e65067b7c2ad286aa38">getOrCreateValueInternal</a>.</p>

</div>
</div>

### CmpInst {#a6d3b6192dfc396b5d5fcb06689a62bcf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend llvm::sandboxir::Context::CmpInst</td>
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



<p>Definition at line 212 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/context-h">Context.h</a>.</p>


<p>Referenced by <a href="#a1cb8188a6775c87364591b658d45c27f">createCmpInst</a>.</p>

</div>
</div>

### CreateInstrCallbacks {#a1546108265ad8c465a33dff7b7454dd5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MapVector&lt;CallbackID, CreateInstrCallback&gt; llvm::sandboxir::Context::CreateInstrCallbacks</td>
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

<p>Callbacks called when an IR instruction is about to get created.</p>


<p>Keys are used as IDs for deregistration.</p>


<p>Definition at line 97 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/context-h">Context.h</a>.</p>


<p>Referenced by <a href="#a98c73743a3ddaad3668316f0a60b5dc4">registerCreateInstrCallback</a>, <a href="#a60377c60e9abe2602cd153de0c991ca4">runCreateInstrCallbacks</a> and <a href="#aaf860dfa8b51917f45c740cdc3741acc">unregisterCreateInstrCallback</a>.</p>

</div>
</div>

### EraseInstrCallbacks {#a2bde7d17436eff7df25a72ba26e1aa2f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MapVector&lt;CallbackID, EraseInstrCallback&gt; llvm::sandboxir::Context::EraseInstrCallbacks</td>
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

<p>Callbacks called when an IR instruction is about to get erased.</p>


<p>Keys are used as IDs for deregistration.</p>


<p>Definition at line 94 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/context-h">Context.h</a>.</p>


<p>Referenced by <a href="#af6d2670f4ff31e843f297ce7d3f7e157">registerEraseInstrCallback</a>, <a href="#a3bd7534254b9665d9a49781b169ba2f7">runEraseInstrCallbacks</a> and <a href="#aee83fd7e06567cc8d42c29f899322e67">unregisterEraseInstrCallback</a>.</p>

</div>
</div>

### ExtractElementInst {#a4812224e74f991f4093975f54f5db90d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend llvm::sandboxir::Context::ExtractElementInst</td>
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



<p>Definition at line 156 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/context-h">Context.h</a>.</p>


<p>Referenced by <a href="#a7951c687043d2620c902e9bfa5eac56f">createExtractElementInst</a> and <a href="#adad27d8740783e65067b7c2ad286aa38">getOrCreateValueInternal</a>.</p>

</div>
</div>

### ExtractValueInst {#a64bb275e2ec1ce6ad350c8976dd89d1d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend llvm::sandboxir::Context::ExtractValueInst</td>
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



<p>Definition at line 160 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/context-h">Context.h</a>.</p>


<p>Referenced by <a href="#ab02a987dcbbb52bd5ca013939320377a">createExtractValueInst</a> and <a href="#adad27d8740783e65067b7c2ad286aa38">getOrCreateValueInternal</a>.</p>

</div>
</div>

### FCmpInst {#adc2a63f70133eaf0b6aaa78a386b15b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend llvm::sandboxir::Context::FCmpInst</td>
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



<p>Definition at line 216 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/context-h">Context.h</a>.</p>


<p>Referenced by <a href="#a6f4742f92fa2e51ff7486abb938073c4">createFCmpInst</a> and <a href="#adad27d8740783e65067b7c2ad286aa38">getOrCreateValueInternal</a>.</p>

</div>
</div>

### FenceInst {#ac70ae476798a68bcc024ed1dc226b9ad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend llvm::sandboxir::Context::FenceInst</td>
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



<p>Definition at line 150 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/context-h">Context.h</a>.</p>


<p>Referenced by <a href="#ad32b60707d80f6067a0ac52278b8f1f4">createFenceInst</a> and <a href="#adad27d8740783e65067b7c2ad286aa38">getOrCreateValueInternal</a>.</p>

</div>
</div>

### FreezeInst {#ac79c0b986194e0535feedaa98c1818d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend llvm::sandboxir::Context::FreezeInst</td>
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



<p>Definition at line 148 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/context-h">Context.h</a>.</p>


<p>Referenced by <a href="#a9474b2572efbad4c603f6f316c190960">createFreezeInst</a> and <a href="#adad27d8740783e65067b7c2ad286aa38">getOrCreateValueInternal</a>.</p>

</div>
</div>

### GetElementPtrInst {#af52100dcbd76cbca1304bc6df9e080b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend llvm::sandboxir::Context::GetElementPtrInst</td>
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



<p>Definition at line 188 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/context-h">Context.h</a>.</p>


<p>Referenced by <a href="#a13cdb8a5d527cb1d32c4a2a702956ff1">createGetElementPtrInst</a> and <a href="#adad27d8740783e65067b7c2ad286aa38">getOrCreateValueInternal</a>.</p>

</div>
</div>

### ICmpInst {#a63e49cc3b84ac25b6367b215371ebe89}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend llvm::sandboxir::Context::ICmpInst</td>
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



<p>Definition at line 214 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/context-h">Context.h</a>.</p>


<p>Referenced by <a href="#aac5cf217b197dfc91bb5e24eff8ec1a6">createICmpInst</a> and <a href="#adad27d8740783e65067b7c2ad286aa38">getOrCreateValueInternal</a>.</p>

</div>
</div>

### InsertElementInst {#aecacd2aeb779f0c15298390ed8556d82}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend llvm::sandboxir::Context::InsertElementInst</td>
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



<p>Definition at line 154 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/context-h">Context.h</a>.</p>


<p>Referenced by <a href="#ae23e1112f3af74c9caf9ec9c147a99fa">createInsertElementInst</a> and <a href="#adad27d8740783e65067b7c2ad286aa38">getOrCreateValueInternal</a>.</p>

</div>
</div>

### InsertValueInst {#a75e893f51915ab1413a9a1a32419de6e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend llvm::sandboxir::Context::InsertValueInst</td>
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



<p>Definition at line 162 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/context-h">Context.h</a>.</p>


<p>Referenced by <a href="#a62816dedba2be083d1f90c92fa30857e">createInsertValueInst</a> and <a href="#adad27d8740783e65067b7c2ad286aa38">getOrCreateValueInternal</a>.</p>

</div>
</div>

### InvokeInst {#a93d94c872010058a3f58409b0ac16be7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend llvm::sandboxir::Context::InvokeInst</td>
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



<p>Definition at line 174 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/context-h">Context.h</a>.</p>


<p>Referenced by <a href="#adbf6b5b8d208e62c40f1db873ac4f695">createInvokeInst</a> and <a href="#adad27d8740783e65067b7c2ad286aa38">getOrCreateValueInternal</a>.</p>

</div>
</div>

### IRTracker {#a86e4b065b61d613fd23434a2b80da629}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Tracker llvm::sandboxir::Context::IRTracker</td>
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



<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/context-h">Context.h</a>.</p>


<p>Referenced by <a href="#a6b033605d86bddde04ddf62e47aea332">accept</a>, <a href="#a9bc6da7c6106e68fc33365a069590be7">Context</a>, <a href="#af021d63b7832bc9cba10fdb5ccd7e925">getTracker</a>, <a href="#ab60fe9b3dff3878469ab487428930acb">revert</a> and <a href="#acbf3fc5379cf327e9cdd7594a772be61">save</a>.</p>

</div>
</div>

### LandingPadInst {#a070f84e27810ea5314794b0e0728f98f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend llvm::sandboxir::Context::LandingPadInst</td>
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



<p>Definition at line 178 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/context-h">Context.h</a>.</p>


<p>Referenced by <a href="#adfb0b5c39ad248a5bdc11755e80cf4d9">createLandingPadInst</a> and <a href="#adad27d8740783e65067b7c2ad286aa38">getOrCreateValueInternal</a>.</p>

</div>
</div>

### LLVMCtx {#aef9f3a49744b7209b0592dd5315a79be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMContext&amp; llvm::sandboxir::Context::LLVMCtx</td>
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



<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/context-h">Context.h</a>.</p>


<p>Referenced by <a href="#a9bc6da7c6106e68fc33365a069590be7">Context</a> and <a href="/web-llvm/docs/api/classes/llvm/sandboxir/cmpinst/#a7b33bd9843f6f96a4f390a9314692657">llvm::sandboxir::CmpInst::makeCmpResultType</a>.</p>

</div>
</div>

### LLVMIRBuilder {#a26a7b32395ac524ee1bf2797f0461ebd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IRBuilder&lt;ConstantFolder&gt; llvm::sandboxir::Context::LLVMIRBuilder</td>
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



<p>Definition at line 142 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/context-h">Context.h</a>.</p>


<p>Referenced by <a href="#a9bc6da7c6106e68fc33365a069590be7">Context</a> and <a href="#a4cb8dee2d7485de19c8f2029b26507d7">getLLVMIRBuilder</a>.</p>

</div>
</div>

### LLVMModuleToModuleMap {#ab97a411015236a1083cdbc4672024c99}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;llvm::Module *, std::unique_ptr&lt;Module&gt; &gt; llvm::sandboxir::Context::LLVMModuleToModuleMap</td>
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

<p>Maps an LLVM <a href="/web-llvm/docs/api/classes/llvm/sandboxir/module">Module</a> to the corresponding <a href="/web-llvm/docs/api/classes/llvm/sandboxir/module">sandboxir::Module</a>.</p>

<p>Definition at line 80 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/context-h">Context.h</a>.</p>


<p>Referenced by <a href="#a4132ef295dfc5dc3e53cfb4c36ae8e7e">getModule</a> and <a href="#a8b26362d79d2939a5341e36e20f3a13a">getOrCreateModule</a>.</p>

</div>
</div>

### LLVMTypeToTypeMap {#a6977d1878b8588984c79b6d940b1c2d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;llvm::Type *, std::unique_ptr&lt;Type, TypeDeleter&gt; &gt; llvm::sandboxir::Context::LLVMTypeToTypeMap</td>
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

<p>Maps LLVM <a href="/web-llvm/docs/api/classes/llvm/sandboxir/type">Type</a> to the corresonding <a href="/web-llvm/docs/api/classes/llvm/sandboxir/type">sandboxir::Type</a>.</p>


<p>Owns all Sandbox IR <a href="/web-llvm/docs/api/classes/llvm/sandboxir/type">Type</a> objects.</p>


<p>Definition at line 90 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/context-h">Context.h</a>.</p>


<p>Referenced by <a href="#a5d72c7051da5356cbfbfa16ecb7dca8a">getType</a>.</p>

</div>
</div>

### LLVMValueToValueMap {#a91988130fe6107522da95b9796016deb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;llvm::Value *, std::unique_ptr&lt;Value&gt; &gt; llvm::sandboxir::Context::LLVMValueToValueMap</td>
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

<p>Maps LLVM <a href="/web-llvm/docs/api/classes/llvm/sandboxir/value">Value</a> to the corresponding <a href="/web-llvm/docs/api/classes/llvm/sandboxir/value">sandboxir::Value</a>.</p>


<p>Owns all SandboxIR objects.</p>


<p>Definition at line 77 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/context-h">Context.h</a>.</p>


<p>Referenced by <a href="#aa15843bad9969a3db23465cd9da678b0">clear</a>, <a href="#afb5c0771d9a9a847440aad09836e1b91">detachLLVMValue</a>, <a href="#afaf17d4dff8ccecdf1614ade84b34083">getNumValues</a>, <a href="#a306a360f0d3259eb92660d80036b9b56">getOrCreateArgument</a>, <a href="#adad27d8740783e65067b7c2ad286aa38">getOrCreateValueInternal</a>, <a href="#a2dee21c5ed6d922ac4567a4fcd58a412">getValue</a> and <a href="#add6c98d077e2f344b4d49266a2692696">registerValue</a>.</p>

</div>
</div>

### LoadInst {#aec18de7f11e2bb7b92ccdac9ee939b8d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend llvm::sandboxir::Context::LoadInst</td>
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



<p>Definition at line 166 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/context-h">Context.h</a>.</p>


<p>Referenced by <a href="#a8f0aa5a68819eb79b24b6d39aa768105">createLoadInst</a> and <a href="#adad27d8740783e65067b7c2ad286aa38">getOrCreateValueInternal</a>.</p>

</div>
</div>

### MoveInstrCallbacks {#aae8fca181738a0996766c6a1dec68c50}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MapVector&lt;CallbackID, MoveInstrCallback&gt; llvm::sandboxir::Context::MoveInstrCallbacks</td>
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

<p>Callbacks called when an IR instruction is about to get moved.</p>


<p>Keys are used as IDs for deregistration.</p>


<p>Definition at line 100 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/context-h">Context.h</a>.</p>


<p>Referenced by <a href="#af134e2ec0c001e0137342f53b89db9dc">registerMoveInstrCallback</a>, <a href="#adacbde8e548ad9d7fb7681d21866cc29">runMoveInstrCallbacks</a> and <a href="#acbd86cf965d05c6e57657855023213e1">unregisterMoveInstrCallback</a>.</p>

</div>
</div>

### NextCallbackID {#a7556f470daa8373b7f866517a684dc4e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CallbackID::ValTy llvm::sandboxir::Context::NextCallbackID = 1</td>
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

<p>A counter used for assigning callback IDs during registration.</p>


<p>The same counter is used for all kinds of callbacks so we can detect mismatched registration/deregistration.</p>


<p>Definition at line 105 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/context-h">Context.h</a>.</p>


<p>Referenced by <a href="#a98c73743a3ddaad3668316f0a60b5dc4">registerCreateInstrCallback</a>, <a href="#af6d2670f4ff31e843f297ce7d3f7e157">registerEraseInstrCallback</a> and <a href="#af134e2ec0c001e0137342f53b89db9dc">registerMoveInstrCallback</a>.</p>

</div>
</div>

### PHINode {#a0a456376211041199b96cb4c83b32b90}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend llvm::sandboxir::Context::PHINode</td>
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



<p>Definition at line 208 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/context-h">Context.h</a>.</p>


<p>Referenced by <a href="#a96b0b98ca8bba81133d5d60453babfec">createPHINode</a> and <a href="#adad27d8740783e65067b7c2ad286aa38">getOrCreateValueInternal</a>.</p>

</div>
</div>

### ResumeInst {#ab1b980fd1d7d17d1426067bdc7f23752}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend llvm::sandboxir::Context::ResumeInst</td>
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



<p>Definition at line 192 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/context-h">Context.h</a>.</p>


<p>Referenced by <a href="#aee320c8b43dc8aa050750db45f7debca">createResumeInst</a> and <a href="#adad27d8740783e65067b7c2ad286aa38">getOrCreateValueInternal</a>.</p>

</div>
</div>

### ReturnInst {#ab8e18f2b60b915a353326b5a71c45ece}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend llvm::sandboxir::Context::ReturnInst</td>
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



<p>Definition at line 170 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/context-h">Context.h</a>.</p>


<p>Referenced by <a href="#a39fd9f172fd1f91f62775e710cc5e1af">createReturnInst</a> and <a href="#adad27d8740783e65067b7c2ad286aa38">getOrCreateValueInternal</a>.</p>

</div>
</div>

### SelectInst {#aaed74093256ebc989231ae246c2a0bbf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend llvm::sandboxir::Context::SelectInst</td>
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



<p>Definition at line 152 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/context-h">Context.h</a>.</p>


<p>Referenced by <a href="#ae914556359efbcbcd9f90eca07f822ec">createSelectInst</a> and <a href="#adad27d8740783e65067b7c2ad286aa38">getOrCreateValueInternal</a>.</p>

</div>
</div>

### ShuffleVectorInst {#aae53c4d91c893229f149bbad96f52bbd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend llvm::sandboxir::Context::ShuffleVectorInst</td>
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



<p>Definition at line 158 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/context-h">Context.h</a>.</p>


<p>Referenced by <a href="#a8372a0db9a902956a6b93ba28739989f">createShuffleVectorInst</a> and <a href="#adad27d8740783e65067b7c2ad286aa38">getOrCreateValueInternal</a>.</p>

</div>
</div>

### StoreInst {#a30505b071682ba3d6a2d8c9e3a1873d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend llvm::sandboxir::Context::StoreInst</td>
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



<p>Definition at line 168 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/context-h">Context.h</a>.</p>


<p>Referenced by <a href="#abb92f16e9c77c403a302f721e6af7f28">createStoreInst</a> and <a href="#adad27d8740783e65067b7c2ad286aa38">getOrCreateValueInternal</a>.</p>

</div>
</div>

### SwitchInst {#ac669814186e6e601ef4f340be89cb142}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend llvm::sandboxir::Context::SwitchInst</td>
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



<p>Definition at line 194 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/context-h">Context.h</a>.</p>


<p>Referenced by <a href="#ad8686c9916cfd1debacae95485f75feb">createSwitchInst</a> and <a href="#adad27d8740783e65067b7c2ad286aa38">getOrCreateValueInternal</a>.</p>

</div>
</div>

### UnaryOperator {#a59c4491d55e6e3eb33f888e2446fabd0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend llvm::sandboxir::Context::UnaryOperator</td>
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



<p>Definition at line 196 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/context-h">Context.h</a>.</p>


<p>Referenced by <a href="#adacedc9fad9cf7172ff2c3dac0cf62c9">createUnaryOperator</a> and <a href="#adad27d8740783e65067b7c2ad286aa38">getOrCreateValueInternal</a>.</p>

</div>
</div>

### UnreachableInst {#a192f8faa22db79e377671ecc70defaa0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend llvm::sandboxir::Context::UnreachableInst</td>
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



<p>Definition at line 210 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/context-h">Context.h</a>.</p>


<p>Referenced by <a href="#af306103547e43fc5c0b0b388218f4e08">createUnreachableInst</a> and <a href="#adad27d8740783e65067b7c2ad286aa38">getOrCreateValueInternal</a>.</p>

</div>
</div>

### VAArgInst {#aae6c786185b49400eea9f348cb08fae8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend llvm::sandboxir::Context::VAArgInst</td>
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



<p>Definition at line 146 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/context-h">Context.h</a>.</p>


<p>Referenced by <a href="#a4ca2867d5a1f665c28b44561e0171446">createVAArgInst</a> and <a href="#adad27d8740783e65067b7c2ad286aa38">getOrCreateValueInternal</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/context-h">Context.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/sandboxir/context-cpp">Context.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>

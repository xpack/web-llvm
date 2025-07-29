---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/lexicalscopes
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `LexicalScopes` Class

<p><a href="/web-llvm/docs/api/classes/llvm/lexicalscopes">LexicalScopes</a> - This class provides interface to collect and use lexical scoping information from machine instruction. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::LexicalScopes { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/lexicalscopes-h">llvm/CodeGen/LexicalScopes.h</a>"
</div>

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0254e1b8b19e02f9f01fd111f35e71d1">BlockSetT</a> = <a href="/web-llvm/docs/api/classes/llvm/smallptrset">SmallPtrSet</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *, 4 &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Map a location to the set of basic blocks it dominates. <a href="#a0254e1b8b19e02f9f01fd111f35e71d1">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c0018016f2b307b109ba4afd66dfa59">LexicalScopes</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3134ce614dc1b5fc41522648d24ff7cb">initialize</a> (const MachineFunction &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>initialize - Scan machine function and constuct lexical scope nest, resets the instance if necessary. <a href="#a3134ce614dc1b5fc41522648d24ff7cb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1decd7f30d5c97d10091c1991911d577">reset</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>releaseMemory - release memory. <a href="#a1decd7f30d5c97d10091c1991911d577">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abca17648a9276ce54a3e54d159d6a94d">empty</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>empty - Return true if there is any lexical scope information available. <a href="#abca17648a9276ce54a3e54d159d6a94d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/lexicalscope">LexicalScope</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af526dd6c94f2521992a7296059d3f0ab">getCurrentFunctionScope</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getCurrentFunctionScope - Return lexical scope for the current function. <a href="#af526dd6c94f2521992a7296059d3f0ab">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6478937e0927f9038e58dca2e03e38ab">getMachineBasicBlocks</a> (const DILocation *DL, SmallPtrSetImpl&lt; const MachineBasicBlock * &gt; &amp;MBBs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getMachineBasicBlocks - Populate given set using machine basic blocks which have machine instructions that belong to lexical scope identified by <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a>. <a href="#a6478937e0927f9038e58dca2e03e38ab">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf24ff038d82eb5079e4719663ef3857">dominates</a> (const DILocation *DL, MachineBasicBlock *MBB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a>'s lexical scope dominates at least one machine instruction's lexical scope in a given machine basic block. <a href="#abf24ff038d82eb5079e4719663ef3857">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/lexicalscope">LexicalScope</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3245044b58379359df4673c0ed9308b0">findLexicalScope</a> (const DILocation *DL)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>findLexicalScope - Find lexical scope, either regular or inlined, for the given <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a>. <a href="#a3245044b58379359df4673c0ed9308b0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/lexicalscope">LexicalScope</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a82f707a6a97e3c8e715c9122fa8c5ac9">getAbstractScopesList</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getAbstractScopesList - Return a reference to list of abstract scopes. <a href="#a82f707a6a97e3c8e715c9122fa8c5ac9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/lexicalscope">LexicalScope</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a97c91dd63cc11f0c4fd4b537b079e8bd">findAbstractScope</a> (const DILocalScope *N)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>findAbstractScope - Find an abstract scope or return null. <a href="#a97c91dd63cc11f0c4fd4b537b079e8bd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/lexicalscope">LexicalScope</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a975b93f1b5bdac0a6ffcaf130570d4d8">findInlinedScope</a> (const DILocalScope *N, const DILocation *IA)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>findInlinedScope - Find an inlined scope for the given scope/inlined-at. <a href="#a975b93f1b5bdac0a6ffcaf130570d4d8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/lexicalscope">LexicalScope</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aba236eb440fe88eb1906b3e8f00bd037">findLexicalScope</a> (const DILocalScope *N)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>findLexicalScope - Find regular lexical scope or return null. <a href="#aba236eb440fe88eb1906b3e8f00bd037">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/lexicalscope">LexicalScope</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2530cf6b1cfff7baf9db14941cef749a">getOrCreateAbstractScope</a> (const DILocalScope *Scope)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getOrCreateAbstractScope - Find or create an abstract lexical scope. <a href="#a2530cf6b1cfff7baf9db14941cef749a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/lexicalscope">LexicalScope</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3e3743b320b9436090a0149d29b06bc8">getOrCreateLexicalScope</a> (const DILocalScope *Scope, const DILocation *IA=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getOrCreateLexicalScope - Find lexical scope for the given Scope/IA. <a href="#a3e3743b320b9436090a0149d29b06bc8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/lexicalscope">LexicalScope</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a87e0b5f3fc74c81bfb83c198d4184f12">getOrCreateLexicalScope</a> (const DILocation *DL)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/lexicalscope">LexicalScope</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a60e3e11262537ac7eeb016dc5a463584">getOrCreateRegularScope</a> (const DILocalScope *Scope)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getOrCreateRegularScope - Find or create a regular lexical scope. <a href="#a60e3e11262537ac7eeb016dc5a463584">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/lexicalscope">LexicalScope</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac982fd73b51fba8627980901d3864c54">getOrCreateInlinedScope</a> (const DILocalScope *Scope, const DILocation *InlinedAt)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getOrCreateInlinedScope - Find or create an inlined lexical scope. <a href="#ac982fd73b51fba8627980901d3864c54">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0bd8a05addcd1cead5df4a8df86536fa">extractLexicalScopes</a> (SmallVectorImpl&lt; InsnRange &gt; &amp;MIRanges, DenseMap&lt; const MachineInstr *, LexicalScope * &gt; &amp;M)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>extractLexicalScopes - Extract instruction ranges for each lexical scopes for the given machine function. <a href="#a0bd8a05addcd1cead5df4a8df86536fa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a634fe3ab2c5e31f655fcd237501829cf">constructScopeNest</a> (LexicalScope *Scope)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>constructScopeNest - Traverse the Scope tree depth-first, storing traversal state in WorkStack and recording the depth-first numbering (setDFSIn, setDFSOut) for edge classification. <a href="#a634fe3ab2c5e31f655fcd237501829cf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa34b0b49ad628f98f3136da336f94667">assignInstructionRanges</a> (SmallVectorImpl&lt; InsnRange &gt; &amp;MIRanges, DenseMap&lt; const MachineInstr *, LexicalScope * &gt; &amp;M)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>assignInstructionRanges - Find ranges of instructions covered by each lexical scope. <a href="#aa34b0b49ad628f98f3136da336f94667">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54cb79a651e5f17a6e93ef16fff7775a">MF</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unordered_map&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dilocalscope">DILocalScope</a> *, <a href="/web-llvm/docs/api/classes/llvm/lexicalscope">LexicalScope</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa1bd881899cabc56107fa5da038742b4">LexicalScopeMap</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>LexicalScopeMap - Tracks the scopes in the current function. <a href="#aa1bd881899cabc56107fa5da038742b4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unordered_map&lt; std::pair&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dilocalscope">DILocalScope</a> *, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dilocation">DILocation</a> * &gt;, <a href="/web-llvm/docs/api/classes/llvm/lexicalscope">LexicalScope</a>, <a href="/web-llvm/docs/api/structs/llvm/pair-hash">pair_hash</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dilocalscope">DILocalScope</a> *, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dilocation">DILocation</a> * &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a59c1be8791a1d4ce89b4dce40cf7f944">InlinedLexicalScopeMap</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>InlinedLexicalScopeMap - Tracks inlined function scopes in current function. <a href="#a59c1be8791a1d4ce89b4dce40cf7f944">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unordered_map&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dilocalscope">DILocalScope</a> *, <a href="/web-llvm/docs/api/classes/llvm/lexicalscope">LexicalScope</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a64231ad67c08fee40649404659712865">AbstractScopeMap</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>AbstractScopeMap - These scopes are not included LexicalScopeMap. <a href="#a64231ad67c08fee40649404659712865">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/lexicalscope">LexicalScope</a> *, 4 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab91bd5b8ef01e31814b1127dcd9cee67">AbstractScopesList</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>AbstractScopesList - Tracks abstract scopes constructed while processing a function. <a href="#ab91bd5b8ef01e31814b1127dcd9cee67">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/lexicalscope">LexicalScope</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2f137a5439c8e7e1aad2f91c1f789e19">CurrentFnLexicalScope</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>CurrentFnLexicalScope - Top level scope for the current function. <a href="#a2f137a5439c8e7e1aad2f91c1f789e19">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dilocation">DILocation</a> *, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/smallptrset">BlockSetT</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad886724972c71e221b285740beb81875">DominatedBlocks</a></td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/lexicalscopes">LexicalScopes</a> - This class provides interface to collect and use lexical scoping information from machine instruction.</p>

<p>Definition at line 141 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/lexicalscopes-h">LexicalScopes.h</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### BlockSetT {#a0254e1b8b19e02f9f01fd111f35e71d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::LexicalScopes::BlockSetT =  SmallPtrSet&lt;const MachineBasicBlock *, 4&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Map a location to the set of basic blocks it dominates.</p>


<p>This is a cache for <a href="#a6478937e0927f9038e58dca2e03e38ab">LexicalScopes::getMachineBasicBlocks</a> results.</p>


<p>Definition at line 253 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/lexicalscopes-h">LexicalScopes.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### LexicalScopes() {#a4c0018016f2b307b109ba4afd66dfa59}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::LexicalScopes::LexicalScopes ()</td>
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



<p>Definition at line 143 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/lexicalscopes-h">LexicalScopes.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### dominates() {#abf24ff038d82eb5079e4719663ef3857}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LexicalScopes::dominates (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dilocation">DILocation</a> * DL, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a>'s lexical scope dominates at least one machine instruction's lexical scope in a given machine basic block.</p>

<p>Declaration at line 168 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/lexicalscopes-h">LexicalScopes.h</a>, definition at line 306 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lexicalscopes-cpp">LexicalScopes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="#a6478937e0927f9038e58dca2e03e38ab">getMachineBasicBlocks</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>.</p>

</div>
</div>

### empty() {#abca17648a9276ce54a3e54d159d6a94d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LexicalScopes::empty ()</td>
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

<p>empty - Return true if there is any lexical scope information available.</p>

<p>Definition at line 153 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/lexicalscopes-h">LexicalScopes.h</a>.</p>

</div>
</div>

### findAbstractScope() {#a97c91dd63cc11f0c4fd4b537b079e8bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LexicalScope * llvm::LexicalScopes::findAbstractScope (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dilocalscope">DILocalScope</a> * N)</td>
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

<p>findAbstractScope - Find an abstract scope or return null.</p>

<p>Definition at line 180 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/lexicalscopes-h">LexicalScopes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### findInlinedScope() {#a975b93f1b5bdac0a6ffcaf130570d4d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LexicalScope * llvm::LexicalScopes::findInlinedScope (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dilocalscope">DILocalScope</a> * N, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dilocation">DILocation</a> * IA)</td>
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

<p>findInlinedScope - Find an inlined scope for the given scope/inlined-at.</p>

<p>Definition at line 186 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/lexicalscopes-h">LexicalScopes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dbgvaluehistorymap/#a19a6a168a50b639280b51eada31cae76">llvm::DbgValueHistoryMap::trimLocationRanges</a>.</p>

</div>
</div>

### findLexicalScope() {#a3245044b58379359df4673c0ed9308b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LexicalScope * LexicalScopes::findLexicalScope (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dilocation">DILocation</a> * DL)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>findLexicalScope - Find lexical scope, either regular or inlined, for the given <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a>.</p>


<p>Return NULL if not found.</p>


<p>Declaration at line 172 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/lexicalscopes-h">LexicalScopes.h</a>, definition at line 124 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lexicalscopes-cpp">LexicalScopes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="#a3245044b58379359df4673c0ed9308b0">findLexicalScope</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>


<p>Referenced by <a href="#a3245044b58379359df4673c0ed9308b0">findLexicalScope</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgvaluehistorymap/#a19a6a168a50b639280b51eada31cae76">llvm::DbgValueHistoryMap::trimLocationRanges</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp/#a1894915deb9e2c5abb856c02fe1513ff">validThroughout</a>.</p>

</div>
</div>

### findLexicalScope() {#aba236eb440fe88eb1906b3e8f00bd037}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LexicalScope * llvm::LexicalScopes::findLexicalScope (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dilocalscope">DILocalScope</a> * N)</td>
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

<p>findLexicalScope - Find regular lexical scope or return null.</p>

<p>Definition at line 192 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/lexicalscopes-h">LexicalScopes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### getAbstractScopesList() {#a82f707a6a97e3c8e715c9122fa8c5ac9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; LexicalScope * &gt; llvm::LexicalScopes::getAbstractScopesList ()</td>
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

<p>getAbstractScopesList - Return a reference to list of abstract scopes.</p>

<p>Definition at line 175 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/lexicalscopes-h">LexicalScopes.h</a>.</p>

</div>
</div>

### getCurrentFunctionScope() {#af526dd6c94f2521992a7296059d3f0ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LexicalScope * llvm::LexicalScopes::getCurrentFunctionScope ()</td>
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

<p>getCurrentFunctionScope - Return lexical scope for the current function.</p>

<p>Definition at line 156 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/lexicalscopes-h">LexicalScopes.h</a>.</p>

</div>
</div>

### getMachineBasicBlocks() {#a6478937e0927f9038e58dca2e03e38ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LexicalScopes::getMachineBasicBlocks (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dilocation">DILocation</a> * DL, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl">SmallPtrSetImpl</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * &gt; &amp; MBBs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>getMachineBasicBlocks - Populate given set using machine basic blocks which have machine instructions that belong to lexical scope identified by <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a>.</p>

<p>Declaration at line 163 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/lexicalscopes-h">LexicalScopes.h</a>, definition at line 280 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lexicalscopes-cpp">LexicalScopes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimplbase/#a16413f1a88d8baca228d0a1b4cc0bfc6">llvm::SmallPtrSetImplBase::clear</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a9d834ae3da8c62c2b668dada51335eb0">llvm::SmallPtrSetImpl&lt; PtrType &gt;::insert</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>.</p>


<p>Referenced by <a href="#abf24ff038d82eb5079e4719663ef3857">dominates</a>.</p>

</div>
</div>

### getOrCreateAbstractScope() {#a2530cf6b1cfff7baf9db14941cef749a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LexicalScope * LexicalScopes::getOrCreateAbstractScope (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dilocalscope">DILocalScope</a> * Scope)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>getOrCreateAbstractScope - Find or create an abstract lexical scope.</p>

<p>Declaration at line 198 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/lexicalscopes-h">LexicalScopes.h</a>, definition at line 212 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lexicalscopes-cpp">LexicalScopes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0e00fad9c34de40b1e31f3aa6f8e024cae1e4c8c9ccd9fc39c391da4bcd093fb2">llvm::Block</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#a2530cf6b1cfff7baf9db14941cef749a">getOrCreateAbstractScope</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>.</p>


<p>Referenced by <a href="#a2530cf6b1cfff7baf9db14941cef749a">getOrCreateAbstractScope</a>.</p>

</div>
</div>

### initialize() {#a3134ce614dc1b5fc41522648d24ff7cb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LexicalScopes::initialize (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; Fn)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>initialize - Scan machine function and constuct lexical scope nest, resets the instance if necessary.</p>


<p>initialize - Scan machine function and constuct lexical scope nest.</p>


<p>Declaration at line 147 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/lexicalscopes-h">LexicalScopes.h</a>, definition at line 51 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lexicalscopes-cpp">LexicalScopes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a4d834f9897d15e3a6349063b5d637cd8">llvm::Function::getSubprogram</a>, <a href="/web-llvm/docs/api/classes/llvm/dicompileunit/#abbc2b566b9aa870d5b7131017b7ba66dadb74da0a389a2704e8e01c66ace2913e">llvm::DICompileUnit::NoDebug</a> and <a href="#a1decd7f30d5c97d10091c1991911d577">reset</a>.</p>

</div>
</div>

### reset() {#a1decd7f30d5c97d10091c1991911d577}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LexicalScopes::reset ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>releaseMemory - release memory.</p>


<p>reset - Reset the instance so that it's prepared for another function.</p>


<p>Declaration at line 150 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/lexicalscopes-h">LexicalScopes.h</a>, definition at line 40 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lexicalscopes-cpp">LexicalScopes.cpp</a>.</p>


<p>Referenced by <a href="#a3134ce614dc1b5fc41522648d24ff7cb">initialize</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### assignInstructionRanges() {#aa34b0b49ad628f98f3136da336f94667}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LexicalScopes::assignInstructionRanges (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#a50e4c9f81d1b75e9f5706df4cdb3c489">InsnRange</a> &gt; &amp; MIRanges, <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *, <a href="/web-llvm/docs/api/classes/llvm/lexicalscope">LexicalScope</a> * &gt; &amp; M)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>assignInstructionRanges - Find ranges of instructions covered by each lexical scope.</p>

<p>Declaration at line 223 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/lexicalscopes-h">LexicalScopes.h</a>, definition at line 259 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lexicalscopes-cpp">LexicalScopes.cpp</a>.</p>

</div>
</div>

### constructScopeNest() {#a634fe3ab2c5e31f655fcd237501829cf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LexicalScopes::constructScopeNest (<a href="/web-llvm/docs/api/classes/llvm/lexicalscope">LexicalScope</a> * Scope)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>constructScopeNest - Traverse the Scope tree depth-first, storing traversal state in WorkStack and recording the depth-first numbering (setDFSIn, setDFSOut) for edge classification.</p>

<p>Declaration at line 221 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/lexicalscopes-h">LexicalScopes.h</a>, definition at line 236 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lexicalscopes-cpp">LexicalScopes.cpp</a>.</p>

</div>
</div>

### extractLexicalScopes() {#a0bd8a05addcd1cead5df4a8df86536fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LexicalScopes::extractLexicalScopes (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#a50e4c9f81d1b75e9f5706df4cdb3c489">InsnRange</a> &gt; &amp; MIRanges, <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *, <a href="/web-llvm/docs/api/classes/llvm/lexicalscope">LexicalScope</a> * &gt; &amp; M)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>extractLexicalScopes - Extract instruction ranges for each lexical scopes for the given machine function.</p>

<p>Declaration at line 219 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/lexicalscopes-h">LexicalScopes.h</a>, definition at line 69 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lexicalscopes-cpp">LexicalScopes.cpp</a>.</p>

</div>
</div>

### getOrCreateInlinedScope() {#ac982fd73b51fba8627980901d3864c54}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LexicalScope * LexicalScopes::getOrCreateInlinedScope (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dilocalscope">DILocalScope</a> * Scope, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dilocation">DILocation</a> * InlinedAt)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>getOrCreateInlinedScope - Find or create an inlined lexical scope.</p>

<p>Declaration at line 214 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/lexicalscopes-h">LexicalScopes.h</a>, definition at line 188 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lexicalscopes-cpp">LexicalScopes.cpp</a>.</p>

</div>
</div>

### getOrCreateLexicalScope() {#a3e3743b320b9436090a0149d29b06bc8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LexicalScope * LexicalScopes::getOrCreateLexicalScope (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dilocalscope">DILocalScope</a> * Scope, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dilocation">DILocation</a> * IA=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>getOrCreateLexicalScope - Find lexical scope for the given Scope/IA.</p>


<p>getOrCreateLexicalScope - Find lexical scope for the given <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a>.</p>


<p>If not available then create new lexical scope.</p>


<p>Declaration at line 203 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/lexicalscopes-h">LexicalScopes.h</a>, definition at line 142 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lexicalscopes-cpp">LexicalScopes.cpp</a>.</p>

</div>
</div>

### getOrCreateLexicalScope() {#a87e0b5f3fc74c81bfb83c198d4184f12}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LexicalScope * llvm::LexicalScopes::getOrCreateLexicalScope (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dilocation">DILocation</a> * DL)</td>
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



<p>Definition at line 205 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/lexicalscopes-h">LexicalScopes.h</a>.</p>

</div>
</div>

### getOrCreateRegularScope() {#a60e3e11262537ac7eeb016dc5a463584}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LexicalScope * LexicalScopes::getOrCreateRegularScope (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dilocalscope">DILocalScope</a> * Scope)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>getOrCreateRegularScope - Find or create a regular lexical scope.</p>

<p>Declaration at line 211 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/lexicalscopes-h">LexicalScopes.h</a>, definition at line 160 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lexicalscopes-cpp">LexicalScopes.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### AbstractScopeMap {#a64231ad67c08fee40649404659712865}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unordered_map&lt;const DILocalScope *, LexicalScope&gt; llvm::LexicalScopes::AbstractScopeMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>AbstractScopeMap - These scopes are not included LexicalScopeMap.</p>

<p>Definition at line 241 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/lexicalscopes-h">LexicalScopes.h</a>.</p>

</div>
</div>

### AbstractScopesList {#ab91bd5b8ef01e31814b1127dcd9cee67}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;LexicalScope *, 4&gt; llvm::LexicalScopes::AbstractScopesList</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>AbstractScopesList - Tracks abstract scopes constructed while processing a function.</p>

<p>Definition at line 245 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/lexicalscopes-h">LexicalScopes.h</a>.</p>

</div>
</div>

### CurrentFnLexicalScope {#a2f137a5439c8e7e1aad2f91c1f789e19}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LexicalScope* llvm::LexicalScopes::CurrentFnLexicalScope = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>CurrentFnLexicalScope - Top level scope for the current function.</p>

<p>Definition at line 249 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/lexicalscopes-h">LexicalScopes.h</a>.</p>

</div>
</div>

### DominatedBlocks {#ad886724972c71e221b285740beb81875}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;const DILocation *, std::unique_ptr&lt;BlockSetT&gt; &gt; llvm::LexicalScopes::DominatedBlocks</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 254 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/lexicalscopes-h">LexicalScopes.h</a>.</p>

</div>
</div>

### InlinedLexicalScopeMap {#a59c1be8791a1d4ce89b4dce40cf7f944}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unordered_map&lt;std::pair&lt;const DILocalScope *, const DILocation *&gt;, LexicalScope, pair_hash&lt;const DILocalScope *, const DILocation *&gt; &gt; llvm::LexicalScopes::InlinedLexicalScopeMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>InlinedLexicalScopeMap - Tracks inlined function scopes in current function.</p>

<p>Definition at line 237 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/lexicalscopes-h">LexicalScopes.h</a>.</p>

</div>
</div>

### LexicalScopeMap {#aa1bd881899cabc56107fa5da038742b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unordered_map&lt;const DILocalScope *, LexicalScope&gt; llvm::LexicalScopes::LexicalScopeMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>LexicalScopeMap - Tracks the scopes in the current function.</p>

<p>Definition at line 230 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/lexicalscopes-h">LexicalScopes.h</a>.</p>

</div>
</div>

### MF {#a54cb79a651e5f17a6e93ef16fff7775a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachineFunction* llvm::LexicalScopes::MF = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 226 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/lexicalscopes-h">LexicalScopes.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/lexicalscopes-h">LexicalScopes.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/lexicalscopes-cpp">LexicalScopes.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>

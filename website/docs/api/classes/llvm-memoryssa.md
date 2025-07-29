---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/memoryssa
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `MemorySSA` Class

<p>Encapsulates <a href="/web-llvm/docs/api/classes/llvm/memoryssa">MemorySSA</a>, including all data associated with memory accesses. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::MemorySSA { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssa-h">llvm/Analysis/MemorySSA.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4b4af87796b358cd0cea30a192003591">AccessList</a> = <a href="/web-llvm/docs/api/classes/llvm/iplist">iplist</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/memoryaccess">MemoryAccess</a>, <a href="/web-llvm/docs/api/structs/llvm/ilist-tag">ilist_tag</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/mssahelpers/allaccesstag">MSSAHelpers::AllAccessTag</a> &gt; &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a043fc380f5e672ab28e6d4d57ab3e2ca">DefsList</a> = <a href="/web-llvm/docs/api/classes/llvm/simple-ilist">simple_ilist</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/memoryaccess">MemoryAccess</a>, <a href="/web-llvm/docs/api/structs/llvm/ilist-tag">ilist_tag</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/mssahelpers/defsonlytag">MSSAHelpers::DefsOnlyTag</a> &gt; &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a74a73d09f6a768f6e03cba3622f75ad7">AccessMap</a> = <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *, std::unique_ptr&lt; <a href="#a4b4af87796b358cd0cea30a192003591">AccessList</a> &gt; &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8150df0c766020e467eb16b03233b148">DefsMap</a> = <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *, std::unique_ptr&lt; <a href="#a043fc380f5e672ab28e6d4d57ab3e2ca">DefsList</a> &gt; &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">enum class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">VerificationLevel { <a href="#a8a5ce5c05f5824d269bc5751104973c7">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">InsertionPlace { <a href="#a9773fde54683945b9e34a0f2e5c1a5a5">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Used in various insertion functions to specify whether we are talking about the beginning or end of a block. <a href="#a9773fde54683945b9e34a0f2e5c1a5a5">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abfd3c432d063870284f175107228d8c5">MemorySSAUpdater</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a49f6b5c5e36a86395a7f91838768798d">MemorySSA</a> (Function &amp;, AliasAnalysis *, DominatorTree *)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae00fb511f1753cc06aaeed20f8de5d5c">MemorySSA</a> (Loop &amp;, AliasAnalysis *, DominatorTree *)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa853d12d6716fb18650576eea9d03c26">MemorySSA</a> (MemorySSA &amp;&amp;)=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae7375c161ecaf6b6f4ebd6abfcb5ce71">~MemorySSA</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/memoryssawalker">MemorySSAWalker</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a949151a1ebd664cb397323294cec0e53">getWalker</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/memoryssawalker">MemorySSAWalker</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ef6f9107316d963f20b9003b7668c4e">getSkipSelfWalker</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/memoryuseordef">MemoryUseOrDef</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab15de610fca1c900038bf3c333919e45">getMemoryAccess</a> (const Instruction *I) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given a memory Mod/Ref'ing instruction, get the <a href="/web-llvm/docs/api/classes/llvm/memoryssa">MemorySSA</a> access associated with it. <a href="#ab15de610fca1c900038bf3c333919e45">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/memoryphi">MemoryPhi</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac191373743120120bdde2006f1531aa4">getMemoryAccess</a> (const BasicBlock *BB) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa863c7ef18d17217ad6fb984e2ba4d93">getDomTree</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0211e050a705084ef5e653127a7fb3df">dump</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa9b4a650e1a6de2061538a19be3a234">print</a> (raw_ostream &amp;) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae3b89ffde42778289bcbd8a187199420">isLiveOnEntryDef</a> (const MemoryAccess *MA) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if <span class="doxyComputerOutput">MA</span> represents the live on entry value. <a href="#ae3b89ffde42778289bcbd8a187199420">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/memoryaccess">MemoryAccess</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac806483fa7b54b1eae5ebde9fd459b7e">getLiveOnEntryDef</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a4b4af87796b358cd0cea30a192003591">AccessList</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a183ce8029c259d7f9edacadcc7448f06">getBlockAccesses</a> (const BasicBlock *BB) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the list of <a href="/web-llvm/docs/api/classes/llvm/memoryaccess">MemoryAccess</a>'s for a given basic block. <a href="#a183ce8029c259d7f9edacadcc7448f06">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a043fc380f5e672ab28e6d4d57ab3e2ca">DefsList</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad586af665c013c65c83a31294555f996">getBlockDefs</a> (const BasicBlock *BB) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the list of <a href="/web-llvm/docs/api/classes/llvm/memorydef">MemoryDef</a>'s and <a href="/web-llvm/docs/api/classes/llvm/memoryphi">MemoryPhi</a>'s for a given basic block. <a href="#ad586af665c013c65c83a31294555f996">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade88aedcbd2b55711000cf3e36c0fc91">locallyDominates</a> (const MemoryAccess *A, const MemoryAccess *B) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given two memory accesses in the same basic block, determine whether <a href="/web-llvm/docs/api/classes/llvm/memoryaccess">MemoryAccess</a> <span class="doxyComputerOutput">A</span> dominates <a href="/web-llvm/docs/api/classes/llvm/memoryaccess">MemoryAccess</a> <span class="doxyComputerOutput">B</span>. <a href="#ade88aedcbd2b55711000cf3e36c0fc91">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a56004f54560e9950f6eb148cb5dfa0a3">dominates</a> (const MemoryAccess *A, const MemoryAccess *B) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given two memory accesses in potentially different blocks, determine whether <a href="/web-llvm/docs/api/classes/llvm/memoryaccess">MemoryAccess</a> <span class="doxyComputerOutput">A</span> dominates <a href="/web-llvm/docs/api/classes/llvm/memoryaccess">MemoryAccess</a> <span class="doxyComputerOutput">B</span>. <a href="#a56004f54560e9950f6eb148cb5dfa0a3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4e92272bbf0049770569394d4956918b">dominates</a> (const MemoryAccess *A, const Use &amp;B) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given a <a href="/web-llvm/docs/api/classes/llvm/memoryaccess">MemoryAccess</a> and a <a href="/web-llvm/docs/api/classes/llvm/use">Use</a>, determine whether <a href="/web-llvm/docs/api/classes/llvm/memoryaccess">MemoryAccess</a> <span class="doxyComputerOutput">A</span> dominates <a href="/web-llvm/docs/api/classes/llvm/use">Use</a> <span class="doxyComputerOutput">B</span>. <a href="#a4e92272bbf0049770569394d4956918b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a88b10d37f671e58cf138ac84a8257c17">verifyMemorySSA</a> (VerificationLevel=VerificationLevel::Fast) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Verify that <a href="/web-llvm/docs/api/classes/llvm/memoryssa">MemorySSA</a> is self consistent (IE definitions dominate all uses, uses appear in the right places). <a href="#a88b10d37f671e58cf138ac84a8257c17">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd30a2d319950c138d97d5b3356342b5">ensureOptimizedUses</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>By default, uses are <em>not</em> optimized during <a href="/web-llvm/docs/api/classes/llvm/memoryssa">MemorySSA</a> construction. <a href="#acd30a2d319950c138d97d5b3356342b5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#ae457f1cf451ed893666c4a384e58f8e5">AliasAnalysis</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a09b19c342a68cda17cb92c8fd9804cc4">getAA</a> ()</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename IterT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a6dcb5e3d63691e83e0fdc0d67148077a">verifyOrderingDominationAndDefUses</a> (IterT Blocks, VerificationLevel=VerificationLevel::Fast) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Verify ordering: the order and existence of MemoryAccesses matches the order and existence of memory affecting instructions. <a href="#a6dcb5e3d63691e83e0fdc0d67148077a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename IterT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aceea1ce23f1a6764f5fd02fa8fde9713">verifyDominationNumbers</a> (IterT Blocks) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Verify that all of the blocks we believe to have valid domination numbers actually have valid domination numbers. <a href="#aceea1ce23f1a6764f5fd02fa8fde9713">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename IterT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad34709127ea574767024538890e0e514">verifyPrevDefInPhis</a> (IterT Blocks) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a4b4af87796b358cd0cea30a192003591">AccessList</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a78d0057da016dd16107bcbd0f069aad8">getWritableBlockAccesses</a> (const BasicBlock *BB) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a043fc380f5e672ab28e6d4d57ab3e2ca">DefsList</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a99c136a293cd78a1986bc2501e2ca137">getWritableBlockDefs</a> (const BasicBlock *BB) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a131110a75135a123427d3280dff1fef4">moveTo</a> (MemoryUseOrDef *What, BasicBlock *BB, AccessList::iterator Where)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a13073dfc4fd40b8388fb60885e493f8d">moveTo</a> (MemoryAccess *What, BasicBlock *BB, InsertionPlace Point)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1aa1ce1cb2192a65bf9e113882cd4ae9">renamePass</a> (BasicBlock *BB, MemoryAccess *IncomingVal, SmallPtrSetImpl&lt; BasicBlock * &gt; &amp;Visited)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd0427b84adce00e5b26f993c7aa48c8">removeFromLookups</a> (MemoryAccess *)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Properly remove <span class="doxyComputerOutput">MA</span> from all of <a href="/web-llvm/docs/api/classes/llvm/memoryssa">MemorySSA</a>'s lookup tables. <a href="#acd0427b84adce00e5b26f993c7aa48c8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae20e35b50e6cf67987421c996cf14a8c">removeFromLists</a> (MemoryAccess *, bool ShouldDelete=true)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Properly remove <span class="doxyComputerOutput">MA</span> from all of <a href="/web-llvm/docs/api/classes/llvm/memoryssa">MemorySSA</a>'s lists. <a href="#ae20e35b50e6cf67987421c996cf14a8c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8bc47ee66a3ac3b5f1a57c497048b090">insertIntoListsForBlock</a> (MemoryAccess *, const BasicBlock *, InsertionPlace)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a97891043f9eacb9b0e18e22767cc7802">insertIntoListsBefore</a> (MemoryAccess *, const BasicBlock *, AccessList::iterator)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/memoryuseordef">MemoryUseOrDef</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9939794555fe9e24e885d55e301de803">createDefinedAccess</a> (Instruction *, MemoryAccess *, const MemoryUseOrDef *Template=nullptr, bool CreationMustSucceed=true)</td>
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

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/memoryssa/cachingwalker">CachingWalker</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab1fe41d146a7c374483dcaeadebdbf6c">getWalkerImpl</a> ()</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename IterT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aa5f392d0c9835d9e57f0378bfb187c5a">buildMemorySSA</a> (BatchAAResults &amp;BAA, IterT Blocks)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac00ea77ceceb48b2895927bdbda9de06">prepareForMoveTo</a> (MemoryAccess *, BasicBlock *)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa6c3ccc8d57f0391906b968f43b3e98b">verifyUseInDefs</a> (MemoryAccess *, MemoryAccess *) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Verify the def-use lists in <a href="/web-llvm/docs/api/classes/llvm/memoryssa">MemorySSA</a>, by verifying that <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/use">Use</a></span> appears in the use list of <span class="doxyComputerOutput">Def</span>. <a href="#aa6c3ccc8d57f0391906b968f43b3e98b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae8329f01f0adf4e4e5582906094c20b4">markUnreachableAsLiveOnEntry</a> (BasicBlock *BB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This handles unreachable block accesses by deleting phi nodes in unreachable blocks, and marking all other unreachable <a href="/web-llvm/docs/api/classes/llvm/memoryaccess">MemoryAccess</a>'s as being uses of the live on entry definition. <a href="#ae8329f01f0adf4e4e5582906094c20b4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/memoryphi">MemoryPhi</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5c0bfd3770ad87bc5d9eb0b25a79506a">createMemoryPhi</a> (BasicBlock *BB)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename AliasAnalysisType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/memoryuseordef">MemoryUseOrDef</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#acc97e9eadd33c31028fddfeb977b9948">createNewAccess</a> (Instruction *, AliasAnalysisType *, const MemoryUseOrDef *Template=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper function to create new memory accesses. <a href="#acc97e9eadd33c31028fddfeb977b9948">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac359ac2337252a5e40f7a410e29286a1">placePHINodes</a> (const SmallPtrSetImpl&lt; BasicBlock * &gt; &amp;)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/memoryaccess">MemoryAccess</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeaa6c211e903a25bc0ca8d6e2cad2023">renameBlock</a> (BasicBlock *, MemoryAccess *, bool)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Rename a single basic block into <a href="/web-llvm/docs/api/classes/llvm/memoryssa">MemorySSA</a> form. <a href="#aeaa6c211e903a25bc0ca8d6e2cad2023">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aecf86642708d444b478880776765cdc5">renameSuccessorPhis</a> (BasicBlock *, MemoryAccess *, bool)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ea0789f679a45f5053ea74316def1de">renamePass</a> (DomTreeNode *, MemoryAccess *IncomingVal, SmallPtrSetImpl&lt; BasicBlock * &gt; &amp;Visited, bool SkipVisited=false, bool RenameAllUses=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is the standard SSA renaming algorithm. <a href="#a2ea0789f679a45f5053ea74316def1de">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a4b4af87796b358cd0cea30a192003591">AccessList</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a15149cbaf5567f27e49e41a6f965ac34">getOrCreateAccessList</a> (const BasicBlock *)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a043fc380f5e672ab28e6d4d57ab3e2ca">DefsList</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a51b01927f064891af68ace526a4f9be1">getOrCreateDefsList</a> (const BasicBlock *)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e0f168aba3bdf8cc523a0b7bb29fb6f">renumberBlock</a> (const BasicBlock *) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Perform a local numbering on blocks so that instruction ordering can be determined in constant time. <a href="#a2e0f168aba3bdf8cc523a0b7bb29fb6f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#ae457f1cf451ed893666c4a384e58f8e5">AliasAnalysis</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9bfebb1c5c9f151ca7054789586a8fb5">AA</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a86af47ce966d32ff64902066ae34eb61">DT</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a78840a488cd8b369b060f4af2b417b13">F</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b20cacf6bd91e129925ebb200fbb88f">L</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, <a href="/web-llvm/docs/api/classes/llvm/memoryaccess">MemoryAccess</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8984431a62626eae31e3a1bd1876094e">ValueToMemoryAccess</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">AccessMap</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aff4fed477ce60887e4d645a6957dc8bb">PerBlockAccesses</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DefsMap</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad5a87419198d5efc849a42ec7ad8db4d">PerBlockDefs</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/memoryaccess">MemoryAccess</a>, <a href="/web-llvm/docs/api/structs/llvm/valuedeleter">ValueDeleter</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4dd3b14809ce8fe0a9fe6df605f6cae9">LiveOnEntryDef</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallptrset">SmallPtrSet</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *, 16 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb1ea38dec30d0ebaaedcbd122c67446">BlockNumberingValid</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/memoryaccess">MemoryAccess</a> *, unsigned long &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae8ec64261cb036ddf4281b81e14a3b05">BlockNumbering</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/memoryssa/clobberwalkerbase">ClobberWalkerBase</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a620baa9e8dafd4ed7485182d9124a774">WalkerBase</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/memoryssa/cachingwalker">CachingWalker</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f5218f0a4b886b7cd1e268c12420d51">Walker</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/memoryssa/skipselfwalker">SkipSelfWalker</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a944949e064d4a513deae18506d568a7a">SkipWalker</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0a17d4dbd713639766530b0c470fc23b">NextID</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af898ae6026843245ed77dd167def0835">IsOptimized</a> = false</td>
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

<p>Encapsulates <a href="/web-llvm/docs/api/classes/llvm/memoryssa">MemorySSA</a>, including all data associated with memory accesses.</p>

<p>Definition at line 701 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssa-h">MemorySSA.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### AccessList {#a4b4af87796b358cd0cea30a192003591}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::MemorySSA::AccessList =  iplist&lt;MemoryAccess, ilist_tag&lt;MSSAHelpers::AllAccessTag&gt;&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 752 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssa-h">MemorySSA.h</a>.</p>

</div>
</div>

### DefsList {#a043fc380f5e672ab28e6d4d57ab3e2ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::MemorySSA::DefsList = 
      simple_ilist&lt;MemoryAccess, ilist_tag&lt;MSSAHelpers::DefsOnlyTag&gt;&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 753 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssa-h">MemorySSA.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Typedefs

### AccessMap {#a74a73d09f6a768f6e03cba3622f75ad7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::MemorySSA::AccessMap =  DenseMap&lt;const BasicBlock *, std::unique_ptr&lt;AccessList&gt;&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 859 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssa-h">MemorySSA.h</a>.</p>

</div>
</div>

### DefsMap {#a8150df0c766020e467eb16b03233b148}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::MemorySSA::DefsMap =  DenseMap&lt;const BasicBlock *, std::unique_ptr&lt;DefsList&gt;&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 860 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssa-h">MemorySSA.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Enumerations

### InsertionPlace {#a9773fde54683945b9e34a0f2e5c1a5a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::MemorySSA::InsertionPlace </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Used in various insertion functions to specify whether we are talking about the beginning or end of a block.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Beginning<a id="a9773fde54683945b9e34a0f2e5c1a5a5ad02ebd2ab52855a8e9fb8082c9530085"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">End<a id="a9773fde54683945b9e34a0f2e5c1a5a5a542e7b754a1b868794fa2f47256a1d97"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BeforeTerminator<a id="a9773fde54683945b9e34a0f2e5c1a5a5a7806c120eb87aea9fbb52fed327e09de"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 790 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssa-h">MemorySSA.h</a>.</p>

</div>
</div>

### VerificationLevel {#a8a5ce5c05f5824d269bc5751104973c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum class llvm::MemorySSA::VerificationLevel </td>
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
<td class="doxyEnumItemName">Fast<a id="a8a5ce5c05f5824d269bc5751104973c7ae16b5b7f26f54214445cbe38d72c2828"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Full<a id="a8a5ce5c05f5824d269bc5751104973c7abbd47109890259c0127154db1af26c75"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 783 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssa-h">MemorySSA.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Friends

### MemorySSAUpdater {#abfd3c432d063870284f175107228d8c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/memoryssaupdater">MemorySSAUpdater</a></td>
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


<p>Definition at line 803 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssa-h">MemorySSA.h</a>.</p>


<p>References <a href="#a8a5ce5c05f5824d269bc5751104973c7ae16b5b7f26f54214445cbe38d72c2828">Fast</a>, <a href="#abfd3c432d063870284f175107228d8c5">MemorySSAUpdater</a>, <a href="#aceea1ce23f1a6764f5fd02fa8fde9713">verifyDominationNumbers</a>, <a href="#a6dcb5e3d63691e83e0fdc0d67148077a">verifyOrderingDominationAndDefUses</a> and <a href="#ad34709127ea574767024538890e0e514">verifyPrevDefInPhis</a>.</p>


<p>Referenced by <a href="#abfd3c432d063870284f175107228d8c5">MemorySSAUpdater</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### MemorySSA() {#a49f6b5c5e36a86395a7f91838768798d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MemorySSA::MemorySSA (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; Func, <a href="/web-llvm/docs/api/namespaces/llvm/#ae457f1cf451ed893666c4a384e58f8e5">AliasAnalysis</a> * AA, <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> * DT)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 703 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssa-h">MemorySSA.h</a>, definition at line 1233 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memoryssa-cpp">MemorySSA.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a949151a1ebd664cb397323294cec0e53">getWalker</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9b5301a03dc90d7ac00440e2de4d9149">llvm::iterator_range</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/memoryssa/clobberwalkerbase/#a195c8f56de5acfa828fa5d3215e9a497">llvm::MemorySSA::ClobberWalkerBase::ClobberWalkerBase</a>, <a href="#aa853d12d6716fb18650576eea9d03c26">MemorySSA</a> and <a href="/web-llvm/docs/api/classes/llvm/memoryssa/optimizeuses/#ad7fb8e8bcc5cf17ad15225ab3cb9e401">llvm::MemorySSA::OptimizeUses::OptimizeUses</a>.</p>

</div>
</div>

### MemorySSA() {#ae00fb511f1753cc06aaeed20f8de5d5c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MemorySSA::MemorySSA (<a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> &amp; L, <a href="/web-llvm/docs/api/namespaces/llvm/#ae457f1cf451ed893666c4a384e58f8e5">AliasAnalysis</a> * AA, <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> * DT)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 704 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssa-h">MemorySSA.h</a>, definition at line 1251 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memoryssa-cpp">MemorySSA.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a949151a1ebd664cb397323294cec0e53">getWalker</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a51c7cbd21e1104ee6841c18d7daa6edb">llvm::map_range</a>.</p>

</div>
</div>

### MemorySSA() {#aa853d12d6716fb18650576eea9d03c26}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MemorySSA::MemorySSA (<a href="/web-llvm/docs/api/classes/llvm/memoryssa">MemorySSA</a> &amp;&amp;)</td>
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



<p>Definition at line 708 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssa-h">MemorySSA.h</a>.</p>


<p>References <a href="#a2ef6f9107316d963f20b9003b7668c4e">getSkipSelfWalker</a>, <a href="#a949151a1ebd664cb397323294cec0e53">getWalker</a> and <a href="#a49f6b5c5e36a86395a7f91838768798d">MemorySSA</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~MemorySSA() {#ae7375c161ecaf6b6f4ebd6abfcb5ce71}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MemorySSA::~MemorySSA ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 710 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssa-h">MemorySSA.h</a>, definition at line 1272 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memoryssa-cpp">MemorySSA.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/user/#a48ec5fcee6d2c17c723e8e67f169f948">llvm::User::dropAllReferences</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### dominates() {#a56004f54560e9950f6eb148cb5dfa0a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MemorySSA::dominates (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/memoryaccess">MemoryAccess</a> * A, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/memoryaccess">MemoryAccess</a> * B)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Given two memory accesses in potentially different blocks, determine whether <a href="/web-llvm/docs/api/classes/llvm/memoryaccess">MemoryAccess</a> <span class="doxyComputerOutput">A</span> dominates <a href="/web-llvm/docs/api/classes/llvm/memoryaccess">MemoryAccess</a> <span class="doxyComputerOutput">B</span>.</p>

<p>Declaration at line 777 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssa-h">MemorySSA.h</a>, definition at line 2173 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memoryssa-cpp">MemorySSA.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/memoryaccess/#a9a9c59da949d32a269725b6e254d426f">llvm::MemoryAccess::getBlock</a>, <a href="#ae3b89ffde42778289bcbd8a187199420">isLiveOnEntryDef</a> and <a href="#ade88aedcbd2b55711000cf3e36c0fc91">locallyDominates</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a158e2caed73e4b5d2ad70c1b2a0e0cc8">llvm::canSinkOrHoistInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/memoryssa-cpp/#a930e3a524f031bdb14fe281e4eff4219">checkClobberSanity</a>, <a href="#a4e92272bbf0049770569394d4956918b">dominates</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopunroll-cpp/#a92bfc4d7aa6add742c2a82b2e8f61455">getMatchingValue</a>, <a href="#a6dcb5e3d63691e83e0fdc0d67148077a">verifyOrderingDominationAndDefUses</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/memcpyoptimizer-cpp/#ab06d3147949b764919b5ad90014afdfd">writtenBetween</a>.</p>

</div>
</div>

### dominates() {#a4e92272bbf0049770569394d4956918b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MemorySSA::dominates (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/memoryaccess">MemoryAccess</a> * A, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/use">Use</a> &amp; B)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Given a <a href="/web-llvm/docs/api/classes/llvm/memoryaccess">MemoryAccess</a> and a <a href="/web-llvm/docs/api/classes/llvm/use">Use</a>, determine whether <a href="/web-llvm/docs/api/classes/llvm/memoryaccess">MemoryAccess</a> <span class="doxyComputerOutput">A</span> dominates <a href="/web-llvm/docs/api/classes/llvm/use">Use</a> <span class="doxyComputerOutput">B</span>.</p>

<p>Declaration at line 781 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssa-h">MemorySSA.h</a>, definition at line 2186 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memoryssa-cpp">MemorySSA.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#a56004f54560e9950f6eb148cb5dfa0a3">dominates</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryaccess/#a9a9c59da949d32a269725b6e254d426f">llvm::MemoryAccess::getBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/use/#a53a48d67682705c5f7f06ffc850fd622">llvm::Use::getUser</a> and <a href="#ade88aedcbd2b55711000cf3e36c0fc91">locallyDominates</a>.</p>

</div>
</div>

### dump() {#a0211e050a705084ef5e653127a7fb3df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_DUMP_METHOD void MemorySSA::dump ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 729 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssa-h">MemorySSA.h</a>, definition at line 1902 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memoryssa-cpp">MemorySSA.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#aa863693eef567397d9c292da5bf22d34">LLVM_DUMP_METHOD</a> and <a href="#afa9b4a650e1a6de2061538a19be3a234">print</a>.</p>

</div>
</div>

### ensureOptimizedUses() {#acd30a2d319950c138d97d5b3356342b5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MemorySSA::ensureOptimizedUses ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>By default, uses are <em>not</em> optimized during <a href="/web-llvm/docs/api/classes/llvm/memoryssa">MemorySSA</a> construction.</p>


<p>Calling this method will attempt to optimize all MemoryUses, if this has not happened yet for this <a href="/web-llvm/docs/api/classes/llvm/memoryssa">MemorySSA</a> instance. This should be done if you plan to query the clobbering access for most uses, or if you walk the def-use chain of uses.</p>


<p>Declaration at line 797 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssa-h">MemorySSA.h</a>, definition at line 2200 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memoryssa-cpp">MemorySSA.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/memoryssa/optimizeuses/#a195658a43b30378309ff4e62455dc137">llvm::MemorySSA::OptimizeUses::optimizeUses</a>.</p>

</div>
</div>

### getAA() {#a09b19c342a68cda17cb92c8fd9804cc4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AliasAnalysis &amp; llvm::MemorySSA::getAA ()</td>
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



<p>Definition at line 799 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssa-h">MemorySSA.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/licm-cpp/#a28d9fc94843828b60459abd31b7e82c6">pointerInvalidatedByLoop</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/moveautoinit-cpp/#aa91fc385b3c151e89ac23b656e9bf8b6">usersDominator</a>.</p>

</div>
</div>

### getBlockAccesses() {#a183ce8029c259d7f9edacadcc7448f06}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const AccessList * llvm::MemorySSA::getBlockAccesses (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB)</td>
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

<p>Return the list of <a href="/web-llvm/docs/api/classes/llvm/memoryaccess">MemoryAccess</a>'s for a given basic block.</p>


<p>This list is not modifiable by the user.</p>


<p>Definition at line 759 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssa-h">MemorySSA.h</a>.</p>


<p>Reference <a href="#a78d0057da016dd16107bcbd0f069aad8">getWritableBlockAccesses</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a158e2caed73e4b5d2ad70c1b2a0e0cc8">llvm::canSinkOrHoistInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/licm-cpp/#a8046d863469d9c33287fa4a673d00571">foreachMemoryAccess</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-licm-cpp-/#af11bb20a72885fc6999bfbcb21bd39fe">anonymous{LICM.cpp}::isOnlyMemoryAccess</a>, <a href="/web-llvm/docs/api/classes/llvm/sinkandhoistlicmflags/#a30d4121b007bf8064374e069fd2de689">llvm::SinkAndHoistLICMFlags::SinkAndHoistLICMFlags</a>, <a href="#aceea1ce23f1a6764f5fd02fa8fde9713">verifyDominationNumbers</a> and <a href="#a6dcb5e3d63691e83e0fdc0d67148077a">verifyOrderingDominationAndDefUses</a>.</p>

</div>
</div>

### getBlockDefs() {#ad586af665c013c65c83a31294555f996}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DefsList * llvm::MemorySSA::getBlockDefs (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB)</td>
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

<p>Return the list of <a href="/web-llvm/docs/api/classes/llvm/memorydef">MemoryDef</a>'s and <a href="/web-llvm/docs/api/classes/llvm/memoryphi">MemoryPhi</a>'s for a given basic block.</p>


<p>This list is not modifiable by the user.</p>


<p>Definition at line 767 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssa-h">MemorySSA.h</a>.</p>


<p>Reference <a href="#a99c136a293cd78a1986bc2501e2ca137">getWritableBlockDefs</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-licm-cpp-/#a9d7f9cdd2e085f1453ac2f3186255fdc">anonymous{LICM.cpp}::isReadOnly</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/licm-cpp/#aed7e046ac6f7dd5ff0edb6e7b7a30e2e">pointerInvalidatedByBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#a050cc2b2d1467ffcad6a825f1141424c">unswitchAllTrivialConditions</a>, <a href="#a6dcb5e3d63691e83e0fdc0d67148077a">verifyOrderingDominationAndDefUses</a> and <a href="#ad34709127ea574767024538890e0e514">verifyPrevDefInPhis</a>.</p>

</div>
</div>

### getDomTree() {#aa863c7ef18d17217ad6fb984e2ba4d93}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DominatorTree &amp; llvm::MemorySSA::getDomTree ()</td>
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



<p>Definition at line 727 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssa-h">MemorySSA.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/analysis/memoryssa-cpp/#a930e3a524f031bdb14fe281e4eff4219">checkClobberSanity</a>.</p>

</div>
</div>

### getLiveOnEntryDef() {#ac806483fa7b54b1eae5ebde9fd459b7e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MemoryAccess * llvm::MemorySSA::getLiveOnEntryDef ()</td>
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



<p>Definition at line 743 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssa-h">MemorySSA.h</a>.</p>

</div>
</div>

### getMemoryAccess() {#ab15de610fca1c900038bf3c333919e45}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MemoryUseOrDef * llvm::MemorySSA::getMemoryAccess (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I)</td>
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

<p>Given a memory Mod/Ref'ing instruction, get the <a href="/web-llvm/docs/api/classes/llvm/memoryssa">MemorySSA</a> access associated with it.</p>


<p>If passed a basic block gets the memory phi node that exists for that block, if there is one. Otherwise, this will get a <a href="/web-llvm/docs/api/classes/llvm/memoryuseordef">MemoryUseOrDef</a>.</p>


<p>Definition at line 719 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssa-h">MemorySSA.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a3e627c32543ca70720c4270a8b11da3f">llvm::cast_or_null</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#a0eaf12b7854445670a7b0af3fe87b86c">buildPartialInvariantUnswitchConditionalBranch</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a158e2caed73e4b5d2ad70c1b2a0e0cc8">llvm::canSinkOrHoistInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/licm-cpp/#a25f0b41add9507b8eafadfbc4a090d6c">cloneInstructionInExitBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopunroll-cpp/#a92bfc4d7aa6add742c2a82b2e8f61455">getMatchingValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/memoryssaupdater-cpp/#ac59d7eb34d6eb5a384a90489cd5dc7bc">getNewDefiningAccessForClone</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae78f734e49b5ad94836bf32dda101ec6">llvm::hasPartialIVCondition</a>, <a href="/web-llvm/docs/api/classes/llvm/loop/#a9f134722dec96eeaf23085a29b5da9f7">llvm::Loop::makeLoopInvariant</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa76a2cf19b821f320ab439d5659ef4b9">llvm::MergeBlockIntoPredecessor</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/licm-cpp/#a22d7cc599c50e811dff1546c5ccb8794">moveInstructionBefore</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/moveautoinit-cpp/#a8f3d27d1b480f6b3c90405707be76295">runMoveAutoInit</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopinstsimplify-cpp/#ac7156f23f48b5eb96ead0522896d7574">simplifyLoopInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopsink-cpp/#a89374dd34ed723e45309afa9ac10eb83">sinkInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#af3ac46dde637293a34d0ff7b619a656b">turnGuardIntoBranch</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/moveautoinit-cpp/#aa91fc385b3c151e89ac23b656e9bf8b6">usersDominator</a>, <a href="#a6dcb5e3d63691e83e0fdc0d67148077a">verifyOrderingDominationAndDefUses</a> and <a href="#ad34709127ea574767024538890e0e514">verifyPrevDefInPhis</a>.</p>

</div>
</div>

### getMemoryAccess() {#ac191373743120120bdde2006f1531aa4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MemoryPhi * llvm::MemorySSA::getMemoryAccess (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB)</td>
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



<p>Definition at line 723 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssa-h">MemorySSA.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a3e627c32543ca70720c4270a8b11da3f">llvm::cast_or_null</a>.</p>

</div>
</div>

### getSkipSelfWalker() {#a2ef6f9107316d963f20b9003b7668c4e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MemorySSAWalker * MemorySSA::getSkipSelfWalker ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 713 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssa-h">MemorySSA.h</a>, definition at line 1603 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memoryssa-cpp">MemorySSA.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/licm-cpp/#a329ad21a549f7f43ad50b65f4d3ca487">getClobberingMemoryAccess</a> and <a href="#aa853d12d6716fb18650576eea9d03c26">MemorySSA</a>.</p>

</div>
</div>

### getWalker() {#a949151a1ebd664cb397323294cec0e53}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MemorySSAWalker * MemorySSA::getWalker ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 712 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssa-h">MemorySSA.h</a>, definition at line 1590 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memoryssa-cpp">MemorySSA.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopunroll-cpp/#a92bfc4d7aa6add742c2a82b2e8f61455">getMatchingValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#af55cf9792d5f9186df02c58b337a1511">llvm::AMDGPU::isClobberedInFunction</a>, <a href="#a49f6b5c5e36a86395a7f91838768798d">MemorySSA</a>, <a href="#ae00fb511f1753cc06aaeed20f8de5d5c">MemorySSA</a>, <a href="#aa853d12d6716fb18650576eea9d03c26">MemorySSA</a>, <a href="#acd0427b84adce00e5b26f993c7aa48c8">removeFromLookups</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/memcpyoptimizer-cpp/#ab06d3147949b764919b5ad90014afdfd">writtenBetween</a>.</p>

</div>
</div>

### isLiveOnEntryDef() {#ae3b89ffde42778289bcbd8a187199420}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MemorySSA::isLiveOnEntryDef (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/memoryaccess">MemoryAccess</a> * MA)</td>
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

<p>Return true if <span class="doxyComputerOutput">MA</span> represents the live on entry value.</p>


<p>Loads and stores from pointer arguments and other global values may be defined by memory operations that do not occur in the current function, so they may be live on entry to the function. <a href="/web-llvm/docs/api/classes/llvm/memoryssa">MemorySSA</a> represents such memory state by the live on entry definition, which is guaranteed to occur before any other memory access in the function.</p>


<p>Definition at line 739 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssa-h">MemorySSA.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a158e2caed73e4b5d2ad70c1b2a0e0cc8">llvm::canSinkOrHoistInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/memoryssa-cpp/#a930e3a524f031bdb14fe281e4eff4219">checkClobberSanity</a>, <a href="#a56004f54560e9950f6eb148cb5dfa0a3">dominates</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/memoryssaupdater-cpp/#ac59d7eb34d6eb5a384a90489cd5dc7bc">getNewDefiningAccessForClone</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/memcpyoptimizer-cpp/#a781cb075ecf323c9670d5695db656718">hasUndefContents</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#af55cf9792d5f9186df02c58b337a1511">llvm::AMDGPU::isClobberedInFunction</a>, <a href="#ade88aedcbd2b55711000cf3e36c0fc91">locallyDominates</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/licm-cpp/#a28d9fc94843828b60459abd31b7e82c6">pointerInvalidatedByLoop</a>.</p>

</div>
</div>

### locallyDominates() {#ade88aedcbd2b55711000cf3e36c0fc91}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MemorySSA::locallyDominates (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/memoryaccess">MemoryAccess</a> * Dominator, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/memoryaccess">MemoryAccess</a> * Dominatee)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Given two memory accesses in the same basic block, determine whether <a href="/web-llvm/docs/api/classes/llvm/memoryaccess">MemoryAccess</a> <span class="doxyComputerOutput">A</span> dominates <a href="/web-llvm/docs/api/classes/llvm/memoryaccess">MemoryAccess</a> <span class="doxyComputerOutput">B</span>.</p>


<p>Determine, for two memory accesses in the same block, whether <span class="doxyComputerOutput">Dominator</span> dominates <span class="doxyComputerOutput">Dominatee</span>.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>True if <span class="doxyComputerOutput">Dominator</span> dominates <span class="doxyComputerOutput">Dominatee</span>.</p></dd>
</dl>


<p>Declaration at line 773 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssa-h">MemorySSA.h</a>, definition at line 2142 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memoryssa-cpp">MemorySSA.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryaccess/#a9a9c59da949d32a269725b6e254d426f">llvm::MemoryAccess::getBlock</a> and <a href="#ae3b89ffde42778289bcbd8a187199420">isLiveOnEntryDef</a>.</p>


<p>Referenced by <a href="#a56004f54560e9950f6eb148cb5dfa0a3">dominates</a>, <a href="#a4e92272bbf0049770569394d4956918b">dominates</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/licm-cpp/#aed7e046ac6f7dd5ff0edb6e7b7a30e2e">pointerInvalidatedByBlock</a>.</p>

</div>
</div>

### print() {#afa9b4a650e1a6de2061538a19be3a234}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MemorySSA::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 730 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssa-h">MemorySSA.h</a>, definition at line 1893 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memoryssa-cpp">MemorySSA.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a739b30c811f1eece61b05320ddf44e5b">llvm::GlobalValue::getParent</a> and <a href="/web-llvm/docs/api/classes/llvm/module/#a8ee5166cba8576e41617fc96aec1fb85">llvm::Module::print</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/memoryaccess/#a0323cfb2d9032e14069108390831f5b7">llvm::MemoryAccess::dump</a>, <a href="#a0211e050a705084ef5e653127a7fb3df">dump</a> and <a href="/web-llvm/docs/api/classes/llvm/memoryaccess/#aadff5eaae30623b4077b9dec90f29dcf">llvm::MemoryAccess::print</a>.</p>

</div>
</div>

### verifyMemorySSA() {#a88b10d37f671e58cf138ac84a8257c17}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MemorySSA::verifyMemorySSA (<a href="#a8a5ce5c05f5824d269bc5751104973c7">VerificationLevel</a> VL=<a href="#a8a5ce5c05f5824d269bc5751104973c7ae16b5b7f26f54214445cbe38d72c2828">VerificationLevel::Fast</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Verify that <a href="/web-llvm/docs/api/classes/llvm/memoryssa">MemorySSA</a> is self consistent (IE definitions dominate all uses, uses appear in the right places).</p>


<p>This is used by unit tests.</p>


<p>Declaration at line 786 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssa-h">MemorySSA.h</a>, definition at line 1905 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memoryssa-cpp">MemorySSA.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a8a5ce5c05f5824d269bc5751104973c7abbd47109890259c0127154db1af26c75">Full</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9b5301a03dc90d7ac00440e2de4d9149">llvm::iterator_range</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a51c7cbd21e1104ee6841c18d7daa6edb">llvm::map_range</a>, <a href="#aceea1ce23f1a6764f5fd02fa8fde9713">verifyDominationNumbers</a>, <a href="#a6dcb5e3d63691e83e0fdc0d67148077a">verifyOrderingDominationAndDefUses</a> and <a href="#ad34709127ea574767024538890e0e514">verifyPrevDefInPhis</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a74b422e2c15d859ba49911cc329f11d7">llvm::deleteDeadLoop</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5efa2c3e00054566f1baaebc766461a4">llvm::hoistRegion</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#aa8f270ce4d001ee9e7839aa11c607931">injectPendingInvariantConditions</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopsimplifycfg-cpp/#a5a5d8a7a6d46886bfb6350ed47c0f225">mergeBlocksIntoPredecessors</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae8cc923f4e20540201f1cd1225811b9f">llvm::promoteLoopAccessesToScalars</a>, <a href="/web-llvm/docs/api/classes/llvm/functiontolooppassadaptor/#aee681bfb37f62d30a1d0a1f47d73b4f1">llvm::FunctionToLoopPassAdaptor::run</a>, <a href="/web-llvm/docs/api/classes/llvm/loopflattenpass/#af1670b8924fecfd8a7f0c4dc140bf603">llvm::LoopFlattenPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/loopinstsimplifypass/#a3e829edc978ccb3a88ff5532faf75879">llvm::LoopInstSimplifyPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/looprotatepass/#aa87b74697e2ab3e760eddd32b866c508">llvm::LoopRotatePass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/simpleloopunswitchpass/#ae7088b7b5c8bd069497f13e3e1990eff">llvm::SimpleLoopUnswitchPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/memcpyoptpass/#a18e40505cff07b625ae84a227804a9f4">llvm::MemCpyOptPass::runImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/moveautoinit-cpp/#a8f3d27d1b480f6b3c90405707be76295">runMoveAutoInit</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopinstsimplify-cpp/#ac7156f23f48b5eb96ead0522896d7574">simplifyLoopInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopsimplify-cpp/#ad54a3c6c671e583284ff935bfde3368c">simplifyOneLoop</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad30fb60072e2996200ea591628e33c5a">llvm::sinkRegion</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a33f79ea6e1fd1b8ba93c75519b1c929c">llvm::splitBlockBefore</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#af3ac46dde637293a34d0ff7b619a656b">turnGuardIntoBranch</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#a2e6301db15e4516c92e21f33761886c6">turnSelectIntoBranch</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#aae4261fb86bc9023c3383785afa66b9a">unswitchNontrivialInvariants</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#a6a082aa2e05f44f7dab89e2ff8c582ff">unswitchTrivialBranch</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#aadf6036e1d19c8ba91242af6ec48d40b">unswitchTrivialSwitch</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### createDefinedAccess() {#a9939794555fe9e24e885d55e301de803}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MemoryUseOrDef * MemorySSA::createDefinedAccess (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I, <a href="/web-llvm/docs/api/classes/llvm/memoryaccess">MemoryAccess</a> * Definition, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/memoryuseordef">MemoryUseOrDef</a> * Template=nullptr, bool CreationMustSucceed=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
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



<p>Declaration at line 842 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssa-h">MemorySSA.h</a>, definition at line 1725 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memoryssa-cpp">MemorySSA.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryuseordef/#a5c00de32cf1426ab78c346e7a251d608">llvm::MemoryUseOrDef::setDefiningAccess</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a88ee8e4eea43084bd8964682683da88ca278c491bdd8a53618c149c4ac790da34">Template</a>.</p>

</div>
</div>

### getWritableBlockAccesses() {#a78d0057da016dd16107bcbd0f069aad8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AccessList * llvm::MemorySSA::getWritableBlockAccesses (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB)</td>
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



<p>Definition at line 812 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssa-h">MemorySSA.h</a>.</p>


<p>Referenced by <a href="#a183ce8029c259d7f9edacadcc7448f06">getBlockAccesses</a> and <a href="#a97891043f9eacb9b0e18e22767cc7802">insertIntoListsBefore</a>.</p>

</div>
</div>

### getWritableBlockDefs() {#a99c136a293cd78a1986bc2501e2ca137}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DefsList * llvm::MemorySSA::getWritableBlockDefs (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB)</td>
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



<p>Definition at line 818 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssa-h">MemorySSA.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/simple-ilist/#a9ed194b42c5b8ba68764c26760c9ddfe">llvm::simple_ilist&lt; T, Options &gt;::end</a>.</p>


<p>Referenced by <a href="#ad586af665c013c65c83a31294555f996">getBlockDefs</a>.</p>

</div>
</div>

### insertIntoListsBefore() {#a97891043f9eacb9b0e18e22767cc7802}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MemorySSA::insertIntoListsBefore (<a href="/web-llvm/docs/api/classes/llvm/memoryaccess">MemoryAccess</a> * What, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB, <a href="/web-llvm/docs/api/classes/llvm/iplist-impl/#a4563732eae31ee14694e7ce17a5a6749">AccessList::iterator</a> InsertPt)</td>
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



<p>Declaration at line 840 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssa-h">MemorySSA.h</a>, definition at line 1650 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memoryssa-cpp">MemorySSA.cpp</a>.</p>


<p>References <a href="#a78d0057da016dd16107bcbd0f069aad8">getWritableBlockAccesses</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>.</p>


<p>Referenced by <a href="#a131110a75135a123427d3280dff1fef4">moveTo</a>.</p>

</div>
</div>

### insertIntoListsForBlock() {#a8bc47ee66a3ac3b5f1a57c497048b090}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MemorySSA::insertIntoListsForBlock (<a href="/web-llvm/docs/api/classes/llvm/memoryaccess">MemoryAccess</a> * NewAccess, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB, <a href="#a9773fde54683945b9e34a0f2e5c1a5a5">InsertionPlace</a> Point)</td>
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



<p>Declaration at line 838 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssa-h">MemorySSA.h</a>, definition at line 1618 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memoryssa-cpp">MemorySSA.cpp</a>.</p>


<p>References <a href="#a9773fde54683945b9e34a0f2e5c1a5a5ad02ebd2ab52855a8e9fb8082c9530085">Beginning</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7b49849160e7f089916f83c52511da9e">llvm::find_if_not</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>.</p>


<p>Referenced by <a href="#a13073dfc4fd40b8388fb60885e493f8d">moveTo</a>.</p>

</div>
</div>

### moveTo() {#a131110a75135a123427d3280dff1fef4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MemorySSA::moveTo (<a href="/web-llvm/docs/api/classes/llvm/memoryuseordef">MemoryUseOrDef</a> * What, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB, <a href="/web-llvm/docs/api/classes/llvm/iplist-impl/#a4563732eae31ee14694e7ce17a5a6749">AccessList::iterator</a> Where)</td>
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



<p>Declaration at line 827 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssa-h">MemorySSA.h</a>, definition at line 1694 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memoryssa-cpp">MemorySSA.cpp</a>.</p>


<p>Reference <a href="#a97891043f9eacb9b0e18e22767cc7802">insertIntoListsBefore</a>.</p>

</div>
</div>

### moveTo() {#a13073dfc4fd40b8388fb60885e493f8d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MemorySSA::moveTo (<a href="/web-llvm/docs/api/classes/llvm/memoryaccess">MemoryAccess</a> * What, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB, <a href="#a9773fde54683945b9e34a0f2e5c1a5a5">InsertionPlace</a> Point)</td>
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



<p>Declaration at line 828 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssa-h">MemorySSA.h</a>, definition at line 1700 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memoryssa-cpp">MemorySSA.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a9773fde54683945b9e34a0f2e5c1a5a5ad02ebd2ab52855a8e9fb8082c9530085">Beginning</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryaccess/#a9a9c59da949d32a269725b6e254d426f">llvm::MemoryAccess::getBlock</a>, <a href="#a8bc47ee66a3ac3b5f1a57c497048b090">insertIntoListsForBlock</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>.</p>

</div>
</div>

### removeFromLists() {#ae20e35b50e6cf67987421c996cf14a8c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MemorySSA::removeFromLists (<a href="/web-llvm/docs/api/classes/llvm/memoryaccess">MemoryAccess</a> * MA, bool ShouldDelete=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
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

<p>Properly remove <span class="doxyComputerOutput">MA</span> from all of <a href="/web-llvm/docs/api/classes/llvm/memoryssa">MemorySSA</a>'s lists.</p>


<p>Because of the way the intrusive list and use lists work, it is important to do removal in the right order. ShouldDelete defaults to true, and will cause the memory access to also be deleted, not just removed.</p>


<p>Declaration at line 837 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssa-h">MemorySSA.h</a>, definition at line 1866 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memoryssa-cpp">MemorySSA.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a018d5142c1a4469d9296a26a59fe2783">llvm::BasicBlock::erase</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryaccess/#a9a9c59da949d32a269725b6e254d426f">llvm::MemoryAccess::getBlock</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>.</p>

</div>
</div>

### removeFromLookups() {#acd0427b84adce00e5b26f993c7aa48c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MemorySSA::removeFromLookups (<a href="/web-llvm/docs/api/classes/llvm/memoryaccess">MemoryAccess</a> * MA)</td>
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

<p>Properly remove <span class="doxyComputerOutput">MA</span> from all of <a href="/web-llvm/docs/api/classes/llvm/memoryssa">MemorySSA</a>'s lookup tables.</p>

<p>Declaration at line 836 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssa-h">MemorySSA.h</a>, definition at line 1839 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memoryssa-cpp">MemorySSA.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a018d5142c1a4469d9296a26a59fe2783">llvm::BasicBlock::erase</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryaccess/#a9a9c59da949d32a269725b6e254d426f">llvm::MemoryAccess::getBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryuseordef/#abe63c310031eb3c578b122f0c31739d7">llvm::MemoryUseOrDef::getMemoryInst</a>, <a href="#a949151a1ebd664cb397323294cec0e53">getWalker</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryssawalker/#a8bb8d1cc3b3a95d81ee75395cadf83c3">llvm::MemorySSAWalker::invalidateInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryuseordef/#a5c00de32cf1426ab78c346e7a251d608">llvm::MemoryUseOrDef::setDefiningAccess</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#a9d7de807ebdfe1819df3ff6cb0f16158">llvm::Value::use_empty</a>.</p>

</div>
</div>

### renamePass() {#a1aa1ce1cb2192a65bf9e113882cd4ae9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MemorySSA::renamePass (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB, <a href="/web-llvm/docs/api/classes/llvm/memoryaccess">MemoryAccess</a> * IncomingVal, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl">SmallPtrSetImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * &gt; &amp; Visited)</td>
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



<p>Definition at line 831 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssa-h">MemorySSA.h</a>.</p>


<p>Reference <a href="#a1aa1ce1cb2192a65bf9e113882cd4ae9">renamePass</a>.</p>


<p>Referenced by <a href="#a1aa1ce1cb2192a65bf9e113882cd4ae9">renamePass</a>.</p>

</div>
</div>

### verifyDominationNumbers() {#aceea1ce23f1a6764f5fd02fa8fde9713}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename IterT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MemorySSA::verifyDominationNumbers (IterT Blocks)</td>
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

<p>Verify that all of the blocks we believe to have valid domination numbers actually have valid domination numbers.</p>

<p>Declaration at line 808 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssa-h">MemorySSA.h</a>, definition at line 1979 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memoryssa-cpp">MemorySSA.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a1f475b0df44ebd7169e720fa1bf9169e">llvm::SmallPtrSetImpl&lt; PtrType &gt;::count</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimplbase/#af8a50544090e81ac83601aff8f4b0142">llvm::SmallPtrSetImplBase::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a11045c7973ab24a8d6315b61fa337d4e">llvm::SmallPtrSetImpl&lt; PtrType &gt;::erase</a> and <a href="#a183ce8029c259d7f9edacadcc7448f06">getBlockAccesses</a>.</p>


<p>Referenced by <a href="#abfd3c432d063870284f175107228d8c5">MemorySSAUpdater</a> and <a href="#a88b10d37f671e58cf138ac84a8257c17">verifyMemorySSA</a>.</p>

</div>
</div>

### verifyOrderingDominationAndDefUses() {#a6dcb5e3d63691e83e0fdc0d67148077a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename IterT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MemorySSA::verifyOrderingDominationAndDefUses (IterT Blocks, <a href="#a8a5ce5c05f5824d269bc5751104973c7">VerificationLevel</a> VL=<a href="#a8a5ce5c05f5824d269bc5751104973c7ae16b5b7f26f54214445cbe38d72c2828">VerificationLevel::Fast</a>)</td>
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

<p>Verify ordering: the order and existence of MemoryAccesses matches the order and existence of memory affecting instructions.</p>


<p>Verify domination: each definition dominates all of its uses. Verify def-uses: the immediate use information - walk all the memory accesses and verifying that, for each use, it appears in the appropriate def's use list</p>


<p>Declaration at line 806 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssa-h">MemorySSA.h</a>, definition at line 2021 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memoryssa-cpp">MemorySSA.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a8a045d250952c0867382a9840ee18fdf">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::begin</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#aac0ea55010b7b1a301e65a0baea057aa">llvm::SmallVectorImpl&lt; T &gt;::clear</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="#a56004f54560e9950f6eb148cb5dfa0a3">dominates</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a075e34e98605d0e7c289763a104869ac">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::end</a>, <a href="#a8a5ce5c05f5824d269bc5751104973c7abbd47109890259c0127154db1af26c75">Full</a>, <a href="#a183ce8029c259d7f9edacadcc7448f06">getBlockAccesses</a>, <a href="#ad586af665c013c65c83a31294555f996">getBlockDefs</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryuseordef/#a20455da69cab73871b8c0111f0afe712">llvm::MemoryUseOrDef::getDefiningAccess</a>, <a href="#ab15de610fca1c900038bf3c333919e45">getMemoryAccess</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acd1cd968cb420c82d70926920fcdc7d7">llvm::is_contained</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3f211484edf604716a6c80030b0a0375">llvm::pred_size</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acb22fb04083152eee862457e42e8dc31">llvm::predecessors</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#abf855b7cd63a0cd7f73759e396f280c9">llvm::Value::uses</a>.</p>


<p>Referenced by <a href="#abfd3c432d063870284f175107228d8c5">MemorySSAUpdater</a> and <a href="#a88b10d37f671e58cf138ac84a8257c17">verifyMemorySSA</a>.</p>

</div>
</div>

### verifyPrevDefInPhis() {#ad34709127ea574767024538890e0e514}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename IterT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MemorySSA::verifyPrevDefInPhis (IterT Blocks)</td>
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



<p>Declaration at line 809 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssa-h">MemorySSA.h</a>, definition at line 1942 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memoryssa-cpp">MemorySSA.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ad586af665c013c65c83a31294555f996">getBlockDefs</a>, <a href="#ab15de610fca1c900038bf3c333919e45">getMemoryAccess</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>


<p>Referenced by <a href="#abfd3c432d063870284f175107228d8c5">MemorySSAUpdater</a> and <a href="#a88b10d37f671e58cf138ac84a8257c17">verifyMemorySSA</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### buildMemorySSA() {#aa5f392d0c9835d9e57f0378bfb187c5a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename IterT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MemorySSA::buildMemorySSA (<a href="/web-llvm/docs/api/classes/llvm/batchaaresults">BatchAAResults</a> &amp; BAA, IterT Blocks)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 854 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssa-h">MemorySSA.h</a>, definition at line 1519 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memoryssa-cpp">MemorySSA.cpp</a>.</p>

</div>
</div>

### createMemoryPhi() {#a5c0bfd3770ad87bc5d9eb0b25a79506a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MemoryPhi * MemorySSA::createMemoryPhi (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 863 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssa-h">MemorySSA.h</a>, definition at line 1716 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memoryssa-cpp">MemorySSA.cpp</a>.</p>

</div>
</div>

### createNewAccess() {#acc97e9eadd33c31028fddfeb977b9948}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename AliasAnalysisType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MemoryUseOrDef * MemorySSA::createNewAccess (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I, AliasAnalysisType * AAP, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/memoryuseordef">MemoryUseOrDef</a> * Template=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Helper function to create new memory accesses.</p>

<p>Declaration at line 865 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssa-h">MemorySSA.h</a>, definition at line 1758 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memoryssa-cpp">MemorySSA.cpp</a>.</p>

</div>
</div>

### getOrCreateAccessList() {#a15149cbaf5567f27e49e41a6f965ac34}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MemorySSA::AccessList * MemorySSA::getOrCreateAccessList (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 873 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssa-h">MemorySSA.h</a>, definition at line 1279 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memoryssa-cpp">MemorySSA.cpp</a>.</p>

</div>
</div>

### getOrCreateDefsList() {#a51b01927f064891af68ace526a4f9be1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MemorySSA::DefsList * MemorySSA::getOrCreateDefsList (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 874 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssa-h">MemorySSA.h</a>, definition at line 1287 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memoryssa-cpp">MemorySSA.cpp</a>.</p>

</div>
</div>

### getWalkerImpl() {#ab1fe41d146a7c374483dcaeadebdbf6c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MemorySSA::CachingWalker * MemorySSA::getWalkerImpl ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 852 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssa-h">MemorySSA.h</a>, definition at line 1592 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memoryssa-cpp">MemorySSA.cpp</a>.</p>

</div>
</div>

### markUnreachableAsLiveOnEntry() {#ae8329f01f0adf4e4e5582906094c20b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MemorySSA::markUnreachableAsLiveOnEntry (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This handles unreachable block accesses by deleting phi nodes in unreachable blocks, and marking all other unreachable <a href="/web-llvm/docs/api/classes/llvm/memoryaccess">MemoryAccess</a>'s as being uses of the live on entry definition.</p>

<p>Declaration at line 862 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssa-h">MemorySSA.h</a>, definition at line 1196 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memoryssa-cpp">MemorySSA.cpp</a>.</p>

</div>
</div>

### placePHINodes() {#ac359ac2337252a5e40f7a410e29286a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MemorySSA::placePHINodes (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl">SmallPtrSetImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * &gt; &amp; DefiningBlocks)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 867 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssa-h">MemorySSA.h</a>, definition at line 1505 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memoryssa-cpp">MemorySSA.cpp</a>.</p>

</div>
</div>

### prepareForMoveTo() {#ac00ea77ceceb48b2895927bdbda9de06}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MemorySSA::prepareForMoveTo (<a href="/web-llvm/docs/api/classes/llvm/memoryaccess">MemoryAccess</a> * What, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 856 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssa-h">MemorySSA.h</a>, definition at line 1678 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memoryssa-cpp">MemorySSA.cpp</a>.</p>

</div>
</div>

### renameBlock() {#aeaa6c211e903a25bc0ca8d6e2cad2023}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MemoryAccess * MemorySSA::renameBlock (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB, <a href="/web-llvm/docs/api/classes/llvm/memoryaccess">MemoryAccess</a> * IncomingVal, bool RenameAllUses)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Rename a single basic block into <a href="/web-llvm/docs/api/classes/llvm/memoryssa">MemorySSA</a> form.</p>


<p>Uses the standard SSA renaming algorithm.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The new incoming value.</p></dd>
</dl>


<p>Declaration at line 868 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssa-h">MemorySSA.h</a>, definition at line 1122 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memoryssa-cpp">MemorySSA.cpp</a>.</p>

</div>
</div>

### renamePass() {#a2ea0789f679a45f5053ea74316def1de}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MemorySSA::renamePass (<a href="/web-llvm/docs/api/namespaces/llvm/#a58b9df85470fc4e2a8066ff6a62e5a34">DomTreeNode</a> * Root, <a href="/web-llvm/docs/api/classes/llvm/memoryaccess">MemoryAccess</a> * IncomingVal, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl">SmallPtrSetImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * &gt; &amp; Visited, bool SkipVisited=false, bool RenameAllUses=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This is the standard SSA renaming algorithm.</p>


<p>We walk the dominator tree in preorder, renaming accesses, and then filling in phi nodes in our successors.</p>


<p>Declaration at line 870 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssa-h">MemorySSA.h</a>, definition at line 1146 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memoryssa-cpp">MemorySSA.cpp</a>.</p>

</div>
</div>

### renameSuccessorPhis() {#aecf86642708d444b478880776765cdc5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MemorySSA::renameSuccessorPhis (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB, <a href="/web-llvm/docs/api/classes/llvm/memoryaccess">MemoryAccess</a> * IncomingVal, bool RenameAllUses)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 869 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssa-h">MemorySSA.h</a>, definition at line 1095 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memoryssa-cpp">MemorySSA.cpp</a>.</p>

</div>
</div>

### renumberBlock() {#a2e0f168aba3bdf8cc523a0b7bb29fb6f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MemorySSA::renumberBlock (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * B)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Perform a local numbering on blocks so that instruction ordering can be determined in constant time.</p>


<p>TODO: We currently just number in order. If we numbered by N, we could allow at least N-1 sequences of insertBefore or insertAfter (and at least log2(N) sequences of mixed before and after) without needing to invalidate the numbering.</p>


<p>Declaration at line 875 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssa-h">MemorySSA.h</a>, definition at line 2129 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memoryssa-cpp">MemorySSA.cpp</a>.</p>

</div>
</div>

### verifyUseInDefs() {#aa6c3ccc8d57f0391906b968f43b3e98b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MemorySSA::verifyUseInDefs (<a href="/web-llvm/docs/api/classes/llvm/memoryaccess">MemoryAccess</a> * Def, <a href="/web-llvm/docs/api/classes/llvm/memoryaccess">MemoryAccess</a> * Use)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Verify the def-use lists in <a href="/web-llvm/docs/api/classes/llvm/memoryssa">MemorySSA</a>, by verifying that <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/use">Use</a></span> appears in the use list of <span class="doxyComputerOutput">Def</span>.</p>

<p>Declaration at line 857 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssa-h">MemorySSA.h</a>, definition at line 2113 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memoryssa-cpp">MemorySSA.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### AA {#a9bfebb1c5c9f151ca7054789586a8fb5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AliasAnalysis* llvm::MemorySSA::AA = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 876 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssa-h">MemorySSA.h</a>.</p>

</div>
</div>

### BlockNumbering {#ae8ec64261cb036ddf4281b81e14a3b05}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;const MemoryAccess *, unsigned long&gt; llvm::MemorySSA::BlockNumbering</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel mutable">mutable</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 898 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssa-h">MemorySSA.h</a>.</p>

</div>
</div>

### BlockNumberingValid {#afb1ea38dec30d0ebaaedcbd122c67446}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallPtrSet&lt;const BasicBlock *, 16&gt; llvm::MemorySSA::BlockNumberingValid</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel mutable">mutable</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 897 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssa-h">MemorySSA.h</a>.</p>

</div>
</div>

### DT {#a86af47ce966d32ff64902066ae34eb61}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DominatorTree* llvm::MemorySSA::DT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 877 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssa-h">MemorySSA.h</a>.</p>

</div>
</div>

### F {#a78840a488cd8b369b060f4af2b417b13}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Function* llvm::MemorySSA::F = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 878 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssa-h">MemorySSA.h</a>.</p>

</div>
</div>

### IsOptimized {#af898ae6026843245ed77dd167def0835}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MemorySSA::IsOptimized = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 905 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssa-h">MemorySSA.h</a>.</p>

</div>
</div>

### L {#a5b20cacf6bd91e129925ebb200fbb88f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Loop* llvm::MemorySSA::L = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 879 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssa-h">MemorySSA.h</a>.</p>

</div>
</div>

### LiveOnEntryDef {#a4dd3b14809ce8fe0a9fe6df605f6cae9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;MemoryAccess, ValueDeleter&gt; llvm::MemorySSA::LiveOnEntryDef</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 892 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssa-h">MemorySSA.h</a>.</p>

</div>
</div>

### NextID {#a0a17d4dbd713639766530b0c470fc23b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MemorySSA::NextID = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 904 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssa-h">MemorySSA.h</a>.</p>

</div>
</div>

### PerBlockAccesses {#aff4fed477ce60887e4d645a6957dc8bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AccessMap llvm::MemorySSA::PerBlockAccesses</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 890 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssa-h">MemorySSA.h</a>.</p>

</div>
</div>

### PerBlockDefs {#ad5a87419198d5efc849a42ec7ad8db4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DefsMap llvm::MemorySSA::PerBlockDefs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 891 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssa-h">MemorySSA.h</a>.</p>

</div>
</div>

### SkipWalker {#a944949e064d4a513deae18506d568a7a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;SkipSelfWalker&gt; llvm::MemorySSA::SkipWalker</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 903 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssa-h">MemorySSA.h</a>.</p>

</div>
</div>

### ValueToMemoryAccess {#a8984431a62626eae31e3a1bd1876094e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;const Value *, MemoryAccess *&gt; llvm::MemorySSA::ValueToMemoryAccess</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 882 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssa-h">MemorySSA.h</a>.</p>

</div>
</div>

### Walker {#a0f5218f0a4b886b7cd1e268c12420d51}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;CachingWalker&gt; llvm::MemorySSA::Walker</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 902 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssa-h">MemorySSA.h</a>.</p>

</div>
</div>

### WalkerBase {#a620baa9e8dafd4ed7485182d9124a774}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;ClobberWalkerBase&gt; llvm::MemorySSA::WalkerBase</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 901 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssa-h">MemorySSA.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssa-h">MemorySSA.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/analysis/memoryssa-cpp">MemorySSA.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>

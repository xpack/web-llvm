---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-codegenprepare-cpp-/addressingmodematcher
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `AddressingModeMatcher` Class

<p>A helper class for matching addressing modes. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class anonymous{CodeGenPrepare.cpp}::AddressingModeMatcher { ... }
</div>

## Private Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2bb823db523814bd908bc06727231b08">AddressingModeMatcher</a> (SmallVectorImpl&lt; Instruction * &gt; &amp;AMI, const TargetLowering &amp;TLI, const TargetRegisterInfo &amp;TRI, const LoopInfo &amp;LI, const std::function&lt; const DominatorTree &amp;()&gt; getDTFn, Type *AT, unsigned AS, Instruction *MI, ExtAddrMode &amp;AM, const SetOfInstrs &amp;InsertedInsts, InstrToOrigTy &amp;PromotedInsts, TypePromotionTransaction &amp;TPT, std::pair&lt; AssertingVH&lt; GetElementPtrInst &gt;, int64_t &gt; &amp;LargeOffsetGEP, bool OptSize, ProfileSummaryInfo *PSI, BlockFrequencyInfo *BFI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abd48db079eae8e49332408a9cbe745cf">matchScaledValue</a> (Value *ScaleReg, int64_t Scale, unsigned Depth)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Try adding ScaleReg*Scale to the current addressing mode. <a href="#abd48db079eae8e49332408a9cbe745cf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a26bb3cdbd5f3ac36e41f1098e7023efc">matchAddr</a> (Value *Addr, unsigned Depth)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If we can, try to add the value of 'Addr' into the current addressing mode. <a href="#a26bb3cdbd5f3ac36e41f1098e7023efc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b83aeacaba3be9b9b9d30384f0022fd">matchOperationAddr</a> (User *AddrInst, unsigned Opcode, unsigned Depth, bool *MovedAway=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given an instruction or constant expr, see if we can fold the operation into the addressing mode. <a href="#a0b83aeacaba3be9b9b9d30384f0022fd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab16956010f28f7c3884e9924850b02ca">isProfitableToFoldIntoAddressingMode</a> (Instruction *I, ExtAddrMode &amp;AMBefore, ExtAddrMode &amp;AMAfter)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>It is possible for the addressing mode of the machine to fold the specified instruction into a load or store that ultimately uses it. <a href="#ab16956010f28f7c3884e9924850b02ca">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a750ec615cdb16dc4c622d5a91b74f291">valueAlreadyLiveAtInst</a> (Value *Val, Value *KnownLive1, Value *KnownLive2)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if Val is already known to be live at the use site that we're folding it into. <a href="#a750ec615cdb16dc4c622d5a91b74f291">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa6573874aabded328ee705e22effb014">isPromotionProfitable</a> (unsigned NewCost, unsigned OldCost, Value *PromotedOperand) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Check whether or not promoting an instruction to a wider type is profitable. <a href="#aa6573874aabded328ee705e22effb014">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * &gt; &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1316b26e7b91042c63155f52cc13ea4b">AddrModeInsts</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlowering">TargetLowering</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a06ef2b5c917c90c930e6fc24cfd9a52d">TLI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a48027822a550886fe2c99da543b18bc0">TRI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adecb7387883d586236f1cc72f7b7d634">DL</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a50de527a586a5fd5ebdc302f299c7e6a">LI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::function&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> &amp;()&gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7f18b3885cfc3b708ef5436eeda9e3b4">getDTFn</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac64c806ec47f162ed49a833a2f59ddd7">AccessTy</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>AccessTy/MemoryInst - This is the type for the access (e.g. <a href="#ac64c806ec47f162ed49a833a2f59ddd7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb9379ea4388700f1f7f54f6b974230e">AddrSpace</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a72fdc4d1b4e2760147df46e9f655bf5c">MemoryInst</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-codegenprepare-cpp-/extaddrmode">ExtAddrMode</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c8725fc519e8d9da6546f35dd03cec5">AddrMode</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is the addressing mode that we're building up. <a href="#a7c8725fc519e8d9da6546f35dd03cec5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/anonymous-codegenprepare-cpp-/#af2dad33e47a12a0b01b11d97d390f7ee">SetOfInstrs</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae5fd735ede73bfb7b96c291d0ace0e3e">InsertedInsts</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The instructions inserted by other <a href="/web-llvm/docs/api/classes/anonymous-codegenprepare-cpp-/codegenprepare">CodeGenPrepare</a> optimizations. <a href="#ae5fd735ede73bfb7b96c291d0ace0e3e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-codegenprepare-cpp-/#a71622f7f81af67784beaf8b1420aa76d">InstrToOrigTy</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a299f8eee052c8185969fc01dcc9c9fa4">PromotedInsts</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A map from the instructions to their type before promotion. <a href="#a299f8eee052c8185969fc01dcc9c9fa4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-codegenprepare-cpp-/typepromotiontransaction">TypePromotionTransaction</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf6bb746ce0f3c0d4cfe7f07400cb4cc">TPT</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The ongoing transaction where every action should be registered. <a href="#abf6bb746ce0f3c0d4cfe7f07400cb4cc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/assertingvh">AssertingVH</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/getelementptrinst">GetElementPtrInst</a> &gt;, int64_t &gt; &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8d52b1f082e79be0b2d338026efeb3ea">LargeOffsetGEP</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a971a22087bde2040323e2c797281f4a9">IgnoreProfitability</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is set to true when we should not do profitability checks. <a href="#a971a22087bde2040323e2c797281f4a9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1f948ff6ae7b2419806cba6406fe0855">OptSize</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True if we are optimizing for size. <a href="#a1f948ff6ae7b2419806cba6406fe0855">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/profilesummaryinfo">ProfileSummaryInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a17b1873dd1a9be616e12a01e4263cba3">PSI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/blockfrequencyinfo">BlockFrequencyInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab0b6a5592665b1ed7b3fd580847d1f19">BFI</a></td>
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

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/anonymous-codegenprepare-cpp-/extaddrmode">ExtAddrMode</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a592ce6f54154b0ca1d672869951cad6b">Match</a> (Value *V, Type *AccessTy, unsigned AS, Instruction *MemoryInst, SmallVectorImpl&lt; Instruction * &gt; &amp;AddrModeInsts, const TargetLowering &amp;TLI, const LoopInfo &amp;LI, const std::function&lt; const DominatorTree &amp;()&gt; getDTFn, const TargetRegisterInfo &amp;TRI, const SetOfInstrs &amp;InsertedInsts, InstrToOrigTy &amp;PromotedInsts, TypePromotionTransaction &amp;TPT, std::pair&lt; AssertingVH&lt; GetElementPtrInst &gt;, int64_t &gt; &amp;LargeOffsetGEP, bool OptSize, ProfileSummaryInfo *PSI, BlockFrequencyInfo *BFI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Find the maximal addressing mode that a load/store of V can fold, give an access type of AccessTy. <a href="#a592ce6f54154b0ca1d672869951cad6b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>A helper class for matching addressing modes.</p>


<p>This encapsulates the logic for matching the target-legal addressing modes.</p>


<p>Definition at line 3744 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>


<div class="doxySectionDef">

## Private Constructors

### AddressingModeMatcher() {#a2bb823db523814bd908bc06727231b08}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{CodeGenPrepare.cpp}::AddressingModeMatcher::AddressingModeMatcher (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * &gt; &amp; AMI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlowering">TargetLowering</a> &amp; TLI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> &amp; TRI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a> &amp; LI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::function&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> &amp;()&gt; getDTFn, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * AT, unsigned AS, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * MI, <a href="/web-llvm/docs/api/structs/anonymous-codegenprepare-cpp-/extaddrmode">ExtAddrMode</a> &amp; AM, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/anonymous-codegenprepare-cpp-/#af2dad33e47a12a0b01b11d97d390f7ee">SetOfInstrs</a> &amp; InsertedInsts, <a href="/web-llvm/docs/api/namespaces/anonymous-codegenprepare-cpp-/#a71622f7f81af67784beaf8b1420aa76d">InstrToOrigTy</a> &amp; PromotedInsts, <a href="/web-llvm/docs/api/classes/anonymous-codegenprepare-cpp-/typepromotiontransaction">TypePromotionTransaction</a> &amp; TPT, std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/assertingvh">AssertingVH</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/getelementptrinst">GetElementPtrInst</a> &gt;, int64_t &gt; &amp; LargeOffsetGEP, bool OptSize, <a href="/web-llvm/docs/api/classes/llvm/profilesummaryinfo">ProfileSummaryInfo</a> * PSI, <a href="/web-llvm/docs/api/classes/llvm/blockfrequencyinfo">BlockFrequencyInfo</a> * BFI)</td>
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



<p>Definition at line 3784 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### isProfitableToFoldIntoAddressingMode() {#ab16956010f28f7c3884e9924850b02ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AddressingModeMatcher::isProfitableToFoldIntoAddressingMode (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I, <a href="/web-llvm/docs/api/structs/anonymous-codegenprepare-cpp-/extaddrmode">ExtAddrMode</a> &amp; AMBefore, <a href="/web-llvm/docs/api/structs/anonymous-codegenprepare-cpp-/extaddrmode">ExtAddrMode</a> &amp; AMAfter)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>It is possible for the addressing mode of the machine to fold the specified instruction into a load or store that ultimately uses it.</p>


<p>However, the specified instruction has multiple uses. Given this, it may actually increase register pressure to fold it into the load. For example, consider this code:</p>



<pre><code>X = ...
Y = X+1
use(Y)   -&gt; nonload/store
Z = Y+1
load Z
</code></pre>


<p>In this case, Y has multiple uses, and can be folded into the load of Z (yielding load [X+2]). However, doing this will cause both "X" and "X+1" to be live at the <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/localizer-cpp/#a428090a453f41a199ef67fc3f2179fbc">use(Y)</a> line. If we don't fold Y into load Z, we use one fewer register. Since Y can't be folded into "use(Y)" we don't increase the number of computations either.</p>


<p>Note that this (like most of <a href="/web-llvm/docs/api/classes/anonymous-codegenprepare-cpp-/codegenprepare">CodeGenPrepare</a>) is just a rough heuristic. If X was live across 'load Z' for other reasons, we actually <em>would</em> want to fold the addressing mode in the Z case. This would make Y die earlier.</p>


<p>Definition at line 3835 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

### isPromotionProfitable() {#aa6573874aabded328ee705e22effb014}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AddressingModeMatcher::isPromotionProfitable (unsigned NewCost, unsigned OldCost, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * PromotedOperand)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Check whether or not promoting an instruction to a wider type is profitable.</p>


<p><span class="doxyComputerOutput">NewCost</span> gives the cost of extension instructions created by the promotion. <span class="doxyComputerOutput">OldCost</span> gives the cost of extension instructions before the promotion plus the number of instructions that have been matched in the addressing mode the promotion. <span class="doxyComputerOutput">PromotedOperand</span> is the value that has been promoted.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>True if the promotion is profitable, false otherwise.</p></dd>
</dl>


<p>Definition at line 3839 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

### matchAddr() {#a26bb3cdbd5f3ac36e41f1098e7023efc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AddressingModeMatcher::matchAddr (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Addr, unsigned Depth)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If we can, try to add the value of 'Addr' into the current addressing mode.</p>


<p>If Addr can't be added to <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/msp430/lib/target/msp430/disassembler/msp430disassembler-cpp/#abf132b4ad93f3557cd3956577592ba68">AddrMode</a> this returns false and leaves <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/msp430/lib/target/msp430/disassembler/msp430disassembler-cpp/#abf132b4ad93f3557cd3956577592ba68">AddrMode</a> unmodified. This assumes that Addr is either a pointer type or intptr_t for the target.</p>


<p>Definition at line 3832 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

### matchOperationAddr() {#a0b83aeacaba3be9b9b9d30384f0022fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AddressingModeMatcher::matchOperationAddr (<a href="/web-llvm/docs/api/classes/llvm/user">User</a> * AddrInst, unsigned Opcode, unsigned Depth, bool * MovedAway=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Given an instruction or constant expr, see if we can fold the operation into the addressing mode.</p>


<p>If so, update the addressing mode and return true, otherwise return false without modifying <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/msp430/lib/target/msp430/disassembler/msp430disassembler-cpp/#abf132b4ad93f3557cd3956577592ba68">AddrMode</a>. If <span class="doxyComputerOutput">MovedAway</span> is not NULL, it contains the information of whether or not AddrInst has to be folded into the addressing mode on success. If <span class="doxyComputerOutput">MovedAway</span> == true, <span class="doxyComputerOutput">AddrInst</span> will not be part of the addressing because it has been moved away. Thus AddrInst must not be added in the matched instructions. This state can happen when AddrInst is a sext, since it may be moved away. Therefore, AddrInst may not be valid when MovedAway is true and it must not be referenced anymore.</p>


<p>Definition at line 3833 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

### matchScaledValue() {#abd48db079eae8e49332408a9cbe745cf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AddressingModeMatcher::matchScaledValue (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * ScaleReg, int64_t Scale, unsigned Depth)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Try adding ScaleReg*Scale to the current addressing mode.</p>


<p>Return true and update <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/msp430/lib/target/msp430/disassembler/msp430disassembler-cpp/#abf132b4ad93f3557cd3956577592ba68">AddrMode</a> if this addr mode is legal for the target, false if not.</p>


<p>Definition at line 3831 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

### valueAlreadyLiveAtInst() {#a750ec615cdb16dc4c622d5a91b74f291}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AddressingModeMatcher::valueAlreadyLiveAtInst (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Val, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * KnownLive1, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * KnownLive2)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if Val is already known to be live at the use site that we're folding it into.</p>


<p>If so, there is no cost to include it in the addressing mode. KnownLive1 and KnownLive2 are two values that we know are live at the instruction already.</p>


<p>Definition at line 3838 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### AccessTy {#ac64c806ec47f162ed49a833a2f59ddd7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type* anonymous{CodeGenPrepare.cpp}::AddressingModeMatcher::AccessTy</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>AccessTy/MemoryInst - This is the type for the access (e.g.</p>


<p>double) and the memory instruction that we're computing this address for.</p>


<p>Definition at line 3754 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

### AddrMode {#a7c8725fc519e8d9da6546f35dd03cec5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ExtAddrMode&amp; anonymous{CodeGenPrepare.cpp}::AddressingModeMatcher::AddrMode</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This is the addressing mode that we're building up.</p>


<p>This is part of the return value of this addressing mode matching stuff.</p>


<p>Definition at line 3760 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

### AddrModeInsts {#a1316b26e7b91042c63155f52cc13ea4b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVectorImpl&lt;Instruction *&gt;&amp; anonymous{CodeGenPrepare.cpp}::AddressingModeMatcher::AddrModeInsts</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 3745 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

### AddrSpace {#afb9379ea4388700f1f7f54f6b974230e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{CodeGenPrepare.cpp}::AddressingModeMatcher::AddrSpace</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 3755 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

### BFI {#ab0b6a5592665b1ed7b3fd580847d1f19}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BlockFrequencyInfo* anonymous{CodeGenPrepare.cpp}::AddressingModeMatcher::BFI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 3782 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

### DL {#adecb7387883d586236f1cc72f7b7d634}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DataLayout&amp; anonymous{CodeGenPrepare.cpp}::AddressingModeMatcher::DL</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 3748 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

### getDTFn {#a7f18b3885cfc3b708ef5436eeda9e3b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const std::function&lt;const DominatorTree &amp;()&gt; anonymous{CodeGenPrepare.cpp}::AddressingModeMatcher::getDTFn</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 3750 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

### IgnoreProfitability {#a971a22087bde2040323e2c797281f4a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{CodeGenPrepare.cpp}::AddressingModeMatcher::IgnoreProfitability</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This is set to true when we should not do profitability checks.</p>


<p>When true, IsProfitableToFoldIntoAddressingMode always returns true.</p>


<p>Definition at line 3776 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

### InsertedInsts {#ae5fd735ede73bfb7b96c291d0ace0e3e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SetOfInstrs&amp; anonymous{CodeGenPrepare.cpp}::AddressingModeMatcher::InsertedInsts</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The instructions inserted by other <a href="/web-llvm/docs/api/classes/anonymous-codegenprepare-cpp-/codegenprepare">CodeGenPrepare</a> optimizations.</p>

<p>Definition at line 3763 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

### LargeOffsetGEP {#a8d52b1f082e79be0b2d338026efeb3ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt;AssertingVH&lt;GetElementPtrInst&gt;, int64_t&gt;&amp; anonymous{CodeGenPrepare.cpp}::AddressingModeMatcher::LargeOffsetGEP</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 3772 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

### LI {#a50de527a586a5fd5ebdc302f299c7e6a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const LoopInfo&amp; anonymous{CodeGenPrepare.cpp}::AddressingModeMatcher::LI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 3749 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

### MemoryInst {#a72fdc4d1b4e2760147df46e9f655bf5c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Instruction* anonymous{CodeGenPrepare.cpp}::AddressingModeMatcher::MemoryInst</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 3756 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

### OptSize {#a1f948ff6ae7b2419806cba6406fe0855}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{CodeGenPrepare.cpp}::AddressingModeMatcher::OptSize = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>True if we are optimizing for size.</p>

<p>Definition at line 3779 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

### PromotedInsts {#a299f8eee052c8185969fc01dcc9c9fa4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstrToOrigTy&amp; anonymous{CodeGenPrepare.cpp}::AddressingModeMatcher::PromotedInsts</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A map from the instructions to their type before promotion.</p>

<p>Definition at line 3766 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

### PSI {#a17b1873dd1a9be616e12a01e4263cba3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ProfileSummaryInfo* anonymous{CodeGenPrepare.cpp}::AddressingModeMatcher::PSI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 3781 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

### TLI {#a06ef2b5c917c90c930e6fc24cfd9a52d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetLowering&amp; anonymous{CodeGenPrepare.cpp}::AddressingModeMatcher::TLI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 3746 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

### TPT {#abf6bb746ce0f3c0d4cfe7f07400cb4cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TypePromotionTransaction&amp; anonymous{CodeGenPrepare.cpp}::AddressingModeMatcher::TPT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The ongoing transaction where every action should be registered.</p>

<p>Definition at line 3769 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

### TRI {#a48027822a550886fe2c99da543b18bc0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetRegisterInfo&amp; anonymous{CodeGenPrepare.cpp}::AddressingModeMatcher::TRI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 3747 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### Match() {#a592ce6f54154b0ca1d672869951cad6b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ExtAddrMode anonymous{CodeGenPrepare.cpp}::AddressingModeMatcher::Match (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * AccessTy, unsigned AS, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * MemoryInst, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * &gt; &amp; AddrModeInsts, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlowering">TargetLowering</a> &amp; TLI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a> &amp; LI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::function&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> &amp;()&gt; getDTFn, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> &amp; TRI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/anonymous-codegenprepare-cpp-/#af2dad33e47a12a0b01b11d97d390f7ee">SetOfInstrs</a> &amp; InsertedInsts, <a href="/web-llvm/docs/api/namespaces/anonymous-codegenprepare-cpp-/#a71622f7f81af67784beaf8b1420aa76d">InstrToOrigTy</a> &amp; PromotedInsts, <a href="/web-llvm/docs/api/classes/anonymous-codegenprepare-cpp-/typepromotiontransaction">TypePromotionTransaction</a> &amp; TPT, std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/assertingvh">AssertingVH</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/getelementptrinst">GetElementPtrInst</a> &gt;, int64_t &gt; &amp; LargeOffsetGEP, bool OptSize, <a href="/web-llvm/docs/api/classes/llvm/profilesummaryinfo">ProfileSummaryInfo</a> * PSI, <a href="/web-llvm/docs/api/classes/llvm/blockfrequencyinfo">BlockFrequencyInfo</a> * BFI)</td>
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

<p>Find the maximal addressing mode that a load/store of V can fold, give an access type of AccessTy.</p>


<p>This returns a list of involved instructions in AddrModeInsts. <span class="doxyComputerOutput">InsertedInsts</span> The instructions inserted by other <a href="/web-llvm/docs/api/classes/anonymous-codegenprepare-cpp-/codegenprepare">CodeGenPrepare</a> optimizations. <span class="doxyComputerOutput">PromotedInsts</span> maps the instructions to their type before promotion. <span class="doxyComputerOutput">The</span> ongoing transaction where every action should be registered.</p>


<p>Definition at line 3810 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/disassembler/aarch64disassembler-cpp/#abdb086b34295fb7aa09493c62d798465">Success</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>

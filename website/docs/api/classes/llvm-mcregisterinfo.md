---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/mcregisterinfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `MCRegisterInfo` Class Reference

<p><a href="/web-llvm/docs/api/classes/llvm/mcregisterinfo">MCRegisterInfo</a> base class - We assume that the target defines a static array of <a href="/web-llvm/docs/api/structs/llvm/mcregisterdesc">MCRegisterDesc</a> objects that represent all of the machine registers that the target has. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::MCRegisterInfo { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcregisterinfo-h">llvm/MC/MCRegisterInfo.h</a>"
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> base class - We assume that the target defines a static array of TargetRegisterDesc objects that represent all of the machine registers that the target has. <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e6b96b6675dc76cace9e66fe7a5d829">regclass_iterator</a> = <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcregisterclass">MCRegisterClass</a> *</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7aba84294411bec516c4f99c2743d8aa">MCSubRegIterator</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa6c2775d1a263919820806bca50c085">MCSubRegIndexIterator</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a98195db99f78cd46313e0de07882b7bb">MCSuperRegIterator</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acdaa5f1dcfe0ac250e2c0f285517494f">MCRegUnitIterator</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aafe231cee5e487fcce3d3735523e0069">MCRegUnitMaskIterator</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a871e5c4479bde111063c92656dadf3cb">MCRegUnitRootIterator</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1d2202a12c9aa0fac1c35b7126eef4a8">MCRegAliasIterator</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a63131f0bdf2182875448ed3627bcc0c9">~MCRegisterInfo</a> ()</td>
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

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/mcregisterdesc">MCRegisterDesc</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0d669c2aaacea16545cd82b179b8d848">operator[]</a> (MCRegister Reg) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/mcsubregiterator">MCSubRegIterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9ded59d8266ccd2647bfd81722046beb">subregs</a> (MCRegister Reg) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return an iterator range over all sub-registers of <span class="doxyComputerOutput">Reg</span>, excluding <span class="doxyComputerOutput">Reg</span>. <a href="#a9ded59d8266ccd2647bfd81722046beb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/mcsubregiterator">MCSubRegIterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a95656353b813a1dd7ddfa7d8445633a8">subregs_inclusive</a> (MCRegister Reg) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return an iterator range over all sub-registers of <span class="doxyComputerOutput">Reg</span>, including <span class="doxyComputerOutput">Reg</span>. <a href="#a95656353b813a1dd7ddfa7d8445633a8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/mcsuperregiterator">MCSuperRegIterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5e72490b2e8a4c4f70e0aab62f0ea176">superregs</a> (MCRegister Reg) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return an iterator range over all super-registers of <span class="doxyComputerOutput">Reg</span>, excluding <span class="doxyComputerOutput">Reg</span>. <a href="#a5e72490b2e8a4c4f70e0aab62f0ea176">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/mcsuperregiterator">MCSuperRegIterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad1f2700e4a533bcbd9d3c4e156a14d67">superregs_inclusive</a> (MCRegister Reg) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return an iterator range over all super-registers of <span class="doxyComputerOutput">Reg</span>, including <span class="doxyComputerOutput">Reg</span>. <a href="#ad1f2700e4a533bcbd9d3c4e156a14d67">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/detail/concat-range">detail::concat_range</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#aad72cfbb210808985a9dc19f4e5d8542">MCPhysReg</a>, <a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/mcsubregiterator">MCSubRegIterator</a> &gt;, <a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/mcsuperregiterator">MCSuperRegIterator</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad85f1120e6b067734e6a186f29da3c73">sub_and_superregs_inclusive</a> (MCRegister Reg) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return an iterator range over all sub- and super-registers of <span class="doxyComputerOutput">Reg</span>, including <span class="doxyComputerOutput">Reg</span>. <a href="#ad85f1120e6b067734e6a186f29da3c73">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/mcregunititerator">MCRegUnitIterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf9973b1c9926f0903d0c6bddfc93118">regunits</a> (MCRegister Reg) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns an iterator range over all regunits for <span class="doxyComputerOutput">Reg</span>. <a href="#abf9973b1c9926f0903d0c6bddfc93118">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a773b83ede7cbfdce567311d244b956a4">InitMCRegisterInfo</a> (const MCRegisterDesc *D, unsigned NR, unsigned RA, unsigned PC, const MCRegisterClass *C, unsigned NC, const MCPhysReg(*RURoots)[2], unsigned NRU, const int16_t *DL, const LaneBitmask *RUMS, const char *Strings, const char *ClassStrings, const uint16_t *SubIndices, unsigned NumIndices, const uint16_t *RET)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Initialize <a href="/web-llvm/docs/api/classes/llvm/mcregisterinfo">MCRegisterInfo</a>, called by <a href="/web-llvm/docs/api/namespaces/llvm/tablegen">TableGen</a> auto-generated routines. <a href="#a773b83ede7cbfdce567311d244b956a4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab7c254cf3539a51c7d3170e13e84e471">mapLLVMRegsToDwarfRegs</a> (const DwarfLLVMRegPair *Map, unsigned Size, bool isEH)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Used to initialize LLVM register to Dwarf register number mapping. <a href="#ab7c254cf3539a51c7d3170e13e84e471">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b44c113e5e36696965e0a8e237d8644">mapDwarfRegsToLLVMRegs</a> (const DwarfLLVMRegPair *Map, unsigned Size, bool isEH)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Used to initialize Dwarf register to LLVM register number mapping. <a href="#a1b44c113e5e36696965e0a8e237d8644">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad08a70c5c39a83a86528e4cd6ef66a16">mapLLVMRegToSEHReg</a> (MCRegister LLVMReg, int SEHReg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>mapLLVMRegToSEHReg - Used to initialize LLVM register to SEH register number mapping. <a href="#ad08a70c5c39a83a86528e4cd6ef66a16">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b3e8d277800ba2430072436f053ab3d">mapLLVMRegToCVReg</a> (MCRegister LLVMReg, int CVReg)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a154e99ffe7d9b27b2eafc9901779d05e">getRARegister</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method should return the register where the return address can be found. <a href="#a154e99ffe7d9b27b2eafc9901779d05e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ab4a7380910579b6946391cc8a7f77f">getProgramCounter</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the register which is the program counter. <a href="#a1ab4a7380910579b6946391cc8a7f77f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/mcregisterdesc">MCRegisterDesc</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a20afbbc02b58a57256a9ac9736d08838">get</a> (MCRegister Reg) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Provide a get method, equivalent to [], but more useful with a pointer to this object. <a href="#a20afbbc02b58a57256a9ac9736d08838">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae3ba9f77f723402ff1e1f6d8ac0e3b36">getSubReg</a> (MCRegister Reg, unsigned Idx) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the physical register number of sub-register "Index" for physical register RegNo. <a href="#ae3ba9f77f723402ff1e1f6d8ac0e3b36">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2168c5f22e98b5c471060a3dfc1ec0db">getMatchingSuperReg</a> (MCRegister Reg, unsigned SubIdx, const MCRegisterClass *RC) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a super-register of the specified register Reg so its sub-register of index SubIdx is Reg. <a href="#a2168c5f22e98b5c471060a3dfc1ec0db">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab2c943894d8d91dead449b33a77981c5">getSubRegIndex</a> (MCRegister RegNo, MCRegister SubRegNo) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>For a given register pair, return the sub-register index if the second register is a sub-register of the first. <a href="#ab2c943894d8d91dead449b33a77981c5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a72c68e39a0c971dae8d761c7aabfdf35">getName</a> (MCRegister RegNo) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the human-readable symbolic target-specific name for the specified physical register. <a href="#a72c68e39a0c971dae8d761c7aabfdf35">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaf1506fdb514093df726e00b8f665ebf">isConstant</a> (MCRegister RegNo) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the given register is constant. <a href="#aaf1506fdb514093df726e00b8f665ebf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac075ed8f381fe6f102ac864a339124a6">isArtificial</a> (MCRegister RegNo) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the given register is artificial, which means it represents a regunit that is not separately addressable but still needs to be modelled, such as the top 16-bits of a 32-bit GPR. <a href="#ac075ed8f381fe6f102ac864a339124a6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9073d0a5218514fa4deb7ef2aa831492">isArtificialRegUnit</a> (MCRegUnit Unit) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true when the given register unit is considered artificial. <a href="#a9073d0a5218514fa4deb7ef2aa831492">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af946f316ed42f8b5eb99735a3b587ab5">getNumRegs</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the number of registers this target has (useful for sizing arrays holding per register information) <a href="#af946f316ed42f8b5eb99735a3b587ab5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a04922e6bf2f754ccfad845d7a0ec00a0">getNumSubRegIndices</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the number of sub-register indices understood by the target. <a href="#a04922e6bf2f754ccfad845d7a0ec00a0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1c0e50e50918b2c91b99e1188d41c901">getNumRegUnits</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the number of (native) register units in the target. <a href="#a1c0e50e50918b2c91b99e1188d41c901">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7be5983b88f5da173b31deaa93c2a8c2">getDwarfRegNum</a> (MCRegister RegNum, bool isEH) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Map a target register to an equivalent dwarf register number. <a href="#a7be5983b88f5da173b31deaa93c2a8c2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad8bd0d8807995fe448c671a5011734ff">getLLVMRegNum</a> (uint64_t RegNum, bool isEH) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Map a dwarf register back to a target register. <a href="#ad8bd0d8807995fe448c671a5011734ff">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a403ac8e5404443f85a39fd7f6cc97574">getDwarfRegNumFromDwarfEHRegNum</a> (uint64_t RegNum) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Map a target EH register number to an equivalent DWARF register number. <a href="#a403ac8e5404443f85a39fd7f6cc97574">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a4f0d89d23611afff28a9b3a347cbfa">getSEHRegNum</a> (MCRegister RegNum) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Map a target register to an equivalent SEH register number. <a href="#a5a4f0d89d23611afff28a9b3a347cbfa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a31c99afffac12a059636852d1d05f8e8">getCodeViewRegNum</a> (MCRegister RegNum) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Map a target register to an equivalent CodeView register number. <a href="#a31c99afffac12a059636852d1d05f8e8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a2e6b96b6675dc76cace9e66fe7a5d829">regclass_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a412da2ed683a7a3f9e888178753ee200">regclass_begin</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a2e6b96b6675dc76cace9e66fe7a5d829">regclass_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1adcc58c9411eebe3577d71087f9efc3">regclass_end</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="#a2e6b96b6675dc76cace9e66fe7a5d829">regclass_iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3cec2db86fe526dfbe229a598ea82e1b">regclasses</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a11124059eb4728d5aa71cbff07e9f178">getNumRegClasses</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcregisterclass">MCRegisterClass</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae179799df1c5f01dc1c55e7ff4868743">getRegClass</a> (unsigned i) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the register class associated with the enumeration value. <a href="#ae179799df1c5f01dc1c55e7ff4868743">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a79e43db4fcb1d498e1b95b7b8210ebc7">getRegClassName</a> (const MCRegisterClass *Class) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint16_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a88977138a65e44f5f302342e4a00b501">getEncodingValue</a> (MCRegister Reg) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the encoding for Reg. <a href="#a88977138a65e44f5f302342e4a00b501">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a97b138b96791a09a0d9b9c77f0fb6e85">isSubRegister</a> (MCRegister RegA, MCRegister RegB) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if RegB is a sub-register of RegA. <a href="#a97b138b96791a09a0d9b9c77f0fb6e85">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab8e1321ecb267615f4f4be14b92cf03a">isSuperRegister</a> (MCRegister RegA, MCRegister RegB) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if RegB is a super-register of RegA. <a href="#ab8e1321ecb267615f4f4be14b92cf03a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac5ea214c523615af8b7c8c6547ef59de">isSubRegisterEq</a> (MCRegister RegA, MCRegister RegB) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if RegB is a sub-register of RegA or if RegB == RegA. <a href="#ac5ea214c523615af8b7c8c6547ef59de">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a10add2603cf9d4706e64a3605783b764">isSuperRegisterEq</a> (MCRegister RegA, MCRegister RegB) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if RegB is a super-register of RegA or if RegB == RegA. <a href="#a10add2603cf9d4706e64a3605783b764">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a973016c591557c107018a0e6478b30a9">isSuperOrSubRegisterEq</a> (MCRegister RegA, MCRegister RegB) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if RegB is a super-register or sub-register of RegA or if RegB == RegA. <a href="#a973016c591557c107018a0e6478b30a9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0bd1b194b601377bdb0f3a4a6e1f7e0d">regsOverlap</a> (MCRegister RegA, MCRegister RegB) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the two registers are equal or alias each other. <a href="#a0bd1b194b601377bdb0f3a4a6e1f7e0d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#aad72cfbb210808985a9dc19f4e5d8542">MCPhysReg</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af7f9f1c04c21fa0720da554972630115">getCachedAliasesOf</a> (MCRegister R) const</td>
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

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/mcregisterdesc">MCRegisterDesc</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54c02aa4e6491600a7ec4d7372fa18b2">Desc</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa620991b540ef6cc9a8e419d8b9c6521">NumRegs</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab2e8be1ad6b0e39a8a4cd2a95e285c26">RAReg</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4ac8cead3897251897eb93e4221682c6">PCReg</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcregisterclass">MCRegisterClass</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae424236d74a204c21f85d27410b8bf42">Classes</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b79c907cd11441d53fafe21c060bbc8">NumClasses</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a66b72219bd2264eccdbdc307254d2cc4">NumRegUnits</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#aad72cfbb210808985a9dc19f4e5d8542">MCPhysReg</a>(*</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af739cac0b1e828ec0380bfb96bbab0b9">RegUnitRoots</a>)[2]</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> int16_t *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ad217e3cbcafcc2464774a260fe3028">DiffLists</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/lanebitmask">LaneBitmask</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2dcdd494ab84ec17619f9ad6d8e0be8e">RegUnitMaskSequences</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1189f9310d3fbb014c068c6b37a64a61">RegStrings</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e2f5fe05c011bb3c9e603f671dfe9d7">RegClassStrings</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint16_t *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a09405597445301177b8d5b6d683f563e">SubRegIndices</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a677bdf16f121f92ac6adcc5cfef66c38">NumSubRegIndices</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint16_t *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa4e7bd7bd37f516924081c0e8ca5454c">RegEncodingTable</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a18c628855599c97c683fb8cb3925635f">L2DwarfRegsSize</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa88e55f6b75b6c3460e0e992c4698ac4">EHL2DwarfRegsSize</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a98c90079c6bbf40879ec419c04ad4739">Dwarf2LRegsSize</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a74a71dd60aaa8151556962f3655ae492">EHDwarf2LRegsSize</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/mcregisterinfo/dwarfllvmregpair">DwarfLLVMRegPair</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a17f9328b381b7a96f82f5279536ef493">L2DwarfRegs</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/mcregisterinfo/dwarfllvmregpair">DwarfLLVMRegPair</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1446417a6f0dfadf5a9eb5b2a182e059">EHL2DwarfRegs</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/mcregisterinfo/dwarfllvmregpair">DwarfLLVMRegPair</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af1c131d49c4d0f672c2132085f7e6176">Dwarf2LRegs</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/mcregisterinfo/dwarfllvmregpair">DwarfLLVMRegPair</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a21a01aa3ef51e6e201157cce5d8f8526">EHDwarf2LRegs</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a>, int &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8fe7e1d016aa5e245c9e35471c7c28a6">L2SEHRegs</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a>, int &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e655117db4c67a3f83f4180b1b99323">L2CVRegs</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; std::vector&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#aad72cfbb210808985a9dc19f4e5d8542">MCPhysReg</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac01a6585a0164f34efd67646a0aae2dc">RegAliasesCache</a></td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/mcregisterinfo">MCRegisterInfo</a> base class - We assume that the target defines a static array of <a href="/web-llvm/docs/api/structs/llvm/mcregisterdesc">MCRegisterDesc</a> objects that represent all of the machine registers that the target has.</p>


<p>As such, we simply have to track a pointer to this array so that we can turn register number into a register descriptor.</p>


<p>Note this class is designed to be a base class of <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a>, which is the interface used by codegen. However, specific targets <em>should never</em> specialize this class. <a href="/web-llvm/docs/api/classes/llvm/mcregisterinfo">MCRegisterInfo</a> should only contain getters to access <a href="/web-llvm/docs/api/namespaces/llvm/tablegen">TableGen</a> generated physical register data. It must not be extended with virtual methods.</p>


<p>Definition at line 149 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcregisterinfo-h">MCRegisterInfo.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### regclass\_iterator {#a2e6b96b6675dc76cace9e66fe7a5d829}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::MCRegisterInfo::regclass_iterator =  const MCRegisterClass *</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 151 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcregisterinfo-h">MCRegisterInfo.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Friends

### MCRegAliasIterator {#a1d2202a12c9aa0fac1c35b7126eef4a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/mcregaliasiterator">MCRegAliasIterator</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 272 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcregisterinfo-h">MCRegisterInfo.h</a>.</p>


<p>Reference <a href="#a1d2202a12c9aa0fac1c35b7126eef4a8">MCRegAliasIterator</a>.</p>


<p>Referenced by <a href="#a1d2202a12c9aa0fac1c35b7126eef4a8">MCRegAliasIterator</a>.</p>

</div>
</div>

### MCRegUnitIterator {#acdaa5f1dcfe0ac250e2c0f285517494f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/mcregunititerator">MCRegUnitIterator</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 269 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcregisterinfo-h">MCRegisterInfo.h</a>.</p>


<p>Reference <a href="#acdaa5f1dcfe0ac250e2c0f285517494f">MCRegUnitIterator</a>.</p>


<p>Referenced by <a href="#acdaa5f1dcfe0ac250e2c0f285517494f">MCRegUnitIterator</a>, <a href="#a0bd1b194b601377bdb0f3a4a6e1f7e0d">regsOverlap</a> and <a href="#abf9973b1c9926f0903d0c6bddfc93118">regunits</a>.</p>

</div>
</div>

### MCRegUnitMaskIterator {#aafe231cee5e487fcce3d3735523e0069}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/mcregunitmaskiterator">MCRegUnitMaskIterator</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 270 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcregisterinfo-h">MCRegisterInfo.h</a>.</p>


<p>Reference <a href="#aafe231cee5e487fcce3d3735523e0069">MCRegUnitMaskIterator</a>.</p>


<p>Referenced by <a href="#aafe231cee5e487fcce3d3735523e0069">MCRegUnitMaskIterator</a>.</p>

</div>
</div>

### MCRegUnitRootIterator {#a871e5c4479bde111063c92656dadf3cb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/mcregunitrootiterator">MCRegUnitRootIterator</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 271 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcregisterinfo-h">MCRegisterInfo.h</a>.</p>


<p>Reference <a href="#a871e5c4479bde111063c92656dadf3cb">MCRegUnitRootIterator</a>.</p>


<p>Referenced by <a href="#a9073d0a5218514fa4deb7ef2aa831492">isArtificialRegUnit</a> and <a href="#a871e5c4479bde111063c92656dadf3cb">MCRegUnitRootIterator</a>.</p>

</div>
</div>

### MCSubRegIndexIterator {#afa6c2775d1a263919820806bca50c085}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/mcsubregindexiterator">MCSubRegIndexIterator</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 267 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcregisterinfo-h">MCRegisterInfo.h</a>.</p>


<p>Reference <a href="#afa6c2775d1a263919820806bca50c085">MCSubRegIndexIterator</a>.</p>


<p>Referenced by <a href="#afa6c2775d1a263919820806bca50c085">MCSubRegIndexIterator</a>.</p>

</div>
</div>

### MCSubRegIterator {#a7aba84294411bec516c4f99c2743d8aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/mcsubregiterator">MCSubRegIterator</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 266 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcregisterinfo-h">MCRegisterInfo.h</a>.</p>


<p>Reference <a href="#a7aba84294411bec516c4f99c2743d8aa">MCSubRegIterator</a>.</p>


<p>Referenced by <a href="#a7aba84294411bec516c4f99c2743d8aa">MCSubRegIterator</a>, <a href="#a9ded59d8266ccd2647bfd81722046beb">subregs</a> and <a href="#a95656353b813a1dd7ddfa7d8445633a8">subregs_inclusive</a>.</p>

</div>
</div>

### MCSuperRegIterator {#a98195db99f78cd46313e0de07882b7bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/mcsuperregiterator">MCSuperRegIterator</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 268 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcregisterinfo-h">MCRegisterInfo.h</a>.</p>


<p>Reference <a href="#a98195db99f78cd46313e0de07882b7bb">MCSuperRegIterator</a>.</p>


<p>Referenced by <a href="#a98195db99f78cd46313e0de07882b7bb">MCSuperRegIterator</a>, <a href="#a5e72490b2e8a4c4f70e0aab62f0ea176">superregs</a> and <a href="#ad1f2700e4a533bcbd9d3c4e156a14d67">superregs_inclusive</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~MCRegisterInfo() {#a63131f0bdf2182875448ed3627bcc0c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual llvm::MCRegisterInfo::~MCRegisterInfo ()</td>
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



<p>Definition at line 274 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcregisterinfo-h">MCRegisterInfo.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator\[\]() {#a0d669c2aaacea16545cd82b179b8d848}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCRegisterDesc &amp; llvm::MCRegisterInfo::operator[] (<a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> Reg)</td>
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



<p>Definition at line 366 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcregisterinfo-h">MCRegisterInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a>.</p>


<p>Referenced by <a href="#a20afbbc02b58a57256a9ac9736d08838">get</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### get() {#a20afbbc02b58a57256a9ac9736d08838}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCRegisterDesc &amp; llvm::MCRegisterInfo::get (<a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> Reg)</td>
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

<p>Provide a get method, equivalent to [], but more useful with a pointer to this object.</p>

<p>Definition at line 374 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcregisterinfo-h">MCRegisterInfo.h</a>.</p>


<p>References <a href="#a0d669c2aaacea16545cd82b179b8d848">operator[]</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a>.</p>


<p>Referenced by <a href="#a72c68e39a0c971dae8d761c7aabfdf35">getName</a>, <a href="/web-llvm/docs/api/classes/llvm/llvmdisasmcontext/#aa6a4fae6275aca4dfeb6d0e2618482ba">llvm::LLVMDisasmContext::getRegisterInfo</a>, <a href="#ae3ba9f77f723402ff1e1f6d8ac0e3b36">getSubReg</a>, <a href="#ab2c943894d8d91dead449b33a77981c5">getSubRegIndex</a>, <a href="#ac075ed8f381fe6f102ac864a339124a6">isArtificial</a>, <a href="#aaf1506fdb514093df726e00b8f665ebf">isConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/mcregunititerator/#ad3b4547b7252d2399f4c9ff6729f02ce">llvm::MCRegUnitIterator::MCRegUnitIterator</a>, <a href="/web-llvm/docs/api/classes/llvm/mcregunitmaskiterator/#a354da5c3004b55b6143efd8272e6ab86">llvm::MCRegUnitMaskIterator::MCRegUnitMaskIterator</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsubregindexiterator/#a067b3c3d9f297a5f7f7da3277bc38f8a">llvm::MCSubRegIndexIterator::MCSubRegIndexIterator</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsubregiterator/#af085591de2aed7f37f36dc4f9ec7049d">llvm::MCSubRegIterator::MCSubRegIterator</a> and <a href="/web-llvm/docs/api/classes/llvm/mcsuperregiterator/#a078d1ea992de6b0fcae912cdd33af95d">llvm::MCSuperRegIterator::MCSuperRegIterator</a>.</p>

</div>
</div>

### getCodeViewRegNum() {#a31c99afffac12a059636852d1d05f8e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int MCRegisterInfo::getCodeViewRegNum (<a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> RegNum)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Map a target register to an equivalent CodeView register number.</p>

<p>Declaration at line 452 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcregisterinfo-h">MCRegisterInfo.h</a>, definition at line 200 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcregisterinfo-cpp">MCRegisterInfo.cpp</a>.</p>


<p>References <a href="#a72c68e39a0c971dae8d761c7aabfdf35">getName</a>, <a href="#af946f316ed42f8b5eb99735a3b587ab5">getNumRegs</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>.</p>

</div>
</div>

### getDwarfRegNum() {#a7be5983b88f5da173b31deaa93c2a8c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t MCRegisterInfo::getDwarfRegNum (<a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> RegNum, bool isEH)</td>
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

<p>Map a target register to an equivalent dwarf register number.</p>


<p>Returns -1 if there is no equivalent value. The second parameter allows targets to use different numberings for EH info and debugging info.</p>


<p>Declaration at line 436 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcregisterinfo-h">MCRegisterInfo.h</a>, definition at line 144 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcregisterinfo-cpp">MCRegisterInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a98c6256d0644613c6b5b3e2ef06ef5ce">llvm::InnerAnalysisManagerProxy&lt; AnalysisManagerT, IRUnitT, ExtraArgTs... &gt;::Key</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>


<p>Referenced by <a href="#a403ac8e5404443f85a39fd7f6cc97574">getDwarfRegNumFromDwarfEHRegNum</a>.</p>

</div>
</div>

### getDwarfRegNumFromDwarfEHRegNum() {#a403ac8e5404443f85a39fd7f6cc97574}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t MCRegisterInfo::getDwarfRegNumFromDwarfEHRegNum (uint64_t RegNum)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Map a target EH register number to an equivalent DWARF register number.</p>

<p>Declaration at line 444 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcregisterinfo-h">MCRegisterInfo.h</a>, definition at line 175 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcregisterinfo-cpp">MCRegisterInfo.cpp</a>.</p>


<p>References <a href="#a7be5983b88f5da173b31deaa93c2a8c2">getDwarfRegNum</a> and <a href="#ad8bd0d8807995fe448c671a5011734ff">getLLVMRegNum</a>.</p>

</div>
</div>

### getEncodingValue() {#a88977138a65e44f5f302342e4a00b501}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint16_t llvm::MCRegisterInfo::getEncodingValue (<a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> Reg)</td>
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

<p>Returns the encoding for Reg.</p>

<p>Definition at line 476 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcregisterinfo-h">MCRegisterInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#ac4f56500894c6c3ca92c54b569cc42a7">anonymous{AArch64AsmParser.cpp}::AArch64Operand::addGPR32as64Operands</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#ac45d96b1d1611280239c5f5ec90e1d22">anonymous{AArch64AsmParser.cpp}::AArch64Operand::addGPR64as32Operands</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#a536cdad3a9f844e78b6003550707b214">anonymous{AArch64AsmParser.cpp}::AArch64Operand::addSyspXzrPairOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonasmprinter/#aee072cd97eb6d078d122611833049aa6">llvm::HexagonAsmPrinter::HexagonProcessInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsreginforecord/#a08ccbcf5688d00eb218e2dac89eedcb1">llvm::MipsRegInfoRecord::SetPhysRegUsed</a> and <a href="/web-llvm/docs/api/classes/llvm/aarch64externalsymbolizer/#aadc518cf2b179163c8eca58f17e333b2">llvm::AArch64ExternalSymbolizer::tryAddingSymbolicOperand</a>.</p>

</div>
</div>

### getLLVMRegNum() {#ad8bd0d8807995fe448c671a5011734ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; MCRegister &gt; MCRegisterInfo::getLLVMRegNum (uint64_t RegNum, bool isEH)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Map a dwarf register back to a target register.</p>


<p>Returns std::nullopt if there is no mapping.</p>


<p>Declaration at line 440 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcregisterinfo-h">MCRegisterInfo.h</a>, definition at line 161 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcregisterinfo-cpp">MCRegisterInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcregister/#a822cab8661beb03276b0566d33e41592">llvm::MCRegister::from</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a98c6256d0644613c6b5b3e2ef06ef5ce">llvm::InnerAnalysisManagerProxy&lt; AnalysisManagerT, IRUnitT, ExtraArgTs... &gt;::Key</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>


<p>Referenced by <a href="#a403ac8e5404443f85a39fd7f6cc97574">getDwarfRegNumFromDwarfEHRegNum</a>.</p>

</div>
</div>

### getMatchingSuperReg() {#a2168c5f22e98b5c471060a3dfc1ec0db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCRegister MCRegisterInfo::getMatchingSuperReg (<a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> Reg, unsigned SubIdx, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcregisterclass">MCRegisterClass</a> * RC)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return a super-register of the specified register Reg so its sub-register of index SubIdx is Reg.</p>

<p>Declaration at line 385 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcregisterinfo-h">MCRegisterInfo.h</a>, definition at line 108 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcregisterinfo-cpp">MCRegisterInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcregisterclass/#ad183dc79953e350b769b1dcfda4f0f1c">llvm::MCRegisterClass::contains</a>, <a href="#ae3ba9f77f723402ff1e1f6d8ac0e3b36">getSubReg</a> and <a href="#a5e72490b2e8a4c4f70e0aab62f0ea176">superregs</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/asmparser/riscvasmparser-cpp/#ae595490c22a7dee4fe405d5c91182591">convertVRToVRMx</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/disassembler/riscvdisassembler-cpp/#a92a882831081786f843c7c6576f3f07c">DecodeGPRPairRegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/disassembler/riscvdisassembler-cpp/#a924863953fe38c5075ca2987a071b0b8">DecodeVRM2RegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/disassembler/riscvdisassembler-cpp/#a88ce4565edd9e27d57d87c13811d631b">DecodeVRM4RegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/disassembler/riscvdisassembler-cpp/#a8523dd0b2a00a817ecb488a195ea33cb">DecodeVRM8RegisterClass</a> and <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo/#aa5aad3f9195b1fd331f449ce9a709da2">llvm::TargetRegisterInfo::getMatchingSuperReg</a>.</p>

</div>
</div>

### getName() {#a72c68e39a0c971dae8d761c7aabfdf35}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * llvm::MCRegisterInfo::getName (<a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> RegNo)</td>
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

<p>Return the human-readable symbolic target-specific name for the specified physical register.</p>

<p>Definition at line 395 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcregisterinfo-h">MCRegisterInfo.h</a>.</p>


<p>References <a href="#a20afbbc02b58a57256a9ac9736d08838">get</a> and <a href="/web-llvm/docs/api/structs/llvm/mcregisterdesc/#a8ddd79e928fa782c64a2f78c9497559e">llvm::MCRegisterDesc::Name</a>.</p>


<p>Referenced by <a href="#a31c99afffac12a059636852d1d05f8e8">getCodeViewRegNum</a> and <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo/#ad4f8f1aca0bb01f65be1d7dee43f7f83">llvm::TargetRegisterInfo::getRegAsmName</a>.</p>

</div>
</div>

### getNumRegClasses() {#a11124059eb4728d5aa71cbff07e9f178}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MCRegisterInfo::getNumRegClasses ()</td>
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



<p>Definition at line 460 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcregisterinfo-h">MCRegisterInfo.h</a>.</p>


<p>References <a href="#a412da2ed683a7a3f9e888178753ee200">regclass_begin</a> and <a href="#a1adcc58c9411eebe3577d71087f9efc3">regclass_end</a>.</p>


<p>Referenced by <a href="#ae179799df1c5f01dc1c55e7ff4868743">getRegClass</a>.</p>

</div>
</div>

### getNumRegs() {#af946f316ed42f8b5eb99735a3b587ab5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MCRegisterInfo::getNumRegs ()</td>
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

<p>Return the number of registers this target has (useful for sizing arrays holding per register information)</p>

<p>Definition at line 414 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcregisterinfo-h">MCRegisterInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a6cba8c24b1495a6caff37e5e6df77aa2">llvm::MachineFunction::allocateRegMask</a>, <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo/#a7bd2eaf010a0c53df66932fc514f1cc9">llvm::TargetRegisterInfo::checkAllSuperRegsMarked</a>, <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo/#afa9e8234d75eca83a898e143f4b2502e">llvm::TargetRegisterInfo::getAllocatableSet</a>, <a href="#a31c99afffac12a059636852d1d05f8e8">getCodeViewRegNum</a>, <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo/#ab636ebc3e5dcb3ca34330098ceb39ecd">llvm::TargetRegisterInfo::getNumSupportedRegs</a>, <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo/#a5e98f8929f677c6db51f167ac8955d02">llvm::TargetRegisterInfo::getRegisterCosts</a>, <a href="#ab2c943894d8d91dead449b33a77981c5">getSubRegIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo/#a3e736a38ebafb662ddd8645d83a1d534">llvm::MachineRegisterInfo::MachineRegisterInfo</a> and <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo/#a4d07b23213b2426cc796329c00f8930d">llvm::TargetRegisterInfo::regmaskSubsetEqual</a>.</p>

</div>
</div>

### getNumRegUnits() {#a1c0e50e50918b2c91b99e1188d41c901}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MCRegisterInfo::getNumRegUnits ()</td>
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

<p>Return the number of (native) register units in the target.</p>


<p><a href="/web-llvm/docs/api/classes/llvm/register">Register</a> units are numbered from 0 to <a href="#a1c0e50e50918b2c91b99e1188d41c901">getNumRegUnits()</a> - 1. They can be accessed through <a href="/web-llvm/docs/api/classes/llvm/mcregunititerator">MCRegUnitIterator</a> defined below.</p>


<p>Definition at line 428 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcregisterinfo-h">MCRegisterInfo.h</a>.</p>

</div>
</div>

### getNumSubRegIndices() {#a04922e6bf2f754ccfad845d7a0ec00a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MCRegisterInfo::getNumSubRegIndices ()</td>
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

<p>Return the number of sub-register indices understood by the target.</p>


<p>Index 0 is reserved for the no-op sub-register, while 1 to <a href="#a04922e6bf2f754ccfad845d7a0ec00a0">getNumSubRegIndices()</a> - 1 represent real sub-registers.</p>


<p>Definition at line 421 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcregisterinfo-h">MCRegisterInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo/#a258e3d0e92c1a4d851ef21a368ceb977">llvm::TargetRegisterInfo::getCoveringSubRegIndexes</a>, <a href="#ae3ba9f77f723402ff1e1f6d8ac0e3b36">getSubReg</a>, <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo/#adfca880a2484a3b601ce29c113673709">llvm::TargetRegisterInfo::getSubRegIdxOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo/#a9ca617768555afceede2d3bcaac1bc04">llvm::TargetRegisterInfo::getSubRegIdxSize</a>, <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo/#a7a23b6fb3b79b0c2bf4bf4f0cb042840">llvm::TargetRegisterInfo::getSubRegIndexLaneMask</a> and <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo/#a51854af704b2998ccd0a81911968792e">llvm::TargetRegisterInfo::getSubRegIndexName</a>.</p>

</div>
</div>

### getProgramCounter() {#a1ab4a7380910579b6946391cc8a7f77f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCRegister llvm::MCRegisterInfo::getProgramCounter ()</td>
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

<p>Return the register which is the program counter.</p>

<p>Definition at line 362 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcregisterinfo-h">MCRegisterInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcinstranalysis/#aafca081ce7f45907550a9313a27dc90a">llvm::MCInstrAnalysis::mayAffectControlFlow</a> and <a href="/web-llvm/docs/api/classes/llvm/mcinstrdesc/#a561df24be97e83b9ce73d964fd33b88d">llvm::MCInstrDesc::mayAffectControlFlow</a>.</p>

</div>
</div>

### getRARegister() {#a154e99ffe7d9b27b2eafc9901779d05e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCRegister llvm::MCRegisterInfo::getRARegister ()</td>
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

<p>This method should return the register where the return address can be found.</p>

<p>Definition at line 357 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcregisterinfo-h">MCRegisterInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mipsasmprinter/#aa1274f5cd1bfb8feb3849ba078a3eb83">llvm::MipsAsmPrinter::emitFrameDirective</a>.</p>

</div>
</div>

### getRegClass() {#ae179799df1c5f01dc1c55e7ff4868743}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCRegisterClass &amp; llvm::MCRegisterInfo::getRegClass (unsigned i)</td>
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

<p>Returns the register class associated with the enumeration value.</p>


<p>See class <a href="/web-llvm/docs/api/classes/llvm/mcoperandinfo">MCOperandInfo</a>.</p>


<p>Definition at line 466 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcregisterinfo-h">MCRegisterInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a11124059eb4728d5aa71cbff07e9f178">getNumRegClasses</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#ac4f56500894c6c3ca92c54b569cc42a7">anonymous{AArch64AsmParser.cpp}::AArch64Operand::addGPR32as64Operands</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#ac45d96b1d1611280239c5f5ec90e1d22">anonymous{AArch64AsmParser.cpp}::AArch64Operand::addGPR64as32Operands</a> and <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#a536cdad3a9f844e78b6003550707b214">anonymous{AArch64AsmParser.cpp}::AArch64Operand::addSyspXzrPairOperand</a>.</p>

</div>
</div>

### getRegClassName() {#a79e43db4fcb1d498e1b95b7b8210ebc7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * llvm::MCRegisterInfo::getRegClassName (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcregisterclass">MCRegisterClass</a> * Class)</td>
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



<p>Definition at line 471 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcregisterinfo-h">MCRegisterInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo/#af024492cfad9653e8826fb8e226a4386">llvm::TargetRegisterInfo::getRegClassName</a>.</p>

</div>
</div>

### getSEHRegNum() {#a5a4f0d89d23611afff28a9b3a347cbfa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int MCRegisterInfo::getSEHRegNum (<a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> RegNum)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Map a target register to an equivalent SEH register number.</p>


<p>Returns LLVM register number if there is no equivalent value.</p>


<p>Declaration at line 448 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcregisterinfo-h">MCRegisterInfo.h</a>, definition at line 194 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcregisterinfo-cpp">MCRegisterInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### getSubReg() {#ae3ba9f77f723402ff1e1f6d8ac0e3b36}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCRegister MCRegisterInfo::getSubReg (<a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> Reg, unsigned Idx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the physical register number of sub-register "Index" for physical register RegNo.</p>


<p>Return zero if the sub-register does not exist.</p>


<p>Declaration at line 381 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcregisterinfo-h">MCRegisterInfo.h</a>, definition at line 116 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcregisterinfo-cpp">MCRegisterInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a20afbbc02b58a57256a9ac9736d08838">get</a>, <a href="#a04922e6bf2f754ccfad845d7a0ec00a0">getNumSubRegIndices</a>, <a href="/web-llvm/docs/api/structs/llvm/mcregisterdesc/#ad61c747e243c73c0e6b6a0cfcc4a45ad">llvm::MCRegisterDesc::SubRegIndices</a> and <a href="#a9ded59d8266ccd2647bfd81722046beb">subregs</a>.</p>


<p>Referenced by <a href="#a2168c5f22e98b5c471060a3dfc1ec0db">getMatchingSuperReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseregisterinfo-cpp/#ac2221ad71323cfdfb9d5909e7d1f3775">getPairedGPR</a> and <a href="/web-llvm/docs/api/classes/llvm/hexagonasmprinter/#aee072cd97eb6d078d122611833049aa6">llvm::HexagonAsmPrinter::HexagonProcessInstruction</a>.</p>

</div>
</div>

### getSubRegIndex() {#ab2c943894d8d91dead449b33a77981c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned MCRegisterInfo::getSubRegIndex (<a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> RegNo, <a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> SubRegNo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>For a given register pair, return the sub-register index if the second register is a sub-register of the first.</p>


<p>Return zero otherwise.</p>


<p>Declaration at line 391 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcregisterinfo-h">MCRegisterInfo.h</a>, definition at line 130 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcregisterinfo-cpp">MCRegisterInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a20afbbc02b58a57256a9ac9736d08838">get</a>, <a href="#af946f316ed42f8b5eb99735a3b587ab5">getNumRegs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#a92a6b0a9b7228d190b0a7d8ae3ef03c7">SubReg</a>, <a href="/web-llvm/docs/api/structs/llvm/mcregisterdesc/#ad61c747e243c73c0e6b6a0cfcc4a45ad">llvm::MCRegisterDesc::SubRegIndices</a> and <a href="#a9ded59d8266ccd2647bfd81722046beb">subregs</a>.</p>

</div>
</div>

### InitMCRegisterInfo() {#a773b83ede7cbfdce567311d244b956a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MCRegisterInfo::InitMCRegisterInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/mcregisterdesc">MCRegisterDesc</a> * D, unsigned NR, unsigned RA, unsigned PC, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcregisterclass">MCRegisterClass</a> * C, unsigned NC, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#aad72cfbb210808985a9dc19f4e5d8542">MCPhysReg</a>(*) RURoots=[2], unsigned NRU, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> int16_t * DL, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/lanebitmask">LaneBitmask</a> * RUMS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Strings, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * ClassStrings, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint16_t * SubIndices, unsigned NumIndices, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint16_t * RET)</td>
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

<p>Initialize <a href="/web-llvm/docs/api/classes/llvm/mcregisterinfo">MCRegisterInfo</a>, called by <a href="/web-llvm/docs/api/namespaces/llvm/tablegen">TableGen</a> auto-generated routines.</p>


<p><em>DO NOT USE</em>.</p>


<p>Definition at line 278 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcregisterinfo-h">MCRegisterInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a6a9f043784cf87001c84980afa76da82">D</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regutils-h/#a1fa2460e32327ade49189c95740bc1b5">NC</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sioptimizeexecmaskingprera-cpp/#a3e47bdb3e296b00df96eff7896fa57bf">RA</a>.</p>

</div>
</div>

### isArtificial() {#ac075ed8f381fe6f102ac864a339124a6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCRegisterInfo::isArtificial (<a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> RegNo)</td>
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

<p>Returns true if the given register is artificial, which means it represents a regunit that is not separately addressable but still needs to be modelled, such as the top 16-bits of a 32-bit GPR.</p>

<p>Definition at line 405 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcregisterinfo-h">MCRegisterInfo.h</a>.</p>


<p>References <a href="#a20afbbc02b58a57256a9ac9736d08838">get</a> and <a href="/web-llvm/docs/api/structs/llvm/mcregisterdesc/#adba859b2f782736e5c0b036a0324486f">llvm::MCRegisterDesc::IsArtificial</a>.</p>


<p>Referenced by <a href="#a9073d0a5218514fa4deb7ef2aa831492">isArtificialRegUnit</a>.</p>

</div>
</div>

### isArtificialRegUnit() {#a9073d0a5218514fa4deb7ef2aa831492}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MCRegisterInfo::isArtificialRegUnit (<a href="/web-llvm/docs/api/namespaces/llvm/#a8adc81fee7f9e66260dd2b626660c9c9">MCRegUnit</a> Unit)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true when the given register unit is considered artificial.</p>


<p><a href="/web-llvm/docs/api/classes/llvm/register">Register</a> units are considered artificial when at least one of the root registers is artificial.</p>


<p>Declaration at line 410 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcregisterinfo-h">MCRegisterInfo.h</a>, definition at line 224 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcregisterinfo-cpp">MCRegisterInfo.cpp</a>.</p>


<p>References <a href="#ac075ed8f381fe6f102ac864a339124a6">isArtificial</a> and <a href="#a871e5c4479bde111063c92656dadf3cb">MCRegUnitRootIterator</a>.</p>

</div>
</div>

### isConstant() {#aaf1506fdb514093df726e00b8f665ebf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCRegisterInfo::isConstant (<a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> RegNo)</td>
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

<p>Returns true if the given register is constant.</p>

<p>Definition at line 400 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcregisterinfo-h">MCRegisterInfo.h</a>.</p>


<p>References <a href="#a20afbbc02b58a57256a9ac9736d08838">get</a> and <a href="/web-llvm/docs/api/structs/llvm/mcregisterdesc/#ac40b431484abe6abeb1d37e50dcfd3ea">llvm::MCRegisterDesc::IsConstant</a>.</p>

</div>
</div>

### isSubRegister() {#a97b138b96791a09a0d9b9c77f0fb6e85}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCRegisterInfo::isSubRegister (<a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> RegA, <a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> RegB)</td>
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

<p>Returns true if RegB is a sub-register of RegA.</p>

<p>Definition at line 483 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcregisterinfo-h">MCRegisterInfo.h</a>.</p>


<p>Reference <a href="#ab8e1321ecb267615f4f4be14b92cf03a">isSuperRegister</a>.</p>

</div>
</div>

### isSubRegisterEq() {#ac5ea214c523615af8b7c8c6547ef59de}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCRegisterInfo::isSubRegisterEq (<a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> RegA, <a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> RegB)</td>
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

<p>Returns true if RegB is a sub-register of RegA or if RegB == RegA.</p>

<p>Definition at line 491 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcregisterinfo-h">MCRegisterInfo.h</a>.</p>


<p>Reference <a href="#a10add2603cf9d4706e64a3605783b764">isSuperRegisterEq</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcinstrdesc/#a53879499740e1ed3770a41e9a444ee5b">llvm::MCInstrDesc::hasDefOfPhysReg</a> and <a href="#a973016c591557c107018a0e6478b30a9">isSuperOrSubRegisterEq</a>.</p>

</div>
</div>

### isSuperOrSubRegisterEq() {#a973016c591557c107018a0e6478b30a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCRegisterInfo::isSuperOrSubRegisterEq (<a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> RegA, <a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> RegB)</td>
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

<p>Returns true if RegB is a super-register or sub-register of RegA or if RegB == RegA.</p>

<p>Definition at line 503 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcregisterinfo-h">MCRegisterInfo.h</a>.</p>


<p>References <a href="#ac5ea214c523615af8b7c8c6547ef59de">isSubRegisterEq</a> and <a href="#ab8e1321ecb267615f4f4be14b92cf03a">isSuperRegister</a>.</p>

</div>
</div>

### isSuperRegister() {#ab8e1321ecb267615f4f4be14b92cf03a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCRegisterInfo::isSuperRegister (<a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> RegA, <a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> RegB)</td>
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

<p>Returns true if RegB is a super-register of RegA.</p>

<p>Definition at line 488 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcregisterinfo-h">MCRegisterInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#acd1cd968cb420c82d70926920fcdc7d7">llvm::is_contained</a> and <a href="#a5e72490b2e8a4c4f70e0aab62f0ea176">superregs</a>.</p>


<p>Referenced by <a href="#a97b138b96791a09a0d9b9c77f0fb6e85">isSubRegister</a>, <a href="#a973016c591557c107018a0e6478b30a9">isSuperOrSubRegisterEq</a> and <a href="#a10add2603cf9d4706e64a3605783b764">isSuperRegisterEq</a>.</p>

</div>
</div>

### isSuperRegisterEq() {#a10add2603cf9d4706e64a3605783b764}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCRegisterInfo::isSuperRegisterEq (<a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> RegA, <a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> RegB)</td>
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

<p>Returns true if RegB is a super-register of RegA or if RegB == RegA.</p>

<p>Definition at line 497 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcregisterinfo-h">MCRegisterInfo.h</a>.</p>


<p>Reference <a href="#ab8e1321ecb267615f4f4be14b92cf03a">isSuperRegister</a>.</p>


<p>Referenced by <a href="#ac5ea214c523615af8b7c8c6547ef59de">isSubRegisterEq</a>.</p>

</div>
</div>

### mapDwarfRegsToLLVMRegs() {#a1b44c113e5e36696965e0a8e237d8644}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MCRegisterInfo::mapDwarfRegsToLLVMRegs (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/mcregisterinfo/dwarfllvmregpair">DwarfLLVMRegPair</a> * Map, unsigned Size, bool isEH)</td>
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

<p>Used to initialize Dwarf register to LLVM register number mapping.</p>


<p>Called by <a href="/web-llvm/docs/api/namespaces/llvm/tablegen">TableGen</a> auto-generated routines. <em>DO NOT USE</em>.</p>


<p>Definition at line 331 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcregisterinfo-h">MCRegisterInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>

</div>
</div>

### mapLLVMRegsToDwarfRegs() {#ab7c254cf3539a51c7d3170e13e84e471}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MCRegisterInfo::mapLLVMRegsToDwarfRegs (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/mcregisterinfo/dwarfllvmregpair">DwarfLLVMRegPair</a> * Map, unsigned Size, bool isEH)</td>
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

<p>Used to initialize LLVM register to Dwarf register number mapping.</p>


<p>Called by <a href="/web-llvm/docs/api/namespaces/llvm/tablegen">TableGen</a> auto-generated routines. <em>DO NOT USE</em>.</p>


<p>Definition at line 317 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcregisterinfo-h">MCRegisterInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>

</div>
</div>

### mapLLVMRegToCVReg() {#a5b3e8d277800ba2430072436f053ab3d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MCRegisterInfo::mapLLVMRegToCVReg (<a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> LLVMReg, int CVReg)</td>
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



<p>Definition at line 351 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcregisterinfo-h">MCRegisterInfo.h</a>.</p>

</div>
</div>

### mapLLVMRegToSEHReg() {#ad08a70c5c39a83a86528e4cd6ef66a16}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MCRegisterInfo::mapLLVMRegToSEHReg (<a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> LLVMReg, int SEHReg)</td>
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

<p>mapLLVMRegToSEHReg - Used to initialize LLVM register to SEH register number mapping.</p>


<p>By default the SEH register number is just the same as the LLVM register number. FIXME: <a href="/web-llvm/docs/api/namespaces/llvm/tablegen">TableGen</a> these numbers. Currently this requires target specific initialization code.</p>


<p>Definition at line 347 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcregisterinfo-h">MCRegisterInfo.h</a>.</p>

</div>
</div>

### regclass\_begin() {#a412da2ed683a7a3f9e888178753ee200}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">regclass_iterator llvm::MCRegisterInfo::regclass_begin ()</td>
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



<p>Definition at line 454 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcregisterinfo-h">MCRegisterInfo.h</a>.</p>


<p>Referenced by <a href="#a11124059eb4728d5aa71cbff07e9f178">getNumRegClasses</a> and <a href="#a3cec2db86fe526dfbe229a598ea82e1b">regclasses</a>.</p>

</div>
</div>

### regclass\_end() {#a1adcc58c9411eebe3577d71087f9efc3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">regclass_iterator llvm::MCRegisterInfo::regclass_end ()</td>
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



<p>Definition at line 455 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcregisterinfo-h">MCRegisterInfo.h</a>.</p>


<p>Referenced by <a href="#a11124059eb4728d5aa71cbff07e9f178">getNumRegClasses</a> and <a href="#a3cec2db86fe526dfbe229a598ea82e1b">regclasses</a>.</p>

</div>
</div>

### regclasses() {#a3cec2db86fe526dfbe229a598ea82e1b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; regclass_iterator &gt; llvm::MCRegisterInfo::regclasses ()</td>
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



<p>Definition at line 456 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcregisterinfo-h">MCRegisterInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>, <a href="#a412da2ed683a7a3f9e888178753ee200">regclass_begin</a> and <a href="#a1adcc58c9411eebe3577d71087f9efc3">regclass_end</a>.</p>

</div>
</div>

### regsOverlap() {#a0bd1b194b601377bdb0f3a4a6e1f7e0d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MCRegisterInfo::regsOverlap (<a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> RegA, <a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> RegB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if the two registers are equal or alias each other.</p>

<p>Declaration at line 508 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcregisterinfo-h">MCRegisterInfo.h</a>, definition at line 211 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcregisterinfo-cpp">MCRegisterInfo.cpp</a>.</p>


<p>References <a href="#acdaa5f1dcfe0ac250e2c0f285517494f">MCRegUnitIterator</a> and <a href="#abf9973b1c9926f0903d0c6bddfc93118">regunits</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64registerinfo/#af05862d6eaf49d6ca3a5ddac9231fd0d">llvm::AArch64RegisterInfo::explainReservedReg</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64registerinfo/#aaaed10441dd729ce9fdc91120f2a77f0">llvm::AArch64RegisterInfo::isAsmClobberable</a> and <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo/#ab5dddfd4ef6db864a18ecdbe51331b92">llvm::TargetRegisterInfo::regsOverlap</a>.</p>

</div>
</div>

### regunits() {#abf9973b1c9926f0903d0c6bddfc93118}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; MCRegUnitIterator &gt; llvm::MCRegisterInfo::regunits (<a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> Reg)</td>
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

<p>Returns an iterator range over all regunits for <span class="doxyComputerOutput">Reg</span>.</p>

<p>Definition at line 262 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcregisterinfo-h">MCRegisterInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>, <a href="#acdaa5f1dcfe0ac250e2c0f285517494f">MCRegUnitIterator</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo/#a0e61a18a8344327fa20ead0274ac9277">llvm::TargetRegisterInfo::hasRegUnit</a> and <a href="#a0bd1b194b601377bdb0f3a4a6e1f7e0d">regsOverlap</a>.</p>

</div>
</div>

### sub\_and\_superregs\_inclusive() {#ad85f1120e6b067734e6a186f29da3c73}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">detail::concat_range&lt; const MCPhysReg, iterator_range&lt; MCSubRegIterator &gt;, iterator_range&lt; MCSuperRegIterator &gt; &gt; llvm::MCRegisterInfo::sub_and_superregs_inclusive (<a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> Reg)</td>
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

<p>Return an iterator range over all sub- and super-registers of <span class="doxyComputerOutput">Reg</span>, including <span class="doxyComputerOutput">Reg</span>.</p>

<p>Definition at line 259 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcregisterinfo-h">MCRegisterInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a52ff73f5c87e0fb78fbdca0465300c95">llvm::concat</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a>, <a href="#a95656353b813a1dd7ddfa7d8445633a8">subregs_inclusive</a> and <a href="#a5e72490b2e8a4c4f70e0aab62f0ea176">superregs</a>.</p>

</div>
</div>

### subregs() {#a9ded59d8266ccd2647bfd81722046beb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; MCSubRegIterator &gt; llvm::MCRegisterInfo::subregs (<a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> Reg)</td>
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

<p>Return an iterator range over all sub-registers of <span class="doxyComputerOutput">Reg</span>, excluding <span class="doxyComputerOutput">Reg</span>.</p>

<p>Definition at line 241 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcregisterinfo-h">MCRegisterInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>, <a href="#a7aba84294411bec516c4f99c2743d8aa">MCSubRegIterator</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a>.</p>


<p>Referenced by <a href="#ae3ba9f77f723402ff1e1f6d8ac0e3b36">getSubReg</a> and <a href="#ab2c943894d8d91dead449b33a77981c5">getSubRegIndex</a>.</p>

</div>
</div>

### subregs\_inclusive() {#a95656353b813a1dd7ddfa7d8445633a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; MCSubRegIterator &gt; llvm::MCRegisterInfo::subregs_inclusive (<a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> Reg)</td>
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

<p>Return an iterator range over all sub-registers of <span class="doxyComputerOutput">Reg</span>, including <span class="doxyComputerOutput">Reg</span>.</p>

<p>Definition at line 245 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcregisterinfo-h">MCRegisterInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>, <a href="#a7aba84294411bec516c4f99c2743d8aa">MCSubRegIterator</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mipsreginforecord/#a08ccbcf5688d00eb218e2dac89eedcb1">llvm::MipsRegInfoRecord::SetPhysRegUsed</a> and <a href="#ad85f1120e6b067734e6a186f29da3c73">sub_and_superregs_inclusive</a>.</p>

</div>
</div>

### superregs() {#a5e72490b2e8a4c4f70e0aab62f0ea176}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; MCSuperRegIterator &gt; llvm::MCRegisterInfo::superregs (<a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> Reg)</td>
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

<p>Return an iterator range over all super-registers of <span class="doxyComputerOutput">Reg</span>, excluding <span class="doxyComputerOutput">Reg</span>.</p>

<p>Definition at line 249 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcregisterinfo-h">MCRegisterInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>, <a href="#a98195db99f78cd46313e0de07882b7bb">MCSuperRegIterator</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo/#a7bd2eaf010a0c53df66932fc514f1cc9">llvm::TargetRegisterInfo::checkAllSuperRegsMarked</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonasmprinter-cpp/#aa974adedc988dcb5c7b9600781bec9f1">getHexagonRegisterPair</a>, <a href="#a2168c5f22e98b5c471060a3dfc1ec0db">getMatchingSuperReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseregisterinfo-cpp/#ac2221ad71323cfdfb9d5909e7d1f3775">getPairedGPR</a>, <a href="#ab8e1321ecb267615f4f4be14b92cf03a">isSuperRegister</a> and <a href="#ad85f1120e6b067734e6a186f29da3c73">sub_and_superregs_inclusive</a>.</p>

</div>
</div>

### superregs\_inclusive() {#ad1f2700e4a533bcbd9d3c4e156a14d67}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; MCSuperRegIterator &gt; llvm::MCRegisterInfo::superregs_inclusive (<a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> Reg)</td>
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

<p>Return an iterator range over all super-registers of <span class="doxyComputerOutput">Reg</span>, including <span class="doxyComputerOutput">Reg</span>.</p>

<p>Definition at line 253 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcregisterinfo-h">MCRegisterInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>, <a href="#a98195db99f78cd46313e0de07882b7bb">MCSuperRegIterator</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo/#a40618817060842f7ea6164f397c2fbd8">llvm::TargetRegisterInfo::markSuperRegs</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### getCachedAliasesOf() {#af7f9f1c04c21fa0720da554972630115}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; MCPhysReg &gt; MCRegisterInfo::getCachedAliasesOf (<a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> R)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 194 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcregisterinfo-h">MCRegisterInfo.h</a>, definition at line 86 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcregisterinfo-cpp">MCRegisterInfo.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Classes {#ae424236d74a204c21f85d27410b8bf42}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCRegisterClass* llvm::MCRegisterInfo::Classes</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 167 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcregisterinfo-h">MCRegisterInfo.h</a>.</p>

</div>
</div>

### Desc {#a54c02aa4e6491600a7ec4d7372fa18b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCRegisterDesc* llvm::MCRegisterInfo::Desc</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 163 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcregisterinfo-h">MCRegisterInfo.h</a>.</p>

</div>
</div>

### DiffLists {#a6ad217e3cbcafcc2464774a260fe3028}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const int16_t* llvm::MCRegisterInfo::DiffLists</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 171 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcregisterinfo-h">MCRegisterInfo.h</a>.</p>

</div>
</div>

### Dwarf2LRegs {#af1c131d49c4d0f672c2132085f7e6176}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DwarfLLVMRegPair* llvm::MCRegisterInfo::Dwarf2LRegs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 188 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcregisterinfo-h">MCRegisterInfo.h</a>.</p>

</div>
</div>

### Dwarf2LRegsSize {#a98c90079c6bbf40879ec419c04ad4739}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MCRegisterInfo::Dwarf2LRegsSize</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 184 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcregisterinfo-h">MCRegisterInfo.h</a>.</p>

</div>
</div>

### EHDwarf2LRegs {#a21a01aa3ef51e6e201157cce5d8f8526}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DwarfLLVMRegPair* llvm::MCRegisterInfo::EHDwarf2LRegs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 189 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcregisterinfo-h">MCRegisterInfo.h</a>.</p>

</div>
</div>

### EHDwarf2LRegsSize {#a74a71dd60aaa8151556962f3655ae492}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MCRegisterInfo::EHDwarf2LRegsSize</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 185 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcregisterinfo-h">MCRegisterInfo.h</a>.</p>

</div>
</div>

### EHL2DwarfRegs {#a1446417a6f0dfadf5a9eb5b2a182e059}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DwarfLLVMRegPair* llvm::MCRegisterInfo::EHL2DwarfRegs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 187 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcregisterinfo-h">MCRegisterInfo.h</a>.</p>

</div>
</div>

### EHL2DwarfRegsSize {#aa88e55f6b75b6c3460e0e992c4698ac4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MCRegisterInfo::EHL2DwarfRegsSize</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 183 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcregisterinfo-h">MCRegisterInfo.h</a>.</p>

</div>
</div>

### L2CVRegs {#a7e655117db4c67a3f83f4180b1b99323}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;MCRegister, int&gt; llvm::MCRegisterInfo::L2CVRegs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 191 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcregisterinfo-h">MCRegisterInfo.h</a>.</p>

</div>
</div>

### L2DwarfRegs {#a17f9328b381b7a96f82f5279536ef493}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DwarfLLVMRegPair* llvm::MCRegisterInfo::L2DwarfRegs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 186 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcregisterinfo-h">MCRegisterInfo.h</a>.</p>

</div>
</div>

### L2DwarfRegsSize {#a18c628855599c97c683fb8cb3925635f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MCRegisterInfo::L2DwarfRegsSize</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 182 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcregisterinfo-h">MCRegisterInfo.h</a>.</p>

</div>
</div>

### L2SEHRegs {#a8fe7e1d016aa5e245c9e35471c7c28a6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;MCRegister, int&gt; llvm::MCRegisterInfo::L2SEHRegs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 190 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcregisterinfo-h">MCRegisterInfo.h</a>.</p>

</div>
</div>

### NumClasses {#a9b79c907cd11441d53fafe21c060bbc8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MCRegisterInfo::NumClasses</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 168 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcregisterinfo-h">MCRegisterInfo.h</a>.</p>

</div>
</div>

### NumRegs {#aa620991b540ef6cc9a8e419d8b9c6521}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MCRegisterInfo::NumRegs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 164 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcregisterinfo-h">MCRegisterInfo.h</a>.</p>

</div>
</div>

### NumRegUnits {#a66b72219bd2264eccdbdc307254d2cc4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MCRegisterInfo::NumRegUnits</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 169 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcregisterinfo-h">MCRegisterInfo.h</a>.</p>

</div>
</div>

### NumSubRegIndices {#a677bdf16f121f92ac6adcc5cfef66c38}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MCRegisterInfo::NumSubRegIndices</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 178 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcregisterinfo-h">MCRegisterInfo.h</a>.</p>

</div>
</div>

### PCReg {#a4ac8cead3897251897eb93e4221682c6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCRegister llvm::MCRegisterInfo::PCReg</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 166 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcregisterinfo-h">MCRegisterInfo.h</a>.</p>

</div>
</div>

### RAReg {#ab2e8be1ad6b0e39a8a4cd2a95e285c26}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCRegister llvm::MCRegisterInfo::RAReg</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 165 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcregisterinfo-h">MCRegisterInfo.h</a>.</p>

</div>
</div>

### RegAliasesCache {#ac01a6585a0164f34efd67646a0aae2dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;std::vector&lt;MCPhysReg&gt; &gt; llvm::MCRegisterInfo::RegAliasesCache</td>
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



<p>Definition at line 193 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcregisterinfo-h">MCRegisterInfo.h</a>.</p>

</div>
</div>

### RegClassStrings {#a2e2f5fe05c011bb3c9e603f671dfe9d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char* llvm::MCRegisterInfo::RegClassStrings</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 175 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcregisterinfo-h">MCRegisterInfo.h</a>.</p>

</div>
</div>

### RegEncodingTable {#aa4e7bd7bd37f516924081c0e8ca5454c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const uint16_t* llvm::MCRegisterInfo::RegEncodingTable</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 179 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcregisterinfo-h">MCRegisterInfo.h</a>.</p>

</div>
</div>

### RegStrings {#a1189f9310d3fbb014c068c6b37a64a61}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char* llvm::MCRegisterInfo::RegStrings</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 174 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcregisterinfo-h">MCRegisterInfo.h</a>.</p>

</div>
</div>

### RegUnitMaskSequences {#a2dcdd494ab84ec17619f9ad6d8e0be8e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const LaneBitmask* llvm::MCRegisterInfo::RegUnitMaskSequences</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 172 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcregisterinfo-h">MCRegisterInfo.h</a>.</p>

</div>
</div>

### RegUnitRoots {#af739cac0b1e828ec0380bfb96bbab0b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCPhysReg(* llvm::MCRegisterInfo::RegUnitRoots)[2]</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 170 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcregisterinfo-h">MCRegisterInfo.h</a>.</p>

</div>
</div>

### SubRegIndices {#a09405597445301177b8d5b6d683f563e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const uint16_t* llvm::MCRegisterInfo::SubRegIndices</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 176 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcregisterinfo-h">MCRegisterInfo.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcregisterinfo-h">MCRegisterInfo.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/mc/mcregisterinfo-cpp">MCRegisterInfo.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>

---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/dwarf-linker/classic/compileunit
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `CompileUnit` Class Reference

<p>Stores all information relating to a compile unit, be it in its original instance in the object file to its brand new cloned and generated <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> tree. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::dwarf_linker::classic::CompileUnit { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinkercompileunit-h">llvm/DWARFLinker/Classic/DWARFLinkerCompileUnit.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af096fb0448f7ae66e40a5572388d3eb3">CompileUnit</a> (DWARFUnit &amp;OrigUnit, unsigned ID, bool CanUseODR, StringRef ClangModuleName)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dwarfunit">DWARFUnit</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa4d3d402cff2849ef9955a380d27c404">getOrigUnit</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af0effacef1abf3538bc1128e5bc941ce">getUniqueID</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a80d99d15a9e1149425f3f33d4bafa84d">createOutputDIE</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a59d1b8bf5202f58fdb82afff38ee53a9">getOutputUnitDIE</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#ac94a19fc8c57bf0350fc4e9f45897828">dwarf::Tag</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afdbad7d065e4c8a6c6e19231853ed629">getTag</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeb5005a183bdc0a2dc5b81c7f3e33229">hasODR</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa65ebf8014c4fcdcb0a3cee6ad8c8749">isClangModule</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a640543dfd6a85c0f9910ecf22faca02c">getLanguage</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6d3d35230825470499dc48f866facb9a">getSysRoot</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the DW_AT_LLVM_sysroot of the compile unit or an empty <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>. <a href="#a6d3d35230825470499dc48f866facb9a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::string &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aff12e7a12c69c545de74f1d62bc10dbb">getClangModuleName</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/classic/compileunit/dieinfo">DIEInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7146a3a9739628d43a2a0ffa00f034cf">getInfo</a> (unsigned Idx)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/classic/compileunit/dieinfo">DIEInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c93ff758e5b22fb10bb640419e8b19b">getInfo</a> (unsigned Idx) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/classic/compileunit/dieinfo">DIEInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54bfcabd5abd73941b6f69aa1937ae5a">getInfo</a> (const DWARFDie &amp;Die)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a496658fa7a527a14a0f58a0eff9ebb00">getStartOffset</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5c4061dfca64ee36247c347e965753bc">getNextUnitOffset</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a72cbef5a618f5495b78db75035c7d00b">setStartOffset</a> (uint64_t DebugInfoSize)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a24a9cad70ea472d556b936b8ea84a4f6">getLowPc</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a653e9a64a41977537c676bf48f97f79a">getHighPc</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a931e1f666e7d5c89c5e165450824877b">hasLabelAt</a> (uint64_t Addr) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/classic/#a72b92e7e63dd93c78821c54fc9782e66">RangesTy</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb01409f3b865f49acc8f61ce7c9d794">getFunctionRanges</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/classic/#a06e26f1f34b50ab3948efbcc37f4b764">RngListAttributesTy</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af3b82d842a7e76a5929ddfd411968fbe">getRangesAttributes</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/classic/patchlocation">PatchLocation</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a728fcd657aa622f779e56bc52b831d7a">getUnitRangesAttribute</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/classic/#ad510da95fc93bd38cc760f31b37e2713">LocListAttributesTy</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa5e7d6fde0067d4f5c7c8deefbd6c48e">getLocationAttributes</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae37905defe9c94924f281526d50be047">markEverythingAsKept</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Mark every <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> in this unit as kept. <a href="#ae37905defe9c94924f281526d50be047">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab048b68f7b45d848956db58a72446e42">computeNextUnitOffset</a> (uint16_t DwarfVersion)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute the end offset for this unit. <a href="#ab048b68f7b45d848956db58a72446e42">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e0245f87f002cbfb58328602d376b0f">noteForwardReference</a> (DIE *Die, const CompileUnit *RefUnit, DeclContext *Ctxt, PatchLocation Attr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Keep track of a forward reference to <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> <span class="doxyComputerOutput">Die</span> in <span class="doxyComputerOutput">RefUnit</span> by <span class="doxyComputerOutput">Attr</span>. <a href="#a1e0245f87f002cbfb58328602d376b0f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0af355b794e2a9bcb54dd930f7ad4b54">fixupForwardReferences</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Apply all fixups recorded by <a href="#a1e0245f87f002cbfb58328602d376b0f">noteForwardReference()</a>. <a href="#a0af355b794e2a9bcb54dd930f7ad4b54">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac585ccf885d9c7926822bcb863e05c44">addLabelLowPc</a> (uint64_t LabelLowPc, int64_t PcOffset)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add the low_pc of a label that is relocated by applying offset <span class="doxyComputerOutput">PCOffset</span>. <a href="#ac585ccf885d9c7926822bcb863e05c44">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a023822e7b997f5371945203928b443f3">addFunctionRange</a> (uint64_t LowPC, uint64_t HighPC, int64_t PCOffset)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add a function range [<span class="doxyComputerOutput">LowPC</span>, <span class="doxyComputerOutput">HighPC</span>) that is relocated by applying offset <span class="doxyComputerOutput">PCOffset</span>. <a href="#a023822e7b997f5371945203928b443f3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a87ab998fa372edd70feb6fea541b02c3">noteRangeAttribute</a> (const DIE &amp;Die, PatchLocation Attr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Keep track of a DW_AT_range attribute that we will need to patch up later. <a href="#a87ab998fa372edd70feb6fea541b02c3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1fc43f16674953b27b04386fdfcd3968">noteLocationAttribute</a> (PatchLocation Attr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Keep track of a location attribute pointing to a location list in the debug_loc section. <a href="#a1fc43f16674953b27b04386fdfcd3968">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a46d841a84033b388ff7fcb14a5e3b736">addNamespaceAccelerator</a> (const DIE *Die, DwarfStringPoolEntryRef Name)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add a name accelerator entry for <em>Die</em> with <em>Name</em>. <a href="#a46d841a84033b388ff7fcb14a5e3b736">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a391479b2f839b262d39fcff975d72376">addNameAccelerator</a> (const DIE *Die, DwarfStringPoolEntryRef Name, bool SkipPubnamesSection=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add a name accelerator entry for <em>Die</em> with <em>Name</em>. <a href="#a391479b2f839b262d39fcff975d72376">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a904e72a5a24bd206b164e6a3d260417d">addObjCAccelerator</a> (const DIE *Die, DwarfStringPoolEntryRef Name, bool SkipPubnamesSection=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add various accelerator entries for <span class="doxyComputerOutput">Die</span> with <span class="doxyComputerOutput">Name</span> which is stored in the string table at <span class="doxyComputerOutput">Offset</span>. <a href="#a904e72a5a24bd206b164e6a3d260417d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa370919f943300e25bac7a0d0d3949f7">addTypeAccelerator</a> (const DIE *Die, DwarfStringPoolEntryRef Name, bool ObjcClassImplementation, uint32_t QualifiedNameHash)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add a type accelerator entry for <span class="doxyComputerOutput">Die</span> with <span class="doxyComputerOutput">Name</span> which is stored in the string table at <span class="doxyComputerOutput">Offset</span>. <a href="#aa370919f943300e25bac7a0d0d3949f7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/classic/compileunit/accelinfo">AccelInfo</a> &gt; &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0188245139fc5b186af8edebb3f7fb12">getPubnames</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/classic/compileunit/accelinfo">AccelInfo</a> &gt; &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a07559c00dfa28cf4aaa3aafa471ce6ea">getPubtypes</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/classic/compileunit/accelinfo">AccelInfo</a> &gt; &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a00261f4e457b54417312beeb89ed5d2d">getNamespaces</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/classic/compileunit/accelinfo">AccelInfo</a> &gt; &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a081191b8ac67bfd99ee13513427a9a57">getObjC</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab79dc6f321ff81658c447f147f07e5c4">getLabelBegin</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a889518b79cbc9ef0fe5cd7a451ac6ec0">setLabelBegin</a> (MCSymbol *S)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/classic/#a06e26f1f34b50ab3948efbcc37f4b764">RngListAttributesTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ad61ecb1bc911b570c60d8d9da5e697">RangeAttributes</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>'rnglist'(DW_AT_ranges, DW_AT_start_scope) attributes to patch after we have gathered all the unit's function addresses. <a href="#a2ad61ecb1bc911b570c60d8d9da5e697">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/classic/patchlocation">PatchLocation</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af0bfad562c2b8054154266df495436b9">UnitRangeAttribute</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/classic/compileunit/accelinfo">AccelInfo</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af451a60a6e536b02744ac5f7adf362af">Pubnames</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Accelerator entries for the unit, both for the pub* sections and the apple* ones. <a href="#af451a60a6e536b02744ac5f7adf362af">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/classic/compileunit/accelinfo">AccelInfo</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a48027f257ecad467c731534cd8a26012">Pubtypes</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/classic/compileunit/accelinfo">AccelInfo</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e31d919bd9cc6b84f21f3b6e7b0d976">Namespaces</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/classic/compileunit/accelinfo">AccelInfo</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a84e38593b64111cc6df48e30682afd02">ObjC</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dwarfunit">DWARFUnit</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c0e7890f4a13ffc2cbbadf3b3b1934d">OrigUnit</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac38377abb13013661211e1225c8d9faf">ID</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/classic/compileunit/dieinfo">DIEInfo</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acfb6202cad0699b06da89958ee548ded">Info</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> info indexed by <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> index. <a href="#acfb6202cad0699b06da89958ee548ded">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/structs/llvm/basicdieunit">BasicDIEUnit</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a932f938a67153098c478c8e049043648">NewUnit</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a35b3ffdff4255aaa11e45a18f9381aa6">LabelBegin</a> = nullptr</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa1c990fcbc67828c631f0451d868b3f9">StartOffset</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a93cf5cf983ae654e6940dcb530214521">NextUnitOffset</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5ddf9882d9726798dcdfe8db6e1fd41c">LowPc</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afc4b816a791637771936538cd5b8a0c8">HighPc</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; std::tuple&lt; <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> *, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/classic/compileunit">CompileUnit</a> *, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/classic/declcontext">DeclContext</a> *, <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/classic/patchlocation">PatchLocation</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a01c9125908541f31c2c5e03b38806eb7">ForwardDIEReferences</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A list of attributes to fixup with the absolute offset of a <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> in the debug_info section. <a href="#a01c9125908541f31c2c5e03b38806eb7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/classic/#a72b92e7e63dd93c78821c54fc9782e66">RangesTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a347c5be17f8237920857f8007a864d79">Ranges</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The ranges in that map are the PC ranges for functions in this unit, associated with the PC offset to apply to the addresses to get the linked address. <a href="#a347c5be17f8237920857f8007a864d79">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smalldensemap">SmallDenseMap</a>&lt; uint64_t, uint64_t, 1 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aadf6f9b5618feac3e9384ae082280b06">Labels</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The DW_AT_low_pc of each DW_TAG_label. <a href="#aadf6f9b5618feac3e9384ae082280b06">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/classic/#ad510da95fc93bd38cc760f31b37e2713">LocListAttributesTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab1fc8befa43418a3677dbbf37718eb74">LocationAttributes</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Location attributes that need to be transferred from the original debug_loc section to the linked one. <a href="#ab1fc8befa43418a3677dbbf37718eb74">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ada6c3ca189bd0807becb22b1cf2c7ea7">HasODR</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Is this unit subject to the ODR rule? <a href="#ada6c3ca189bd0807becb22b1cf2c7ea7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint16_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af72dc342d67a1ff6f1d3940523d3d494">Language</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The DW_AT_language of this unit. <a href="#af72dc342d67a1ff6f1d3940523d3d494">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a22f0af8fcb6c84c7d55b9fb42f519881">SysRoot</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The DW_AT_LLVM_sysroot of this unit. <a href="#a22f0af8fcb6c84c7d55b9fb42f519881">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a097655dbeffa4d6d1379252eeedcb3">ClangModuleName</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If this is a Clang module, this holds the module's name. <a href="#a6a097655dbeffa4d6d1379252eeedcb3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Stores all information relating to a compile unit, be it in its original instance in the object file to its brand new cloned and generated <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> tree.</p>

<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### CompileUnit() {#af096fb0448f7ae66e40a5572388d3eb3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::dwarf_linker::classic::CompileUnit::CompileUnit (<a href="/web-llvm/docs/api/classes/llvm/dwarfunit">DWARFUnit</a> &amp; OrigUnit, unsigned ID, bool CanUseODR, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> ClangModuleName)</td>
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



<p>Definition at line 108 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#acdfbcf188e2d4a80837e89de2ccdffab">if</a> and <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#ae150cb3561ce0a2979ed60d29301eef7">llvm::dwarf::toUnsigned</a>.</p>


<p>Referenced by <a href="#a0af355b794e2a9bcb54dd930f7ad4b54">fixupForwardReferences</a> and <a href="#a1e0245f87f002cbfb58328602d376b0f">noteForwardReference</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addFunctionRange() {#a023822e7b997f5371945203928b443f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CompileUnit::addFunctionRange (uint64_t LowPC, uint64_t HighPC, int64_t PCOffset)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add a function range [<span class="doxyComputerOutput">LowPC</span>, <span class="doxyComputerOutput">HighPC</span>) that is relocated by applying offset <span class="doxyComputerOutput">PCOffset</span>.</p>

<p>Declaration at line 204 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>, definition at line 165 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/classic/dwarflinkercompileunit-cpp">DWARFLinkerCompileUnit.cpp</a>.</p>

</div>
</div>

### addLabelLowPc() {#ac585ccf885d9c7926822bcb863e05c44}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CompileUnit::addLabelLowPc (uint64_t LabelLowPc, int64_t PcOffset)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add the low_pc of a label that is relocated by applying offset <span class="doxyComputerOutput">PCOffset</span>.</p>

<p>Declaration at line 200 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>, definition at line 161 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/classic/dwarflinkercompileunit-cpp">DWARFLinkerCompileUnit.cpp</a>.</p>

</div>
</div>

### addNameAccelerator() {#a391479b2f839b262d39fcff975d72376}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::CompileUnit::addNameAccelerator (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> * Die, <a href="/web-llvm/docs/api/classes/llvm/dwarfstringpoolentryref">DwarfStringPoolEntryRef</a> Name, bool SkipPubnamesSection=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add a name accelerator entry for <em>Die</em> with <em>Name</em>.</p>

<p>Declaration at line 217 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>, definition at line 199 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/classic/dwarflinkercompileunit-cpp">DWARFLinkerCompileUnit.cpp</a>.</p>

</div>
</div>

### addNamespaceAccelerator() {#a46d841a84033b388ff7fcb14a5e3b736}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::CompileUnit::addNamespaceAccelerator (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> * Die, <a href="/web-llvm/docs/api/classes/llvm/dwarfstringpoolentryref">DwarfStringPoolEntryRef</a> Name)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add a name accelerator entry for <em>Die</em> with <em>Name</em>.</p>

<p>Declaration at line 214 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>, definition at line 188 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/classic/dwarflinkercompileunit-cpp">DWARFLinkerCompileUnit.cpp</a>.</p>

</div>
</div>

### addObjCAccelerator() {#a904e72a5a24bd206b164e6a3d260417d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::CompileUnit::addObjCAccelerator (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> * Die, <a href="/web-llvm/docs/api/classes/llvm/dwarfstringpoolentryref">DwarfStringPoolEntryRef</a> Name, bool SkipPubnamesSection=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add various accelerator entries for <span class="doxyComputerOutput">Die</span> with <span class="doxyComputerOutput">Name</span> which is stored in the string table at <span class="doxyComputerOutput">Offset</span>.</p>


<p><span class="doxyComputerOutput">Name</span> must be an Objective-C selector.</p>


<p>Declaration at line 223 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>, definition at line 193 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/classic/dwarflinkercompileunit-cpp">DWARFLinkerCompileUnit.cpp</a>.</p>

</div>
</div>

### addTypeAccelerator() {#aa370919f943300e25bac7a0d0d3949f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::CompileUnit::addTypeAccelerator (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> * Die, <a href="/web-llvm/docs/api/classes/llvm/dwarfstringpoolentryref">DwarfStringPoolEntryRef</a> Name, bool ObjcClassImplementation, uint32_t QualifiedNameHash)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add a type accelerator entry for <span class="doxyComputerOutput">Die</span> with <span class="doxyComputerOutput">Name</span> which is stored in the string table at <span class="doxyComputerOutput">Offset</span>.</p>

<p>Declaration at line 228 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>, definition at line 205 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/classic/dwarflinkercompileunit-cpp">DWARFLinkerCompileUnit.cpp</a>.</p>

</div>
</div>

### computeNextUnitOffset() {#ab048b68f7b45d848956db58a72446e42}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::CompileUnit::computeNextUnitOffset (uint16_t DwarfVersion)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Compute the end offset for this unit.</p>


<p>Must be called after the <a href="/web-llvm/docs/api/namespaces/cu">CU</a>'s DIEs have been cloned.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>the next unit offset (which is also the current debug_info section size).</p></dd>
</dl>


<p>Declaration at line 186 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>, definition at line 127 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/classic/dwarflinkercompileunit-cpp">DWARFLinkerCompileUnit.cpp</a>.</p>

</div>
</div>

### createOutputDIE() {#a80d99d15a9e1149425f3f33d4bafa84d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::dwarf_linker::classic::CompileUnit::createOutputDIE ()</td>
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



<p>Definition at line 132 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>.</p>

</div>
</div>

### fixupForwardReferences() {#a0af355b794e2a9bcb54dd930f7ad4b54}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::CompileUnit::fixupForwardReferences ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Apply all fixups recorded by <a href="#a1e0245f87f002cbfb58328602d376b0f">noteForwardReference()</a>.</p>

<p>Declaration at line 196 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>, definition at line 143 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/classic/dwarflinkercompileunit-cpp">DWARFLinkerCompileUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#af096fb0448f7ae66e40a5572388d3eb3">CompileUnit</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/classic/declcontext/#a398703d3a38108ed0712ef334cb77603">llvm::dwarf_linker::classic::DeclContext::getCanonicalDIEOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/die/#ac44e64e0d814099105dde610b11c9914">llvm::DIE::getOffset</a>, <a href="#a496658fa7a527a14a0f58a0eff9ebb00">getStartOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/classic/declcontext/#a148c449f20cbba036280051cac77e13a">llvm::dwarf_linker::classic::DeclContext::hasCanonicalDIE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9db8c44b250b90e3ab7e4d144e7c9c2ea60baadb22e80b147e4885ad16760e569">llvm::Ref</a> and <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/classic/patchlocation/#a297986172ace6b3e087903365ad01038">llvm::dwarf_linker::classic::PatchLocation::set</a>.</p>

</div>
</div>

### getClangModuleName() {#aff12e7a12c69c545de74f1d62bc10dbb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const std::string &amp; llvm::dwarf_linker::classic::CompileUnit::getClangModuleName ()</td>
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



<p>Definition at line 148 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>.</p>

</div>
</div>

### getFunctionRanges() {#abb01409f3b865f49acc8f61ce7c9d794}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const RangesTy &amp; llvm::dwarf_linker::classic::CompileUnit::getFunctionRanges ()</td>
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



<p>Definition at line 166 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>.</p>

</div>
</div>

### getHighPc() {#a653e9a64a41977537c676bf48f97f79a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::dwarf_linker::classic::CompileUnit::getHighPc ()</td>
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



<p>Definition at line 163 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>.</p>

</div>
</div>

### getInfo() {#a7146a3a9739628d43a2a0ffa00f034cf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DIEInfo &amp; llvm::dwarf_linker::classic::CompileUnit::getInfo (unsigned Idx)</td>
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



<p>Definition at line 150 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>.</p>

</div>
</div>

### getInfo() {#a0c93ff758e5b22fb10bb640419e8b19b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DIEInfo &amp; llvm::dwarf_linker::classic::CompileUnit::getInfo (unsigned Idx)</td>
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



<p>Definition at line 151 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>.</p>

</div>
</div>

### getInfo() {#a54bfcabd5abd73941b6f69aa1937ae5a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DIEInfo &amp; llvm::dwarf_linker::classic::CompileUnit::getInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfdie">DWARFDie</a> &amp; Die)</td>
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



<p>Definition at line 153 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#aa19e6ee8bd7aee2cdb0877d7e07a5926">llvm::DWARFUnit::getDIEIndex</a> and <a href="#aa4d3d402cff2849ef9955a380d27c404">getOrigUnit</a>.</p>

</div>
</div>

### getLabelBegin() {#ab79dc6f321ff81658c447f147f07e5c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSymbol * llvm::dwarf_linker::classic::CompileUnit::getLabelBegin ()</td>
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



<p>Definition at line 264 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>.</p>

</div>
</div>

### getLanguage() {#a640543dfd6a85c0f9910ecf22faca02c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint16_t llvm::CompileUnit::getLanguage ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 144 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>, definition at line 49 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/classic/dwarflinkercompileunit-cpp">DWARFLinkerCompileUnit.cpp</a>.</p>


<p>References <a href="#aa4d3d402cff2849ef9955a380d27c404">getOrigUnit</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a2b5f2734488f7b1b52e982683675df24">llvm::DWARFUnit::getUnitDIE</a> and <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#ae150cb3561ce0a2979ed60d29301eef7">llvm::dwarf::toUnsigned</a>.</p>

</div>
</div>

### getLocationAttributes() {#aa5e7d6fde0067d4f5c7c8deefbd6c48e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const LocListAttributesTy &amp; llvm::dwarf_linker::classic::CompileUnit::getLocationAttributes ()</td>
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



<p>Definition at line 174 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>.</p>

</div>
</div>

### getLowPc() {#a24a9cad70ea472d556b936b8ea84a4f6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; uint64_t &gt; llvm::dwarf_linker::classic::CompileUnit::getLowPc ()</td>
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



<p>Definition at line 162 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>.</p>

</div>
</div>

### getNamespaces() {#a00261f4e457b54417312beeb89ed5d2d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const std::vector&lt; AccelInfo &gt; &amp; llvm::dwarf_linker::classic::CompileUnit::getNamespaces ()</td>
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



<p>Definition at line 261 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>.</p>

</div>
</div>

### getNextUnitOffset() {#a5c4061dfca64ee36247c347e965753bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::dwarf_linker::classic::CompileUnit::getNextUnitOffset ()</td>
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



<p>Definition at line 159 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>.</p>

</div>
</div>

### getObjC() {#a081191b8ac67bfd99ee13513427a9a57}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const std::vector&lt; AccelInfo &gt; &amp; llvm::dwarf_linker::classic::CompileUnit::getObjC ()</td>
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



<p>Definition at line 262 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>.</p>

</div>
</div>

### getOrigUnit() {#aa4d3d402cff2849ef9955a380d27c404}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DWARFUnit &amp; llvm::dwarf_linker::classic::CompileUnit::getOrigUnit ()</td>
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



<p>Definition at line 128 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>.</p>


<p>Referenced by <a href="#a54bfcabd5abd73941b6f69aa1937ae5a">getInfo</a>, <a href="#a640543dfd6a85c0f9910ecf22faca02c">getLanguage</a> and <a href="#a6d3d35230825470499dc48f866facb9a">getSysRoot</a>.</p>

</div>
</div>

### getOutputUnitDIE() {#a59d1b8bf5202f58fdb82afff38ee53a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DIE * llvm::dwarf_linker::classic::CompileUnit::getOutputUnitDIE ()</td>
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



<p>Definition at line 134 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/dieunit/#abf2a1b885dfb5c0adb161aa1f0bc5d50">llvm::DIEUnit::getUnitDie</a>.</p>

</div>
</div>

### getPubnames() {#a0188245139fc5b186af8edebb3f7fb12}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const std::vector&lt; AccelInfo &gt; &amp; llvm::dwarf_linker::classic::CompileUnit::getPubnames ()</td>
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



<p>Definition at line 259 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>.</p>

</div>
</div>

### getPubtypes() {#a07559c00dfa28cf4aaa3aafa471ce6ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const std::vector&lt; AccelInfo &gt; &amp; llvm::dwarf_linker::classic::CompileUnit::getPubtypes ()</td>
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



<p>Definition at line 260 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>.</p>

</div>
</div>

### getRangesAttributes() {#af3b82d842a7e76a5929ddfd411968fbe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const RngListAttributesTy &amp; llvm::dwarf_linker::classic::CompileUnit::getRangesAttributes ()</td>
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



<p>Definition at line 168 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>.</p>

</div>
</div>

### getStartOffset() {#a496658fa7a527a14a0f58a0eff9ebb00}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::dwarf_linker::classic::CompileUnit::getStartOffset ()</td>
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



<p>Definition at line 158 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>.</p>


<p>Referenced by <a href="#a0af355b794e2a9bcb54dd930f7ad4b54">fixupForwardReferences</a>.</p>

</div>
</div>

### getSysRoot() {#a6d3d35230825470499dc48f866facb9a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::CompileUnit::getSysRoot ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the DW_AT_LLVM_sysroot of the compile unit or an empty <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>.</p>

<p>Declaration at line 146 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>, definition at line 57 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/classic/dwarflinkercompileunit-cpp">DWARFLinkerCompileUnit.cpp</a>.</p>


<p>References <a href="#aa4d3d402cff2849ef9955a380d27c404">getOrigUnit</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a2b5f2734488f7b1b52e982683675df24">llvm::DWARFUnit::getUnitDIE</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a223dd14e7d12bc5cea01889b972a98b2">llvm::StringRef::str</a> and <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#aa10731e4d6c303386a70337b0e0668d0">llvm::dwarf::toStringRef</a>.</p>

</div>
</div>

### getTag() {#afdbad7d065e4c8a6c6e19231853ed629}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">dwarf::Tag llvm::dwarf_linker::classic::CompileUnit::getTag ()</td>
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



<p>Definition at line 140 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>.</p>

</div>
</div>

### getUniqueID() {#af0effacef1abf3538bc1128e5bc941ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::dwarf_linker::classic::CompileUnit::getUniqueID ()</td>
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



<p>Definition at line 130 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>.</p>

</div>
</div>

### getUnitRangesAttribute() {#a728fcd657aa622f779e56bc52b831d7a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; PatchLocation &gt; llvm::dwarf_linker::classic::CompileUnit::getUnitRangesAttribute ()</td>
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



<p>Definition at line 170 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>.</p>

</div>
</div>

### hasLabelAt() {#a931e1f666e7d5c89c5e165450824877b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::dwarf_linker::classic::CompileUnit::hasLabelAt (uint64_t Addr)</td>
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



<p>Definition at line 164 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>.</p>

</div>
</div>

### hasODR() {#aeb5005a183bdc0a2dc5b81c7f3e33229}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::dwarf_linker::classic::CompileUnit::hasODR ()</td>
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



<p>Definition at line 142 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>.</p>

</div>
</div>

### isClangModule() {#aa65ebf8014c4fcdcb0a3cee6ad8c8749}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::dwarf_linker::classic::CompileUnit::isClangModule ()</td>
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



<p>Definition at line 143 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>.</p>

</div>
</div>

### markEverythingAsKept() {#ae37905defe9c94924f281526d50be047}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::CompileUnit::markEverythingAsKept ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Mark every <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> in this unit as kept.</p>


<p>This function also marks variables as InDebugMap so that they appear in the reconstructed accelerator tables.</p>


<p>Declaration at line 181 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>, definition at line 65 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/classic/dwarflinkercompileunit-cpp">DWARFLinkerCompileUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>, <a href="/web-llvm/docs/api/classes/llvm/die/#aeac16c22ec5a0c13658381144c7e3439">llvm::DIE::getTag</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a815bbd56c6c63d9d49ae2720d85529ad">llvm::inFunctionScope</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aeeb5973ff74c4c4d279e275b34b7ef54">llvm::toStringRef</a>.</p>

</div>
</div>

### noteForwardReference() {#a1e0245f87f002cbfb58328602d376b0f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::CompileUnit::noteForwardReference (<a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> * Die, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/classic/compileunit">CompileUnit</a> * RefUnit, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/classic/declcontext">DeclContext</a> * Ctxt, <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/classic/patchlocation">PatchLocation</a> Attr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Keep track of a forward reference to <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> <span class="doxyComputerOutput">Die</span> in <span class="doxyComputerOutput">RefUnit</span> by <span class="doxyComputerOutput">Attr</span>.</p>


<p>Keep track of a forward cross-cu reference from this unit to <span class="doxyComputerOutput">Die</span> that lives in <span class="doxyComputerOutput">RefUnit</span>.</p>


<p>The attribute should be fixed up later to point to the absolute offset of <span class="doxyComputerOutput">Die</span> in the debug_info section or to the canonical offset of <span class="doxyComputerOutput">Ctxt</span> if it is non-null.</p>


<p>Declaration at line 192 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>, definition at line 138 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/classic/dwarflinkercompileunit-cpp">DWARFLinkerCompileUnit.cpp</a>.</p>


<p>Reference <a href="#af096fb0448f7ae66e40a5572388d3eb3">CompileUnit</a>.</p>

</div>
</div>

### noteLocationAttribute() {#a1fc43f16674953b27b04386fdfcd3968}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::CompileUnit::noteLocationAttribute (<a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/classic/patchlocation">PatchLocation</a> Attr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Keep track of a location attribute pointing to a location list in the debug_loc section.</p>

<p>Declaration at line 211 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>, definition at line 184 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/classic/dwarflinkercompileunit-cpp">DWARFLinkerCompileUnit.cpp</a>.</p>

</div>
</div>

### noteRangeAttribute() {#a87ab998fa372edd70feb6fea541b02c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::CompileUnit::noteRangeAttribute (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> &amp; Die, <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/classic/patchlocation">PatchLocation</a> Attr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Keep track of a DW_AT_range attribute that we will need to patch up later.</p>

<p>Declaration at line 207 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>, definition at line 175 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/classic/dwarflinkercompileunit-cpp">DWARFLinkerCompileUnit.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/die/#aeac16c22ec5a0c13658381144c7e3439">llvm::DIE::getTag</a>.</p>

</div>
</div>

### setLabelBegin() {#a889518b79cbc9ef0fe5cd7a451ac6ec0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::dwarf_linker::classic::CompileUnit::setLabelBegin (<a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * S)</td>
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



<p>Definition at line 265 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>.</p>

</div>
</div>

### setStartOffset() {#a72cbef5a618f5495b78db75035c7d00b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::dwarf_linker::classic::CompileUnit::setStartOffset (uint64_t DebugInfoSize)</td>
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



<p>Definition at line 160 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### Namespaces {#a1e31d919bd9cc6b84f21f3b6e7b0d976}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;AccelInfo&gt; llvm::dwarf_linker::classic::CompileUnit::Namespaces</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 317 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>.</p>

</div>
</div>

### ObjC {#a84e38593b64111cc6df48e30682afd02}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;AccelInfo&gt; llvm::dwarf_linker::classic::CompileUnit::ObjC</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 318 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>.</p>

</div>
</div>

### Pubnames {#af451a60a6e536b02744ac5f7adf362af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;AccelInfo&gt; llvm::dwarf_linker::classic::CompileUnit::Pubnames</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Accelerator entries for the unit, both for the pub* sections and the apple* ones.</p>

<p>Definition at line 315 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>.</p>

</div>
</div>

### Pubtypes {#a48027f257ecad467c731534cd8a26012}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;AccelInfo&gt; llvm::dwarf_linker::classic::CompileUnit::Pubtypes</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 316 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>.</p>

</div>
</div>

### RangeAttributes {#a2ad61ecb1bc911b570c60d8d9da5e697}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RngListAttributesTy llvm::dwarf_linker::classic::CompileUnit::RangeAttributes</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>'rnglist'(DW_AT_ranges, DW_AT_start_scope) attributes to patch after we have gathered all the unit's function addresses.</p>

<p>Definition at line 301 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>.</p>

</div>
</div>

### UnitRangeAttribute {#af0bfad562c2b8054154266df495436b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;PatchLocation&gt; llvm::dwarf_linker::classic::CompileUnit::UnitRangeAttribute</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 302 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### ClangModuleName {#a6a097655dbeffa4d6d1379252eeedcb3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::dwarf_linker::classic::CompileUnit::ClangModuleName</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If this is a Clang module, this holds the module's name.</p>

<p>Definition at line 331 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>.</p>

</div>
</div>

### ForwardDIEReferences {#a01c9125908541f31c2c5e03b38806eb7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt; std::tuple&lt;DIE *, const CompileUnit *, DeclContext *, PatchLocation&gt; &gt; llvm::dwarf_linker::classic::CompileUnit::ForwardDIEReferences</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A list of attributes to fixup with the absolute offset of a <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> in the debug_info section.</p>


<p>The offsets for the attributes in this array couldn't be set while cloning because for cross-cu forward references the target <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a>'s offset isn't known you emit the reference attribute.</p>


<p>Definition at line 288 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>.</p>

</div>
</div>

### HasODR {#ada6c3ca189bd0807becb22b1cf2c7ea7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::dwarf_linker::classic::CompileUnit::HasODR</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Is this unit subject to the ODR rule?</p>

<p>Definition at line 322 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>.</p>

</div>
</div>

### HighPc {#afc4b816a791637771936538cd5b8a0c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::dwarf_linker::classic::CompileUnit::HighPc = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 278 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>.</p>

</div>
</div>

### ID {#ac38377abb13013661211e1225c8d9faf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::dwarf_linker::classic::CompileUnit::ID</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 269 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>.</p>

</div>
</div>

### Info {#acfb6202cad0699b06da89958ee548ded}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;DIEInfo&gt; llvm::dwarf_linker::classic::CompileUnit::Info</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> info indexed by <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> index.</p>

<p>Definition at line 270 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>.</p>

</div>
</div>

### LabelBegin {#a35b3ffdff4255aaa11e45a18f9381aa6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSymbol* llvm::dwarf_linker::classic::CompileUnit::LabelBegin = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 272 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>.</p>

</div>
</div>

### Labels {#aadf6f9b5618feac3e9384ae082280b06}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallDenseMap&lt;uint64_t, uint64_t, 1&gt; llvm::dwarf_linker::classic::CompileUnit::Labels</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The DW_AT_low_pc of each DW_TAG_label.</p>

<p>Definition at line 296 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>.</p>

</div>
</div>

### Language {#af72dc342d67a1ff6f1d3940523d3d494}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint16_t llvm::dwarf_linker::classic::CompileUnit::Language = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The DW_AT_language of this unit.</p>

<p>Definition at line 325 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>.</p>

</div>
</div>

### LocationAttributes {#ab1fc8befa43418a3677dbbf37718eb74}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LocListAttributesTy llvm::dwarf_linker::classic::CompileUnit::LocationAttributes</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Location attributes that need to be transferred from the original debug_loc section to the linked one.</p>


<p>They are stored along with the PC offset that is to be applied to their function's address or to be applied to address operands of location expression.</p>


<p>Definition at line 310 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>.</p>

</div>
</div>

### LowPc {#a5ddf9882d9726798dcdfe8db6e1fd41c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;uint64_t&gt; llvm::dwarf_linker::classic::CompileUnit::LowPc</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 277 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>.</p>

</div>
</div>

### NewUnit {#a932f938a67153098c478c8e049043648}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;BasicDIEUnit&gt; llvm::dwarf_linker::classic::CompileUnit::NewUnit</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 271 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>.</p>

</div>
</div>

### NextUnitOffset {#a93cf5cf983ae654e6940dcb530214521}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::dwarf_linker::classic::CompileUnit::NextUnitOffset</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 275 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>.</p>

</div>
</div>

### OrigUnit {#a6c0e7890f4a13ffc2cbbadf3b3b1934d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DWARFUnit&amp; llvm::dwarf_linker::classic::CompileUnit::OrigUnit</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 268 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>.</p>

</div>
</div>

### Ranges {#a347c5be17f8237920857f8007a864d79}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RangesTy llvm::dwarf_linker::classic::CompileUnit::Ranges</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The ranges in that map are the PC ranges for functions in this unit, associated with the PC offset to apply to the addresses to get the linked address.</p>

<p>Definition at line 293 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>.</p>

</div>
</div>

### StartOffset {#aa1c990fcbc67828c631f0451d868b3f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::dwarf_linker::classic::CompileUnit::StartOffset</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 274 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>.</p>

</div>
</div>

### SysRoot {#a22f0af8fcb6c84c7d55b9fb42f519881}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::dwarf_linker::classic::CompileUnit::SysRoot</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The DW_AT_LLVM_sysroot of this unit.</p>

<p>Definition at line 328 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/classic/dwarflinkercompileunit-cpp">DWARFLinkerCompileUnit.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>

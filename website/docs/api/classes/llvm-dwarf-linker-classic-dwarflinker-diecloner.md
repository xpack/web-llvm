---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/dwarf-linker/classic/dwarflinker/diecloner
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `DIECloner` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::dwarf_linker::classic::DWARFLinker::DIECloner { ... }
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acbaef2dea0363393cf7fc9d4e7fd1239">ExpressionHandlerRef</a> = <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; void( <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; uint8_t &gt; &amp;, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; uint8_t &gt; &amp;, int64_t AddrRelocAdjustment)&gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f781005586a07ce6d9690f6444047f2">AttributeSpec</a> = <a href="/web-llvm/docs/api/structs/llvm/dwarfabbreviationdeclaration/attributespec">DWARFAbbreviationDeclaration::AttributeSpec</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb99ef0f759452bf4095a1a8601b0143">DIECloner</a> (DWARFLinker &amp;Linker, DwarfEmitter *Emitter, DWARFFile &amp;ObjFile, BumpPtrAllocator &amp;DIEAlloc, std::vector&lt; std::unique_ptr&lt; CompileUnit &gt; &gt; &amp;CompileUnits, bool Update, OffsetsStringPool &amp;DebugStrPool, OffsetsStringPool &amp;DebugLineStrPool, DebugDieValuePool &amp;StringOffsetPool)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1d20d4bda50d8c58ac28f4c61634aa6e">cloneDIE</a> (const DWARFDie &amp;InputDIE, const DWARFFile &amp;File, CompileUnit &amp;U, int64_t PCOffset, uint32_t OutOffset, unsigned Flags, bool IsLittleEndian, DIE *Die=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Recursively clone <span class="doxyComputerOutput">InputDIE</span> into an tree of <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> objects where useless (as decided by lookForDIEsToKeep()) bits have been stripped out and addresses have been rewritten according to the address map. <a href="#a1d20d4bda50d8c58ac28f4c61634aa6e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab906c3b536c8af593e74cd3b37f3d1fd">cloneAllCompileUnits</a> (DWARFContext &amp;DwarfContext, const DWARFFile &amp;File, bool IsLittleEndian)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct the output <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> tree by cloning the DIEs we chose to keep above. <a href="#ab906c3b536c8af593e74cd3b37f3d1fd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af05287ad0951d6fd95c05e69b23089bd">emitDebugAddrSection</a> (CompileUnit &amp;Unit, const uint16_t DwarfVersion) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit the .debug_addr section for the <span class="doxyComputerOutput">Unit</span>. <a href="#af05287ad0951d6fd95c05e69b23089bd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a16605f2c5b585ffed53d6a3c4f269764">generateUnitLocations</a> (CompileUnit &amp;Unit, const DWARFFile &amp;File, ExpressionHandlerRef ExprHandler)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute and emit debug locations (.debug_loc, .debug_loclists) for <span class="doxyComputerOutput">Unit</span>, patch the attributes referencing it. <a href="#a16605f2c5b585ffed53d6a3c4f269764">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab52cc2061200d94def1cdee0a6acf14c">cloneAttribute</a> (DIE &amp;Die, const DWARFDie &amp;InputDIE, const DWARFFile &amp;File, CompileUnit &amp;U, const DWARFFormValue &amp;Val, const AttributeSpec AttrSpec, unsigned AttrSize, AttributesInfo &amp;AttrInfo, bool IsLittleEndian)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper for cloneDIE. <a href="#ab52cc2061200d94def1cdee0a6acf14c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc5959c671f569784f9ca6476432a3e9">cloneStringAttribute</a> (DIE &amp;Die, AttributeSpec AttrSpec, const DWARFFormValue &amp;Val, const DWARFUnit &amp;U, AttributesInfo &amp;Info)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Clone a string attribute described by <span class="doxyComputerOutput">AttrSpec</span> and add it to <span class="doxyComputerOutput">Die</span>. <a href="#abc5959c671f569784f9ca6476432a3e9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8361dcb692063e31890c47253dd110a7">cloneDieReferenceAttribute</a> (DIE &amp;Die, const DWARFDie &amp;InputDIE, AttributeSpec AttrSpec, unsigned AttrSize, const DWARFFormValue &amp;Val, const DWARFFile &amp;File, CompileUnit &amp;Unit)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Clone an attribute referencing another <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> and add it to <span class="doxyComputerOutput">Die</span>. <a href="#a8361dcb692063e31890c47253dd110a7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a312879f2f5bfbf095c463e2919b97b10">cloneExpression</a> (DataExtractor &amp;Data, DWARFExpression Expression, const DWARFFile &amp;File, CompileUnit &amp;Unit, SmallVectorImpl&lt; uint8_t &gt; &amp;OutputBuffer, int64_t AddrRelocAdjustment, bool IsLittleEndian)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Clone a DWARF expression that may be referencing another <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a>. <a href="#a312879f2f5bfbf095c463e2919b97b10">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a632464c8d3ad5ccff1a0e8bbc986b458">cloneBlockAttribute</a> (DIE &amp;Die, const DWARFDie &amp;InputDIE, const DWARFFile &amp;File, CompileUnit &amp;Unit, AttributeSpec AttrSpec, const DWARFFormValue &amp;Val, bool IsLittleEndian)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Clone an attribute referencing another <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> and add it to <span class="doxyComputerOutput">Die</span>. <a href="#a632464c8d3ad5ccff1a0e8bbc986b458">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a49a527ae8fc5384122641e0ef392d1f3">cloneAddressAttribute</a> (DIE &amp;Die, const DWARFDie &amp;InputDIE, AttributeSpec AttrSpec, unsigned AttrSize, const DWARFFormValue &amp;Val, const CompileUnit &amp;Unit, AttributesInfo &amp;Info)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Clone an attribute referencing another <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> and add it to <span class="doxyComputerOutput">Die</span>. <a href="#a49a527ae8fc5384122641e0ef392d1f3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aae4f4263011a8b92e317019aac0e6029">cloneScalarAttribute</a> (DIE &amp;Die, const DWARFDie &amp;InputDIE, const DWARFFile &amp;File, CompileUnit &amp;U, AttributeSpec AttrSpec, const DWARFFormValue &amp;Val, unsigned AttrSize, AttributesInfo &amp;Info)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Clone a scalar attribute and add it to <span class="doxyComputerOutput">Die</span>. <a href="#aae4f4263011a8b92e317019aac0e6029">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a7782d11497cd8c1dfd9347b2f37bc7">getDIENames</a> (const DWARFDie &amp;Die, AttributesInfo &amp;Info, OffsetsStringPool &amp;StringPool, bool StripTemplate=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the potential name and mangled name for the entity described by <span class="doxyComputerOutput">Die</span> and store them in \Info if they are not already there. <a href="#a5a7782d11497cd8c1dfd9347b2f37bc7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac51f161687735cbba0d38e8420042a14">hashFullyQualifiedName</a> (DWARFDie DIE, CompileUnit &amp;U, const DWARFFile &amp;File, int RecurseDepth=0)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a91a862f31a63198677b8776cf1d313ff">addObjCAccelerator</a> (CompileUnit &amp;Unit, const DIE *Die, DwarfStringPoolEntryRef Name, OffsetsStringPool &amp;StringPool, bool SkipPubSection)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper for cloneDIE. <a href="#a91a862f31a63198677b8776cf1d313ff">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a787ac41ddd4ec8002d55e71016d4797a">rememberUnitForMacroOffset</a> (CompileUnit &amp;Unit)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab2be61e5247ddb03a930133003f105bb">generateLineTableForUnit</a> (CompileUnit &amp;Unit)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Clone and emit the line table for the specified <span class="doxyComputerOutput">Unit</span>. <a href="#ab2be61e5247ddb03a930133003f105bb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/classic/dwarflinker">DWARFLinker</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d4b4b241e1a8326c430926b7da9e760">Linker</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/classic/dwarfemitter">DwarfEmitter</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a806fefaf51c9ce341b37587346242610">Emitter</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/dwarffile">DWARFFile</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#add1cac5e1b7f360c727f263cdf680df0">ObjFile</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#aca9ad9fe13b3bf966c4c7dd96cec79df">OffsetsStringPool</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a66960fb1ca5bda23e214334d464e11dd">DebugStrPool</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#aca9ad9fe13b3bf966c4c7dd96cec79df">OffsetsStringPool</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7acd3c4eac1c096244b267ed0ef98dfd">DebugLineStrPool</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/classic/#a1ea4442463c620b2bef27de747ab16d7">DebugDieValuePool</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aad6ec343cf73a2c5ddf983531ed0d2a7">StringOffsetPool</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/classic/#a1ea4442463c620b2bef27de747ab16d7">DebugDieValuePool</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad4471aa06d644aa1a38ac79393a51d9a">AddrPool</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a8e612822d4ba7bb36c9c79582a567108">BumpPtrAllocator</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade0caf7c5669d5d25b2ab5a5c4808653">DIEAlloc</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Allocator used for all the <a href="/web-llvm/docs/api/classes/llvm/dievalue">DIEValue</a> objects. <a href="#ade0caf7c5669d5d25b2ab5a5c4808653">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/classic/compileunit">CompileUnit</a> &gt; &gt; &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a03579385e5406d03030a74a07b7ea515">CompileUnits</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/classic/#a883bd25ef016f5881dd3f8573823f0b0">Offset2UnitMap</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae1e74075d5d19a2c488474691fa1e6dd">UnitMacroMap</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Keeps mapping from offset of the macro table to corresponding compile unit. <a href="#ae1e74075d5d19a2c488474691fa1e6dd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67050003fff793fceb39e8bd1c0a6d8a">Update</a></td>
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


<p>Definition at line 543 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinker-h">DWARFLinker.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### ExpressionHandlerRef {#acbaef2dea0363393cf7fc9d4e7fd1239}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::dwarf_linker::classic::DWARFLinker::DIECloner::ExpressionHandlerRef =  function_ref&lt;void(
        SmallVectorImpl&lt;uint8_t&gt; &amp;, SmallVectorImpl&lt;uint8_t&gt; &amp;,
        int64_t AddrRelocAdjustment)&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 600 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinker-h">DWARFLinker.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Typedefs

### AttributeSpec {#a3f781005586a07ce6d9690f6444047f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::dwarf_linker::classic::DWARFLinker::DIECloner::AttributeSpec =  DWARFAbbreviationDeclaration::AttributeSpec</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 610 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinker-h">DWARFLinker.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### DIECloner() {#afb99ef0f759452bf4095a1a8601b0143}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::dwarf_linker::classic::DWARFLinker::DIECloner::DIECloner (<a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/classic/dwarflinker">DWARFLinker</a> &amp; Linker, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/classic/dwarfemitter">DwarfEmitter</a> * Emitter, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/dwarffile">DWARFFile</a> &amp; ObjFile, <a href="/web-llvm/docs/api/namespaces/llvm/#a8e612822d4ba7bb36c9c79582a567108">BumpPtrAllocator</a> &amp; DIEAlloc, std::vector&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/classic/compileunit">CompileUnit</a> &gt; &gt; &amp; CompileUnits, bool Update, <a href="/web-llvm/docs/api/namespaces/llvm/#aca9ad9fe13b3bf966c4c7dd96cec79df">OffsetsStringPool</a> &amp; DebugStrPool, <a href="/web-llvm/docs/api/namespaces/llvm/#aca9ad9fe13b3bf966c4c7dd96cec79df">OffsetsStringPool</a> &amp; DebugLineStrPool, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/classic/#a1ea4442463c620b2bef27de747ab16d7">DebugDieValuePool</a> &amp; StringOffsetPool)</td>
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



<p>Definition at line 564 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinker-h">DWARFLinker.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### cloneAllCompileUnits() {#ab906c3b536c8af593e74cd3b37f3d1fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::DWARFLinker::DIECloner::cloneAllCompileUnits (<a href="/web-llvm/docs/api/classes/llvm/dwarfcontext">DWARFContext</a> &amp; DwarfContext, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/dwarffile">DWARFFile</a> &amp; File, bool IsLittleEndian)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Construct the output <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> tree by cloning the DIEs we chose to keep above.</p>


<p>If there are no valid relocs, then there's nothing to clone/emit.</p>


<p>Declaration at line 593 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinker-h">DWARFLinker.h</a>, definition at line 2608 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/classic/dwarflinker-cpp">DWARFLinker.cpp</a>.</p>

</div>
</div>

### cloneDIE() {#a1d20d4bda50d8c58ac28f4c61634aa6e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DIE * llvm::DWARFLinker::DIECloner::cloneDIE (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfdie">DWARFDie</a> &amp; InputDIE, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/dwarffile">DWARFFile</a> &amp; File, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/classic/compileunit">CompileUnit</a> &amp; U, int64_t PCOffset, uint32_t OutOffset, unsigned Flags, bool IsLittleEndian, <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> * Die=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Recursively clone <span class="doxyComputerOutput">InputDIE</span> into an tree of <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> objects where useless (as decided by lookForDIEsToKeep()) bits have been stripped out and addresses have been rewritten according to the address map.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">OutOffset</td>
<td class="doxyParamItemDescription"><p>is the offset the cloned <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> in the output compile unit.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">PCOffset</td>
<td class="doxyParamItemDescription"><p>(while cloning a function scope) is the offset applied to the entry point of the function to get the linked address.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Die</td>
<td class="doxyParamItemDescription"><p>the output <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> to use, pass NULL to create one.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>the root of the cloned tree or null if nothing was selected.</p></dd>
</dl>


<p>Declaration at line 586 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinker-h">DWARFLinker.h</a>, definition at line 1685 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/classic/dwarflinker-cpp">DWARFLinker.cpp</a>.</p>

</div>
</div>

### emitDebugAddrSection() {#af05287ad0951d6fd95c05e69b23089bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DWARFLinker::DIECloner::emitDebugAddrSection (<a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/classic/compileunit">CompileUnit</a> &amp; Unit, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint16_t DwarfVersion)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit the .debug_addr section for the <span class="doxyComputerOutput">Unit</span>.</p>

<p>Declaration at line 597 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinker-h">DWARFLinker.h</a>, definition at line 2064 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/classic/dwarflinker-cpp">DWARFLinker.cpp</a>.</p>

</div>
</div>

### generateUnitLocations() {#a16605f2c5b585ffed53d6a3c4f269764}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DWARFLinker::DIECloner::generateUnitLocations (<a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/classic/compileunit">CompileUnit</a> &amp; Unit, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/dwarffile">DWARFFile</a> &amp; File, <a href="/web-llvm/docs/api/classes/llvm/function-ref">ExpressionHandlerRef</a> ExprHandler)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Compute and emit debug locations (.debug_loc, .debug_loclists) for <span class="doxyComputerOutput">Unit</span>, patch the attributes referencing it.</p>

<p>Declaration at line 606 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinker-h">DWARFLinker.h</a>, definition at line 1999 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/classic/dwarflinker-cpp">DWARFLinker.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### addObjCAccelerator() {#a91a862f31a63198677b8776cf1d313ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DWARFLinker::DIECloner::addObjCAccelerator (<a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/classic/compileunit">CompileUnit</a> &amp; Unit, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> * Die, <a href="/web-llvm/docs/api/classes/llvm/dwarfstringpoolentryref">DwarfStringPoolEntryRef</a> Name, <a href="/web-llvm/docs/api/namespaces/llvm/#aca9ad9fe13b3bf966c4c7dd96cec79df">OffsetsStringPool</a> &amp; StringPool, bool SkipPubSection)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Helper for cloneDIE.</p>

<p>Declaration at line 711 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinker-h">DWARFLinker.h</a>, definition at line 1629 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/classic/dwarflinker-cpp">DWARFLinker.cpp</a>.</p>

</div>
</div>

### cloneAddressAttribute() {#a49a527ae8fc5384122641e0ef392d1f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::DWARFLinker::DIECloner::cloneAddressAttribute (<a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> &amp; Die, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfdie">DWARFDie</a> &amp; InputDIE, <a href="/web-llvm/docs/api/structs/llvm/dwarfabbreviationdeclaration/attributespec">AttributeSpec</a> AttrSpec, unsigned AttrSize, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfformvalue">DWARFFormValue</a> &amp; Val, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/classic/compileunit">CompileUnit</a> &amp; Unit, AttributesInfo &amp; Info)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Clone an attribute referencing another <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> and add it to <span class="doxyComputerOutput">Die</span>.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>the size of the new attribute.</p></dd>
</dl>


<p>Declaration at line 685 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinker-h">DWARFLinker.h</a>, definition at line 1344 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/classic/dwarflinker-cpp">DWARFLinker.cpp</a>.</p>

</div>
</div>

### cloneAttribute() {#ab52cc2061200d94def1cdee0a6acf14c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::DWARFLinker::DIECloner::cloneAttribute (<a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> &amp; Die, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfdie">DWARFDie</a> &amp; InputDIE, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/dwarffile">DWARFFile</a> &amp; File, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/classic/compileunit">CompileUnit</a> &amp; Unit, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfformvalue">DWARFFormValue</a> &amp; Val, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/dwarfabbreviationdeclaration/attributespec">AttributeSpec</a> AttrSpec, unsigned AttrSize, AttributesInfo &amp; Info, bool IsLittleEndian)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Helper for cloneDIE.</p>


<p>Clone <span class="doxyComputerOutput">InputDIE's</span> attribute described by <span class="doxyComputerOutput">AttrSpec</span> with value <span class="doxyComputerOutput">Val</span>, and add it to <span class="doxyComputerOutput">Die</span>.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>the size of the cloned attribute.</p></dd>
</dl>


<p>Declaration at line 644 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinker-h">DWARFLinker.h</a>, definition at line 1567 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/classic/dwarflinker-cpp">DWARFLinker.cpp</a>.</p>

</div>
</div>

### cloneBlockAttribute() {#a632464c8d3ad5ccff1a0e8bbc986b458}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::DWARFLinker::DIECloner::cloneBlockAttribute (<a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> &amp; Die, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfdie">DWARFDie</a> &amp; InputDIE, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/dwarffile">DWARFFile</a> &amp; File, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/classic/compileunit">CompileUnit</a> &amp; Unit, <a href="/web-llvm/docs/api/structs/llvm/dwarfabbreviationdeclaration/attributespec">AttributeSpec</a> AttrSpec, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfformvalue">DWARFFormValue</a> &amp; Val, bool IsLittleEndian)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Clone an attribute referencing another <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> and add it to <span class="doxyComputerOutput">Die</span>.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>the size of the new attribute.</p></dd>
</dl>


<p>Declaration at line 676 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinker-h">DWARFLinker.h</a>, definition at line 1278 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/classic/dwarflinker-cpp">DWARFLinker.cpp</a>.</p>

</div>
</div>

### cloneDieReferenceAttribute() {#a8361dcb692063e31890c47253dd110a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::DWARFLinker::DIECloner::cloneDieReferenceAttribute (<a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> &amp; Die, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfdie">DWARFDie</a> &amp; InputDIE, <a href="/web-llvm/docs/api/structs/llvm/dwarfabbreviationdeclaration/attributespec">AttributeSpec</a> AttrSpec, unsigned AttrSize, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfformvalue">DWARFFormValue</a> &amp; Val, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/dwarffile">DWARFFile</a> &amp; File, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/classic/compileunit">CompileUnit</a> &amp; Unit)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Clone an attribute referencing another <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> and add it to <span class="doxyComputerOutput">Die</span>.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>the size of the new attribute.</p></dd>
</dl>


<p>Declaration at line 660 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinker-h">DWARFLinker.h</a>, definition at line 1079 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/classic/dwarflinker-cpp">DWARFLinker.cpp</a>.</p>

</div>
</div>

### cloneExpression() {#a312879f2f5bfbf095c463e2919b97b10}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DWARFLinker::DIECloner::cloneExpression (<a href="/web-llvm/docs/api/classes/llvm/dataextractor">DataExtractor</a> &amp; Data, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression">DWARFExpression</a> Expression, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/dwarffile">DWARFFile</a> &amp; File, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/classic/compileunit">CompileUnit</a> &amp; Unit, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; uint8_t &gt; &amp; OutputBuffer, int64_t AddrRelocAdjustment, bool IsLittleEndian)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Clone a DWARF expression that may be referencing another <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a>.</p>

<p>Declaration at line 668 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinker-h">DWARFLinker.h</a>, definition at line 1156 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/classic/dwarflinker-cpp">DWARFLinker.cpp</a>.</p>

</div>
</div>

### cloneScalarAttribute() {#aae4f4263011a8b92e317019aac0e6029}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::DWARFLinker::DIECloner::cloneScalarAttribute (<a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> &amp; Die, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfdie">DWARFDie</a> &amp; InputDIE, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/dwarffile">DWARFFile</a> &amp; File, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/classic/compileunit">CompileUnit</a> &amp; U, <a href="/web-llvm/docs/api/structs/llvm/dwarfabbreviationdeclaration/attributespec">AttributeSpec</a> AttrSpec, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfformvalue">DWARFFormValue</a> &amp; Val, unsigned AttrSize, AttributesInfo &amp; Info)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Clone a scalar attribute and add it to <span class="doxyComputerOutput">Die</span>.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>the size of the new attribute.</p></dd>
</dl>


<p>Declaration at line 693 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinker-h">DWARFLinker.h</a>, definition at line 1409 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/classic/dwarflinker-cpp">DWARFLinker.cpp</a>.</p>

</div>
</div>

### cloneStringAttribute() {#abc5959c671f569784f9ca6476432a3e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::DWARFLinker::DIECloner::cloneStringAttribute (<a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> &amp; Die, <a href="/web-llvm/docs/api/structs/llvm/dwarfabbreviationdeclaration/attributespec">AttributeSpec</a> AttrSpec, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfformvalue">DWARFFormValue</a> &amp; Val, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfunit">DWARFUnit</a> &amp; U, AttributesInfo &amp; Info)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Clone a string attribute described by <span class="doxyComputerOutput">AttrSpec</span> and add it to <span class="doxyComputerOutput">Die</span>.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>the size of the new attribute.</p></dd>
</dl>


<p>Declaration at line 653 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinker-h">DWARFLinker.h</a>, definition at line 1034 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/classic/dwarflinker-cpp">DWARFLinker.cpp</a>.</p>

</div>
</div>

### generateLineTableForUnit() {#ab2be61e5247ddb03a930133003f105bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DWARFLinker::DIECloner::generateLineTableForUnit (<a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/classic/compileunit">CompileUnit</a> &amp; Unit)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Clone and emit the line table for the specified <span class="doxyComputerOutput">Unit</span>.</p>


<p>Translate directories and file names if necessary. Relocate address ranges.</p>


<p>Declaration at line 720 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinker-h">DWARFLinker.h</a>, definition at line 2143 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/classic/dwarflinker-cpp">DWARFLinker.cpp</a>.</p>

</div>
</div>

### getDIENames() {#a5a7782d11497cd8c1dfd9347b2f37bc7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DWARFLinker::DIECloner::getDIENames (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfdie">DWARFDie</a> &amp; Die, AttributesInfo &amp; Info, <a href="/web-llvm/docs/api/namespaces/llvm/#aca9ad9fe13b3bf966c4c7dd96cec79df">OffsetsStringPool</a> &amp; StringPool, bool StripTemplate=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the potential name and mangled name for the entity described by <span class="doxyComputerOutput">Die</span> and store them in \Info if they are not already there.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>is a name was found.</p></dd>
</dl>


<p>Declaration at line 703 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinker-h">DWARFLinker.h</a>, definition at line 153 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/classic/dwarflinker-cpp">DWARFLinker.cpp</a>.</p>

</div>
</div>

### hashFullyQualifiedName() {#ac51f161687735cbba0d38e8420042a14}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::DWARFLinker::DIECloner::hashFullyQualifiedName (<a href="/web-llvm/docs/api/classes/llvm/dwarfdie">DWARFDie</a> DIE, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/classic/compileunit">CompileUnit</a> &amp; U, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/dwarffile">DWARFFile</a> &amp; File, int RecurseDepth=0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 706 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinker-h">DWARFLinker.h</a>, definition at line 2386 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/classic/dwarflinker-cpp">DWARFLinker.cpp</a>.</p>

</div>
</div>

### rememberUnitForMacroOffset() {#a787ac41ddd4ec8002d55e71016d4797a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DWARFLinker::DIECloner::rememberUnitForMacroOffset (<a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/classic/compileunit">CompileUnit</a> &amp; Unit)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 715 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinker-h">DWARFLinker.h</a>, definition at line 2126 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/classic/dwarflinker-cpp">DWARFLinker.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### AddrPool {#ad4471aa06d644aa1a38ac79393a51d9a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DebugDieValuePool llvm::dwarf_linker::classic::DWARFLinker::DIECloner::AddrPool</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 550 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinker-h">DWARFLinker.h</a>.</p>

</div>
</div>

### CompileUnits {#a03579385e5406d03030a74a07b7ea515}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;std::unique_ptr&lt;CompileUnit&gt; &gt;&amp; llvm::dwarf_linker::classic::DWARFLinker::DIECloner::CompileUnits</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 555 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinker-h">DWARFLinker.h</a>.</p>

</div>
</div>

### DebugLineStrPool {#a7acd3c4eac1c096244b267ed0ef98dfd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OffsetsStringPool&amp; llvm::dwarf_linker::classic::DWARFLinker::DIECloner::DebugLineStrPool</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 548 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinker-h">DWARFLinker.h</a>.</p>

</div>
</div>

### DebugStrPool {#a66960fb1ca5bda23e214334d464e11dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OffsetsStringPool&amp; llvm::dwarf_linker::classic::DWARFLinker::DIECloner::DebugStrPool</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 547 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinker-h">DWARFLinker.h</a>.</p>

</div>
</div>

### DIEAlloc {#ade0caf7c5669d5d25b2ab5a5c4808653}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BumpPtrAllocator&amp; llvm::dwarf_linker::classic::DWARFLinker::DIECloner::DIEAlloc</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Allocator used for all the <a href="/web-llvm/docs/api/classes/llvm/dievalue">DIEValue</a> objects.</p>

<p>Definition at line 553 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinker-h">DWARFLinker.h</a>.</p>

</div>
</div>

### Emitter {#a806fefaf51c9ce341b37587346242610}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DwarfEmitter* llvm::dwarf_linker::classic::DWARFLinker::DIECloner::Emitter</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 545 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinker-h">DWARFLinker.h</a>.</p>

</div>
</div>

### Linker {#a5d4b4b241e1a8326c430926b7da9e760}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DWARFLinker&amp; llvm::dwarf_linker::classic::DWARFLinker::DIECloner::Linker</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 544 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinker-h">DWARFLinker.h</a>.</p>

</div>
</div>

### ObjFile {#add1cac5e1b7f360c727f263cdf680df0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DWARFFile&amp; llvm::dwarf_linker::classic::DWARFLinker::DIECloner::ObjFile</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 546 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinker-h">DWARFLinker.h</a>.</p>

</div>
</div>

### StringOffsetPool {#aad6ec343cf73a2c5ddf983531ed0d2a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DebugDieValuePool&amp; llvm::dwarf_linker::classic::DWARFLinker::DIECloner::StringOffsetPool</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 549 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinker-h">DWARFLinker.h</a>.</p>

</div>
</div>

### UnitMacroMap {#ae1e74075d5d19a2c488474691fa1e6dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Offset2UnitMap llvm::dwarf_linker::classic::DWARFLinker::DIECloner::UnitMacroMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Keeps mapping from offset of the macro table to corresponding compile unit.</p>

<p>Definition at line 559 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinker-h">DWARFLinker.h</a>.</p>

</div>
</div>

### Update {#a67050003fff793fceb39e8bd1c0a6d8a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::dwarf_linker::classic::DWARFLinker::DIECloner::Update</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 561 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinker-h">DWARFLinker.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinker-h">DWARFLinker.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/classic/dwarflinker-cpp">DWARFLinker.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>

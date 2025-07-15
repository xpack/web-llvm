---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-miparser-cpp-/miparser
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `MIParser` Class Reference



## Declaration

<div class="doxyDeclaration">
class anonymous{MIParser.cpp}::MIParser { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a93d095d296c6ba07c739858dd35bfba4">MIParser</a> (PerFunctionMIParsingState &amp;PFS, SMDiagnostic &amp;Error, StringRef Source)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd6806455d95827bd992f0254608a412">MIParser</a> (PerFunctionMIParsingState &amp;PFS, SMDiagnostic &amp;Error, StringRef Source, SMRange SourceRange)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adbe0edbdba34278d011549a9e7c3d16e">lex</a> (unsigned SkipChar=0)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><span class="doxyComputerOutput">SkipChar</span> gives the number of characters to skip before looking for the next token. <a href="#adbe0edbdba34278d011549a9e7c3d16e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3dc4a2fe21b3ba008ab4f2b3d937b7b6">error</a> (const Twine &amp;Msg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Report an error at the current location with the given message. <a href="#a3dc4a2fe21b3ba008ab4f2b3d937b7b6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7d46d39efe0be42a72faf3e6db59de3f">error</a> (StringRef::iterator Loc, const Twine &amp;Msg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Report an error at the given location with the given message. <a href="#a7d46d39efe0be42a72faf3e6db59de3f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a043bc88be0f1b6eac408827079cfcdf9">parseBasicBlockDefinitions</a> (DenseMap&lt; unsigned, MachineBasicBlock * &gt; &amp;MBBSlots)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3904021432d1d4cf1620b9c09506e612">parseBasicBlocks</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9d7f3f2b0dc486075d4d462b7d744174">parse</a> (MachineInstr *&amp;MI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b6fb16ad1a073527ca219f25f242b9d">parseStandaloneMBB</a> (MachineBasicBlock *&amp;MBB)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afbc0c7f10ce30d72b70bd6982596e10b">parseStandaloneNamedRegister</a> (Register &amp;Reg)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab9db1ce7c4830ea5a0c54b0d843b5363">parseStandaloneVirtualRegister</a> (VRegInfo *&amp;Info)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0e113b6be43fae44b91eaac633118ba8">parseStandaloneRegister</a> (Register &amp;Reg)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af08d4f3585dbd246421362d8e6460e4a">parseStandaloneStackObject</a> (int &amp;FI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad9870bb0f0c1501dfa004566dbd5194b">parseStandaloneMDNode</a> (MDNode *&amp;Node)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af71425aaaccfd0af24609329584e5937">parseMachineMetadata</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a95e6736c0c4d939cc02161cd2db1644a">parseMDTuple</a> (MDNode *&amp;MD, bool IsDistinct)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae1c0498b0c1e685f7decf651532fc0d9">parseMDNodeVector</a> (SmallVectorImpl&lt; Metadata * &gt; &amp;Elts)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a83428d68b950a2dd6afc4c3292a82f49">parseMetadata</a> (Metadata *&amp;MD)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aee1834e01cdaec2445802850ce7e92b4">parseBasicBlockDefinition</a> (DenseMap&lt; unsigned, MachineBasicBlock * &gt; &amp;MBBSlots)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a28645da3fb06003fe7d32756e5ff929b">parseBasicBlock</a> (MachineBasicBlock &amp;MBB, MachineBasicBlock *&amp;AddFalthroughFrom)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade810268bd683de9734a8fc78cc09266">parseBasicBlockLiveins</a> (MachineBasicBlock &amp;MBB)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ace3ad3f99a9b90046e398bc0c09d372b">parseBasicBlockSuccessors</a> (MachineBasicBlock &amp;MBB)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e4a55a09d735c80c50bbb0bc0f93158">parseNamedRegister</a> (Register &amp;Reg)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a408291205fdd1fc5034490d72966c6ab">parseVirtualRegister</a> (VRegInfo *&amp;Info)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a451417fceac11225426e2b816a7775e8">parseNamedVirtualRegister</a> (VRegInfo *&amp;Info)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af24785732d415fd376c19df162d3d1aa">parseRegister</a> (Register &amp;Reg, VRegInfo *&amp;VRegInfo)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a04eaad27a8fb5a2f35432c4a09fa2221">parseRegisterFlag</a> (unsigned &amp;Flags)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e4e4f98e1264c57604c033122d6fceb">parseRegisterClassOrBank</a> (VRegInfo &amp;RegInfo)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a68d5b2d8a31ebf3554d265357f1baf28">parseSubRegisterIndex</a> (unsigned &amp;SubReg)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a9e6ec38e90a9bb7a0ee15119e1e709">parseRegisterTiedDefIndex</a> (unsigned &amp;TiedDefIdx)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad4d22d791beba2d17644bc14544e3877">parseRegisterOperand</a> (MachineOperand &amp;Dest, std::optional&lt; unsigned &gt; &amp;TiedDefIdx, bool IsDef=false)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7d7396e09a5fcf968a2536b1375c356f">parseImmediateOperand</a> (MachineOperand &amp;Dest)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a08b018143e68b6cc36ab362d8b3b2626">parseIRConstant</a> (StringRef::iterator Loc, StringRef StringValue, const Constant *&amp;C)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a77465bdd671f1ee4c84511ad14036857">parseIRConstant</a> (StringRef::iterator Loc, const Constant *&amp;C)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1119c30ad17d23efa29bf5593774867d">parseLowLevelType</a> (StringRef::iterator Loc, LLT &amp;Ty)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a96f48f9a5690ef01b9d2574472e1f7e2">parseTypedImmediateOperand</a> (MachineOperand &amp;Dest)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4175071c6efe1557747e226a1e8fe2e2">parseFPImmediateOperand</a> (MachineOperand &amp;Dest)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4324e2adebdc2aaca8ead3ed32de1667">parseMBBReference</a> (MachineBasicBlock *&amp;MBB)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa5f0e43ec22230708870040ca6a9bc2e">parseMBBOperand</a> (MachineOperand &amp;Dest)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a453f3120ed4a899975ffac8bdda7417a">parseStackFrameIndex</a> (int &amp;FI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f18959fe1cc20cb62b5a169b61c0bb8">parseStackObjectOperand</a> (MachineOperand &amp;Dest)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a978abc1545ddae1a0e2cae4c02ab84b4">parseFixedStackFrameIndex</a> (int &amp;FI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a509beb4628e05fbfe24e7bc562aa6d48">parseFixedStackObjectOperand</a> (MachineOperand &amp;Dest)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5ce71fb49004a1d688feb4434a27ab44">parseGlobalValue</a> (GlobalValue *&amp;GV)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a88ed2f870a01ae1fa7343375ab87dfb3">parseGlobalAddressOperand</a> (MachineOperand &amp;Dest)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa736beb031d297f0eade73ddf496a663">parseConstantPoolIndexOperand</a> (MachineOperand &amp;Dest)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c8d28ec07b076990dfad603aa041f9b">parseSubRegisterIndexOperand</a> (MachineOperand &amp;Dest)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0688b95ba758f0bdee953833ccbd7a4d">parseJumpTableIndexOperand</a> (MachineOperand &amp;Dest)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeab6958e2224c86557e4ae4a338bf07d">parseExternalSymbolOperand</a> (MachineOperand &amp;Dest)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7eba052b8ea2a231281c651c53ef10b5">parseMCSymbolOperand</a> (MachineOperand &amp;Dest)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a47550df64460e1d79194f04e687fd4bc">parseMDNode</a> (MDNode *&amp;Node)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ab2f664870f2d3c5f2036875672cf2a">parseDIExpression</a> (MDNode *&amp;Expr)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3ac7a622a7557191953d14a7961a79fa">parseDILocation</a> (MDNode *&amp;Expr)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0ba2f5ae9cb5a6e84640d02c50e52a09">parseMetadataOperand</a> (MachineOperand &amp;Dest)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af8e8e9f4122f068cfa33e5f17879c2ca">parseCFIOffset</a> (int &amp;Offset)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7954356a1d4fe56e90cf50b2820cd502">parseCFIRegister</a> (Register &amp;Reg)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a025beb578c2bc100c73a38c7d1b89a6d">parseCFIAddressSpace</a> (unsigned &amp;AddressSpace)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb68fcdc971343ff6082386d506d8cb8">parseCFIEscapeValues</a> (std::string &amp;Values)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac0b8e1a3e4961f36e5acd8259ccceeab">parseCFIOperand</a> (MachineOperand &amp;Dest)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9f34c58afe83b8b8dcc0299d74238a5a">parseIRBlock</a> (BasicBlock *&amp;BB, const Function &amp;F)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a77f5672641188aaed10066f78ebb24af">parseBlockAddressOperand</a> (MachineOperand &amp;Dest)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a02ce808485bec6d45ce163e0d50bb061">parseIntrinsicOperand</a> (MachineOperand &amp;Dest)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4590f4e05f484028f3b4bf3387955427">parsePredicateOperand</a> (MachineOperand &amp;Dest)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a70c970df35e9a1ebde9a6371fb8a6bc6">parseShuffleMaskOperand</a> (MachineOperand &amp;Dest)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6273fafa595d2e1f8940595b5dccc8dc">parseTargetIndexOperand</a> (MachineOperand &amp;Dest)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1c86a488cc8a95190bc351fac90405e2">parseDbgInstrRefOperand</a> (MachineOperand &amp;Dest)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a115cf2109c3a6f662603ef7879242c59">parseCustomRegisterMaskOperand</a> (MachineOperand &amp;Dest)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae35da4f6e23c51b04dc46d9fcfc7c066">parseLiveoutRegisterMaskOperand</a> (MachineOperand &amp;Dest)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af7b186f0f87ad315cbd814abed5dab72">parseMachineOperand</a> (const unsigned OpCode, const unsigned OpIdx, MachineOperand &amp;Dest, std::optional&lt; unsigned &gt; &amp;TiedDefIdx)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf35a52665d3f70d22acefe2846cb50f">parseMachineOperandAndTargetFlags</a> (const unsigned OpCode, const unsigned OpIdx, MachineOperand &amp;Dest, std::optional&lt; unsigned &gt; &amp;TiedDefIdx)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9aaa7797bd399f29fdd9f7c55e2d182a">parseOffset</a> (int64_t &amp;Offset)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1d3978999a978f56f13fb8aae7348436">parseIRBlockAddressTaken</a> (BasicBlock *&amp;BB)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4db9053414b75c0c90cb830a6b06b659">parseAlignment</a> (uint64_t &amp;Alignment)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abd8f29ecab2bd9275731d9762e4707b3">parseAddrspace</a> (unsigned &amp;Addrspace)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b4cb75e4b5f5a31d24d90dcebed12e3">parseSectionID</a> (std::optional&lt; MBBSectionID &gt; &amp;SID)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac3eddaf93bd102b2ee5c2d357f439000">parseBBID</a> (std::optional&lt; UniqueBBID &gt; &amp;BBID)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af740a2ed2a8eef5fe4c7c4fc710fd77b">parseCallFrameSize</a> (unsigned &amp;CallFrameSize)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a13fa87aa1554fb342fde9c3f9cac14b8">parseOperandsOffset</a> (MachineOperand &amp;Op)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4b9a684b49a12183c3ace195827aa01e">parseIRValue</a> (const Value *&amp;V)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adb56879a68087d3940588f0c5e124c4c">parseMemoryOperandFlag</a> (MachineMemOperand::Flags &amp;Flags)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a58471cf0d31837efb05a35712ce9ad7c">parseMemoryPseudoSourceValue</a> (const PseudoSourceValue *&amp;PSV)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0e477b282f9f9b58b7a5b2f9b0e4fdee">parseMachinePointerInfo</a> (MachinePointerInfo &amp;Dest)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a62edb7a01e25422fd05722f2dc31445c">parseOptionalScope</a> (LLVMContext &amp;Context, SyncScope::ID &amp;SSID)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7eb95d6aa8ae9f89008ea38203b6e894">parseOptionalAtomicOrdering</a> (AtomicOrdering &amp;Order)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaf6c3eb212e9e66ac2d36fdb7e0a51ed">parseMachineMemoryOperand</a> (MachineMemOperand *&amp;Dest)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2c772f7f4d284b2ad112741a2f451bf4">parsePreOrPostInstrSymbol</a> (MCSymbol *&amp;Symbol)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9d2304dd85a4ed00a421fad88a95e33d">parseHeapAllocMarker</a> (MDNode *&amp;Node)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a16226e28e8a3155a820ac00075ed1892">parsePCSections</a> (MDNode *&amp;Node)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af77884023f62584e3a1c2daad3d643c1">parseTargetImmMnemonic</a> (const unsigned OpCode, const unsigned OpIdx, MachineOperand &amp;Dest, const MIRFormatter &amp;MF)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a05a86ae27331f2e229826bd40cfecc9c">getUnsigned</a> (unsigned &amp;Result)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Convert the integer literal in the current token into an unsigned integer. <a href="#a05a86ae27331f2e229826bd40cfecc9c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad224457a99939f65fd9ad6f7ef129334">getUint64</a> (uint64_t &amp;Result)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Convert the integer literal in the current token into an uint64. <a href="#ad224457a99939f65fd9ad6f7ef129334">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a70415e948882e9534bf839c8b1925d96">getHexUint</a> (APInt &amp;Result)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Convert the hexadecimal literal in the current token into an unsigned <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> with a minimum bitwidth required to represent the value. <a href="#a70415e948882e9534bf839c8b1925d96">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a096f43c3f11baeac11d0cf21e019acac">expectAndConsume</a> (MIToken::TokenKind TokenKind)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If the current token is of the given kind, consume it and return false. <a href="#a096f43c3f11baeac11d0cf21e019acac">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1694d1784a89868a65e559ba8a0302a3">consumeIfPresent</a> (MIToken::TokenKind TokenKind)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If the current token is of the given kind, consume it and return true. <a href="#a1694d1784a89868a65e559ba8a0302a3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a213dfccee7f26ba6e7759232d60152b1">parseInstruction</a> (unsigned &amp;OpCode, unsigned &amp;Flags)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad314b3e97628d7a74f4929b1be954d97">assignRegisterTies</a> (MachineInstr &amp;MI, ArrayRef&lt; ParsedMachineOperand &gt; Operands)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab88117b3b0345f449d884dcd05afa468">verifyImplicitOperands</a> (ArrayRef&lt; ParsedMachineOperand &gt; Operands, const MCInstrDesc &amp;MCID)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7a91c16f361711bd97758304353c596b">getIRBlock</a> (unsigned Slot)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a560395feb66a406d77384c376b6f0ea9">getIRBlock</a> (unsigned Slot, const Function &amp;F)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3633e9190743c142820cc19cd5cc417c">getOrCreateMCSymbol</a> (StringRef Name)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get or create an <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> for a given name. <a href="#a3633e9190743c142820cc19cd5cc417c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a42774580ce9a9f5a1822293df0be87d3">parseStringConstant</a> (std::string &amp;Result)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseStringConstant ::= StringConstant <a href="#a42774580ce9a9f5a1822293df0be87d3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b35addf88e26efa03720773abd2113c">mapSMLoc</a> (StringRef::iterator Loc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Map the location in the MI string to the corresponding location specified in <span class="doxyComputerOutput">SourceRange</span>. <a href="#a8b35addf88e26efa03720773abd2113c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9dafd0d5ed8d166dc00b157f17b5b50b">MF</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smdiagnostic">SMDiagnostic</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adcb3d37670fef132f558c142643ac7fd">Error</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a51c76be2966fe21ad27b383cac3e9eee">Source</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a770e1934fde00c797055db0b03aa4fbb">CurrentSource</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smrange">SMRange</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a292a9d3b6c1d9eafdff3bb0bcf366363">SourceRange</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/mitoken">MIToken</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a650ccba2efd678b6d865edde765ee880">Token</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/perfunctionmiparsingstate">PerFunctionMIParsingState</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6d2ad090a11ab6fe2b7caf0b6993132e">PFS</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; unsigned, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeeab9f500caa3522d5936cc68fff9621">Slots2BasicBlocks</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Maps from slot numbers to function's unnamed basic blocks. <a href="#aeeab9f500caa3522d5936cc68fff9621">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 400 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp">MIParser.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### MIParser() {#a93d095d296c6ba07c739858dd35bfba4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MIParser::MIParser (<a href="/web-llvm/docs/api/structs/llvm/perfunctionmiparsingstate">PerFunctionMIParsingState</a> &amp; PFS, <a href="/web-llvm/docs/api/classes/llvm/smdiagnostic">SMDiagnostic</a> &amp; Error, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Source)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 411 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp">MIParser.cpp</a>.</p>

</div>
</div>

### MIParser() {#afd6806455d95827bd992f0254608a412}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MIParser::MIParser (<a href="/web-llvm/docs/api/structs/llvm/perfunctionmiparsingstate">PerFunctionMIParsingState</a> &amp; PFS, <a href="/web-llvm/docs/api/classes/llvm/smdiagnostic">SMDiagnostic</a> &amp; Error, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Source, <a href="/web-llvm/docs/api/classes/llvm/smrange">SMRange</a> SourceRange)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 413 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp">MIParser.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### error() {#a3dc4a2fe21b3ba008ab4f2b3d937b7b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MIParser::error (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Msg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Report an error at the current location with the given message.</p>


<p>This function always return true.</p>


<p>Definition at line 423 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp">MIParser.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/symbolrecordmapping-cpp/#a9cdf893c7d17e47fa1ed8bebf92a5da4">error</a>.</p>

</div>
</div>

### error() {#a7d46d39efe0be42a72faf3e6db59de3f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MIParser::error (<a href="/web-llvm/docs/api/classes/llvm/stringref/#a20d37563688a61a452fb26e317e37308">StringRef::iterator</a> Loc, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Msg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Report an error at the given location with the given message.</p>


<p>This function always return true.</p>


<p>Definition at line 428 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp">MIParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/sourcemgr/#a346262ff27e71aff626fe6548ef8a777adaf658d40b0b4eb15c0350864c87c2b8">llvm::SourceMgr::DK_Error</a>, <a href="/web-llvm/docs/api/classes/llvm/memorybuffer/#ae4604d3bedbb15e6c516f9357d3b773e">llvm::MemoryBuffer::getBufferEnd</a>, <a href="/web-llvm/docs/api/classes/llvm/memorybuffer/#a2037f11968aa30bfda0b4de9f335624d">llvm::MemoryBuffer::getBufferIdentifier</a>, <a href="/web-llvm/docs/api/classes/llvm/memorybuffer/#af1972b9a0324e0311ad641eac2de2b7f">llvm::MemoryBuffer::getBufferStart</a>, <a href="/web-llvm/docs/api/classes/llvm/smloc/#a16ebb09610e55f63cfc55f28e3a56ad5">llvm::SMLoc::getFromPointer</a>, <a href="/web-llvm/docs/api/classes/llvm/sourcemgr/#a208a36067279ac9669eb29f34ae9daed">llvm::SourceMgr::getMainFileID</a>, <a href="/web-llvm/docs/api/classes/llvm/sourcemgr/#a56740d2dab215f8642e6acf4ff49c62d">llvm::SourceMgr::getMemoryBuffer</a>, <a href="/web-llvm/docs/api/classes/llvm/sourcemgr/#acdf08ebc749ce91001ea768a16da0605">llvm::SourceMgr::GetMessage</a> and <a href="/web-llvm/docs/api/classes/llvm/twine/#a4c1c1093a7749409c70838678514cc7c">llvm::Twine::str</a>.</p>

</div>
</div>

### lex() {#adbe0edbdba34278d011549a9e7c3d16e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MIParser::lex (unsigned SkipChar=0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><span class="doxyComputerOutput">SkipChar</span> gives the number of characters to skip before looking for the next token.</p>

<p>Definition at line 418 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp">MIParser.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a2874020a85f1d17cb16881f9ff586d1f">llvm::lexMIToken</a>.</p>


<p>Referenced by <a href="#a9d7f3f2b0dc486075d4d462b7d744174">parse</a>, <a href="#abd8f29ecab2bd9275731d9762e4707b3">parseAddrspace</a>, <a href="#a4db9053414b75c0c90cb830a6b06b659">parseAlignment</a>, <a href="#a28645da3fb06003fe7d32756e5ff929b">parseBasicBlock</a>, <a href="#aee1834e01cdaec2445802850ce7e92b4">parseBasicBlockDefinition</a>, <a href="#a043bc88be0f1b6eac408827079cfcdf9">parseBasicBlockDefinitions</a>, <a href="#ade810268bd683de9734a8fc78cc09266">parseBasicBlockLiveins</a>, <a href="#a3904021432d1d4cf1620b9c09506e612">parseBasicBlocks</a>, <a href="#ace3ad3f99a9b90046e398bc0c09d372b">parseBasicBlockSuccessors</a>, <a href="#ac3eddaf93bd102b2ee5c2d357f439000">parseBBID</a>, <a href="#a77f5672641188aaed10066f78ebb24af">parseBlockAddressOperand</a>, <a href="#af740a2ed2a8eef5fe4c7c4fc710fd77b">parseCallFrameSize</a>, <a href="#a025beb578c2bc100c73a38c7d1b89a6d">parseCFIAddressSpace</a>, <a href="#afb68fcdc971343ff6082386d506d8cb8">parseCFIEscapeValues</a>, <a href="#af8e8e9f4122f068cfa33e5f17879c2ca">parseCFIOffset</a>, <a href="#ac0b8e1a3e4961f36e5acd8259ccceeab">parseCFIOperand</a>, <a href="#a7954356a1d4fe56e90cf50b2820cd502">parseCFIRegister</a>, <a href="#aa736beb031d297f0eade73ddf496a663">parseConstantPoolIndexOperand</a>, <a href="#a115cf2109c3a6f662603ef7879242c59">parseCustomRegisterMaskOperand</a>, <a href="#a1c86a488cc8a95190bc351fac90405e2">parseDbgInstrRefOperand</a>, <a href="#a8ab2f664870f2d3c5f2036875672cf2a">parseDIExpression</a>, <a href="#a3ac7a622a7557191953d14a7961a79fa">parseDILocation</a>, <a href="#aeab6958e2224c86557e4ae4a338bf07d">parseExternalSymbolOperand</a>, <a href="#a978abc1545ddae1a0e2cae4c02ab84b4">parseFixedStackFrameIndex</a>, <a href="#a4175071c6efe1557747e226a1e8fe2e2">parseFPImmediateOperand</a>, <a href="#a88ed2f870a01ae1fa7343375ab87dfb3">parseGlobalAddressOperand</a>, <a href="#a9d2304dd85a4ed00a421fad88a95e33d">parseHeapAllocMarker</a>, <a href="#a7d7396e09a5fcf968a2536b1375c356f">parseImmediateOperand</a>, <a href="#a02ce808485bec6d45ce163e0d50bb061">parseIntrinsicOperand</a>, <a href="#a1d3978999a978f56f13fb8aae7348436">parseIRBlockAddressTaken</a>, <a href="#a77465bdd671f1ee4c84511ad14036857">parseIRConstant</a>, <a href="#a0688b95ba758f0bdee953833ccbd7a4d">parseJumpTableIndexOperand</a>, <a href="#ae35da4f6e23c51b04dc46d9fcfc7c066">parseLiveoutRegisterMaskOperand</a>, <a href="#a1119c30ad17d23efa29bf5593774867d">parseLowLevelType</a>, <a href="#aaf6c3eb212e9e66ac2d36fdb7e0a51ed">parseMachineMemoryOperand</a>, <a href="#af71425aaaccfd0af24609329584e5937">parseMachineMetadata</a>, <a href="#af7b186f0f87ad315cbd814abed5dab72">parseMachineOperand</a>, <a href="#adf35a52665d3f70d22acefe2846cb50f">parseMachineOperandAndTargetFlags</a>, <a href="#a0e477b282f9f9b58b7a5b2f9b0e4fdee">parseMachinePointerInfo</a>, <a href="#aa5f0e43ec22230708870040ca6a9bc2e">parseMBBOperand</a>, <a href="#a7eba052b8ea2a231281c651c53ef10b5">parseMCSymbolOperand</a>, <a href="#a47550df64460e1d79194f04e687fd4bc">parseMDNode</a>, <a href="#ae1c0498b0c1e685f7decf651532fc0d9">parseMDNodeVector</a>, <a href="#adb56879a68087d3940588f0c5e124c4c">parseMemoryOperandFlag</a>, <a href="#a58471cf0d31837efb05a35712ce9ad7c">parseMemoryPseudoSourceValue</a>, <a href="#a83428d68b950a2dd6afc4c3292a82f49">parseMetadata</a>, <a href="#a9aaa7797bd399f29fdd9f7c55e2d182a">parseOffset</a>, <a href="#a7eb95d6aa8ae9f89008ea38203b6e894">parseOptionalAtomicOrdering</a>, <a href="#a62edb7a01e25422fd05722f2dc31445c">parseOptionalScope</a>, <a href="#a16226e28e8a3155a820ac00075ed1892">parsePCSections</a>, <a href="#a4590f4e05f484028f3b4bf3387955427">parsePredicateOperand</a>, <a href="#a2c772f7f4d284b2ad112741a2f451bf4">parsePreOrPostInstrSymbol</a>, <a href="#a6e4e4f98e1264c57604c033122d6fceb">parseRegisterClassOrBank</a>, <a href="#a04eaad27a8fb5a2f35432c4a09fa2221">parseRegisterFlag</a>, <a href="#ad4d22d791beba2d17644bc14544e3877">parseRegisterOperand</a>, <a href="#a4a9e6ec38e90a9bb7a0ee15119e1e709">parseRegisterTiedDefIndex</a>, <a href="#a5b4cb75e4b5f5a31d24d90dcebed12e3">parseSectionID</a>, <a href="#a70c970df35e9a1ebde9a6371fb8a6bc6">parseShuffleMaskOperand</a>, <a href="#a453f3120ed4a899975ffac8bdda7417a">parseStackFrameIndex</a>, <a href="#a8b6fb16ad1a073527ca219f25f242b9d">parseStandaloneMBB</a>, <a href="#ad9870bb0f0c1501dfa004566dbd5194b">parseStandaloneMDNode</a>, <a href="#afbc0c7f10ce30d72b70bd6982596e10b">parseStandaloneNamedRegister</a>, <a href="#a0e113b6be43fae44b91eaac633118ba8">parseStandaloneRegister</a>, <a href="#af08d4f3585dbd246421362d8e6460e4a">parseStandaloneStackObject</a>, <a href="#ab9db1ce7c4830ea5a0c54b0d843b5363">parseStandaloneVirtualRegister</a>, <a href="#a68d5b2d8a31ebf3554d265357f1baf28">parseSubRegisterIndex</a>, <a href="#a0c8d28ec07b076990dfad603aa041f9b">parseSubRegisterIndexOperand</a>, <a href="#af77884023f62584e3a1c2daad3d643c1">parseTargetImmMnemonic</a>, <a href="#a6273fafa595d2e1f8940595b5dccc8dc">parseTargetIndexOperand</a> and <a href="#a96f48f9a5690ef01b9d2574472e1f7e2">parseTypedImmediateOperand</a>.</p>

</div>
</div>

### parse() {#a9d7f3f2b0dc486075d4d462b7d744174}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MIParser::parse (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *&amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 433 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp">MIParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a73e49b39421c784a08abf178343da0bc">llvm::MIToken::coloncolon</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a190591b275f9c74a12e9cc66e386d86c">llvm::MIToken::comma</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ab09679b541a6ba1219b3602569847364">llvm::MachineOperand::CreateImm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a463a58e257d5f6fb2c39eb9a2474fc24ac2e06fc138163b7095fa483616a0a47a">llvm::dwarf_linker::DebugLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6ab3c838fbfa1a8d60a66b3fe4aa360af9">llvm::MIToken::equal</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/symbolrecordmapping-cpp/#a9cdf893c7d17e47fa1ed8bebf92a5da4">error</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6ae9b7e1e40ac9f787f763b636479f00d6">llvm::MIToken::exclaim</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6ac47c420adaca267e079109b3d4dca293">llvm::MIToken::IntegerLiteral</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a8a6dea4150203fad21673ccf124a968b">llvm::MIToken::kw_cfi_type</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6ae3b209d9029d0e9a79026e60f8328f23">llvm::MIToken::kw_debug_instr_number</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6afae5d39056b30c2d5219236ee0650abc">llvm::MIToken::kw_debug_location</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6afe193166e332234f73dabc8d161a364e">llvm::MIToken::kw_heap_alloc_marker</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6ae79b65c3955b6b96bd3e16a9691b0718">llvm::MIToken::kw_pcsections</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6aea446ae4c2ab038ada07483d17fa8fd3">llvm::MIToken::kw_post_instr_symbol</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a16baa8a695f87a8d642a0271f9c8bb4b">llvm::MIToken::kw_pre_instr_symbol</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a7ec17f6a52a8e82ff01425357cd53bb6">llvm::MIToken::lbrace</a>, <a href="#adbe0edbdba34278d011549a9e7c3d16e">lex</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6abc4fb36ac618caf2a11cb6c74f598d07">llvm::MIToken::md_dilocation</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirnamerpass-cpp/#a05e4be4ec3e2c3587dda0e376bb6822c">Operands</a>, <a href="#a3ac7a622a7557191953d14a7961a79fa">parseDILocation</a>, <a href="#a9d2304dd85a4ed00a421fad88a95e33d">parseHeapAllocMarker</a>, <a href="#aaf6c3eb212e9e66ac2d36fdb7e0a51ed">parseMachineMemoryOperand</a>, <a href="#adf35a52665d3f70d22acefe2846cb50f">parseMachineOperandAndTargetFlags</a>, <a href="#a47550df64460e1d79194f04e687fd4bc">parseMDNode</a>, <a href="#a16226e28e8a3155a820ac00075ed1892">parsePCSections</a>, <a href="#a2c772f7f4d284b2ad112741a2f451bf4">parsePreOrPostInstrSymbol</a>, <a href="#ad4d22d791beba2d17644bc14544e3877">parseRegisterOperand</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>.</p>


<p>Referenced by <a href="#a28645da3fb06003fe7d32756e5ff929b">parseBasicBlock</a>.</p>

</div>
</div>

### parseAddrspace() {#abd8f29ecab2bd9275731d9762e4707b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MIParser::parseAddrspace (unsigned &amp; Addrspace)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 511 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp">MIParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/symbolrecordmapping-cpp/#a9cdf893c7d17e47fa1ed8bebf92a5da4">error</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6ac47c420adaca267e079109b3d4dca293">llvm::MIToken::IntegerLiteral</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a0943c04acc16f5a20793de60d48cfc93">llvm::MIToken::kw_addrspace</a> and <a href="#adbe0edbdba34278d011549a9e7c3d16e">lex</a>.</p>


<p>Referenced by <a href="#aaf6c3eb212e9e66ac2d36fdb7e0a51ed">parseMachineMemoryOperand</a>.</p>

</div>
</div>

### parseAlignment() {#a4db9053414b75c0c90cb830a6b06b659}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MIParser::parseAlignment (uint64_t &amp; Alignment)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 510 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp">MIParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/symbolrecordmapping-cpp/#a9cdf893c7d17e47fa1ed8bebf92a5da4">error</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6ac47c420adaca267e079109b3d4dca293">llvm::MIToken::IntegerLiteral</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a434f6a0d80fb13e4326e848a6391f057">llvm::isPowerOf2_64</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a2b36847798e6a577ff1a459d436716cc">llvm::MIToken::kw_align</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a8fa817130e25e7d76dba39a1bd0962ee">llvm::MIToken::kw_basealign</a> and <a href="#adbe0edbdba34278d011549a9e7c3d16e">lex</a>.</p>


<p>Referenced by <a href="#aee1834e01cdaec2445802850ce7e92b4">parseBasicBlockDefinition</a> and <a href="#aaf6c3eb212e9e66ac2d36fdb7e0a51ed">parseMachineMemoryOperand</a>.</p>

</div>
</div>

### parseBasicBlock() {#a28645da3fb06003fe7d32756e5ff929b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MIParser::parseBasicBlock (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *&amp; AddFalthroughFrom)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 447 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp">MIParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#aafacf84de1cb994a92dc045f4aa1d518a9a9e5ef20669b2c9666b2689808b48ee">llvm::MachineInstr::BundledPred</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#aafacf84de1cb994a92dc045f4aa1d518ad00e31da3877ce738df8343edcff6ed8">llvm::MachineInstr::BundledSucc</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6ac56884d19c1537e43044a3078cac0004">llvm::MIToken::colon</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a9451d22efb0e7385c6b73ca7799b1d70">llvm::MIToken::Eof</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/symbolrecordmapping-cpp/#a9cdf893c7d17e47fa1ed8bebf92a5da4">error</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5247dc29909dbdf0e1e7b26aa0b3451d">llvm::guessSuccessors</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a5956125b492bac740985726d73b707c3">llvm::MIToken::kw_liveins</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6ac906e38f5901242459dd9fc47e3696f8">llvm::MIToken::kw_successors</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a7ec17f6a52a8e82ff01425357cd53bb6">llvm::MIToken::lbrace</a>, <a href="#adbe0edbdba34278d011549a9e7c3d16e">lex</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6aa19f9b1b5cf9928ce12e0dab92099c10">llvm::MIToken::lparen</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a7e5c1b1fdcdabc0c2d3ed5941308db6c">llvm::MIToken::MachineBasicBlockLabel</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a38401c9f9d25b14c3ca4a36214b5f290">llvm::MIToken::Newline</a>, <a href="#a9d7f3f2b0dc486075d4d462b7d744174">parse</a>, <a href="#ade810268bd683de9734a8fc78cc09266">parseBasicBlockLiveins</a>, <a href="#ace3ad3f99a9b90046e398bc0c09d372b">parseBasicBlockSuccessors</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a1b4d75865bc6f7723d3f2cae13c8b651">llvm::MIToken::rbrace</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6af002c0577ea092d33ec2e5268ff4201e">llvm::MIToken::rparen</a> and <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#aba86b0738c2ab2a52688b846c45bfe59">llvm::MachineInstr::setFlag</a>.</p>


<p>Referenced by <a href="#a3904021432d1d4cf1620b9c09506e612">parseBasicBlocks</a>.</p>

</div>
</div>

### parseBasicBlockDefinition() {#aee1834e01cdaec2445802850ce7e92b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MIParser::parseBasicBlockDefinition (<a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; unsigned, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * &gt; &amp; MBBSlots)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 446 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp">MIParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6ac56884d19c1537e43044a3078cac0004">llvm::MIToken::colon</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a190591b275f9c74a12e9cc66e386d86c">llvm::MIToken::comma</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5f6182886dc2f96c204299e92c1565d5">llvm::dyn_cast_or_null</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/symbolrecordmapping-cpp/#a9cdf893c7d17e47fa1ed8bebf92a5da4">error</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#adb33f3ede2f5bfc9b3ee658aaf648492">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::insert</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6ab80383451bf22665b8b1e7deec8dba7e">llvm::MIToken::IRBlock</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a2b36847798e6a577ff1a459d436716cc">llvm::MIToken::kw_align</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a36279270727e3d0a5a71ed49bc937df8">llvm::MIToken::kw_bb_id</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6aff7ad41fba511dad3cf8ed9165271232">llvm::MIToken::kw_bbsections</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a294c5581d42ad37196ca937c31e8598e">llvm::MIToken::kw_call_frame_size</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a94a48b5a62dbb5e2a2842729175252c2">llvm::MIToken::kw_ehfunclet_entry</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a8fe59ab747442928d520456cead79f7c">llvm::MIToken::kw_inlineasm_br_indirect_target</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6af0d89f9b8ae87326fdcc19e5b8b17450">llvm::MIToken::kw_ir_block_address_taken</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a061c7ab03098b9fa400aeaf9b0e668f7">llvm::MIToken::kw_landing_pad</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6ab98be0dc02a2cf82b6c6e1a7e0e8f15f">llvm::MIToken::kw_machine_block_address_taken</a>, <a href="#adbe0edbdba34278d011549a9e7c3d16e">lex</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acefe92adee8725ad904c7c43649790e8a4ee29ca12c7d126654bd0e5275de6135">llvm::List</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6aa19f9b1b5cf9928ce12e0dab92099c10">llvm::MIToken::lparen</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a7e5c1b1fdcdabc0c2d3ed5941308db6c">llvm::MIToken::MachineBasicBlockLabel</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a8b71950fb9a704439e1752de75ef57af">llvm::MIToken::NamedIRBlock</a>, <a href="#a4db9053414b75c0c90cb830a6b06b659">parseAlignment</a>, <a href="#ac3eddaf93bd102b2ee5c2d357f439000">parseBBID</a>, <a href="#af740a2ed2a8eef5fe4c7c4fc710fd77b">parseCallFrameSize</a>, <a href="#a9f34c58afe83b8b8dcc0299d74238a5a">parseIRBlock</a>, <a href="#a1d3978999a978f56f13fb8aae7348436">parseIRBlockAddressTaken</a>, <a href="#a5b4cb75e4b5f5a31d24d90dcebed12e3">parseSectionID</a> and <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6af002c0577ea092d33ec2e5268ff4201e">llvm::MIToken::rparen</a>.</p>


<p>Referenced by <a href="#a043bc88be0f1b6eac408827079cfcdf9">parseBasicBlockDefinitions</a>.</p>

</div>
</div>

### parseBasicBlockDefinitions() {#a043bc88be0f1b6eac408827079cfcdf9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MIParser::parseBasicBlockDefinitions (<a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; unsigned, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * &gt; &amp; MBBSlots)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 431 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp">MIParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/symbolrecordmapping-cpp/#a9cdf893c7d17e47fa1ed8bebf92a5da4">error</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a7ec17f6a52a8e82ff01425357cd53bb6">llvm::MIToken::lbrace</a>, <a href="#adbe0edbdba34278d011549a9e7c3d16e">lex</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a7e5c1b1fdcdabc0c2d3ed5941308db6c">llvm::MIToken::MachineBasicBlockLabel</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a38401c9f9d25b14c3ca4a36214b5f290">llvm::MIToken::Newline</a>, <a href="#aee1834e01cdaec2445802850ce7e92b4">parseBasicBlockDefinition</a> and <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a1b4d75865bc6f7723d3f2cae13c8b651">llvm::MIToken::rbrace</a>.</p>

</div>
</div>

### parseBasicBlockLiveins() {#ade810268bd683de9734a8fc78cc09266}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MIParser::parseBasicBlockLiveins (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 449 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp">MIParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6ac56884d19c1537e43044a3078cac0004">llvm::MIToken::colon</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a190591b275f9c74a12e9cc66e386d86c">llvm::MIToken::comma</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/symbolrecordmapping-cpp/#a9cdf893c7d17e47fa1ed8bebf92a5da4">error</a>, <a href="/web-llvm/docs/api/structs/llvm/lanebitmask/#a3714a639930eab71d7202da05ad82990">llvm::LaneBitmask::getAll</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6ab7084e2fd8ea5e2682facafa33c2abc6">llvm::MIToken::HexLiteral</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6ac47c420adaca267e079109b3d4dca293">llvm::MIToken::IntegerLiteral</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a5956125b492bac740985726d73b707c3">llvm::MIToken::kw_liveins</a>, <a href="#adbe0edbdba34278d011549a9e7c3d16e">lex</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6ada1e13f84d573245c05460a99ef47607">llvm::MIToken::NamedRegister</a> and <a href="#a1e4a55a09d735c80c50bbb0bc0f93158">parseNamedRegister</a>.</p>


<p>Referenced by <a href="#a28645da3fb06003fe7d32756e5ff929b">parseBasicBlock</a>.</p>

</div>
</div>

### parseBasicBlocks() {#a3904021432d1d4cf1620b9c09506e612}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MIParser::parseBasicBlocks ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 432 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp">MIParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a935e2a8884592189d8f261634a0b24c5">llvm::MachineBasicBlock::addSuccessor</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a9451d22efb0e7385c6b73ca7799b1d70">llvm::MIToken::Eof</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#adc8f1be4a77ae671ac139d5f06b44deb">llvm::MachineBasicBlock::isSuccessor</a>, <a href="#adbe0edbdba34278d011549a9e7c3d16e">lex</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a7e5c1b1fdcdabc0c2d3ed5941308db6c">llvm::MIToken::MachineBasicBlockLabel</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a38401c9f9d25b14c3ca4a36214b5f290">llvm::MIToken::Newline</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a0c54da24de983d197068425e718fb607">llvm::MachineBasicBlock::normalizeSuccProbs</a>, <a href="#a28645da3fb06003fe7d32756e5ff929b">parseBasicBlock</a> and <a href="#a4324e2adebdc2aaca8ead3ed32de1667">parseMBBReference</a>.</p>

</div>
</div>

### parseBasicBlockSuccessors() {#ace3ad3f99a9b90046e398bc0c09d372b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MIParser::parseBasicBlockSuccessors (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 450 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp">MIParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6ac56884d19c1537e43044a3078cac0004">llvm::MIToken::colon</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a190591b275f9c74a12e9cc66e386d86c">llvm::MIToken::comma</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/symbolrecordmapping-cpp/#a9cdf893c7d17e47fa1ed8bebf92a5da4">error</a>, <a href="/web-llvm/docs/api/classes/llvm/branchprobability/#a286629cb3167717b736d06f88c8f4817">llvm::BranchProbability::getRaw</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6ab7084e2fd8ea5e2682facafa33c2abc6">llvm::MIToken::HexLiteral</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6ac47c420adaca267e079109b3d4dca293">llvm::MIToken::IntegerLiteral</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6ac906e38f5901242459dd9fc47e3696f8">llvm::MIToken::kw_successors</a>, <a href="#adbe0edbdba34278d011549a9e7c3d16e">lex</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6aa19f9b1b5cf9928ce12e0dab92099c10">llvm::MIToken::lparen</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a3f519613749a65e91b6dfe908aaf554e">llvm::MIToken::MachineBasicBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="#a4324e2adebdc2aaca8ead3ed32de1667">parseMBBReference</a> and <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6af002c0577ea092d33ec2e5268ff4201e">llvm::MIToken::rparen</a>.</p>


<p>Referenced by <a href="#a28645da3fb06003fe7d32756e5ff929b">parseBasicBlock</a>.</p>

</div>
</div>

### parseBBID() {#ac3eddaf93bd102b2ee5c2d357f439000}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MIParser::parseBBID (std::optional&lt; <a href="/web-llvm/docs/api/structs/llvm/uniquebbid">UniqueBBID</a> &gt; &amp; BBID)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 513 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp">MIParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/symbolrecordmapping-cpp/#a9cdf893c7d17e47fa1ed8bebf92a5da4">error</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6ac47c420adaca267e079109b3d4dca293">llvm::MIToken::IntegerLiteral</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a36279270727e3d0a5a71ed49bc937df8">llvm::MIToken::kw_bb_id</a> and <a href="#adbe0edbdba34278d011549a9e7c3d16e">lex</a>.</p>


<p>Referenced by <a href="#aee1834e01cdaec2445802850ce7e92b4">parseBasicBlockDefinition</a>.</p>

</div>
</div>

### parseBlockAddressOperand() {#a77f5672641188aaed10066f78ebb24af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MIParser::parseBlockAddressOperand (<a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; Dest)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 493 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp">MIParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a190591b275f9c74a12e9cc66e386d86c">llvm::MIToken::comma</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ad3ad3b0e833c44eb432854df8e3bff6a">llvm::MachineOperand::CreateBA</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/symbolrecordmapping-cpp/#a9cdf893c7d17e47fa1ed8bebf92a5da4">error</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/blockaddress/#af6e2f535824d8f9b4bf1b1a75e5ab57c">llvm::BlockAddress::get</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a850ebe3ac4c626d9ea0cb6f26e7c904e">llvm::MIToken::GlobalValue</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6ab80383451bf22665b8b1e7deec8dba7e">llvm::MIToken::IRBlock</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a10b64d0278daea287b892ac95f4a70c1">llvm::MIToken::kw_blockaddress</a>, <a href="#adbe0edbdba34278d011549a9e7c3d16e">lex</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6aa19f9b1b5cf9928ce12e0dab92099c10">llvm::MIToken::lparen</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a26360791c68fa9d21c6ea07375867965">llvm::MIToken::NamedGlobalValue</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a8b71950fb9a704439e1752de75ef57af">llvm::MIToken::NamedIRBlock</a>, <a href="#a5ce71fb49004a1d688feb4434a27ab44">parseGlobalValue</a>, <a href="#a9f34c58afe83b8b8dcc0299d74238a5a">parseIRBlock</a>, <a href="#a13fa87aa1554fb342fde9c3f9cac14b8">parseOperandsOffset</a> and <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6af002c0577ea092d33ec2e5268ff4201e">llvm::MIToken::rparen</a>.</p>


<p>Referenced by <a href="#af7b186f0f87ad315cbd814abed5dab72">parseMachineOperand</a>.</p>

</div>
</div>

### parseCallFrameSize() {#af740a2ed2a8eef5fe4c7c4fc710fd77b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MIParser::parseCallFrameSize (unsigned &amp; CallFrameSize)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 514 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp">MIParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/symbolrecordmapping-cpp/#a9cdf893c7d17e47fa1ed8bebf92a5da4">error</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a294c5581d42ad37196ca937c31e8598e">llvm::MIToken::kw_call_frame_size</a> and <a href="#adbe0edbdba34278d011549a9e7c3d16e">lex</a>.</p>


<p>Referenced by <a href="#aee1834e01cdaec2445802850ce7e92b4">parseBasicBlockDefinition</a>.</p>

</div>
</div>

### parseCFIAddressSpace() {#a025beb578c2bc100c73a38c7d1b89a6d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MIParser::parseCFIAddressSpace (unsigned &amp; AddressSpace)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 489 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp">MIParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/symbolrecordmapping-cpp/#a9cdf893c7d17e47fa1ed8bebf92a5da4">error</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6ac47c420adaca267e079109b3d4dca293">llvm::MIToken::IntegerLiteral</a> and <a href="#adbe0edbdba34278d011549a9e7c3d16e">lex</a>.</p>


<p>Referenced by <a href="#ac0b8e1a3e4961f36e5acd8259ccceeab">parseCFIOperand</a>.</p>

</div>
</div>

### parseCFIEscapeValues() {#afb68fcdc971343ff6082386d506d8cb8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MIParser::parseCFIEscapeValues (std::string &amp; Values)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 490 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp">MIParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a190591b275f9c74a12e9cc66e386d86c">llvm::MIToken::comma</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/symbolrecordmapping-cpp/#a9cdf893c7d17e47fa1ed8bebf92a5da4">error</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6ab7084e2fd8ea5e2682facafa33c2abc6">llvm::MIToken::HexLiteral</a> and <a href="#adbe0edbdba34278d011549a9e7c3d16e">lex</a>.</p>


<p>Referenced by <a href="#ac0b8e1a3e4961f36e5acd8259ccceeab">parseCFIOperand</a>.</p>

</div>
</div>

### parseCFIOffset() {#af8e8e9f4122f068cfa33e5f17879c2ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MIParser::parseCFIOffset (int &amp; Offset)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 487 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp">MIParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/symbolrecordmapping-cpp/#a9cdf893c7d17e47fa1ed8bebf92a5da4">error</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6ac47c420adaca267e079109b3d4dca293">llvm::MIToken::IntegerLiteral</a>, <a href="#adbe0edbdba34278d011549a9e7c3d16e">lex</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>


<p>Referenced by <a href="#ac0b8e1a3e4961f36e5acd8259ccceeab">parseCFIOperand</a>.</p>

</div>
</div>

### parseCFIOperand() {#ac0b8e1a3e4961f36e5acd8259ccceeab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MIParser::parseCFIOperand (<a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; Dest)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 491 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp">MIParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mccfiinstruction/#a64fe578753bb594671a8e440e32a2b95">llvm::MCCFIInstruction::cfiDefCfa</a>, <a href="/web-llvm/docs/api/classes/llvm/mccfiinstruction/#abbe481ab35db0dcfa03f9f5bbabb9def">llvm::MCCFIInstruction::cfiDefCfaOffset</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a190591b275f9c74a12e9cc66e386d86c">llvm::MIToken::comma</a>, <a href="/web-llvm/docs/api/classes/llvm/mccfiinstruction/#ad6a85756410e7929f561fc1454069563">llvm::MCCFIInstruction::createAdjustCfaOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a3cf19eb005905508319869685dda19ec">llvm::MachineOperand::CreateCFIIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/mccfiinstruction/#a03445be1c81520587d5bb31b353f5558">llvm::MCCFIInstruction::createDefCfaRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/mccfiinstruction/#ac6eb36207cf2c7ebbd9a67e63dcc5568">llvm::MCCFIInstruction::createEscape</a>, <a href="/web-llvm/docs/api/classes/llvm/mccfiinstruction/#a5243e6ada761524b2689a8b52cbe9d0c">llvm::MCCFIInstruction::createLLVMDefAspaceCfa</a>, <a href="/web-llvm/docs/api/classes/llvm/mccfiinstruction/#a897ff5de2f1ce15003e513758c7cf7b1">llvm::MCCFIInstruction::createNegateRAState</a>, <a href="/web-llvm/docs/api/classes/llvm/mccfiinstruction/#a8546686a46d43f38c7104b866513fa2e">llvm::MCCFIInstruction::createNegateRAStateWithPC</a>, <a href="/web-llvm/docs/api/classes/llvm/mccfiinstruction/#a6a60a82f8cb445e9e7029e38733b2d30">llvm::MCCFIInstruction::createOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/mccfiinstruction/#a5efbfe5cee3e83355dec981c2d43611f">llvm::MCCFIInstruction::createRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/mccfiinstruction/#ae4f57b410a806f657695bfb7e19400c0">llvm::MCCFIInstruction::createRelOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/mccfiinstruction/#a8c6c95634a9db9cd0fc23175a01afd80">llvm::MCCFIInstruction::createRememberState</a>, <a href="/web-llvm/docs/api/classes/llvm/mccfiinstruction/#a43cce47857fdb1dfec97aeba83ab82a3">llvm::MCCFIInstruction::createRestore</a>, <a href="/web-llvm/docs/api/classes/llvm/mccfiinstruction/#ae2bed50736717b1120a41c6dcc41428f">llvm::MCCFIInstruction::createRestoreState</a>, <a href="/web-llvm/docs/api/classes/llvm/mccfiinstruction/#ae43652fadd6c5abd6a6554cd3395baee">llvm::MCCFIInstruction::createSameValue</a>, <a href="/web-llvm/docs/api/classes/llvm/mccfiinstruction/#a1a4f533e313a1288ce2cad49aa92d5e5">llvm::MCCFIInstruction::createUndefined</a>, <a href="/web-llvm/docs/api/classes/llvm/mccfiinstruction/#acdd3d6ea5364f4dd2460d0e31a191de4">llvm::MCCFIInstruction::createWindowSave</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a312a88bc3c813a44c29c661d9e981769">llvm::MIToken::kw_cfi_aarch64_negate_ra_sign_state</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a9741536facc1c8c790ac0929276d2bef">llvm::MIToken::kw_cfi_aarch64_negate_ra_sign_state_with_pc</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6aa4c84979e85e8fa30a9d33d7ebe59ca5">llvm::MIToken::kw_cfi_adjust_cfa_offset</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6aa94c3b98223057a43e6d39505f4a6e5f">llvm::MIToken::kw_cfi_def_cfa</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6aaec8c69ba4f771177000277c8e2403b3">llvm::MIToken::kw_cfi_def_cfa_offset</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a9b449f07ddab22c2e49164fc2aee112c">llvm::MIToken::kw_cfi_def_cfa_register</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6aa99f8585275a495b73a9319979194b5a">llvm::MIToken::kw_cfi_escape</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a3cc78b122a3960aed2a370a5241e6015">llvm::MIToken::kw_cfi_llvm_def_aspace_cfa</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a4cefddc97b52262ec3ca131128079be4">llvm::MIToken::kw_cfi_offset</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a8f3b8e825a1b96c0feb33b74c56eb891">llvm::MIToken::kw_cfi_register</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a94740fe117708e6e5de35dea49614ad0">llvm::MIToken::kw_cfi_rel_offset</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6ae264c83e0df5209a1dfcd322b0d0e74a">llvm::MIToken::kw_cfi_remember_state</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a836ad743b6d5b6e1d0bd80e05f42812c">llvm::MIToken::kw_cfi_restore</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6aee2c9ff26df9a29da2a3b5409cfde779">llvm::MIToken::kw_cfi_restore_state</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a9d9cd9b85ae5fce2a539f56fb037766a">llvm::MIToken::kw_cfi_same_value</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a7bb4c83768ee2a94a0a21aa1a0815752">llvm::MIToken::kw_cfi_undefined</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a712ca0bbf0925efcb0f451e6a53357ed">llvm::MIToken::kw_cfi_window_save</a>, <a href="#adbe0edbdba34278d011549a9e7c3d16e">lex</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="#a025beb578c2bc100c73a38c7d1b89a6d">parseCFIAddressSpace</a>, <a href="#afb68fcdc971343ff6082386d506d8cb8">parseCFIEscapeValues</a>, <a href="#af8e8e9f4122f068cfa33e5f17879c2ca">parseCFIOffset</a> and <a href="#a7954356a1d4fe56e90cf50b2820cd502">parseCFIRegister</a>.</p>


<p>Referenced by <a href="#af7b186f0f87ad315cbd814abed5dab72">parseMachineOperand</a>.</p>

</div>
</div>

### parseCFIRegister() {#a7954356a1d4fe56e90cf50b2820cd502}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MIParser::parseCFIRegister (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &amp; Reg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 488 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp">MIParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/symbolrecordmapping-cpp/#a9cdf893c7d17e47fa1ed8bebf92a5da4">error</a>, <a href="#adbe0edbdba34278d011549a9e7c3d16e">lex</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6ada1e13f84d573245c05460a99ef47607">llvm::MIToken::NamedRegister</a>, <a href="#a1e4a55a09d735c80c50bbb0bc0f93158">parseNamedRegister</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>


<p>Referenced by <a href="#ac0b8e1a3e4961f36e5acd8259ccceeab">parseCFIOperand</a>.</p>

</div>
</div>

### parseConstantPoolIndexOperand() {#aa736beb031d297f0eade73ddf496a663}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MIParser::parseConstantPoolIndexOperand (<a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; Dest)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 478 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp">MIParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a33dab87da238f19cc21814c491b2d6af">llvm::MIToken::ConstantPoolItem</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#aebe6fe7948d0ae093aba94381c73ed67">llvm::MachineOperand::CreateCPI</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/symbolrecordmapping-cpp/#a9cdf893c7d17e47fa1ed8bebf92a5da4">error</a>, <a href="#adbe0edbdba34278d011549a9e7c3d16e">lex</a> and <a href="#a13fa87aa1554fb342fde9c3f9cac14b8">parseOperandsOffset</a>.</p>


<p>Referenced by <a href="#af7b186f0f87ad315cbd814abed5dab72">parseMachineOperand</a>.</p>

</div>
</div>

### parseCustomRegisterMaskOperand() {#a115cf2109c3a6f662603ef7879242c59}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MIParser::parseCustomRegisterMaskOperand (<a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; Dest)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 499 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp">MIParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a190591b275f9c74a12e9cc66e386d86c">llvm::MIToken::comma</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a4c01d756ca363aef75429d61d21c0c14">llvm::MachineOperand::CreateRegMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/symbolrecordmapping-cpp/#a9cdf893c7d17e47fa1ed8bebf92a5da4">error</a>, <a href="#adbe0edbdba34278d011549a9e7c3d16e">lex</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6aa19f9b1b5cf9928ce12e0dab92099c10">llvm::MIToken::lparen</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6ada1e13f84d573245c05460a99ef47607">llvm::MIToken::NamedRegister</a>, <a href="#a1e4a55a09d735c80c50bbb0bc0f93158">parseNamedRegister</a> and <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6af002c0577ea092d33ec2e5268ff4201e">llvm::MIToken::rparen</a>.</p>


<p>Referenced by <a href="#af7b186f0f87ad315cbd814abed5dab72">parseMachineOperand</a>.</p>

</div>
</div>

### parseDbgInstrRefOperand() {#a1c86a488cc8a95190bc351fac90405e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MIParser::parseDbgInstrRefOperand (<a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; Dest)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 498 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp">MIParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a190591b275f9c74a12e9cc66e386d86c">llvm::MIToken::comma</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ab5cfdca0e0de9a0c79714b57b290e8a5">llvm::MachineOperand::CreateDbgInstrRef</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/symbolrecordmapping-cpp/#a9cdf893c7d17e47fa1ed8bebf92a5da4">error</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6ac47c420adaca267e079109b3d4dca293">llvm::MIToken::IntegerLiteral</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a44c287f7c3c0e3293241bde17a716828">llvm::MIToken::kw_dbg_instr_ref</a>, <a href="#adbe0edbdba34278d011549a9e7c3d16e">lex</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6aa19f9b1b5cf9928ce12e0dab92099c10">llvm::MIToken::lparen</a> and <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6af002c0577ea092d33ec2e5268ff4201e">llvm::MIToken::rparen</a>.</p>


<p>Referenced by <a href="#af7b186f0f87ad315cbd814abed5dab72">parseMachineOperand</a>.</p>

</div>
</div>

### parseDIExpression() {#a8ab2f664870f2d3c5f2036875672cf2a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MIParser::parseDIExpression (<a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> *&amp; Expr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 484 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp">MIParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/symbolrecordmapping-cpp/#a9cdf893c7d17e47fa1ed8bebf92a5da4">error</a>, <a href="#adbe0edbdba34278d011549a9e7c3d16e">lex</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a693d5398216b0ca25097c2bde8fe6284">llvm::parseDIExpressionBodyAtBeginning</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a171c000a87a56f9b4c9b4e3f43c5facfa33af1aad55fa136e2ab54409f4b4891f">llvm::Read</a>.</p>


<p>Referenced by <a href="#a0ba2f5ae9cb5a6e84640d02c50e52a09">parseMetadataOperand</a> and <a href="#ad9870bb0f0c1501dfa004566dbd5194b">parseStandaloneMDNode</a>.</p>

</div>
</div>

### parseDILocation() {#a3ac7a622a7557191953d14a7961a79fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MIParser::parseDILocation (<a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> *&amp; Expr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 485 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp">MIParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6ac56884d19c1537e43044a3078cac0004">llvm::MIToken::colon</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a190591b275f9c74a12e9cc66e386d86c">llvm::MIToken::comma</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/symbolrecordmapping-cpp/#a9cdf893c7d17e47fa1ed8bebf92a5da4">error</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6ae9b7e1e40ac9f787f763b636479f00d6">llvm::MIToken::exclaim</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a7d10a7b9b7f40b04d27ed97c38ea1950">llvm::MDNode::get</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a97b4377341cd7c584adcaa160aad0a02">llvm::MIToken::Identifier</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6ac47c420adaca267e079109b3d4dca293">llvm::MIToken::IntegerLiteral</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="#adbe0edbdba34278d011549a9e7c3d16e">lex</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6aa19f9b1b5cf9928ce12e0dab92099c10">llvm::MIToken::lparen</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6abc4fb36ac618caf2a11cb6c74f598d07">llvm::MIToken::md_dilocation</a>, <a href="#a3ac7a622a7557191953d14a7961a79fa">parseDILocation</a>, <a href="#a47550df64460e1d79194f04e687fd4bc">parseMDNode</a> and <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6af002c0577ea092d33ec2e5268ff4201e">llvm::MIToken::rparen</a>.</p>


<p>Referenced by <a href="#a9d7f3f2b0dc486075d4d462b7d744174">parse</a>, <a href="#a3ac7a622a7557191953d14a7961a79fa">parseDILocation</a> and <a href="#ad9870bb0f0c1501dfa004566dbd5194b">parseStandaloneMDNode</a>.</p>

</div>
</div>

### parseExternalSymbolOperand() {#aeab6958e2224c86557e4ae4a338bf07d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MIParser::parseExternalSymbolOperand (<a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; Dest)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 481 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp">MIParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a2871c33d3a1264270d23ec72b71f1399">llvm::MachineOperand::CreateES</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6abde8ba21041eb8328acc02146a3a0d77">llvm::MIToken::ExternalSymbol</a>, <a href="#adbe0edbdba34278d011549a9e7c3d16e">lex</a> and <a href="#a13fa87aa1554fb342fde9c3f9cac14b8">parseOperandsOffset</a>.</p>


<p>Referenced by <a href="#af7b186f0f87ad315cbd814abed5dab72">parseMachineOperand</a>.</p>

</div>
</div>

### parseFixedStackFrameIndex() {#a978abc1545ddae1a0e2cae4c02ab84b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MIParser::parseFixedStackFrameIndex (int &amp; FI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 474 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp">MIParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/symbolrecordmapping-cpp/#a9cdf893c7d17e47fa1ed8bebf92a5da4">error</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a9d8e09e328411c8dbdbd11f38bf1ff5b">llvm::MIToken::FixedStackObject</a> and <a href="#adbe0edbdba34278d011549a9e7c3d16e">lex</a>.</p>


<p>Referenced by <a href="#a509beb4628e05fbfe24e7bc562aa6d48">parseFixedStackObjectOperand</a> and <a href="#a58471cf0d31837efb05a35712ce9ad7c">parseMemoryPseudoSourceValue</a>.</p>

</div>
</div>

### parseFixedStackObjectOperand() {#a509beb4628e05fbfe24e7bc562aa6d48}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MIParser::parseFixedStackObjectOperand (<a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; Dest)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 475 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp">MIParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#afda3f1971b3e44709267be818ffd3035">llvm::MachineOperand::CreateFI</a> and <a href="#a978abc1545ddae1a0e2cae4c02ab84b4">parseFixedStackFrameIndex</a>.</p>


<p>Referenced by <a href="#af7b186f0f87ad315cbd814abed5dab72">parseMachineOperand</a>.</p>

</div>
</div>

### parseFPImmediateOperand() {#a4175071c6efe1557747e226a1e8fe2e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MIParser::parseFPImmediateOperand (<a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; Dest)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 469 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp">MIParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a2cd605d7476194cf38e7ef6d2c57391a">llvm::MachineOperand::CreateFPImm</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/symbolrecordmapping-cpp/#a9cdf893c7d17e47fa1ed8bebf92a5da4">error</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a6eb3a607d6c59086dc0bdfd74a10e6a4">llvm::MIToken::FloatingPointLiteral</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6ab7084e2fd8ea5e2682facafa33c2abc6">llvm::MIToken::HexLiteral</a>, <a href="#adbe0edbdba34278d011549a9e7c3d16e">lex</a> and <a href="#a08b018143e68b6cc36ab362d8b3b2626">parseIRConstant</a>.</p>


<p>Referenced by <a href="#af7b186f0f87ad315cbd814abed5dab72">parseMachineOperand</a>.</p>

</div>
</div>

### parseGlobalAddressOperand() {#a88ed2f870a01ae1fa7343375ab87dfb3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MIParser::parseGlobalAddressOperand (<a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; Dest)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 477 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp">MIParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ace112d8a86396bd55e99738cd41005b6">llvm::MachineOperand::CreateGA</a>, <a href="#adbe0edbdba34278d011549a9e7c3d16e">lex</a>, <a href="#a5ce71fb49004a1d688feb4434a27ab44">parseGlobalValue</a> and <a href="#a13fa87aa1554fb342fde9c3f9cac14b8">parseOperandsOffset</a>.</p>


<p>Referenced by <a href="#af7b186f0f87ad315cbd814abed5dab72">parseMachineOperand</a>.</p>

</div>
</div>

### parseGlobalValue() {#a5ce71fb49004a1d688feb4434a27ab44}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MIParser::parseGlobalValue (<a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> *&amp; GV)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 476 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp">MIParser.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/symbolrecordmapping-cpp/#a9cdf893c7d17e47fa1ed8bebf92a5da4">error</a>.</p>


<p>Referenced by <a href="#a77f5672641188aaed10066f78ebb24af">parseBlockAddressOperand</a>, <a href="#a88ed2f870a01ae1fa7343375ab87dfb3">parseGlobalAddressOperand</a> and <a href="#a58471cf0d31837efb05a35712ce9ad7c">parseMemoryPseudoSourceValue</a>.</p>

</div>
</div>

### parseHeapAllocMarker() {#a9d2304dd85a4ed00a421fad88a95e33d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MIParser::parseHeapAllocMarker (<a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> *&amp; Node)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 524 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp">MIParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a73e49b39421c784a08abf178343da0bc">llvm::MIToken::coloncolon</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a190591b275f9c74a12e9cc66e386d86c">llvm::MIToken::comma</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/symbolrecordmapping-cpp/#a9cdf893c7d17e47fa1ed8bebf92a5da4">error</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6afe193166e332234f73dabc8d161a364e">llvm::MIToken::kw_heap_alloc_marker</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a7ec17f6a52a8e82ff01425357cd53bb6">llvm::MIToken::lbrace</a>, <a href="#adbe0edbdba34278d011549a9e7c3d16e">lex</a> and <a href="#a47550df64460e1d79194f04e687fd4bc">parseMDNode</a>.</p>


<p>Referenced by <a href="#a9d7f3f2b0dc486075d4d462b7d744174">parse</a>.</p>

</div>
</div>

### parseImmediateOperand() {#a7d7396e09a5fcf968a2536b1375c356f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MIParser::parseImmediateOperand (<a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; Dest)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 463 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp">MIParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ab09679b541a6ba1219b3602569847364">llvm::MachineOperand::CreateImm</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/symbolrecordmapping-cpp/#a9cdf893c7d17e47fa1ed8bebf92a5da4">error</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a637b69dea56f804278aa50e975337e01">Int</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6ac47c420adaca267e079109b3d4dca293">llvm::MIToken::IntegerLiteral</a> and <a href="#adbe0edbdba34278d011549a9e7c3d16e">lex</a>.</p>


<p>Referenced by <a href="#af7b186f0f87ad315cbd814abed5dab72">parseMachineOperand</a>.</p>

</div>
</div>

### parseIntrinsicOperand() {#a02ce808485bec6d45ce163e0d50bb061}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MIParser::parseIntrinsicOperand (<a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; Dest)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 494 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp">MIParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#af7cf8fdf7e933b17b3fdf1d49b67e195">llvm::MachineOperand::CreateIntrinsicID</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/symbolrecordmapping-cpp/#a9cdf893c7d17e47fa1ed8bebf92a5da4">error</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a2034e311c1521d501ce4310e1a1ff6c5">llvm::MIToken::kw_intrinsic</a>, <a href="#adbe0edbdba34278d011549a9e7c3d16e">lex</a>, <a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#a821cf516da0409f54e4cd8a5b7478ea7">llvm::Intrinsic::lookupIntrinsicID</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6aa19f9b1b5cf9928ce12e0dab92099c10">llvm::MIToken::lparen</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a26360791c68fa9d21c6ea07375867965">llvm::MIToken::NamedGlobalValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#a35fedf4db6d756bd82501607f93c1e79aab5fb650050f184fa7c19c26abde5226">llvm::Intrinsic::not_intrinsic</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6af002c0577ea092d33ec2e5268ff4201e">llvm::MIToken::rparen</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a>.</p>


<p>Referenced by <a href="#af7b186f0f87ad315cbd814abed5dab72">parseMachineOperand</a>.</p>

</div>
</div>

### parseIRBlock() {#a9f34c58afe83b8b8dcc0299d74238a5a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MIParser::parseIRBlock (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *&amp; BB, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 492 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp">MIParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a5f6182886dc2f96c204299e92c1565d5">llvm::dyn_cast_or_null</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/symbolrecordmapping-cpp/#a9cdf893c7d17e47fa1ed8bebf92a5da4">error</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6ab80383451bf22665b8b1e7deec8dba7e">llvm::MIToken::IRBlock</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a> and <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a8b71950fb9a704439e1752de75ef57af">llvm::MIToken::NamedIRBlock</a>.</p>


<p>Referenced by <a href="#aee1834e01cdaec2445802850ce7e92b4">parseBasicBlockDefinition</a>, <a href="#a77f5672641188aaed10066f78ebb24af">parseBlockAddressOperand</a> and <a href="#a1d3978999a978f56f13fb8aae7348436">parseIRBlockAddressTaken</a>.</p>

</div>
</div>

### parseIRBlockAddressTaken() {#a1d3978999a978f56f13fb8aae7348436}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MIParser::parseIRBlockAddressTaken (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *&amp; BB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 509 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp">MIParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/symbolrecordmapping-cpp/#a9cdf893c7d17e47fa1ed8bebf92a5da4">error</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6ab80383451bf22665b8b1e7deec8dba7e">llvm::MIToken::IRBlock</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6af0d89f9b8ae87326fdcc19e5b8b17450">llvm::MIToken::kw_ir_block_address_taken</a>, <a href="#adbe0edbdba34278d011549a9e7c3d16e">lex</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a8b71950fb9a704439e1752de75ef57af">llvm::MIToken::NamedIRBlock</a> and <a href="#a9f34c58afe83b8b8dcc0299d74238a5a">parseIRBlock</a>.</p>


<p>Referenced by <a href="#aee1834e01cdaec2445802850ce7e92b4">parseBasicBlockDefinition</a>.</p>

</div>
</div>

### parseIRConstant() {#a08b018143e68b6cc36ab362d8b3b2626}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MIParser::parseIRConstant (<a href="/web-llvm/docs/api/classes/llvm/stringref/#a20d37563688a61a452fb26e317e37308">StringRef::iterator</a> Loc, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> StringValue, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> *&amp; C)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 464 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp">MIParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a> and <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/symbolrecordmapping-cpp/#a9cdf893c7d17e47fa1ed8bebf92a5da4">error</a>.</p>


<p>Referenced by <a href="#a4175071c6efe1557747e226a1e8fe2e2">parseFPImmediateOperand</a>, <a href="#a77465bdd671f1ee4c84511ad14036857">parseIRConstant</a> and <a href="#a96f48f9a5690ef01b9d2574472e1f7e2">parseTypedImmediateOperand</a>.</p>

</div>
</div>

### parseIRConstant() {#a77465bdd671f1ee4c84511ad14036857}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MIParser::parseIRConstant (<a href="/web-llvm/docs/api/classes/llvm/stringref/#a20d37563688a61a452fb26e317e37308">StringRef::iterator</a> Loc, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> *&amp; C)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 466 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp">MIParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="#adbe0edbdba34278d011549a9e7c3d16e">lex</a> and <a href="#a08b018143e68b6cc36ab362d8b3b2626">parseIRConstant</a>.</p>

</div>
</div>

### parseIRValue() {#a4b9a684b49a12183c3ace195827aa01e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MIParser::parseIRValue (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *&amp; V)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 516 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp">MIParser.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/symbolrecordmapping-cpp/#a9cdf893c7d17e47fa1ed8bebf92a5da4">error</a>.</p>


<p>Referenced by <a href="#a0e477b282f9f9b58b7a5b2f9b0e4fdee">parseMachinePointerInfo</a>.</p>

</div>
</div>

### parseJumpTableIndexOperand() {#a0688b95ba758f0bdee953833ccbd7a4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MIParser::parseJumpTableIndexOperand (<a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; Dest)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 480 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp">MIParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ab3700e1a41d8d584dc6e1720b803b2f6">llvm::MachineOperand::CreateJTI</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/symbolrecordmapping-cpp/#a9cdf893c7d17e47fa1ed8bebf92a5da4">error</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6af1ed79b968bc264cdbc86258d8566f0c">llvm::MIToken::JumpTableIndex</a> and <a href="#adbe0edbdba34278d011549a9e7c3d16e">lex</a>.</p>


<p>Referenced by <a href="#af7b186f0f87ad315cbd814abed5dab72">parseMachineOperand</a>.</p>

</div>
</div>

### parseLiveoutRegisterMaskOperand() {#ae35da4f6e23c51b04dc46d9fcfc7c066}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MIParser::parseLiveoutRegisterMaskOperand (<a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; Dest)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 500 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp">MIParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a190591b275f9c74a12e9cc66e386d86c">llvm::MIToken::comma</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac5416f0631d02c0c4404b906af9e3be9">llvm::MachineOperand::CreateRegLiveOut</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/symbolrecordmapping-cpp/#a9cdf893c7d17e47fa1ed8bebf92a5da4">error</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6aac74710d2bd4bbd53711b6ab4bfd2f28">llvm::MIToken::kw_liveout</a>, <a href="#adbe0edbdba34278d011549a9e7c3d16e">lex</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6aa19f9b1b5cf9928ce12e0dab92099c10">llvm::MIToken::lparen</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6ada1e13f84d573245c05460a99ef47607">llvm::MIToken::NamedRegister</a>, <a href="#a1e4a55a09d735c80c50bbb0bc0f93158">parseNamedRegister</a> and <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6af002c0577ea092d33ec2e5268ff4201e">llvm::MIToken::rparen</a>.</p>


<p>Referenced by <a href="#af7b186f0f87ad315cbd814abed5dab72">parseMachineOperand</a>.</p>

</div>
</div>

### parseLowLevelType() {#a1119c30ad17d23efa29bf5593774867d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MIParser::parseLowLevelType (<a href="/web-llvm/docs/api/classes/llvm/stringref/#a20d37563688a61a452fb26e317e37308">StringRef::iterator</a> Loc, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> &amp; Ty)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 467 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp">MIParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a0d10fe510ced2849a8074fe81e5d04ce">llvm::all_of</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a3fb2867a1e9fa36e135d9ee4dffb0167">llvm::StringRef::drop_front</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/symbolrecordmapping-cpp/#a9cdf893c7d17e47fa1ed8bebf92a5da4">error</a>, <a href="/web-llvm/docs/api/classes/llvm/elementcount/#a79ea372f9aa69492fccfafc0e5a1589c">llvm::ElementCount::get</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a217e0207d9cc8e046c2dccbf0e4bb198">llvm::APInt::getZExtValue</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a4706e21cf646fba2fb2044291a31ddd4">llvm::MIToken::greater</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a97b4377341cd7c584adcaa160aad0a02">llvm::MIToken::Identifier</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6ac47c420adaca267e079109b3d4dca293">llvm::MIToken::IntegerLiteral</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a4e7dadb5d20a08f47b6c4b6f6c28451a">llvm::MIToken::less</a>, <a href="#adbe0edbdba34278d011549a9e7c3d16e">lex</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a7ff0361855acbbe71b15b8dc6003fbc5">llvm::LLT::pointer</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a67021459c7ef8f9a634b4eac7ffd0f96">llvm::LLT::scalar</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a5db9240c74644c67759dd0f901fc3c7d">llvm::StringRef::size</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#ad2c874bad47bf92187afb13eb2840643">llvm::LLT::token</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a5360139c6b31d85cf3e29e2e6b7cf873">llvm::LLT::vector</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp/#ae11bc08fe8d4e564a486f41d54fd1a3c">verifyAddrSpace</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp/#a445320fe38048e124314eb2ecabaa22b">verifyScalarSize</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp/#a5e4b2e26f7b24adba3970e27caae53c7">verifyVectorElementCount</a>.</p>


<p>Referenced by <a href="#aaf6c3eb212e9e66ac2d36fdb7e0a51ed">parseMachineMemoryOperand</a> and <a href="#ad4d22d791beba2d17644bc14544e3877">parseRegisterOperand</a>.</p>

</div>
</div>

### parseMachineMemoryOperand() {#aaf6c3eb212e9e66ac2d36fdb7e0a51ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MIParser::parseMachineMemoryOperand (<a href="/web-llvm/docs/api/classes/llvm/machinememoperand">MachineMemOperand</a> *&amp; Dest)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 522 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp">MIParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a190591b275f9c74a12e9cc66e386d86c">llvm::MIToken::comma</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/symbolrecordmapping-cpp/#a9cdf893c7d17e47fa1ed8bebf92a5da4">error</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a97b4377341cd7c584adcaa160aad0a02">llvm::MIToken::Identifier</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6ac47c420adaca267e079109b3d4dca293">llvm::MIToken::IntegerLiteral</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a0943c04acc16f5a20793de60d48cfc93">llvm::MIToken::kw_addrspace</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a2b36847798e6a577ff1a459d436716cc">llvm::MIToken::kw_align</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a8fa817130e25e7d76dba39a1bd0962ee">llvm::MIToken::kw_basealign</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6abe977bfd868e054053a14b23da6252d7">llvm::MIToken::kw_unknown_size</a>, <a href="#adbe0edbdba34278d011549a9e7c3d16e">lex</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6aa19f9b1b5cf9928ce12e0dab92099c10">llvm::MIToken::lparen</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a16fa35720e09effc00ef5f5ad17a53dc">llvm::MIToken::md_alias_scope</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6aaede05e6d1ec29188d1d6e0741a9e60f">llvm::MIToken::md_noalias</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6ab66c1639a1e0b1b014352f33e42c0fbc">llvm::MIToken::md_range</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6aeca7cae50fb8dd8c7776861ce14cc24d">llvm::MIToken::md_tbaa</a>, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#aaa2020e47e35179234b9ea27d555b2dda7d12be6206e5b0026c71bbcd5cb76494">llvm::MachineMemOperand::MOLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#aaa2020e47e35179234b9ea27d555b2ddac2989bebe46c9b9fcb7a92e5ade8dde6">llvm::MachineMemOperand::MONone</a>, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#aaa2020e47e35179234b9ea27d555b2ddaed357b1367bc90a56fefa4d1b0e17374">llvm::MachineMemOperand::MOStore</a>, <a href="/web-llvm/docs/api/structs/llvm/aamdnodes/#a81f3c11f463009d8b19b544f5bfed40c">llvm::AAMDNodes::NoAlias</a>, <a href="#abd8f29ecab2bd9275731d9762e4707b3">parseAddrspace</a>, <a href="#a4db9053414b75c0c90cb830a6b06b659">parseAlignment</a>, <a href="#a1119c30ad17d23efa29bf5593774867d">parseLowLevelType</a>, <a href="#a0e477b282f9f9b58b7a5b2f9b0e4fdee">parseMachinePointerInfo</a>, <a href="#a47550df64460e1d79194f04e687fd4bc">parseMDNode</a>, <a href="#adb56879a68087d3940588f0c5e124c4c">parseMemoryOperandFlag</a>, <a href="#a7eb95d6aa8ae9f89008ea38203b6e894">parseOptionalAtomicOrdering</a>, <a href="#a62edb7a01e25422fd05722f2dc31445c">parseOptionalScope</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5542d44947f8d964b5ce3b20ea719b44">llvm::PowerOf2Ceil</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#a34bd74317e3f04bfc4318c2d1a470877">Range</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6af002c0577ea092d33ec2e5268ff4201e">llvm::MIToken::rparen</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a67021459c7ef8f9a634b4eac7ffd0f96">llvm::LLT::scalar</a>, <a href="/web-llvm/docs/api/structs/llvm/aamdnodes/#a5175e1defb539f65df5ded7a806fa5c8">llvm::AAMDNodes::Scope</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a> and <a href="/web-llvm/docs/api/structs/llvm/aamdnodes/#a56188042f9dd6003cb8ed087e8ae654f">llvm::AAMDNodes::TBAA</a>.</p>


<p>Referenced by <a href="#a9d7f3f2b0dc486075d4d462b7d744174">parse</a>.</p>

</div>
</div>

### parseMachineMetadata() {#af71425aaaccfd0af24609329584e5937}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MIParser::parseMachineMetadata ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 440 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp">MIParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6ab3c838fbfa1a8d60a66b3fe4aa360af9">llvm::MIToken::equal</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/symbolrecordmapping-cpp/#a9cdf893c7d17e47fa1ed8bebf92a5da4">error</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6ae9b7e1e40ac9f787f763b636479f00d6">llvm::MIToken::exclaim</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6ac47c420adaca267e079109b3d4dca293">llvm::MIToken::IntegerLiteral</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a2c5805b066544ecd04f444556adedb6c">llvm::MIToken::kw_distinct</a>, <a href="#adbe0edbdba34278d011549a9e7c3d16e">lex</a> and <a href="#a95e6736c0c4d939cc02161cd2db1644a">parseMDTuple</a>.</p>

</div>
</div>

### parseMachineOperand() {#af7b186f0f87ad315cbd814abed5dab72}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MIParser::parseMachineOperand (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned OpCode, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned OpIdx, <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; Dest, std::optional&lt; unsigned &gt; &amp; TiedDefIdx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 501 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp">MIParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a33dab87da238f19cc21814c491b2d6af">llvm::MIToken::ConstantPoolItem</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a4c01d756ca363aef75429d61d21c0c14">llvm::MachineOperand::CreateRegMask</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a73902454a32cbf1ad7ceac917df4bbd4">llvm::MIToken::dot</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a695bb4e1c6c5b89177aeb0f0cf489580">llvm::MIToken::Error</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/symbolrecordmapping-cpp/#a9cdf893c7d17e47fa1ed8bebf92a5da4">error</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6ae9b7e1e40ac9f787f763b636479f00d6">llvm::MIToken::exclaim</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6abde8ba21041eb8328acc02146a3a0d77">llvm::MIToken::ExternalSymbol</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a9d8e09e328411c8dbdbd11f38bf1ff5b">llvm::MIToken::FixedStackObject</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a850ebe3ac4c626d9ea0cb6f26e7c904e">llvm::MIToken::GlobalValue</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a97b4377341cd7c584adcaa160aad0a02">llvm::MIToken::Identifier</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6ac47c420adaca267e079109b3d4dca293">llvm::MIToken::IntegerLiteral</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6af1ed79b968bc264cdbc86258d8566f0c">llvm::MIToken::JumpTableIndex</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a59ea063561870edcff0bdd8f0d95b1a2">llvm::MIToken::kw_bfloat</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a10b64d0278daea287b892ac95f4a70c1">llvm::MIToken::kw_blockaddress</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a312a88bc3c813a44c29c661d9e981769">llvm::MIToken::kw_cfi_aarch64_negate_ra_sign_state</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a9741536facc1c8c790ac0929276d2bef">llvm::MIToken::kw_cfi_aarch64_negate_ra_sign_state_with_pc</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6aa4c84979e85e8fa30a9d33d7ebe59ca5">llvm::MIToken::kw_cfi_adjust_cfa_offset</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6aa94c3b98223057a43e6d39505f4a6e5f">llvm::MIToken::kw_cfi_def_cfa</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6aaec8c69ba4f771177000277c8e2403b3">llvm::MIToken::kw_cfi_def_cfa_offset</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a9b449f07ddab22c2e49164fc2aee112c">llvm::MIToken::kw_cfi_def_cfa_register</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6aa99f8585275a495b73a9319979194b5a">llvm::MIToken::kw_cfi_escape</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a3cc78b122a3960aed2a370a5241e6015">llvm::MIToken::kw_cfi_llvm_def_aspace_cfa</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a4cefddc97b52262ec3ca131128079be4">llvm::MIToken::kw_cfi_offset</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a8f3b8e825a1b96c0feb33b74c56eb891">llvm::MIToken::kw_cfi_register</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a94740fe117708e6e5de35dea49614ad0">llvm::MIToken::kw_cfi_rel_offset</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6ae264c83e0df5209a1dfcd322b0d0e74a">llvm::MIToken::kw_cfi_remember_state</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a836ad743b6d5b6e1d0bd80e05f42812c">llvm::MIToken::kw_cfi_restore</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6aee2c9ff26df9a29da2a3b5409cfde779">llvm::MIToken::kw_cfi_restore_state</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a9d9cd9b85ae5fce2a539f56fb037766a">llvm::MIToken::kw_cfi_same_value</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a7bb4c83768ee2a94a0a21aa1a0815752">llvm::MIToken::kw_cfi_undefined</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a712ca0bbf0925efcb0f451e6a53357ed">llvm::MIToken::kw_cfi_window_save</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a44c287f7c3c0e3293241bde17a716828">llvm::MIToken::kw_dbg_instr_ref</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a3c27c3f12ff5eac92e28e03d48af0a58">llvm::MIToken::kw_dead</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a6edca770467a61b3a5750a36b7c7731e">llvm::MIToken::kw_debug_use</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6addae3c49cf7e04a1535a29021ae91423">llvm::MIToken::kw_def</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a7ae1acf31fbbb0badf28636cabfb713d">llvm::MIToken::kw_double</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a4cb41f854136268b98f0a3b6f8b7d0b9">llvm::MIToken::kw_early_clobber</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a00d4edc540b86353fb2bbb5873454baa">llvm::MIToken::kw_float</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6abcdb15858b72e3e47c8fef5fc016f9e6">llvm::MIToken::kw_floatpred</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6ae03198c8736faa98f11254fde262dfa5">llvm::MIToken::kw_fp128</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a0b7a365eb84a10bcbe39e8a2603d1199">llvm::MIToken::kw_half</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6ab206051858a3a8aec9100cc51e5cfcb5">llvm::MIToken::kw_implicit</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6aa6a826947733d28faf3db46eb2924cbd">llvm::MIToken::kw_implicit_define</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6ae7fa8038ec793e64852ab7942c2bf5f0">llvm::MIToken::kw_internal</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a8e3daba81bd1d6ca3888c15382de1861">llvm::MIToken::kw_intpred</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a2034e311c1521d501ce4310e1a1ff6c5">llvm::MIToken::kw_intrinsic</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6ae6c29e07f6ec069203986ffe91d9bb63">llvm::MIToken::kw_killed</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6aac74710d2bd4bbd53711b6ab4bfd2f28">llvm::MIToken::kw_liveout</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a891e978963b68a2dbc9d02c116407fa0">llvm::MIToken::kw_ppc_fp128</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6abd8994d7aa807f0fc7a79bc0bd49ae51">llvm::MIToken::kw_renamable</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6af964d58ac7722e837d761dbff9598883">llvm::MIToken::kw_shufflemask</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6aa260bb514add2a91dc5689d2e3d0097b">llvm::MIToken::kw_target_index</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6af21fe671190c392445d0b4f6809403da">llvm::MIToken::kw_undef</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a217dd3c7155a23f5fd9f0592c0d19d4a">llvm::MIToken::kw_x86_fp80</a>, <a href="#adbe0edbdba34278d011549a9e7c3d16e">lex</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a3f519613749a65e91b6dfe908aaf554e">llvm::MIToken::MachineBasicBlock</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6ad3d487e3a5ce2baa29da23330ebbedc5">llvm::MIToken::MCSymbol</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a44e938a244ddbf730937be8d17272feb">llvm::MIToken::md_diexpr</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a26360791c68fa9d21c6ea07375867965">llvm::MIToken::NamedGlobalValue</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6ada1e13f84d573245c05460a99ef47607">llvm::MIToken::NamedRegister</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a4bb75c93c34ebe814b2500733ed2cbe2">llvm::MIToken::NamedVirtualRegister</a>, <a href="#a77f5672641188aaed10066f78ebb24af">parseBlockAddressOperand</a>, <a href="#ac0b8e1a3e4961f36e5acd8259ccceeab">parseCFIOperand</a>, <a href="#aa736beb031d297f0eade73ddf496a663">parseConstantPoolIndexOperand</a>, <a href="#a115cf2109c3a6f662603ef7879242c59">parseCustomRegisterMaskOperand</a>, <a href="#a1c86a488cc8a95190bc351fac90405e2">parseDbgInstrRefOperand</a>, <a href="#aeab6958e2224c86557e4ae4a338bf07d">parseExternalSymbolOperand</a>, <a href="#a509beb4628e05fbfe24e7bc562aa6d48">parseFixedStackObjectOperand</a>, <a href="#a4175071c6efe1557747e226a1e8fe2e2">parseFPImmediateOperand</a>, <a href="#a88ed2f870a01ae1fa7343375ab87dfb3">parseGlobalAddressOperand</a>, <a href="#a7d7396e09a5fcf968a2536b1375c356f">parseImmediateOperand</a>, <a href="#a02ce808485bec6d45ce163e0d50bb061">parseIntrinsicOperand</a>, <a href="#a0688b95ba758f0bdee953833ccbd7a4d">parseJumpTableIndexOperand</a>, <a href="#ae35da4f6e23c51b04dc46d9fcfc7c066">parseLiveoutRegisterMaskOperand</a>, <a href="#aa5f0e43ec22230708870040ca6a9bc2e">parseMBBOperand</a>, <a href="#a7eba052b8ea2a231281c651c53ef10b5">parseMCSymbolOperand</a>, <a href="#a0ba2f5ae9cb5a6e84640d02c50e52a09">parseMetadataOperand</a>, <a href="#a4590f4e05f484028f3b4bf3387955427">parsePredicateOperand</a>, <a href="#ad4d22d791beba2d17644bc14544e3877">parseRegisterOperand</a>, <a href="#a70c970df35e9a1ebde9a6371fb8a6bc6">parseShuffleMaskOperand</a>, <a href="#a6f18959fe1cc20cb62b5a169b61c0bb8">parseStackObjectOperand</a>, <a href="#a0c8d28ec07b076990dfad603aa041f9b">parseSubRegisterIndexOperand</a>, <a href="#af77884023f62584e3a1c2daad3d643c1">parseTargetImmMnemonic</a>, <a href="#a6273fafa595d2e1f8940595b5dccc8dc">parseTargetIndexOperand</a>, <a href="#a96f48f9a5690ef01b9d2574472e1f7e2">parseTypedImmediateOperand</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a02ea7320381cc7361f5f3530892eb3e1">llvm::MIToken::StackObject</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a2d9fa763e09f66fdd3f9f6a94c1b58e2">llvm::MIToken::SubRegisterIndex</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a1fcbf573b686db8220b374ddfce6bbdc">llvm::MIToken::underscore</a> and <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6aad89006e07a1b4b432094251dafeb05e">llvm::MIToken::VirtualRegister</a>.</p>


<p>Referenced by <a href="#adf35a52665d3f70d22acefe2846cb50f">parseMachineOperandAndTargetFlags</a>.</p>

</div>
</div>

### parseMachineOperandAndTargetFlags() {#adf35a52665d3f70d22acefe2846cb50f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MIParser::parseMachineOperandAndTargetFlags (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned OpCode, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned OpIdx, <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; Dest, std::optional&lt; unsigned &gt; &amp; TiedDefIdx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 504 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp">MIParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a190591b275f9c74a12e9cc66e386d86c">llvm::MIToken::comma</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/symbolrecordmapping-cpp/#a9cdf893c7d17e47fa1ed8bebf92a5da4">error</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a97b4377341cd7c584adcaa160aad0a02">llvm::MIToken::Identifier</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a4c9594c955fec80c73ddd964b5efd554">llvm::MachineOperand::isReg</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a030a2c5533093a46e7531c32906e5f3b">llvm::MIToken::kw_target_flags</a>, <a href="#adbe0edbdba34278d011549a9e7c3d16e">lex</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6aa19f9b1b5cf9928ce12e0dab92099c10">llvm::MIToken::lparen</a>, <a href="#af7b186f0f87ad315cbd814abed5dab72">parseMachineOperand</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6af002c0577ea092d33ec2e5268ff4201e">llvm::MIToken::rparen</a> and <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ad407b071bad6c9a435cade250ec8c8b6">llvm::MachineOperand::setTargetFlags</a>.</p>


<p>Referenced by <a href="#a9d7f3f2b0dc486075d4d462b7d744174">parse</a>.</p>

</div>
</div>

### parseMachinePointerInfo() {#a0e477b282f9f9b58b7a5b2f9b0e4fdee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MIParser::parseMachinePointerInfo (<a href="/web-llvm/docs/api/structs/llvm/machinepointerinfo">MachinePointerInfo</a> &amp; Dest)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 519 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp">MIParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/symbolrecordmapping-cpp/#a9cdf893c7d17e47fa1ed8bebf92a5da4">error</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a9d8e09e328411c8dbdbd11f38bf1ff5b">llvm::MIToken::FixedStackObject</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a850ebe3ac4c626d9ea0cb6f26e7c904e">llvm::MIToken::GlobalValue</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a56f6273627f38aacd8af4fe49a4dbab8">llvm::MIToken::IRValue</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a706a66b904c74b059eb4094498c964fc">llvm::MIToken::kw_call_entry</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a76138fb77b2f732e63b38f1e7065d383">llvm::MIToken::kw_constant_pool</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6ab93677f69d0041e06070c90910dcc30b">llvm::MIToken::kw_custom</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6ace222a16b52ad3ea7a399d31fd100d21">llvm::MIToken::kw_got</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a5c9a5d789f0256a1c4af7a366c8a83a8">llvm::MIToken::kw_jump_table</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a1005b6baed24c36e03431f6b02a184b0">llvm::MIToken::kw_stack</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6af13ae889d1ef5322dcc99aa328e20f6f">llvm::MIToken::kw_unknown_address</a>, <a href="#adbe0edbdba34278d011549a9e7c3d16e">lex</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a26360791c68fa9d21c6ea07375867965">llvm::MIToken::NamedGlobalValue</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a95e22b395cd577a493f41e1bc9f66857">llvm::MIToken::NamedIRValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="#a4b9a684b49a12183c3ace195827aa01e">parseIRValue</a>, <a href="#a58471cf0d31837efb05a35712ce9ad7c">parseMemoryPseudoSourceValue</a>, <a href="#a9aaa7797bd399f29fdd9f7c55e2d182a">parseOffset</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6ae8d68bd011115d762d74f4fa23c3d46e">llvm::MIToken::QuotedIRValue</a> and <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a02ea7320381cc7361f5f3530892eb3e1">llvm::MIToken::StackObject</a>.</p>


<p>Referenced by <a href="#aaf6c3eb212e9e66ac2d36fdb7e0a51ed">parseMachineMemoryOperand</a>.</p>

</div>
</div>

### parseMBBOperand() {#aa5f0e43ec22230708870040ca6a9bc2e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MIParser::parseMBBOperand (<a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; Dest)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 471 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp">MIParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#af38d24646cd711efc334aee49919cdf5">llvm::MachineOperand::CreateMBB</a>, <a href="#adbe0edbdba34278d011549a9e7c3d16e">lex</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a> and <a href="#a4324e2adebdc2aaca8ead3ed32de1667">parseMBBReference</a>.</p>


<p>Referenced by <a href="#af7b186f0f87ad315cbd814abed5dab72">parseMachineOperand</a>.</p>

</div>
</div>

### parseMBBReference() {#a4324e2adebdc2aaca8ead3ed32de1667}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MIParser::parseMBBReference (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *&amp; MBB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 470 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp">MIParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/symbolrecordmapping-cpp/#a9cdf893c7d17e47fa1ed8bebf92a5da4">error</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a3f519613749a65e91b6dfe908aaf554e">llvm::MIToken::MachineBasicBlock</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a7e5c1b1fdcdabc0c2d3ed5941308db6c">llvm::MIToken::MachineBasicBlockLabel</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#af83da56920f4f1059b02e07966f9fccfab2ee912b91d69b435159c7c3f6df7f5f">llvm::Number</a>.</p>


<p>Referenced by <a href="#a3904021432d1d4cf1620b9c09506e612">parseBasicBlocks</a>, <a href="#ace3ad3f99a9b90046e398bc0c09d372b">parseBasicBlockSuccessors</a>, <a href="#aa5f0e43ec22230708870040ca6a9bc2e">parseMBBOperand</a> and <a href="#a8b6fb16ad1a073527ca219f25f242b9d">parseStandaloneMBB</a>.</p>

</div>
</div>

### parseMCSymbolOperand() {#a7eba052b8ea2a231281c651c53ef10b5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MIParser::parseMCSymbolOperand (<a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; Dest)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 482 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp">MIParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a081ab7d53b85dfd7a2f8609689147393">llvm::MachineOperand::CreateMCSymbol</a>, <a href="#adbe0edbdba34278d011549a9e7c3d16e">lex</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6ad3d487e3a5ce2baa29da23330ebbedc5">llvm::MIToken::MCSymbol</a> and <a href="#a13fa87aa1554fb342fde9c3f9cac14b8">parseOperandsOffset</a>.</p>


<p>Referenced by <a href="#af7b186f0f87ad315cbd814abed5dab72">parseMachineOperand</a>.</p>

</div>
</div>

### parseMDNode() {#a47550df64460e1d79194f04e687fd4bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MIParser::parseMDNode (<a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> *&amp; Node)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel nodiscard">nodiscard</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 483 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp">MIParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/symbolrecordmapping-cpp/#a9cdf893c7d17e47fa1ed8bebf92a5da4">error</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6ae9b7e1e40ac9f787f763b636479f00d6">llvm::MIToken::exclaim</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6ac47c420adaca267e079109b3d4dca293">llvm::MIToken::IntegerLiteral</a> and <a href="#adbe0edbdba34278d011549a9e7c3d16e">lex</a>.</p>


<p>Referenced by <a href="#a9d7f3f2b0dc486075d4d462b7d744174">parse</a>, <a href="#a3ac7a622a7557191953d14a7961a79fa">parseDILocation</a>, <a href="#a9d2304dd85a4ed00a421fad88a95e33d">parseHeapAllocMarker</a>, <a href="#aaf6c3eb212e9e66ac2d36fdb7e0a51ed">parseMachineMemoryOperand</a>, <a href="#a0ba2f5ae9cb5a6e84640d02c50e52a09">parseMetadataOperand</a>, <a href="#a16226e28e8a3155a820ac00075ed1892">parsePCSections</a> and <a href="#ad9870bb0f0c1501dfa004566dbd5194b">parseStandaloneMDNode</a>.</p>

</div>
</div>

### parseMDNodeVector() {#ae1c0498b0c1e685f7decf651532fc0d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MIParser::parseMDNodeVector (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> * &gt; &amp; Elts)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 442 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp">MIParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a190591b275f9c74a12e9cc66e386d86c">llvm::MIToken::comma</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/symbolrecordmapping-cpp/#a9cdf893c7d17e47fa1ed8bebf92a5da4">error</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a7ec17f6a52a8e82ff01425357cd53bb6">llvm::MIToken::lbrace</a>, <a href="#adbe0edbdba34278d011549a9e7c3d16e">lex</a>, <a href="#a83428d68b950a2dd6afc4c3292a82f49">parseMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a> and <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a1b4d75865bc6f7723d3f2cae13c8b651">llvm::MIToken::rbrace</a>.</p>


<p>Referenced by <a href="#a95e6736c0c4d939cc02161cd2db1644a">parseMDTuple</a>.</p>

</div>
</div>

### parseMDTuple() {#a95e6736c0c4d939cc02161cd2db1644a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MIParser::parseMDTuple (<a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> *&amp; MD, bool IsDistinct)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 441 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp">MIParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mdtuple/#aad2e50b107c264353f4de80e03f9f754">llvm::MDTuple::get</a>, <a href="/web-llvm/docs/api/classes/llvm/mdtuple/#a2b677a1b5f22a826519b4d4875a7342c">llvm::MDTuple::getDistinct</a> and <a href="#ae1c0498b0c1e685f7decf651532fc0d9">parseMDNodeVector</a>.</p>


<p>Referenced by <a href="#af71425aaaccfd0af24609329584e5937">parseMachineMetadata</a>.</p>

</div>
</div>

### parseMemoryOperandFlag() {#adb56879a68087d3940588f0c5e124c4c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MIParser::parseMemoryOperandFlag (<a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#aaa2020e47e35179234b9ea27d555b2dd">MachineMemOperand::Flags</a> &amp; Flags)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 517 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp">MIParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/symbolrecordmapping-cpp/#a9cdf893c7d17e47fa1ed8bebf92a5da4">error</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6aa622b3d50d254c6f16b5f0dc2693f9ac">llvm::MIToken::kw_dereferenceable</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6aa82f97904d6c89ebe2d24b97cc8c9b3f">llvm::MIToken::kw_invariant</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a8d5d15b10a5a1d9cf253d722eb2a6089">llvm::MIToken::kw_non_temporal</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a1ede3539864c36bc93493e09f7b0fdec">llvm::MIToken::kw_volatile</a>, <a href="#adbe0edbdba34278d011549a9e7c3d16e">lex</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#aaa2020e47e35179234b9ea27d555b2dda7b999a936bc7a4d45dfadbe356e77b3f">llvm::MachineMemOperand::MODereferenceable</a>, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#aaa2020e47e35179234b9ea27d555b2ddac63dd9c4fe69bfeaac7a363fda846ac6">llvm::MachineMemOperand::MOInvariant</a>, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#aaa2020e47e35179234b9ea27d555b2dda8d09c51969b0954512ed65ee26551081">llvm::MachineMemOperand::MONonTemporal</a>, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#aaa2020e47e35179234b9ea27d555b2dda796891d6ca349b671fce24b6d01d77a8">llvm::MachineMemOperand::MOVolatile</a> and <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a7dcd0f9b261114fe964552407f110a04">llvm::MIToken::StringConstant</a>.</p>


<p>Referenced by <a href="#aaf6c3eb212e9e66ac2d36fdb7e0a51ed">parseMachineMemoryOperand</a>.</p>

</div>
</div>

### parseMemoryPseudoSourceValue() {#a58471cf0d31837efb05a35712ce9ad7c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MIParser::parseMemoryPseudoSourceValue (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/pseudosourcevalue">PseudoSourceValue</a> *&amp; PSV)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 518 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp">MIParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/symbolrecordmapping-cpp/#a9cdf893c7d17e47fa1ed8bebf92a5da4">error</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6abde8ba21041eb8328acc02146a3a0d77">llvm::MIToken::ExternalSymbol</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a9d8e09e328411c8dbdbd11f38bf1ff5b">llvm::MIToken::FixedStackObject</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a850ebe3ac4c626d9ea0cb6f26e7c904e">llvm::MIToken::GlobalValue</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a706a66b904c74b059eb4094498c964fc">llvm::MIToken::kw_call_entry</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a76138fb77b2f732e63b38f1e7065d383">llvm::MIToken::kw_constant_pool</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6ab93677f69d0041e06070c90910dcc30b">llvm::MIToken::kw_custom</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6ace222a16b52ad3ea7a399d31fd100d21">llvm::MIToken::kw_got</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a5c9a5d789f0256a1c4af7a366c8a83a8">llvm::MIToken::kw_jump_table</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a1005b6baed24c36e03431f6b02a184b0">llvm::MIToken::kw_stack</a>, <a href="#adbe0edbdba34278d011549a9e7c3d16e">lex</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a26360791c68fa9d21c6ea07375867965">llvm::MIToken::NamedGlobalValue</a>, <a href="#a978abc1545ddae1a0e2cae4c02ab84b4">parseFixedStackFrameIndex</a>, <a href="#a5ce71fb49004a1d688feb4434a27ab44">parseGlobalValue</a>, <a href="#a453f3120ed4a899975ffac8bdda7417a">parseStackFrameIndex</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a02ea7320381cc7361f5f3530892eb3e1">llvm::MIToken::StackObject</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a>.</p>


<p>Referenced by <a href="#a0e477b282f9f9b58b7a5b2f9b0e4fdee">parseMachinePointerInfo</a>.</p>

</div>
</div>

### parseMetadata() {#a83428d68b950a2dd6afc4c3292a82f49}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MIParser::parseMetadata (<a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> *&amp; MD)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 443 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp">MIParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/symbolrecordmapping-cpp/#a9cdf893c7d17e47fa1ed8bebf92a5da4">error</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6ae9b7e1e40ac9f787f763b636479f00d6">llvm::MIToken::exclaim</a>, <a href="/web-llvm/docs/api/classes/llvm/mdstring/#affbb7e2e9ad8d18114816f2443d672b9">llvm::MDString::get</a>, <a href="/web-llvm/docs/api/classes/llvm/mdtuple/#ac2e84f7e25af6e1de8cb811a57c6ee29">llvm::MDTuple::getTemporary</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6ac47c420adaca267e079109b3d4dca293">llvm::MIToken::IntegerLiteral</a>, <a href="#adbe0edbdba34278d011549a9e7c3d16e">lex</a> and <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a7dcd0f9b261114fe964552407f110a04">llvm::MIToken::StringConstant</a>.</p>


<p>Referenced by <a href="#ae1c0498b0c1e685f7decf651532fc0d9">parseMDNodeVector</a>.</p>

</div>
</div>

### parseMetadataOperand() {#a0ba2f5ae9cb5a6e84640d02c50e52a09}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MIParser::parseMetadataOperand (<a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; Dest)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 486 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp">MIParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a903091abda5acf43af8ade829181b9b4">llvm::MachineOperand::CreateMetadata</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6ae9b7e1e40ac9f787f763b636479f00d6">llvm::MIToken::exclaim</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a44e938a244ddbf730937be8d17272feb">llvm::MIToken::md_diexpr</a>, <a href="#a8ab2f664870f2d3c5f2036875672cf2a">parseDIExpression</a> and <a href="#a47550df64460e1d79194f04e687fd4bc">parseMDNode</a>.</p>


<p>Referenced by <a href="#af7b186f0f87ad315cbd814abed5dab72">parseMachineOperand</a>.</p>

</div>
</div>

### parseNamedRegister() {#a1e4a55a09d735c80c50bbb0bc0f93158}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MIParser::parseNamedRegister (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &amp; Reg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 452 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp">MIParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/symbolrecordmapping-cpp/#a9cdf893c7d17e47fa1ed8bebf92a5da4">error</a> and <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6ada1e13f84d573245c05460a99ef47607">llvm::MIToken::NamedRegister</a>.</p>


<p>Referenced by <a href="#ade810268bd683de9734a8fc78cc09266">parseBasicBlockLiveins</a>, <a href="#a7954356a1d4fe56e90cf50b2820cd502">parseCFIRegister</a>, <a href="#a115cf2109c3a6f662603ef7879242c59">parseCustomRegisterMaskOperand</a>, <a href="#ae35da4f6e23c51b04dc46d9fcfc7c066">parseLiveoutRegisterMaskOperand</a>, <a href="#af24785732d415fd376c19df162d3d1aa">parseRegister</a> and <a href="#afbc0c7f10ce30d72b70bd6982596e10b">parseStandaloneNamedRegister</a>.</p>

</div>
</div>

### parseNamedVirtualRegister() {#a451417fceac11225426e2b816a7775e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MIParser::parseNamedVirtualRegister (<a href="/web-llvm/docs/api/structs/llvm/vreginfo">VRegInfo</a> *&amp; Info)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 454 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp">MIParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a4bb75c93c34ebe814b2500733ed2cbe2">llvm::MIToken::NamedVirtualRegister</a>.</p>


<p>Referenced by <a href="#a408291205fdd1fc5034490d72966c6ab">parseVirtualRegister</a>.</p>

</div>
</div>

### parseOffset() {#a9aaa7797bd399f29fdd9f7c55e2d182a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MIParser::parseOffset (int64_t &amp; Offset)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 508 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp">MIParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/symbolrecordmapping-cpp/#a9cdf893c7d17e47fa1ed8bebf92a5da4">error</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6ac47c420adaca267e079109b3d4dca293">llvm::MIToken::IntegerLiteral</a>, <a href="#adbe0edbdba34278d011549a9e7c3d16e">lex</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a95a262807a0e29e6c8da9c780b5cd489">llvm::MIToken::minus</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a> and <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a80a791797a5aa271f17b100dc2915658">llvm::MIToken::plus</a>.</p>


<p>Referenced by <a href="#a0e477b282f9f9b58b7a5b2f9b0e4fdee">parseMachinePointerInfo</a> and <a href="#a13fa87aa1554fb342fde9c3f9cac14b8">parseOperandsOffset</a>.</p>

</div>
</div>

### parseOperandsOffset() {#a13fa87aa1554fb342fde9c3f9cac14b8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MIParser::parseOperandsOffset (<a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; Op)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 515 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp">MIParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a> and <a href="#a9aaa7797bd399f29fdd9f7c55e2d182a">parseOffset</a>.</p>


<p>Referenced by <a href="#a77f5672641188aaed10066f78ebb24af">parseBlockAddressOperand</a>, <a href="#aa736beb031d297f0eade73ddf496a663">parseConstantPoolIndexOperand</a>, <a href="#aeab6958e2224c86557e4ae4a338bf07d">parseExternalSymbolOperand</a>, <a href="#a88ed2f870a01ae1fa7343375ab87dfb3">parseGlobalAddressOperand</a>, <a href="#a7eba052b8ea2a231281c651c53ef10b5">parseMCSymbolOperand</a> and <a href="#a6273fafa595d2e1f8940595b5dccc8dc">parseTargetIndexOperand</a>.</p>

</div>
</div>

### parseOptionalAtomicOrdering() {#a7eb95d6aa8ae9f89008ea38203b6e894}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MIParser::parseOptionalAtomicOrdering (<a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7">AtomicOrdering</a> &amp; Order)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 521 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp">MIParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7a993ca650a85e8e69b8f7eaa4809c4862">llvm::Acquire</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7a960fbd067612ca87e16d5dfdb12fe40a">llvm::AcquireRelease</a>, <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#a3de12858bdbbd0b3da179d508ff2be75">llvm::StringSwitch&lt; T, R &gt;::Case</a>, <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#a7f0e82e8a818ca43926fceb49be81661">llvm::StringSwitch&lt; T, R &gt;::Default</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/symbolrecordmapping-cpp/#a9cdf893c7d17e47fa1ed8bebf92a5da4">error</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a97b4377341cd7c584adcaa160aad0a02">llvm::MIToken::Identifier</a>, <a href="#adbe0edbdba34278d011549a9e7c3d16e">lex</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7a14194d0b2e6c6680067975517cd58eac">llvm::Monotonic</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7a56a57d29a3f9dda8671b4d6490a94b08">llvm::NotAtomic</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7ab8e7b465df7c5979dc731d06e84ce2cf">llvm::Release</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7ae3b0fa849dbd758b450f98fcfde936a2">llvm::SequentiallyConsistent</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7a288d468c5e0969f26a310773eda65603">llvm::Unordered</a>.</p>


<p>Referenced by <a href="#aaf6c3eb212e9e66ac2d36fdb7e0a51ed">parseMachineMemoryOperand</a>.</p>

</div>
</div>

### parseOptionalScope() {#a62edb7a01e25422fd05722f2dc31445c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MIParser::parseOptionalScope (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; Context, <a href="/web-llvm/docs/api/namespaces/llvm/syncscope/#a80741d3f96133391b683effd8e5b77f0">SyncScope::ID</a> &amp; SSID)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 520 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp">MIParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/symbolrecordmapping-cpp/#a9cdf893c7d17e47fa1ed8bebf92a5da4">error</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a97b4377341cd7c584adcaa160aad0a02">llvm::MIToken::Identifier</a>, <a href="#adbe0edbdba34278d011549a9e7c3d16e">lex</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6aa19f9b1b5cf9928ce12e0dab92099c10">llvm::MIToken::lparen</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6af002c0577ea092d33ec2e5268ff4201e">llvm::MIToken::rparen</a> and <a href="/web-llvm/docs/api/namespaces/llvm/syncscope/#a15caddcf5c9b41f2f15c2ec363589f6caf9706a2e196638078e8323bfd9ba17de">llvm::SyncScope::System</a>.</p>


<p>Referenced by <a href="#aaf6c3eb212e9e66ac2d36fdb7e0a51ed">parseMachineMemoryOperand</a>.</p>

</div>
</div>

### parsePCSections() {#a16226e28e8a3155a820ac00075ed1892}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MIParser::parsePCSections (<a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> *&amp; Node)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 525 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp">MIParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a73e49b39421c784a08abf178343da0bc">llvm::MIToken::coloncolon</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a190591b275f9c74a12e9cc66e386d86c">llvm::MIToken::comma</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/symbolrecordmapping-cpp/#a9cdf893c7d17e47fa1ed8bebf92a5da4">error</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6ae79b65c3955b6b96bd3e16a9691b0718">llvm::MIToken::kw_pcsections</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a7ec17f6a52a8e82ff01425357cd53bb6">llvm::MIToken::lbrace</a>, <a href="#adbe0edbdba34278d011549a9e7c3d16e">lex</a> and <a href="#a47550df64460e1d79194f04e687fd4bc">parseMDNode</a>.</p>


<p>Referenced by <a href="#a9d7f3f2b0dc486075d4d462b7d744174">parse</a>.</p>

</div>
</div>

### parsePredicateOperand() {#a4590f4e05f484028f3b4bf3387955427}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MIParser::parsePredicateOperand (<a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; Dest)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 495 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp">MIParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78bad99425e1c7df18b4be5edbffbf896e55">llvm::CmpInst::BAD_FCMP_PREDICATE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba07aee43ffb66908a25c55c77ce4c0d05">llvm::CmpInst::BAD_ICMP_PREDICATE</a>, <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#a3de12858bdbbd0b3da179d508ff2be75">llvm::StringSwitch&lt; T, R &gt;::Case</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a985d3c6d580d9dad7efe3129606150ae">llvm::MachineOperand::CreatePredicate</a>, <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#a7f0e82e8a818ca43926fceb49be81661">llvm::StringSwitch&lt; T, R &gt;::Default</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/symbolrecordmapping-cpp/#a9cdf893c7d17e47fa1ed8bebf92a5da4">error</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78bae9c013750fff3023001d7e3af8df2d6d">llvm::CmpInst::FCMP_FALSE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba024db78a5ed74f64666f3ca4955e6eca">llvm::CmpInst::FCMP_OEQ</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba541533f34077bbbcfb703a90f6d2da9b">llvm::CmpInst::FCMP_OGE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba4c399f525bbcf03d72af4b303e6eeca8">llvm::CmpInst::FCMP_OGT</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba9835cfe02fb5027680bd7203b024f77a">llvm::CmpInst::FCMP_OLE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba326bee0a4a424cef21c1cf8adb8b8dd8">llvm::CmpInst::FCMP_OLT</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba8a80b27ca29fe2076b9bbdee02c65464">llvm::CmpInst::FCMP_ONE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78baa3213b645e029aba8bb1b85213607d5e">llvm::CmpInst::FCMP_ORD</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba0a33c71e3c5e8f128ca47539a85962f5">llvm::CmpInst::FCMP_TRUE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba919643b83ce3c9af2e4296ed5e413a1f">llvm::CmpInst::FCMP_UEQ</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78bae51609fc6a425f849d37c28cb9bc0344">llvm::CmpInst::FCMP_UGE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba959268ceeae23abe5c9ad9e895669d0c">llvm::CmpInst::FCMP_UGT</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba396dda2571cd3c575f1d9cb44dc2cc09">llvm::CmpInst::FCMP_ULE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba75016d5872d90adf89cc1cbf5763f474">llvm::CmpInst::FCMP_ULT</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78bad601460c9371d0f0ada5ae006bdba2bd">llvm::CmpInst::FCMP_UNE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78baf0159e4005258dc54f20b6fc227d19ed">llvm::CmpInst::FCMP_UNO</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78baa719225e2de4059f93fd3209e1f48218">llvm::CmpInst::ICMP_EQ</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78bac17897ebf2f6a6986280fc3bdf28a30a">llvm::CmpInst::ICMP_NE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78bac1aa7b798ba11d2e497d5cce6ce6d3dc">llvm::CmpInst::ICMP_SGE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba720a42e85f7e981afd61e28473b0000a">llvm::CmpInst::ICMP_SGT</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba2751d6136a2819749dcef65dc19a4246">llvm::CmpInst::ICMP_SLE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba15ae464950ac676919c2f0c7aafc706c">llvm::CmpInst::ICMP_SLT</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba573bcd571c938fce863525330bbfc4b8">llvm::CmpInst::ICMP_UGE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba607cecdc5172814382033e001ed11fad">llvm::CmpInst::ICMP_UGT</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78bad92f160316221fd4090520bb2b3cefc5">llvm::CmpInst::ICMP_ULE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba91d86a4753c8bd7624e01bf565d87f8e">llvm::CmpInst::ICMP_ULT</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a97b4377341cd7c584adcaa160aad0a02">llvm::MIToken::Identifier</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a66c10680694a0184d50e7a8c0d1ea874">llvm::CmpInst::isFPPredicate</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#ad8c2100cae3093d71e65a48908158e22">llvm::CmpInst::isIntPredicate</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6abcdb15858b72e3e47c8fef5fc016f9e6">llvm::MIToken::kw_floatpred</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a8e3daba81bd1d6ca3888c15382de1861">llvm::MIToken::kw_intpred</a>, <a href="#adbe0edbdba34278d011549a9e7c3d16e">lex</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6aa19f9b1b5cf9928ce12e0dab92099c10">llvm::MIToken::lparen</a> and <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6af002c0577ea092d33ec2e5268ff4201e">llvm::MIToken::rparen</a>.</p>


<p>Referenced by <a href="#af7b186f0f87ad315cbd814abed5dab72">parseMachineOperand</a>.</p>

</div>
</div>

### parsePreOrPostInstrSymbol() {#a2c772f7f4d284b2ad112741a2f451bf4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MIParser::parsePreOrPostInstrSymbol (<a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> *&amp; Symbol)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 523 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp">MIParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a73e49b39421c784a08abf178343da0bc">llvm::MIToken::coloncolon</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a190591b275f9c74a12e9cc66e386d86c">llvm::MIToken::comma</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/symbolrecordmapping-cpp/#a9cdf893c7d17e47fa1ed8bebf92a5da4">error</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6aea446ae4c2ab038ada07483d17fa8fd3">llvm::MIToken::kw_post_instr_symbol</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a16baa8a695f87a8d642a0271f9c8bb4b">llvm::MIToken::kw_pre_instr_symbol</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a7ec17f6a52a8e82ff01425357cd53bb6">llvm::MIToken::lbrace</a>, <a href="#adbe0edbdba34278d011549a9e7c3d16e">lex</a> and <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6ad3d487e3a5ce2baa29da23330ebbedc5">llvm::MIToken::MCSymbol</a>.</p>


<p>Referenced by <a href="#a9d7f3f2b0dc486075d4d462b7d744174">parse</a>.</p>

</div>
</div>

### parseRegister() {#af24785732d415fd376c19df162d3d1aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MIParser::parseRegister (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &amp; Reg, <a href="/web-llvm/docs/api/structs/llvm/vreginfo">VRegInfo</a> *&amp; VRegInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 455 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp">MIParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6ada1e13f84d573245c05460a99ef47607">llvm::MIToken::NamedRegister</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a4bb75c93c34ebe814b2500733ed2cbe2">llvm::MIToken::NamedVirtualRegister</a>, <a href="#a1e4a55a09d735c80c50bbb0bc0f93158">parseNamedRegister</a>, <a href="#a408291205fdd1fc5034490d72966c6ab">parseVirtualRegister</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a1fcbf573b686db8220b374ddfce6bbdc">llvm::MIToken::underscore</a> and <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6aad89006e07a1b4b432094251dafeb05e">llvm::MIToken::VirtualRegister</a>.</p>


<p>Referenced by <a href="#ad4d22d791beba2d17644bc14544e3877">parseRegisterOperand</a> and <a href="#a0e113b6be43fae44b91eaac633118ba8">parseStandaloneRegister</a>.</p>

</div>
</div>

### parseRegisterClassOrBank() {#a6e4e4f98e1264c57604c033122d6fceb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MIParser::parseRegisterClassOrBank (<a href="/web-llvm/docs/api/structs/llvm/vreginfo">VRegInfo</a> &amp; RegInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 457 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp">MIParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/symbolrecordmapping-cpp/#a9cdf893c7d17e47fa1ed8bebf92a5da4">error</a>, <a href="/web-llvm/docs/api/structs/llvm/vreginfo/#a8408a547dab7a555dbb2ec921a944141a5eaad4d1be16bfba57c6b97de5a674e9">llvm::VRegInfo::GENERIC</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a97b4377341cd7c584adcaa160aad0a02">llvm::MIToken::Identifier</a>, <a href="/web-llvm/docs/api/structs/reginfo/#a054fbcc9a600f0b033b93a3006dc4c7a">RegInfo::Kind</a>, <a href="#adbe0edbdba34278d011549a9e7c3d16e">lex</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/structs/llvm/vreginfo/#a8408a547dab7a555dbb2ec921a944141a83465f4ee6489afc731340ed6c9c99b6">llvm::VRegInfo::NORMAL</a>, <a href="/web-llvm/docs/api/structs/llvm/vreginfo/#a8408a547dab7a555dbb2ec921a944141ad412f0f8ee146367d4b0ca7e1681e269">llvm::VRegInfo::REGBANK</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a1fcbf573b686db8220b374ddfce6bbdc">llvm::MIToken::underscore</a> and <a href="/web-llvm/docs/api/structs/llvm/vreginfo/#a8408a547dab7a555dbb2ec921a944141a592454c2980a78a8164c4d7514b9f4bb">llvm::VRegInfo::UNKNOWN</a>.</p>


<p>Referenced by <a href="#ad4d22d791beba2d17644bc14544e3877">parseRegisterOperand</a>.</p>

</div>
</div>

### parseRegisterFlag() {#a04eaad27a8fb5a2f35432c4a09fa2221}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MIParser::parseRegisterFlag (unsigned &amp; Flags)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 456 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp">MIParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/regstate/#ade26fe5c9b3fe6948def36f7ca12dfc5a2fee1a7db4e84247a193a9af1f907013">llvm::RegState::Dead</a>, <a href="/web-llvm/docs/api/namespaces/llvm/regstate/#ade26fe5c9b3fe6948def36f7ca12dfc5a14af644ca4aff07a3768974c824ac9d5">llvm::RegState::Debug</a>, <a href="/web-llvm/docs/api/namespaces/llvm/regstate/#ade26fe5c9b3fe6948def36f7ca12dfc5a72c17e2ff2d5af62a30e56ac152aa8d5">llvm::RegState::Define</a>, <a href="/web-llvm/docs/api/namespaces/llvm/regstate/#ade26fe5c9b3fe6948def36f7ca12dfc5acf55f329675ba5045a4863c7a018209b">llvm::RegState::EarlyClobber</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/symbolrecordmapping-cpp/#a9cdf893c7d17e47fa1ed8bebf92a5da4">error</a>, <a href="/web-llvm/docs/api/namespaces/llvm/regstate/#ade26fe5c9b3fe6948def36f7ca12dfc5a0fec8ba6f4a4dc758b725205985eee99">llvm::RegState::Implicit</a>, <a href="/web-llvm/docs/api/namespaces/llvm/regstate/#ade26fe5c9b3fe6948def36f7ca12dfc5a833922eca2ad0eab70573ba1f5fba9af">llvm::RegState::ImplicitDefine</a>, <a href="/web-llvm/docs/api/namespaces/llvm/regstate/#ade26fe5c9b3fe6948def36f7ca12dfc5a7fcf0a8c65265b4519b79fa537bbd8a0">llvm::RegState::InternalRead</a>, <a href="/web-llvm/docs/api/namespaces/llvm/regstate/#ade26fe5c9b3fe6948def36f7ca12dfc5a9ddde91ef09476d28a088fe57f8e2921">llvm::RegState::Kill</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a3c27c3f12ff5eac92e28e03d48af0a58">llvm::MIToken::kw_dead</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a6edca770467a61b3a5750a36b7c7731e">llvm::MIToken::kw_debug_use</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6addae3c49cf7e04a1535a29021ae91423">llvm::MIToken::kw_def</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a4cb41f854136268b98f0a3b6f8b7d0b9">llvm::MIToken::kw_early_clobber</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6ab206051858a3a8aec9100cc51e5cfcb5">llvm::MIToken::kw_implicit</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6aa6a826947733d28faf3db46eb2924cbd">llvm::MIToken::kw_implicit_define</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6ae7fa8038ec793e64852ab7942c2bf5f0">llvm::MIToken::kw_internal</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6ae6c29e07f6ec069203986ffe91d9bb63">llvm::MIToken::kw_killed</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6abd8994d7aa807f0fc7a79bc0bd49ae51">llvm::MIToken::kw_renamable</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6af21fe671190c392445d0b4f6809403da">llvm::MIToken::kw_undef</a>, <a href="#adbe0edbdba34278d011549a9e7c3d16e">lex</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/regstate/#ade26fe5c9b3fe6948def36f7ca12dfc5a4c5b26e761294db59c1ad1cc6fc1d0ba">llvm::RegState::Renamable</a> and <a href="/web-llvm/docs/api/namespaces/llvm/regstate/#ade26fe5c9b3fe6948def36f7ca12dfc5ab502f975742e9bff6d6dd7b49439b806">llvm::RegState::Undef</a>.</p>


<p>Referenced by <a href="#ad4d22d791beba2d17644bc14544e3877">parseRegisterOperand</a>.</p>

</div>
</div>

### parseRegisterOperand() {#ad4d22d791beba2d17644bc14544e3877}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MIParser::parseRegisterOperand (<a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; Dest, std::optional&lt; unsigned &gt; &amp; TiedDefIdx, bool IsDef=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 460 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp">MIParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6ac56884d19c1537e43044a3078cac0004">llvm::MIToken::colon</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#af2c351dad09a71aa08e1d85c67ae6e53">llvm::MachineOperand::CreateReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/regstate/#ade26fe5c9b3fe6948def36f7ca12dfc5a2fee1a7db4e84247a193a9af1f907013">llvm::RegState::Dead</a>, <a href="/web-llvm/docs/api/namespaces/llvm/regstate/#ade26fe5c9b3fe6948def36f7ca12dfc5a14af644ca4aff07a3768974c824ac9d5">llvm::RegState::Debug</a>, <a href="/web-llvm/docs/api/namespaces/llvm/regstate/#ade26fe5c9b3fe6948def36f7ca12dfc5a72c17e2ff2d5af62a30e56ac152aa8d5">llvm::RegState::Define</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a73902454a32cbf1ad7ceac917df4bbd4">llvm::MIToken::dot</a>, <a href="/web-llvm/docs/api/namespaces/llvm/regstate/#ade26fe5c9b3fe6948def36f7ca12dfc5acf55f329675ba5045a4863c7a018209b">llvm::RegState::EarlyClobber</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/symbolrecordmapping-cpp/#a9cdf893c7d17e47fa1ed8bebf92a5da4">error</a>, <a href="/web-llvm/docs/api/structs/llvm/vreginfo/#a8408a547dab7a555dbb2ec921a944141a5eaad4d1be16bfba57c6b97de5a674e9">llvm::VRegInfo::GENERIC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/regstate/#ade26fe5c9b3fe6948def36f7ca12dfc5a0fec8ba6f4a4dc758b725205985eee99">llvm::RegState::Implicit</a>, <a href="/web-llvm/docs/api/namespaces/llvm/regstate/#ade26fe5c9b3fe6948def36f7ca12dfc5a7fcf0a8c65265b4519b79fa537bbd8a0">llvm::RegState::InternalRead</a>, <a href="/web-llvm/docs/api/namespaces/llvm/regstate/#ade26fe5c9b3fe6948def36f7ca12dfc5a9ddde91ef09476d28a088fe57f8e2921">llvm::RegState::Kill</a>, <a href="/web-llvm/docs/api/structs/reginfo/#a054fbcc9a600f0b033b93a3006dc4c7a">RegInfo::Kind</a>, <a href="#adbe0edbdba34278d011549a9e7c3d16e">lex</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6aa19f9b1b5cf9928ce12e0dab92099c10">llvm::MIToken::lparen</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>, <a href="#a1119c30ad17d23efa29bf5593774867d">parseLowLevelType</a>, <a href="#af24785732d415fd376c19df162d3d1aa">parseRegister</a>, <a href="#a6e4e4f98e1264c57604c033122d6fceb">parseRegisterClassOrBank</a>, <a href="#a04eaad27a8fb5a2f35432c4a09fa2221">parseRegisterFlag</a>, <a href="#a4a9e6ec38e90a9bb7a0ee15119e1e709">parseRegisterTiedDefIndex</a>, <a href="#a68d5b2d8a31ebf3554d265357f1baf28">parseSubRegisterIndex</a>, <a href="/web-llvm/docs/api/structs/llvm/vreginfo/#a8408a547dab7a555dbb2ec921a944141ad412f0f8ee146367d4b0ca7e1681e269">llvm::VRegInfo::REGBANK</a>, <a href="/web-llvm/docs/api/namespaces/llvm/regstate/#ade26fe5c9b3fe6948def36f7ca12dfc5a4c5b26e761294db59c1ad1cc6fc1d0ba">llvm::RegState::Renamable</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6af002c0577ea092d33ec2e5268ff4201e">llvm::MIToken::rparen</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#a92a6b0a9b7228d190b0a7d8ae3ef03c7">SubReg</a> and <a href="/web-llvm/docs/api/namespaces/llvm/regstate/#ade26fe5c9b3fe6948def36f7ca12dfc5ab502f975742e9bff6d6dd7b49439b806">llvm::RegState::Undef</a>.</p>


<p>Referenced by <a href="#a9d7f3f2b0dc486075d4d462b7d744174">parse</a> and <a href="#af7b186f0f87ad315cbd814abed5dab72">parseMachineOperand</a>.</p>

</div>
</div>

### parseRegisterTiedDefIndex() {#a4a9e6ec38e90a9bb7a0ee15119e1e709}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MIParser::parseRegisterTiedDefIndex (unsigned &amp; TiedDefIdx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 459 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp">MIParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/symbolrecordmapping-cpp/#a9cdf893c7d17e47fa1ed8bebf92a5da4">error</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6ac47c420adaca267e079109b3d4dca293">llvm::MIToken::IntegerLiteral</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a61a7c9d358791d8e1d5fea11c59d8b81">llvm::MIToken::kw_tied_def</a>, <a href="#adbe0edbdba34278d011549a9e7c3d16e">lex</a> and <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6af002c0577ea092d33ec2e5268ff4201e">llvm::MIToken::rparen</a>.</p>


<p>Referenced by <a href="#ad4d22d791beba2d17644bc14544e3877">parseRegisterOperand</a>.</p>

</div>
</div>

### parseSectionID() {#a5b4cb75e4b5f5a31d24d90dcebed12e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MIParser::parseSectionID (std::optional&lt; <a href="/web-llvm/docs/api/structs/llvm/mbbsectionid">MBBSectionID</a> &gt; &amp; SID)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 512 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp">MIParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/structs/llvm/mbbsectionid/#a2cbbe04f568b5890eeb2b58c0cbf6d71">llvm::MBBSectionID::ColdSectionID</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/symbolrecordmapping-cpp/#a9cdf893c7d17e47fa1ed8bebf92a5da4">error</a>, <a href="/web-llvm/docs/api/structs/llvm/mbbsectionid/#a27940a53407c67036b8292fa9bf4721d">llvm::MBBSectionID::ExceptionSectionID</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6ac47c420adaca267e079109b3d4dca293">llvm::MIToken::IntegerLiteral</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6aff7ad41fba511dad3cf8ed9165271232">llvm::MIToken::kw_bbsections</a> and <a href="#adbe0edbdba34278d011549a9e7c3d16e">lex</a>.</p>


<p>Referenced by <a href="#aee1834e01cdaec2445802850ce7e92b4">parseBasicBlockDefinition</a>.</p>

</div>
</div>

### parseShuffleMaskOperand() {#a70c970df35e9a1ebde9a6371fb8a6bc6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MIParser::parseShuffleMaskOperand (<a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; Dest)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 496 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp">MIParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a190591b275f9c74a12e9cc66e386d86c">llvm::MIToken::comma</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ab261a066a6f63f72c705a1d7a40e56de">llvm::MachineOperand::CreateShuffleMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/symbolrecordmapping-cpp/#a9cdf893c7d17e47fa1ed8bebf92a5da4">error</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a637b69dea56f804278aa50e975337e01">Int</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6ac47c420adaca267e079109b3d4dca293">llvm::MIToken::IntegerLiteral</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6af964d58ac7722e837d761dbff9598883">llvm::MIToken::kw_shufflemask</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6af21fe671190c392445d0b4f6809403da">llvm::MIToken::kw_undef</a>, <a href="#adbe0edbdba34278d011549a9e7c3d16e">lex</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6aa19f9b1b5cf9928ce12e0dab92099c10">llvm::MIToken::lparen</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a> and <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6af002c0577ea092d33ec2e5268ff4201e">llvm::MIToken::rparen</a>.</p>


<p>Referenced by <a href="#af7b186f0f87ad315cbd814abed5dab72">parseMachineOperand</a>.</p>

</div>
</div>

### parseStackFrameIndex() {#a453f3120ed4a899975ffac8bdda7417a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MIParser::parseStackFrameIndex (int &amp; FI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 472 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp">MIParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/symbolrecordmapping-cpp/#a9cdf893c7d17e47fa1ed8bebf92a5da4">error</a>, <a href="#adbe0edbdba34278d011549a9e7c3d16e">lex</a> and <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a02ea7320381cc7361f5f3530892eb3e1">llvm::MIToken::StackObject</a>.</p>


<p>Referenced by <a href="#a58471cf0d31837efb05a35712ce9ad7c">parseMemoryPseudoSourceValue</a>, <a href="#a6f18959fe1cc20cb62b5a169b61c0bb8">parseStackObjectOperand</a> and <a href="#af08d4f3585dbd246421362d8e6460e4a">parseStandaloneStackObject</a>.</p>

</div>
</div>

### parseStackObjectOperand() {#a6f18959fe1cc20cb62b5a169b61c0bb8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MIParser::parseStackObjectOperand (<a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; Dest)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 473 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp">MIParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#afda3f1971b3e44709267be818ffd3035">llvm::MachineOperand::CreateFI</a> and <a href="#a453f3120ed4a899975ffac8bdda7417a">parseStackFrameIndex</a>.</p>


<p>Referenced by <a href="#af7b186f0f87ad315cbd814abed5dab72">parseMachineOperand</a>.</p>

</div>
</div>

### parseStandaloneMBB() {#a8b6fb16ad1a073527ca219f25f242b9d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MIParser::parseStandaloneMBB (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *&amp; MBB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 434 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp">MIParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a9451d22efb0e7385c6b73ca7799b1d70">llvm::MIToken::Eof</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/symbolrecordmapping-cpp/#a9cdf893c7d17e47fa1ed8bebf92a5da4">error</a>, <a href="#adbe0edbdba34278d011549a9e7c3d16e">lex</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a3f519613749a65e91b6dfe908aaf554e">llvm::MIToken::MachineBasicBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a> and <a href="#a4324e2adebdc2aaca8ead3ed32de1667">parseMBBReference</a>.</p>

</div>
</div>

### parseStandaloneMDNode() {#ad9870bb0f0c1501dfa004566dbd5194b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MIParser::parseStandaloneMDNode (<a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> *&amp; Node)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 439 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp">MIParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a9451d22efb0e7385c6b73ca7799b1d70">llvm::MIToken::Eof</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/symbolrecordmapping-cpp/#a9cdf893c7d17e47fa1ed8bebf92a5da4">error</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6ae9b7e1e40ac9f787f763b636479f00d6">llvm::MIToken::exclaim</a>, <a href="#adbe0edbdba34278d011549a9e7c3d16e">lex</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a44e938a244ddbf730937be8d17272feb">llvm::MIToken::md_diexpr</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6abc4fb36ac618caf2a11cb6c74f598d07">llvm::MIToken::md_dilocation</a>, <a href="#a8ab2f664870f2d3c5f2036875672cf2a">parseDIExpression</a>, <a href="#a3ac7a622a7557191953d14a7961a79fa">parseDILocation</a> and <a href="#a47550df64460e1d79194f04e687fd4bc">parseMDNode</a>.</p>

</div>
</div>

### parseStandaloneNamedRegister() {#afbc0c7f10ce30d72b70bd6982596e10b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MIParser::parseStandaloneNamedRegister (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &amp; Reg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 435 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp">MIParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a9451d22efb0e7385c6b73ca7799b1d70">llvm::MIToken::Eof</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/symbolrecordmapping-cpp/#a9cdf893c7d17e47fa1ed8bebf92a5da4">error</a>, <a href="#adbe0edbdba34278d011549a9e7c3d16e">lex</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6ada1e13f84d573245c05460a99ef47607">llvm::MIToken::NamedRegister</a> and <a href="#a1e4a55a09d735c80c50bbb0bc0f93158">parseNamedRegister</a>.</p>

</div>
</div>

### parseStandaloneRegister() {#a0e113b6be43fae44b91eaac633118ba8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MIParser::parseStandaloneRegister (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &amp; Reg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 437 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp">MIParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a9451d22efb0e7385c6b73ca7799b1d70">llvm::MIToken::Eof</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/symbolrecordmapping-cpp/#a9cdf893c7d17e47fa1ed8bebf92a5da4">error</a>, <a href="#adbe0edbdba34278d011549a9e7c3d16e">lex</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6ada1e13f84d573245c05460a99ef47607">llvm::MIToken::NamedRegister</a>, <a href="#af24785732d415fd376c19df162d3d1aa">parseRegister</a> and <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6aad89006e07a1b4b432094251dafeb05e">llvm::MIToken::VirtualRegister</a>.</p>

</div>
</div>

### parseStandaloneStackObject() {#af08d4f3585dbd246421362d8e6460e4a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MIParser::parseStandaloneStackObject (int &amp; FI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 438 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp">MIParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a9451d22efb0e7385c6b73ca7799b1d70">llvm::MIToken::Eof</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/symbolrecordmapping-cpp/#a9cdf893c7d17e47fa1ed8bebf92a5da4">error</a>, <a href="#adbe0edbdba34278d011549a9e7c3d16e">lex</a>, <a href="#a453f3120ed4a899975ffac8bdda7417a">parseStackFrameIndex</a> and <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a02ea7320381cc7361f5f3530892eb3e1">llvm::MIToken::StackObject</a>.</p>

</div>
</div>

### parseStandaloneVirtualRegister() {#ab9db1ce7c4830ea5a0c54b0d843b5363}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MIParser::parseStandaloneVirtualRegister (<a href="/web-llvm/docs/api/structs/llvm/vreginfo">VRegInfo</a> *&amp; Info)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 436 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp">MIParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a9451d22efb0e7385c6b73ca7799b1d70">llvm::MIToken::Eof</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/symbolrecordmapping-cpp/#a9cdf893c7d17e47fa1ed8bebf92a5da4">error</a>, <a href="#adbe0edbdba34278d011549a9e7c3d16e">lex</a>, <a href="#a408291205fdd1fc5034490d72966c6ab">parseVirtualRegister</a> and <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6aad89006e07a1b4b432094251dafeb05e">llvm::MIToken::VirtualRegister</a>.</p>

</div>
</div>

### parseSubRegisterIndex() {#a68d5b2d8a31ebf3554d265357f1baf28}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MIParser::parseSubRegisterIndex (unsigned &amp; SubReg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 458 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp">MIParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a73902454a32cbf1ad7ceac917df4bbd4">llvm::MIToken::dot</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/symbolrecordmapping-cpp/#a9cdf893c7d17e47fa1ed8bebf92a5da4">error</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a97b4377341cd7c584adcaa160aad0a02">llvm::MIToken::Identifier</a>, <a href="#adbe0edbdba34278d011549a9e7c3d16e">lex</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#a92a6b0a9b7228d190b0a7d8ae3ef03c7">SubReg</a>.</p>


<p>Referenced by <a href="#ad4d22d791beba2d17644bc14544e3877">parseRegisterOperand</a>.</p>

</div>
</div>

### parseSubRegisterIndexOperand() {#a0c8d28ec07b076990dfad603aa041f9b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MIParser::parseSubRegisterIndexOperand (<a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; Dest)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 479 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp">MIParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ab09679b541a6ba1219b3602569847364">llvm::MachineOperand::CreateImm</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/symbolrecordmapping-cpp/#a9cdf893c7d17e47fa1ed8bebf92a5da4">error</a>, <a href="#adbe0edbdba34278d011549a9e7c3d16e">lex</a> and <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a2d9fa763e09f66fdd3f9f6a94c1b58e2">llvm::MIToken::SubRegisterIndex</a>.</p>


<p>Referenced by <a href="#af7b186f0f87ad315cbd814abed5dab72">parseMachineOperand</a>.</p>

</div>
</div>

### parseTargetImmMnemonic() {#af77884023f62584e3a1c2daad3d643c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MIParser::parseTargetImmMnemonic (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned OpCode, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned OpIdx, <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; Dest, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mirformatter">MIRFormatter</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 527 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp">MIParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a190591b275f9c74a12e9cc66e386d86c">llvm::MIToken::comma</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ab09679b541a6ba1219b3602569847364">llvm::MachineOperand::CreateImm</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a73902454a32cbf1ad7ceac917df4bbd4">llvm::MIToken::dot</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a97b4377341cd7c584adcaa160aad0a02">llvm::MIToken::Identifier</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6ac47c420adaca267e079109b3d4dca293">llvm::MIToken::IntegerLiteral</a> and <a href="#adbe0edbdba34278d011549a9e7c3d16e">lex</a>.</p>


<p>Referenced by <a href="#af7b186f0f87ad315cbd814abed5dab72">parseMachineOperand</a>.</p>

</div>
</div>

### parseTargetIndexOperand() {#a6273fafa595d2e1f8940595b5dccc8dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MIParser::parseTargetIndexOperand (<a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; Dest)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 497 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp">MIParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#af3137f95a28140bba664c03c2f350870">llvm::MachineOperand::CreateTargetIndex</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/symbolrecordmapping-cpp/#a9cdf893c7d17e47fa1ed8bebf92a5da4">error</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a97b4377341cd7c584adcaa160aad0a02">llvm::MIToken::Identifier</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6aa260bb514add2a91dc5689d2e3d0097b">llvm::MIToken::kw_target_index</a>, <a href="#adbe0edbdba34278d011549a9e7c3d16e">lex</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6aa19f9b1b5cf9928ce12e0dab92099c10">llvm::MIToken::lparen</a>, <a href="#a13fa87aa1554fb342fde9c3f9cac14b8">parseOperandsOffset</a> and <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6af002c0577ea092d33ec2e5268ff4201e">llvm::MIToken::rparen</a>.</p>


<p>Referenced by <a href="#af7b186f0f87ad315cbd814abed5dab72">parseMachineOperand</a>.</p>

</div>
</div>

### parseTypedImmediateOperand() {#a96f48f9a5690ef01b9d2574472e1f7e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MIParser::parseTypedImmediateOperand (<a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; Dest)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 468 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp">MIParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a0d10fe510ced2849a8074fe81e5d04ce">llvm::all_of</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a5e7a07b4efeaec2afcb83a6551b38441">llvm::MachineOperand::CreateCImm</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a3fb2867a1e9fa36e135d9ee4dffb0167">llvm::StringRef::drop_front</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/symbolrecordmapping-cpp/#a9cdf893c7d17e47fa1ed8bebf92a5da4">error</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a61364ca3a5ff90fb2aa0d5a371fd43f7">llvm::StringRef::front</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a97b4377341cd7c584adcaa160aad0a02">llvm::MIToken::Identifier</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6ac47c420adaca267e079109b3d4dca293">llvm::MIToken::IntegerLiteral</a>, <a href="#adbe0edbdba34278d011549a9e7c3d16e">lex</a>, <a href="#a08b018143e68b6cc36ab362d8b3b2626">parseIRConstant</a> and <a href="/web-llvm/docs/api/classes/llvm/stringref/#a5db9240c74644c67759dd0f901fc3c7d">llvm::StringRef::size</a>.</p>


<p>Referenced by <a href="#af7b186f0f87ad315cbd814abed5dab72">parseMachineOperand</a>.</p>

</div>
</div>

### parseVirtualRegister() {#a408291205fdd1fc5034490d72966c6ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MIParser::parseVirtualRegister (<a href="/web-llvm/docs/api/structs/llvm/vreginfo">VRegInfo</a> *&amp; Info)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 453 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp">MIParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6a4bb75c93c34ebe814b2500733ed2cbe2">llvm::MIToken::NamedVirtualRegister</a>, <a href="#a451417fceac11225426e2b816a7775e8">parseNamedVirtualRegister</a> and <a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6aad89006e07a1b4b432094251dafeb05e">llvm::MIToken::VirtualRegister</a>.</p>


<p>Referenced by <a href="#af24785732d415fd376c19df162d3d1aa">parseRegister</a> and <a href="#ab9db1ce7c4830ea5a0c54b0d843b5363">parseStandaloneVirtualRegister</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### assignRegisterTies() {#ad314b3e97628d7a74f4929b1be954d97}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MIParser::assignRegisterTies (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/anonymous-miparser-cpp-/parsedmachineoperand">ParsedMachineOperand</a> &gt; Operands)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 557 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp">MIParser.cpp</a>.</p>

</div>
</div>

### consumeIfPresent() {#a1694d1784a89868a65e559ba8a0302a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MIParser::consumeIfPresent (<a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6">MIToken::TokenKind</a> TokenKind)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If the current token is of the given kind, consume it and return true.</p>


<p>Otherwise return false.</p>


<p>Definition at line 553 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp">MIParser.cpp</a>.</p>

</div>
</div>

### expectAndConsume() {#a096f43c3f11baeac11d0cf21e019acac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MIParser::expectAndConsume (<a href="/web-llvm/docs/api/structs/llvm/mitoken/#a826fc5728ce5ed55eef1807bf32e02a6">MIToken::TokenKind</a> TokenKind)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If the current token is of the given kind, consume it and return false.</p>


<p>Otherwise report an error and return true.</p>


<p>Definition at line 549 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp">MIParser.cpp</a>.</p>

</div>
</div>

### getHexUint() {#a70415e948882e9534bf839c8b1925d96}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MIParser::getHexUint (<a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; Result)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Convert the hexadecimal literal in the current token into an unsigned <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> with a minimum bitwidth required to represent the value.</p>


<p>Return true if the literal does not represent an integer value.</p>


<p>Definition at line 545 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp">MIParser.cpp</a>.</p>

</div>
</div>

### getIRBlock() {#a7a91c16f361711bd97758304353c596b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const BasicBlock * MIParser::getIRBlock (unsigned Slot)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 563 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp">MIParser.cpp</a>.</p>

</div>
</div>

### getIRBlock() {#a560395feb66a406d77384c376b6f0ea9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const BasicBlock * MIParser::getIRBlock (unsigned Slot, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 564 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp">MIParser.cpp</a>.</p>

</div>
</div>

### getOrCreateMCSymbol() {#a3633e9190743c142820cc19cd5cc417c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSymbol * MIParser::getOrCreateMCSymbol (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get or create an <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> for a given name.</p>

<p>Definition at line 567 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp">MIParser.cpp</a>.</p>

</div>
</div>

### getUint64() {#ad224457a99939f65fd9ad6f7ef129334}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MIParser::getUint64 (uint64_t &amp; Result)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Convert the integer literal in the current token into an uint64.</p>


<p>Return true if an error occurred.</p>


<p>Definition at line 539 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp">MIParser.cpp</a>.</p>

</div>
</div>

### getUnsigned() {#a05a86ae27331f2e229826bd40cfecc9c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MIParser::getUnsigned (unsigned &amp; Result)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Convert the integer literal in the current token into an unsigned integer.</p>


<p>Return true if an error occurred.</p>


<p>Definition at line 534 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp">MIParser.cpp</a>.</p>

</div>
</div>

### mapSMLoc() {#a8b35addf88e26efa03720773abd2113c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SMLoc MIParser::mapSMLoc (<a href="/web-llvm/docs/api/classes/llvm/stringref/#a20d37563688a61a452fb26e317e37308">StringRef::iterator</a> Loc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Map the location in the MI string to the corresponding location specified in <span class="doxyComputerOutput">SourceRange</span>.</p>

<p>Definition at line 575 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp">MIParser.cpp</a>.</p>

</div>
</div>

### parseInstruction() {#a213dfccee7f26ba6e7759232d60152b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MIParser::parseInstruction (unsigned &amp; OpCode, unsigned &amp; Flags)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 555 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp">MIParser.cpp</a>.</p>

</div>
</div>

### parseStringConstant() {#a42774580ce9a9f5a1822293df0be87d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MIParser::parseStringConstant (std::string &amp; Result)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseStringConstant ::= StringConstant</p>

<p>Definition at line 571 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp">MIParser.cpp</a>.</p>

</div>
</div>

### verifyImplicitOperands() {#ab88117b3b0345f449d884dcd05afa468}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MIParser::verifyImplicitOperands (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/anonymous-miparser-cpp-/parsedmachineoperand">ParsedMachineOperand</a> &gt; Operands, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinstrdesc">MCInstrDesc</a> &amp; MCID)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 560 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp">MIParser.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### CurrentSource {#a770e1934fde00c797055db0b03aa4fbb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef anonymous{MIParser.cpp}::MIParser::CurrentSource</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 403 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp">MIParser.cpp</a>.</p>

</div>
</div>

### Error {#adcb3d37670fef132f558c142643ac7fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SMDiagnostic&amp; anonymous{MIParser.cpp}::MIParser::Error</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 402 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp">MIParser.cpp</a>.</p>

</div>
</div>

### MF {#a9dafd0d5ed8d166dc00b157f17b5b50b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineFunction&amp; anonymous{MIParser.cpp}::MIParser::MF</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 401 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp">MIParser.cpp</a>.</p>

</div>
</div>

### PFS {#a6d2ad090a11ab6fe2b7caf0b6993132e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PerFunctionMIParsingState&amp; anonymous{MIParser.cpp}::MIParser::PFS</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 406 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp">MIParser.cpp</a>.</p>

</div>
</div>

### Slots2BasicBlocks {#aeeab9f500caa3522d5936cc68fff9621}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;unsigned, const BasicBlock *&gt; anonymous{MIParser.cpp}::MIParser::Slots2BasicBlocks</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Maps from slot numbers to function's unnamed basic blocks.</p>

<p>Definition at line 408 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp">MIParser.cpp</a>.</p>

</div>
</div>

### Source {#a51c76be2966fe21ad27b383cac3e9eee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef anonymous{MIParser.cpp}::MIParser::Source</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 403 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp">MIParser.cpp</a>.</p>

</div>
</div>

### SourceRange {#a292a9d3b6c1d9eafdff3bb0bcf366363}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SMRange anonymous{MIParser.cpp}::MIParser::SourceRange</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 404 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp">MIParser.cpp</a>.</p>

</div>
</div>

### Token {#a650ccba2efd678b6d865edde765ee880}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MIToken anonymous{MIParser.cpp}::MIParser::Token</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 405 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp">MIParser.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp">MIParser.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>

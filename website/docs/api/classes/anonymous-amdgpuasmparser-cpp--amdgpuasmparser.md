---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `AMDGPUAsmParser` Class



## Declaration

<div class="doxyDeclaration">
class anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser { ... }
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mctargetasmparser">MCTargetAsmParser</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/mctargetasmparser">MCTargetAsmParser</a> - Generic interface to target specific assembly parsers. <a href="/web-llvm/docs/api/classes/llvm/mctargetasmparser/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcasmparser">MCAsmParser</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a47a14d2c92e97f56f678c222b4b08fae">Parser</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a47bc6785f1a651e9d4349eb6c8317a19">ForcedEncodingSize</a> = 0</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b6b6add9ac0f36dd827785d07ea6e5e">ForcedDPP</a> = false</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8540eac5fbf14fbd632448ce5edfb87c">ForcedSDWA</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/kernelscopeinfo">KernelScopeInfo</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a94983992fec14119c86f87ea3d379c18">KernelScope</a></td>
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

## Auto-generated Match Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">OperandMode { <a href="#a5108ba4d1e0aaaf1c45f0694b21c482b">...</a> }</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad427f76801ceb008e1d15f59313cff3d">OptionalImmIndexMap</a> = std::map&lt; <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#aac6196abacab3897ea9874e72d3db8fc">AMDGPUOperand::ImmTy</a>, unsigned &gt;</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a81457c117babd6d9e5304f33e74819">createConstantSymbol</a> (StringRef Id, int64_t Val)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>} <a href="#a9a81457c117babd6d9e5304f33e74819">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a543505c1bc44ee2792883d40ed5d18ef">ParseAsAbsoluteExpression</a> (uint32_t &amp;Ret)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb6d098a03fdc973b72c051df5841436">OutOfRangeError</a> (SMRange Range)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a117255be5807c86dcd89efe6e9467eec">calculateGPRBlocks</a> (const FeatureBitset &amp;Features, const MCExpr *VCCUsed, const MCExpr *FlatScrUsed, bool XNACKUsed, std::optional&lt; bool &gt; EnableWavefrontSize32, const MCExpr *NextFreeVGPR, SMRange VGPRRange, const MCExpr *NextFreeSGPR, SMRange SGPRRange, const MCExpr *&amp;VGPRBlocks, const MCExpr *&amp;SGPRBlocks)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Calculate VGPR/SGPR blocks required for given target, reserved registers, and user-specified NextFreeXGPR values. <a href="#a117255be5807c86dcd89efe6e9467eec">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8cedb6297d77e9823854e583e6e0700b">ParseDirectiveAMDGCNTarget</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9f6979dab815bd0a32f56617904bdc56">ParseDirectiveAMDHSACodeObjectVersion</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab55ae23753363847aa507ada0955569b">ParseDirectiveAMDHSAKernel</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a158cd152420a04034bd0835be80ea0ae">ParseAMDKernelCodeTValue</a> (StringRef ID, AMDGPUMCKernelCodeT &amp;Header)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aafc61c13bff045c10435ba7411983d2c">ParseDirectiveAMDKernelCodeT</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae4218404039ac7293af07cd701386ccd">subtargetHasRegister</a> (const MCRegisterInfo &amp;MRI, MCRegister Reg)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa8fc15510cd8a3f435a37295b5caef3d">ParseDirectiveAMDGPUHsaKernel</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1cc06bfe344c78019ea74a903f757579">ParseDirectiveISAVersion</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af971baeb22f5ef72ac2ee7c92cc2387e">ParseDirectiveHSAMetadata</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa1305df25fb331acfb073c2e18e66034">ParseDirectivePALMetadataBegin</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parse the assembler directive for new MsgPack-format PAL metadata. <a href="#aa1305df25fb331acfb073c2e18e66034">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af2c0f30c3fa5d4cb3ef52f26a7088105">ParseDirectivePALMetadata</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parse the assembler directive for old linear-format PAL metadata. <a href="#af2c0f30c3fa5d4cb3ef52f26a7088105">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9d2bdcef97c8e16680039b0a5e73735e">ParseDirectiveAMDGPULDS</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ParseDirectiveAMDGPULDS ::= .amdgpu_lds identifier ',' size_expression [',' align_expression]. <a href="#a9d2bdcef97c8e16680039b0a5e73735e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a435a9a5fba34d91b92e3ccecd259433f">ParseToEndDirective</a> (const char *AssemblerDirectiveBegin, const char *AssemblerDirectiveEnd, std::string &amp;CollectString)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Common code to parse out a block of text (typically YAML) between start and end directives. <a href="#a435a9a5fba34d91b92e3ccecd259433f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a234441b9c1bbcdbc500127a033c2e653">AddNextRegisterToList</a> (MCRegister &amp;Reg, unsigned &amp;RegWidth, RegisterKind RegKind, MCRegister Reg1, SMLoc Loc)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad5507f1367d663ce52ade9dda3d8c3be">ParseAMDGPURegister</a> (RegisterKind &amp;RegKind, MCRegister &amp;Reg, unsigned &amp;RegNum, unsigned &amp;RegWidth, bool RestoreOnFailure=false)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa31d05b9b3e2274c1c609e9068f485ef">ParseAMDGPURegister</a> (RegisterKind &amp;RegKind, MCRegister &amp;Reg, unsigned &amp;RegNum, unsigned &amp;RegWidth, SmallVectorImpl&lt; AsmToken &gt; &amp;Tokens)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a710d213a3e716462d40a0fb6228406d2">ParseRegularReg</a> (RegisterKind &amp;RegKind, unsigned &amp;RegNum, unsigned &amp;RegWidth, SmallVectorImpl&lt; AsmToken &gt; &amp;Tokens)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a92e8ee1aa2f66e7579183a0acbb40a4f">ParseSpecialReg</a> (RegisterKind &amp;RegKind, unsigned &amp;RegNum, unsigned &amp;RegWidth, SmallVectorImpl&lt; AsmToken &gt; &amp;Tokens)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a34b0423eea63c2a35ae31a252e805643">ParseRegList</a> (RegisterKind &amp;RegKind, unsigned &amp;RegNum, unsigned &amp;RegWidth, SmallVectorImpl&lt; AsmToken &gt; &amp;Tokens)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad8f9c1daf350802e97afa90a45e80998">ParseRegRange</a> (unsigned &amp;Num, unsigned &amp;Width)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a868886caf54ce07e4bfc471b9076032e">getRegularReg</a> (RegisterKind RegKind, unsigned RegNum, unsigned SubReg, unsigned RegWidth, SMLoc Loc)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae6bbe25af68d69ac51381e350fc82ea8">isRegister</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1008e28f0bfda60a8f55da9905c7907d">isRegister</a> (const AsmToken &amp;Token, const AsmToken &amp;NextToken) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a138d6dcd6fc282c474018d7c4c0fbf7f">getGprCountSymbolName</a> (RegisterKind RegKind)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ddb2dcf2b1a93866457d7118786af95">initializeGprCountSymbol</a> (RegisterKind RegKind)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aca9931d36195af5ef3e9c4c339666b9d">updateGprCountSymbols</a> (RegisterKind RegKind, unsigned DwordRegIndex, unsigned RegWidth)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a23a48b6961d6d2b1cece40c8bc0f305e">cvtMubufImpl</a> (MCInst &amp;Inst, const OperandVector &amp;Operands, bool IsAtomic)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/parsestatus">ParseStatus</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a70e1d5fd1c994109d1ac7be165c04a11">parseStructuredOpFields</a> (ArrayRef&lt; StructuredOpField * &gt; Fields)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c392b642016cbf17d5c5a94df3d0dc3">validateStructuredOpFields</a> (ArrayRef&lt; const StructuredOpField * &gt; Fields)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6eff51bcc1e84587c8223c6acbdff0f7">parseSendMsgBody</a> (OperandInfoTy &amp;Msg, OperandInfoTy &amp;Op, OperandInfoTy &amp;Stream)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a63fd81326007702b0c1ae4a305370b31">validateSendMsg</a> (const OperandInfoTy &amp;Msg, const OperandInfoTy &amp;Op, const OperandInfoTy &amp;Stream)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/parsestatus">ParseStatus</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c129416da237e2889bd3b364af5580c">parseHwregFunc</a> (OperandInfoTy &amp;HwReg, OperandInfoTy &amp;Offset, OperandInfoTy &amp;Width)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a61fbafda24977099a2fa826027211852">getFlatOffsetLoc</a> (const OperandVector &amp;Operands) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb91ce4e02e6f75a5359ac17ad9b88a5">getSMEMOffsetLoc</a> (const OperandVector &amp;Operands) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa036d1a736a687d8ed704456053f5895">getBLGPLoc</a> (const OperandVector &amp;Operands) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ed62187e701fe3c99befc24d1ce92da">getOperandLoc</a> (std::function&lt; bool(const AMDGPUOperand &amp;)&gt; Test, const OperandVector &amp;Operands) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a66dae450bf482278ab7a3b6cedfdfda9">getImmLoc</a> (AMDGPUOperand::ImmTy Type, const OperandVector &amp;Operands) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a756af86a325bfcc762d5b49a5cd41a46">getRegLoc</a> (MCRegister Reg, const OperandVector &amp;Operands) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0a41ae0a6ba8f96f1992efac0ae0f736">getLitLoc</a> (const OperandVector &amp;Operands, bool SearchMandatoryLiterals=false) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a61d60a81d7818a2d339c950b9ae07164">getMandatoryLitLoc</a> (const OperandVector &amp;Operands) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1f3e1aaa5aa7fa68aa2b8283756b7c2c">getConstLoc</a> (const OperandVector &amp;Operands) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad8ac0688695eefd339e10c534671b89f">getInstLoc</a> (const OperandVector &amp;Operands) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0982a69137f512538f3ba9ed0a51cebe">validateInstruction</a> (const MCInst &amp;Inst, const SMLoc &amp;IDLoc, const OperandVector &amp;Operands)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5c9a80ca3f27cba8a468d14339c65c4a">validateOffset</a> (const MCInst &amp;Inst, const OperandVector &amp;Operands)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a80ae4d00af28940cd6cd856d8eff1ae4">validateFlatOffset</a> (const MCInst &amp;Inst, const OperandVector &amp;Operands)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a62a490fe5c5e8934cb074a3dc889468d">validateSMEMOffset</a> (const MCInst &amp;Inst, const OperandVector &amp;Operands)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af50191dc42ece6518d0e562efcd79307">validateSOPLiteral</a> (const MCInst &amp;Inst) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a55c2d4dc3eb1d01d884432972293a34f">validateConstantBusLimitations</a> (const MCInst &amp;Inst, const OperandVector &amp;Operands)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae7ccbcffee0b1de875f762c116fae81c">validateVOPDRegBankConstraints</a> (const MCInst &amp;Inst, const OperandVector &amp;Operands)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a460fc7b33c1cd769f5cf2be6014f92da">validateIntClampSupported</a> (const MCInst &amp;Inst)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a01b9b3e92cea528f0e617c6d35806b1c">validateMIMGAtomicDMask</a> (const MCInst &amp;Inst)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a118483cae9e0c617479c8169cd5f0449">validateMIMGGatherDMask</a> (const MCInst &amp;Inst)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e5970da7a566c9f954fb41e33ec9cef">validateMovrels</a> (const MCInst &amp;Inst, const OperandVector &amp;Operands)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f5d348d6e01265ce9169bae68af40c0">validateMIMGDataSize</a> (const MCInst &amp;Inst, const SMLoc &amp;IDLoc)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae92a3c3e0e6e1962a283a5cff528fa34">validateMIMGAddrSize</a> (const MCInst &amp;Inst, const SMLoc &amp;IDLoc)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#affe8e0e1234867fb44eecab893d47cf7">validateMIMGD16</a> (const MCInst &amp;Inst)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a59ddcdb4ebb1a6b8a615c73b94311554">validateMIMGDim</a> (const MCInst &amp;Inst, const OperandVector &amp;Operands)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af2cfac42d0b04b8e5e78972ac8b887d4">validateMIMGMSAA</a> (const MCInst &amp;Inst)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af95d2ab489c6c3a844f22f4db73982e1">validateOpSel</a> (const MCInst &amp;Inst)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2f32aaa6de7997a91317ed0a47f6a6be">validateNeg</a> (const MCInst &amp;Inst, int OpName)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7cd6fc86c696d22315362d3540a39655">validateDPP</a> (const MCInst &amp;Inst, const OperandVector &amp;Operands)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab55af519108c29ba51bd428352d55087">validateVccOperand</a> (MCRegister Reg) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a013521c9b7a057eba196a402782881f1">validateVOPLiteral</a> (const MCInst &amp;Inst, const OperandVector &amp;Operands)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6dfafe167fd7a6e5b0f864cf9a51632b">validateMAIAccWrite</a> (const MCInst &amp;Inst, const OperandVector &amp;Operands)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a44bdf174034a1b8b8f5f97b38b2ff190">validateMAISrc2</a> (const MCInst &amp;Inst, const OperandVector &amp;Operands)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5137963d3d21a7f10f8df31a032ca187">validateMFMA</a> (const MCInst &amp;Inst, const OperandVector &amp;Operands)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9d5c58effe43809a37dfd1713cf9b55e">validateAGPRLdSt</a> (const MCInst &amp;Inst) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6de0e019aaab9c666d02d2eb56f058a8">validateVGPRAlign</a> (const MCInst &amp;Inst) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7fa301acaec42118c60e6c805036eacc">validateBLGP</a> (const MCInst &amp;Inst, const OperandVector &amp;Operands)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b631f93e635247a8c50b181c51e2ff3">validateDS</a> (const MCInst &amp;Inst, const OperandVector &amp;Operands)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a39fda554e35a9d19e1b53d7563ba1235">validateGWS</a> (const MCInst &amp;Inst, const OperandVector &amp;Operands)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab6676014c1baba88d4625c34f9803ee4">validateDivScale</a> (const MCInst &amp;Inst)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af909474c7595106b43172a1e21bca078">validateWaitCnt</a> (const MCInst &amp;Inst, const OperandVector &amp;Operands)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a863ff5ccf09e2459e301f36989e38fc7">validateCoherencyBits</a> (const MCInst &amp;Inst, const OperandVector &amp;Operands, const SMLoc &amp;IDLoc)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2359f8c65e5c2dea22fab8c57936dd61">validateTHAndScopeBits</a> (const MCInst &amp;Inst, const OperandVector &amp;Operands, const unsigned CPol)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a51703ec9e1a3532934bda6fc6d24667d">validateTFE</a> (const MCInst &amp;Inst, const OperandVector &amp;Operands)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af9d2b066d2b7bc3c73752950674162bd">validateLdsDirect</a> (const MCInst &amp;Inst)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e2c602207905d5aca8b1a2bae459bd0">getConstantBusLimit</a> (unsigned Opcode) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa565f07572e7d84c3d779f9447d35bae">usesConstantBus</a> (const MCInst &amp;Inst, unsigned OpIdx)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a508f82e8c2f272d6702a6cc80b19ad89">isInlineConstant</a> (const MCInst &amp;Inst, unsigned OpIdx) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a502df3adb84c617a604b07b799b44635">findImplicitSGPRReadInVOP</a> (const MCInst &amp;Inst) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7234587538030f6642812b4afd0a143a">isSupportedMnemo</a> (StringRef Mnemo, const FeatureBitset &amp;FBS)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a44f9030bb4b867ff48c812c45587f729">isSupportedMnemo</a> (StringRef Mnemo, const FeatureBitset &amp;FBS, ArrayRef&lt; unsigned &gt; Variants)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afc2f9b34dcc8d5590de76fa323c386ef">checkUnsupportedInstruction</a> (StringRef Name, const SMLoc &amp;IDLoc)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0ade8085c04ca131cd06be151b500037">isId</a> (const StringRef Id) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abdace62f83edae6890e8eb5ba67ed074">isId</a> (const AsmToken &amp;Token, const StringRef Id) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af6daa0ef9939708fdb6e42cf199d3e86">isToken</a> (const AsmToken::TokenKind Kind) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a20dfd82893fe044b468e5525572f03d0">getId</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ace26672fababa8403f7326ff663c8706">trySkipId</a> (const StringRef Id)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af3b997aa90c7f21c08a6e22d6be3442f">trySkipId</a> (const StringRef Pref, const StringRef Id)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab099ab3d47092efb4431b1ad7755d32d">trySkipId</a> (const StringRef Id, const AsmToken::TokenKind Kind)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a163031b7584edfcd1b5425ba5f25cbee">trySkipToken</a> (const AsmToken::TokenKind Kind)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a11166f8df21f7cce256a44bac5f5d47c">skipToken</a> (const AsmToken::TokenKind Kind, const StringRef ErrMsg)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7064627bb8d216d774e6e684c2121f07">parseString</a> (StringRef &amp;Val, const StringRef ErrMsg="expected a string")</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8f8abf4c919ccba2f2fe21b946e68816">parseId</a> (StringRef &amp;Val, const StringRef ErrMsg="")</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acb91b8d53082f83a6716716838f1dee1">peekTokens</a> (MutableArrayRef&lt; AsmToken &gt; Tokens)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039">AsmToken::TokenKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2923c0dd11b447eaa37ab8514d1270a2">getTokenKind</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5c37f34a36aa6bb7baad4e347a83b5e4">parseExpr</a> (int64_t &amp;Imm, StringRef Expected="")</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc850f2e5d8c879ed992414a3054025e">parseExpr</a> (OperandVector &amp;Operands)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a126bbdc17a81565362ead20965e8b6c3">getTokenStr</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/asmtoken">AsmToken</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2dbbb80441bb8ded15dad16ea3c952dd">peekToken</a> (bool ShouldSkipSpace=true)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/asmtoken">AsmToken</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a46304ba682a9e66877de380fd59db2d2">getToken</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1993a16fc362b1d6f9547b775af976c7">getLoc</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf132b7452e6dcb0ce988fb7984dc93f">lex</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a887ee9b0b1952f6adb88d8ef15c82a53">AMDGPUAsmParser</a> (const MCSubtargetInfo &amp;STI, MCAsmParser &amp;_Parser, const MCInstrInfo &amp;MII, const MCTargetOptions &amp;Options)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54492f3614b470db6344ad0f37ab6089">hasMIMG_R128</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3922545a69d102106123e763a4a31c25">hasPackedD16</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f910445c0ee081e07f20fd28f2aaad2">hasA16</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0714efbd16188fd6667055435904879d">hasG16</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8c75281cf5dd6fcdf9e2f75f70c3bb9f">hasGDS</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af6fc1eb24bc3b5beaf4a2a292ba1d759">isSI</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae8c11d76cf3216eae559553ba6cb045a">isCI</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8e77658ae7e2c85817cc9e6fb62901bf">isVI</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abedd2529418cdf49b008a6c05bf3baec">isGFX9</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa4556f85d06de11c2b68e6b4b781e7ab">isGFX90A</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2655a995ec2394a6f0b91e04782f37f2">isGFX940</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa58939d2807dd46c0c31c68ed255b59b">isGFX9Plus</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a82bb4dbeafcda7b3cf1e8f26b3cfbd">isGFX10</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a60199205d0327ba1bec2eb9aaac9f3b3">isGFX10Plus</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae7af5638a45b8a78d1ac005bcb225280">isGFX11</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a93fd6449c3f63d76ff63b7231aec9269">isGFX11Plus</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab6c0ad5500b6cf0018b49d5d9bc477f5">isGFX12</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9d0aa89a1f031ab50a8126419a8191be">isGFX12Plus</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8d868e94e982ab01119ccdfd484a07ee">isGFX10_AEncoding</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3bfb807b985518a3727b9c1dee859f46">isGFX10_BEncoding</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0e929744420b8548ed003f174cd3f3a0">hasInv2PiInlineImm</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a958902b2e72c873ece47b4c7fd455668">hasFlatOffsets</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a79c2d889df9ef0eb5ce622c66a8d7010">hasArchitectedFlatScratch</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a993582fe0bc1fb493cd48aead4b11c16">hasSGPR102_SGPR103</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd1547d9873dcf550d8e370a51a9c37e">hasSGPR104_SGPR105</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae0afa06cf1f3b2ab727dbbc42a20e9c6">hasIntClamp</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab7856e68e06d844222886334c4c9fd4d">hasPartialNSAEncoding</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa879368e13ab22a5a62cd72fbb1768c9">getNSAMaxSize</a> (bool HasSampler=false) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c20880d48555851fafbfc418cecc7c1">getMaxNumUserSGPRs</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae4435ea1cd4a7f8c793cfb51552eead4">hasKernargPreload</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/amdgputargetstreamer">AMDGPUTargetStreamer</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a311f125284969ccb357f273b49a77f9a">getTargetStreamer</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcregisterinfo">MCRegisterInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a75ed4572cff3fae7911dba55aba309bf">getMRI</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo">MCInstrInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9f04d08c1bd449da7d97c0c66621eb97">getMII</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/featurebitset">FeatureBitset</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a16aaca0a854369fe286a9d8bb3372a">getFeatureBits</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a68e05bfbdc8f741cbe98a89178b5b92a">setForcedEncodingSize</a> (unsigned Size)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd348be108cbdbac20658db6d4bd1a1c">setForcedDPP</a> (bool ForceDPP_)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afcafade6789b141859f6a8de96f5c440">setForcedSDWA</a> (bool ForceSDWA_)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8c474bd3ccb2bda9a89f31fb3d7bf1cb">getForcedEncodingSize</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1857461798003294368b95288123a76a">isForcedVOP3</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aae673d780d4f7a887dcdb07e93a14bfe">isForcedDPP</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2fdb1206f7410fc6fce1780b2573edbf">isForcedSDWA</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a53aaf0a7f96759d2983685f8e8a35220">getMatchedVariants</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a10f0d2b118c2bae2632b32ffdd98e376">getMatchedVariantName</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand">AMDGPUOperand</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe4d54f7147e2f219afa02529b48a0d0">parseRegister</a> (bool RestoreOnFailure=false)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a911c9b67b1375d8bc5a84dc2796614b0">ParseRegister</a> (MCRegister &amp;RegNo, SMLoc &amp;StartLoc, SMLoc &amp;EndLoc, bool RestoreOnFailure)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4477cf7edf08ac705e5805c530ff0486">parseRegister</a> (MCRegister &amp;Reg, SMLoc &amp;StartLoc, SMLoc &amp;EndLoc) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/parsestatus">ParseStatus</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5e29118c0f500ee77e2601b120205f54">tryParseRegister</a> (MCRegister &amp;Reg, SMLoc &amp;StartLoc, SMLoc &amp;EndLoc) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>tryParseRegister - parse one register if possible <a href="#a5e29118c0f500ee77e2601b120205f54">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae55539b0211e9bc98123340231aa6902">checkTargetMatchPredicate</a> (MCInst &amp;Inst) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>checkTargetMatchPredicate - Validate the instruction match against any complex target predicates not expressible via match classes. <a href="#ae55539b0211e9bc98123340231aa6902">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a04ee19cd4568c1352a7d3fce29933cc1">validateTargetOperandClass</a> (MCParsedAsmOperand &amp;Op, unsigned Kind) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Allow a target to add special case operand matching for things that tblgen doesn't/can't handle effectively. <a href="#a04ee19cd4568c1352a7d3fce29933cc1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6bffa32d06d1516ee01e79b5a250c72e">matchAndEmitInstruction</a> (SMLoc IDLoc, unsigned &amp;Opcode, OperandVector &amp;Operands, MCStreamer &amp;Out, uint64_t &amp;ErrorInfo, bool MatchingInlineAsm) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Recognize a series of operands of a parsed instruction as an actual MCInst and emit it to the specified MCStreamer. <a href="#a6bffa32d06d1516ee01e79b5a250c72e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a52dd8abe6dc2354306df33d817dc3101">ParseDirective</a> (AsmToken DirectiveID) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ParseDirective - Parse a target specific assembler directive This method is deprecated, use 'parseDirective' instead. <a href="#a52dd8abe6dc2354306df33d817dc3101">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/parsestatus">ParseStatus</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2f6673e616e48f8b6505d19ef64eddab">parseOperand</a> (OperandVector &amp;Operands, StringRef Mnemonic, OperandMode Mode=OperandMode_Default)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade88d8ed031d487c85dcc6698f28b43f">parseMnemonicSuffix</a> (StringRef Name)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af09dfe84acccdfc6a55c91388892da8e">parseInstruction</a> (ParseInstructionInfo &amp;Info, StringRef Name, SMLoc NameLoc, OperandVector &amp;Operands) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parse one assembly instruction. <a href="#af09dfe84acccdfc6a55c91388892da8e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/parsestatus">ParseStatus</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a40cae821d596ce5a10da36c3d1836dac">parseTokenOp</a> (StringRef Name, OperandVector &amp;Operands)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/parsestatus">ParseStatus</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a82b29753ac1baad9801c7217c0a97dd4">parseIntWithPrefix</a> (const char *Prefix, int64_t &amp;Int)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/parsestatus">ParseStatus</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4bbb3e5e0e2e2c935c2a911665fff611">parseIntWithPrefix</a> (const char *Prefix, OperandVector &amp;Operands, AMDGPUOperand::ImmTy ImmTy=AMDGPUOperand::ImmTyNone, std::function&lt; bool(int64_t &amp;)&gt; ConvertResult=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/parsestatus">ParseStatus</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac9d07a4881948a410fcba201eeb36480">parseOperandArrayWithPrefix</a> (const char *Prefix, OperandVector &amp;Operands, AMDGPUOperand::ImmTy ImmTy=AMDGPUOperand::ImmTyNone, bool(*ConvertResult)(int64_t &amp;)=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/parsestatus">ParseStatus</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab2ff8b8fa2100a684cea688b74d329ab">parseNamedBit</a> (StringRef Name, OperandVector &amp;Operands, AMDGPUOperand::ImmTy ImmTy=AMDGPUOperand::ImmTyNone)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac905bca0319767a6f6590aa62145c2be">getCPolKind</a> (StringRef Id, StringRef Mnemo, bool &amp;Disabling) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/parsestatus">ParseStatus</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a905978e46c9c9a277645e938f41e1876">parseCPol</a> (OperandVector &amp;Operands)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/parsestatus">ParseStatus</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1a55d776c65cd09db2546fb584a2de47">parseScope</a> (OperandVector &amp;Operands, int64_t &amp;Scope)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/parsestatus">ParseStatus</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3a4cad862e9d4dda82fe89b5a2557e97">parseTH</a> (OperandVector &amp;Operands, int64_t &amp;TH)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/parsestatus">ParseStatus</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8dbdde33e6acd3e814ee9db9b8cfef68">parseStringWithPrefix</a> (StringRef Prefix, StringRef &amp;Value, SMLoc &amp;StringLoc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/parsestatus">ParseStatus</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a066421d8538981830a93a7598a571e8f">parseStringOrIntWithPrefix</a> (OperandVector &amp;Operands, StringRef Name, ArrayRef&lt; const char * &gt; Ids, int64_t &amp;IntVal)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/parsestatus">ParseStatus</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a11669d3b022f7e99114faaf694659b89">parseStringOrIntWithPrefix</a> (OperandVector &amp;Operands, StringRef Name, ArrayRef&lt; const char * &gt; Ids, AMDGPUOperand::ImmTy Type)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3740088be499ac1b2813ea1d6904ef15">isModifier</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aae8e311d01222d265293e010df5bc7f5">isOperandModifier</a> (const AsmToken &amp;Token, const AsmToken &amp;NextToken) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a84254eeb4895568119e37386e6e1ba71">isRegOrOperandModifier</a> (const AsmToken &amp;Token, const AsmToken &amp;NextToken) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab69ace2a64f183c1e0600a4155b0a976">isNamedOperandModifier</a> (const AsmToken &amp;Token, const AsmToken &amp;NextToken) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a76b985d6b897a055389b82198509ee">isOpcodeModifierWithVal</a> (const AsmToken &amp;Token, const AsmToken &amp;NextToken) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec6bf39ecab2cbc57a7ef96190d6019e">parseSP3NegModifier</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/parsestatus">ParseStatus</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a62ccca1cd262d040e8aee057ab0d22d5">parseImm</a> (OperandVector &amp;Operands, bool HasSP3AbsModifier=false, bool HasLit=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/parsestatus">ParseStatus</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab2ca31c142db4eaa8c629f36d61339bf">parseReg</a> (OperandVector &amp;Operands)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/parsestatus">ParseStatus</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a60728802d4e08feb0abc5cc75c3eefc9">parseRegOrImm</a> (OperandVector &amp;Operands, bool HasSP3AbsMod=false, bool HasLit=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/parsestatus">ParseStatus</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a74b6654d186e55d185e29c67ebd46cc6">parseRegOrImmWithFPInputMods</a> (OperandVector &amp;Operands, bool AllowImm=true)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/parsestatus">ParseStatus</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2d208597e9458f13c660462e0d3a4a6a">parseRegOrImmWithIntInputMods</a> (OperandVector &amp;Operands, bool AllowImm=true)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/parsestatus">ParseStatus</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a21f740d984294cfbcc067eab247ed24d">parseRegWithFPInputMods</a> (OperandVector &amp;Operands)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/parsestatus">ParseStatus</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aabf72174f316fbcb2e171c231b94d743">parseRegWithIntInputMods</a> (OperandVector &amp;Operands)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/parsestatus">ParseStatus</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aad55de4993c720c50d992a7cbda3d8d3">parseVReg32OrOff</a> (OperandVector &amp;Operands)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/parsestatus">ParseStatus</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a971176e60129a0824a8c1e2a193e6b62">tryParseIndexKey</a> (OperandVector &amp;Operands, AMDGPUOperand::ImmTy ImmTy)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/parsestatus">ParseStatus</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c025a975a2c1bb92eeff1c356d17df3">parseIndexKey8bit</a> (OperandVector &amp;Operands)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/parsestatus">ParseStatus</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8a20622d48ff74bd05f5de0cafcba3ab">parseIndexKey16bit</a> (OperandVector &amp;Operands)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/parsestatus">ParseStatus</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a157290e9f9aa7ff61c53d131b090e50a">parseDfmtNfmt</a> (int64_t &amp;Format)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/parsestatus">ParseStatus</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1125b7de6fb9f81f501a1988550e60d9">parseUfmt</a> (int64_t &amp;Format)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/parsestatus">ParseStatus</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad0ddd35516c856b2c41317d0c1febdea">parseSymbolicSplitFormat</a> (StringRef FormatStr, SMLoc Loc, int64_t &amp;Format)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/parsestatus">ParseStatus</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9cba0b00a0bcffcb413914db33553071">parseSymbolicUnifiedFormat</a> (StringRef FormatStr, SMLoc Loc, int64_t &amp;Format)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/parsestatus">ParseStatus</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aae18974f031b21f7dd37b072a1cbe24d">parseFORMAT</a> (OperandVector &amp;Operands)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/parsestatus">ParseStatus</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac75ca253bd4248bf1ab2b4d4695f0500">parseSymbolicOrNumericFormat</a> (int64_t &amp;Format)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/parsestatus">ParseStatus</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae93e542fa2b3eac118a87c97a47bc681">parseNumericFormat</a> (int64_t &amp;Format)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/parsestatus">ParseStatus</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af9a4f566ce16209db2301b23edfe1573">parseFlatOffset</a> (OperandVector &amp;Operands)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/parsestatus">ParseStatus</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa73d0a8ecc958df50e46e59e1ad97478">parseR128A16</a> (OperandVector &amp;Operands)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/parsestatus">ParseStatus</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3ad635dcc304d17a852fa28adac99bb9">parseBLGP</a> (OperandVector &amp;Operands)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4110e462b4bf86153ae19de70eb84443">tryParseFmt</a> (const char *Pref, int64_t MaxVal, int64_t &amp;Val)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea4cc2cee6a095dbbd1f35f80ad3c3e1">matchDfmtNfmt</a> (int64_t &amp;Dfmt, int64_t &amp;Nfmt, StringRef FormatStr, SMLoc Loc)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a38abdd95e7f5b6e9f4fc534bb392f8b8">cvtExp</a> (MCInst &amp;Inst, const OperandVector &amp;Operands)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e283edef71599b2ffccac2843fce5a0">parseCnt</a> (int64_t &amp;IntVal)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/parsestatus">ParseStatus</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac3b25b92e123263ee61ca38bdee04828">parseSWaitCnt</a> (OperandVector &amp;Operands)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec0a91539564d9315907e97bc05acdbb">parseDepCtr</a> (int64_t &amp;IntVal, unsigned &amp;Mask)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a90bf6e63a8b618e76af97748e777d330">depCtrError</a> (SMLoc Loc, int ErrorId, StringRef DepCtrName)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/parsestatus">ParseStatus</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa54525f0109858da308fa32559539255">parseDepCtr</a> (OperandVector &amp;Operands)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac5924990c1b6a01f79b3dd8019f5f7b">parseDelay</a> (int64_t &amp;Delay)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/parsestatus">ParseStatus</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a493337bf1e3308881e03af9142a5bb5a">parseSDelayALU</a> (OperandVector &amp;Operands)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/parsestatus">ParseStatus</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a16bbeaa5435876a2a30093aa9f7adc09">parseHwreg</a> (OperandVector &amp;Operands)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a01d6b546873c9427d25bf80c857cb2c4">onBeginOfFile</a> () override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab65e752ef8a4ee9e6df01039bfa00b0e">parsePrimaryExpr</a> (const MCExpr *&amp;Res, SMLoc &amp;EndLoc) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parse <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu">AMDGPU</a> specific expressions. <a href="#ab65e752ef8a4ee9e6df01039bfa00b0e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/parsestatus">ParseStatus</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a877255e198cc72078a64aa635548b03b">parseCustomOperand</a> (OperandVector &amp;Operands, unsigned MCK)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/parsestatus">ParseStatus</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a26a8456ca91f0f85ed2f854837b0dc29">parseExpTgt</a> (OperandVector &amp;Operands)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/parsestatus">ParseStatus</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e026648ec951bc9ce02a0e99e31f583">parseSendMsg</a> (OperandVector &amp;Operands)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/parsestatus">ParseStatus</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc5a32fe7c02fdcfc1484e926e376ce0">parseInterpSlot</a> (OperandVector &amp;Operands)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/parsestatus">ParseStatus</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5c3abd5a0df4ec19738884622846a92b">parseInterpAttr</a> (OperandVector &amp;Operands)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/parsestatus">ParseStatus</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a082f5bbf706dd5cd5bcb35d7bdf5564f">parseSOPPBrTarget</a> (OperandVector &amp;Operands)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/parsestatus">ParseStatus</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5c229c26ac4e66cb56bd6d00cb6e86d4">parseBoolReg</a> (OperandVector &amp;Operands)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe6b5f546bd5056f7d59de67f0b5b73b">parseSwizzleOperand</a> (int64_t &amp;Op, const unsigned MinVal, const unsigned MaxVal, const Twine &amp;ErrMsg, SMLoc &amp;Loc)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab9d915a16cfd251019c425b36648aa5b">parseSwizzleOperands</a> (const unsigned OpNum, int64_t *Op, const unsigned MinVal, const unsigned MaxVal, const StringRef ErrMsg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/parsestatus">ParseStatus</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a45d3320cf47a5c534c3e884ea6501728">parseSwizzle</a> (OperandVector &amp;Operands)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac327ffb53b577c5a4cfed8b62cd05a13">parseSwizzleOffset</a> (int64_t &amp;Imm)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a084f15a5b33b0ce4978446665fabd0b7">parseSwizzleMacro</a> (int64_t &amp;Imm)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad3c62cbfb35509cada7ddfa5dbf92b42">parseSwizzleQuadPerm</a> (int64_t &amp;Imm)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6fc763bfb813e4442ede4201150335d7">parseSwizzleBitmaskPerm</a> (int64_t &amp;Imm)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af50d93f657b70f0b66da8a3f052dec81">parseSwizzleBroadcast</a> (int64_t &amp;Imm)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad4f24fc9dd2450e0cd0af87b71e13baf">parseSwizzleSwap</a> (int64_t &amp;Imm)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a98cf404e7899b4845ce05a1d1e34101e">parseSwizzleReverse</a> (int64_t &amp;Imm)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad5af3c7927dc204657a840c176cc3d30">parseSwizzleFFT</a> (int64_t &amp;Imm)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeac6096195ab728c4deed35b2cd4bf67">parseSwizzleRotate</a> (int64_t &amp;Imm)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/parsestatus">ParseStatus</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad03402b69301c9df929a7ca211df947c">parseGPRIdxMode</a> (OperandVector &amp;Operands)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a158cdc1506b2dfbeace5ec8c87327426">parseGPRIdxMacro</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7d59a38f68d5236ad8c34c43351ce8cc">cvtMubuf</a> (MCInst &amp;Inst, const OperandVector &amp;Operands)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6986b4213079ebe325963a5422becbf3">cvtMubufAtomic</a> (MCInst &amp;Inst, const OperandVector &amp;Operands)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/parsestatus">ParseStatus</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9d5e44bae726c6d5f1d1af4aba4a48ff">parseOModSI</a> (OperandVector &amp;Operands)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4547aa57e2b9056a73e2a8b26cc18d5b">cvtVOP3</a> (MCInst &amp;Inst, const OperandVector &amp;Operands, OptionalImmIndexMap &amp;OptionalIdx)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af9f84a232dd5f4bc0758374c9d26203f">cvtVOP3OpSel</a> (MCInst &amp;Inst, const OperandVector &amp;Operands)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a21584d32fc8f81d68e30d7dac7838ff5">cvtVOP3</a> (MCInst &amp;Inst, const OperandVector &amp;Operands)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54a0d60e48d43aad665fd4096d2b4945">cvtVOP3P</a> (MCInst &amp;Inst, const OperandVector &amp;Operands)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a238abfd2ac2842861ab322354aec3d64">cvtSWMMAC</a> (MCInst &amp;Inst, const OperandVector &amp;Operands)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b9f3d685a06c0789d0e594e044be2b9">cvtVOPD</a> (MCInst &amp;Inst, const OperandVector &amp;Operands)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a169daf8f1c8486c073f4faa87b0f402e">cvtVOP3OpSel</a> (MCInst &amp;Inst, const OperandVector &amp;Operands, OptionalImmIndexMap &amp;OptionalIdx)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a21401db3d85754eab356474360dd2394">cvtVOP3P</a> (MCInst &amp;Inst, const OperandVector &amp;Operands, OptionalImmIndexMap &amp;OptionalIdx)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af30bfdcbe6574a1d0de2c2c59c1a8f18">cvtVOP3Interp</a> (MCInst &amp;Inst, const OperandVector &amp;Operands)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac4e2add1506387486f82ff6117a6a0e4">cvtVINTERP</a> (MCInst &amp;Inst, const OperandVector &amp;Operands)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a332d48815071fdb4e2e94e999c154559">parseDimId</a> (unsigned &amp;Encoding)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/parsestatus">ParseStatus</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c31665501f9b711e245f1b4e201683b">parseDim</a> (OperandVector &amp;Operands)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb7bcf8b1454072ac361ae5764cd4abc">convertDppBoundCtrl</a> (int64_t &amp;BoundCtrl)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/parsestatus">ParseStatus</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a59d9c798683c4a134a731c43840d62aa">parseDPP8</a> (OperandVector &amp;Operands)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/parsestatus">ParseStatus</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af1e3005e43d45d207eb661fa024b1753">parseDPPCtrl</a> (OperandVector &amp;Operands)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3c48b1ea644084c3a3e9751a96f10a11">isSupportedDPPCtrl</a> (StringRef Ctrl, const OperandVector &amp;Operands)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ee2ba5e7987e0dc7330c99ad35cdf88">parseDPPCtrlSel</a> (StringRef Ctrl)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac8acd31ba54707e7714ebb81abe2bf8f">parseDPPCtrlPerm</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adfaf977dc82c560bd265a68c807cd1a0">cvtDPP</a> (MCInst &amp;Inst, const OperandVector &amp;Operands, bool IsDPP8=false)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a15aaf557b5842153fe4a540281698b35">cvtDPP8</a> (MCInst &amp;Inst, const OperandVector &amp;Operands)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a81d4a718e3a11c1c3507fb28db101cf6">cvtVOP3DPP</a> (MCInst &amp;Inst, const OperandVector &amp;Operands, bool IsDPP8=false)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa5e7317f66ba20d6de650a0294a112c4">cvtVOP3DPP8</a> (MCInst &amp;Inst, const OperandVector &amp;Operands)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/parsestatus">ParseStatus</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb4f66c7a0618aeff77aba400ebda133">parseSDWASel</a> (OperandVector &amp;Operands, StringRef Prefix, AMDGPUOperand::ImmTy Type)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/parsestatus">ParseStatus</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a37e7a53cd92512fc5eb8f7a59be76557">parseSDWADstUnused</a> (OperandVector &amp;Operands)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade74ac635e66be70c5b81ab88d578d88">cvtSdwaVOP1</a> (MCInst &amp;Inst, const OperandVector &amp;Operands)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a91b1e73c724242ec19e9e99688540dc6">cvtSdwaVOP2</a> (MCInst &amp;Inst, const OperandVector &amp;Operands)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa705db92f05d9b4e557da7c69c4a6960">cvtSdwaVOP2b</a> (MCInst &amp;Inst, const OperandVector &amp;Operands)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa5f806029a40f8f5bcb8210ce52841ce">cvtSdwaVOP2e</a> (MCInst &amp;Inst, const OperandVector &amp;Operands)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af5e01806d4b89fadd4b471243098cc12">cvtSdwaVOPC</a> (MCInst &amp;Inst, const OperandVector &amp;Operands)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a57878d0e3afa7d6e659b92b9d71c0923">cvtSDWA</a> (MCInst &amp;Inst, const OperandVector &amp;Operands, uint64_t BasicInstType, bool SkipDstVcc=false, bool SkipSrcVcc=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/parsestatus">ParseStatus</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b822486044ee842c7c868f39ff4830b">parseEndpgm</a> (OperandVector &amp;Operands)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/parsestatus">ParseStatus</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c71cb47a3f1bcc8147c44cc1395ed63">parseVOPD</a> (OperandVector &amp;Operands)</td>
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


<p>Definition at line 1317 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<div class="doxySectionDef">

## Private Member Attributes

### ForcedDPP {#a1b6b6add9ac0f36dd827785d07ea6e5e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::ForcedDPP = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1321 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>

</div>
</div>

### ForcedEncodingSize {#a47bc6785f1a651e9d4349eb6c8317a19}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::ForcedEncodingSize = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1320 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>

</div>
</div>

### ForcedSDWA {#a8540eac5fbf14fbd632448ce5edfb87c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::ForcedSDWA = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1322 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>

</div>
</div>

### KernelScope {#a94983992fec14119c86f87ea3d379c18}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">KernelScopeInfo anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::KernelScope</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1323 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>

</div>
</div>

### Parser {#a47a14d2c92e97f56f678c222b4b08fae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCAsmParser&amp; anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::Parser</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1318 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Auto-generated Match Functions



<p>{</p>


### AddNextRegisterToList {#a234441b9c1bbcdbc500127a033c2e653}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUAsmParser::AddNextRegisterToList (<a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> &amp; Reg, unsigned &amp; RegWidth, <a href="/web-llvm/docs/api/namespaces/anonymous-amdgpuasmparser-cpp-/#a30f503d41098d2871ebfc07b76480ea0">RegisterKind</a> RegKind, <a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> Reg1, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1380 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>

</div>
</div>

### AMDGPUAsmParser {#a887ee9b0b1952f6adb88d8ef15c82a53}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::AMDGPUAsmParser (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI, <a href="/web-llvm/docs/api/classes/llvm/mcasmparser">MCAsmParser</a> &amp; _Parser, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo">MCInstrInfo</a> &amp; MII, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mctargetoptions">MCTargetOptions</a> &amp; Options)</td>
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



<p>Definition at line 1418 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mctargetasmparser/#a1f36fcf8463068f9a2d25b02411c08b9">llvm::MCTargetAsmParser::copySTI</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparserextension/#aa7399d73f97fdf5bcf6b19f760264848">llvm::MCAsmParserExtension::getContext</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2c346c56fb9021d994675d1710d2d551">llvm::getCPU</a>, <a href="#a6a16aaca0a854369fe286a9d8bb3372a">getFeatureBits</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/ucversion/#a826e7eb7566b6093e87bf78f186b96a2">llvm::AMDGPU::UCVersion::getGFXVersions</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a4c450943f424116a9b6b9a3db451af6c">llvm::AMDGPU::getIsaVersion</a>, <a href="/web-llvm/docs/api/classes/llvm/mctargetasmparser/#aa1990a3125ab983e6e90a452cb5a2e66">llvm::MCTargetAsmParser::getSTI</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparserextension/#a77a335167c72ea8bc771501825f81696">llvm::MCAsmParserExtension::Initialize</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-amdgpuasmparser-cpp-/#a30f503d41098d2871ebfc07b76480ea0adc309b24d889a772b3b6e2cfe1649ff3">anonymous{AMDGPUAsmParser.cpp}::IS_SGPR</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-amdgpuasmparser-cpp-/#a30f503d41098d2871ebfc07b76480ea0a40b4f5a49b34776935190c3d9bac5edf">anonymous{AMDGPUAsmParser.cpp}::IS_VGPR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a3d357ec8432b58835aaa34defcc4eff9">llvm::AMDGPU::isHsaAbi</a>, <a href="/web-llvm/docs/api/classes/llvm/mctargetasmparser/#a32cd9ae9007321c391a62dd4bd69d268">llvm::MCTargetAsmParser::MCTargetAsmParser</a>, <a href="/web-llvm/docs/api/classes/llvm/mctargetasmparser/#a86c4103ccd50c7d1f8df88d71ccfef5e">llvm::MCTargetAsmParser::MII</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64stacktagging-cpp/#a8e818224d2d1de9b995783ff897b0083ab7e4e0120a041dbe6528b050c04269e0">none</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/core/lvoptions-cpp/#ab4088b7a11f3cbc38ac16a6e9c72494e">Options</a>, <a href="/web-llvm/docs/api/classes/llvm/mctargetasmparser/#a9bc309121dfab6b0c03a026eec7b2ab7">llvm::MCTargetAsmParser::setAvailableFeatures</a> and <a href="/web-llvm/docs/api/classes/llvm/mctargetasmparser/#aff6afefbe685c9940c3e082c7f576df6">llvm::MCTargetAsmParser::STI</a>.</p>


<p>Referenced by <a href="#a75ed4572cff3fae7911dba55aba309bf">getMRI</a> and <a href="#a16bbeaa5435876a2a30093aa9f7adc09">parseHwreg</a>.</p>

</div>
</div>

### calculateGPRBlocks {#a117255be5807c86dcd89efe6e9467eec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUAsmParser::calculateGPRBlocks (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/featurebitset">FeatureBitset</a> &amp; Features, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * VCCUsed, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * FlatScrUsed, bool XNACKUsed, std::optional&lt; bool &gt; EnableWavefrontSize32, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * NextFreeVGPR, <a href="/web-llvm/docs/api/classes/llvm/smrange">SMRange</a> VGPRRange, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * NextFreeSGPR, <a href="/web-llvm/docs/api/classes/llvm/smrange">SMRange</a> SGPRRange, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> *&amp; VGPRBlocks, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> *&amp; SGPRBlocks)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Calculate VGPR/SGPR blocks required for given target, reserved registers, and user-specified NextFreeXGPR values.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Features</td>
<td class="doxyParamItemDescription"><p>[in] <a href="/web-llvm/docs/api/classes/llvm/target">Target</a> features, used for bug corrections.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">VCCUsed</td>
<td class="doxyParamItemDescription"><p>[in] Whether VCC special SGPR is reserved.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">FlatScrUsed</td>
<td class="doxyParamItemDescription"><p>[in] Whether FLAT_SCRATCH special SGPR is reserved.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">XNACKUsed</td>
<td class="doxyParamItemDescription"><p>[in] Whether XNACK_MASK special SGPR is reserved.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">EnableWavefrontSize32</td>
<td class="doxyParamItemDescription"><p>[in] <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> of ENABLE_WAVEFRONT_SIZE32 kernel descriptor field, if valid.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">NextFreeVGPR</td>
<td class="doxyParamItemDescription"><p>[in] Max VGPR number referenced, plus one.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">VGPRRange</td>
<td class="doxyParamItemDescription"><p>[in] Token range, used for VGPR diagnostics.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">NextFreeSGPR</td>
<td class="doxyParamItemDescription"><p>[in] Max SGPR number referenced, plus one.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">SGPRRange</td>
<td class="doxyParamItemDescription"><p>[in] Token range, used for SGPR diagnostics.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">VGPRBlocks</td>
<td class="doxyParamItemDescription"><p>[out] Result VGPR block count.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">SGPRBlocks</td>
<td class="doxyParamItemDescription"><p>[out] Result SGPR block count.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 1353 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>

</div>
</div>

### checkTargetMatchPredicate {#ae55539b0211e9bc98123340231aa6902}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned AMDGPUAsmParser::checkTargetMatchPredicate (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst)</td>
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

<p>checkTargetMatchPredicate - Validate the instruction match against any complex target predicates not expressible via match classes.</p>

<p>Definition at line 1603 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181eca06434d3505958806f243119630f8c976">llvm::SIInstrFlags::DPP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/sdwa/#a487d59303b94fbf4adddd9a08c30da0aaddbc3f8d705f646af626fd73cdf3618b">llvm::AMDGPU::SDWA::DWORD</a>, <a href="#a8c474bd3ccb2bda9a89f31fb3d7bf1cb">getForcedEncodingSize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a27efe1286cc31f5fc95355af30b0356c">llvm::AMDGPU::getNamedOperandIdx</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinst/#a5c26b1db954c27889986dba3b310a8e4">llvm::MCInst::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinst/#aef5de3ac30fe221c5b4e702574ab46a9">llvm::MCInst::getOperand</a>, <a href="#aae673d780d4f7a887dcdb07e93a14bfe">isForcedDPP</a>, <a href="#a2fdb1206f7410fc6fce1780b2573edbf">isForcedSDWA</a>, <a href="/web-llvm/docs/api/classes/llvm/mctargetasmparser/#a29cb086c359baadd9df6e5f101e41007a36e5dd518d3d92d2d6207a9ed03d6b48">llvm::MCTargetAsmParser::Match_InvalidOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/mctargetasmparser/#a29cb086c359baadd9df6e5f101e41007a2d220d934e235f8d0ff1eb07adf2b483">llvm::MCTargetAsmParser::Match_Success</a>, <a href="/web-llvm/docs/api/classes/llvm/mctargetasmparser/#a86c4103ccd50c7d1f8df88d71ccfef5e">llvm::MCTargetAsmParser::MII</a>, <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181eca3cb08b10c27a453c57a2708e83859b47">llvm::SIInstrFlags::SDWA</a> and <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181eca78562688e8d67f7ffa892e4b92311a98">llvm::SIInstrFlags::VOP3</a>.</p>

</div>
</div>

### checkUnsupportedInstruction {#afc2f9b34dcc8d5590de76fa323c386ef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUAsmParser::checkUnsupportedInstruction (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> &amp; IDLoc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1810 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>

</div>
</div>

### convertDppBoundCtrl {#afb7bcf8b1454072ac361ae5764cd4abc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUAsmParser::convertDppBoundCtrl (int64_t &amp; BoundCtrl)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1891 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>Reference <a href="#a93fd6449c3f63d76ff63b7231aec9269">isGFX11Plus</a>.</p>


<p>Referenced by <a href="#a21401db3d85754eab356474360dd2394">cvtVOP3P</a>.</p>

</div>
</div>

### createConstantSymbol {#a9a81457c117babd6d9e5304f33e74819}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AMDGPUAsmParser::createConstantSymbol (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Id, int64_t Val)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>}</p>

<p>Definition at line 1334 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>

</div>
</div>

### cvtDPP {#adfaf977dc82c560bd265a68c807cd1a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AMDGPUAsmParser::cvtDPP (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a61e27c75c3334cffa54c44c02077da1e">OperandVector</a> &amp; Operands, bool IsDPP8=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1897 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp/#ac9d379c622b78d95b1ecd4823ccb15ac">addOptionalImmOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#aa66df54e14d6219d63e025455bfe52ae">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::addRegOperands</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a595e70d3c4ee2ed95ece67a1957167a4">llvm::MCOperand::createImm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/dpp/#aa19c007b0d0fdcbf3db8462eeb72c059a86bc62297264c5c421f06a54985349a1">llvm::AMDGPU::DPP::DPP8_FI_0</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/dpp/#aa19c007b0d0fdcbf3db8462eeb72c059a470b8d8ac84510a78711e68988cb0d6b">llvm::AMDGPU::DPP::DPP8_FI_1</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinst/#a3c5c7109f398fdca515509e2284cd8c0">llvm::MCInst::getNumOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinst/#a5c26b1db954c27889986dba3b310a8e4">llvm::MCInst::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinst/#aef5de3ac30fe221c5b4e702574ab46a9">llvm::MCInst::getOperand</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a8f27aa11689bf9b12f6fb0e436e367c7">llvm::AMDGPU::hasNamedOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#aac6196abacab3897ea9874e72d3db8fca107c472f8bfeb150ed0737921a85e408">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::ImmTyDppBankMask</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#aac6196abacab3897ea9874e72d3db8fca9551790c26c1cb431ce82ab01f748a53">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::ImmTyDppBoundCtrl</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#aac6196abacab3897ea9874e72d3db8fca07d5a47db7db2fcf76162ad332f72686">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::ImmTyDppFI</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#aac6196abacab3897ea9874e72d3db8fca8bb6ce8b62f92662c470a40065d126af">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::ImmTyDppRowMask</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#a23ce1a2b844fbe612c836b788bb80b29">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isRegOrImmWithInputMods</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/classes/llvm/mctargetasmparser/#a86c4103ccd50c7d1f8df88d71ccfef5e">llvm::MCTargetAsmParser::MII</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirnamerpass-cpp/#a05e4be4ec3e2c3587dda0e376bb6822c">Operands</a> and <a href="/web-llvm/docs/api/namespaces/llvm/mcoi/#aaa8eb58fd1b8466eb64a43df890cb8c1ae01b27a05209c02ca1bdb5a6033731fb">llvm::MCOI::TIED_TO</a>.</p>


<p>Referenced by <a href="#a15aaf557b5842153fe4a540281698b35">cvtDPP8</a> and <a href="#a21401db3d85754eab356474360dd2394">cvtVOP3P</a>.</p>

</div>
</div>

### cvtDPP8 {#a15aaf557b5842153fe4a540281698b35}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::cvtDPP8 (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a61e27c75c3334cffa54c44c02077da1e">OperandVector</a> &amp; Operands)</td>
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



<p>Definition at line 1898 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="#adfaf977dc82c560bd265a68c807cd1a0">cvtDPP</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirnamerpass-cpp/#a05e4be4ec3e2c3587dda0e376bb6822c">Operands</a>.</p>

</div>
</div>

### cvtExp {#a38abdd95e7f5b6e9f4fc534bb392f8b8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AMDGPUAsmParser::cvtExp (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a61e27c75c3334cffa54c44c02077da1e">OperandVector</a> &amp; Operands)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1688 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp/#ac9d379c622b78d95b1ecd4823ccb15ac">addOptionalImmOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a595e70d3c4ee2ed95ece67a1957167a4">llvm::MCOperand::createImm</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a46271d9f83558334670c19539bceb965">llvm::MCOperand::createReg</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinst/#aef5de3ac30fe221c5b4e702574ab46a9">llvm::MCInst::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a94abf618eb8001b802910ab872a7d1d9">llvm::MCOperand::getReg</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#aac6196abacab3897ea9874e72d3db8fca2ff55b791397522185702a9ff4701ef5">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::ImmTyExpCompr</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#aac6196abacab3897ea9874e72d3db8fca8b92c2d67ca16440f8c439f063c4c32b">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::ImmTyExpTgt</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#aac6196abacab3897ea9874e72d3db8fca5b645a3daa82f94403a3ae30c2ab1089">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::ImmTyExpVM</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirnamerpass-cpp/#a05e4be4ec3e2c3587dda0e376bb6822c">Operands</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a604722fe2776c0df4d275cff37a37d95">llvm::MCOperand::setReg</a> and <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ae534d5d22096b2665d16e5ab600ebbce">llvm::MCInst::size</a>.</p>


<p>Referenced by <a href="#a82b29753ac1baad9801c7217c0a97dd4">parseIntWithPrefix</a>.</p>

</div>
</div>

### cvtMubuf {#a7d59a38f68d5236ad8c34c43351ce8cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::cvtMubuf (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a61e27c75c3334cffa54c44c02077da1e">OperandVector</a> &amp; Operands)</td>
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



<p>Definition at line 1868 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirnamerpass-cpp/#a05e4be4ec3e2c3587dda0e376bb6822c">Operands</a>.</p>

</div>
</div>

### cvtMubufAtomic {#a6986b4213079ebe325963a5422becbf3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::cvtMubufAtomic (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a61e27c75c3334cffa54c44c02077da1e">OperandVector</a> &amp; Operands)</td>
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



<p>Definition at line 1869 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirnamerpass-cpp/#a05e4be4ec3e2c3587dda0e376bb6822c">Operands</a>.</p>

</div>
</div>

### cvtMubufImpl {#a23a48b6961d6d2b1cece40c8bc0f305e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AMDGPUAsmParser::cvtMubufImpl (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a61e27c75c3334cffa54c44c02077da1e">OperandVector</a> &amp; Operands, bool IsAtomic)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1407 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>

</div>
</div>

### cvtSDWA {#a57878d0e3afa7d6e659b92b9d71c0923}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AMDGPUAsmParser::cvtSDWA (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a61e27c75c3334cffa54c44c02077da1e">OperandVector</a> &amp; Operands, uint64_t BasicInstType, bool SkipDstVcc=false, bool SkipSrcVcc=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1915 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp/#ac9d379c622b78d95b1ecd4823ccb15ac">addOptionalImmOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#aa66df54e14d6219d63e025455bfe52ae">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::addRegOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad7df02a018c3a01d74738d5ba3a09e93">llvm::MCInst::begin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/sdwa/#a487d59303b94fbf4adddd9a08c30da0aaddbc3f8d705f646af626fd73cdf3618b">llvm::AMDGPU::SDWA::DWORD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a27efe1286cc31f5fc95355af30b0356c">llvm::AMDGPU::getNamedOperandIdx</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinst/#a3c5c7109f398fdca515509e2284cd8c0">llvm::MCInst::getNumOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinst/#a5c26b1db954c27889986dba3b310a8e4">llvm::MCInst::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinst/#aef5de3ac30fe221c5b4e702574ab46a9">llvm::MCInst::getOperand</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a8f27aa11689bf9b12f6fb0e436e367c7">llvm::AMDGPU::hasNamedOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#aac6196abacab3897ea9874e72d3db8fcaf005c69ec582b7a5d66df13f4e317a1e">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::ImmTyClamp</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#aac6196abacab3897ea9874e72d3db8fcaf4e10bb6d0fda8ad54cca3f45eb2b143">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::ImmTyOModSI</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#aac6196abacab3897ea9874e72d3db8fca5ef6d8d490dc55a1a768223f15a959a3">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::ImmTySDWADstSel</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#aac6196abacab3897ea9874e72d3db8fca38365958fa12a0f2acd965b2bc77ea00">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::ImmTySDWADstUnused</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#aac6196abacab3897ea9874e72d3db8fcae0c54cec4b9a48401c2fd0dc32b9da24">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::ImmTySDWASrc0Sel</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#aac6196abacab3897ea9874e72d3db8fca066b849c42884b62cdb679dd05d1c28d">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::ImmTySDWASrc1Sel</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinst/#a780fe7b1259c076cd5abef9ce9dda01d">llvm::MCInst::insert</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#a23ce1a2b844fbe612c836b788bb80b29">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isRegOrImmWithInputMods</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/classes/llvm/mctargetasmparser/#a86c4103ccd50c7d1f8df88d71ccfef5e">llvm::MCTargetAsmParser::MII</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirnamerpass-cpp/#a05e4be4ec3e2c3587dda0e376bb6822c">Operands</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/sdwa/#a4473412439e8285e235ccafa0c3824b6a58f19664e2b69107495d2085514f7874">llvm::AMDGPU::SDWA::UNUSED_PRESERVE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181eca0dd2852ae8f20b7261f6d01eb354f1ff">llvm::SIInstrFlags::VOP1</a>, <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181eca600d26b3fa43f262c5ca2270667c0be2">llvm::SIInstrFlags::VOP2</a> and <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181eca40767b966aa194931bb6ce67e3649de7">llvm::SIInstrFlags::VOPC</a>.</p>


<p>Referenced by <a href="#ade74ac635e66be70c5b81ab88d578d88">cvtSdwaVOP1</a>, <a href="#a91b1e73c724242ec19e9e99688540dc6">cvtSdwaVOP2</a>, <a href="#aa705db92f05d9b4e557da7c69c4a6960">cvtSdwaVOP2b</a>, <a href="#aa5f806029a40f8f5bcb8210ce52841ce">cvtSdwaVOP2e</a> and <a href="#af5e01806d4b89fadd4b471243098cc12">cvtSdwaVOPC</a>.</p>

</div>
</div>

### cvtSdwaVOP1 {#ade74ac635e66be70c5b81ab88d578d88}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AMDGPUAsmParser::cvtSdwaVOP1 (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a61e27c75c3334cffa54c44c02077da1e">OperandVector</a> &amp; Operands)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1910 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="#a57878d0e3afa7d6e659b92b9d71c0923">cvtSDWA</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirnamerpass-cpp/#a05e4be4ec3e2c3587dda0e376bb6822c">Operands</a> and <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181eca0dd2852ae8f20b7261f6d01eb354f1ff">llvm::SIInstrFlags::VOP1</a>.</p>

</div>
</div>

### cvtSdwaVOP2 {#a91b1e73c724242ec19e9e99688540dc6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AMDGPUAsmParser::cvtSdwaVOP2 (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a61e27c75c3334cffa54c44c02077da1e">OperandVector</a> &amp; Operands)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1911 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="#a57878d0e3afa7d6e659b92b9d71c0923">cvtSDWA</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirnamerpass-cpp/#a05e4be4ec3e2c3587dda0e376bb6822c">Operands</a> and <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181eca600d26b3fa43f262c5ca2270667c0be2">llvm::SIInstrFlags::VOP2</a>.</p>

</div>
</div>

### cvtSdwaVOP2b {#aa705db92f05d9b4e557da7c69c4a6960}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AMDGPUAsmParser::cvtSdwaVOP2b (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a61e27c75c3334cffa54c44c02077da1e">OperandVector</a> &amp; Operands)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1912 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="#a57878d0e3afa7d6e659b92b9d71c0923">cvtSDWA</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirnamerpass-cpp/#a05e4be4ec3e2c3587dda0e376bb6822c">Operands</a> and <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181eca600d26b3fa43f262c5ca2270667c0be2">llvm::SIInstrFlags::VOP2</a>.</p>

</div>
</div>

### cvtSdwaVOP2e {#aa5f806029a40f8f5bcb8210ce52841ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AMDGPUAsmParser::cvtSdwaVOP2e (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a61e27c75c3334cffa54c44c02077da1e">OperandVector</a> &amp; Operands)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1913 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="#a57878d0e3afa7d6e659b92b9d71c0923">cvtSDWA</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirnamerpass-cpp/#a05e4be4ec3e2c3587dda0e376bb6822c">Operands</a> and <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181eca600d26b3fa43f262c5ca2270667c0be2">llvm::SIInstrFlags::VOP2</a>.</p>

</div>
</div>

### cvtSdwaVOPC {#af5e01806d4b89fadd4b471243098cc12}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AMDGPUAsmParser::cvtSdwaVOPC (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a61e27c75c3334cffa54c44c02077da1e">OperandVector</a> &amp; Operands)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1914 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="#a57878d0e3afa7d6e659b92b9d71c0923">cvtSDWA</a>, <a href="#a8e77658ae7e2c85817cc9e6fb62901bf">isVI</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirnamerpass-cpp/#a05e4be4ec3e2c3587dda0e376bb6822c">Operands</a> and <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181eca40767b966aa194931bb6ce67e3649de7">llvm::SIInstrFlags::VOPC</a>.</p>

</div>
</div>

### cvtSWMMAC {#a238abfd2ac2842861ab322354aec3d64}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AMDGPUAsmParser::cvtSWMMAC (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a61e27c75c3334cffa54c44c02077da1e">OperandVector</a> &amp; Operands)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1878 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp/#ac9d379c622b78d95b1ecd4823ccb15ac">addOptionalImmOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#aa66df54e14d6219d63e025455bfe52ae">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::addRegOperands</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp/#ab8e8537ee53695e10c4b4d9e0f1da12e">addSrcModifiersAndSrc</a>, <a href="#a54a0d60e48d43aad665fd4096d2b4945">cvtVOP3P</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinst/#a5c26b1db954c27889986dba3b310a8e4">llvm::MCInst::getOpcode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a8f27aa11689bf9b12f6fb0e436e367c7">llvm::AMDGPU::hasNamedOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#aac6196abacab3897ea9874e72d3db8fcaf005c69ec582b7a5d66df13f4e317a1e">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::ImmTyClamp</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#aac6196abacab3897ea9874e72d3db8fca4df6d1cb3360e33d52bed3dd55d9342e">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::ImmTyIndexKey16bit</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#aac6196abacab3897ea9874e72d3db8fca3b0787bbfe8d09244425732c5a8840d7">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::ImmTyIndexKey8bit</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirnamerpass-cpp/#a05e4be4ec3e2c3587dda0e376bb6822c">Operands</a>.</p>

</div>
</div>

### cvtVINTERP {#ac4e2add1506387486f82ff6117a6a0e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AMDGPUAsmParser::cvtVINTERP (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a61e27c75c3334cffa54c44c02077da1e">OperandVector</a> &amp; Operands)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1887 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a926d7ce2143863b7a2afda0fca4d2b65">AbstractManglingParser&lt; Derived, Alloc &gt;::Ops</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp/#ac9d379c622b78d95b1ecd4823ccb15ac">addOptionalImmOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#aa66df54e14d6219d63e025455bfe52ae">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::addRegOperands</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sisrcmods/#a4d4c7f0ccdd236a97a1583b77f8fd442a8e2f726558b97b38629c9fa9f8691612">llvm::SISrcMods::DST_OP_SEL</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a4509c43893edc940979f690c468664c1">llvm::MCOperand::getImm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a27efe1286cc31f5fc95355af30b0356c">llvm::AMDGPU::getNamedOperandIdx</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinst/#a3c5c7109f398fdca515509e2284cd8c0">llvm::MCInst::getNumOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinst/#a5c26b1db954c27889986dba3b310a8e4">llvm::MCInst::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinst/#aef5de3ac30fe221c5b4e702574ab46a9">llvm::MCInst::getOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#aac6196abacab3897ea9874e72d3db8fcaf005c69ec582b7a5d66df13f4e317a1e">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::ImmTyClamp</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#aac6196abacab3897ea9874e72d3db8fcaf3ba690efda9412129e1195c93663d18">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::ImmTyOpSel</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#aac6196abacab3897ea9874e72d3db8fcadeeea91bbd0d55b997e0f5291a4a1a7e">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::ImmTyWaitEXP</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#a23ce1a2b844fbe612c836b788bb80b29">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isRegOrImmWithInputMods</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/classes/llvm/mctargetasmparser/#a86c4103ccd50c7d1f8df88d71ccfef5e">llvm::MCTargetAsmParser::MII</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sisrcmods/#a4d4c7f0ccdd236a97a1583b77f8fd442a3b095994a942145ccaaed4f175c7172a">llvm::SISrcMods::OP_SEL_0</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirnamerpass-cpp/#a05e4be4ec3e2c3587dda0e376bb6822c">Operands</a> and <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a170578b62596712cf242f97ea687074b">llvm::MCOperand::setImm</a>.</p>


<p>Referenced by <a href="#a21401db3d85754eab356474360dd2394">cvtVOP3P</a>.</p>

</div>
</div>

### cvtVOP3 {#a4547aa57e2b9056a73e2a8b26cc18d5b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AMDGPUAsmParser::cvtVOP3 (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a61e27c75c3334cffa54c44c02077da1e">OperandVector</a> &amp; Operands, <a href="#ad427f76801ceb008e1d15f59313cff3d">OptionalImmIndexMap</a> &amp; OptionalIdx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1873 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp/#ac9d379c622b78d95b1ecd4823ccb15ac">addOptionalImmOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#aa66df54e14d6219d63e025455bfe52ae">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::addRegOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad7df02a018c3a01d74738d5ba3a09e93">llvm::MCInst::begin</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a595e70d3c4ee2ed95ece67a1957167a4">llvm::MCOperand::createImm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a27efe1286cc31f5fc95355af30b0356c">llvm::AMDGPU::getNamedOperandIdx</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinst/#a3c5c7109f398fdca515509e2284cd8c0">llvm::MCInst::getNumOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinst/#a5c26b1db954c27889986dba3b310a8e4">llvm::MCInst::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinst/#aef5de3ac30fe221c5b4e702574ab46a9">llvm::MCInst::getOperand</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a8f27aa11689bf9b12f6fb0e436e367c7">llvm::AMDGPU::hasNamedOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#aac6196abacab3897ea9874e72d3db8fca040e9137b23fb0a740bfb222d4911c49">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::ImmTyByteSel</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#aac6196abacab3897ea9874e72d3db8fcaf005c69ec582b7a5d66df13f4e317a1e">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::ImmTyClamp</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#aac6196abacab3897ea9874e72d3db8fcaf4e10bb6d0fda8ad54cca3f45eb2b143">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::ImmTyOModSI</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinst/#a780fe7b1259c076cd5abef9ce9dda01d">llvm::MCInst::insert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#addb7ac73684b6266c9a9c177c602d603">llvm::AMDGPU::isMAC</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#a23ce1a2b844fbe612c836b788bb80b29">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isRegOrImmWithInputMods</a>, <a href="/web-llvm/docs/api/classes/llvm/mctargetasmparser/#a86c4103ccd50c7d1f8df88d71ccfef5e">llvm::MCTargetAsmParser::MII</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirnamerpass-cpp/#a05e4be4ec3e2c3587dda0e376bb6822c">Operands</a>.</p>


<p>Referenced by <a href="#a21584d32fc8f81d68e30d7dac7838ff5">cvtVOP3</a> and <a href="#a54a0d60e48d43aad665fd4096d2b4945">cvtVOP3P</a>.</p>

</div>
</div>

### cvtVOP3 {#a21584d32fc8f81d68e30d7dac7838ff5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AMDGPUAsmParser::cvtVOP3 (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a61e27c75c3334cffa54c44c02077da1e">OperandVector</a> &amp; Operands)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1876 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="#a4547aa57e2b9056a73e2a8b26cc18d5b">cvtVOP3</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirnamerpass-cpp/#a05e4be4ec3e2c3587dda0e376bb6822c">Operands</a>.</p>

</div>
</div>

### cvtVOP3DPP {#a81d4a718e3a11c1c3507fb28db101cf6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AMDGPUAsmParser::cvtVOP3DPP (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a61e27c75c3334cffa54c44c02077da1e">OperandVector</a> &amp; Operands, bool IsDPP8=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1901 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp/#ac9d379c622b78d95b1ecd4823ccb15ac">addOptionalImmOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#aa66df54e14d6219d63e025455bfe52ae">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::addRegOperands</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a595e70d3c4ee2ed95ece67a1957167a4">llvm::MCOperand::createImm</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a46271d9f83558334670c19539bceb965">llvm::MCOperand::createReg</a>, <a href="#af9f84a232dd5f4bc0758374c9d26203f">cvtVOP3OpSel</a>, <a href="#a54a0d60e48d43aad665fd4096d2b4945">cvtVOP3P</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/dpp/#aa19c007b0d0fdcbf3db8462eeb72c059a86bc62297264c5c421f06a54985349a1">llvm::AMDGPU::DPP::DPP8_FI_0</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/dpp/#aa19c007b0d0fdcbf3db8462eeb72c059a470b8d8ac84510a78711e68988cb0d6b">llvm::AMDGPU::DPP::DPP8_FI_1</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a27efe1286cc31f5fc95355af30b0356c">llvm::AMDGPU::getNamedOperandIdx</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinst/#a3c5c7109f398fdca515509e2284cd8c0">llvm::MCInst::getNumOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinst/#a5c26b1db954c27889986dba3b310a8e4">llvm::MCInst::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinst/#aef5de3ac30fe221c5b4e702574ab46a9">llvm::MCInst::getOperand</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a8f27aa11689bf9b12f6fb0e436e367c7">llvm::AMDGPU::hasNamedOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#aac6196abacab3897ea9874e72d3db8fca040e9137b23fb0a740bfb222d4911c49">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::ImmTyByteSel</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#aac6196abacab3897ea9874e72d3db8fcaf005c69ec582b7a5d66df13f4e317a1e">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::ImmTyClamp</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#aac6196abacab3897ea9874e72d3db8fcaf79a7cadd64c125693239a99d15776d4">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::ImmTyDPP8</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#aac6196abacab3897ea9874e72d3db8fca107c472f8bfeb150ed0737921a85e408">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::ImmTyDppBankMask</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#aac6196abacab3897ea9874e72d3db8fca9551790c26c1cb431ce82ab01f748a53">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::ImmTyDppBoundCtrl</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#aac6196abacab3897ea9874e72d3db8fca9e3ba413ec741a423d42d99974585677">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::ImmTyDppCtrl</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#aac6196abacab3897ea9874e72d3db8fca07d5a47db7db2fcf76162ad332f72686">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::ImmTyDppFI</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#aac6196abacab3897ea9874e72d3db8fca8bb6ce8b62f92662c470a40065d126af">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::ImmTyDppRowMask</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#aac6196abacab3897ea9874e72d3db8fcaf4e10bb6d0fda8ad54cca3f45eb2b143">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::ImmTyOModSI</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#aac6196abacab3897ea9874e72d3db8fcaf3ba690efda9412129e1195c93663d18">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::ImmTyOpSel</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#a23ce1a2b844fbe612c836b788bb80b29">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isRegOrImmWithInputMods</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/classes/llvm/mctargetasmparser/#a86c4103ccd50c7d1f8df88d71ccfef5e">llvm::MCTargetAsmParser::MII</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirnamerpass-cpp/#a05e4be4ec3e2c3587dda0e376bb6822c">Operands</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mcoi/#aaa8eb58fd1b8466eb64a43df890cb8c1ae01b27a05209c02ca1bdb5a6033731fb">llvm::MCOI::TIED_TO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181eca78562688e8d67f7ffa892e4b92311a98">llvm::SIInstrFlags::VOP3</a> and <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181eca4b3bb80273571c42a8b35d5e952034c9">llvm::SIInstrFlags::VOP3P</a>.</p>


<p>Referenced by <a href="#aa5e7317f66ba20d6de650a0294a112c4">cvtVOP3DPP8</a>.</p>

</div>
</div>

### cvtVOP3DPP8 {#aa5e7317f66ba20d6de650a0294a112c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::cvtVOP3DPP8 (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a61e27c75c3334cffa54c44c02077da1e">OperandVector</a> &amp; Operands)</td>
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



<p>Definition at line 1903 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="#a81d4a718e3a11c1c3507fb28db101cf6">cvtVOP3DPP</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirnamerpass-cpp/#a05e4be4ec3e2c3587dda0e376bb6822c">Operands</a>.</p>

</div>
</div>

### cvtVOP3Interp {#af30bfdcbe6574a1d0de2c2c59c1a8f18}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AMDGPUAsmParser::cvtVOP3Interp (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a61e27c75c3334cffa54c44c02077da1e">OperandVector</a> &amp; Operands)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1886 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp/#ac9d379c622b78d95b1ecd4823ccb15ac">addOptionalImmOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#aa66df54e14d6219d63e025455bfe52ae">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::addRegOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a595e70d3c4ee2ed95ece67a1957167a4">llvm::MCOperand::createImm</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinst/#a3c5c7109f398fdca515509e2284cd8c0">llvm::MCInst::getNumOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinst/#a5c26b1db954c27889986dba3b310a8e4">llvm::MCInst::getOpcode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a8f27aa11689bf9b12f6fb0e436e367c7">llvm::AMDGPU::hasNamedOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#aac6196abacab3897ea9874e72d3db8fcaf005c69ec582b7a5d66df13f4e317a1e">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::ImmTyClamp</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#aac6196abacab3897ea9874e72d3db8fcab73f5f2d6a06746d900ab0d87a8e76e1">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::ImmTyHigh</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#aac6196abacab3897ea9874e72d3db8fcaf4e10bb6d0fda8ad54cca3f45eb2b143">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::ImmTyOModSI</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#a23ce1a2b844fbe612c836b788bb80b29">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isRegOrImmWithInputMods</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/classes/llvm/mctargetasmparser/#a86c4103ccd50c7d1f8df88d71ccfef5e">llvm::MCTargetAsmParser::MII</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirnamerpass-cpp/#a05e4be4ec3e2c3587dda0e376bb6822c">Operands</a>.</p>


<p>Referenced by <a href="#a21401db3d85754eab356474360dd2394">cvtVOP3P</a>.</p>

</div>
</div>

### cvtVOP3OpSel {#af9f84a232dd5f4bc0758374c9d26203f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AMDGPUAsmParser::cvtVOP3OpSel (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a61e27c75c3334cffa54c44c02077da1e">OperandVector</a> &amp; Operands)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1875 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp/#ad3bff1e1b8f6b45aeb994f8ba063dd4e">cvtVOP3DstOpSelOnly</a>, <a href="#a54a0d60e48d43aad665fd4096d2b4945">cvtVOP3P</a>, <a href="#a75ed4572cff3fae7911dba55aba309bf">getMRI</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirnamerpass-cpp/#a05e4be4ec3e2c3587dda0e376bb6822c">Operands</a>.</p>


<p>Referenced by <a href="#a81d4a718e3a11c1c3507fb28db101cf6">cvtVOP3DPP</a>.</p>

</div>
</div>

### cvtVOP3OpSel {#a169daf8f1c8486c073f4faa87b0f402e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AMDGPUAsmParser::cvtVOP3OpSel (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a61e27c75c3334cffa54c44c02077da1e">OperandVector</a> &amp; Operands, <a href="#ad427f76801ceb008e1d15f59313cff3d">OptionalImmIndexMap</a> &amp; OptionalIdx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1881 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp/#ad3bff1e1b8f6b45aeb994f8ba063dd4e">cvtVOP3DstOpSelOnly</a>, <a href="#a54a0d60e48d43aad665fd4096d2b4945">cvtVOP3P</a>, <a href="#a75ed4572cff3fae7911dba55aba309bf">getMRI</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirnamerpass-cpp/#a05e4be4ec3e2c3587dda0e376bb6822c">Operands</a>.</p>

</div>
</div>

### cvtVOP3P {#a54a0d60e48d43aad665fd4096d2b4945}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AMDGPUAsmParser::cvtVOP3P (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a61e27c75c3334cffa54c44c02077da1e">OperandVector</a> &amp; Operands)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1877 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="#a4547aa57e2b9056a73e2a8b26cc18d5b">cvtVOP3</a>, <a href="#a54a0d60e48d43aad665fd4096d2b4945">cvtVOP3P</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirnamerpass-cpp/#a05e4be4ec3e2c3587dda0e376bb6822c">Operands</a>.</p>


<p>Referenced by <a href="#a238abfd2ac2842861ab322354aec3d64">cvtSWMMAC</a>, <a href="#a81d4a718e3a11c1c3507fb28db101cf6">cvtVOP3DPP</a>, <a href="#af9f84a232dd5f4bc0758374c9d26203f">cvtVOP3OpSel</a>, <a href="#a169daf8f1c8486c073f4faa87b0f402e">cvtVOP3OpSel</a> and <a href="#a54a0d60e48d43aad665fd4096d2b4945">cvtVOP3P</a>.</p>

</div>
</div>

### cvtVOP3P {#a21401db3d85754eab356474360dd2394}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::cvtVOP3P (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a61e27c75c3334cffa54c44c02077da1e">OperandVector</a> &amp; Operands, <a href="#ad427f76801ceb008e1d15f59313cff3d">OptionalImmIndexMap</a> &amp; OptionalIdx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1883 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="#afb7bcf8b1454072ac361ae5764cd4abc">convertDppBoundCtrl</a>, <a href="#adfaf977dc82c560bd265a68c807cd1a0">cvtDPP</a>, <a href="#ac4e2add1506387486f82ff6117a6a0e4">cvtVINTERP</a>, <a href="#af30bfdcbe6574a1d0de2c2c59c1a8f18">cvtVOP3Interp</a>, <a href="#a3c48b1ea644084c3a3e9751a96f10a11">isSupportedDPPCtrl</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirnamerpass-cpp/#a05e4be4ec3e2c3587dda0e376bb6822c">Operands</a>, <a href="#a4c31665501f9b711e245f1b4e201683b">parseDim</a>, <a href="#a332d48815071fdb4e2e94e999c154559">parseDimId</a>, <a href="#a59d9c798683c4a134a731c43840d62aa">parseDPP8</a>, <a href="#af1e3005e43d45d207eb661fa024b1753">parseDPPCtrl</a>, <a href="#ac8acd31ba54707e7714ebb81abe2bf8f">parseDPPCtrlPerm</a> and <a href="#a1ee2ba5e7987e0dc7330c99ad35cdf88">parseDPPCtrlSel</a>.</p>

</div>
</div>

### cvtVOPD {#a0b9f3d685a06c0789d0e594e044be2b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AMDGPUAsmParser::cvtVOPD (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a61e27c75c3334cffa54c44c02077da1e">OperandVector</a> &amp; Operands)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1880 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/vopd/#a398bc0b5b6f80a8ebee6f6578149d50d">llvm::AMDGPU::VOPD::COMPONENTS</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinst/#a5c26b1db954c27889986dba3b310a8e4">llvm::MCInst::getOpcode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ac8cf6481479c40f15c819868c13c7d97">llvm::AMDGPU::getVOPDInstInfo</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/classes/llvm/mctargetasmparser/#a86c4103ccd50c7d1f8df88d71ccfef5e">llvm::MCTargetAsmParser::MII</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirnamerpass-cpp/#a05e4be4ec3e2c3587dda0e376bb6822c">Operands</a>.</p>

</div>
</div>

### depCtrError {#a90bf6e63a8b618e76af97748e777d330}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AMDGPUAsmParser::depCtrError (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc, int ErrorId, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> DepCtrName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1694 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343a902b0d55fddef6f8d651fe1035b7d4bd">llvm::Error</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ac65d03e0b232d162aff05104ed254730">llvm::AMDGPU::OPR_ID_DUPLICATE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ae1cf67368d695dbc33c5cb1a69169e68">llvm::AMDGPU::OPR_ID_UNKNOWN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a21454bd6883c7f6f749fe8fb6f9058e7">llvm::AMDGPU::OPR_ID_UNSUPPORTED</a> and <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a3eb2d4e8dbbf9dab0795060429f984ae">llvm::AMDGPU::OPR_VAL_INVALID</a>.</p>


<p>Referenced by <a href="#aec0a91539564d9315907e97bc05acdbb">parseDepCtr</a>.</p>

</div>
</div>

### findImplicitSGPRReadInVOP {#a502df3adb84c617a604b07b799b44635}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned AMDGPUAsmParser::findImplicitSGPRReadInVOP (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1803 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>

</div>
</div>

### getBLGPLoc {#aa036d1a736a687d8ed704456053f5895}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SMLoc AMDGPUAsmParser::getBLGPLoc (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a61e27c75c3334cffa54c44c02077da1e">OperandVector</a> &amp; Operands)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1750 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>

</div>
</div>

### getConstantBusLimit {#a7e2c602207905d5aca8b1a2bae459bd0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned AMDGPUAsmParser::getConstantBusLimit (unsigned Opcode)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1800 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>

</div>
</div>

### getConstLoc {#a1f3e1aaa5aa7fa68aa2b8283756b7c2c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SMLoc AMDGPUAsmParser::getConstLoc (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a61e27c75c3334cffa54c44c02077da1e">OperandVector</a> &amp; Operands)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1759 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>

</div>
</div>

### getCPolKind {#ac905bca0319767a6f6590aa62145c2be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned AMDGPUAsmParser::getCPolKind (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Id, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Mnemo, bool &amp; Disabling)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1635 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#a3de12858bdbbd0b3da179d508ff2be75">llvm::StringSwitch&lt; T, R &gt;::Case</a>, <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#a7f0e82e8a818ca43926fceb49be81661">llvm::StringSwitch&lt; T, R &gt;::Default</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/cpol/#a7d79a4b341da8ac60b91c1f4b1ea42c4a2d8942c601cf6ab6e7ee6dcfddf7e4f2">llvm::AMDGPU::CPol::DLC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/cpol/#a7d79a4b341da8ac60b91c1f4b1ea42c4a54ef769ac24b3f9c29d7f0dc5433fecd">llvm::AMDGPU::CPol::GLC</a>, <a href="#a2655a995ec2394a6f0b91e04782f37f2">isGFX940</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/cpol/#a7d79a4b341da8ac60b91c1f4b1ea42c4a3795a38ac6eb8cb14191aaba99205a87">llvm::AMDGPU::CPol::NT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/cpol/#a7d79a4b341da8ac60b91c1f4b1ea42c4a39cdb386c8e6358db46b658828960381">llvm::AMDGPU::CPol::SC0</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/cpol/#a7d79a4b341da8ac60b91c1f4b1ea42c4a4690b39a9275d5b009ecf78b08cfd27c">llvm::AMDGPU::CPol::SC1</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/cpol/#a7d79a4b341da8ac60b91c1f4b1ea42c4aca1659af59093b2b14c2f8aad41e8e2a">llvm::AMDGPU::CPol::SCC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/cpol/#a7d79a4b341da8ac60b91c1f4b1ea42c4a3a23f03bffa1237fdd6821059886a6a0">llvm::AMDGPU::CPol::SLC</a> and <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2cd8968ff703aaeb395dcd63f6805ff1">llvm::StringRef::starts_with</a>.</p>


<p>Referenced by <a href="#a905978e46c9c9a277645e938f41e1876">parseCPol</a> and <a href="#a82b29753ac1baad9801c7217c0a97dd4">parseIntWithPrefix</a>.</p>

</div>
</div>

### getFeatureBits {#a6a16aaca0a854369fe286a9d8bb3372a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const FeatureBitset &amp; anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::getFeatureBits ()</td>
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



<p>Definition at line 1582 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mctargetasmparser/#aa1990a3125ab983e6e90a452cb5a2e66">llvm::MCTargetAsmParser::getSTI</a>.</p>


<p>Referenced by <a href="#a887ee9b0b1952f6adb88d8ef15c82a53">AMDGPUAsmParser</a>, <a href="#a79c2d889df9ef0eb5ce622c66a8d7010">hasArchitectedFlatScratch</a>, <a href="#a958902b2e72c873ece47b4c7fd455668">hasFlatOffsets</a>, <a href="#ae0afa06cf1f3b2ab727dbbc42a20e9c6">hasIntClamp</a>, <a href="#a0e929744420b8548ed003f174cd3f3a0">hasInv2PiInlineImm</a> and <a href="#ab7856e68e06d844222886334c4c9fd4d">hasPartialNSAEncoding</a>.</p>

</div>
</div>

### getFlatOffsetLoc {#a61fbafda24977099a2fa826027211852}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SMLoc AMDGPUAsmParser::getFlatOffsetLoc (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a61e27c75c3334cffa54c44c02077da1e">OperandVector</a> &amp; Operands)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1748 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>

</div>
</div>

### getForcedEncodingSize {#a8c474bd3ccb2bda9a89f31fb3d7bf1cb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::getForcedEncodingSize ()</td>
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



<p>Definition at line 1590 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>Referenced by <a href="#ae55539b0211e9bc98123340231aa6902">checkTargetMatchPredicate</a>, <a href="#a10f0d2b118c2bae2632b32ffdd98e376">getMatchedVariantName</a> and <a href="#a53aaf0a7f96759d2983685f8e8a35220">getMatchedVariants</a>.</p>

</div>
</div>

### getGprCountSymbolName {#a138d6dcd6fc282c474018d7c4c0fbf7f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; StringRef &gt; AMDGPUAsmParser::getGprCountSymbolName (<a href="/web-llvm/docs/api/namespaces/anonymous-amdgpuasmparser-cpp-/#a30f503d41098d2871ebfc07b76480ea0">RegisterKind</a> RegKind)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1403 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>

</div>
</div>

### getId {#a20dfd82893fe044b468e5525572f03d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef AMDGPUAsmParser::getId ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1815 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>

</div>
</div>

### getImmLoc {#a66dae450bf482278ab7a3b6cedfdfda9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SMLoc AMDGPUAsmParser::getImmLoc (<a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#aac6196abacab3897ea9874e72d3db8fc">AMDGPUOperand::ImmTy</a> Type, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a61e27c75c3334cffa54c44c02077da1e">OperandVector</a> &amp; Operands)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1754 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>

</div>
</div>

### getInstLoc {#ad8ac0688695eefd339e10c534671b89f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SMLoc AMDGPUAsmParser::getInstLoc (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a61e27c75c3334cffa54c44c02077da1e">OperandVector</a> &amp; Operands)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1760 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>

</div>
</div>

### getLitLoc {#a0a41ae0a6ba8f96f1992efac0ae0f736}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SMLoc AMDGPUAsmParser::getLitLoc (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a61e27c75c3334cffa54c44c02077da1e">OperandVector</a> &amp; Operands, bool SearchMandatoryLiterals=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1756 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>

</div>
</div>

### getLoc {#a1993a16fc362b1d6f9547b775af976c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SMLoc AMDGPUAsmParser::getLoc ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1831 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>

</div>
</div>

### getMandatoryLitLoc {#a61d60a81d7818a2d339c950b9ae07164}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SMLoc AMDGPUAsmParser::getMandatoryLitLoc (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a61e27c75c3334cffa54c44c02077da1e">OperandVector</a> &amp; Operands)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1758 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>

</div>
</div>

### getMatchedVariantName {#a10f0d2b118c2bae2632b32ffdd98e376}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef AMDGPUAsmParser::getMatchedVariantName ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1595 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="#a8c474bd3ccb2bda9a89f31fb3d7bf1cb">getForcedEncodingSize</a>, <a href="#aae673d780d4f7a887dcdb07e93a14bfe">isForcedDPP</a>, <a href="#a2fdb1206f7410fc6fce1780b2573edbf">isForcedSDWA</a> and <a href="#a1857461798003294368b95288123a76a">isForcedVOP3</a>.</p>

</div>
</div>

### getMatchedVariants {#a53aaf0a7f96759d2983685f8e8a35220}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; unsigned &gt; AMDGPUAsmParser::getMatchedVariants ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1594 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ab9c6b351507d3c0730f4290919d43a12">llvm::ArrayRef</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpuasmvariants/#acbadb81d3b8c1eff592ec40b8a37721daa64856c91898815a78f67a6cf84c646d">llvm::AMDGPUAsmVariants::DEFAULT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpuasmvariants/#acbadb81d3b8c1eff592ec40b8a37721da1dbebe696d317896d0ede1bb630b09a8">llvm::AMDGPUAsmVariants::DPP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp/#a1d9478127b3a2f487afd3dd68811e92f">getAllVariants</a>, <a href="#a8c474bd3ccb2bda9a89f31fb3d7bf1cb">getForcedEncodingSize</a>, <a href="#aae673d780d4f7a887dcdb07e93a14bfe">isForcedDPP</a>, <a href="#a2fdb1206f7410fc6fce1780b2573edbf">isForcedSDWA</a>, <a href="#a1857461798003294368b95288123a76a">isForcedVOP3</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpuasmvariants/#acbadb81d3b8c1eff592ec40b8a37721da7c1d851117b08a78306bee251c6c966b">llvm::AMDGPUAsmVariants::SDWA</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpuasmvariants/#acbadb81d3b8c1eff592ec40b8a37721da6d772c7e4b2dbd7bc0eb7c3a83b55e35">llvm::AMDGPUAsmVariants::SDWA9</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpuasmvariants/#acbadb81d3b8c1eff592ec40b8a37721da94c0dc1d806f9998c5bafdc9c6a99dbd">llvm::AMDGPUAsmVariants::VOP3</a> and <a href="/web-llvm/docs/api/namespaces/llvm/amdgpuasmvariants/#acbadb81d3b8c1eff592ec40b8a37721da3bbbc0f34852c8f0b1300d85592b9dc2">llvm::AMDGPUAsmVariants::VOP3_DPP</a>.</p>


<p>Referenced by <a href="#a6bffa32d06d1516ee01e79b5a250c72e">matchAndEmitInstruction</a>.</p>

</div>
</div>

### getMaxNumUserSGPRs {#a4c20880d48555851fafbfc418cecc7c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::getMaxNumUserSGPRs ()</td>
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



<p>Definition at line 1561 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a2b981a267feb0c817f91ab394b62699a">llvm::AMDGPU::getMaxNumUserSGPRs</a> and <a href="/web-llvm/docs/api/classes/llvm/mctargetasmparser/#aa1990a3125ab983e6e90a452cb5a2e66">llvm::MCTargetAsmParser::getSTI</a>.</p>

</div>
</div>

### getMII {#a9f04d08c1bd449da7d97c0c66621eb97}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCInstrInfo * anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::getMII ()</td>
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



<p>Definition at line 1578 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mctargetasmparser/#a86c4103ccd50c7d1f8df88d71ccfef5e">llvm::MCTargetAsmParser::MII</a>.</p>

</div>
</div>

### getMRI {#a75ed4572cff3fae7911dba55aba309bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCRegisterInfo * anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::getMRI ()</td>
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



<p>Definition at line 1572 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="#a887ee9b0b1952f6adb88d8ef15c82a53">AMDGPUAsmParser</a> and <a href="/web-llvm/docs/api/classes/llvm/mcasmparserextension/#aa7399d73f97fdf5bcf6b19f760264848">llvm::MCAsmParserExtension::getContext</a>.</p>


<p>Referenced by <a href="#af9f84a232dd5f4bc0758374c9d26203f">cvtVOP3OpSel</a> and <a href="#a169daf8f1c8486c073f4faa87b0f402e">cvtVOP3OpSel</a>.</p>

</div>
</div>

### getNSAMaxSize {#aa879368e13ab22a5a62cd72fbb1768c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::getNSAMaxSize (bool HasSampler=false)</td>
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



<p>Definition at line 1557 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a329c56090fef55473ff6ae5bc6e8d9b8">llvm::AMDGPU::getNSAMaxSize</a> and <a href="/web-llvm/docs/api/classes/llvm/mctargetasmparser/#aa1990a3125ab983e6e90a452cb5a2e66">llvm::MCTargetAsmParser::getSTI</a>.</p>

</div>
</div>

### getOperandLoc {#a8ed62187e701fe3c99befc24d1ce92da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SMLoc AMDGPUAsmParser::getOperandLoc (std::function&lt; bool(<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand">AMDGPUOperand</a> &amp;)&gt; Test, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a61e27c75c3334cffa54c44c02077da1e">OperandVector</a> &amp; Operands)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1752 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>

</div>
</div>

### getRegLoc {#a756af86a325bfcc762d5b49a5cd41a46}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SMLoc AMDGPUAsmParser::getRegLoc (<a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> Reg, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a61e27c75c3334cffa54c44c02077da1e">OperandVector</a> &amp; Operands)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1755 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>

</div>
</div>

### getRegularReg {#a868886caf54ce07e4bfc471b9076032e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCRegister AMDGPUAsmParser::getRegularReg (<a href="/web-llvm/docs/api/namespaces/anonymous-amdgpuasmparser-cpp-/#a30f503d41098d2871ebfc07b76480ea0">RegisterKind</a> RegKind, unsigned RegNum, unsigned SubReg, unsigned RegWidth, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1398 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>

</div>
</div>

### getSMEMOffsetLoc {#abb91ce4e02e6f75a5359ac17ad9b88a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SMLoc AMDGPUAsmParser::getSMEMOffsetLoc (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a61e27c75c3334cffa54c44c02077da1e">OperandVector</a> &amp; Operands)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1749 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>

</div>
</div>

### getTargetStreamer {#a311f125284969ccb357f273b49a77f9a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AMDGPUTargetStreamer &amp; anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::getTargetStreamer ()</td>
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



<p>Definition at line 1567 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mcasmparserextension/#aef625855ca29806691daef93804afba0">llvm::MCAsmParserExtension::getParser</a>.</p>


<p>Referenced by <a href="#a01d6b546873c9427d25bf80c857cb2c4">onBeginOfFile</a>.</p>

</div>
</div>

### getToken {#a46304ba682a9e66877de380fd59db2d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AsmToken AMDGPUAsmParser::getToken ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1830 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>

</div>
</div>

### getTokenKind {#a2923c0dd11b447eaa37ab8514d1270a2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AsmToken::TokenKind AMDGPUAsmParser::getTokenKind ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1825 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>

</div>
</div>

### getTokenStr {#a126bbdc17a81565362ead20965e8b6c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef AMDGPUAsmParser::getTokenStr ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1828 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>

</div>
</div>

### hasA16 {#a6f910445c0ee081e07f20fd28f2aaad2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::hasA16 ()</td>
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



<p>Definition at line 1472 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mctargetasmparser/#aa1990a3125ab983e6e90a452cb5a2e66">llvm::MCTargetAsmParser::getSTI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a3098cf72c541f769b52598ff4e7dba74">llvm::AMDGPU::hasA16</a>.</p>


<p>Referenced by <a href="#ab2ff8b8fa2100a684cea688b74d329ab">parseNamedBit</a>.</p>

</div>
</div>

### hasArchitectedFlatScratch {#a79c2d889df9ef0eb5ce622c66a8d7010}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::hasArchitectedFlatScratch ()</td>
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



<p>Definition at line 1539 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>Reference <a href="#a6a16aaca0a854369fe286a9d8bb3372a">getFeatureBits</a>.</p>

</div>
</div>

### hasFlatOffsets {#a958902b2e72c873ece47b4c7fd455668}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::hasFlatOffsets ()</td>
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



<p>Definition at line 1535 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>Reference <a href="#a6a16aaca0a854369fe286a9d8bb3372a">getFeatureBits</a>.</p>

</div>
</div>

### hasG16 {#a0714efbd16188fd6667055435904879d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::hasG16 ()</td>
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



<p>Definition at line 1474 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mctargetasmparser/#aa1990a3125ab983e6e90a452cb5a2e66">llvm::MCTargetAsmParser::getSTI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a9adcf3cabdbd72a34b34f13f2826314b">llvm::AMDGPU::hasG16</a>.</p>

</div>
</div>

### hasGDS {#a8c75281cf5dd6fcdf9e2f75f70c3bb9f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::hasGDS ()</td>
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



<p>Definition at line 1476 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mctargetasmparser/#aa1990a3125ab983e6e90a452cb5a2e66">llvm::MCTargetAsmParser::getSTI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ac06f184d382ba9a26ef8deaea0b31cd8">llvm::AMDGPU::hasGDS</a>.</p>

</div>
</div>

### hasIntClamp {#ae0afa06cf1f3b2ab727dbbc42a20e9c6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::hasIntClamp ()</td>
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



<p>Definition at line 1549 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>Reference <a href="#a6a16aaca0a854369fe286a9d8bb3372a">getFeatureBits</a>.</p>

</div>
</div>

### hasInv2PiInlineImm {#a0e929744420b8548ed003f174cd3f3a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::hasInv2PiInlineImm ()</td>
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



<p>Definition at line 1531 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>Reference <a href="#a6a16aaca0a854369fe286a9d8bb3372a">getFeatureBits</a>.</p>

</div>
</div>

### hasKernargPreload {#ae4435ea1cd4a7f8c793cfb51552eead4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::hasKernargPreload ()</td>
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



<p>Definition at line 1565 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mctargetasmparser/#aa1990a3125ab983e6e90a452cb5a2e66">llvm::MCTargetAsmParser::getSTI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#adbe8b2394969d3cf98b70d46ce725354">llvm::AMDGPU::hasKernargPreload</a>.</p>

</div>
</div>

### hasMIMG\_R128 {#a54492f3614b470db6344ad0f37ab6089}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::hasMIMG_R128 ()</td>
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



<p>Definition at line 1464 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mctargetasmparser/#aa1990a3125ab983e6e90a452cb5a2e66">llvm::MCTargetAsmParser::getSTI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a9896067acfdb72b73caeb1ede75c9479">llvm::AMDGPU::hasMIMG_R128</a>.</p>


<p>Referenced by <a href="#ab2ff8b8fa2100a684cea688b74d329ab">parseNamedBit</a>.</p>

</div>
</div>

### hasPackedD16 {#a3922545a69d102106123e763a4a31c25}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::hasPackedD16 ()</td>
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



<p>Definition at line 1468 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mctargetasmparser/#aa1990a3125ab983e6e90a452cb5a2e66">llvm::MCTargetAsmParser::getSTI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a3856884676648fe8f7af93f6c5e60e1f">llvm::AMDGPU::hasPackedD16</a>.</p>

</div>
</div>

### hasPartialNSAEncoding {#ab7856e68e06d844222886334c4c9fd4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::hasPartialNSAEncoding ()</td>
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



<p>Definition at line 1553 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>Reference <a href="#a6a16aaca0a854369fe286a9d8bb3372a">getFeatureBits</a>.</p>

</div>
</div>

### hasSGPR102\_SGPR103 {#a993582fe0bc1fb493cd48aead4b11c16}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::hasSGPR102_SGPR103 ()</td>
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



<p>Definition at line 1543 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a626413fe751b97e13812bb7b635e6dd5">llvm::AMDGPU::isGFX9</a> and <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ad198ccff657f64471c12cc36d9aa1969">llvm::AMDGPU::isVI</a>.</p>

</div>
</div>

### hasSGPR104\_SGPR105 {#afd1547d9873dcf550d8e370a51a9c37e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::hasSGPR104_SGPR105 ()</td>
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



<p>Definition at line 1547 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ab07da835cd8eddcfffcfb4192dff59a6">llvm::AMDGPU::isGFX10Plus</a>.</p>

</div>
</div>

### initializeGprCountSymbol {#a8ddb2dcf2b1a93866457d7118786af95}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AMDGPUAsmParser::initializeGprCountSymbol (<a href="/web-llvm/docs/api/namespaces/anonymous-amdgpuasmparser-cpp-/#a30f503d41098d2871ebfc07b76480ea0">RegisterKind</a> RegKind)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1404 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>

</div>
</div>

### isCI {#ae8c11d76cf3216eae559553ba6cb045a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::isCI ()</td>
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



<p>Definition at line 1482 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mctargetasmparser/#aa1990a3125ab983e6e90a452cb5a2e66">llvm::MCTargetAsmParser::getSTI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ade135e9169df98a7457505a0ea5b6179">llvm::AMDGPU::isCI</a>.</p>

</div>
</div>

### isForcedDPP {#aae673d780d4f7a887dcdb07e93a14bfe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::isForcedDPP ()</td>
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



<p>Definition at line 1592 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>Referenced by <a href="#ae55539b0211e9bc98123340231aa6902">checkTargetMatchPredicate</a>, <a href="#a10f0d2b118c2bae2632b32ffdd98e376">getMatchedVariantName</a> and <a href="#a53aaf0a7f96759d2983685f8e8a35220">getMatchedVariants</a>.</p>

</div>
</div>

### isForcedSDWA {#a2fdb1206f7410fc6fce1780b2573edbf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::isForcedSDWA ()</td>
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



<p>Definition at line 1593 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>Referenced by <a href="#ae55539b0211e9bc98123340231aa6902">checkTargetMatchPredicate</a>, <a href="#a10f0d2b118c2bae2632b32ffdd98e376">getMatchedVariantName</a> and <a href="#a53aaf0a7f96759d2983685f8e8a35220">getMatchedVariants</a>.</p>

</div>
</div>

### isForcedVOP3 {#a1857461798003294368b95288123a76a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::isForcedVOP3 ()</td>
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



<p>Definition at line 1591 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>Referenced by <a href="#a10f0d2b118c2bae2632b32ffdd98e376">getMatchedVariantName</a> and <a href="#a53aaf0a7f96759d2983685f8e8a35220">getMatchedVariants</a>.</p>

</div>
</div>

### isGFX10 {#a4a82bb4dbeafcda7b3cf1e8f26b3cfbd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::isGFX10 ()</td>
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



<p>Definition at line 1507 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mctargetasmparser/#aa1990a3125ab983e6e90a452cb5a2e66">llvm::MCTargetAsmParser::getSTI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a27e5626ce22d0cd09916837dc88b7efe">llvm::AMDGPU::isGFX10</a>.</p>

</div>
</div>

### isGFX10\_AEncoding {#a8d868e94e982ab01119ccdfd484a07ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::isGFX10_AEncoding ()</td>
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



<p>Definition at line 1525 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mctargetasmparser/#aa1990a3125ab983e6e90a452cb5a2e66">llvm::MCTargetAsmParser::getSTI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a65249b090745fad14294b652b417566b">llvm::AMDGPU::isGFX10_AEncoding</a>.</p>

</div>
</div>

### isGFX10\_BEncoding {#a3bfb807b985518a3727b9c1dee859f46}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::isGFX10_BEncoding ()</td>
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



<p>Definition at line 1527 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mctargetasmparser/#aa1990a3125ab983e6e90a452cb5a2e66">llvm::MCTargetAsmParser::getSTI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a03038e2ec3d91a361fbbb066e575de9a">llvm::AMDGPU::isGFX10_BEncoding</a>.</p>

</div>
</div>

### isGFX10Plus {#a60199205d0327ba1bec2eb9aaac9f3b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::isGFX10Plus ()</td>
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



<p>Definition at line 1511 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mctargetasmparser/#aa1990a3125ab983e6e90a452cb5a2e66">llvm::MCTargetAsmParser::getSTI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ab07da835cd8eddcfffcfb4192dff59a6">llvm::AMDGPU::isGFX10Plus</a>.</p>


<p>Referenced by <a href="#a3c48b1ea644084c3a3e9751a96f10a11">isSupportedDPPCtrl</a>, <a href="#a905978e46c9c9a277645e938f41e1876">parseCPol</a>, <a href="#a4c31665501f9b711e245f1b4e201683b">parseDim</a>, <a href="#a59d9c798683c4a134a731c43840d62aa">parseDPP8</a>, <a href="#aae18974f031b21f7dd37b072a1cbe24d">parseFORMAT</a>, <a href="#af09dfe84acccdfc6a55c91388892da8e">parseInstruction</a>, <a href="#ad0ddd35516c856b2c41317d0c1febdea">parseSymbolicSplitFormat</a> and <a href="#a9cba0b00a0bcffcb413914db33553071">parseSymbolicUnifiedFormat</a>.</p>

</div>
</div>

### isGFX11 {#ae7af5638a45b8a78d1ac005bcb225280}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::isGFX11 ()</td>
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



<p>Definition at line 1513 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mctargetasmparser/#aa1990a3125ab983e6e90a452cb5a2e66">llvm::MCTargetAsmParser::getSTI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a3d6f72ac6639b51b7a8a54368ad6332e">llvm::AMDGPU::isGFX11</a>.</p>

</div>
</div>

### isGFX11Plus {#a93fd6449c3f63d76ff63b7231aec9269}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::isGFX11Plus ()</td>
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



<p>Definition at line 1517 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mctargetasmparser/#aa1990a3125ab983e6e90a452cb5a2e66">llvm::MCTargetAsmParser::getSTI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#aa5f3cd2ec6af3adbc143654720b1214b">llvm::AMDGPU::isGFX11Plus</a>.</p>


<p>Referenced by <a href="#afb7bcf8b1454072ac361ae5764cd4abc">convertDppBoundCtrl</a>.</p>

</div>
</div>

### isGFX12 {#ab6c0ad5500b6cf0018b49d5d9bc477f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::isGFX12 ()</td>
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



<p>Definition at line 1521 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mctargetasmparser/#aa1990a3125ab983e6e90a452cb5a2e66">llvm::MCTargetAsmParser::getSTI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a7b0ac753cc89fce435513a67b4014bd8">llvm::AMDGPU::isGFX12</a>.</p>

</div>
</div>

### isGFX12Plus {#a9d0aa89a1f031ab50a8126419a8191be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::isGFX12Plus ()</td>
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



<p>Definition at line 1523 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mctargetasmparser/#aa1990a3125ab983e6e90a452cb5a2e66">llvm::MCTargetAsmParser::getSTI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a318d59d6a50364a460b64bb7ad1f17d0">llvm::AMDGPU::isGFX12Plus</a>.</p>


<p>Referenced by <a href="#a905978e46c9c9a277645e938f41e1876">parseCPol</a>.</p>

</div>
</div>

### isGFX9 {#abedd2529418cdf49b008a6c05bf3baec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::isGFX9 ()</td>
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



<p>Definition at line 1490 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mctargetasmparser/#aa1990a3125ab983e6e90a452cb5a2e66">llvm::MCTargetAsmParser::getSTI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a626413fe751b97e13812bb7b635e6dd5">llvm::AMDGPU::isGFX9</a>.</p>


<p>Referenced by <a href="#a3c48b1ea644084c3a3e9751a96f10a11">isSupportedDPPCtrl</a> and <a href="#ab2ff8b8fa2100a684cea688b74d329ab">parseNamedBit</a>.</p>

</div>
</div>

### isGFX90A {#aa4556f85d06de11c2b68e6b4b781e7ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::isGFX90A ()</td>
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



<p>Definition at line 1495 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mctargetasmparser/#aa1990a3125ab983e6e90a452cb5a2e66">llvm::MCTargetAsmParser::getSTI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a6927ea03a5a90995645230645e0fbd89">llvm::AMDGPU::isGFX90A</a>.</p>


<p>Referenced by <a href="#a3c48b1ea644084c3a3e9751a96f10a11">isSupportedDPPCtrl</a> and <a href="#a905978e46c9c9a277645e938f41e1876">parseCPol</a>.</p>

</div>
</div>

### isGFX940 {#a2655a995ec2394a6f0b91e04782f37f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::isGFX940 ()</td>
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



<p>Definition at line 1499 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mctargetasmparser/#aa1990a3125ab983e6e90a452cb5a2e66">llvm::MCTargetAsmParser::getSTI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a3aa6cae3cc5611453bbb619f354ea415">llvm::AMDGPU::isGFX940</a>.</p>


<p>Referenced by <a href="#ac905bca0319767a6f6590aa62145c2be">getCPolKind</a>.</p>

</div>
</div>

### isGFX9Plus {#aa58939d2807dd46c0c31c68ed255b59b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::isGFX9Plus ()</td>
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



<p>Definition at line 1503 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mctargetasmparser/#aa1990a3125ab983e6e90a452cb5a2e66">llvm::MCTargetAsmParser::getSTI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ac251a1b5841022f34ff2791b1ce3b690">llvm::AMDGPU::isGFX9Plus</a>.</p>

</div>
</div>

### isId {#a0ade8085c04ca131cd06be151b500037}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUAsmParser::isId (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Id)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1812 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>

</div>
</div>

### isId {#abdace62f83edae6890e8eb5ba67ed074}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUAsmParser::isId (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/asmtoken">AsmToken</a> &amp; Token, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Id)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1813 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>

</div>
</div>

### isInlineConstant {#a508f82e8c2f272d6702a6cc80b19ad89}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUAsmParser::isInlineConstant (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned OpIdx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1802 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>

</div>
</div>

### isModifier {#a3740088be499ac1b2813ea1d6904ef15}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUAsmParser::isModifier ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1650 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#a9836d66cf9617f7396887c361cbbded0">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::getToken</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#a710e72de4b87af42e7605679d1fb2c24">llvm::AsmToken::is</a>, <a href="#a9a76b985d6b897a055389b82198509ee">isOpcodeModifierWithVal</a>, <a href="#aae8e311d01222d265293e010df5bc7f5">isOperandModifier</a>, <a href="#a84254eeb4895568119e37386e6e1ba71">isRegOrOperandModifier</a> and <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a1189cff13fec34dee4d501f4d7a7e3a2">llvm::AsmToken::Minus</a>.</p>


<p>Referenced by <a href="#a62ccca1cd262d040e8aee057ab0d22d5">parseImm</a>, <a href="#a82b29753ac1baad9801c7217c0a97dd4">parseIntWithPrefix</a>, <a href="#a60728802d4e08feb0abc5cc75c3eefc9">parseRegOrImm</a> and <a href="#a082f5bbf706dd5cd5bcb35d7bdf5564f">parseSOPPBrTarget</a>.</p>

</div>
</div>

### isNamedOperandModifier {#ab69ace2a64f183c1e0600a4155b0a976}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUAsmParser::isNamedOperandModifier (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/asmtoken">AsmToken</a> &amp; Token, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/asmtoken">AsmToken</a> &amp; NextToken)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1653 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#a3168618a19701d0fb78aefb4d4e664de">llvm::AsmToken::getString</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a806fe218bb80f0671afdad4cec36569b">llvm::AsmToken::Identifier</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#a710e72de4b87af42e7605679d1fb2c24">llvm::AsmToken::is</a> and <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a85fc8bab3d6f4fa71b0d876dd9a96e1a">llvm::AsmToken::LParen</a>.</p>


<p>Referenced by <a href="#aae8e311d01222d265293e010df5bc7f5">isOperandModifier</a> and <a href="#a82b29753ac1baad9801c7217c0a97dd4">parseIntWithPrefix</a>.</p>

</div>
</div>

### isOpcodeModifierWithVal {#a9a76b985d6b897a055389b82198509ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUAsmParser::isOpcodeModifierWithVal (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/asmtoken">AsmToken</a> &amp; Token, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/asmtoken">AsmToken</a> &amp; NextToken)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1654 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a29a91140113f0cc0421255bec47955f5">llvm::AsmToken::Colon</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a806fe218bb80f0671afdad4cec36569b">llvm::AsmToken::Identifier</a> and <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#a710e72de4b87af42e7605679d1fb2c24">llvm::AsmToken::is</a>.</p>


<p>Referenced by <a href="#a3740088be499ac1b2813ea1d6904ef15">isModifier</a> and <a href="#a82b29753ac1baad9801c7217c0a97dd4">parseIntWithPrefix</a>.</p>

</div>
</div>

### isOperandModifier {#aae8e311d01222d265293e010df5bc7f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUAsmParser::isOperandModifier (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/asmtoken">AsmToken</a> &amp; Token, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/asmtoken">AsmToken</a> &amp; NextToken)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1651 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#a710e72de4b87af42e7605679d1fb2c24">llvm::AsmToken::is</a>, <a href="#ab69ace2a64f183c1e0600a4155b0a976">isNamedOperandModifier</a> and <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a7da9940ae6624563c0ff853d5fa7abc5">llvm::AsmToken::Pipe</a>.</p>


<p>Referenced by <a href="#a3740088be499ac1b2813ea1d6904ef15">isModifier</a>, <a href="#a84254eeb4895568119e37386e6e1ba71">isRegOrOperandModifier</a> and <a href="#a82b29753ac1baad9801c7217c0a97dd4">parseIntWithPrefix</a>.</p>

</div>
</div>

### isRegister {#ae6bbe25af68d69ac51381e350fc82ea8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUAsmParser::isRegister ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1401 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>

</div>
</div>

### isRegister {#a1008e28f0bfda60a8f55da9905c7907d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUAsmParser::isRegister (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/asmtoken">AsmToken</a> &amp; Token, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/asmtoken">AsmToken</a> &amp; NextToken)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1402 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>

</div>
</div>

### isRegOrOperandModifier {#a84254eeb4895568119e37386e6e1ba71}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUAsmParser::isRegOrOperandModifier (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/asmtoken">AsmToken</a> &amp; Token, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/asmtoken">AsmToken</a> &amp; NextToken)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1652 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>Reference <a href="#aae8e311d01222d265293e010df5bc7f5">isOperandModifier</a>.</p>


<p>Referenced by <a href="#a3740088be499ac1b2813ea1d6904ef15">isModifier</a> and <a href="#a82b29753ac1baad9801c7217c0a97dd4">parseIntWithPrefix</a>.</p>

</div>
</div>

### isSI {#af6fc1eb24bc3b5beaf4a2a292ba1d759}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::isSI ()</td>
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



<p>Definition at line 1478 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mctargetasmparser/#aa1990a3125ab983e6e90a452cb5a2e66">llvm::MCTargetAsmParser::getSTI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a58f60f9ac04e27846a67a951d920837e">llvm::AMDGPU::isSI</a>.</p>

</div>
</div>

### isSupportedDPPCtrl {#a3c48b1ea644084c3a3e9751a96f10a11}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUAsmParser::isSupportedDPPCtrl (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Ctrl, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a61e27c75c3334cffa54c44c02077da1e">OperandVector</a> &amp; Operands)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1894 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="#a60199205d0327ba1bec2eb9aaac9f3b3">isGFX10Plus</a>, <a href="#abedd2529418cdf49b008a6c05bf3baec">isGFX9</a>, <a href="#aa4556f85d06de11c2b68e6b4b781e7ab">isGFX90A</a>, <a href="#a8e77658ae7e2c85817cc9e6fb62901bf">isVI</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirnamerpass-cpp/#a05e4be4ec3e2c3587dda0e376bb6822c">Operands</a>.</p>


<p>Referenced by <a href="#a21401db3d85754eab356474360dd2394">cvtVOP3P</a> and <a href="#af1e3005e43d45d207eb661fa024b1753">parseDPPCtrl</a>.</p>

</div>
</div>

### isSupportedMnemo {#a7234587538030f6642812b4afd0a143a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUAsmParser::isSupportedMnemo (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Mnemo, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/featurebitset">FeatureBitset</a> &amp; FBS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1805 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>

</div>
</div>

### isSupportedMnemo {#a44f9030bb4b867ff48c812c45587f729}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUAsmParser::isSupportedMnemo (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Mnemo, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/featurebitset">FeatureBitset</a> &amp; FBS, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; unsigned &gt; Variants)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1807 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>

</div>
</div>

### isToken {#af6daa0ef9939708fdb6e42cf199d3e86}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUAsmParser::isToken (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039">AsmToken::TokenKind</a> Kind)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1814 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>

</div>
</div>

### isVI {#a8e77658ae7e2c85817cc9e6fb62901bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::isVI ()</td>
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



<p>Definition at line 1486 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mctargetasmparser/#aa1990a3125ab983e6e90a452cb5a2e66">llvm::MCTargetAsmParser::getSTI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ad198ccff657f64471c12cc36d9aa1969">llvm::AMDGPU::isVI</a>.</p>


<p>Referenced by <a href="#af5e01806d4b89fadd4b471243098cc12">cvtSdwaVOPC</a> and <a href="#a3c48b1ea644084c3a3e9751a96f10a11">isSupportedDPPCtrl</a>.</p>

</div>
</div>

### lex {#abf132b7452e6dcb0ce988fb7984dc93f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AMDGPUAsmParser::lex ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1832 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>

</div>
</div>

### matchAndEmitInstruction {#a6bffa32d06d1516ee01e79b5a250c72e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUAsmParser::matchAndEmitInstruction (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> IDLoc, unsigned &amp; Opcode, <a href="/web-llvm/docs/api/namespaces/llvm/#a61e27c75c3334cffa54c44c02077da1e">OperandVector</a> &amp; Operands, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp; Out, uint64_t &amp; ErrorInfo, bool MatchingInlineAsm)</td>
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

<p>Recognize a series of operands of a parsed instruction as an actual MCInst and emit it to the specified MCStreamer.</p>


<p>This returns false on success and returns true on failure to match.</p>


<p>On failure, the target parser is responsible for emitting a diagnostic explaining the match failure.</p>


<p>Definition at line 1606 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a2e263d122b10b0bcc1bbf6c63202208c">llvm::MCStreamer::emitInstruction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343a902b0d55fddef6f8d651fe1035b7d4bd">llvm::Error</a>, <a href="#a53aaf0a7f96759d2983685f8e8a35220">getMatchedVariants</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#a630948d3f118fad4a7e9d4764ba76a90">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::getStartLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/mctargetasmparser/#aa1990a3125ab983e6e90a452cb5a2e66">llvm::MCTargetAsmParser::getSTI</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#a9836d66cf9617f7396887c361cbbded0">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::getToken</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp/#ae58d7ce01c34f2ecb225e1dedfa736e3">isInvalidVOPDY</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/classes/llvm/mctargetasmparser/#a29cb086c359baadd9df6e5f101e41007a36e5dd518d3d92d2d6207a9ed03d6b48">llvm::MCTargetAsmParser::Match_InvalidOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/mctargetasmparser/#a29cb086c359baadd9df6e5f101e41007ad4be62682e617f3f38dac1faa3c0757c">llvm::MCTargetAsmParser::Match_MissingFeature</a>, <a href="/web-llvm/docs/api/classes/llvm/mctargetasmparser/#a29cb086c359baadd9df6e5f101e41007a139f943e96519daf325c91ae28f28683">llvm::MCTargetAsmParser::Match_MnemonicFail</a>, <a href="/web-llvm/docs/api/classes/llvm/mctargetasmparser/#a29cb086c359baadd9df6e5f101e41007a2d220d934e235f8d0ff1eb07adf2b483">llvm::MCTargetAsmParser::Match_Success</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirnamerpass-cpp/#a05e4be4ec3e2c3587dda0e376bb6822c">Operands</a> and <a href="/web-llvm/docs/api/classes/llvm/mcinst/#a580e2a6e8a248c5a4a814c03186e9241">llvm::MCInst::setLoc</a>.</p>

</div>
</div>

### matchDfmtNfmt {#aea4cc2cee6a095dbbd1f35f80ad3c3e1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUAsmParser::matchDfmtNfmt (int64_t &amp; Dfmt, int64_t &amp; Nfmt, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> FormatStr, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1686 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/mtbufformat/#a1639288a4e781b242be214c44eb42c4ca6523540e869e65331060df57c9add409">llvm::AMDGPU::MTBUFFormat::DFMT_UNDEF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343a902b0d55fddef6f8d651fe1035b7d4bd">llvm::Error</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/mtbufformat/#ace425756e45dc13fdd4ee49616cbe202">llvm::AMDGPU::MTBUFFormat::getDfmt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/mtbufformat/#ac4ceeee60ddf9662daddba7a110cd607">llvm::AMDGPU::MTBUFFormat::getNfmt</a>, <a href="/web-llvm/docs/api/classes/llvm/mctargetasmparser/#aa1990a3125ab983e6e90a452cb5a2e66">llvm::MCTargetAsmParser::getSTI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/mtbufformat/#a5d70ded8d54418ba62fd42d38c15ad5fa236bdeff44903627faf337bd91ca344e">llvm::AMDGPU::MTBUFFormat::NFMT_UNDEF</a>.</p>


<p>Referenced by <a href="#a82b29753ac1baad9801c7217c0a97dd4">parseIntWithPrefix</a> and <a href="#ad0ddd35516c856b2c41317d0c1febdea">parseSymbolicSplitFormat</a>.</p>

</div>
</div>

### onBeginOfFile {#a01d6b546873c9427d25bf80c857cb2c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AMDGPUAsmParser::onBeginOfFile ()</td>
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



<p>Definition at line 1835 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/amdgputargetstreamer/#a84c5158f5734778cd2e73a84e4247621">llvm::AMDGPUTargetStreamer::EmitDirectiveAMDGCNTarget</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparserextension/#aef625855ca29806691daef93804afba0">llvm::MCAsmParserExtension::getParser</a>, <a href="/web-llvm/docs/api/classes/llvm/mctargetasmparser/#aa1990a3125ab983e6e90a452cb5a2e66">llvm::MCTargetAsmParser::getSTI</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparserextension/#ad4802c6230c2d4e9ddf64155b05344a9">llvm::MCAsmParserExtension::getStreamer</a>, <a href="#a311f125284969ccb357f273b49a77f9a">getTargetStreamer</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetstreamer/#a256a30b3dc1c110426c6b0000a547761">llvm::AMDGPUTargetStreamer::initializeTargetID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a3d357ec8432b58835aaa34defcc4eff9">llvm::AMDGPU::isHsaAbi</a> and <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a060ea888d89f5d59a5743118e429296f">llvm::Triple::r600</a>.</p>

</div>
</div>

### OperandMode {#a5108ba4d1e0aaaf1c45f0694b21c482b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::OperandMode </td>
</tr>
</table>
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
<td class="doxyEnumItemName">OperandMode_Default<a id="a5108ba4d1e0aaaf1c45f0694b21c482baabf56f6ac3c8d8fb9a3479b29c7a8cdf"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OperandMode_NSA<a id="a5108ba4d1e0aaaf1c45f0694b21c482ba97d4520a0e14c2103b5ddaac94a65bf9"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 1411 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>

</div>
</div>

### OptionalImmIndexMap {#ad427f76801ceb008e1d15f59313cff3d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::OptionalImmIndexMap =  std::map&lt;AMDGPUOperand::ImmTy, unsigned&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1416 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>

</div>
</div>

### OutOfRangeError {#abb6d098a03fdc973b72c051df5841436}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUAsmParser::OutOfRangeError (<a href="/web-llvm/docs/api/classes/llvm/smrange">SMRange</a> Range)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1337 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>

</div>
</div>

### ParseAMDGPURegister {#ad5507f1367d663ce52ade9dda3d8c3be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUAsmParser::ParseAMDGPURegister (<a href="/web-llvm/docs/api/namespaces/anonymous-amdgpuasmparser-cpp-/#a30f503d41098d2871ebfc07b76480ea0">RegisterKind</a> &amp; RegKind, <a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> &amp; Reg, unsigned &amp; RegNum, unsigned &amp; RegWidth, bool RestoreOnFailure=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1382 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>

</div>
</div>

### ParseAMDGPURegister {#aa31d05b9b3e2274c1c609e9068f485ef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUAsmParser::ParseAMDGPURegister (<a href="/web-llvm/docs/api/namespaces/anonymous-amdgpuasmparser-cpp-/#a30f503d41098d2871ebfc07b76480ea0">RegisterKind</a> &amp; RegKind, <a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> &amp; Reg, unsigned &amp; RegNum, unsigned &amp; RegWidth, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/asmtoken">AsmToken</a> &gt; &amp; Tokens)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1385 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>

</div>
</div>

### ParseAMDKernelCodeTValue {#a158cd152420a04034bd0835be80ea0ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUAsmParser::ParseAMDKernelCodeTValue (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> ID, <a href="/web-llvm/docs/api/structs/llvm/amdgpu/amdgpumckernelcodet">AMDGPUMCKernelCodeT</a> &amp; Header)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1362 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>

</div>
</div>

### ParseAsAbsoluteExpression {#a543505c1bc44ee2792883d40ed5d18ef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUAsmParser::ParseAsAbsoluteExpression (uint32_t &amp; Ret)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1336 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>

</div>
</div>

### parseBLGP {#a3ad635dcc304d17a852fa28adac99bb9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ParseStatus AMDGPUAsmParser::parseBLGP (<a href="/web-llvm/docs/api/namespaces/llvm/#a61e27c75c3334cffa54c44c02077da1e">OperandVector</a> &amp; Operands)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1684 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#aac6196abacab3897ea9874e72d3db8fcaf1b6a24364959b43f2ba2a7cbe099577">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::ImmTyBLGP</a>, <a href="/web-llvm/docs/api/classes/llvm/parsestatus/#a78a275295bb9a176cb9fcfa9bbc43db1">llvm::ParseStatus::isNoMatch</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirnamerpass-cpp/#a05e4be4ec3e2c3587dda0e376bb6822c">Operands</a>, <a href="#a82b29753ac1baad9801c7217c0a97dd4">parseIntWithPrefix</a> and <a href="#ac9d07a4881948a410fcba201eeb36480">parseOperandArrayWithPrefix</a>.</p>


<p>Referenced by <a href="#a82b29753ac1baad9801c7217c0a97dd4">parseIntWithPrefix</a>.</p>

</div>
</div>

### parseBoolReg {#a5c229c26ac4e66cb56bd6d00cb6e86d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ParseStatus AMDGPUAsmParser::parseBoolReg (<a href="/web-llvm/docs/api/namespaces/llvm/#a61e27c75c3334cffa54c44c02077da1e">OperandVector</a> &amp; Operands)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1845 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirnamerpass-cpp/#a05e4be4ec3e2c3587dda0e376bb6822c">Operands</a> and <a href="#ab2ca31c142db4eaa8c629f36d61339bf">parseReg</a>.</p>

</div>
</div>

### parseCnt {#a7e283edef71599b2ffccac2843fce5a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUAsmParser::parseCnt (int64_t &amp; IntVal)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1690 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a829ba931cbc81b6741c399abca551130">llvm::AsmToken::Amp</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039ac4b2675d2cb80935b789d9f140092e25">llvm::AsmToken::Comma</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ac9ad1c3b2c132bb923532658442fa53d">llvm::AMDGPU::decodeExpcnt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a5fb6ac70a302c2950012a955ef7b1d6a">llvm::AMDGPU::decodeLgkmcnt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#aef5f5f2f99f041ac50a50e80446dd80c">llvm::AMDGPU::decodeVmcnt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp/#ac9d9799b3fbd93955c7584681187805f">encodeCnt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a7d9da1d38203f7899139c8dedb15d97c">llvm::AMDGPU::encodeExpcnt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ade75980e3c0b71d253a7381a15d8ed00">llvm::AMDGPU::encodeLgkmcnt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ac95f41127d78da414e20eb091961726c">llvm::AMDGPU::encodeVmcnt</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039ae10c5f59f330bfd15608e1dda213a98f">llvm::AsmToken::EndOfStatement</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#aca439bf65258d9d8d057812938b617c5">llvm::StringRef::ends_with</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343a902b0d55fddef6f8d651fe1035b7d4bd">llvm::Error</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2cd7b2e49608a96ba42f59f642cf99ac">llvm::Failed</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2c346c56fb9021d994675d1710d2d551">llvm::getCPU</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a4c450943f424116a9b6b9a3db451af6c">llvm::AMDGPU::getIsaVersion</a>, <a href="/web-llvm/docs/api/classes/llvm/mctargetasmparser/#aa1990a3125ab983e6e90a452cb5a2e66">llvm::MCTargetAsmParser::getSTI</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a806fe218bb80f0671afdad4cec36569b">llvm::AsmToken::Identifier</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#a5d8227b613dc0aff33ca27637d41c74a">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isToken</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a85fc8bab3d6f4fa71b0d876dd9a96e1a">llvm::AsmToken::LParen</a> and <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a94d3b37c4d0fe4ca14de941b7c905322">llvm::AsmToken::RParen</a>.</p>


<p>Referenced by <a href="#a82b29753ac1baad9801c7217c0a97dd4">parseIntWithPrefix</a> and <a href="#ac3b25b92e123263ee61ca38bdee04828">parseSWaitCnt</a>.</p>

</div>
</div>

### parseCPol {#a905978e46c9c9a277645e938f41e1876}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ParseStatus AMDGPUAsmParser::parseCPol (<a href="/web-llvm/docs/api/namespaces/llvm/#a61e27c75c3334cffa54c44c02077da1e">OperandVector</a> &amp; Operands)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1636 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#aa6d2ada1e702e79ab63562d3cbd03ee0">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::CreateImm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/cpol/#a7d79a4b341da8ac60b91c1f4b1ea42c4a2d8942c601cf6ab6e7ee6dcfddf7e4f2">llvm::AMDGPU::CPol::DLC</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/statistic-cpp/#a558f5c44426d0eb7abb82a65e8892d9a">Enabled</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343a902b0d55fddef6f8d651fe1035b7d4bd">llvm::Error</a>, <a href="#ac905bca0319767a6f6590aa62145c2be">getCPolKind</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#a9836d66cf9617f7396887c361cbbded0">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::getToken</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#aac6196abacab3897ea9874e72d3db8fcae93a1de3d01070de353bc7ac2c243eaf">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::ImmTyCPol</a>, <a href="/web-llvm/docs/api/classes/llvm/parsestatus/#a01a3be3f469c6f0a26bf9a5180b7b322">llvm::ParseStatus::isFailure</a>, <a href="#a60199205d0327ba1bec2eb9aaac9f3b3">isGFX10Plus</a>, <a href="#a9d0aa89a1f031ab50a8126419a8191be">isGFX12Plus</a>, <a href="#aa4556f85d06de11c2b68e6b4b781e7ab">isGFX90A</a>, <a href="/web-llvm/docs/api/classes/llvm/parsestatus/#a78a275295bb9a176cb9fcfa9bbc43db1">llvm::ParseStatus::isNoMatch</a>, <a href="/web-llvm/docs/api/classes/llvm/parsestatus/#a60b6e83411b03e0c4dc4858bb5e9f912">llvm::ParseStatus::isSuccess</a>, <a href="/web-llvm/docs/api/classes/llvm/parsestatus/#a670f6078c68c861b8ecaa1ec082fd736">llvm::ParseStatus::NoMatch</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirnamerpass-cpp/#a05e4be4ec3e2c3587dda0e376bb6822c">Operands</a>, <a href="#a1a55d776c65cd09db2546fb584a2de47">parseScope</a>, <a href="#a3a4cad862e9d4dda82fe89b5a2557e97">parseTH</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/cpol/#a7d79a4b341da8ac60b91c1f4b1ea42c4aca1659af59093b2b14c2f8aad41e8e2a">llvm::AMDGPU::CPol::SCC</a> and <a href="/web-llvm/docs/api/classes/llvm/parsestatus/#a66a81b1ff471ed3e871c93599118f34c">llvm::ParseStatus::Success</a>.</p>


<p>Referenced by <a href="#a82b29753ac1baad9801c7217c0a97dd4">parseIntWithPrefix</a>.</p>

</div>
</div>

### parseCustomOperand {#a877255e198cc72078a64aa635548b03b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ParseStatus AMDGPUAsmParser::parseCustomOperand (<a href="/web-llvm/docs/api/namespaces/llvm/#a61e27c75c3334cffa54c44c02077da1e">OperandVector</a> &amp; Operands, unsigned MCK)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1838 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#aac6196abacab3897ea9874e72d3db8fcad673fd3693f21e595b61e0efcfebace7">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::ImmTyGDS</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#aac6196abacab3897ea9874e72d3db8fca0d40ab857cb9338f800d4102f5a5fb3c">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::ImmTyTFE</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirnamerpass-cpp/#a05e4be4ec3e2c3587dda0e376bb6822c">Operands</a>, <a href="#ab2ff8b8fa2100a684cea688b74d329ab">parseNamedBit</a> and <a href="#a40cae821d596ce5a10da36c3d1836dac">parseTokenOp</a>.</p>

</div>
</div>

### parseDelay {#aac5924990c1b6a01f79b3dd8019f5f7b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUAsmParser::parseDelay (int64_t &amp; Delay)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1697 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#a3de12858bdbbd0b3da179d508ff2be75">llvm::StringSwitch&lt; T, R &gt;::Case</a>, <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#a7f0e82e8a818ca43926fceb49be81661">llvm::StringSwitch&lt; T, R &gt;::Default</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343a902b0d55fddef6f8d651fe1035b7d4bd">llvm::Error</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a806fe218bb80f0671afdad4cec36569b">llvm::AsmToken::Identifier</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a85fc8bab3d6f4fa71b0d876dd9a96e1a">llvm::AsmToken::LParen</a> and <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a94d3b37c4d0fe4ca14de941b7c905322">llvm::AsmToken::RParen</a>.</p>


<p>Referenced by <a href="#aec0a91539564d9315907e97bc05acdbb">parseDepCtr</a> and <a href="#a493337bf1e3308881e03af9142a5bb5a">parseSDelayALU</a>.</p>

</div>
</div>

### parseDepCtr {#aec0a91539564d9315907e97bc05acdbb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseDepCtr (int64_t &amp; IntVal, unsigned &amp; Mask)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1693 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="#a90bf6e63a8b618e76af97748e777d330">depCtrError</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirnamerpass-cpp/#a05e4be4ec3e2c3587dda0e376bb6822c">Operands</a>, <a href="#aac5924990c1b6a01f79b3dd8019f5f7b">parseDelay</a>, <a href="#aec0a91539564d9315907e97bc05acdbb">parseDepCtr</a>, <a href="#a16bbeaa5435876a2a30093aa9f7adc09">parseHwreg</a> and <a href="#a493337bf1e3308881e03af9142a5bb5a">parseSDelayALU</a>.</p>


<p>Referenced by <a href="#aec0a91539564d9315907e97bc05acdbb">parseDepCtr</a> and <a href="#aa54525f0109858da308fa32559539255">parseDepCtr</a>.</p>

</div>
</div>

### parseDepCtr {#aa54525f0109858da308fa32559539255}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ParseStatus AMDGPUAsmParser::parseDepCtr (<a href="/web-llvm/docs/api/namespaces/llvm/#a61e27c75c3334cffa54c44c02077da1e">OperandVector</a> &amp; Operands)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1695 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#aa6d2ada1e702e79ab63562d3cbd03ee0">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::CreateImm</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039ae10c5f59f330bfd15608e1dda213a98f">llvm::AsmToken::EndOfStatement</a>, <a href="/web-llvm/docs/api/classes/llvm/parsestatus/#a07e0e7c7dba79a89519092de57d17358">llvm::ParseStatus::Failure</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/depctr/#aed8a3720f645c7bbc2321b96e35d0db1">llvm::AMDGPU::DepCtr::getDefaultDepCtrEncoding</a>, <a href="/web-llvm/docs/api/classes/llvm/mctargetasmparser/#aa1990a3125ab983e6e90a452cb5a2e66">llvm::MCTargetAsmParser::getSTI</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a806fe218bb80f0671afdad4cec36569b">llvm::AsmToken::Identifier</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#a5d8227b613dc0aff33ca27637d41c74a">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isToken</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a85fc8bab3d6f4fa71b0d876dd9a96e1a">llvm::AsmToken::LParen</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirnamerpass-cpp/#a05e4be4ec3e2c3587dda0e376bb6822c">Operands</a>, <a href="#aec0a91539564d9315907e97bc05acdbb">parseDepCtr</a> and <a href="/web-llvm/docs/api/classes/llvm/parsestatus/#a66a81b1ff471ed3e871c93599118f34c">llvm::ParseStatus::Success</a>.</p>

</div>
</div>

### parseDfmtNfmt {#a157290e9f9aa7ff61c53d131b090e50a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ParseStatus AMDGPUAsmParser::parseDfmtNfmt (int64_t &amp; Format)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1673 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039ac4b2675d2cb80935b789d9f140092e25">llvm::AsmToken::Comma</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/mtbufformat/#a1639288a4e781b242be214c44eb42c4ca8b7ccf769433236212a15d3076881aa7">llvm::AMDGPU::MTBUFFormat::DFMT_DEFAULT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/mtbufformat/#a1639288a4e781b242be214c44eb42c4cac45aafc770d4681d282f7beb40d4ad03">llvm::AMDGPU::MTBUFFormat::DFMT_MAX</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/mtbufformat/#a1639288a4e781b242be214c44eb42c4ca6523540e869e65331060df57c9add409">llvm::AMDGPU::MTBUFFormat::DFMT_UNDEF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/mtbufformat/#a88658310897a5ba8565bf1366213a307">llvm::AMDGPU::MTBUFFormat::encodeDfmtNfmt</a>, <a href="/web-llvm/docs/api/classes/llvm/parsestatus/#a07e0e7c7dba79a89519092de57d17358">llvm::ParseStatus::Failure</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/mtbufformat/#a5d70ded8d54418ba62fd42d38c15ad5fa3861fe2916797a81c4ed930d3b12653a">llvm::AMDGPU::MTBUFFormat::NFMT_DEFAULT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/mtbufformat/#a5d70ded8d54418ba62fd42d38c15ad5fa666d8c0c7a439fa8b46a5b6f43214466">llvm::AMDGPU::MTBUFFormat::NFMT_MAX</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/mtbufformat/#a5d70ded8d54418ba62fd42d38c15ad5fa236bdeff44903627faf337bd91ca344e">llvm::AMDGPU::MTBUFFormat::NFMT_UNDEF</a>, <a href="/web-llvm/docs/api/classes/llvm/parsestatus/#a670f6078c68c861b8ecaa1ec082fd736">llvm::ParseStatus::NoMatch</a>, <a href="/web-llvm/docs/api/classes/llvm/parsestatus/#a66a81b1ff471ed3e871c93599118f34c">llvm::ParseStatus::Success</a> and <a href="#a4110e462b4bf86153ae19de70eb84443">tryParseFmt</a>.</p>


<p>Referenced by <a href="#aae18974f031b21f7dd37b072a1cbe24d">parseFORMAT</a> and <a href="#a82b29753ac1baad9801c7217c0a97dd4">parseIntWithPrefix</a>.</p>

</div>
</div>

### parseDim {#a4c31665501f9b711e245f1b4e201683b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ParseStatus AMDGPUAsmParser::parseDim (<a href="/web-llvm/docs/api/namespaces/llvm/#a61e27c75c3334cffa54c44c02077da1e">OperandVector</a> &amp; Operands)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1890 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a29a91140113f0cc0421255bec47955f5">llvm::AsmToken::Colon</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#aa6d2ada1e702e79ab63562d3cbd03ee0">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::CreateImm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343a902b0d55fddef6f8d651fe1035b7d4bd">llvm::Error</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#aac6196abacab3897ea9874e72d3db8fcaf6aeca3fc739d2f9fa57dfe5180bb8cd">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::ImmTyDim</a>, <a href="#a60199205d0327ba1bec2eb9aaac9f3b3">isGFX10Plus</a>, <a href="/web-llvm/docs/api/classes/llvm/parsestatus/#a670f6078c68c861b8ecaa1ec082fd736">llvm::ParseStatus::NoMatch</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirnamerpass-cpp/#a05e4be4ec3e2c3587dda0e376bb6822c">Operands</a>, <a href="#a332d48815071fdb4e2e94e999c154559">parseDimId</a> and <a href="/web-llvm/docs/api/classes/llvm/parsestatus/#a66a81b1ff471ed3e871c93599118f34c">llvm::ParseStatus::Success</a>.</p>


<p>Referenced by <a href="#a21401db3d85754eab356474360dd2394">cvtVOP3P</a>.</p>

</div>
</div>

### parseDimId {#a332d48815071fdb4e2e94e999c154559}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUAsmParser::parseDimId (unsigned &amp; Encoding)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1889 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringref/#a3fb2867a1e9fa36e135d9ee4dffb0167">llvm::StringRef::drop_front</a>, <a href="/web-llvm/docs/api/structs/llvm/amdgpu/mimgdiminfo/#a9227339ee9f7c6f525fd30ae236d21b7">llvm::AMDGPU::MIMGDimInfo::Encoding</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a98923a223372aac9b7bbd61fde6142ab">llvm::AMDGPU::getMIMGDimInfoByAsmSuffix</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#a9836d66cf9617f7396887c361cbbded0">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::getToken</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a2369278b71442a32bd6a7f6a6f411033">llvm::AsmToken::Integer</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#a5d8227b613dc0aff33ca27637d41c74a">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isToken</a> and <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2cd8968ff703aaeb395dcd63f6805ff1">llvm::StringRef::starts_with</a>.</p>


<p>Referenced by <a href="#a21401db3d85754eab356474360dd2394">cvtVOP3P</a> and <a href="#a4c31665501f9b711e245f1b4e201683b">parseDim</a>.</p>

</div>
</div>

### ParseDirective {#a52dd8abe6dc2354306df33d817dc3101}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUAsmParser::ParseDirective (<a href="/web-llvm/docs/api/classes/llvm/asmtoken">AsmToken</a> DirectiveID)</td>
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

<p>ParseDirective - Parse a target specific assembler directive This method is deprecated, use 'parseDirective' instead.</p>


<p>The parser is positioned following the directive name. The target specific directive parser should parse the entire directive doing or recording any target specific work, or return true and do nothing if the directive is not target specific. If the directive is specific for the target, the entire line is parsed up to and including the end-of-statement token and false is returned.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">DirectiveID</td>
<td class="doxyParamItemDescription"><p>- the identifier token of the directive.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 1610 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/palmd/#a1cb9ed110f803fda0c8dc1d3c9587f36">llvm::AMDGPU::PALMD::AssemblerDirective</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/hsamd/#a4d2014dc2c245c35e2a7df264f161508">llvm::AMDGPU::HSAMD::AssemblerDirectiveBegin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/hsamd/v3/#a461f2193b620e67d5ef8800016925ca9">llvm::AMDGPU::HSAMD::V3::AssemblerDirectiveBegin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/palmd/#a2ed75550f1758e49da7beadad0ae54c7">llvm::AMDGPU::PALMD::AssemblerDirectiveBegin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343a902b0d55fddef6f8d651fe1035b7d4bd">llvm::Error</a>, <a href="/web-llvm/docs/api/classes/llvm/mctargetasmparser/#aa1990a3125ab983e6e90a452cb5a2e66">llvm::MCTargetAsmParser::getSTI</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#a3168618a19701d0fb78aefb4d4e664de">llvm::AsmToken::getString</a> and <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a3d357ec8432b58835aaa34defcc4eff9">llvm::AMDGPU::isHsaAbi</a>.</p>

</div>
</div>

### ParseDirectiveAMDGCNTarget {#a8cedb6297d77e9823854e583e6e0700b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUAsmParser::ParseDirectiveAMDGCNTarget ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1359 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>

</div>
</div>

### ParseDirectiveAMDGPUHsaKernel {#aa8fc15510cd8a3f435a37295b5caef3d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUAsmParser::ParseDirectiveAMDGPUHsaKernel ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1366 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>

</div>
</div>

### ParseDirectiveAMDGPULDS {#a9d2bdcef97c8e16680039b0a5e73735e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUAsmParser::ParseDirectiveAMDGPULDS ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>ParseDirectiveAMDGPULDS ::= .amdgpu_lds identifier ',' size_expression [',' align_expression].</p>

<p>Definition at line 1372 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>

</div>
</div>

### ParseDirectiveAMDHSACodeObjectVersion {#a9f6979dab815bd0a32f56617904bdc56}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUAsmParser::ParseDirectiveAMDHSACodeObjectVersion ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1360 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>

</div>
</div>

### ParseDirectiveAMDHSAKernel {#ab55ae23753363847aa507ada0955569b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUAsmParser::ParseDirectiveAMDHSAKernel ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1361 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>

</div>
</div>

### ParseDirectiveAMDKernelCodeT {#aafc61c13bff045c10435ba7411983d2c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUAsmParser::ParseDirectiveAMDKernelCodeT ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1363 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>

</div>
</div>

### ParseDirectiveHSAMetadata {#af971baeb22f5ef72ac2ee7c92cc2387e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUAsmParser::ParseDirectiveHSAMetadata ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1369 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>

</div>
</div>

### ParseDirectiveISAVersion {#a1cc06bfe344c78019ea74a903f757579}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUAsmParser::ParseDirectiveISAVersion ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1368 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>

</div>
</div>

### ParseDirectivePALMetadata {#af2c0f30c3fa5d4cb3ef52f26a7088105}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUAsmParser::ParseDirectivePALMetadata ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Parse the assembler directive for old linear-format PAL metadata.</p>

<p>Definition at line 1371 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>

</div>
</div>

### ParseDirectivePALMetadataBegin {#aa1305df25fb331acfb073c2e18e66034}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUAsmParser::ParseDirectivePALMetadataBegin ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Parse the assembler directive for new MsgPack-format PAL metadata.</p>

<p>Definition at line 1370 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>

</div>
</div>

### parseDPP8 {#a59d9c798683c4a134a731c43840d62aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ParseStatus AMDGPUAsmParser::parseDPP8 (<a href="/web-llvm/docs/api/namespaces/llvm/#a61e27c75c3334cffa54c44c02077da1e">OperandVector</a> &amp; Operands)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1892 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a29a91140113f0cc0421255bec47955f5">llvm::AsmToken::Colon</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039ac4b2675d2cb80935b789d9f140092e25">llvm::AsmToken::Comma</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#aa6d2ada1e702e79ab63562d3cbd03ee0">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::CreateImm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343a902b0d55fddef6f8d651fe1035b7d4bd">llvm::Error</a>, <a href="/web-llvm/docs/api/classes/llvm/parsestatus/#a07e0e7c7dba79a89519092de57d17358">llvm::ParseStatus::Failure</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparserextension/#aef625855ca29806691daef93804afba0">llvm::MCAsmParserExtension::getParser</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#aac6196abacab3897ea9874e72d3db8fcaf79a7cadd64c125693239a99d15776d4">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::ImmTyDPP8</a>, <a href="#a60199205d0327ba1bec2eb9aaac9f3b3">isGFX10Plus</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a33f6b27b4c0cd2e6d1e970ea90de765d">llvm::AsmToken::LBrac</a>, <a href="/web-llvm/docs/api/classes/llvm/parsestatus/#a670f6078c68c861b8ecaa1ec082fd736">llvm::ParseStatus::NoMatch</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirnamerpass-cpp/#a05e4be4ec3e2c3587dda0e376bb6822c">Operands</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a23ee1110c9b68d6faa5a6823d1a90740">llvm::AsmToken::RBrac</a> and <a href="/web-llvm/docs/api/classes/llvm/parsestatus/#a66a81b1ff471ed3e871c93599118f34c">llvm::ParseStatus::Success</a>.</p>


<p>Referenced by <a href="#a21401db3d85754eab356474360dd2394">cvtVOP3P</a>.</p>

</div>
</div>

### parseDPPCtrl {#af1e3005e43d45d207eb661fa024b1753}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ParseStatus AMDGPUAsmParser::parseDPPCtrl (<a href="/web-llvm/docs/api/namespaces/llvm/#a61e27c75c3334cffa54c44c02077da1e">OperandVector</a> &amp; Operands)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1893 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a29a91140113f0cc0421255bec47955f5">llvm::AsmToken::Colon</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#aa6d2ada1e702e79ab63562d3cbd03ee0">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::CreateImm</a>, <a href="/web-llvm/docs/api/classes/llvm/parsestatus/#a07e0e7c7dba79a89519092de57d17358">llvm::ParseStatus::Failure</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a806fe218bb80f0671afdad4cec36569b">llvm::AsmToken::Identifier</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#aac6196abacab3897ea9874e72d3db8fca9e3ba413ec741a423d42d99974585677">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::ImmTyDppCtrl</a>, <a href="#a3c48b1ea644084c3a3e9751a96f10a11">isSupportedDPPCtrl</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#a5d8227b613dc0aff33ca27637d41c74a">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isToken</a>, <a href="/web-llvm/docs/api/classes/llvm/parsestatus/#a670f6078c68c861b8ecaa1ec082fd736">llvm::ParseStatus::NoMatch</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirnamerpass-cpp/#a05e4be4ec3e2c3587dda0e376bb6822c">Operands</a>, <a href="#ac8acd31ba54707e7714ebb81abe2bf8f">parseDPPCtrlPerm</a>, <a href="#a1ee2ba5e7987e0dc7330c99ad35cdf88">parseDPPCtrlSel</a> and <a href="/web-llvm/docs/api/classes/llvm/parsestatus/#a66a81b1ff471ed3e871c93599118f34c">llvm::ParseStatus::Success</a>.</p>


<p>Referenced by <a href="#a21401db3d85754eab356474360dd2394">cvtVOP3P</a>.</p>

</div>
</div>

### parseDPPCtrlPerm {#ac8acd31ba54707e7714ebb81abe2bf8f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t AMDGPUAsmParser::parseDPPCtrlPerm ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1896 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039ac4b2675d2cb80935b789d9f140092e25">llvm::AsmToken::Comma</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343a902b0d55fddef6f8d651fe1035b7d4bd">llvm::Error</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparserextension/#aef625855ca29806691daef93804afba0">llvm::MCAsmParserExtension::getParser</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a33f6b27b4c0cd2e6d1e970ea90de765d">llvm::AsmToken::LBrac</a> and <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a23ee1110c9b68d6faa5a6823d1a90740">llvm::AsmToken::RBrac</a>.</p>


<p>Referenced by <a href="#a21401db3d85754eab356474360dd2394">cvtVOP3P</a> and <a href="#af1e3005e43d45d207eb661fa024b1753">parseDPPCtrl</a>.</p>

</div>
</div>

### parseDPPCtrlSel {#a1ee2ba5e7987e0dc7330c99ad35cdf88}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t AMDGPUAsmParser::parseDPPCtrlSel (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Ctrl)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1895 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#a3de12858bdbbd0b3da179d508ff2be75">llvm::StringSwitch&lt; T, R &gt;::Case</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/genericconvergenceverifierimpl-h/#a2bb73b5d562083dde29e9091dd81bef3">Check</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae58c751054b01f206f9b9e34e461d25fa7a1920d61156abc05a60135aefe8bc67">llvm::Default</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343a902b0d55fddef6f8d651fe1035b7d4bd">llvm::Error</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparserextension/#aef625855ca29806691daef93804afba0">llvm::MCAsmParserExtension::getParser</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9ac8e4e13ad96a39c3f8db9ed633ad2bac1a5298f939e87e8f962a5edfc206918">llvm::Hi</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9ac8e4e13ad96a39c3f8db9ed633ad2baff50b4aa1c9cc2197ef898436641c911">llvm::Lo</a>.</p>


<p>Referenced by <a href="#a21401db3d85754eab356474360dd2394">cvtVOP3P</a> and <a href="#af1e3005e43d45d207eb661fa024b1753">parseDPPCtrl</a>.</p>

</div>
</div>

### parseEndpgm {#a0b822486044ee842c7c868f39ff4830b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ParseStatus AMDGPUAsmParser::parseEndpgm (<a href="/web-llvm/docs/api/namespaces/llvm/#a61e27c75c3334cffa54c44c02077da1e">OperandVector</a> &amp; Operands)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1920 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#aa6d2ada1e702e79ab63562d3cbd03ee0">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::CreateImm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343a902b0d55fddef6f8d651fe1035b7d4bd">llvm::Error</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a4554b8c1e903115f6d7c75b0cc8900dcae71a5bce3c21304da97e1e5d3dab0ed3">llvm::AMDGPU::Imm</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#aac6196abacab3897ea9874e72d3db8fca53303dcc815ab55f8a1f737852055ded">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::ImmTyEndpgm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a87e65296f2a6d9570117a852af342764">llvm::isUInt</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirnamerpass-cpp/#a05e4be4ec3e2c3587dda0e376bb6822c">Operands</a> and <a href="/web-llvm/docs/api/classes/llvm/parsestatus/#a66a81b1ff471ed3e871c93599118f34c">llvm::ParseStatus::Success</a>.</p>

</div>
</div>

### parseExpr {#a5c37f34a36aa6bb7baad4e347a83b5e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUAsmParser::parseExpr (int64_t &amp; Imm, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Expected="")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1826 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>

</div>
</div>

### parseExpr {#abc850f2e5d8c879ed992414a3054025e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUAsmParser::parseExpr (<a href="/web-llvm/docs/api/namespaces/llvm/#a61e27c75c3334cffa54c44c02077da1e">OperandVector</a> &amp; Operands)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1827 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>

</div>
</div>

### parseExpTgt {#a26a8456ca91f0f85ed2f854837b0dc29}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ParseStatus AMDGPUAsmParser::parseExpTgt (<a href="/web-llvm/docs/api/namespaces/llvm/#a61e27c75c3334cffa54c44c02077da1e">OperandVector</a> &amp; Operands)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1840 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#aa6d2ada1e702e79ab63562d3cbd03ee0">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::CreateImm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343a902b0d55fddef6f8d651fe1035b7d4bd">llvm::Error</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/exp/#af7592dc94276d1958420bcfb414b6998a4b89c8394d5ab3580d6d73e057d3bbb9">llvm::AMDGPU::Exp::ET_INVALID</a>, <a href="/web-llvm/docs/api/classes/llvm/mctargetasmparser/#aa1990a3125ab983e6e90a452cb5a2e66">llvm::MCTargetAsmParser::getSTI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/exp/#ac236558198da971873e571fa38d2b58a">llvm::AMDGPU::Exp::getTgtId</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#aac6196abacab3897ea9874e72d3db8fca8b92c2d67ca16440f8c439f063c4c32b">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::ImmTyExpTgt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/exp/#a19cafb2b98160d416f6b684843fc4989">llvm::AMDGPU::Exp::isSupportedTgtId</a>, <a href="/web-llvm/docs/api/classes/llvm/parsestatus/#a670f6078c68c861b8ecaa1ec082fd736">llvm::ParseStatus::NoMatch</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirnamerpass-cpp/#a05e4be4ec3e2c3587dda0e376bb6822c">Operands</a> and <a href="/web-llvm/docs/api/classes/llvm/parsestatus/#a66a81b1ff471ed3e871c93599118f34c">llvm::ParseStatus::Success</a>.</p>

</div>
</div>

### parseFlatOffset {#af9a4f566ce16209db2301b23edfe1573}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ParseStatus AMDGPUAsmParser::parseFlatOffset (<a href="/web-llvm/docs/api/namespaces/llvm/#a61e27c75c3334cffa54c44c02077da1e">OperandVector</a> &amp; Operands)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1682 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#aac6196abacab3897ea9874e72d3db8fca45cf846b7e62d831b596bccad4de5315">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::ImmTyInstOffset</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#aac6196abacab3897ea9874e72d3db8fca02f46f2486aed0107b1313c8c7bae9b7">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::ImmTyOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/parsestatus/#a78a275295bb9a176cb9fcfa9bbc43db1">llvm::ParseStatus::isNoMatch</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirnamerpass-cpp/#a05e4be4ec3e2c3587dda0e376bb6822c">Operands</a> and <a href="#a82b29753ac1baad9801c7217c0a97dd4">parseIntWithPrefix</a>.</p>


<p>Referenced by <a href="#a82b29753ac1baad9801c7217c0a97dd4">parseIntWithPrefix</a>.</p>

</div>
</div>

### parseFORMAT {#aae18974f031b21f7dd37b072a1cbe24d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ParseStatus AMDGPUAsmParser::parseFORMAT (<a href="/web-llvm/docs/api/namespaces/llvm/#a61e27c75c3334cffa54c44c02077da1e">OperandVector</a> &amp; Operands)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1679 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a29a91140113f0cc0421255bec47955f5">llvm::AsmToken::Colon</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039ac4b2675d2cb80935b789d9f140092e25">llvm::AsmToken::Comma</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#aa6d2ada1e702e79ab63562d3cbd03ee0">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::CreateImm</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039ae10c5f59f330bfd15608e1dda213a98f">llvm::AsmToken::EndOfStatement</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343a902b0d55fddef6f8d651fe1035b7d4bd">llvm::Error</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/mtbufformat/#a2521888c0029b6776056a5b8d18ec449">llvm::AMDGPU::MTBUFFormat::getDefaultFormatEncoding</a>, <a href="/web-llvm/docs/api/classes/llvm/mctargetasmparser/#aa1990a3125ab983e6e90a452cb5a2e66">llvm::MCTargetAsmParser::getSTI</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#aac6196abacab3897ea9874e72d3db8fca86191e0af51710ca8b408b289300cf0d">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::ImmTyFORMAT</a>, <a href="/web-llvm/docs/api/classes/llvm/parsestatus/#a01a3be3f469c6f0a26bf9a5180b7b322">llvm::ParseStatus::isFailure</a>, <a href="#a60199205d0327ba1bec2eb9aaac9f3b3">isGFX10Plus</a>, <a href="/web-llvm/docs/api/classes/llvm/parsestatus/#a60b6e83411b03e0c4dc4858bb5e9f912">llvm::ParseStatus::isSuccess</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#a5d8227b613dc0aff33ca27637d41c74a">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isToken</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirnamerpass-cpp/#a05e4be4ec3e2c3587dda0e376bb6822c">Operands</a>, <a href="#a157290e9f9aa7ff61c53d131b090e50a">parseDfmtNfmt</a>, <a href="#a60728802d4e08feb0abc5cc75c3eefc9">parseRegOrImm</a>, <a href="#ac75ca253bd4248bf1ab2b4d4695f0500">parseSymbolicOrNumericFormat</a>, <a href="#a1125b7de6fb9f81f501a1988550e60d9">parseUfmt</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a> and <a href="/web-llvm/docs/api/classes/llvm/parsestatus/#a66a81b1ff471ed3e871c93599118f34c">llvm::ParseStatus::Success</a>.</p>


<p>Referenced by <a href="#a82b29753ac1baad9801c7217c0a97dd4">parseIntWithPrefix</a>.</p>

</div>
</div>

### parseGPRIdxMacro {#a158cdc1506b2dfbeace5ec8c87327426}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t AMDGPUAsmParser::parseGPRIdxMacro ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1866 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039ac4b2675d2cb80935b789d9f140092e25">llvm::AsmToken::Comma</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343a902b0d55fddef6f8d651fe1035b7d4bd">llvm::Error</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/vgprindexmode/#a9afd95476c40096a5898ba0f06370b3aa7f78de6c8b0734050d847d1cb4c68298">llvm::AMDGPU::VGPRIndexMode::ID_MAX</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/vgprindexmode/#a9afd95476c40096a5898ba0f06370b3aac95e69cbecdf2384529d8d832b09a9fd">llvm::AMDGPU::VGPRIndexMode::ID_MIN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/swizzle/#af86ab86293794f6553fee00cf270f36b">llvm::AMDGPU::Swizzle::IdSymbolic</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a4554b8c1e903115f6d7c75b0cc8900dcae71a5bce3c21304da97e1e5d3dab0ed3">llvm::AMDGPU::Imm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/vgprindexmode/#af5252ebf458b72b49d66ec97f51841e3a11888c04a6eafe3c6e1bd5c1267f92aa">llvm::AMDGPU::VGPRIndexMode::OFF</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a94d3b37c4d0fe4ca14de941b7c905322">llvm::AsmToken::RParen</a> and <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/vgprindexmode/#af5252ebf458b72b49d66ec97f51841e3a281986d81382b7cb4d8b26022b439d54">llvm::AMDGPU::VGPRIndexMode::UNDEF</a>.</p>


<p>Referenced by <a href="#ad03402b69301c9df929a7ca211df947c">parseGPRIdxMode</a>.</p>

</div>
</div>

### parseGPRIdxMode {#ad03402b69301c9df929a7ca211df947c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ParseStatus AMDGPUAsmParser::parseGPRIdxMode (<a href="/web-llvm/docs/api/namespaces/llvm/#a61e27c75c3334cffa54c44c02077da1e">OperandVector</a> &amp; Operands)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1865 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#aa6d2ada1e702e79ab63562d3cbd03ee0">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::CreateImm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343a902b0d55fddef6f8d651fe1035b7d4bd">llvm::Error</a>, <a href="/web-llvm/docs/api/classes/llvm/parsestatus/#a07e0e7c7dba79a89519092de57d17358">llvm::ParseStatus::Failure</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparserextension/#aef625855ca29806691daef93804afba0">llvm::MCAsmParserExtension::getParser</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a4554b8c1e903115f6d7c75b0cc8900dcae71a5bce3c21304da97e1e5d3dab0ed3">llvm::AMDGPU::Imm</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#aac6196abacab3897ea9874e72d3db8fcad4fc7a84a69230aae91424d2ef3daf73">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::ImmTyGprIdxMode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a87e65296f2a6d9570117a852af342764">llvm::isUInt</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a85fc8bab3d6f4fa71b0d876dd9a96e1a">llvm::AsmToken::LParen</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirnamerpass-cpp/#a05e4be4ec3e2c3587dda0e376bb6822c">Operands</a>, <a href="#a158cdc1506b2dfbeace5ec8c87327426">parseGPRIdxMacro</a>, <a href="/web-llvm/docs/api/classes/llvm/parsestatus/#a66a81b1ff471ed3e871c93599118f34c">llvm::ParseStatus::Success</a> and <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/vgprindexmode/#af5252ebf458b72b49d66ec97f51841e3a281986d81382b7cb4d8b26022b439d54">llvm::AMDGPU::VGPRIndexMode::UNDEF</a>.</p>

</div>
</div>

### parseHwreg {#a16bbeaa5435876a2a30093aa9f7adc09}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ParseStatus AMDGPUAsmParser::parseHwreg (<a href="/web-llvm/docs/api/namespaces/llvm/#a61e27c75c3334cffa54c44c02077da1e">OperandVector</a> &amp; Operands)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1700 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="#a887ee9b0b1952f6adb88d8ef15c82a53">AMDGPUAsmParser</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#aa6d2ada1e702e79ab63562d3cbd03ee0">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::CreateImm</a>, <a href="/web-llvm/docs/api/structs/llvm/amdgpu/encodingfield/#aa9cf17c01a263d11167a1040a65535bb">llvm::AMDGPU::EncodingField&lt; 10, 6 &gt;::Default</a>, <a href="/web-llvm/docs/api/structs/llvm/amdgpu/encodingfield/#aa9cf17c01a263d11167a1040a65535bb">llvm::AMDGPU::EncodingField&lt; 15, 11, 32 &gt;::Default</a>, <a href="/web-llvm/docs/api/structs/llvm/amdgpu/encodingfield/#aa9cf17c01a263d11167a1040a65535bb">llvm::AMDGPU::EncodingField&lt; 5, 0 &gt;::Default</a>, <a href="/web-llvm/docs/api/structs/llvm/amdgpu/encodingfields/#a03c632ab947ee3f16c67594f7e010ef5">llvm::AMDGPU::EncodingFields&lt; HwregId, HwregOffset, HwregSize &gt;::encode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343a902b0d55fddef6f8d651fe1035b7d4bd">llvm::Error</a>, <a href="/web-llvm/docs/api/classes/llvm/parsestatus/#a07e0e7c7dba79a89519092de57d17358">llvm::ParseStatus::Failure</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#aac6196abacab3897ea9874e72d3db8fcac8698f7407c44136e38a954eee31ec18">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::ImmTyHwreg</a>, <a href="/web-llvm/docs/api/classes/llvm/parsestatus/#a78a275295bb9a176cb9fcfa9bbc43db1">llvm::ParseStatus::isNoMatch</a>, <a href="/web-llvm/docs/api/classes/llvm/parsestatus/#a60b6e83411b03e0c4dc4858bb5e9f912">llvm::ParseStatus::isSuccess</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a87e65296f2a6d9570117a852af342764">llvm::isUInt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1a995470163b6d76695cba5bc8dfb529">llvm::isUIntN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirnamerpass-cpp/#a05e4be4ec3e2c3587dda0e376bb6822c">Operands</a>, <a href="/web-llvm/docs/api/classes/llvm/parsestatus/#a66a81b1ff471ed3e871c93599118f34c">llvm::ParseStatus::Success</a>, <a href="/web-llvm/docs/api/structs/llvm/amdgpu/encodingfield/#a159c3877705a0b8175783ac351b14693">llvm::AMDGPU::EncodingField&lt; 10, 6 &gt;::Width</a>, <a href="/web-llvm/docs/api/structs/llvm/amdgpu/encodingfield/#a159c3877705a0b8175783ac351b14693">llvm::AMDGPU::EncodingField&lt; 15, 11, 32 &gt;::Width</a> and <a href="/web-llvm/docs/api/structs/llvm/amdgpu/encodingfield/#a159c3877705a0b8175783ac351b14693">llvm::AMDGPU::EncodingField&lt; 5, 0 &gt;::Width</a>.</p>


<p>Referenced by <a href="#aec0a91539564d9315907e97bc05acdbb">parseDepCtr</a>.</p>

</div>
</div>

### parseHwregFunc {#a6c129416da237e2889bd3b364af5580c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ParseStatus AMDGPUAsmParser::parseHwregFunc (OperandInfoTy &amp; HwReg, OperandInfoTy &amp; Offset, OperandInfoTy &amp; Width)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1745 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>

</div>
</div>

### parseId {#a8f8abf4c919ccba2f2fe21b946e68816}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUAsmParser::parseId (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &amp; Val, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> ErrMsg="")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1822 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>

</div>
</div>

### parseImm {#a62ccca1cd262d040e8aee057ab0d22d5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ParseStatus AMDGPUAsmParser::parseImm (<a href="/web-llvm/docs/api/namespaces/llvm/#a61e27c75c3334cffa54c44c02077da1e">OperandVector</a> &amp; Operands, bool HasSP3AbsModifier=false, bool HasLit=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1656 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#a9c5a2112c559ffbe2c7bbf5698b6482f">llvm::APFloat::bitcastToAPInt</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#ae7fe7691e456e49addd866aa23896387">llvm::APFloat::changeSign</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#ac83df2fb4fcefd0a95deb09db83a0635">llvm::APFloat::convertFromString</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#a4e67ee2af4aa2b58e472d12c10b2a427">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::CreateExpr</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#aa6d2ada1e702e79ab63562d3cbd03ee0">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::CreateImm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0596fb939ff753151c9c37ed2b671b4c">llvm::errorToBool</a>, <a href="/web-llvm/docs/api/classes/llvm/parsestatus/#a07e0e7c7dba79a89519092de57d17358">llvm::ParseStatus::Failure</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparserextension/#aef625855ca29806691daef93804afba0">llvm::MCAsmParserExtension::getParser</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#a9836d66cf9617f7396887c361cbbded0">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::getToken</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a217e0207d9cc8e046c2dccbf0e4bb198">llvm::APInt::getZExtValue</a>, <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#a6ba7c3d54a5a714f7a27861ee114cce3">llvm::APFloatBase::IEEEdouble</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#aac6196abacab3897ea9874e72d3db8fcaa685e5bd5b6d415252efb40a82ce1a28">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::ImmTyNone</a>, <a href="#a3740088be499ac1b2813ea1d6904ef15">isModifier</a>, <a href="/web-llvm/docs/api/classes/llvm/parsestatus/#a60b6e83411b03e0c4dc4858bb5e9f912">llvm::ParseStatus::isSuccess</a>, <a href="/web-llvm/docs/api/structs/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/modifiers/#a9481c3d7cbb97f569e63104d2cce5175">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::Modifiers::Lit</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a85fc8bab3d6f4fa71b0d876dd9a96e1a">llvm::AsmToken::LParen</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a1189cff13fec34dee4d501f4d7a7e3a2">llvm::AsmToken::Minus</a>, <a href="/web-llvm/docs/api/classes/llvm/parsestatus/#a670f6078c68c861b8ecaa1ec082fd736">llvm::ParseStatus::NoMatch</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirnamerpass-cpp/#a05e4be4ec3e2c3587dda0e376bb6822c">Operands</a>, <a href="#a62ccca1cd262d040e8aee057ab0d22d5">parseImm</a>, <a href="#ab65e752ef8a4ee9e6df01039bfa00b0e">parsePrimaryExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039ad1efc309b8dfe9289db5493d71569f0b">llvm::AsmToken::Real</a>, <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#a22ed74f1ed33c4d33f524a650ea536a6">llvm::APFloatBase::rmNearestTiesToEven</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a94d3b37c4d0fe4ca14de941b7c905322">llvm::AsmToken::RParen</a> and <a href="/web-llvm/docs/api/classes/llvm/parsestatus/#a66a81b1ff471ed3e871c93599118f34c">llvm::ParseStatus::Success</a>.</p>


<p>Referenced by <a href="#a62ccca1cd262d040e8aee057ab0d22d5">parseImm</a>, <a href="#a82b29753ac1baad9801c7217c0a97dd4">parseIntWithPrefix</a> and <a href="#a60728802d4e08feb0abc5cc75c3eefc9">parseRegOrImm</a>.</p>

</div>
</div>

### parseIndexKey16bit {#a8a20622d48ff74bd05f5de0cafcba3ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ParseStatus AMDGPUAsmParser::parseIndexKey16bit (<a href="/web-llvm/docs/api/namespaces/llvm/#a61e27c75c3334cffa54c44c02077da1e">OperandVector</a> &amp; Operands)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1671 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#aac6196abacab3897ea9874e72d3db8fca4df6d1cb3360e33d52bed3dd55d9342e">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::ImmTyIndexKey16bit</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirnamerpass-cpp/#a05e4be4ec3e2c3587dda0e376bb6822c">Operands</a> and <a href="#a971176e60129a0824a8c1e2a193e6b62">tryParseIndexKey</a>.</p>


<p>Referenced by <a href="#a82b29753ac1baad9801c7217c0a97dd4">parseIntWithPrefix</a>.</p>

</div>
</div>

### parseIndexKey8bit {#a9c025a975a2c1bb92eeff1c356d17df3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ParseStatus AMDGPUAsmParser::parseIndexKey8bit (<a href="/web-llvm/docs/api/namespaces/llvm/#a61e27c75c3334cffa54c44c02077da1e">OperandVector</a> &amp; Operands)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1670 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#aac6196abacab3897ea9874e72d3db8fca3b0787bbfe8d09244425732c5a8840d7">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::ImmTyIndexKey8bit</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirnamerpass-cpp/#a05e4be4ec3e2c3587dda0e376bb6822c">Operands</a> and <a href="#a971176e60129a0824a8c1e2a193e6b62">tryParseIndexKey</a>.</p>


<p>Referenced by <a href="#a82b29753ac1baad9801c7217c0a97dd4">parseIntWithPrefix</a>.</p>

</div>
</div>

### parseInstruction {#af09dfe84acccdfc6a55c91388892da8e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUAsmParser::parseInstruction (<a href="/web-llvm/docs/api/structs/llvm/parseinstructioninfo">ParseInstructionInfo</a> &amp; Info, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> NameLoc, <a href="/web-llvm/docs/api/namespaces/llvm/#a61e27c75c3334cffa54c44c02077da1e">OperandVector</a> &amp; Operands)</td>
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

<p>Parse one assembly instruction.</p>


<p>The parser is positioned following the instruction name. The target specific instruction parser should parse the entire instruction and construct the appropriate MCInst, or emit an error. On success, the entire line should be parsed up to and including the end-of-statement token. On failure, the parser is not required to read to the end of the line.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Name</td>
<td class="doxyParamItemDescription"><p>- The instruction name.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">NameLoc</td>
<td class="doxyParamItemDescription"><p>- The source location of the name.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Operands</td>
<td class="doxyParamItemDescription"><p>[out] - The list of parsed operands, this returns ownership of them to the caller.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>True on failure.</p></dd>
</dl>


<p>Definition at line 1614 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp/#a7e3060b58038543e52c27501d1bb957a">applyMnemonicAliases</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039ac4b2675d2cb80935b789d9f140092e25">llvm::AsmToken::Comma</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#a3f085efcb427da17842f4447cea3d0d5">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::CreateToken</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039ae10c5f59f330bfd15608e1dda213a98f">llvm::AsmToken::EndOfStatement</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343a902b0d55fddef6f8d651fe1035b7d4bd">llvm::Error</a>, <a href="/web-llvm/docs/api/classes/llvm/mctargetasmparser/#a05c3c74b5d565682e793e2336c8b2774">llvm::MCTargetAsmParser::getAvailableFeatures</a>, <a href="/web-llvm/docs/api/classes/llvm/parsestatus/#a01a3be3f469c6f0a26bf9a5180b7b322">llvm::ParseStatus::isFailure</a>, <a href="#a60199205d0327ba1bec2eb9aaac9f3b3">isGFX10Plus</a>, <a href="/web-llvm/docs/api/classes/llvm/parsestatus/#a60b6e83411b03e0c4dc4858bb5e9f912">llvm::ParseStatus::isSuccess</a>, <a href="#a5108ba4d1e0aaaf1c45f0694b21c482baabf56f6ac3c8d8fb9a3479b29c7a8cdf">OperandMode_Default</a>, <a href="#a5108ba4d1e0aaaf1c45f0694b21c482ba97d4520a0e14c2103b5ddaac94a65bf9">OperandMode_NSA</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirnamerpass-cpp/#a05e4be4ec3e2c3587dda0e376bb6822c">Operands</a>, <a href="#ade88d8ed031d487c85dcc6698f28b43f">parseMnemonicSuffix</a> and <a href="#a2f6673e616e48f8b6505d19ef64eddab">parseOperand</a>.</p>

</div>
</div>

### parseInterpAttr {#a5c3abd5a0df4ec19738884622846a92b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ParseStatus AMDGPUAsmParser::parseInterpAttr (<a href="/web-llvm/docs/api/namespaces/llvm/#a61e27c75c3334cffa54c44c02077da1e">OperandVector</a> &amp; Operands)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1843 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#a3de12858bdbbd0b3da179d508ff2be75">llvm::StringSwitch&lt; T, R &gt;::Case</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#aa6d2ada1e702e79ab63562d3cbd03ee0">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::CreateImm</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a7b0fa1a82461032cdf16b7f6c59f0a6a">llvm::StringRef::data</a>, <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#a7f0e82e8a818ca43926fceb49be81661">llvm::StringSwitch&lt; T, R &gt;::Default</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343a902b0d55fddef6f8d651fe1035b7d4bd">llvm::Error</a>, <a href="/web-llvm/docs/api/classes/llvm/smloc/#a16ebb09610e55f63cfc55f28e3a56ad5">llvm::SMLoc::getFromPointer</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#aac6196abacab3897ea9874e72d3db8fca2d980b3c725150072bc1bca3b9717703">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::ImmTyInterpAttr</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#aac6196abacab3897ea9874e72d3db8fcadc4ee0d2f112f47edabec0e19de95b2d">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::ImmTyInterpAttrChan</a>, <a href="/web-llvm/docs/api/classes/llvm/parsestatus/#a670f6078c68c861b8ecaa1ec082fd736">llvm::ParseStatus::NoMatch</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirnamerpass-cpp/#a05e4be4ec3e2c3587dda0e376bb6822c">Operands</a> and <a href="/web-llvm/docs/api/classes/llvm/parsestatus/#a66a81b1ff471ed3e871c93599118f34c">llvm::ParseStatus::Success</a>.</p>

</div>
</div>

### parseInterpSlot {#abc5a32fe7c02fdcfc1484e926e376ce0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ParseStatus AMDGPUAsmParser::parseInterpSlot (<a href="/web-llvm/docs/api/namespaces/llvm/#a61e27c75c3334cffa54c44c02077da1e">OperandVector</a> &amp; Operands)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1842 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#a3de12858bdbbd0b3da179d508ff2be75">llvm::StringSwitch&lt; T, R &gt;::Case</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#aa6d2ada1e702e79ab63562d3cbd03ee0">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::CreateImm</a>, <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#a7f0e82e8a818ca43926fceb49be81661">llvm::StringSwitch&lt; T, R &gt;::Default</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343a902b0d55fddef6f8d651fe1035b7d4bd">llvm::Error</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#aac6196abacab3897ea9874e72d3db8fcac16758e9406b631d54854588a576a29c">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::ImmTyInterpSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/parsestatus/#a670f6078c68c861b8ecaa1ec082fd736">llvm::ParseStatus::NoMatch</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirnamerpass-cpp/#a05e4be4ec3e2c3587dda0e376bb6822c">Operands</a> and <a href="/web-llvm/docs/api/classes/llvm/parsestatus/#a66a81b1ff471ed3e871c93599118f34c">llvm::ParseStatus::Success</a>.</p>

</div>
</div>

### parseIntWithPrefix {#a82b29753ac1baad9801c7217c0a97dd4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ParseStatus anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseIntWithPrefix (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Prefix, int64_t &amp; Int)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1620 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="#a38abdd95e7f5b6e9f4fc534bb392f8b8">cvtExp</a>, <a href="#ac905bca0319767a6f6590aa62145c2be">getCPolKind</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#aac6196abacab3897ea9874e72d3db8fcaa685e5bd5b6d415252efb40a82ce1a28">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::ImmTyNone</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a637b69dea56f804278aa50e975337e01">Int</a>, <a href="#a3740088be499ac1b2813ea1d6904ef15">isModifier</a>, <a href="#ab69ace2a64f183c1e0600a4155b0a976">isNamedOperandModifier</a>, <a href="#a9a76b985d6b897a055389b82198509ee">isOpcodeModifierWithVal</a>, <a href="#aae8e311d01222d265293e010df5bc7f5">isOperandModifier</a>, <a href="#a84254eeb4895568119e37386e6e1ba71">isRegOrOperandModifier</a>, <a href="#aea4cc2cee6a095dbbd1f35f80ad3c3e1">matchDfmtNfmt</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirnamerpass-cpp/#a05e4be4ec3e2c3587dda0e376bb6822c">Operands</a>, <a href="#a3ad635dcc304d17a852fa28adac99bb9">parseBLGP</a>, <a href="#a7e283edef71599b2ffccac2843fce5a0">parseCnt</a>, <a href="#a905978e46c9c9a277645e938f41e1876">parseCPol</a>, <a href="#a157290e9f9aa7ff61c53d131b090e50a">parseDfmtNfmt</a>, <a href="#af9a4f566ce16209db2301b23edfe1573">parseFlatOffset</a>, <a href="#aae18974f031b21f7dd37b072a1cbe24d">parseFORMAT</a>, <a href="#a62ccca1cd262d040e8aee057ab0d22d5">parseImm</a>, <a href="#a8a20622d48ff74bd05f5de0cafcba3ab">parseIndexKey16bit</a>, <a href="#a9c025a975a2c1bb92eeff1c356d17df3">parseIndexKey8bit</a>, <a href="#a82b29753ac1baad9801c7217c0a97dd4">parseIntWithPrefix</a>, <a href="#ab2ff8b8fa2100a684cea688b74d329ab">parseNamedBit</a>, <a href="#ae93e542fa2b3eac118a87c97a47bc681">parseNumericFormat</a>, <a href="#ac9d07a4881948a410fcba201eeb36480">parseOperandArrayWithPrefix</a>, <a href="#aa73d0a8ecc958df50e46e59e1ad97478">parseR128A16</a>, <a href="#ab2ca31c142db4eaa8c629f36d61339bf">parseReg</a>, <a href="#a60728802d4e08feb0abc5cc75c3eefc9">parseRegOrImm</a>, <a href="#a74b6654d186e55d185e29c67ebd46cc6">parseRegOrImmWithFPInputMods</a>, <a href="#a2d208597e9458f13c660462e0d3a4a6a">parseRegOrImmWithIntInputMods</a>, <a href="#a21f740d984294cfbcc067eab247ed24d">parseRegWithFPInputMods</a>, <a href="#aabf72174f316fbcb2e171c231b94d743">parseRegWithIntInputMods</a>, <a href="#a1a55d776c65cd09db2546fb584a2de47">parseScope</a>, <a href="#aec6bf39ecab2cbc57a7ef96190d6019e">parseSP3NegModifier</a>, <a href="#a066421d8538981830a93a7598a571e8f">parseStringOrIntWithPrefix</a>, <a href="#a8dbdde33e6acd3e814ee9db9b8cfef68">parseStringWithPrefix</a>, <a href="#ac3b25b92e123263ee61ca38bdee04828">parseSWaitCnt</a>, <a href="#ac75ca253bd4248bf1ab2b4d4695f0500">parseSymbolicOrNumericFormat</a>, <a href="#ad0ddd35516c856b2c41317d0c1febdea">parseSymbolicSplitFormat</a>, <a href="#a9cba0b00a0bcffcb413914db33553071">parseSymbolicUnifiedFormat</a>, <a href="#a3a4cad862e9d4dda82fe89b5a2557e97">parseTH</a>, <a href="#a1125b7de6fb9f81f501a1988550e60d9">parseUfmt</a>, <a href="#aad55de4993c720c50d992a7cbda3d8d3">parseVReg32OrOff</a>, <a href="#a4110e462b4bf86153ae19de70eb84443">tryParseFmt</a> and <a href="#a971176e60129a0824a8c1e2a193e6b62">tryParseIndexKey</a>.</p>


<p>Referenced by <a href="#a3ad635dcc304d17a852fa28adac99bb9">parseBLGP</a>, <a href="#af9a4f566ce16209db2301b23edfe1573">parseFlatOffset</a>, <a href="#a82b29753ac1baad9801c7217c0a97dd4">parseIntWithPrefix</a>, <a href="#a4bbb3e5e0e2e2c935c2a911665fff611">parseIntWithPrefix</a>, <a href="#a9d5e44bae726c6d5f1d1af4aba4a48ff">parseOModSI</a>, <a href="#a4110e462b4bf86153ae19de70eb84443">tryParseFmt</a> and <a href="#a971176e60129a0824a8c1e2a193e6b62">tryParseIndexKey</a>.</p>

</div>
</div>

### parseIntWithPrefix {#a4bbb3e5e0e2e2c935c2a911665fff611}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ParseStatus AMDGPUAsmParser::parseIntWithPrefix (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Prefix, <a href="/web-llvm/docs/api/namespaces/llvm/#a61e27c75c3334cffa54c44c02077da1e">OperandVector</a> &amp; Operands, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#aac6196abacab3897ea9874e72d3db8fc">AMDGPUOperand::ImmTy</a> ImmTy=<a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#aac6196abacab3897ea9874e72d3db8fcaa685e5bd5b6d415252efb40a82ce1a28">AMDGPUOperand::ImmTyNone</a>, std::function&lt; bool(int64_t &amp;)&gt; ConvertResult=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1623 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#aa6d2ada1e702e79ab63562d3cbd03ee0">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::CreateImm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343a902b0d55fddef6f8d651fe1035b7d4bd">llvm::Error</a>, <a href="/web-llvm/docs/api/classes/llvm/parsestatus/#a60b6e83411b03e0c4dc4858bb5e9f912">llvm::ParseStatus::isSuccess</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirnamerpass-cpp/#a05e4be4ec3e2c3587dda0e376bb6822c">Operands</a>, <a href="#a82b29753ac1baad9801c7217c0a97dd4">parseIntWithPrefix</a> and <a href="/web-llvm/docs/api/classes/llvm/parsestatus/#a66a81b1ff471ed3e871c93599118f34c">llvm::ParseStatus::Success</a>.</p>

</div>
</div>

### parseMnemonicSuffix {#ade88d8ed031d487c85dcc6698f28b43f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef AMDGPUAsmParser::parseMnemonicSuffix (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1613 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="#acd348be108cbdbac20658db6d4bd1a1c">setForcedDPP</a>, <a href="#a68e05bfbdc8f741cbe98a89178b5b92a">setForcedEncodingSize</a> and <a href="#afcafade6789b141859f6a8de96f5c440">setForcedSDWA</a>.</p>


<p>Referenced by <a href="#af09dfe84acccdfc6a55c91388892da8e">parseInstruction</a>.</p>

</div>
</div>

### parseNamedBit {#ab2ff8b8fa2100a684cea688b74d329ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ParseStatus AMDGPUAsmParser::parseNamedBit (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/namespaces/llvm/#a61e27c75c3334cffa54c44c02077da1e">OperandVector</a> &amp; Operands, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#aac6196abacab3897ea9874e72d3db8fc">AMDGPUOperand::ImmTy</a> ImmTy=<a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#aac6196abacab3897ea9874e72d3db8fcaa685e5bd5b6d415252efb40a82ce1a28">AMDGPUOperand::ImmTyNone</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1633 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#aa6d2ada1e702e79ab63562d3cbd03ee0">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::CreateImm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343a902b0d55fddef6f8d651fe1035b7d4bd">llvm::Error</a>, <a href="#a6f910445c0ee081e07f20fd28f2aaad2">hasA16</a>, <a href="#a54492f3614b470db6344ad0f37ab6089">hasMIMG_R128</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#aac6196abacab3897ea9874e72d3db8fca3927f830d00f75bb2e2aba10856298af">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::ImmTyA16</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#aac6196abacab3897ea9874e72d3db8fcaf99873ea3e78297b518afa494e67c3c6">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::ImmTyR128A16</a>, <a href="#abedd2529418cdf49b008a6c05bf3baec">isGFX9</a>, <a href="/web-llvm/docs/api/classes/llvm/parsestatus/#a670f6078c68c861b8ecaa1ec082fd736">llvm::ParseStatus::NoMatch</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirnamerpass-cpp/#a05e4be4ec3e2c3587dda0e376bb6822c">Operands</a> and <a href="/web-llvm/docs/api/classes/llvm/parsestatus/#a66a81b1ff471ed3e871c93599118f34c">llvm::ParseStatus::Success</a>.</p>


<p>Referenced by <a href="#a877255e198cc72078a64aa635548b03b">parseCustomOperand</a>, <a href="#a82b29753ac1baad9801c7217c0a97dd4">parseIntWithPrefix</a> and <a href="#aa73d0a8ecc958df50e46e59e1ad97478">parseR128A16</a>.</p>

</div>
</div>

### parseNumericFormat {#ae93e542fa2b3eac118a87c97a47bc681}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ParseStatus AMDGPUAsmParser::parseNumericFormat (int64_t &amp; Format)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1681 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343a902b0d55fddef6f8d651fe1035b7d4bd">llvm::Error</a>, <a href="/web-llvm/docs/api/classes/llvm/parsestatus/#a07e0e7c7dba79a89519092de57d17358">llvm::ParseStatus::Failure</a>, <a href="/web-llvm/docs/api/classes/llvm/mctargetasmparser/#aa1990a3125ab983e6e90a452cb5a2e66">llvm::MCTargetAsmParser::getSTI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/mtbufformat/#aa71ec16c7a2bb6aaeb19ca20d7cb7442">llvm::AMDGPU::MTBUFFormat::isValidFormatEncoding</a> and <a href="/web-llvm/docs/api/classes/llvm/parsestatus/#a66a81b1ff471ed3e871c93599118f34c">llvm::ParseStatus::Success</a>.</p>


<p>Referenced by <a href="#a82b29753ac1baad9801c7217c0a97dd4">parseIntWithPrefix</a> and <a href="#ac75ca253bd4248bf1ab2b4d4695f0500">parseSymbolicOrNumericFormat</a>.</p>

</div>
</div>

### parseOModSI {#a9d5e44bae726c6d5f1d1af4aba4a48ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ParseStatus AMDGPUAsmParser::parseOModSI (<a href="/web-llvm/docs/api/namespaces/llvm/#a61e27c75c3334cffa54c44c02077da1e">OperandVector</a> &amp; Operands)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1871 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp/#ab46e1348d402e1f38768731498eccadc">ConvertOmodDiv</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp/#a4c360c6d1bbb9bd8480261a269e26262">ConvertOmodMul</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#aac6196abacab3897ea9874e72d3db8fcaf4e10bb6d0fda8ad54cca3f45eb2b143">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::ImmTyOModSI</a>, <a href="/web-llvm/docs/api/classes/llvm/parsestatus/#a670f6078c68c861b8ecaa1ec082fd736">llvm::ParseStatus::NoMatch</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirnamerpass-cpp/#a05e4be4ec3e2c3587dda0e376bb6822c">Operands</a> and <a href="#a82b29753ac1baad9801c7217c0a97dd4">parseIntWithPrefix</a>.</p>

</div>
</div>

### parseOperand {#a2f6673e616e48f8b6505d19ef64eddab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ParseStatus AMDGPUAsmParser::parseOperand (<a href="/web-llvm/docs/api/namespaces/llvm/#a61e27c75c3334cffa54c44c02077da1e">OperandVector</a> &amp; Operands, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Mnemonic, <a href="#a5108ba4d1e0aaaf1c45f0694b21c482b">OperandMode</a> Mode=<a href="#a5108ba4d1e0aaaf1c45f0694b21c482baabf56f6ac3c8d8fb9a3479b29c7a8cdf">OperandMode_Default</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1611 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039ac4b2675d2cb80935b789d9f140092e25">llvm::AsmToken::Comma</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#a3f085efcb427da17842f4447cea3d0d5">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::CreateToken</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039ae10c5f59f330bfd15608e1dda213a98f">llvm::AsmToken::EndOfStatement</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343a902b0d55fddef6f8d651fe1035b7d4bd">llvm::Error</a>, <a href="/web-llvm/docs/api/classes/llvm/parsestatus/#a07e0e7c7dba79a89519092de57d17358">llvm::ParseStatus::Failure</a>, <a href="/web-llvm/docs/api/classes/llvm/parsestatus/#a01a3be3f469c6f0a26bf9a5180b7b322">llvm::ParseStatus::isFailure</a>, <a href="/web-llvm/docs/api/classes/llvm/parsestatus/#a78a275295bb9a176cb9fcfa9bbc43db1">llvm::ParseStatus::isNoMatch</a>, <a href="/web-llvm/docs/api/classes/llvm/parsestatus/#a60b6e83411b03e0c4dc4858bb5e9f912">llvm::ParseStatus::isSuccess</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a33f6b27b4c0cd2e6d1e970ea90de765d">llvm::AsmToken::LBrac</a>, <a href="#a5108ba4d1e0aaaf1c45f0694b21c482ba97d4520a0e14c2103b5ddaac94a65bf9">OperandMode_NSA</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirnamerpass-cpp/#a05e4be4ec3e2c3587dda0e376bb6822c">Operands</a>, <a href="#ab2ca31c142db4eaa8c629f36d61339bf">parseReg</a>, <a href="#a60728802d4e08feb0abc5cc75c3eefc9">parseRegOrImm</a>, <a href="#a4c71cb47a3f1bcc8147c44cc1395ed63">parseVOPD</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a23ee1110c9b68d6faa5a6823d1a90740">llvm::AsmToken::RBrac</a> and <a href="/web-llvm/docs/api/classes/llvm/parsestatus/#a66a81b1ff471ed3e871c93599118f34c">llvm::ParseStatus::Success</a>.</p>


<p>Referenced by <a href="#af09dfe84acccdfc6a55c91388892da8e">parseInstruction</a>.</p>

</div>
</div>

### parseOperandArrayWithPrefix {#ac9d07a4881948a410fcba201eeb36480}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ParseStatus AMDGPUAsmParser::parseOperandArrayWithPrefix (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Prefix, <a href="/web-llvm/docs/api/namespaces/llvm/#a61e27c75c3334cffa54c44c02077da1e">OperandVector</a> &amp; Operands, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#aac6196abacab3897ea9874e72d3db8fc">AMDGPUOperand::ImmTy</a> ImmTy=<a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#aac6196abacab3897ea9874e72d3db8fcaa685e5bd5b6d415252efb40a82ce1a28">AMDGPUOperand::ImmTyNone</a>, bool(*)(int64_t &amp;) ConvertResult=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1627 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a29a91140113f0cc0421255bec47955f5">llvm::AsmToken::Colon</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039ac4b2675d2cb80935b789d9f140092e25">llvm::AsmToken::Comma</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#aa6d2ada1e702e79ab63562d3cbd03ee0">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::CreateImm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343a902b0d55fddef6f8d651fe1035b7d4bd">llvm::Error</a>, <a href="/web-llvm/docs/api/classes/llvm/parsestatus/#a07e0e7c7dba79a89519092de57d17358">llvm::ParseStatus::Failure</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a33f6b27b4c0cd2e6d1e970ea90de765d">llvm::AsmToken::LBrac</a>, <a href="/web-llvm/docs/api/classes/llvm/parsestatus/#a670f6078c68c861b8ecaa1ec082fd736">llvm::ParseStatus::NoMatch</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirnamerpass-cpp/#a05e4be4ec3e2c3587dda0e376bb6822c">Operands</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a23ee1110c9b68d6faa5a6823d1a90740">llvm::AsmToken::RBrac</a> and <a href="/web-llvm/docs/api/classes/llvm/parsestatus/#a66a81b1ff471ed3e871c93599118f34c">llvm::ParseStatus::Success</a>.</p>


<p>Referenced by <a href="#a3ad635dcc304d17a852fa28adac99bb9">parseBLGP</a> and <a href="#a82b29753ac1baad9801c7217c0a97dd4">parseIntWithPrefix</a>.</p>

</div>
</div>

### parsePrimaryExpr {#ab65e752ef8a4ee9e6df01039bfa00b0e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUAsmParser::parsePrimaryExpr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> *&amp; Res, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> &amp; EndLoc)</td>
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

<p>Parse <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu">AMDGPU</a> specific expressions.</p>


<p>expr ::= or(expr, ...) | max(expr, ...)</p>


<p>Definition at line 1836 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#a3de12858bdbbd0b3da179d508ff2be75">llvm::StringSwitch&lt; T, R &gt;::Case</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039ac4b2675d2cb80935b789d9f140092e25">llvm::AsmToken::Comma</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpumcexpr/#a8b210af308c92a311c2a71c9a2ad051a">llvm::AMDGPUMCExpr::create</a>, <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#a7f0e82e8a818ca43926fceb49be81661">llvm::StringSwitch&lt; T, R &gt;::Default</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343a902b0d55fddef6f8d651fe1035b7d4bd">llvm::Error</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparserextension/#aa7399d73f97fdf5bcf6b19f760264848">llvm::MCAsmParserExtension::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparserextension/#aef625855ca29806691daef93804afba0">llvm::MCAsmParserExtension::getParser</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#a9836d66cf9617f7396887c361cbbded0">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::getToken</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a806fe218bb80f0671afdad4cec36569b">llvm::AsmToken::Identifier</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#a5d8227b613dc0aff33ca27637d41c74a">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isToken</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a85fc8bab3d6f4fa71b0d876dd9a96e1a">llvm::AsmToken::LParen</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a94d3b37c4d0fe4ca14de941b7c905322">llvm::AsmToken::RParen</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>.</p>


<p>Referenced by <a href="#a62ccca1cd262d040e8aee057ab0d22d5">parseImm</a>.</p>

</div>
</div>

### parseR128A16 {#aa73d0a8ecc958df50e46e59e1ad97478}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ParseStatus AMDGPUAsmParser::parseR128A16 (<a href="/web-llvm/docs/api/namespaces/llvm/#a61e27c75c3334cffa54c44c02077da1e">OperandVector</a> &amp; Operands)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1683 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#aac6196abacab3897ea9874e72d3db8fca3927f830d00f75bb2e2aba10856298af">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::ImmTyA16</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#aac6196abacab3897ea9874e72d3db8fcaf99873ea3e78297b518afa494e67c3c6">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::ImmTyR128A16</a>, <a href="/web-llvm/docs/api/classes/llvm/parsestatus/#a78a275295bb9a176cb9fcfa9bbc43db1">llvm::ParseStatus::isNoMatch</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirnamerpass-cpp/#a05e4be4ec3e2c3587dda0e376bb6822c">Operands</a> and <a href="#ab2ff8b8fa2100a684cea688b74d329ab">parseNamedBit</a>.</p>


<p>Referenced by <a href="#a82b29753ac1baad9801c7217c0a97dd4">parseIntWithPrefix</a>.</p>

</div>
</div>

### parseReg {#ab2ca31c142db4eaa8c629f36d61339bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ParseStatus AMDGPUAsmParser::parseReg (<a href="/web-llvm/docs/api/namespaces/llvm/#a61e27c75c3334cffa54c44c02077da1e">OperandVector</a> &amp; Operands)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1658 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/parsestatus/#a07e0e7c7dba79a89519092de57d17358">llvm::ParseStatus::Failure</a>, <a href="/web-llvm/docs/api/classes/llvm/parsestatus/#a670f6078c68c861b8ecaa1ec082fd736">llvm::ParseStatus::NoMatch</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirnamerpass-cpp/#a05e4be4ec3e2c3587dda0e376bb6822c">Operands</a>, <a href="#abe4d54f7147e2f219afa02529b48a0d0">parseRegister</a> and <a href="/web-llvm/docs/api/classes/llvm/parsestatus/#a66a81b1ff471ed3e871c93599118f34c">llvm::ParseStatus::Success</a>.</p>


<p>Referenced by <a href="#a5c229c26ac4e66cb56bd6d00cb6e86d4">parseBoolReg</a>, <a href="#a82b29753ac1baad9801c7217c0a97dd4">parseIntWithPrefix</a>, <a href="#a2f6673e616e48f8b6505d19ef64eddab">parseOperand</a>, <a href="#a60728802d4e08feb0abc5cc75c3eefc9">parseRegOrImm</a>, <a href="#a74b6654d186e55d185e29c67ebd46cc6">parseRegOrImmWithFPInputMods</a> and <a href="#a2d208597e9458f13c660462e0d3a4a6a">parseRegOrImmWithIntInputMods</a>.</p>

</div>
</div>

### parseRegister {#abe4d54f7147e2f219afa02529b48a0d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; AMDGPUOperand &gt; AMDGPUAsmParser::parseRegister (bool RestoreOnFailure=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1597 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#a9ceb192ff77adbd8ddbbddaa9a38ae99">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::CreateReg</a>, <a href="/web-llvm/docs/api/classes/llvm/mctargetasmparser/#aa1990a3125ab983e6e90a452cb5a2e66">llvm::MCTargetAsmParser::getSTI</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#a9836d66cf9617f7396887c361cbbded0">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::getToken</a> and <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a3d357ec8432b58835aaa34defcc4eff9">llvm::AMDGPU::isHsaAbi</a>.</p>


<p>Referenced by <a href="#ab2ca31c142db4eaa8c629f36d61339bf">parseReg</a>, <a href="#a911c9b67b1375d8bc5a84dc2796614b0">ParseRegister</a> and <a href="#aad55de4993c720c50d992a7cbda3d8d3">parseVReg32OrOff</a>.</p>

</div>
</div>

### parseRegister {#a4477cf7edf08ac705e5805c530ff0486}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUAsmParser::parseRegister (<a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> &amp; Reg, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> &amp; StartLoc, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> &amp; EndLoc)</td>
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



<p>Definition at line 1600 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>Reference <a href="#a911c9b67b1375d8bc5a84dc2796614b0">ParseRegister</a>.</p>

</div>
</div>

### ParseRegister {#a911c9b67b1375d8bc5a84dc2796614b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUAsmParser::ParseRegister (<a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> &amp; RegNo, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> &amp; StartLoc, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> &amp; EndLoc, bool RestoreOnFailure)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1598 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#abe4d54f7147e2f219afa02529b48a0d0">parseRegister</a>.</p>


<p>Referenced by <a href="#a4477cf7edf08ac705e5805c530ff0486">parseRegister</a> and <a href="#a5e29118c0f500ee77e2601b120205f54">tryParseRegister</a>.</p>

</div>
</div>

### ParseRegList {#a34b0423eea63c2a35ae31a252e805643}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCRegister AMDGPUAsmParser::ParseRegList (<a href="/web-llvm/docs/api/namespaces/anonymous-amdgpuasmparser-cpp-/#a30f503d41098d2871ebfc07b76480ea0">RegisterKind</a> &amp; RegKind, unsigned &amp; RegNum, unsigned &amp; RegWidth, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/asmtoken">AsmToken</a> &gt; &amp; Tokens)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1394 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>

</div>
</div>

### parseRegOrImm {#a60728802d4e08feb0abc5cc75c3eefc9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ParseStatus AMDGPUAsmParser::parseRegOrImm (<a href="/web-llvm/docs/api/namespaces/llvm/#a61e27c75c3334cffa54c44c02077da1e">OperandVector</a> &amp; Operands, bool HasSP3AbsMod=false, bool HasLit=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1659 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="#a3740088be499ac1b2813ea1d6904ef15">isModifier</a>, <a href="/web-llvm/docs/api/classes/llvm/parsestatus/#a78a275295bb9a176cb9fcfa9bbc43db1">llvm::ParseStatus::isNoMatch</a>, <a href="/web-llvm/docs/api/classes/llvm/parsestatus/#a670f6078c68c861b8ecaa1ec082fd736">llvm::ParseStatus::NoMatch</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirnamerpass-cpp/#a05e4be4ec3e2c3587dda0e376bb6822c">Operands</a>, <a href="#a62ccca1cd262d040e8aee057ab0d22d5">parseImm</a> and <a href="#ab2ca31c142db4eaa8c629f36d61339bf">parseReg</a>.</p>


<p>Referenced by <a href="#aae18974f031b21f7dd37b072a1cbe24d">parseFORMAT</a>, <a href="#a82b29753ac1baad9801c7217c0a97dd4">parseIntWithPrefix</a>, <a href="#a2f6673e616e48f8b6505d19ef64eddab">parseOperand</a>, <a href="#a74b6654d186e55d185e29c67ebd46cc6">parseRegOrImmWithFPInputMods</a> and <a href="#a2d208597e9458f13c660462e0d3a4a6a">parseRegOrImmWithIntInputMods</a>.</p>

</div>
</div>

### parseRegOrImmWithFPInputMods {#a74b6654d186e55d185e29c67ebd46cc6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ParseStatus AMDGPUAsmParser::parseRegOrImmWithFPInputMods (<a href="/web-llvm/docs/api/namespaces/llvm/#a61e27c75c3334cffa54c44c02077da1e">OperandVector</a> &amp; Operands, bool AllowImm=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1661 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/modifiers/#afae6e3125ab96eaff88183a4df5f83f7">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::Modifiers::Abs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343a902b0d55fddef6f8d651fe1035b7d4bd">llvm::Error</a>, <a href="/web-llvm/docs/api/classes/llvm/parsestatus/#a07e0e7c7dba79a89519092de57d17358">llvm::ParseStatus::Failure</a>, <a href="/web-llvm/docs/api/structs/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/modifiers/#aad7378c29bc95c596341b83e689c3484">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::Modifiers::hasFPModifiers</a>, <a href="/web-llvm/docs/api/classes/llvm/parsestatus/#a60b6e83411b03e0c4dc4858bb5e9f912">llvm::ParseStatus::isSuccess</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#a5d8227b613dc0aff33ca27637d41c74a">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isToken</a>, <a href="/web-llvm/docs/api/structs/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/modifiers/#a9481c3d7cbb97f569e63104d2cce5175">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::Modifiers::Lit</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a85fc8bab3d6f4fa71b0d876dd9a96e1a">llvm::AsmToken::LParen</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a1189cff13fec34dee4d501f4d7a7e3a2">llvm::AsmToken::Minus</a>, <a href="/web-llvm/docs/api/structs/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/modifiers/#a1817cc7ade7b89f0243a9573ba865204">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::Modifiers::Neg</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirnamerpass-cpp/#a05e4be4ec3e2c3587dda0e376bb6822c">Operands</a>, <a href="#ab2ca31c142db4eaa8c629f36d61339bf">parseReg</a>, <a href="#a60728802d4e08feb0abc5cc75c3eefc9">parseRegOrImm</a>, <a href="#aec6bf39ecab2cbc57a7ef96190d6019e">parseSP3NegModifier</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a7da9940ae6624563c0ff853d5fa7abc5">llvm::AsmToken::Pipe</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a94d3b37c4d0fe4ca14de941b7c905322">llvm::AsmToken::RParen</a> and <a href="/web-llvm/docs/api/classes/llvm/parsestatus/#a66a81b1ff471ed3e871c93599118f34c">llvm::ParseStatus::Success</a>.</p>


<p>Referenced by <a href="#a82b29753ac1baad9801c7217c0a97dd4">parseIntWithPrefix</a> and <a href="#a21f740d984294cfbcc067eab247ed24d">parseRegWithFPInputMods</a>.</p>

</div>
</div>

### parseRegOrImmWithIntInputMods {#a2d208597e9458f13c660462e0d3a4a6a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ParseStatus AMDGPUAsmParser::parseRegOrImmWithIntInputMods (<a href="/web-llvm/docs/api/namespaces/llvm/#a61e27c75c3334cffa54c44c02077da1e">OperandVector</a> &amp; Operands, bool AllowImm=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1663 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343a902b0d55fddef6f8d651fe1035b7d4bd">llvm::Error</a>, <a href="/web-llvm/docs/api/classes/llvm/parsestatus/#a07e0e7c7dba79a89519092de57d17358">llvm::ParseStatus::Failure</a>, <a href="/web-llvm/docs/api/structs/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/modifiers/#af5f3d34d8cc544b80277897a0cdec58b">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::Modifiers::hasIntModifiers</a>, <a href="/web-llvm/docs/api/classes/llvm/parsestatus/#a60b6e83411b03e0c4dc4858bb5e9f912">llvm::ParseStatus::isSuccess</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a85fc8bab3d6f4fa71b0d876dd9a96e1a">llvm::AsmToken::LParen</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirnamerpass-cpp/#a05e4be4ec3e2c3587dda0e376bb6822c">Operands</a>, <a href="#ab2ca31c142db4eaa8c629f36d61339bf">parseReg</a>, <a href="#a60728802d4e08feb0abc5cc75c3eefc9">parseRegOrImm</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a94d3b37c4d0fe4ca14de941b7c905322">llvm::AsmToken::RParen</a>, <a href="/web-llvm/docs/api/structs/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/modifiers/#a4ab62a341b384f1dd49ff39468020e3a">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::Modifiers::Sext</a> and <a href="/web-llvm/docs/api/classes/llvm/parsestatus/#a66a81b1ff471ed3e871c93599118f34c">llvm::ParseStatus::Success</a>.</p>


<p>Referenced by <a href="#a82b29753ac1baad9801c7217c0a97dd4">parseIntWithPrefix</a> and <a href="#aabf72174f316fbcb2e171c231b94d743">parseRegWithIntInputMods</a>.</p>

</div>
</div>

### ParseRegRange {#ad8f9c1daf350802e97afa90a45e80998}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUAsmParser::ParseRegRange (unsigned &amp; Num, unsigned &amp; Width)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1397 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>

</div>
</div>

### ParseRegularReg {#a710d213a3e716462d40a0fb6228406d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCRegister AMDGPUAsmParser::ParseRegularReg (<a href="/web-llvm/docs/api/namespaces/anonymous-amdgpuasmparser-cpp-/#a30f503d41098d2871ebfc07b76480ea0">RegisterKind</a> &amp; RegKind, unsigned &amp; RegNum, unsigned &amp; RegWidth, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/asmtoken">AsmToken</a> &gt; &amp; Tokens)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1388 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>

</div>
</div>

### parseRegWithFPInputMods {#a21f740d984294cfbcc067eab247ed24d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ParseStatus AMDGPUAsmParser::parseRegWithFPInputMods (<a href="/web-llvm/docs/api/namespaces/llvm/#a61e27c75c3334cffa54c44c02077da1e">OperandVector</a> &amp; Operands)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1665 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirnamerpass-cpp/#a05e4be4ec3e2c3587dda0e376bb6822c">Operands</a> and <a href="#a74b6654d186e55d185e29c67ebd46cc6">parseRegOrImmWithFPInputMods</a>.</p>


<p>Referenced by <a href="#a82b29753ac1baad9801c7217c0a97dd4">parseIntWithPrefix</a>.</p>

</div>
</div>

### parseRegWithIntInputMods {#aabf72174f316fbcb2e171c231b94d743}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ParseStatus AMDGPUAsmParser::parseRegWithIntInputMods (<a href="/web-llvm/docs/api/namespaces/llvm/#a61e27c75c3334cffa54c44c02077da1e">OperandVector</a> &amp; Operands)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1666 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirnamerpass-cpp/#a05e4be4ec3e2c3587dda0e376bb6822c">Operands</a> and <a href="#a2d208597e9458f13c660462e0d3a4a6a">parseRegOrImmWithIntInputMods</a>.</p>


<p>Referenced by <a href="#a82b29753ac1baad9801c7217c0a97dd4">parseIntWithPrefix</a>.</p>

</div>
</div>

### parseScope {#a1a55d776c65cd09db2546fb584a2de47}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ParseStatus AMDGPUAsmParser::parseScope (<a href="/web-llvm/docs/api/namespaces/llvm/#a61e27c75c3334cffa54c44c02077da1e">OperandVector</a> &amp; Operands, int64_t &amp; Scope)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1637 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/parsestatus/#a60b6e83411b03e0c4dc4858bb5e9f912">llvm::ParseStatus::isSuccess</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirnamerpass-cpp/#a05e4be4ec3e2c3587dda0e376bb6822c">Operands</a>, <a href="#a066421d8538981830a93a7598a571e8f">parseStringOrIntWithPrefix</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/cpol/#a7d79a4b341da8ac60b91c1f4b1ea42c4a5058ee66fad10c33b4b4444dd2686b7e">llvm::AMDGPU::CPol::SCOPE_CU</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/cpol/#a7d79a4b341da8ac60b91c1f4b1ea42c4a824fd28203d9969e65c6b03a75509ef3">llvm::AMDGPU::CPol::SCOPE_DEV</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/cpol/#a7d79a4b341da8ac60b91c1f4b1ea42c4a7dc2e69975fb9894a38e613ae389fd2a">llvm::AMDGPU::CPol::SCOPE_SE</a> and <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/cpol/#a7d79a4b341da8ac60b91c1f4b1ea42c4a642542075686ad680d6c3e477dc6eebd">llvm::AMDGPU::CPol::SCOPE_SYS</a>.</p>


<p>Referenced by <a href="#a905978e46c9c9a277645e938f41e1876">parseCPol</a> and <a href="#a82b29753ac1baad9801c7217c0a97dd4">parseIntWithPrefix</a>.</p>

</div>
</div>

### parseSDelayALU {#a493337bf1e3308881e03af9142a5bb5a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ParseStatus AMDGPUAsmParser::parseSDelayALU (<a href="/web-llvm/docs/api/namespaces/llvm/#a61e27c75c3334cffa54c44c02077da1e">OperandVector</a> &amp; Operands)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1698 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#aa6d2ada1e702e79ab63562d3cbd03ee0">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::CreateImm</a>, <a href="/web-llvm/docs/api/classes/llvm/parsestatus/#a07e0e7c7dba79a89519092de57d17358">llvm::ParseStatus::Failure</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a806fe218bb80f0671afdad4cec36569b">llvm::AsmToken::Identifier</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#a5d8227b613dc0aff33ca27637d41c74a">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isToken</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a85fc8bab3d6f4fa71b0d876dd9a96e1a">llvm::AsmToken::LParen</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirnamerpass-cpp/#a05e4be4ec3e2c3587dda0e376bb6822c">Operands</a>, <a href="#aac5924990c1b6a01f79b3dd8019f5f7b">parseDelay</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a7da9940ae6624563c0ff853d5fa7abc5">llvm::AsmToken::Pipe</a> and <a href="/web-llvm/docs/api/classes/llvm/parsestatus/#a66a81b1ff471ed3e871c93599118f34c">llvm::ParseStatus::Success</a>.</p>


<p>Referenced by <a href="#aec0a91539564d9315907e97bc05acdbb">parseDepCtr</a>.</p>

</div>
</div>

### parseSDWADstUnused {#a37e7a53cd92512fc5eb8f7a59be76557}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ParseStatus AMDGPUAsmParser::parseSDWADstUnused (<a href="/web-llvm/docs/api/namespaces/llvm/#a61e27c75c3334cffa54c44c02077da1e">OperandVector</a> &amp; Operands)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1909 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#aac6196abacab3897ea9874e72d3db8fca38365958fa12a0f2acd965b2bc77ea00">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::ImmTySDWADstUnused</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirnamerpass-cpp/#a05e4be4ec3e2c3587dda0e376bb6822c">Operands</a> and <a href="#a066421d8538981830a93a7598a571e8f">parseStringOrIntWithPrefix</a>.</p>

</div>
</div>

### parseSDWASel {#abb4f66c7a0618aeff77aba400ebda133}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ParseStatus AMDGPUAsmParser::parseSDWASel (<a href="/web-llvm/docs/api/namespaces/llvm/#a61e27c75c3334cffa54c44c02077da1e">OperandVector</a> &amp; Operands, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Prefix, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#aac6196abacab3897ea9874e72d3db8fc">AMDGPUOperand::ImmTy</a> Type)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1907 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirnamerpass-cpp/#a05e4be4ec3e2c3587dda0e376bb6822c">Operands</a> and <a href="#a066421d8538981830a93a7598a571e8f">parseStringOrIntWithPrefix</a>.</p>

</div>
</div>

### parseSendMsg {#a7e026648ec951bc9ce02a0e99e31f583}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ParseStatus AMDGPUAsmParser::parseSendMsg (<a href="/web-llvm/docs/api/namespaces/llvm/#a61e27c75c3334cffa54c44c02077da1e">OperandVector</a> &amp; Operands)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1841 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#aa6d2ada1e702e79ab63562d3cbd03ee0">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::CreateImm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/sendmsg/#a18b32cda4aa104e7092cd79c9c234401">llvm::AMDGPU::SendMsg::encodeMsg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343a902b0d55fddef6f8d651fe1035b7d4bd">llvm::Error</a>, <a href="/web-llvm/docs/api/classes/llvm/parsestatus/#a07e0e7c7dba79a89519092de57d17358">llvm::ParseStatus::Failure</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#aac6196abacab3897ea9874e72d3db8fcac149121124fe545cec0d7688ea39f435">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::ImmTySendMsg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a87e65296f2a6d9570117a852af342764">llvm::isUInt</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a85fc8bab3d6f4fa71b0d876dd9a96e1a">llvm::AsmToken::LParen</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/sendmsg/#a8594419a4ddfad2c9a79279c490e466da4fd68f389956f8ba7df3b7c868a587f1">llvm::AMDGPU::SendMsg::OP_NONE_</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirnamerpass-cpp/#a05e4be4ec3e2c3587dda0e376bb6822c">Operands</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ae1cf67368d695dbc33c5cb1a69169e68">llvm::AMDGPU::OPR_ID_UNKNOWN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/sendmsg/#a27adb1199e74a321ab952df3817c34b4afec82ae1bf5379f91bdbb2ebeb7d73b4">llvm::AMDGPU::SendMsg::STREAM_ID_NONE_</a> and <a href="/web-llvm/docs/api/classes/llvm/parsestatus/#a66a81b1ff471ed3e871c93599118f34c">llvm::ParseStatus::Success</a>.</p>

</div>
</div>

### parseSendMsgBody {#a6eff51bcc1e84587c8223c6acbdff0f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUAsmParser::parseSendMsgBody (OperandInfoTy &amp; Msg, OperandInfoTy &amp; Op, OperandInfoTy &amp; Stream)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1740 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>

</div>
</div>

### parseSOPPBrTarget {#a082f5bbf706dd5cd5bcb35d7bdf5564f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ParseStatus AMDGPUAsmParser::parseSOPPBrTarget (<a href="/web-llvm/docs/api/namespaces/llvm/#a61e27c75c3334cffa54c44c02077da1e">OperandVector</a> &amp; Operands)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1844 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343a902b0d55fddef6f8d651fe1035b7d4bd">llvm::Error</a>, <a href="/web-llvm/docs/api/classes/llvm/parsestatus/#a07e0e7c7dba79a89519092de57d17358">llvm::ParseStatus::Failure</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#a630948d3f118fad4a7e9d4764ba76a90">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::getStartLoc</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#a72d2637b8226831e335bf142e7b3f352">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isExpr</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#ae14745a72acdb68188b6dc3991cc3dfe">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isImm</a>, <a href="#a3740088be499ac1b2813ea1d6904ef15">isModifier</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#abb79ad2db74dd301e79b8145b9abfd87">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isS16Imm</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#a43ad7d3a52a625302db35bf74a9a3836">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isSymbolRefExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/parsestatus/#a670f6078c68c861b8ecaa1ec082fd736">llvm::ParseStatus::NoMatch</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirnamerpass-cpp/#a05e4be4ec3e2c3587dda0e376bb6822c">Operands</a> and <a href="/web-llvm/docs/api/classes/llvm/parsestatus/#a66a81b1ff471ed3e871c93599118f34c">llvm::ParseStatus::Success</a>.</p>

</div>
</div>

### parseSP3NegModifier {#aec6bf39ecab2cbc57a7ef96190d6019e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUAsmParser::parseSP3NegModifier ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1655 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#a5d8227b613dc0aff33ca27637d41c74a">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isToken</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a1189cff13fec34dee4d501f4d7a7e3a2">llvm::AsmToken::Minus</a> and <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a7da9940ae6624563c0ff853d5fa7abc5">llvm::AsmToken::Pipe</a>.</p>


<p>Referenced by <a href="#a82b29753ac1baad9801c7217c0a97dd4">parseIntWithPrefix</a> and <a href="#a74b6654d186e55d185e29c67ebd46cc6">parseRegOrImmWithFPInputMods</a>.</p>

</div>
</div>

### ParseSpecialReg {#a92e8ee1aa2f66e7579183a0acbb40a4f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCRegister AMDGPUAsmParser::ParseSpecialReg (<a href="/web-llvm/docs/api/namespaces/anonymous-amdgpuasmparser-cpp-/#a30f503d41098d2871ebfc07b76480ea0">RegisterKind</a> &amp; RegKind, unsigned &amp; RegNum, unsigned &amp; RegWidth, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/asmtoken">AsmToken</a> &gt; &amp; Tokens)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1391 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>

</div>
</div>

### parseString {#a7064627bb8d216d774e6e684c2121f07}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUAsmParser::parseString (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &amp; Val, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> ErrMsg="expected a string")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1821 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>

</div>
</div>

### parseStringOrIntWithPrefix {#a066421d8538981830a93a7598a571e8f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ParseStatus AMDGPUAsmParser::parseStringOrIntWithPrefix (<a href="/web-llvm/docs/api/namespaces/llvm/#a61e27c75c3334cffa54c44c02077da1e">OperandVector</a> &amp; Operands, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * &gt; Ids, int64_t &amp; IntVal)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1641 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a29a91140113f0cc0421255bec47955f5">llvm::AsmToken::Colon</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343a902b0d55fddef6f8d651fe1035b7d4bd">llvm::Error</a>, <a href="/web-llvm/docs/api/classes/llvm/parsestatus/#a07e0e7c7dba79a89519092de57d17358">llvm::ParseStatus::Failure</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a806fe218bb80f0671afdad4cec36569b">llvm::AsmToken::Identifier</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#a5d8227b613dc0aff33ca27637d41c74a">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isToken</a>, <a href="/web-llvm/docs/api/classes/llvm/parsestatus/#a670f6078c68c861b8ecaa1ec082fd736">llvm::ParseStatus::NoMatch</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirnamerpass-cpp/#a05e4be4ec3e2c3587dda0e376bb6822c">Operands</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a> and <a href="/web-llvm/docs/api/classes/llvm/parsestatus/#a66a81b1ff471ed3e871c93599118f34c">llvm::ParseStatus::Success</a>.</p>


<p>Referenced by <a href="#a82b29753ac1baad9801c7217c0a97dd4">parseIntWithPrefix</a>, <a href="#a1a55d776c65cd09db2546fb584a2de47">parseScope</a>, <a href="#a37e7a53cd92512fc5eb8f7a59be76557">parseSDWADstUnused</a>, <a href="#abb4f66c7a0618aeff77aba400ebda133">parseSDWASel</a> and <a href="#a11669d3b022f7e99114faaf694659b89">parseStringOrIntWithPrefix</a>.</p>

</div>
</div>

### parseStringOrIntWithPrefix {#a11669d3b022f7e99114faaf694659b89}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ParseStatus AMDGPUAsmParser::parseStringOrIntWithPrefix (<a href="/web-llvm/docs/api/namespaces/llvm/#a61e27c75c3334cffa54c44c02077da1e">OperandVector</a> &amp; Operands, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * &gt; Ids, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#aac6196abacab3897ea9874e72d3db8fc">AMDGPUOperand::ImmTy</a> Type)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1645 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#aa6d2ada1e702e79ab63562d3cbd03ee0">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::CreateImm</a>, <a href="/web-llvm/docs/api/classes/llvm/parsestatus/#a60b6e83411b03e0c4dc4858bb5e9f912">llvm::ParseStatus::isSuccess</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirnamerpass-cpp/#a05e4be4ec3e2c3587dda0e376bb6822c">Operands</a> and <a href="#a066421d8538981830a93a7598a571e8f">parseStringOrIntWithPrefix</a>.</p>

</div>
</div>

### parseStringWithPrefix {#a8dbdde33e6acd3e814ee9db9b8cfef68}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ParseStatus AMDGPUAsmParser::parseStringWithPrefix (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Prefix, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &amp; Value, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> &amp; StringLoc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1639 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a29a91140113f0cc0421255bec47955f5">llvm::AsmToken::Colon</a>, <a href="/web-llvm/docs/api/classes/llvm/parsestatus/#a07e0e7c7dba79a89519092de57d17358">llvm::ParseStatus::Failure</a>, <a href="/web-llvm/docs/api/classes/llvm/parsestatus/#a670f6078c68c861b8ecaa1ec082fd736">llvm::ParseStatus::NoMatch</a> and <a href="/web-llvm/docs/api/classes/llvm/parsestatus/#a66a81b1ff471ed3e871c93599118f34c">llvm::ParseStatus::Success</a>.</p>


<p>Referenced by <a href="#a82b29753ac1baad9801c7217c0a97dd4">parseIntWithPrefix</a> and <a href="#a3a4cad862e9d4dda82fe89b5a2557e97">parseTH</a>.</p>

</div>
</div>

### parseStructuredOpFields {#a70e1d5fd1c994109d1ac7be165c04a11}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ParseStatus AMDGPUAsmParser::parseStructuredOpFields (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; StructuredOpField * &gt; Fields)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1737 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>

</div>
</div>

### parseSWaitCnt {#ac3b25b92e123263ee61ca38bdee04828}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ParseStatus AMDGPUAsmParser::parseSWaitCnt (<a href="/web-llvm/docs/api/namespaces/llvm/#a61e27c75c3334cffa54c44c02077da1e">OperandVector</a> &amp; Operands)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1691 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#aa6d2ada1e702e79ab63562d3cbd03ee0">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::CreateImm</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039ae10c5f59f330bfd15608e1dda213a98f">llvm::AsmToken::EndOfStatement</a>, <a href="/web-llvm/docs/api/classes/llvm/parsestatus/#a07e0e7c7dba79a89519092de57d17358">llvm::ParseStatus::Failure</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2c346c56fb9021d994675d1710d2d551">llvm::getCPU</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a4c450943f424116a9b6b9a3db451af6c">llvm::AMDGPU::getIsaVersion</a>, <a href="/web-llvm/docs/api/classes/llvm/mctargetasmparser/#aa1990a3125ab983e6e90a452cb5a2e66">llvm::MCTargetAsmParser::getSTI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a602bf9c2a80b4f1561e755b693886e25">llvm::AMDGPU::getWaitcntBitMask</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a806fe218bb80f0671afdad4cec36569b">llvm::AsmToken::Identifier</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#a5d8227b613dc0aff33ca27637d41c74a">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isToken</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a85fc8bab3d6f4fa71b0d876dd9a96e1a">llvm::AsmToken::LParen</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirnamerpass-cpp/#a05e4be4ec3e2c3587dda0e376bb6822c">Operands</a>, <a href="#a7e283edef71599b2ffccac2843fce5a0">parseCnt</a> and <a href="/web-llvm/docs/api/classes/llvm/parsestatus/#a66a81b1ff471ed3e871c93599118f34c">llvm::ParseStatus::Success</a>.</p>


<p>Referenced by <a href="#a82b29753ac1baad9801c7217c0a97dd4">parseIntWithPrefix</a>.</p>

</div>
</div>

### parseSwizzle {#a45d3320cf47a5c534c3e884ea6501728}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ParseStatus AMDGPUAsmParser::parseSwizzle (<a href="/web-llvm/docs/api/namespaces/llvm/#a61e27c75c3334cffa54c44c02077da1e">OperandVector</a> &amp; Operands)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1854 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a29a91140113f0cc0421255bec47955f5">llvm::AsmToken::Colon</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#aa6d2ada1e702e79ab63562d3cbd03ee0">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::CreateImm</a>, <a href="/web-llvm/docs/api/classes/llvm/parsestatus/#a07e0e7c7dba79a89519092de57d17358">llvm::ParseStatus::Failure</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a4554b8c1e903115f6d7c75b0cc8900dcae71a5bce3c21304da97e1e5d3dab0ed3">llvm::AMDGPU::Imm</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#aac6196abacab3897ea9874e72d3db8fcae245f2c36be17caa96752cf101b62796">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::ImmTySwizzle</a>, <a href="/web-llvm/docs/api/classes/llvm/parsestatus/#a670f6078c68c861b8ecaa1ec082fd736">llvm::ParseStatus::NoMatch</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirnamerpass-cpp/#a05e4be4ec3e2c3587dda0e376bb6822c">Operands</a>, <a href="#a084f15a5b33b0ce4978446665fabd0b7">parseSwizzleMacro</a>, <a href="#ac327ffb53b577c5a4cfed8b62cd05a13">parseSwizzleOffset</a> and <a href="/web-llvm/docs/api/classes/llvm/parsestatus/#a66a81b1ff471ed3e871c93599118f34c">llvm::ParseStatus::Success</a>.</p>

</div>
</div>

### parseSwizzleBitmaskPerm {#a6fc763bfb813e4442ede4201150335d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUAsmParser::parseSwizzleBitmaskPerm (int64_t &amp; Imm)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1858 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/swizzle/#a381cab423ce806fd73e190fcb8f49a83ae94fe537b6f11c57e17e7b82bf923846">llvm::AMDGPU::Swizzle::BITMASK_WIDTH</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039ac4b2675d2cb80935b789d9f140092e25">llvm::AsmToken::Comma</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp/#af8d5cf401f670f061cb63a8853e69343">encodeBitmaskPerm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343a902b0d55fddef6f8d651fe1035b7d4bd">llvm::Error</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a4554b8c1e903115f6d7c75b0cc8900dcae71a5bce3c21304da97e1e5d3dab0ed3">llvm::AMDGPU::Imm</a> and <a href="/web-llvm/docs/api/classes/llvm/stringref/#a5db9240c74644c67759dd0f901fc3c7d">llvm::StringRef::size</a>.</p>


<p>Referenced by <a href="#a084f15a5b33b0ce4978446665fabd0b7">parseSwizzleMacro</a>.</p>

</div>
</div>

### parseSwizzleBroadcast {#af50d93f657b70f0b66da8a3f052dec81}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUAsmParser::parseSwizzleBroadcast (int64_t &amp; Imm)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1859 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/swizzle/#a381cab423ce806fd73e190fcb8f49a83a111922802b1817b5eda4c2b2eedbe1d2">llvm::AMDGPU::Swizzle::BITMASK_MAX</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp/#af8d5cf401f670f061cb63a8853e69343">encodeBitmaskPerm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343a902b0d55fddef6f8d651fe1035b7d4bd">llvm::Error</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a4554b8c1e903115f6d7c75b0cc8900dcae71a5bce3c21304da97e1e5d3dab0ed3">llvm::AMDGPU::Imm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a434f6a0d80fb13e4326e848a6391f057">llvm::isPowerOf2_64</a> and <a href="#abe6b5f546bd5056f7d59de67f0b5b73b">parseSwizzleOperand</a>.</p>


<p>Referenced by <a href="#a084f15a5b33b0ce4978446665fabd0b7">parseSwizzleMacro</a>.</p>

</div>
</div>

### parseSwizzleFFT {#ad5af3c7927dc204657a840c176cc3d30}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUAsmParser::parseSwizzleFFT (int64_t &amp; Imm)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1862 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343a902b0d55fddef6f8d651fe1035b7d4bd">llvm::Error</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/swizzle/#a381cab423ce806fd73e190fcb8f49a83a6d1a1fa107c0114b85ff4fd4f350249d">llvm::AMDGPU::Swizzle::FFT_MODE_ENC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/swizzle/#a381cab423ce806fd73e190fcb8f49a83ae7e32a6f930f4121d60e606e29be59fa">llvm::AMDGPU::Swizzle::FFT_SWIZZLE_MAX</a>, <a href="/web-llvm/docs/api/classes/llvm/mctargetasmparser/#aa1990a3125ab983e6e90a452cb5a2e66">llvm::MCTargetAsmParser::getSTI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a4554b8c1e903115f6d7c75b0cc8900dcae71a5bce3c21304da97e1e5d3dab0ed3">llvm::AMDGPU::Imm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ac251a1b5841022f34ff2791b1ce3b690">llvm::AMDGPU::isGFX9Plus</a> and <a href="#abe6b5f546bd5056f7d59de67f0b5b73b">parseSwizzleOperand</a>.</p>


<p>Referenced by <a href="#a084f15a5b33b0ce4978446665fabd0b7">parseSwizzleMacro</a>.</p>

</div>
</div>

### parseSwizzleMacro {#a084f15a5b33b0ce4978446665fabd0b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUAsmParser::parseSwizzleMacro (int64_t &amp; Imm)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1856 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343a902b0d55fddef6f8d651fe1035b7d4bd">llvm::Error</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/swizzle/#a4f8d63108fc54934889e0b11c61f31c2aa82ee48b2dffe6feea7c981b40e82c0a">llvm::AMDGPU::Swizzle::ID_BITMASK_PERM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/swizzle/#a4f8d63108fc54934889e0b11c61f31c2a45963ea85feec95c4749f3e29ad4203c">llvm::AMDGPU::Swizzle::ID_BROADCAST</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/swizzle/#a4f8d63108fc54934889e0b11c61f31c2a3453b0147852c7bcff11b218a616c2d9">llvm::AMDGPU::Swizzle::ID_FFT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/swizzle/#a4f8d63108fc54934889e0b11c61f31c2adbc8019a078b4a0407e5094281305a62">llvm::AMDGPU::Swizzle::ID_QUAD_PERM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/swizzle/#a4f8d63108fc54934889e0b11c61f31c2a5b31fa892b7889649899a01b58c02bfd">llvm::AMDGPU::Swizzle::ID_REVERSE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/swizzle/#a4f8d63108fc54934889e0b11c61f31c2a58a8662aa4261301c6ae7bdea81ba332">llvm::AMDGPU::Swizzle::ID_ROTATE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/swizzle/#a4f8d63108fc54934889e0b11c61f31c2a0c72d4f818886442d3002d7c19e80785">llvm::AMDGPU::Swizzle::ID_SWAP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/swizzle/#af86ab86293794f6553fee00cf270f36b">llvm::AMDGPU::Swizzle::IdSymbolic</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a4554b8c1e903115f6d7c75b0cc8900dcae71a5bce3c21304da97e1e5d3dab0ed3">llvm::AMDGPU::Imm</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a85fc8bab3d6f4fa71b0d876dd9a96e1a">llvm::AsmToken::LParen</a>, <a href="#a6fc763bfb813e4442ede4201150335d7">parseSwizzleBitmaskPerm</a>, <a href="#af50d93f657b70f0b66da8a3f052dec81">parseSwizzleBroadcast</a>, <a href="#ad5af3c7927dc204657a840c176cc3d30">parseSwizzleFFT</a>, <a href="#ad3c62cbfb35509cada7ddfa5dbf92b42">parseSwizzleQuadPerm</a>, <a href="#a98cf404e7899b4845ce05a1d1e34101e">parseSwizzleReverse</a>, <a href="#aeac6096195ab728c4deed35b2cd4bf67">parseSwizzleRotate</a>, <a href="#ad4f24fc9dd2450e0cd0af87b71e13baf">parseSwizzleSwap</a> and <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a94d3b37c4d0fe4ca14de941b7c905322">llvm::AsmToken::RParen</a>.</p>


<p>Referenced by <a href="#a45d3320cf47a5c534c3e884ea6501728">parseSwizzle</a>.</p>

</div>
</div>

### parseSwizzleOffset {#ac327ffb53b577c5a4cfed8b62cd05a13}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUAsmParser::parseSwizzleOffset (int64_t &amp; Imm)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1855 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343a902b0d55fddef6f8d651fe1035b7d4bd">llvm::Error</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a4554b8c1e903115f6d7c75b0cc8900dcae71a5bce3c21304da97e1e5d3dab0ed3">llvm::AMDGPU::Imm</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a87e65296f2a6d9570117a852af342764">llvm::isUInt</a>.</p>


<p>Referenced by <a href="#a45d3320cf47a5c534c3e884ea6501728">parseSwizzle</a>.</p>

</div>
</div>

### parseSwizzleOperand {#abe6b5f546bd5056f7d59de67f0b5b73b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUAsmParser::parseSwizzleOperand (int64_t &amp; Op, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned MinVal, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned MaxVal, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; ErrMsg, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> &amp; Loc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1847 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039ac4b2675d2cb80935b789d9f140092e25">llvm::AsmToken::Comma</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343a902b0d55fddef6f8d651fe1035b7d4bd">llvm::Error</a>.</p>


<p>Referenced by <a href="#af50d93f657b70f0b66da8a3f052dec81">parseSwizzleBroadcast</a>, <a href="#ad5af3c7927dc204657a840c176cc3d30">parseSwizzleFFT</a>, <a href="#ab9d915a16cfd251019c425b36648aa5b">parseSwizzleOperands</a>, <a href="#a98cf404e7899b4845ce05a1d1e34101e">parseSwizzleReverse</a>, <a href="#aeac6096195ab728c4deed35b2cd4bf67">parseSwizzleRotate</a> and <a href="#ad4f24fc9dd2450e0cd0af87b71e13baf">parseSwizzleSwap</a>.</p>

</div>
</div>

### parseSwizzleOperands {#ab9d915a16cfd251019c425b36648aa5b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUAsmParser::parseSwizzleOperands (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned OpNum, int64_t * Op, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned MinVal, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned MaxVal, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> ErrMsg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1850 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>Reference <a href="#abe6b5f546bd5056f7d59de67f0b5b73b">parseSwizzleOperand</a>.</p>


<p>Referenced by <a href="#ad3c62cbfb35509cada7ddfa5dbf92b42">parseSwizzleQuadPerm</a>.</p>

</div>
</div>

### parseSwizzleQuadPerm {#ad3c62cbfb35509cada7ddfa5dbf92b42}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUAsmParser::parseSwizzleQuadPerm (int64_t &amp; Imm)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1857 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a4554b8c1e903115f6d7c75b0cc8900dcae71a5bce3c21304da97e1e5d3dab0ed3">llvm::AMDGPU::Imm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/swizzle/#a381cab423ce806fd73e190fcb8f49a83ad71af14870448db33fbb43c2e1e50672">llvm::AMDGPU::Swizzle::LANE_MAX</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/swizzle/#a381cab423ce806fd73e190fcb8f49a83acf0725b2c90fcca9a43a6d391381232d">llvm::AMDGPU::Swizzle::LANE_NUM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/swizzle/#a381cab423ce806fd73e190fcb8f49a83acf3ca28a336368c8e2e89d5f996b8d66">llvm::AMDGPU::Swizzle::LANE_SHIFT</a>, <a href="#ab9d915a16cfd251019c425b36648aa5b">parseSwizzleOperands</a> and <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/swizzle/#a381cab423ce806fd73e190fcb8f49a83ac0315a1c23874571d99e8afc42f6f1a6">llvm::AMDGPU::Swizzle::QUAD_PERM_ENC</a>.</p>


<p>Referenced by <a href="#a084f15a5b33b0ce4978446665fabd0b7">parseSwizzleMacro</a>.</p>

</div>
</div>

### parseSwizzleReverse {#a98cf404e7899b4845ce05a1d1e34101e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUAsmParser::parseSwizzleReverse (int64_t &amp; Imm)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1861 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/swizzle/#a381cab423ce806fd73e190fcb8f49a83a111922802b1817b5eda4c2b2eedbe1d2">llvm::AMDGPU::Swizzle::BITMASK_MAX</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp/#af8d5cf401f670f061cb63a8853e69343">encodeBitmaskPerm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343a902b0d55fddef6f8d651fe1035b7d4bd">llvm::Error</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a4554b8c1e903115f6d7c75b0cc8900dcae71a5bce3c21304da97e1e5d3dab0ed3">llvm::AMDGPU::Imm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a434f6a0d80fb13e4326e848a6391f057">llvm::isPowerOf2_64</a> and <a href="#abe6b5f546bd5056f7d59de67f0b5b73b">parseSwizzleOperand</a>.</p>


<p>Referenced by <a href="#a084f15a5b33b0ce4978446665fabd0b7">parseSwizzleMacro</a>.</p>

</div>
</div>

### parseSwizzleRotate {#aeac6096195ab728c4deed35b2cd4bf67}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUAsmParser::parseSwizzleRotate (int64_t &amp; Imm)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1863 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343a902b0d55fddef6f8d651fe1035b7d4bd">llvm::Error</a>, <a href="/web-llvm/docs/api/classes/llvm/mctargetasmparser/#aa1990a3125ab983e6e90a452cb5a2e66">llvm::MCTargetAsmParser::getSTI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a4554b8c1e903115f6d7c75b0cc8900dcae71a5bce3c21304da97e1e5d3dab0ed3">llvm::AMDGPU::Imm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ac251a1b5841022f34ff2791b1ce3b690">llvm::AMDGPU::isGFX9Plus</a>, <a href="#abe6b5f546bd5056f7d59de67f0b5b73b">parseSwizzleOperand</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/swizzle/#a381cab423ce806fd73e190fcb8f49a83a16e0dd7f4558950530ba31b97366d546">llvm::AMDGPU::Swizzle::ROTATE_DIR_SHIFT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/swizzle/#a381cab423ce806fd73e190fcb8f49a83a4d2037dcbc8b1ebc589bad3215a21012">llvm::AMDGPU::Swizzle::ROTATE_MAX_SIZE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/swizzle/#a381cab423ce806fd73e190fcb8f49a83a29bead916d7cd5999b54609a84f8e9f6">llvm::AMDGPU::Swizzle::ROTATE_MODE_ENC</a> and <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/swizzle/#a381cab423ce806fd73e190fcb8f49a83af33d59cbb98ea3a4dca4c0bd9c4df6cf">llvm::AMDGPU::Swizzle::ROTATE_SIZE_SHIFT</a>.</p>


<p>Referenced by <a href="#a084f15a5b33b0ce4978446665fabd0b7">parseSwizzleMacro</a>.</p>

</div>
</div>

### parseSwizzleSwap {#ad4f24fc9dd2450e0cd0af87b71e13baf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUAsmParser::parseSwizzleSwap (int64_t &amp; Imm)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1860 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/swizzle/#a381cab423ce806fd73e190fcb8f49a83a111922802b1817b5eda4c2b2eedbe1d2">llvm::AMDGPU::Swizzle::BITMASK_MAX</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp/#af8d5cf401f670f061cb63a8853e69343">encodeBitmaskPerm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343a902b0d55fddef6f8d651fe1035b7d4bd">llvm::Error</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a4554b8c1e903115f6d7c75b0cc8900dcae71a5bce3c21304da97e1e5d3dab0ed3">llvm::AMDGPU::Imm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a434f6a0d80fb13e4326e848a6391f057">llvm::isPowerOf2_64</a> and <a href="#abe6b5f546bd5056f7d59de67f0b5b73b">parseSwizzleOperand</a>.</p>


<p>Referenced by <a href="#a084f15a5b33b0ce4978446665fabd0b7">parseSwizzleMacro</a>.</p>

</div>
</div>

### parseSymbolicOrNumericFormat {#ac75ca253bd4248bf1ab2b4d4695f0500}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ParseStatus AMDGPUAsmParser::parseSymbolicOrNumericFormat (int64_t &amp; Format)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1680 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a29a91140113f0cc0421255bec47955f5">llvm::AsmToken::Colon</a>, <a href="/web-llvm/docs/api/classes/llvm/parsestatus/#a07e0e7c7dba79a89519092de57d17358">llvm::ParseStatus::Failure</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a33f6b27b4c0cd2e6d1e970ea90de765d">llvm::AsmToken::LBrac</a>, <a href="/web-llvm/docs/api/classes/llvm/parsestatus/#a670f6078c68c861b8ecaa1ec082fd736">llvm::ParseStatus::NoMatch</a>, <a href="#ae93e542fa2b3eac118a87c97a47bc681">parseNumericFormat</a>, <a href="#ad0ddd35516c856b2c41317d0c1febdea">parseSymbolicSplitFormat</a>, <a href="#a9cba0b00a0bcffcb413914db33553071">parseSymbolicUnifiedFormat</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a23ee1110c9b68d6faa5a6823d1a90740">llvm::AsmToken::RBrac</a> and <a href="/web-llvm/docs/api/classes/llvm/parsestatus/#a66a81b1ff471ed3e871c93599118f34c">llvm::ParseStatus::Success</a>.</p>


<p>Referenced by <a href="#aae18974f031b21f7dd37b072a1cbe24d">parseFORMAT</a> and <a href="#a82b29753ac1baad9801c7217c0a97dd4">parseIntWithPrefix</a>.</p>

</div>
</div>

### parseSymbolicSplitFormat {#ad0ddd35516c856b2c41317d0c1febdea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ParseStatus AMDGPUAsmParser::parseSymbolicSplitFormat (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> FormatStr, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc, int64_t &amp; Format)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1675 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039ac4b2675d2cb80935b789d9f140092e25">llvm::AsmToken::Comma</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/mtbufformat/#a81576381721fb9bbda2d0dbf37866dd6">llvm::AMDGPU::MTBUFFormat::convertDfmtNfmt2Ufmt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/mtbufformat/#a1639288a4e781b242be214c44eb42c4ca8b7ccf769433236212a15d3076881aa7">llvm::AMDGPU::MTBUFFormat::DFMT_DEFAULT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/mtbufformat/#a1639288a4e781b242be214c44eb42c4ca6523540e869e65331060df57c9add409">llvm::AMDGPU::MTBUFFormat::DFMT_UNDEF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/mtbufformat/#a88658310897a5ba8565bf1366213a307">llvm::AMDGPU::MTBUFFormat::encodeDfmtNfmt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343a902b0d55fddef6f8d651fe1035b7d4bd">llvm::Error</a>, <a href="/web-llvm/docs/api/classes/llvm/parsestatus/#a07e0e7c7dba79a89519092de57d17358">llvm::ParseStatus::Failure</a>, <a href="/web-llvm/docs/api/classes/llvm/mctargetasmparser/#aa1990a3125ab983e6e90a452cb5a2e66">llvm::MCTargetAsmParser::getSTI</a>, <a href="#a60199205d0327ba1bec2eb9aaac9f3b3">isGFX10Plus</a>, <a href="#aea4cc2cee6a095dbbd1f35f80ad3c3e1">matchDfmtNfmt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/mtbufformat/#a5d70ded8d54418ba62fd42d38c15ad5fa3861fe2916797a81c4ed930d3b12653a">llvm::AMDGPU::MTBUFFormat::NFMT_DEFAULT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/mtbufformat/#a5d70ded8d54418ba62fd42d38c15ad5fa236bdeff44903627faf337bd91ca344e">llvm::AMDGPU::MTBUFFormat::NFMT_UNDEF</a>, <a href="/web-llvm/docs/api/classes/llvm/parsestatus/#a66a81b1ff471ed3e871c93599118f34c">llvm::ParseStatus::Success</a> and <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/mtbufformat/#ad3114b80fe75fc1d13fb0d768704c8a5a0dd1e270e143e4f1f45ee074260863d4">llvm::AMDGPU::MTBUFFormat::UFMT_UNDEF</a>.</p>


<p>Referenced by <a href="#a82b29753ac1baad9801c7217c0a97dd4">parseIntWithPrefix</a> and <a href="#ac75ca253bd4248bf1ab2b4d4695f0500">parseSymbolicOrNumericFormat</a>.</p>

</div>
</div>

### parseSymbolicUnifiedFormat {#a9cba0b00a0bcffcb413914db33553071}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ParseStatus AMDGPUAsmParser::parseSymbolicUnifiedFormat (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> FormatStr, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc, int64_t &amp; Format)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1677 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343a902b0d55fddef6f8d651fe1035b7d4bd">llvm::Error</a>, <a href="/web-llvm/docs/api/classes/llvm/mctargetasmparser/#aa1990a3125ab983e6e90a452cb5a2e66">llvm::MCTargetAsmParser::getSTI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/mtbufformat/#aa145eb4bbc534a2bae0b03059fad51b7">llvm::AMDGPU::MTBUFFormat::getUnifiedFormat</a>, <a href="#a60199205d0327ba1bec2eb9aaac9f3b3">isGFX10Plus</a>, <a href="/web-llvm/docs/api/classes/llvm/parsestatus/#a670f6078c68c861b8ecaa1ec082fd736">llvm::ParseStatus::NoMatch</a>, <a href="/web-llvm/docs/api/classes/llvm/parsestatus/#a66a81b1ff471ed3e871c93599118f34c">llvm::ParseStatus::Success</a> and <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/mtbufformat/#ad3114b80fe75fc1d13fb0d768704c8a5a0dd1e270e143e4f1f45ee074260863d4">llvm::AMDGPU::MTBUFFormat::UFMT_UNDEF</a>.</p>


<p>Referenced by <a href="#a82b29753ac1baad9801c7217c0a97dd4">parseIntWithPrefix</a> and <a href="#ac75ca253bd4248bf1ab2b4d4695f0500">parseSymbolicOrNumericFormat</a>.</p>

</div>
</div>

### parseTH {#a3a4cad862e9d4dda82fe89b5a2557e97}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ParseStatus AMDGPUAsmParser::parseTH (<a href="/web-llvm/docs/api/namespaces/llvm/#a61e27c75c3334cffa54c44c02077da1e">OperandVector</a> &amp; Operands, int64_t &amp; TH)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1638 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#a3de12858bdbbd0b3da179d508ff2be75">llvm::StringSwitch&lt; T, R &gt;::Case</a>, <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#a7f0e82e8a818ca43926fceb49be81661">llvm::StringSwitch&lt; T, R &gt;::Default</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343a902b0d55fddef6f8d651fe1035b7d4bd">llvm::Error</a>, <a href="/web-llvm/docs/api/classes/llvm/parsestatus/#a60b6e83411b03e0c4dc4858bb5e9f912">llvm::ParseStatus::isSuccess</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirnamerpass-cpp/#a05e4be4ec3e2c3587dda0e376bb6822c">Operands</a>, <a href="#a8dbdde33e6acd3e814ee9db9b8cfef68">parseStringWithPrefix</a>, <a href="/web-llvm/docs/api/classes/llvm/parsestatus/#a66a81b1ff471ed3e871c93599118f34c">llvm::ParseStatus::Success</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/cpol/#a7d79a4b341da8ac60b91c1f4b1ea42c4addb25eae45a1a3aebb6a89356a12a274">llvm::AMDGPU::CPol::TH_ATOMIC_CASCADE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/cpol/#a7d79a4b341da8ac60b91c1f4b1ea42c4a26903d9581af4af246f494648dafc69b">llvm::AMDGPU::CPol::TH_ATOMIC_NT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/cpol/#a7d79a4b341da8ac60b91c1f4b1ea42c4a2e92f3bb1fbe1699bbc5a048f05bc71c">llvm::AMDGPU::CPol::TH_ATOMIC_RETURN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/cpol/#a7d79a4b341da8ac60b91c1f4b1ea42c4a943e8db97b9a05f4680b59c7560f83f7">llvm::AMDGPU::CPol::TH_BYPASS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/cpol/#a7d79a4b341da8ac60b91c1f4b1ea42c4ace018baf0cbdb988694819bfee3e56f2">llvm::AMDGPU::CPol::TH_HT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/cpol/#a7d79a4b341da8ac60b91c1f4b1ea42c4a8154ff62ee9b4a9eaca3572120081634">llvm::AMDGPU::CPol::TH_LU</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/cpol/#a7d79a4b341da8ac60b91c1f4b1ea42c4aaef85254998537aca69557f206ae1583">llvm::AMDGPU::CPol::TH_NT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/cpol/#a7d79a4b341da8ac60b91c1f4b1ea42c4a8a6ed7cfa54389ce147314d0ac1937c5">llvm::AMDGPU::CPol::TH_NT_HT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/cpol/#a7d79a4b341da8ac60b91c1f4b1ea42c4a6b9df5d911ce3782abe88c21c637b0d7">llvm::AMDGPU::CPol::TH_NT_RT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/cpol/#a7d79a4b341da8ac60b91c1f4b1ea42c4a0b5420229ddf44fe3e38da83afcfb778">llvm::AMDGPU::CPol::TH_NT_WB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/cpol/#a7d79a4b341da8ac60b91c1f4b1ea42c4aef4b0079f425ae147002d32dac402226">llvm::AMDGPU::CPol::TH_REAL_BYPASS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/cpol/#a7d79a4b341da8ac60b91c1f4b1ea42c4a7bd735c6eb6c7d5dba48fed697dfe1f9">llvm::AMDGPU::CPol::TH_RT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/cpol/#a7d79a4b341da8ac60b91c1f4b1ea42c4a3918171dcff01b95c474c6a9580f9fc4">llvm::AMDGPU::CPol::TH_RT_NT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/cpol/#a7d79a4b341da8ac60b91c1f4b1ea42c4abbf66453708eb862964d6b60073c529b">llvm::AMDGPU::CPol::TH_RT_WB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/cpol/#a7d79a4b341da8ac60b91c1f4b1ea42c4aef781227c1057999bb260e756ae9f107">llvm::AMDGPU::CPol::TH_TYPE_ATOMIC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/cpol/#a7d79a4b341da8ac60b91c1f4b1ea42c4aeeb5b956d3b600a2c0203104cbedac83">llvm::AMDGPU::CPol::TH_TYPE_LOAD</a> and <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/cpol/#a7d79a4b341da8ac60b91c1f4b1ea42c4a120170f2992da8e04d8809ba48de4c23">llvm::AMDGPU::CPol::TH_TYPE_STORE</a>.</p>


<p>Referenced by <a href="#a905978e46c9c9a277645e938f41e1876">parseCPol</a> and <a href="#a82b29753ac1baad9801c7217c0a97dd4">parseIntWithPrefix</a>.</p>

</div>
</div>

### ParseToEndDirective {#a435a9a5fba34d91b92e3ccecd259433f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUAsmParser::ParseToEndDirective (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * AssemblerDirectiveBegin, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * AssemblerDirectiveEnd, std::string &amp; CollectString)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Common code to parse out a block of text (typically YAML) between start and end directives.</p>

<p>Definition at line 1376 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>

</div>
</div>

### parseTokenOp {#a40cae821d596ce5a10da36c3d1836dac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ParseStatus AMDGPUAsmParser::parseTokenOp (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/namespaces/llvm/#a61e27c75c3334cffa54c44c02077da1e">OperandVector</a> &amp; Operands)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1618 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#a3f085efcb427da17842f4447cea3d0d5">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::CreateToken</a>, <a href="/web-llvm/docs/api/classes/llvm/parsestatus/#a670f6078c68c861b8ecaa1ec082fd736">llvm::ParseStatus::NoMatch</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirnamerpass-cpp/#a05e4be4ec3e2c3587dda0e376bb6822c">Operands</a> and <a href="/web-llvm/docs/api/classes/llvm/parsestatus/#a66a81b1ff471ed3e871c93599118f34c">llvm::ParseStatus::Success</a>.</p>


<p>Referenced by <a href="#a877255e198cc72078a64aa635548b03b">parseCustomOperand</a>.</p>

</div>
</div>

### parseUfmt {#a1125b7de6fb9f81f501a1988550e60d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ParseStatus AMDGPUAsmParser::parseUfmt (int64_t &amp; Format)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1674 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/parsestatus/#a07e0e7c7dba79a89519092de57d17358">llvm::ParseStatus::Failure</a>, <a href="/web-llvm/docs/api/classes/llvm/parsestatus/#a670f6078c68c861b8ecaa1ec082fd736">llvm::ParseStatus::NoMatch</a>, <a href="/web-llvm/docs/api/classes/llvm/parsestatus/#a66a81b1ff471ed3e871c93599118f34c">llvm::ParseStatus::Success</a>, <a href="#a4110e462b4bf86153ae19de70eb84443">tryParseFmt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/mtbufformat/#ad3114b80fe75fc1d13fb0d768704c8a5ab3a1cd28cc7e61cd410a53a20af20625">llvm::AMDGPU::MTBUFFormat::UFMT_MAX</a> and <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/mtbufformat/#ad3114b80fe75fc1d13fb0d768704c8a5a0dd1e270e143e4f1f45ee074260863d4">llvm::AMDGPU::MTBUFFormat::UFMT_UNDEF</a>.</p>


<p>Referenced by <a href="#aae18974f031b21f7dd37b072a1cbe24d">parseFORMAT</a> and <a href="#a82b29753ac1baad9801c7217c0a97dd4">parseIntWithPrefix</a>.</p>

</div>
</div>

### parseVOPD {#a4c71cb47a3f1bcc8147c44cc1395ed63}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ParseStatus AMDGPUAsmParser::parseVOPD (<a href="/web-llvm/docs/api/namespaces/llvm/#a61e27c75c3334cffa54c44c02077da1e">OperandVector</a> &amp; Operands)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1922 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a29a91140113f0cc0421255bec47955f5">llvm::AsmToken::Colon</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#a3f085efcb427da17842f4447cea3d0d5">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::CreateToken</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343a902b0d55fddef6f8d651fe1035b7d4bd">llvm::Error</a>, <a href="/web-llvm/docs/api/classes/llvm/mctargetasmparser/#aa1990a3125ab983e6e90a452cb5a2e66">llvm::MCTargetAsmParser::getSTI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#af277efe76de2cd454da028d38646f2b5">llvm::AMDGPU::hasVOPD</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a806fe218bb80f0671afdad4cec36569b">llvm::AsmToken::Identifier</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#a5d8227b613dc0aff33ca27637d41c74a">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isToken</a>, <a href="/web-llvm/docs/api/classes/llvm/parsestatus/#a670f6078c68c861b8ecaa1ec082fd736">llvm::ParseStatus::NoMatch</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirnamerpass-cpp/#a05e4be4ec3e2c3587dda0e376bb6822c">Operands</a> and <a href="/web-llvm/docs/api/classes/llvm/parsestatus/#a66a81b1ff471ed3e871c93599118f34c">llvm::ParseStatus::Success</a>.</p>


<p>Referenced by <a href="#a2f6673e616e48f8b6505d19ef64eddab">parseOperand</a>.</p>

</div>
</div>

### parseVReg32OrOff {#aad55de4993c720c50d992a7cbda3d8d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ParseStatus AMDGPUAsmParser::parseVReg32OrOff (<a href="/web-llvm/docs/api/namespaces/llvm/#a61e27c75c3334cffa54c44c02077da1e">OperandVector</a> &amp; Operands)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1667 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#aa6d2ada1e702e79ab63562d3cbd03ee0">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::CreateImm</a>, <a href="/web-llvm/docs/api/classes/llvm/parsestatus/#a07e0e7c7dba79a89519092de57d17358">llvm::ParseStatus::Failure</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#aac6196abacab3897ea9874e72d3db8fca96a2e9977c530f18cdc5cdde12de257b">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::ImmTyOff</a>, <a href="/web-llvm/docs/api/classes/llvm/parsestatus/#a670f6078c68c861b8ecaa1ec082fd736">llvm::ParseStatus::NoMatch</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirnamerpass-cpp/#a05e4be4ec3e2c3587dda0e376bb6822c">Operands</a>, <a href="#abe4d54f7147e2f219afa02529b48a0d0">parseRegister</a> and <a href="/web-llvm/docs/api/classes/llvm/parsestatus/#a66a81b1ff471ed3e871c93599118f34c">llvm::ParseStatus::Success</a>.</p>


<p>Referenced by <a href="#a82b29753ac1baad9801c7217c0a97dd4">parseIntWithPrefix</a>.</p>

</div>
</div>

### peekToken {#a2dbbb80441bb8ded15dad16ea3c952dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AsmToken AMDGPUAsmParser::peekToken (bool ShouldSkipSpace=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1829 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>

</div>
</div>

### peekTokens {#acb91b8d53082f83a6716716838f1dee1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AMDGPUAsmParser::peekTokens (<a href="/web-llvm/docs/api/classes/llvm/mutablearrayref">MutableArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/asmtoken">AsmToken</a> &gt; Tokens)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1824 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>

</div>
</div>

### setForcedDPP {#acd348be108cbdbac20658db6d4bd1a1c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::setForcedDPP (bool ForceDPP_)</td>
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



<p>Definition at line 1587 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>Referenced by <a href="#ade88d8ed031d487c85dcc6698f28b43f">parseMnemonicSuffix</a>.</p>

</div>
</div>

### setForcedEncodingSize {#a68e05bfbdc8f741cbe98a89178b5b92a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::setForcedEncodingSize (unsigned Size)</td>
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



<p>Definition at line 1586 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>


<p>Referenced by <a href="#ade88d8ed031d487c85dcc6698f28b43f">parseMnemonicSuffix</a>.</p>

</div>
</div>

### setForcedSDWA {#afcafade6789b141859f6a8de96f5c440}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::setForcedSDWA (bool ForceSDWA_)</td>
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



<p>Definition at line 1588 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>Referenced by <a href="#ade88d8ed031d487c85dcc6698f28b43f">parseMnemonicSuffix</a>.</p>

</div>
</div>

### skipToken {#a11166f8df21f7cce256a44bac5f5d47c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUAsmParser::skipToken (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039">AsmToken::TokenKind</a> Kind, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> ErrMsg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1820 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>

</div>
</div>

### subtargetHasRegister {#ae4218404039ac7293af07cd701386ccd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUAsmParser::subtargetHasRegister (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcregisterinfo">MCRegisterInfo</a> &amp; MRI, <a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> Reg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1365 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>

</div>
</div>

### tryParseFmt {#a4110e462b4bf86153ae19de70eb84443}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUAsmParser::tryParseFmt (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Pref, int64_t MaxVal, int64_t &amp; Val)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1685 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343a902b0d55fddef6f8d651fe1035b7d4bd">llvm::Error</a> and <a href="#a82b29753ac1baad9801c7217c0a97dd4">parseIntWithPrefix</a>.</p>


<p>Referenced by <a href="#a157290e9f9aa7ff61c53d131b090e50a">parseDfmtNfmt</a>, <a href="#a82b29753ac1baad9801c7217c0a97dd4">parseIntWithPrefix</a> and <a href="#a1125b7de6fb9f81f501a1988550e60d9">parseUfmt</a>.</p>

</div>
</div>

### tryParseIndexKey {#a971176e60129a0824a8c1e2a193e6b62}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ParseStatus AMDGPUAsmParser::tryParseIndexKey (<a href="/web-llvm/docs/api/namespaces/llvm/#a61e27c75c3334cffa54c44c02077da1e">OperandVector</a> &amp; Operands, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#aac6196abacab3897ea9874e72d3db8fc">AMDGPUOperand::ImmTy</a> ImmTy)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1668 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#aa6d2ada1e702e79ab63562d3cbd03ee0">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::CreateImm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343a902b0d55fddef6f8d651fe1035b7d4bd">llvm::Error</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#aac6196abacab3897ea9874e72d3db8fca4df6d1cb3360e33d52bed3dd55d9342e">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::ImmTyIndexKey16bit</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#aac6196abacab3897ea9874e72d3db8fca3b0787bbfe8d09244425732c5a8840d7">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::ImmTyIndexKey8bit</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirnamerpass-cpp/#a05e4be4ec3e2c3587dda0e376bb6822c">Operands</a>, <a href="#a82b29753ac1baad9801c7217c0a97dd4">parseIntWithPrefix</a> and <a href="/web-llvm/docs/api/classes/llvm/parsestatus/#a66a81b1ff471ed3e871c93599118f34c">llvm::ParseStatus::Success</a>.</p>


<p>Referenced by <a href="#a8a20622d48ff74bd05f5de0cafcba3ab">parseIndexKey16bit</a>, <a href="#a9c025a975a2c1bb92eeff1c356d17df3">parseIndexKey8bit</a> and <a href="#a82b29753ac1baad9801c7217c0a97dd4">parseIntWithPrefix</a>.</p>

</div>
</div>

### tryParseRegister {#a5e29118c0f500ee77e2601b120205f54}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ParseStatus AMDGPUAsmParser::tryParseRegister (<a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> &amp; Reg, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> &amp; StartLoc, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> &amp; EndLoc)</td>
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

<p>tryParseRegister - parse one register if possible</p>


<p>Check whether a register specification can be parsed at the current location, without failing the entire parse if it can't. Must not consume tokens if the parse fails.</p>


<p>Definition at line 1601 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/parsestatus/#a07e0e7c7dba79a89519092de57d17358">llvm::ParseStatus::Failure</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparserextension/#aef625855ca29806691daef93804afba0">llvm::MCAsmParserExtension::getParser</a>, <a href="/web-llvm/docs/api/classes/llvm/parsestatus/#a670f6078c68c861b8ecaa1ec082fd736">llvm::ParseStatus::NoMatch</a>, <a href="#a911c9b67b1375d8bc5a84dc2796614b0">ParseRegister</a> and <a href="/web-llvm/docs/api/classes/llvm/parsestatus/#a66a81b1ff471ed3e871c93599118f34c">llvm::ParseStatus::Success</a>.</p>

</div>
</div>

### trySkipId {#ace26672fababa8403f7326ff663c8706}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUAsmParser::trySkipId (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Id)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1816 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>

</div>
</div>

### trySkipId {#af3b997aa90c7f21c08a6e22d6be3442f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUAsmParser::trySkipId (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Pref, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Id)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1817 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>

</div>
</div>

### trySkipId {#ab099ab3d47092efb4431b1ad7755d32d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUAsmParser::trySkipId (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Id, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039">AsmToken::TokenKind</a> Kind)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1818 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>

</div>
</div>

### trySkipToken {#a163031b7584edfcd1b5425ba5f25cbee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUAsmParser::trySkipToken (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039">AsmToken::TokenKind</a> Kind)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1819 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>

</div>
</div>

### updateGprCountSymbols {#aca9931d36195af5ef3e9c4c339666b9d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUAsmParser::updateGprCountSymbols (<a href="/web-llvm/docs/api/namespaces/anonymous-amdgpuasmparser-cpp-/#a30f503d41098d2871ebfc07b76480ea0">RegisterKind</a> RegKind, unsigned DwordRegIndex, unsigned RegWidth)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1405 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>

</div>
</div>

### usesConstantBus {#aa565f07572e7d84c3d779f9447d35bae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUAsmParser::usesConstantBus (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned OpIdx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1801 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>

</div>
</div>

### validateAGPRLdSt {#a9d5c58effe43809a37dfd1713cf9b55e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUAsmParser::validateAGPRLdSt (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1787 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>

</div>
</div>

### validateBLGP {#a7fa301acaec42118c60e6c805036eacc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUAsmParser::validateBLGP (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a61e27c75c3334cffa54c44c02077da1e">OperandVector</a> &amp; Operands)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1789 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>

</div>
</div>

### validateCoherencyBits {#a863ff5ccf09e2459e301f36989e38fc7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUAsmParser::validateCoherencyBits (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a61e27c75c3334cffa54c44c02077da1e">OperandVector</a> &amp; Operands, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> &amp; IDLoc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1794 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>

</div>
</div>

### validateConstantBusLimitations {#a55c2d4dc3eb1d01d884432972293a34f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUAsmParser::validateConstantBusLimitations (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a61e27c75c3334cffa54c44c02077da1e">OperandVector</a> &amp; Operands)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1767 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>

</div>
</div>

### validateDivScale {#ab6676014c1baba88d4625c34f9803ee4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUAsmParser::validateDivScale (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1792 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>

</div>
</div>

### validateDPP {#a7cd6fc86c696d22315362d3540a39655}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUAsmParser::validateDPP (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a61e27c75c3334cffa54c44c02077da1e">OperandVector</a> &amp; Operands)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1781 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>

</div>
</div>

### validateDS {#a5b631f93e635247a8c50b181c51e2ff3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUAsmParser::validateDS (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a61e27c75c3334cffa54c44c02077da1e">OperandVector</a> &amp; Operands)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1790 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>

</div>
</div>

### validateFlatOffset {#a80ae4d00af28940cd6cd856d8eff1ae4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUAsmParser::validateFlatOffset (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a61e27c75c3334cffa54c44c02077da1e">OperandVector</a> &amp; Operands)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1764 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>

</div>
</div>

### validateGWS {#a39fda554e35a9d19e1b53d7563ba1235}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUAsmParser::validateGWS (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a61e27c75c3334cffa54c44c02077da1e">OperandVector</a> &amp; Operands)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1791 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>

</div>
</div>

### validateInstruction {#a0982a69137f512538f3ba9ed0a51cebe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUAsmParser::validateInstruction (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> &amp; IDLoc, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a61e27c75c3334cffa54c44c02077da1e">OperandVector</a> &amp; Operands)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1762 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>

</div>
</div>

### validateIntClampSupported {#a460fc7b33c1cd769f5cf2be6014f92da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUAsmParser::validateIntClampSupported (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1770 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>

</div>
</div>

### validateLdsDirect {#af9d2b066d2b7bc3c73752950674162bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; StringRef &gt; AMDGPUAsmParser::validateLdsDirect (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1799 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>

</div>
</div>

### validateMAIAccWrite {#a6dfafe167fd7a6e5b0f864cf9a51632b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUAsmParser::validateMAIAccWrite (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a61e27c75c3334cffa54c44c02077da1e">OperandVector</a> &amp; Operands)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1784 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>

</div>
</div>

### validateMAISrc2 {#a44bdf174034a1b8b8f5f97b38b2ff190}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUAsmParser::validateMAISrc2 (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a61e27c75c3334cffa54c44c02077da1e">OperandVector</a> &amp; Operands)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1785 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>

</div>
</div>

### validateMFMA {#a5137963d3d21a7f10f8df31a032ca187}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUAsmParser::validateMFMA (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a61e27c75c3334cffa54c44c02077da1e">OperandVector</a> &amp; Operands)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1786 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>

</div>
</div>

### validateMIMGAddrSize {#ae92a3c3e0e6e1962a283a5cff528fa34}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUAsmParser::validateMIMGAddrSize (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> &amp; IDLoc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1775 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>

</div>
</div>

### validateMIMGAtomicDMask {#a01b9b3e92cea528f0e617c6d35806b1c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUAsmParser::validateMIMGAtomicDMask (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1771 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>

</div>
</div>

### validateMIMGD16 {#affe8e0e1234867fb44eecab893d47cf7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUAsmParser::validateMIMGD16 (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1776 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>

</div>
</div>

### validateMIMGDataSize {#a0f5d348d6e01265ce9169bae68af40c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUAsmParser::validateMIMGDataSize (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> &amp; IDLoc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1774 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>

</div>
</div>

### validateMIMGDim {#a59ddcdb4ebb1a6b8a615c73b94311554}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUAsmParser::validateMIMGDim (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a61e27c75c3334cffa54c44c02077da1e">OperandVector</a> &amp; Operands)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1777 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>

</div>
</div>

### validateMIMGGatherDMask {#a118483cae9e0c617479c8169cd5f0449}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUAsmParser::validateMIMGGatherDMask (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1772 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>

</div>
</div>

### validateMIMGMSAA {#af2cfac42d0b04b8e5e78972ac8b887d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUAsmParser::validateMIMGMSAA (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1778 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>

</div>
</div>

### validateMovrels {#a7e5970da7a566c9f954fb41e33ec9cef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUAsmParser::validateMovrels (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a61e27c75c3334cffa54c44c02077da1e">OperandVector</a> &amp; Operands)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1773 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>

</div>
</div>

### validateNeg {#a2f32aaa6de7997a91317ed0a47f6a6be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUAsmParser::validateNeg (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, int OpName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1780 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>

</div>
</div>

### validateOffset {#a5c9a80ca3f27cba8a468d14339c65c4a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUAsmParser::validateOffset (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a61e27c75c3334cffa54c44c02077da1e">OperandVector</a> &amp; Operands)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1763 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>

</div>
</div>

### validateOpSel {#af95d2ab489c6c3a844f22f4db73982e1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUAsmParser::validateOpSel (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1779 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>

</div>
</div>

### validateSendMsg {#a63fd81326007702b0c1ae4a305370b31}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUAsmParser::validateSendMsg (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> OperandInfoTy &amp; Msg, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> OperandInfoTy &amp; Op, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> OperandInfoTy &amp; Stream)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1741 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>

</div>
</div>

### validateSMEMOffset {#a62a490fe5c5e8934cb074a3dc889468d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUAsmParser::validateSMEMOffset (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a61e27c75c3334cffa54c44c02077da1e">OperandVector</a> &amp; Operands)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1765 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>

</div>
</div>

### validateSOPLiteral {#af50191dc42ece6518d0e562efcd79307}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUAsmParser::validateSOPLiteral (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1766 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>

</div>
</div>

### validateStructuredOpFields {#a7c392b642016cbf17d5c5a94df3d0dc3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUAsmParser::validateStructuredOpFields (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> StructuredOpField * &gt; Fields)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1738 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>

</div>
</div>

### validateTargetOperandClass {#a04ee19cd4568c1352a7d3fce29933cc1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned AMDGPUAsmParser::validateTargetOperandClass (<a href="/web-llvm/docs/api/classes/llvm/mcparsedasmoperand">MCParsedAsmOperand</a> &amp; Op, unsigned Kind)</td>
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

<p>Allow a target to add special case operand matching for things that tblgen doesn't/can't handle effectively.</p>


<p>For example, literal immediates on ARM. TableGen expects a token operand, but the parser will recognize them as immediates.</p>


<p>Definition at line 1604 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#a5da081c55cdc6b6177d44f16709f407f">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isAddr64</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#a3fe560c5124729f869042921509ee5f4">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isGDS</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#a99a00d1441baffd67cc30c446eb4dc6d">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isIdxen</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#ae4037548ce62acb9759955250737db54">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isInterpAttr</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#acbee773b6ce142455d118167c39d9e55">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isInterpAttrChan</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#a67c3b2574b178fb5d5f6fa38d5376101">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isInterpSlot</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#a74e4facce65c38df1b0b9ee5770d1c48">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isLDS</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#a25a9c23ba883fb9aa73d55a43260e4a5">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isNull</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#a489f00cf9dd045f774be9a4a5f8ba360">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isOffen</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#a88cac794786119f504d4a0c96540f2ea">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isSOPPBrTarget</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#a8d2d0919dd1d18d1f5617d78bbacf2ce">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isSSrc_b32</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#a7c8e83fc3517ec8e0ce5574d6ff94ef5">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isSSrc_f32</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#a136032b6433e8780b837c9ea1f03af10">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isTFE</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#a1e78a8f72b1a1d2cdc5616e36e501aa1">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isVReg32OrOff</a>, <a href="/web-llvm/docs/api/classes/llvm/mctargetasmparser/#a29cb086c359baadd9df6e5f101e41007a36e5dd518d3d92d2d6207a9ed03d6b48">llvm::MCTargetAsmParser::Match_InvalidOperand</a> and <a href="/web-llvm/docs/api/classes/llvm/mctargetasmparser/#a29cb086c359baadd9df6e5f101e41007a2d220d934e235f8d0ff1eb07adf2b483">llvm::MCTargetAsmParser::Match_Success</a>.</p>

</div>
</div>

### validateTFE {#a51703ec9e1a3532934bda6fc6d24667d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUAsmParser::validateTFE (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a61e27c75c3334cffa54c44c02077da1e">OperandVector</a> &amp; Operands)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1798 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>

</div>
</div>

### validateTHAndScopeBits {#a2359f8c65e5c2dea22fab8c57936dd61}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUAsmParser::validateTHAndScopeBits (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a61e27c75c3334cffa54c44c02077da1e">OperandVector</a> &amp; Operands, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned CPol)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1796 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>

</div>
</div>

### validateVccOperand {#ab55af519108c29ba51bd428352d55087}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUAsmParser::validateVccOperand (<a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> Reg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1782 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>

</div>
</div>

### validateVGPRAlign {#a6de0e019aaab9c666d02d2eb56f058a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUAsmParser::validateVGPRAlign (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1788 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>

</div>
</div>

### validateVOPDRegBankConstraints {#ae7ccbcffee0b1de875f762c116fae81c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUAsmParser::validateVOPDRegBankConstraints (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a61e27c75c3334cffa54c44c02077da1e">OperandVector</a> &amp; Operands)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1768 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>

</div>
</div>

### validateVOPLiteral {#a013521c9b7a057eba196a402782881f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUAsmParser::validateVOPLiteral (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a61e27c75c3334cffa54c44c02077da1e">OperandVector</a> &amp; Operands)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1783 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>

</div>
</div>

### validateWaitCnt {#af909474c7595106b43172a1e21bca078}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUAsmParser::validateWaitCnt (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a61e27c75c3334cffa54c44c02077da1e">OperandVector</a> &amp; Operands)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1793 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>

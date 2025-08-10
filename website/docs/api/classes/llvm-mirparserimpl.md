---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/mirparserimpl
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `MIRParserImpl` Class

<p>This class implements the parsing of LLVM IR that's embedded inside a MIR file. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::MIRParserImpl { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a778a9ed3680bc4858de45e780a407893">MIRParserImpl</a> (std::unique_ptr&lt; MemoryBuffer &gt; Contents, StringRef Filename, LLVMContext &amp;Context, std::function&lt; void(Function &amp;)&gt; ProcessIRFunction)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a081423ee9e0967e35ecfcad1af58be23">reportDiagnostic</a> (const SMDiagnostic &amp;Diag)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0219c7f9cad07740ec0c2d18dac6e946">error</a> (const Twine &amp;Message)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Report an error with the given message at unknown location. <a href="#a0219c7f9cad07740ec0c2d18dac6e946">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a02e579110bd0e0a8008ad1fb8718d45f">error</a> (SMLoc Loc, const Twine &amp;Message)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Report an error with the given message at the given location. <a href="#a02e579110bd0e0a8008ad1fb8718d45f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a93da07a8e8488d1f8a6c3cc183910bda">error</a> (const SMDiagnostic &amp;Error, SMRange SourceRange)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Report a given error with the location translated from the location in an embedded string literal to a location in the MIR file. <a href="#a93da07a8e8488d1f8a6c3cc183910bda">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a453c89e061b40c47d23dca6d7be8d2c5">parseIRModule</a> (DataLayoutCallbackTy DataLayoutCallback)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Try to parse the optional LLVM module and the machine functions in the MIR file. <a href="#a453c89e061b40c47d23dca6d7be8d2c5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2bd6903bee5451ebaffd790ccf869664">createDummyFunction</a> (StringRef Name, Module &amp;M)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create an empty function with the given name. <a href="#a2bd6903bee5451ebaffd790ccf869664">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aff4be0d6e305b2b9b41970bc607c528c">parseMachineFunctions</a> (Module &amp;M, MachineModuleInfo &amp;MMI, ModuleAnalysisManager *FAM=nullptr)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afbccb941c0215a918667f3a574b976b9">parseMachineFunction</a> (Module &amp;M, MachineModuleInfo &amp;MMI, ModuleAnalysisManager *FAM)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parse the machine function in the current YAML document. <a href="#afbccb941c0215a918667f3a574b976b9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3518bb886d39c70ab9163440243d2d5b">initializeMachineFunction</a> (const yaml::MachineFunction &amp;YamlMF, MachineFunction &amp;MF)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Initialize the machine function to the state that's described in the MIR file. <a href="#a3518bb886d39c70ab9163440243d2d5b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0cd181d3140028362e24cdc5d675ac16">parseRegisterInfo</a> (PerFunctionMIParsingState &amp;PFS, const yaml::MachineFunction &amp;YamlMF)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0909a505055aae0cb9dee8e5730b3724">setupRegisterInfo</a> (const PerFunctionMIParsingState &amp;PFS, const yaml::MachineFunction &amp;YamlMF)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a14e404f789b4aa6b37a554702f0c28ae">initializeFrameInfo</a> (PerFunctionMIParsingState &amp;PFS, const yaml::MachineFunction &amp;YamlMF)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea53e647298055af644a50c3a29e1411">initializeCallSiteInfo</a> (PerFunctionMIParsingState &amp;PFS, const yaml::MachineFunction &amp;YamlMF)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abcac742b9eada6520eb78f1fcc9ba35d">parseCalleeSavedRegister</a> (PerFunctionMIParsingState &amp;PFS, std::vector&lt; CalleeSavedInfo &gt; &amp;CSIInfo, const yaml::StringValue &amp;RegisterSource, bool IsRestored, int FrameIdx)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/structs/llvm/mirparserimpl/varexprloc">VarExprLoc</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7db0bf7fbc32682239ef46f866c36016">parseVarExprLoc</a> (PerFunctionMIParsingState &amp;PFS, const yaml::StringValue &amp;VarStr, const yaml::StringValue &amp;ExprStr, const yaml::StringValue &amp;LocStr)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a350e13622868acbfca1779538a0f3b9b">parseStackObjectsDebugInfo</a> (PerFunctionMIParsingState &amp;PFS, const T &amp;Object, int FrameIdx)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a69398364db52b18db9d922fec6d8eb87">initializeConstantPool</a> (PerFunctionMIParsingState &amp;PFS, MachineConstantPool &amp;ConstantPool, const yaml::MachineFunction &amp;YamlMF)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4e8962fa2139c288809acff971691109">initializeJumpTableInfo</a> (PerFunctionMIParsingState &amp;PFS, const yaml::MachineJumpTable &amp;YamlJTI)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#add4fede1a05c8d8148b6ef72f2da3494">parseMachineMetadataNodes</a> (PerFunctionMIParsingState &amp;PFS, MachineFunction &amp;MF, const yaml::MachineFunction &amp;YMF)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9d55670b674a7d3bc9f2df1668d63be8">parseCalledGlobals</a> (PerFunctionMIParsingState &amp;PFS, MachineFunction &amp;MF, const yaml::MachineFunction &amp;YMF)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a185886cd3957b9b6b342c4633f268348">parseMDNode</a> (PerFunctionMIParsingState &amp;PFS, MDNode *&amp;Node, const yaml::StringValue &amp;Source)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ab9f981c0577a86d566108a57fd85eb">parseMBBReference</a> (PerFunctionMIParsingState &amp;PFS, MachineBasicBlock *&amp;MBB, const yaml::StringValue &amp;Source)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aef0fcc2f0d275f3823d66a81c56b1d4e">parseMachineMetadata</a> (PerFunctionMIParsingState &amp;PFS, const yaml::StringValue &amp;Source)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smdiagnostic">SMDiagnostic</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a92d79d3c68c93855864dfd76d1743dd3">diagFromMIStringDiag</a> (const SMDiagnostic &amp;Error, SMRange SourceRange)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a MIR diagnostic converted from an MI string diagnostic. <a href="#a92d79d3c68c93855864dfd76d1743dd3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smdiagnostic">SMDiagnostic</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a82e7ae721839ce66bd6162bbb9f6e47a">diagFromBlockStringDiag</a> (const SMDiagnostic &amp;Error, SMRange SourceRange)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a MIR diagnostic converted from a diagnostic located in a YAML block scalar string. <a href="#a82e7ae721839ce66bd6162bbb9f6e47a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a34aea37f8cfe23566cc442a2e56f0e86">computeFunctionProperties</a> (MachineFunction &amp;MF, const yaml::MachineFunction &amp;YamlMF)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeda1882b76b24a0d5d1ac86a1299339b">setupDebugValueTracking</a> (MachineFunction &amp;MF, PerFunctionMIParsingState &amp;PFS, const yaml::MachineFunction &amp;YamlMF)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aacd18dc953a6910eda622f48ea460048">parseMachineInst</a> (MachineFunction &amp;MF, yaml::MachineInstrLoc MILoc, MachineInstr const *&amp;MI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sourcemgr">SourceMgr</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1bde191ffe3a2b4c9a5c5307944c5e07">SM</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6cf417e74c530d70d860f6e4a32106a6">Context</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/yaml/input">yaml::Input</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc8c7cb13b2d580e488d378fcb732c76">In</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9250e1fa9856a086c1b378fdd5504118">Filename</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/slotmapping">SlotMapping</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad44270bab272ab9139c4775670625087">IRSlots</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/structs/llvm/pertargetmiparsingstate">PerTargetMIParsingState</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac7fe88b78bf43261a9a70dd5d5bc1565">Target</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa769330724ce7d8f6142ae0f36691b98">NoLLVMIR</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True when the MIR file doesn't have LLVM IR. <a href="#aa769330724ce7d8f6142ae0f36691b98">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a74cdeef71d385f75e8aee33306a452c2">NoMIRDocuments</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True when a well formed MIR file does not contain any MIR/machine function parts. <a href="#a74cdeef71d385f75e8aee33306a452c2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::function&lt; void(<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp;)&gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7a38f61d8de68a8bc39ebc04a13933a7">ProcessIRFunction</a></td>
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

<p>This class implements the parsing of LLVM IR that's embedded inside a MIR file.</p>

<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/mirparser-cpp">MIRParser.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### MIRParserImpl() {#a778a9ed3680bc4858de45e780a407893}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MIRParserImpl::MIRParserImpl (std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a> &gt; Contents, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Filename, <a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; Context, std::function&lt; void(<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp;)&gt; ProcessIRFunction)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/mirparser-cpp">MIRParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/mirparser-cpp/#a967e6f2ef0e74965cf044671367967bb">handleYAMLDiag</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### createDummyFunction() {#a2bd6903bee5451ebaffd790ccf869664}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Function * MIRParserImpl::createDummyFunction (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create an empty function with the given name.</p>

<p>Definition at line 99 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/mirparser-cpp">MIRParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a4a5b798214be930cf8e133c032ba0129">llvm::BasicBlock::Create</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a05d7aedbbdc0fd24e8bc27edfe9c603f">llvm::Function::Create</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57ca6c93794d7b99cd433e96c53eadb15a6e">llvm::GlobalValue::ExternalLinkage</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/functiontype/#af8be7844c269f201ebcee1e15048c378">llvm::FunctionType::get</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a9fffac2512fe651f0d5e37e27f5bd51c">llvm::Function::getContext</a> and <a href="/web-llvm/docs/api/classes/llvm/type/#a6e20e76960d952de088354cbcd14c3ab">llvm::Type::getVoidTy</a>.</p>


<p>Referenced by <a href="#afbccb941c0215a918667f3a574b976b9">parseMachineFunction</a>.</p>

</div>
</div>

### error() {#a0219c7f9cad07740ec0c2d18dac6e946}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MIRParserImpl::error (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Message)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Report an error with the given message at unknown location.</p>


<p>Always returns true.</p>


<p>Definition at line 78 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/mirparser-cpp">MIRParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/sourcemgr/#a346262ff27e71aff626fe6548ef8a777adaf658d40b0b4eb15c0350864c87c2b8">llvm::SourceMgr::DK_Error</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abfcab32516704f11d146c757f402ad5caa73815097c71f15fe54ab447a7ff00ba">llvm::DS_Error</a> and <a href="/web-llvm/docs/api/classes/llvm/twine/#a4c1c1093a7749409c70838678514cc7c">llvm::Twine::str</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/mirparser-cpp/#aaaac05904c75a73a1ddf58e9b790ce38">typecheckMDNode</a>.</p>

</div>
</div>

### error() {#a02e579110bd0e0a8008ad1fb8718d45f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MIRParserImpl::error (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Message)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Report an error with the given message at the given location.</p>


<p>Always returns true.</p>


<p>Definition at line 83 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/mirparser-cpp">MIRParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/sourcemgr/#a346262ff27e71aff626fe6548ef8a777adaf658d40b0b4eb15c0350864c87c2b8">llvm::SourceMgr::DK_Error</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#abfcab32516704f11d146c757f402ad5caa73815097c71f15fe54ab447a7ff00ba">llvm::DS_Error</a>.</p>

</div>
</div>

### error() {#a93da07a8e8488d1f8a6c3cc183910bda}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MIRParserImpl::error (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smdiagnostic">SMDiagnostic</a> &amp; Error, <a href="/web-llvm/docs/api/classes/llvm/smrange">SMRange</a> SourceRange)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Report a given error with the location translated from the location in an embedded string literal to a location in the MIR file.</p>


<p>Always returns true.</p>


<p>Definition at line 89 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/mirparser-cpp">MIRParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/sourcemgr/#a346262ff27e71aff626fe6548ef8a777adaf658d40b0b4eb15c0350864c87c2b8">llvm::SourceMgr::DK_Error</a> and <a href="#a081423ee9e0967e35ecfcad1af58be23">reportDiagnostic</a>.</p>

</div>
</div>

### initializeCallSiteInfo() {#aea53e647298055af644a50c3a29e1411}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MIRParserImpl::initializeCallSiteInfo (<a href="/web-llvm/docs/api/structs/llvm/perfunctionmiparsingstate">PerFunctionMIParsingState</a> &amp; PFS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/yaml/machinefunction">yaml::MachineFunction</a> &amp; YamlMF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 127 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/mirparser-cpp">MIRParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#abc52118fc8160efd2667defd485e4a8e">llvm::MachineFunction::addCallSiteInfo</a>, <a href="/web-llvm/docs/api/structs/llvm/machinefunction/callsiteinfo/#a7dd0ce0929085262c9b87a02b532a411">llvm::MachineFunction::CallSiteInfo::ArgRegPairs</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/machineinstrloc/#aec118b50f06a567a4cd9c2672df78eca">llvm::yaml::MachineInstrLoc::BlockNum</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/machinefunction/#aadfb30b1968ac77ae1d8adabab992c5f">llvm::yaml::MachineFunction::CallSitesInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/symbolrecordmapping-cpp/#a9cdf893c7d17e47fa1ed8bebf92a5da4">error</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3d142c9e7c066059e15232c56dec9e2e">llvm::MachineFunction::getName</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#af777ff93c9e07a6ff5ffe3226deb3e76">llvm::MachineFunction::getTarget</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a26e1467ec6a91a35dfc32239e50f0fb5aa87e833111cd757568924c1c4b80e337">llvm::MachineInstr::IgnoreBundle</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a30e7d619f3195fd890116da8b3ed6bab">llvm::MachineInstr::isCall</a>, <a href="/web-llvm/docs/api/structs/llvm/perfunctionmiparsingstate/#ae7f8c6f160583712d2adaafb4cca24fe">llvm::PerFunctionMIParsingState::MF</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/machineinstrloc/#a2fa0de3b3a876eac2d341f1c52478242">llvm::yaml::MachineInstrLoc::Offset</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ae6d6d411dc7c73c8f28c468492c6a0e2">llvm::parseNamedRegisterReference</a>.</p>


<p>Referenced by <a href="#a3518bb886d39c70ab9163440243d2d5b">initializeMachineFunction</a>.</p>

</div>
</div>

### initializeConstantPool() {#a69398364db52b18db9d922fec6d8eb87}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MIRParserImpl::initializeConstantPool (<a href="/web-llvm/docs/api/structs/llvm/perfunctionmiparsingstate">PerFunctionMIParsingState</a> &amp; PFS, <a href="/web-llvm/docs/api/classes/llvm/machineconstantpool">MachineConstantPool</a> &amp; ConstantPool, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/yaml/machinefunction">yaml::MachineFunction</a> &amp; YamlMF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 150 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/mirparser-cpp">MIRParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/perfunctionmiparsingstate/#a5e33668004b320a3ccfc96d48a235302">llvm::PerFunctionMIParsingState::ConstantPoolSlots</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/machinefunction/#a8ebb130d06aa8c1b7de125c912bca5c0">llvm::yaml::MachineFunction::Constants</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5f6182886dc2f96c204299e92c1565d5">llvm::dyn_cast_or_null</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/symbolrecordmapping-cpp/#a9cdf893c7d17e47fa1ed8bebf92a5da4">error</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a739b30c811f1eece61b05320ddf44e5b">llvm::GlobalValue::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#adb33f3ede2f5bfc9b3ee658aaf648492">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::insert</a>, <a href="/web-llvm/docs/api/structs/llvm/perfunctionmiparsingstate/#ae7f8c6f160583712d2adaafb4cca24fe">llvm::PerFunctionMIParsingState::MF</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#abf2c472d771169c6100c6302079309da">llvm::parseConstantValue</a>.</p>


<p>Referenced by <a href="#a3518bb886d39c70ab9163440243d2d5b">initializeMachineFunction</a>.</p>

</div>
</div>

### initializeFrameInfo() {#a14e404f789b4aa6b37a554702f0c28ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MIRParserImpl::initializeFrameInfo (<a href="/web-llvm/docs/api/structs/llvm/perfunctionmiparsingstate">PerFunctionMIParsingState</a> &amp; PFS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/yaml/machinefunction">yaml::MachineFunction</a> &amp; YamlMF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 124 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/mirparser-cpp">MIRParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/yaml/machineframeinfo/#a5bf18fefab479cb029f0e9f108729c1d">llvm::yaml::MachineFrameInfo::AdjustsStack</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a03cf34252938b54f7e86c736f9fd7dc1">llvm::MachineFrameInfo::CreateFixedObject</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#ad2270087c6b8d7061c3a5e83fb61c0a6">llvm::MachineFrameInfo::CreateFixedSpillStackObject</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a1ae307f415a8989475e3f7ddd6eefc8b">llvm::MachineFrameInfo::CreateStackObject</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#ab9af51d42f8f27a88d68ee1d1deb5eb7">llvm::MachineFrameInfo::CreateVariableSizedObject</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/machineframeinfo/#abe8303ed6b0f0d79541058d84e663622">llvm::yaml::MachineFrameInfo::CVBytesOfCalleeSavedRegisters</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5f6182886dc2f96c204299e92c1565d5">llvm::dyn_cast_or_null</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a1f09e99062be1101e3a2cf3ff88878f7">llvm::MachineFrameInfo::ensureMaxAlignment</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/machinefunction/#a59151a92c7061811f3634c5bb91f066d">llvm::yaml::MachineFunction::EntryValueObjects</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/symbolrecordmapping-cpp/#a9cdf893c7d17e47fa1ed8bebf92a5da4">error</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/machinefunction/#ac62b09916d93504555ac2dfebad458f0">llvm::yaml::MachineFunction::FixedStackObjects</a>, <a href="/web-llvm/docs/api/structs/llvm/perfunctionmiparsingstate/#a19f71c010b6aa6cb68154df3628b105c">llvm::PerFunctionMIParsingState::FixedStackObjectSlots</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/machinefunction/#af74e9ad9493c6d667c9ffc71941e0468">llvm::yaml::MachineFunction::FrameInfo</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/machineframeinfo/#afb21232f3c7815e299a2ac4045079ce2">llvm::yaml::MachineFrameInfo::FunctionContext</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a54f334a9c8ca6d105eae383ae87e4524">llvm::MachineFunction::getFrameInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/targetsubtargetinfo/#ac83b44e69c9f9f4f9d60be2d72f4a5df">llvm::TargetSubtargetInfo::getFrameLowering</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/machineframeinfo/#a306aa6e7fca4dc92686608c643fcca8a">llvm::yaml::MachineFrameInfo::HasCalls</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/machineframeinfo/#a9016735335a3c6435f7f16116825219c">llvm::yaml::MachineFrameInfo::HasMustTailInVarArgFunc</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/machineframeinfo/#af0e50d4ef5d9bc86991571c9619de069">llvm::yaml::MachineFrameInfo::HasOpaqueSPAdjustment</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/machineframeinfo/#a51235e1a5d7863dc6e9933438de22e6d">llvm::yaml::MachineFrameInfo::HasPatchPoint</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/machineframeinfo/#a0498221b210f6df4f02fd3add9725c29">llvm::yaml::MachineFrameInfo::HasStackMap</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/machineframeinfo/#a5ed48d893132df78f141176402c448db">llvm::yaml::MachineFrameInfo::HasTailCall</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/machineframeinfo/#a4e92ff52f16ad6886618a56be6a9d055">llvm::yaml::MachineFrameInfo::HasVAStart</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#adb33f3ede2f5bfc9b3ee658aaf648492">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::insert</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/machineframeinfo/#a3b6b5df16492bd4c6f017af899a9a146">llvm::yaml::MachineFrameInfo::IsCalleeSavedInfoValid</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/machineframeinfo/#aa9b00eeb533d4001da1e812507e16959">llvm::yaml::MachineFrameInfo::IsFrameAddressTaken</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/machineframeinfo/#afa74fd3cd131ed4389fde07f7e2b89f0">llvm::yaml::MachineFrameInfo::IsReturnAddressTaken</a>, <a href="/web-llvm/docs/api/classes/llvm/targetframelowering/#a6e380efd1c5b2089017a2b2b04b2e95d">llvm::TargetFrameLowering::isSupportedStackID</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/machineframeinfo/#ab55df3c6c13bf6d53d1488479ea7c0bc">llvm::yaml::MachineFrameInfo::LocalFrameSize</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a853b47f34cdca978a18d7120e64bd4a1">llvm::MachineFrameInfo::mapLocalFrameObject</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/machineframeinfo/#a8d6fb6a5a29375a2921f6790102343da">llvm::yaml::MachineFrameInfo::MaxAlignment</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/machineframeinfo/#a44e7d9e28508a268f8b00da0eb02d792">llvm::yaml::MachineFrameInfo::MaxCallFrameSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/structs/llvm/perfunctionmiparsingstate/#ae7f8c6f160583712d2adaafb4cca24fe">llvm::PerFunctionMIParsingState::MF</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/machineframeinfo/#aca7b8fcc1a367fef683a9da2d099d8a4">llvm::yaml::MachineFrameInfo::OffsetAdjustment</a>, <a href="#abcac742b9eada6520eb78f1fcc9ba35d">parseCalleeSavedRegister</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae6d6d411dc7c73c8f28c468492c6a0e2">llvm::parseNamedRegisterReference</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a08a8c609669414a1232956e43255bd38">llvm::parseStackObjectReference</a>, <a href="#a350e13622868acbfca1779538a0f3b9b">parseStackObjectsDebugInfo</a>, <a href="#a7db0bf7fbc32682239ef46f866c36016">parseVarExprLoc</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/machineframeinfo/#a0a35e68f5c41b739bbe9c62797258568">llvm::yaml::MachineFrameInfo::RestorePoint</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/machineframeinfo/#ad430069d4a06a264245119f22a382968">llvm::yaml::MachineFrameInfo::SavePoint</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a14ca8f1aa1c62b860504b766ad3b15f9">llvm::MachineFrameInfo::setAdjustsStack</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#ab3f912e64e60536d8369f1414b7ef380">llvm::MachineFrameInfo::setCalleeSavedInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a7e65d5ed1e6c20323a0d723c43a9f264">llvm::MachineFrameInfo::setCalleeSavedInfoValid</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a5ed62fb6fd245cb4efd8ea1bb4d56856">llvm::MachineFrameInfo::setCVBytesOfCalleeSavedRegisters</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a4b9a38005d95189db3246e0e4ec6088d">llvm::MachineFrameInfo::setFrameAddressIsTaken</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#afe5772922837eb92e41c2d397809c9eb">llvm::MachineFrameInfo::setFunctionContextIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a5bb88f5f9d77d753e87c256950f16955">llvm::MachineFrameInfo::setHasCalls</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#aef2320fad6df35f6fca25cd93720da60">llvm::MachineFrameInfo::setHasMustTailInVarArgFunc</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#aa1c21b032c9a8c45eed19c74c40e9999">llvm::MachineFrameInfo::setHasOpaqueSPAdjustment</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a24116ef8cbdb5ac84d8b39da3123a2ba">llvm::MachineFrameInfo::setHasPatchPoint</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a516c061efff162d3443801359559aa65">llvm::MachineFrameInfo::setHasStackMap</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a701abf47478571dfb8c619678b7ce7d7">llvm::MachineFrameInfo::setHasTailCall</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#ae52ff27f281ac6f032b78b0d95bc7d24">llvm::MachineFrameInfo::setHasVAStart</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a39e8a5cc0ba7568b8e0584139d97c0cc">llvm::MachineFrameInfo::setLocalFrameSize</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a02a7503d1af1782b35b3683e173cb5f0">llvm::MachineFrameInfo::setMaxCallFrameSize</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#af4c34648ca4596767ff0c3409fc3f2d9">llvm::MachineFrameInfo::setObjectAlignment</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a3cd29e7edbcaceb5834eaa7d089a5bc4">llvm::MachineFrameInfo::setObjectOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#af941923e75bebb485321894b2ddbeb0a">llvm::MachineFrameInfo::setOffsetAdjustment</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a17b15f54419f33a561a4b6959b2d0969">llvm::MachineFrameInfo::setRestorePoint</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a81b01652144140bfb79c6ffdaff923f9">llvm::MachineFrameInfo::setReturnAddressIsTaken</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#abc98dd738845a40c876cbbf6f5e51f09">llvm::MachineFrameInfo::setSavePoint</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a6ba514594eb802f087046edbe201f8f4">llvm::MachineFrameInfo::setStackID</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a79ce969f0376bbc0a6f06966ce274167">llvm::MachineFrameInfo::setStackProtectorIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#ae4d51e9e70d6a7fb366f2a09d10a0945">llvm::MachineFrameInfo::setStackSize</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ac523d75b0141b2e47d95ebce7adc0ebc">llvm::MachineFunction::setVariableDbgInfo</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/stringvalue/#a62537bd770b4aa64686f83ff5d57392e">llvm::yaml::StringValue::SourceRange</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/fixedmachinestackobject/#a8f6272acd5c26ffaf9ee9c2ac6b7c88badcfc39ed7b8ef2094eefb99c5489ea33">llvm::yaml::FixedMachineStackObject::SpillSlot</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/machinestackobject/#a00910689f93f2d2788fd111a0f5f3c98ae1857f4d9ec015e8ad5d2ee7e314a547">llvm::yaml::MachineStackObject::SpillSlot</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/machinefunction/#a26ee805cbe23d49eeb1ec869ee64b831">llvm::yaml::MachineFunction::StackObjects</a>, <a href="/web-llvm/docs/api/structs/llvm/perfunctionmiparsingstate/#a952ba2c542e998e95f8d2dc847250845">llvm::PerFunctionMIParsingState::StackObjectSlots</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/machineframeinfo/#a7b38bb0439934cfd108a4e94039817d3">llvm::yaml::MachineFrameInfo::StackProtector</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/machineframeinfo/#a632ec82029fec352e6e4daed322f7e7a">llvm::yaml::MachineFrameInfo::StackSize</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/stringvalue/#a7b5941aef995e9272fb38c7b69fbb6e4">llvm::yaml::StringValue::Value</a> and <a href="/web-llvm/docs/api/structs/llvm/yaml/machinestackobject/#a00910689f93f2d2788fd111a0f5f3c98a01e62a4d3114de10ceb202f080f4f84f">llvm::yaml::MachineStackObject::VariableSized</a>.</p>


<p>Referenced by <a href="#a3518bb886d39c70ab9163440243d2d5b">initializeMachineFunction</a>.</p>

</div>
</div>

### initializeJumpTableInfo() {#a4e8962fa2139c288809acff971691109}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MIRParserImpl::initializeJumpTableInfo (<a href="/web-llvm/docs/api/structs/llvm/perfunctionmiparsingstate">PerFunctionMIParsingState</a> &amp; PFS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/yaml/machinejumptable">yaml::MachineJumpTable</a> &amp; YamlJTI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 154 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/mirparser-cpp">MIRParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machinejumptableinfo/#a5a48ea8ae9371565b98b24668016e5ef">llvm::MachineJumpTableInfo::createJumpTableIndex</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/machinejumptable/#a6986f1a514dddef9e9217329a45b54cc">llvm::yaml::MachineJumpTable::Entries</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/symbolrecordmapping-cpp/#a9cdf893c7d17e47fa1ed8bebf92a5da4">error</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3c6ee10aa5e2d19af3872a019e2b9375">llvm::MachineFunction::getOrCreateJumpTableInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#adb33f3ede2f5bfc9b3ee658aaf648492">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::insert</a>, <a href="/web-llvm/docs/api/structs/llvm/perfunctionmiparsingstate/#a000b59a1a49e0cf2befc72e409bd3ef3">llvm::PerFunctionMIParsingState::JumpTableSlots</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/machinejumptable/#ac8a93874ae04bba919a09c023a2170f0">llvm::yaml::MachineJumpTable::Kind</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a> and <a href="/web-llvm/docs/api/structs/llvm/perfunctionmiparsingstate/#ae7f8c6f160583712d2adaafb4cca24fe">llvm::PerFunctionMIParsingState::MF</a>.</p>


<p>Referenced by <a href="#a3518bb886d39c70ab9163440243d2d5b">initializeMachineFunction</a>.</p>

</div>
</div>

### initializeMachineFunction() {#a3518bb886d39c70ab9163440243d2d5b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MIRParserImpl::initializeMachineFunction (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/yaml/machinefunction">yaml::MachineFunction</a> &amp; YamlMF, <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Initialize the machine function to the state that's described in the MIR file.</p>


<p>Return true if error occurred.</p>


<p>Definition at line 115 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/mirparser-cpp">MIRParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/sourcemgr/#afe70aa1105a855036bdeb6426cac27db">llvm::SourceMgr::AddNewSourceBuffer</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/machinefunction/#a3c7726b1a6b7f283b069bbb0b635475f">llvm::yaml::MachineFunction::Alignment</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#af588c66ab3fcfe66fd0c99bcd645ee36">llvm::MachineFunction::assignBeginEndSections</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/machinefunction/#a10b0117a0460fe70fd0e4740a0a41241">llvm::yaml::MachineFunction::Body</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/machinefunction/#a2f5576db3c62625645adc327ee4f5052">llvm::yaml::MachineFunction::CallsEHReturn</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/machinefunction/#a31b15da483d0a8768ca941f4ca1fae7d">llvm::yaml::MachineFunction::CallsUnwindInit</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/machinefunction/#a8ebb130d06aa8c1b7de125c912bca5c0">llvm::yaml::MachineFunction::Constants</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/machinejumptable/#a6986f1a514dddef9e9217329a45b54cc">llvm::yaml::MachineJumpTable::Entries</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/symbolrecordmapping-cpp/#a9cdf893c7d17e47fa1ed8bebf92a5da4">error</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9a7b5c68c90f85baaedaa854cc5002cc">llvm::errs</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/machinefunction/#aeea0f7fcb710f25aae085b35964183ae">llvm::yaml::MachineFunction::ExposesReturnsTwice</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunctionproperties/#ad85237c6c667e4713efe8921e9c32ac1a8014afd87e04236365d1796e38bc15f5">llvm::MachineFunctionProperties::FailedISel</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/machinefunction/#a27d7806fe25e0c00e75bdc3a94c03c62">llvm::yaml::MachineFunction::FailedISel</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunctionproperties/#ad85237c6c667e4713efe8921e9c32ac1a006012900aff2102a22e6424f2994592">llvm::MachineFunctionProperties::FailsVerification</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/machinefunction/#a0e5937af98ee91491e15bcad511fbae7">llvm::yaml::MachineFunction::FailsVerification</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#aba1fee9e9c9b537fd2a02f33f714ca68">llvm::MachineFunction::getConstantPool</a>, <a href="/web-llvm/docs/api/classes/llvm/memorybuffer/#a0f68098734d6d3b451aacf5b38a67131">llvm::MemoryBuffer::getMemBuffer</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ac1f888bba00f32cb4f9a0010c958f397">llvm::MachineFunction::getProperties</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a810234b6b3d223b7c74a4253fcc5ea5e">llvm::MachineFunction::getRegInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#af777ff93c9e07a6ff5ffe3226deb3e76">llvm::MachineFunction::getTarget</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a74e97fc3012191edf10e8c51291da4a7">llvm::MachineFunction::hasBBSections</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/machinefunction/#ace3586455329b8de92d6857cc4e5a255">llvm::yaml::MachineFunction::HasEHCatchret</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/machinefunction/#accac34c441267d31490a426fa871c892">llvm::yaml::MachineFunction::HasEHFunclets</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/machinefunction/#a982bf1866296321d833c4c54011a9393">llvm::yaml::MachineFunction::HasEHScopes</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/machinefunction/#ab3ffdf1d35d7990b7638d08bc6218a6b">llvm::yaml::MachineFunction::HasWinCFI</a>, <a href="#aea53e647298055af644a50c3a29e1411">initializeCallSiteInfo</a>, <a href="#a69398364db52b18db9d922fec6d8eb87">initializeConstantPool</a>, <a href="#a14e404f789b4aa6b37a554702f0c28ae">initializeFrameInfo</a>, <a href="#a4e8962fa2139c288809acff971691109">initializeJumpTableInfo</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/machinefunction/#ae60e01471d2263c6c6ed653bd7d05a93">llvm::yaml::MachineFunction::IsOutlined</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/machinefunction/#ae6bdcb605d4ef43e0e7486b009ce49a0">llvm::yaml::MachineFunction::JumpTableInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunctionproperties/#ad85237c6c667e4713efe8921e9c32ac1aefa6e814420e5fc1dfad353869159a37">llvm::MachineFunctionProperties::Legalized</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/machinefunction/#add00963bb9e345967a5d15e26a94ea0c">llvm::yaml::MachineFunction::Legalized</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/machinefunction/#ade5f2c6b21e9075909823e4f3383520b">llvm::yaml::MachineFunction::MachineFuncInfo</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/machinefunction/#a2baf55b45f594519e22af6975eea84e2">llvm::yaml::MachineFunction::MachineMetadataNodes</a>, <a href="/web-llvm/docs/api/classes/llvm/targetsubtargetinfo/#a9e6de090b178b663c02bc8aa8fe70226">llvm::TargetSubtargetInfo::mirFileLoaded</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>, <a href="#a9d55670b674a7d3bc9f2df1668d63be8">parseCalledGlobals</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a46e5b5618c54f98506becf5e4878b626">llvm::parseMachineBasicBlockDefinitions</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abb9e54f3e39333556759f12543621846">llvm::parseMachineInstructions</a>, <a href="#add4fede1a05c8d8148b6ef72f2da3494">parseMachineMetadataNodes</a>, <a href="#a0cd181d3140028362e24cdc5d675ac16">parseRegisterInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunctionproperties/#ad85237c6c667e4713efe8921e9c32ac1a062927be2f9d18d9995e64b0779c3dcf">llvm::MachineFunctionProperties::RegBankSelected</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/machinefunction/#a5c415cc48ef81a0d2b31ab5bd9dcf281">llvm::yaml::MachineFunction::RegBankSelected</a>, <a href="#a081423ee9e0967e35ecfcad1af58be23">reportDiagnostic</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunctionproperties/#ad85237c6c667e4713efe8921e9c32ac1a91b442d385b54e1418d81adc34871053">llvm::MachineFunctionProperties::Selected</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/machinefunction/#a4c9919ff2d03b35595aa261a510e1f0d">llvm::yaml::MachineFunction::Selected</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunctionproperties/#aa7780563d7ca260d0ae67d957b56427f">llvm::MachineFunctionProperties::set</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a4b3445417981acbcdd4f4f0089a29de8">llvm::MachineFunction::setAlignment</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a4196ab45a8b997c0c7a0f2b1cf5f1969">llvm::MachineFunction::setCallsEHReturn</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a122edbb5c5297c3db56edfcaf1176a26">llvm::MachineFunction::setCallsUnwindInit</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a264579e2d24c216da3bd59985907e60a">llvm::MachineFunction::setExposesReturnsTwice</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3d4a88a04d48c381b5e9d9ea93c515e5">llvm::MachineFunction::setHasEHCatchret</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a1d782e1998ba28bc8ccd7eb843c05145">llvm::MachineFunction::setHasEHFunclets</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#aca75b4e226f440516b523cda6e9ef730">llvm::MachineFunction::setHasEHScopes</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a330afa0baf556056f9c032480dd57347">llvm::MachineFunction::setHasWinCFI</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#aa2c7c5b384c76cec2bfb10c27be020f5">llvm::MachineFunction::setIsOutlined</a>, <a href="#a0909a505055aae0cb9dee8e5730b3724">setupRegisterInfo</a>, <a href="/web-llvm/docs/api/structs/llvm/perfunctionmiparsingstate/#a04c6eaa02b55eaf51e4b182bd0c640cb">llvm::PerFunctionMIParsingState::SM</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/stringvalue/#a62537bd770b4aa64686f83ff5d57392e">llvm::yaml::StringValue::SourceRange</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunctionproperties/#ad85237c6c667e4713efe8921e9c32ac1a76b22d924565975a49b2283fa838e5f2">llvm::MachineFunctionProperties::TracksDebugUserValues</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/machinefunction/#a8757f3219b5b658572cec694611f0b64">llvm::yaml::MachineFunction::TracksDebugUserValues</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/blockstringvalue/#a3e6ec08737f4978c37a681cfbd0c9f65">llvm::yaml::BlockStringValue::Value</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/stringvalue/#a7b5941aef995e9272fb38c7b69fbb6e4">llvm::yaml::StringValue::Value</a>, <a href="/web-llvm/docs/api/structs/llvm/maybealign/#a06846474be3ab85f8d30c388faf3b116">llvm::MaybeAlign::valueOrOne</a> and <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a8efc9cbc802adc2bb2673b4ba6308869">llvm::MachineFunction::verify</a>.</p>


<p>Referenced by <a href="#afbccb941c0215a918667f3a574b976b9">parseMachineFunction</a>.</p>

</div>
</div>

### parseCalledGlobals() {#a9d55670b674a7d3bc9f2df1668d63be8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MIRParserImpl::parseCalledGlobals (<a href="/web-llvm/docs/api/structs/llvm/perfunctionmiparsingstate">PerFunctionMIParsingState</a> &amp; PFS, <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/yaml/machinefunction">yaml::MachineFunction</a> &amp; YMF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 161 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/mirparser-cpp">MIRParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ae8ce46656dc5a130e73673e891256125">llvm::MachineFunction::addCalledGlobal</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/machineinstrloc/#aec118b50f06a567a4cd9c2672df78eca">llvm::yaml::MachineInstrLoc::BlockNum</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/machinefunction/#a38c6e87eb849a07b79b7c06a19fdf659">llvm::yaml::MachineFunction::CalledGlobals</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/symbolrecordmapping-cpp/#a9cdf893c7d17e47fa1ed8bebf92a5da4">error</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3d142c9e7c066059e15232c56dec9e2e">llvm::MachineFunction::getName</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a26e1467ec6a91a35dfc32239e50f0fb5aa87e833111cd757568924c1c4b80e337">llvm::MachineInstr::IgnoreBundle</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a30e7d619f3195fd890116da8b3ed6bab">llvm::MachineInstr::isCall</a> and <a href="/web-llvm/docs/api/structs/llvm/yaml/machineinstrloc/#a2fa0de3b3a876eac2d341f1c52478242">llvm::yaml::MachineInstrLoc::Offset</a>.</p>


<p>Referenced by <a href="#a3518bb886d39c70ab9163440243d2d5b">initializeMachineFunction</a>.</p>

</div>
</div>

### parseCalleeSavedRegister() {#abcac742b9eada6520eb78f1fcc9ba35d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MIRParserImpl::parseCalleeSavedRegister (<a href="/web-llvm/docs/api/structs/llvm/perfunctionmiparsingstate">PerFunctionMIParsingState</a> &amp; PFS, std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/calleesavedinfo">CalleeSavedInfo</a> &gt; &amp; CSIInfo, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/yaml/stringvalue">yaml::StringValue</a> &amp; RegisterSource, bool IsRestored, int FrameIdx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 130 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/mirparser-cpp">MIRParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/symbolrecordmapping-cpp/#a9cdf893c7d17e47fa1ed8bebf92a5da4">error</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae6d6d411dc7c73c8f28c468492c6a0e2">llvm::parseNamedRegisterReference</a>, <a href="/web-llvm/docs/api/classes/llvm/calleesavedinfo/#a4af79cf20ef6f2770049ebb3a395d178">llvm::CalleeSavedInfo::setRestored</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/stringvalue/#a62537bd770b4aa64686f83ff5d57392e">llvm::yaml::StringValue::SourceRange</a> and <a href="/web-llvm/docs/api/structs/llvm/yaml/stringvalue/#a7b5941aef995e9272fb38c7b69fbb6e4">llvm::yaml::StringValue::Value</a>.</p>


<p>Referenced by <a href="#a14e404f789b4aa6b37a554702f0c28ae">initializeFrameInfo</a>.</p>

</div>
</div>

### parseIRModule() {#a453c89e061b40c47d23dca6d7be8d2c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; Module &gt; MIRParserImpl::parseIRModule (<a href="/web-llvm/docs/api/namespaces/llvm/#aa50ec5faa5aae091f99b0f840f58a379">DataLayoutCallbackTy</a> DataLayoutCallback)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Try to parse the optional LLVM module and the machine functions in the MIR file.</p>


<p>Return null if an error occurred.</p>


<p>Definition at line 96 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/mirparser-cpp">MIRParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a5f6182886dc2f96c204299e92c1565d5">llvm::dyn_cast_or_null</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aacd73143fc1dac7545bf6cfc42ffe112">llvm::parseAssembly</a> and <a href="#a081423ee9e0967e35ecfcad1af58be23">reportDiagnostic</a>.</p>

</div>
</div>

### parseMachineFunction() {#afbccb941c0215a918667f3a574b976b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MIRParserImpl::parseMachineFunction (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M, <a href="/web-llvm/docs/api/classes/llvm/machinemoduleinfo">MachineModuleInfo</a> &amp; MMI, <a href="/web-llvm/docs/api/namespaces/llvm/#af9c9208365fd9ce11392b4d79485e259">ModuleAnalysisManager</a> * FAM)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Parse the machine function in the current YAML document.</p>


<p>Return true if an error occurred.</p>


<p>Definition at line 108 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/mirparser-cpp">MIRParser.cpp</a>.</p>


<p>References <a href="#a2bd6903bee5451ebaffd790ccf869664">createDummyFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/symbolrecordmapping-cpp/#a9cdf893c7d17e47fa1ed8bebf92a5da4">error</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#a83c7e5ca51099e4efa895791a02fb0ed">FAM</a>, <a href="/web-llvm/docs/api/classes/llvm/machinemoduleinfo/#ac1a4ac2dc30f53dff05d2c7b2d8ebaef">llvm::MachineModuleInfo::getMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/machinemoduleinfo/#a89ccc89e9bd5881953bd1524a0d29f84">llvm::MachineModuleInfo::getOrCreateMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/machinemoduleinfo/#aa9ff5ea479131ab7fa913ceb779bd875">llvm::MachineModuleInfo::getTarget</a>, <a href="#a3518bb886d39c70ab9163440243d2d5b">initializeMachineFunction</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/machinefunction/#ade5f2c6b21e9075909823e4f3383520b">llvm::yaml::MachineFunction::MachineFuncInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#a85bddafa659a93a7a67c9094648259be">MAM</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/machinefunction/#aba2e8ec06abbe646d4bd35e6a6e3a97c">llvm::yaml::MachineFunction::Name</a> and <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#a315c7135a7dd2656de0c8bdb497c5116">llvm::yaml::yamlize</a>.</p>


<p>Referenced by <a href="#aff4be0d6e305b2b9b41970bc607c528c">parseMachineFunctions</a>.</p>

</div>
</div>

### parseMachineFunctions() {#aff4be0d6e305b2b9b41970bc607c528c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MIRParserImpl::parseMachineFunctions (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M, <a href="/web-llvm/docs/api/classes/llvm/machinemoduleinfo">MachineModuleInfo</a> &amp; MMI, <a href="/web-llvm/docs/api/namespaces/llvm/#af9c9208365fd9ce11392b4d79485e259">ModuleAnalysisManager</a> * FAM=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 101 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/mirparser-cpp">MIRParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#a85bddafa659a93a7a67c9094648259be">MAM</a> and <a href="#afbccb941c0215a918667f3a574b976b9">parseMachineFunction</a>.</p>

</div>
</div>

### parseMachineMetadataNodes() {#add4fede1a05c8d8148b6ef72f2da3494}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MIRParserImpl::parseMachineMetadataNodes (<a href="/web-llvm/docs/api/structs/llvm/perfunctionmiparsingstate">PerFunctionMIParsingState</a> &amp; PFS, <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/yaml/machinefunction">yaml::MachineFunction</a> &amp; YMF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 157 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/mirparser-cpp">MIRParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/symbolrecordmapping-cpp/#a9cdf893c7d17e47fa1ed8bebf92a5da4">error</a>, <a href="/web-llvm/docs/api/structs/llvm/perfunctionmiparsingstate/#aae7833cc08e3b69a50ffa05d10e06348">llvm::PerFunctionMIParsingState::MachineForwardRefMDNodes</a> and <a href="/web-llvm/docs/api/structs/llvm/yaml/machinefunction/#a2baf55b45f594519e22af6975eea84e2">llvm::yaml::MachineFunction::MachineMetadataNodes</a>.</p>


<p>Referenced by <a href="#a3518bb886d39c70ab9163440243d2d5b">initializeMachineFunction</a>.</p>

</div>
</div>

### parseRegisterInfo() {#a0cd181d3140028362e24cdc5d675ac16}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MIRParserImpl::parseRegisterInfo (<a href="/web-llvm/docs/api/structs/llvm/perfunctionmiparsingstate">PerFunctionMIParsingState</a> &amp; PFS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/yaml/machinefunction">yaml::MachineFunction</a> &amp; YamlMF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 118 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/mirparser-cpp">MIRParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/machinefunction/#a3303a0dc072a32f8f6c197a2712c40ab">llvm::yaml::MachineFunction::CalleeSavedRegisters</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/symbolrecordmapping-cpp/#a9cdf893c7d17e47fa1ed8bebf92a5da4">error</a>, <a href="/web-llvm/docs/api/structs/llvm/vreginfo/#a8408a547dab7a555dbb2ec921a944141a5eaad4d1be16bfba57c6b97de5a674e9">llvm::VRegInfo::GENERIC</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a810234b6b3d223b7c74a4253fcc5ea5e">llvm::MachineFunction::getRegInfo</a>, <a href="/web-llvm/docs/api/structs/llvm/perfunctionmiparsingstate/#a0cf857c0d07b6c5d63ebdb58adfb174a">llvm::PerFunctionMIParsingState::getVRegInfo</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/machinefunction/#ab51f61ae0bd39115370428967ca3d51b">llvm::yaml::MachineFunction::LiveIns</a>, <a href="/web-llvm/docs/api/structs/llvm/perfunctionmiparsingstate/#ae7f8c6f160583712d2adaafb4cca24fe">llvm::PerFunctionMIParsingState::MF</a>, <a href="/web-llvm/docs/api/structs/llvm/vreginfo/#a8408a547dab7a555dbb2ec921a944141a83465f4ee6489afc731340ed6c9c99b6">llvm::VRegInfo::NORMAL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae6d6d411dc7c73c8f28c468492c6a0e2">llvm::parseNamedRegisterReference</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abc7e17ec6845c465279316efe03b5371">llvm::parseRegisterReference</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ade73344881e7f4f575682bf1bca283aa">llvm::parseVirtualRegisterReference</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/structs/llvm/vreginfo/#a8408a547dab7a555dbb2ec921a944141ad412f0f8ee146367d4b0ca7e1681e269">llvm::VRegInfo::REGBANK</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/machinefunction/#a7a8c97438b408f27171481c989bf78d8">llvm::yaml::MachineFunction::TracksRegLiveness</a> and <a href="/web-llvm/docs/api/structs/llvm/yaml/machinefunction/#ac2571f4b44b3f6a8beffcb959ca04f80">llvm::yaml::MachineFunction::VirtualRegisters</a>.</p>


<p>Referenced by <a href="#a3518bb886d39c70ab9163440243d2d5b">initializeMachineFunction</a>.</p>

</div>
</div>

### parseStackObjectsDebugInfo() {#a350e13622868acbfca1779538a0f3b9b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MIRParserImpl::parseStackObjectsDebugInfo (<a href="/web-llvm/docs/api/structs/llvm/perfunctionmiparsingstate">PerFunctionMIParsingState</a> &amp; PFS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> T &amp; Object, int FrameIdx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 146 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/mirparser-cpp">MIRParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/perfunctionmiparsingstate/#ae7f8c6f160583712d2adaafb4cca24fe">llvm::PerFunctionMIParsingState::MF</a>, <a href="#a7db0bf7fbc32682239ef46f866c36016">parseVarExprLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ac523d75b0141b2e47d95ebce7adc0ebc">llvm::MachineFunction::setVariableDbgInfo</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="#a14e404f789b4aa6b37a554702f0c28ae">initializeFrameInfo</a>.</p>

</div>
</div>

### parseVarExprLoc() {#a7db0bf7fbc32682239ef46f866c36016}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; MIRParserImpl::VarExprLoc &gt; MIRParserImpl::parseVarExprLoc (<a href="/web-llvm/docs/api/structs/llvm/perfunctionmiparsingstate">PerFunctionMIParsingState</a> &amp; PFS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/yaml/stringvalue">yaml::StringValue</a> &amp; VarStr, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/yaml/stringvalue">yaml::StringValue</a> &amp; ExprStr, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/yaml/stringvalue">yaml::StringValue</a> &amp; LocStr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 141 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/mirparser-cpp">MIRParser.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/mirparser-cpp/#aaaac05904c75a73a1ddf58e9b790ce38">typecheckMDNode</a>.</p>


<p>Referenced by <a href="#a14e404f789b4aa6b37a554702f0c28ae">initializeFrameInfo</a> and <a href="#a350e13622868acbfca1779538a0f3b9b">parseStackObjectsDebugInfo</a>.</p>

</div>
</div>

### reportDiagnostic() {#a081423ee9e0967e35ecfcad1af58be23}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MIRParserImpl::reportDiagnostic (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smdiagnostic">SMDiagnostic</a> &amp; Diag)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/mirparser-cpp">MIRParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/sourcemgr/#a346262ff27e71aff626fe6548ef8a777adaf658d40b0b4eb15c0350864c87c2b8">llvm::SourceMgr::DK_Error</a>, <a href="/web-llvm/docs/api/classes/llvm/sourcemgr/#a346262ff27e71aff626fe6548ef8a777ad5935d1ea3df60ee7ba90b8e23fa6b42">llvm::SourceMgr::DK_Note</a>, <a href="/web-llvm/docs/api/classes/llvm/sourcemgr/#a346262ff27e71aff626fe6548ef8a777ae5a15719ab746bdc7713c4784fc1c6ea">llvm::SourceMgr::DK_Remark</a>, <a href="/web-llvm/docs/api/classes/llvm/sourcemgr/#a346262ff27e71aff626fe6548ef8a777a6bcc8ac9374461ed0599334db63365d0">llvm::SourceMgr::DK_Warning</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abfcab32516704f11d146c757f402ad5caa73815097c71f15fe54ab447a7ff00ba">llvm::DS_Error</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abfcab32516704f11d146c757f402ad5ca320faa3dfbce0b3e99c5c255d45da362">llvm::DS_Note</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abfcab32516704f11d146c757f402ad5ca1cde8c8828756cdaf2a93260e247ae31">llvm::DS_Warning</a>, <a href="/web-llvm/docs/api/classes/llvm/smdiagnostic/#a17d8b2d1fcb48a67f4d620f46bed2977">llvm::SMDiagnostic::getKind</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>


<p>Referenced by <a href="#a93da07a8e8488d1f8a6c3cc183910bda">error</a>, <a href="#a3518bb886d39c70ab9163440243d2d5b">initializeMachineFunction</a> and <a href="#a453c89e061b40c47d23dca6d7be8d2c5">parseIRModule</a>.</p>

</div>
</div>

### setupRegisterInfo() {#a0909a505055aae0cb9dee8e5730b3724}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MIRParserImpl::setupRegisterInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/perfunctionmiparsingstate">PerFunctionMIParsingState</a> &amp; PFS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/yaml/machinefunction">yaml::MachineFunction</a> &amp; YamlMF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 121 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/mirparser-cpp">MIRParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/symbolrecordmapping-cpp/#a9cdf893c7d17e47fa1ed8bebf92a5da4">error</a>, <a href="/web-llvm/docs/api/structs/llvm/vreginfo/#a8408a547dab7a555dbb2ec921a944141a5eaad4d1be16bfba57c6b97de5a674e9">llvm::VRegInfo::GENERIC</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3d142c9e7c066059e15232c56dec9e2e">llvm::MachineFunction::getName</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a810234b6b3d223b7c74a4253fcc5ea5e">llvm::MachineFunction::getRegInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/targetsubtargetinfo/#a43c530c830206ecf5ad3359364634c75">llvm::TargetSubtargetInfo::getRegisterInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ae6876d59aeec5bc210b359fbdcf6c1ad">llvm::MachineOperand::getRegMask</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a55fdcb2a9df9a69067eed1bc17a0b927">llvm::MachineOperand::isRegMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/structs/llvm/perfunctionmiparsingstate/#ae7f8c6f160583712d2adaafb4cca24fe">llvm::PerFunctionMIParsingState::MF</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>, <a href="/web-llvm/docs/api/structs/llvm/vreginfo/#a8408a547dab7a555dbb2ec921a944141a83465f4ee6489afc731340ed6c9c99b6">llvm::VRegInfo::NORMAL</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>, <a href="/web-llvm/docs/api/structs/llvm/vreginfo/#a8408a547dab7a555dbb2ec921a944141ad412f0f8ee146367d4b0ca7e1681e269">llvm::VRegInfo::REGBANK</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>, <a href="/web-llvm/docs/api/structs/llvm/vreginfo/#a8408a547dab7a555dbb2ec921a944141a592454c2980a78a8164c4d7514b9f4bb">llvm::VRegInfo::UNKNOWN</a>, <a href="/web-llvm/docs/api/structs/llvm/perfunctionmiparsingstate/#af04a49c4719319a475237aa431d2c1ba">llvm::PerFunctionMIParsingState::VRegInfos</a> and <a href="/web-llvm/docs/api/structs/llvm/perfunctionmiparsingstate/#a6c00589d8b2d82496406b0ceeb825d2a">llvm::PerFunctionMIParsingState::VRegInfosNamed</a>.</p>


<p>Referenced by <a href="#a3518bb886d39c70ab9163440243d2d5b">initializeMachineFunction</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### computeFunctionProperties() {#a34aea37f8cfe23566cc442a2e56f0e86}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MIRParserImpl::computeFunctionProperties (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/yaml/machinefunction">yaml::MachineFunction</a> &amp; YamlMF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 184 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/mirparser-cpp">MIRParser.cpp</a>.</p>

</div>
</div>

### diagFromBlockStringDiag() {#a82e7ae721839ce66bd6162bbb9f6e47a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SMDiagnostic MIRParserImpl::diagFromBlockStringDiag (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smdiagnostic">SMDiagnostic</a> &amp; Error, <a href="/web-llvm/docs/api/classes/llvm/smrange">SMRange</a> SourceRange)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return a MIR diagnostic converted from a diagnostic located in a YAML block scalar string.</p>

<p>Definition at line 181 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/mirparser-cpp">MIRParser.cpp</a>.</p>

</div>
</div>

### diagFromMIStringDiag() {#a92d79d3c68c93855864dfd76d1743dd3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SMDiagnostic MIRParserImpl::diagFromMIStringDiag (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smdiagnostic">SMDiagnostic</a> &amp; Error, <a href="/web-llvm/docs/api/classes/llvm/smrange">SMRange</a> SourceRange)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return a MIR diagnostic converted from an MI string diagnostic.</p>

<p>Definition at line 176 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/mirparser-cpp">MIRParser.cpp</a>.</p>

</div>
</div>

### parseMachineInst() {#aacd18dc953a6910eda622f48ea460048}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MIRParserImpl::parseMachineInst (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/structs/llvm/yaml/machineinstrloc">yaml::MachineInstrLoc</a> MILoc, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> *&amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 190 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/mirparser-cpp">MIRParser.cpp</a>.</p>

</div>
</div>

### parseMachineMetadata() {#aef0fcc2f0d275f3823d66a81c56b1d4e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MIRParserImpl::parseMachineMetadata (<a href="/web-llvm/docs/api/structs/llvm/perfunctionmiparsingstate">PerFunctionMIParsingState</a> &amp; PFS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/yaml/stringvalue">yaml::StringValue</a> &amp; Source)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 172 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/mirparser-cpp">MIRParser.cpp</a>.</p>

</div>
</div>

### parseMBBReference() {#a8ab9f981c0577a86d566108a57fd85eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MIRParserImpl::parseMBBReference (<a href="/web-llvm/docs/api/structs/llvm/perfunctionmiparsingstate">PerFunctionMIParsingState</a> &amp; PFS, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *&amp; MBB, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/yaml/stringvalue">yaml::StringValue</a> &amp; Source)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 168 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/mirparser-cpp">MIRParser.cpp</a>.</p>

</div>
</div>

### parseMDNode() {#a185886cd3957b9b6b342c4633f268348}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MIRParserImpl::parseMDNode (<a href="/web-llvm/docs/api/structs/llvm/perfunctionmiparsingstate">PerFunctionMIParsingState</a> &amp; PFS, <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> *&amp; Node, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/yaml/stringvalue">yaml::StringValue</a> &amp; Source)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 165 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/mirparser-cpp">MIRParser.cpp</a>.</p>

</div>
</div>

### setupDebugValueTracking() {#aeda1882b76b24a0d5d1ac86a1299339b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MIRParserImpl::setupDebugValueTracking (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/structs/llvm/perfunctionmiparsingstate">PerFunctionMIParsingState</a> &amp; PFS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/yaml/machinefunction">yaml::MachineFunction</a> &amp; YamlMF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 187 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/mirparser-cpp">MIRParser.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Context {#a6cf417e74c530d70d860f6e4a32106a6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMContext&amp; llvm::MIRParserImpl::Context</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/mirparser-cpp">MIRParser.cpp</a>.</p>

</div>
</div>

### Filename {#a9250e1fa9856a086c1b378fdd5504118}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::MIRParserImpl::Filename</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 55 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/mirparser-cpp">MIRParser.cpp</a>.</p>

</div>
</div>

### In {#acc8c7cb13b2d580e488d378fcb732c76}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">yaml::Input llvm::MIRParserImpl::In</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 54 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/mirparser-cpp">MIRParser.cpp</a>.</p>

</div>
</div>

### IRSlots {#ad44270bab272ab9139c4775670625087}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SlotMapping llvm::MIRParserImpl::IRSlots</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 56 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/mirparser-cpp">MIRParser.cpp</a>.</p>

</div>
</div>

### NoLLVMIR {#aa769330724ce7d8f6142ae0f36691b98}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MIRParserImpl::NoLLVMIR = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>True when the MIR file doesn't have LLVM IR.</p>


<p>Dummy IR functions are created and inserted into the given module when this is true.</p>


<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/mirparser-cpp">MIRParser.cpp</a>.</p>

</div>
</div>

### NoMIRDocuments {#a74cdeef71d385f75e8aee33306a452c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MIRParserImpl::NoMIRDocuments = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>True when a well formed MIR file does not contain any MIR/machine function parts.</p>

<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/mirparser-cpp">MIRParser.cpp</a>.</p>

</div>
</div>

### ProcessIRFunction {#a7a38f61d8de68a8bc39ebc04a13933a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::function&lt;void(Function &amp;)&gt; llvm::MIRParserImpl::ProcessIRFunction</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 66 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/mirparser-cpp">MIRParser.cpp</a>.</p>

</div>
</div>

### SM {#a1bde191ffe3a2b4c9a5c5307944c5e07}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SourceMgr llvm::MIRParserImpl::SM</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/mirparser-cpp">MIRParser.cpp</a>.</p>

</div>
</div>

### Target {#ac7fe88b78bf43261a9a70dd5d5bc1565}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;PerTargetMIParsingState&gt; llvm::MIRParserImpl::Target</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/mirparser-cpp">MIRParser.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/mirparser-cpp">MIRParser.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>

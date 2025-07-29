---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/mirparser
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `MIRParser` Class

<p>This class initializes machine functions by applying the state loaded from a MIR file. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::MIRParser { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/mirparser/mirparser-h">llvm/CodeGen/MIRParser/MIRParser.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f4e62a313aa32098e6dece42f160bbd">MIRParser</a> (std::unique_ptr&lt; MIRParserImpl &gt; Impl)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6d5270e0457b968174f728f47eccb650">MIRParser</a> (const MIRParser &amp;)=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa65ccf0fb7d2302121c508f0e0946d0c">~MIRParser</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7a3656f6df00caa58ca005ee5b63a4e1">parseIRModule</a> (DataLayoutCallbackTy DataLayoutCallback=[](StringRef, StringRef) { return std::nullopt;})</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parses the optional LLVM IR module in the MIR file. <a href="#a7a3656f6df00caa58ca005ee5b63a4e1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a911b88526d380131a7909cc8d5f8c5cd">parseMachineFunctions</a> (Module &amp;M, MachineModuleInfo &amp;MMI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parses MachineFunctions in the MIR file and add them to the given <a href="/web-llvm/docs/api/classes/llvm/machinemoduleinfo">MachineModuleInfo</a> <span class="doxyComputerOutput">MMI</span>. <a href="#a911b88526d380131a7909cc8d5f8c5cd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a20340b8661bf7b699e8948b1a8a81ced">parseMachineFunctions</a> (Module &amp;M, ModuleAnalysisManager &amp;MAM)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parses MachineFunctions in the MIR file and add them as the result of <a href="/web-llvm/docs/api/classes/llvm/machinefunctionanalysis">MachineFunctionAnalysis</a> in <a href="/web-llvm/docs/api/namespaces/llvm/#a79ab9199d2ba6a1c9cac2b79efc194a3">ModulePassManager</a> <span class="doxyComputerOutput">MAM</span>. <a href="#a20340b8661bf7b699e8948b1a8a81ced">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/mirparserimpl">MIRParserImpl</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb6da93b07e0c846b913775902d54417">Impl</a></td>
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

<p>This class initializes machine functions by applying the state loaded from a MIR file.</p>

<p>Definition at line 45 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/mirparser/mirparser-h">MIRParser.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### MIRParser() {#a0f4e62a313aa32098e6dece42f160bbd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MIRParser::MIRParser (std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/mirparserimpl">MIRParserImpl</a> &gt; Impl)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 49 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/mirparser/mirparser-h">MIRParser.h</a>, definition at line 1211 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/mirparser-cpp">MIRParser.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a>.</p>


<p>Referenced by <a href="#a6d5270e0457b968174f728f47eccb650">MIRParser</a>.</p>

</div>
</div>

### MIRParser() {#a6d5270e0457b968174f728f47eccb650}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MIRParser::MIRParser (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mirparser">MIRParser</a> &amp;)</td>
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



<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/mirparser/mirparser-h">MIRParser.h</a>.</p>


<p>Reference <a href="#a0f4e62a313aa32098e6dece42f160bbd">MIRParser</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~MIRParser() {#aa65ccf0fb7d2302121c508f0e0946d0c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MIRParser::~MIRParser ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/mirparser/mirparser-h">MIRParser.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### parseIRModule() {#a7a3656f6df00caa58ca005ee5b63a4e1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; Module &gt; MIRParser::parseIRModule (<a href="/web-llvm/docs/api/namespaces/llvm/#aa50ec5faa5aae091f99b0f840f58a379">DataLayoutCallbackTy</a> DataLayoutCallback=[](<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>) { return std::nullopt;})</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Parses the optional LLVM IR module in the MIR file.</p>


<p>A new, empty module is created if the LLVM IR isn't present.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>nullptr if a parsing error occurred.</p></dd>
</dl>


<p>Declaration at line 58 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/mirparser/mirparser-h">MIRParser.h</a>, definition at line 1217 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/mirparser-cpp">MIRParser.cpp</a>.</p>

</div>
</div>

### parseMachineFunctions() {#a911b88526d380131a7909cc8d5f8c5cd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MIRParser::parseMachineFunctions (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M, <a href="/web-llvm/docs/api/classes/llvm/machinemoduleinfo">MachineModuleInfo</a> &amp; MMI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Parses MachineFunctions in the MIR file and add them to the given <a href="/web-llvm/docs/api/classes/llvm/machinemoduleinfo">MachineModuleInfo</a> <span class="doxyComputerOutput">MMI</span>.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if an error occurred.</p></dd>
</dl>


<p>Declaration at line 65 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/mirparser/mirparser-h">MIRParser.h</a>, definition at line 1221 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/mirparser-cpp">MIRParser.cpp</a>.</p>

</div>
</div>

### parseMachineFunctions() {#a20340b8661bf7b699e8948b1a8a81ced}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MIRParser::parseMachineFunctions (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M, <a href="/web-llvm/docs/api/namespaces/llvm/#af9c9208365fd9ce11392b4d79485e259">ModuleAnalysisManager</a> &amp; MAM)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Parses MachineFunctions in the MIR file and add them as the result of <a href="/web-llvm/docs/api/classes/llvm/machinefunctionanalysis">MachineFunctionAnalysis</a> in <a href="/web-llvm/docs/api/namespaces/llvm/#a79ab9199d2ba6a1c9cac2b79efc194a3">ModulePassManager</a> <span class="doxyComputerOutput">MAM</span>.</p>


<p><a href="/web-llvm/docs/api/classes/llvm/user">User</a> should register at least <a href="/web-llvm/docs/api/classes/llvm/machinefunctionanalysis">MachineFunctionAnalysis</a>, <a href="/web-llvm/docs/api/classes/llvm/machinemoduleanalysis">MachineModuleAnalysis</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4143e067711d3c7795276b225a8d6eb9">FunctionAnalysisManagerModuleProxy</a> and <a href="/web-llvm/docs/api/classes/llvm/passinstrumentationanalysis">PassInstrumentationAnalysis</a> in <span class="doxyComputerOutput">MAM</span> before parsing MIR.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if an error occurred.</p></dd>
</dl>


<p>Declaration at line 74 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/mirparser/mirparser-h">MIRParser.h</a>, definition at line 1225 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/mirparser-cpp">MIRParser.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#a85bddafa659a93a7a67c9094648259be">MAM</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Impl {#abb6da93b07e0c846b913775902d54417}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;MIRParserImpl&gt; llvm::MIRParser::Impl</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/mirparser/mirparser-h">MIRParser.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/mirparser/mirparser-h">MIRParser.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/mirparser-cpp">MIRParser.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>

---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/llvm/mcparserutils
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# `MCParserUtils` Namespace



## Definition

<div class="doxyDefinition">
namespace llvm::MCParserUtils { ... }
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a71d0c2aeb5e324a4a962bcfa85617f2c">parseAssignmentExpression</a> (StringRef Name, bool allow_redef, MCAsmParser &amp;Parser, MCSymbol *&amp;Symbol, const MCExpr *&amp;Value)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parse a value expression and return whether it can be assigned to a symbol with the given name. <a href="#a71d0c2aeb5e324a4a962bcfa85617f2c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<div class="doxySectionDef">

## Functions

### parseAssignmentExpression() {#a71d0c2aeb5e324a4a962bcfa85617f2c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCParserUtils::parseAssignmentExpression (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, bool allow_redef, <a href="/web-llvm/docs/api/classes/llvm/mcasmparser">MCAsmParser</a> &amp; Parser, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> *&amp; Symbol, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> *&amp; Value)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Parse a value expression and return whether it can be assigned to a symbol with the given name.</p>


<p>On success, returns false and sets the Symbol and <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> output parameters.</p>


<p>Definition at line 6424 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#ac28f9bc04d492da0076b2852d4e9dded">llvm::MCStreamer::emitValueToOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparser/#afe58695435b93e0599ed2f77e877a0aa">llvm::MCAsmParser::Error</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparser/#af5501a0543911b575ec50e456ee228ae">llvm::MCAsmParser::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#a16611db1be4d04f03c570d9302504c04">llvm::AsmToken::getLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#ac11eef690074972378846024abbe8722">llvm::MCContext::getOrCreateSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparser/#a40ca835fddf3ca47f6b9a7bd43d929f0">llvm::MCAsmParser::getStreamer</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparser/#a607ccd51956df621f1f5ea07c5d3b2c6">llvm::MCAsmParser::getTok</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#a2192a3f25b0bc0505cc168a012038046">llvm::MCSymbol::getVariableValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#aa462dae167e31cac32e97bb0c77ab071">llvm::MCSymbol::isUndefined</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#a8f6614e2886fdbfefe64b8b2a7580295">llvm::MCSymbol::isUsed</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#a620bf1ce8489b3da259faf0c55a862aa">llvm::MCSymbol::isVariable</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#a7099c67764b3ea472791762cb6bd9e2f">llvm::MCContext::lookupSymbol</a>, <a href="#a71d0c2aeb5e324a4a962bcfa85617f2c">parseAssignmentExpression</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparser/#a7b442abcc8f942ce12304975367e1fa2">llvm::MCAsmParser::parseEOL</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparser/#a582bb95a08ad05ff3bd5de25a92edd4a">llvm::MCAsmParser::parseExpression</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#aa64f2a23a64ea508097104bbe78ad7ff">llvm::MCSymbol::setRedefinable</a> and <a href="/web-llvm/docs/api/classes/llvm/mcasmparser/#aca3b32b0f673fcda41b604540f49a4f9">llvm::MCAsmParser::TokError</a>.</p>


<p>Referenced by <a href="#a71d0c2aeb5e324a4a962bcfa85617f2c">parseAssignmentExpression</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp">AsmParser.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>

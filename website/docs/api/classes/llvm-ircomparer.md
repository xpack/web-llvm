---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/ircomparer
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `IRComparer` Class Template Reference



## Declaration

<div class="doxyDeclaration">
template &lt;typename T&gt;
class llvm::IRComparer&lt;T&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/standardinstrumentations-h">llvm/Passes/StandardInstrumentations.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a84064e5673c90b6db99c13762225bda2">IRComparer</a> (const IRDataT&lt; T &gt; &amp;Before, const IRDataT&lt; T &gt; &amp;After)</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ab12e7da19a8a01d2ee492ae7cb7d0831">compare</a> (bool CompareModule, std::function&lt; void(bool InModule, unsigned Minor, const FuncDataT&lt; T &gt; &amp;Before, const FuncDataT&lt; T &gt; &amp;After)&gt; CompareFunc)</td>
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

## Protected Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/irdatat">IRDataT</a>&lt; T &gt; &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a0399d94d8485be063ddcb0192dc8cea3">Before</a></td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/irdatat">IRDataT</a>&lt; T &gt; &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a837c7d8d75c02b05863151501feac0a0">After</a></td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a8760ed87ce8c468e4567141d3000e67c">analyzeIR</a> (Any IR, IRDataT&lt; T &gt; &amp;Data)</td>
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

## Protected Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename FunctionT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a26d5929376d42e6e04ff0877e26e71aa">generateFunctionData</a> (IRDataT&lt; T &gt; &amp;Data, const FunctionT &amp;F)</td>
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


<p>Definition at line 403 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/standardinstrumentations-h">StandardInstrumentations.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### IRComparer() {#a84064e5673c90b6db99c13762225bda2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::IRComparer&lt; T &gt;::IRComparer (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/irdatat">IRDataT</a>&lt; T &gt; &amp; Before, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/irdatat">IRDataT</a>&lt; T &gt; &amp; After)</td>
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



<p>Definition at line 405 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/standardinstrumentations-h">StandardInstrumentations.h</a>.</p>


<p>References <a href="#a837c7d8d75c02b05863151501feac0a0">llvm::IRComparer&lt; T &gt;::After</a> and <a href="#a0399d94d8485be063ddcb0192dc8cea3">llvm::IRComparer&lt; T &gt;::Before</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### compare() {#ab12e7da19a8a01d2ee492ae7cb7d0831}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void IRComparer::compare (bool CompareModule, std::function&lt; void(bool InModule, unsigned Minor, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/funcdatat">FuncDataT</a>&lt; T &gt; &amp;<a href="#a0399d94d8485be063ddcb0192dc8cea3">Before</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/funcdatat">FuncDataT</a>&lt; T &gt; &amp;<a href="#a837c7d8d75c02b05863151501feac0a0">After</a>)&gt; CompareFunc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 411 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/standardinstrumentations-h">StandardInstrumentations.h</a>, definition at line 669 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/standardinstrumentations-cpp">StandardInstrumentations.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="#a837c7d8d75c02b05863151501feac0a0">llvm::IRComparer&lt; T &gt;::After</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="#a0399d94d8485be063ddcb0192dc8cea3">llvm::IRComparer&lt; T &gt;::Before</a> and <a href="/web-llvm/docs/api/classes/llvm/orderedchangeddata/#a08f0240b1df29f4783ccd0e0f7ced7b7">llvm::OrderedChangedData&lt; FuncDataT&lt; T &gt; &gt;::report</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dotcfgchangereporter/#abdd394d923544b065d3bacb30ab0eb14">llvm::DotCfgChangeReporter::handleAfter</a>, <a href="/web-llvm/docs/api/classes/llvm/inlinechangeprinter/#a6560be42758e4a21d3a0075d6b14ad89">llvm::InLineChangePrinter::handleAfter</a> and <a href="/web-llvm/docs/api/classes/llvm/dotcfgchangereporter/#a615c5ec895d4fc067bccdf23990d691e">llvm::DotCfgChangeReporter::handleInitialIR</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### After {#a837c7d8d75c02b05863151501feac0a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const IRDataT&lt;T&gt;&amp; llvm::IRComparer&lt; T &gt;::After</td>
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



<p>Definition at line 426 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/standardinstrumentations-h">StandardInstrumentations.h</a>.</p>


<p>Referenced by <a href="#ab12e7da19a8a01d2ee492ae7cb7d0831">llvm::IRComparer&lt; T &gt;::compare</a> and <a href="#a84064e5673c90b6db99c13762225bda2">llvm::IRComparer&lt; T &gt;::IRComparer</a>.</p>

</div>
</div>

### Before {#a0399d94d8485be063ddcb0192dc8cea3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const IRDataT&lt;T&gt;&amp; llvm::IRComparer&lt; T &gt;::Before</td>
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



<p>Definition at line 425 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/standardinstrumentations-h">StandardInstrumentations.h</a>.</p>


<p>Referenced by <a href="#ab12e7da19a8a01d2ee492ae7cb7d0831">llvm::IRComparer&lt; T &gt;::compare</a> and <a href="#a84064e5673c90b6db99c13762225bda2">llvm::IRComparer&lt; T &gt;::IRComparer</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### analyzeIR() {#a8760ed87ce8c468e4567141d3000e67c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void IRComparer::analyzeIR (<a href="/web-llvm/docs/api/classes/llvm/any">Any</a> IR, <a href="/web-llvm/docs/api/classes/llvm/irdatat">IRDataT</a>&lt; T &gt; &amp; Data)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 418 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/standardinstrumentations-h">StandardInstrumentations.h</a>, definition at line 696 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/standardinstrumentations-cpp">StandardInstrumentations.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="#a26d5929376d42e6e04ff0877e26e71aa">llvm::IRComparer&lt; T &gt;::generateFunctionData</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizer-cpp/#a05ab4853f7153e537774d02580e761ec">IR</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a> and <a href="/web-llvm/docs/api/files/lib/lib/passes/standardinstrumentations-cpp/#aadda06082cd66f0282ca446bc410dfb6">unwrapIR</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dotcfgchangereporter/#a3ac37a6f140c650acd870e4c5713660f">llvm::DotCfgChangeReporter::generateIRRepresentation</a>, <a href="/web-llvm/docs/api/classes/llvm/inlinechangeprinter/#aa5359fcdd79ecebad94c436ebed24322">llvm::InLineChangePrinter::generateIRRepresentation</a> and <a href="/web-llvm/docs/api/classes/llvm/dotcfgchangereporter/#a615c5ec895d4fc067bccdf23990d691e">llvm::DotCfgChangeReporter::handleInitialIR</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Static Functions

### generateFunctionData() {#a26d5929376d42e6e04ff0877e26e71aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename FunctionT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool IRComparer::generateFunctionData (<a href="/web-llvm/docs/api/classes/llvm/irdatat">IRDataT</a>&lt; T &gt; &amp; Data, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> FunctionT &amp; F)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 423 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/standardinstrumentations-h">StandardInstrumentations.h</a>, definition at line 733 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/standardinstrumentations-cpp">StandardInstrumentations.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a653cce37b80c03eebe7a00520a8eabb6">llvm::formatv</a>, <a href="/web-llvm/docs/api/classes/llvm/orderedchangeddata/#a3846b5b4b33ce32278c67229a8ee3775">llvm::OrderedChangedData&lt; T &gt;::getData</a>, <a href="/web-llvm/docs/api/classes/llvm/orderedchangeddata/#afc006b2301774274b1035b587e2690e0">llvm::OrderedChangedData&lt; T &gt;::getOrder</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/stringmap/#afea367cbdd62e85c20d3ebe044253ce7">llvm::StringMap&lt; ValueTy, AllocatorTy &gt;::insert</a> and <a href="/web-llvm/docs/api/files/lib/lib/passes/standardinstrumentations-cpp/#a80e2fb07c2c1c12f53c6f6e93e04cc04">shouldGenerateData</a>.</p>


<p>Referenced by <a href="#a8760ed87ce8c468e4567141d3000e67c">llvm::IRComparer&lt; T &gt;::analyzeIR</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/standardinstrumentations-h">StandardInstrumentations.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/passes/standardinstrumentations-cpp">StandardInstrumentations.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>

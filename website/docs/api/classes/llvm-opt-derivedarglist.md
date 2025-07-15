---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/opt/derivedarglist
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `DerivedArgList` Class Reference

<p><a href="/web-llvm/docs/api/classes/llvm/opt/derivedarglist">DerivedArgList</a> - An ordered collection of driver arguments, whose storage may be in another argument list. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::opt::DerivedArgList { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/arglist-h">llvm/Option/ArgList.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/opt/arglist">ArgList</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/opt/arglist">ArgList</a> - Ordered collection of driver arguments. <a href="/web-llvm/docs/api/classes/llvm/opt/arglist/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d277d762ce98a3fc1696e9cbd68d4b7">DerivedArgList</a> (const InputArgList &amp;BaseArgs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct a new derived arg list from <span class="doxyComputerOutput">BaseArgs</span>. <a href="#a5d277d762ce98a3fc1696e9cbd68d4b7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a828078be898f5e342f458ac8bdaa6a4c">getArgString</a> (unsigned Index) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getArgString - Return the input argument string at <span class="doxyComputerOutput">Index</span>. <a href="#a828078be898f5e342f458ac8bdaa6a4c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a70237a37e944d733ebaf4929d9ffc3c4">getNumInputArgStrings</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getNumInputArgStrings - Return the number of original argument strings, which are guaranteed to be the first strings in the argument string list. <a href="#a70237a37e944d733ebaf4929d9ffc3c4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/opt/inputarglist">InputArgList</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7b0a8686d83a68c6472f23740a9ddc1c">getBaseArgs</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/opt/inputarglist">InputArgList</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a28e41bbb9ab385161eaef03bf3a3aead">BaseArgs</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/opt/arg">Arg</a> &gt;, 16 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b935a1d75d65d14f9ab43989b115ec6">SynthesizedArgs</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The list of arguments we synthesized. <a href="#a6b935a1d75d65d14f9ab43989b115ec6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Arg Synthesis Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3d55ec36adb7b3cd60797b4781ad586f">AddSynthesizedArg</a> (Arg *A)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>AddSynthesizedArg - Add a argument to the list of synthesized arguments (to be freed). <a href="#a3d55ec36adb7b3cd60797b4781ad586f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b6c382bbada1a154fe79e6260be6cfc">MakeArgStringRef</a> (StringRef Str) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct a constant string pointer whose lifetime will match that of the <a href="/web-llvm/docs/api/classes/llvm/opt/arglist">ArgList</a>. <a href="#a0b6c382bbada1a154fe79e6260be6cfc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3a30886094ab508b4a00828729da9d55">AddFlagArg</a> (const Arg *BaseArg, const Option Opt)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>AddFlagArg - Construct a new FlagArg for the given option <span class="doxyComputerOutput">Id</span> and append it to the argument list. <a href="#a3a30886094ab508b4a00828729da9d55">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a913fc3de04c49ef64ed77e50f0d5f7d9">AddPositionalArg</a> (const Arg *BaseArg, const Option Opt, StringRef Value)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>AddPositionalArg - Construct a new Positional arg for the given option <span class="doxyComputerOutput">Id</span>, with the provided <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a></span> and append it to the argument list. <a href="#a913fc3de04c49ef64ed77e50f0d5f7d9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aca09243bbb137b7edf07ad9b20181bf4">AddSeparateArg</a> (const Arg *BaseArg, const Option Opt, StringRef Value)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>AddSeparateArg - Construct a new Positional arg for the given option <span class="doxyComputerOutput">Id</span>, with the provided <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a></span> and append it to the argument list. <a href="#aca09243bbb137b7edf07ad9b20181bf4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a07d2e877f7b7ac9f51686c52df637170">AddJoinedArg</a> (const Arg *BaseArg, const Option Opt, StringRef Value)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>AddJoinedArg - Construct a new Positional arg for the given option <span class="doxyComputerOutput">Id</span>, with the provided <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a></span> and append it to the argument list. <a href="#a07d2e877f7b7ac9f51686c52df637170">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/opt/arg">Arg</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aca9495741a522bfdc26c89f88b16ff69">MakeFlagArg</a> (const Arg *BaseArg, const Option Opt) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>MakeFlagArg - Construct a new FlagArg for the given option <span class="doxyComputerOutput">Id</span>. <a href="#aca9495741a522bfdc26c89f88b16ff69">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/opt/arg">Arg</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a909c2fa4bf18ec1dbe50a77adf3f48a3">MakePositionalArg</a> (const Arg *BaseArg, const Option Opt, StringRef Value) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>MakePositionalArg - Construct a new Positional arg for the given option <span class="doxyComputerOutput">Id</span>, with the provided <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a></span>. <a href="#a909c2fa4bf18ec1dbe50a77adf3f48a3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/opt/arg">Arg</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2afff7edd330e44f3f1814a6e364c081">MakeSeparateArg</a> (const Arg *BaseArg, const Option Opt, StringRef Value) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>MakeSeparateArg - Construct a new Positional arg for the given option <span class="doxyComputerOutput">Id</span>, with the provided <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a></span>. <a href="#a2afff7edd330e44f3f1814a6e364c081">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/opt/arg">Arg</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5893f33295c921df5928e5ab9feb90cc">MakeJoinedArg</a> (const Arg *BaseArg, const Option Opt, StringRef Value) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>MakeJoinedArg - Construct a new Positional arg for the given option <span class="doxyComputerOutput">Id</span>, with the provided <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a></span>. <a href="#a5893f33295c921df5928e5ab9feb90cc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a678763a7949f037831ab90dcea55a817">MakeArgString</a> (const Twine &amp;Str) const</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/opt/derivedarglist">DerivedArgList</a> - An ordered collection of driver arguments, whose storage may be in another argument list.</p>

<p>Definition at line 466 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/arglist-h">ArgList.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### DerivedArgList() {#a5d277d762ce98a3fc1696e9cbd68d4b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DerivedArgList::DerivedArgList (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/opt/inputarglist">InputArgList</a> &amp; BaseArgs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Construct a new derived arg list from <span class="doxyComputerOutput">BaseArgs</span>.</p>

<p>Declaration at line 474 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/arglist-h">ArgList.h</a>, definition at line 241 of file <a href="/web-llvm/docs/api/files/lib/lib/option/arglist-cpp">ArgList.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getArgString() {#a828078be898f5e342f458ac8bdaa6a4c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * llvm::opt::DerivedArgList::getArgString (unsigned Index)</td>
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

<p>getArgString - Return the input argument string at <span class="doxyComputerOutput">Index</span>.</p>

<p>Definition at line 476 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/arglist-h">ArgList.h</a>.</p>

</div>
</div>

### getBaseArgs() {#a7b0a8686d83a68c6472f23740a9ddc1c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const InputArgList &amp; llvm::opt::DerivedArgList::getBaseArgs ()</td>
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



<p>Definition at line 484 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/arglist-h">ArgList.h</a>.</p>

</div>
</div>

### getNumInputArgStrings() {#a70237a37e944d733ebaf4929d9ffc3c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::opt::DerivedArgList::getNumInputArgStrings ()</td>
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

<p>getNumInputArgStrings - Return the number of original argument strings, which are guaranteed to be the first strings in the argument string list.</p>

<p>Definition at line 480 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/arglist-h">ArgList.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### BaseArgs {#a28e41bbb9ab385161eaef03bf3a3aead}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const InputArgList&amp; llvm::opt::DerivedArgList::BaseArgs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 467 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/arglist-h">ArgList.h</a>.</p>

</div>
</div>

### SynthesizedArgs {#a6b935a1d75d65d14f9ab43989b115ec6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;std::unique_ptr&lt;Arg&gt;, 16&gt; llvm::opt::DerivedArgList::SynthesizedArgs</td>
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

<p>The list of arguments we synthesized.</p>

<p>Definition at line 470 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/arglist-h">ArgList.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Arg Synthesis

### AddFlagArg {#a3a30886094ab508b4a00828729da9d55}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::opt::DerivedArgList::AddFlagArg (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/opt/arg">Arg</a> * BaseArg, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/opt/option">Option</a> Opt)</td>
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

<p>AddFlagArg - Construct a new FlagArg for the given option <span class="doxyComputerOutput">Id</span> and append it to the argument list.</p>

<p>Definition at line 500 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/arglist-h">ArgList.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/opt/arglist/#a862d6016ee6bbfb979acf4739b4fcfac">llvm::opt::ArgList::append</a> and <a href="#aca9495741a522bfdc26c89f88b16ff69">MakeFlagArg</a>.</p>

</div>
</div>

### AddJoinedArg {#a07d2e877f7b7ac9f51686c52df637170}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::opt::DerivedArgList::AddJoinedArg (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/opt/arg">Arg</a> * BaseArg, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/opt/option">Option</a> Opt, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Value)</td>
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

<p>AddJoinedArg - Construct a new Positional arg for the given option <span class="doxyComputerOutput">Id</span>, with the provided <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a></span> and append it to the argument list.</p>

<p>Definition at line 522 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/arglist-h">ArgList.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/opt/arglist/#a862d6016ee6bbfb979acf4739b4fcfac">llvm::opt::ArgList::append</a> and <a href="#a5893f33295c921df5928e5ab9feb90cc">MakeJoinedArg</a>.</p>

</div>
</div>

### AddPositionalArg {#a913fc3de04c49ef64ed77e50f0d5f7d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::opt::DerivedArgList::AddPositionalArg (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/opt/arg">Arg</a> * BaseArg, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/opt/option">Option</a> Opt, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Value)</td>
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

<p>AddPositionalArg - Construct a new Positional arg for the given option <span class="doxyComputerOutput">Id</span>, with the provided <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a></span> and append it to the argument list.</p>

<p>Definition at line 507 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/arglist-h">ArgList.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/opt/arglist/#a862d6016ee6bbfb979acf4739b4fcfac">llvm::opt::ArgList::append</a> and <a href="#a909c2fa4bf18ec1dbe50a77adf3f48a3">MakePositionalArg</a>.</p>

</div>
</div>

### AddSeparateArg {#aca09243bbb137b7edf07ad9b20181bf4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::opt::DerivedArgList::AddSeparateArg (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/opt/arg">Arg</a> * BaseArg, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/opt/option">Option</a> Opt, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Value)</td>
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

<p>AddSeparateArg - Construct a new Positional arg for the given option <span class="doxyComputerOutput">Id</span>, with the provided <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a></span> and append it to the argument list.</p>

<p>Definition at line 515 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/arglist-h">ArgList.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/opt/arglist/#a862d6016ee6bbfb979acf4739b4fcfac">llvm::opt::ArgList::append</a> and <a href="#a2afff7edd330e44f3f1814a6e364c081">MakeSeparateArg</a>.</p>

</div>
</div>

### AddSynthesizedArg {#a3d55ec36adb7b3cd60797b4781ad586f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DerivedArgList::AddSynthesizedArg (<a href="/web-llvm/docs/api/classes/llvm/opt/arg">Arg</a> * A)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>AddSynthesizedArg - Add a argument to the list of synthesized arguments (to be freed).</p>

<p>Declaration at line 493 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/arglist-h">ArgList.h</a>, definition at line 248 of file <a href="/web-llvm/docs/api/files/lib/lib/option/arglist-cpp">ArgList.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>.</p>

</div>
</div>

### MakeArgString {#a678763a7949f037831ab90dcea55a817}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * llvm::opt::ArgList::MakeArgString (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Str)</td>
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



<p>Definition at line 495 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/arglist-h">ArgList.h</a>.</p>


<p>Referenced by <a href="#aca9495741a522bfdc26c89f88b16ff69">MakeFlagArg</a>, <a href="#a5893f33295c921df5928e5ab9feb90cc">MakeJoinedArg</a>, <a href="#a909c2fa4bf18ec1dbe50a77adf3f48a3">MakePositionalArg</a> and <a href="#a2afff7edd330e44f3f1814a6e364c081">MakeSeparateArg</a>.</p>

</div>
</div>

### MakeArgStringRef {#a0b6c382bbada1a154fe79e6260be6cfc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * DerivedArgList::MakeArgStringRef (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Str)</td>
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

<p>Construct a constant string pointer whose lifetime will match that of the <a href="/web-llvm/docs/api/classes/llvm/opt/arglist">ArgList</a>.</p>

<p>Declaration at line 496 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/arglist-h">ArgList.h</a>, definition at line 244 of file <a href="/web-llvm/docs/api/files/lib/lib/option/arglist-cpp">ArgList.cpp</a>.</p>

</div>
</div>

### MakeFlagArg {#aca9495741a522bfdc26c89f88b16ff69}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Arg * DerivedArgList::MakeFlagArg (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/opt/arg">Arg</a> * BaseArg, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/opt/option">Option</a> Opt)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>MakeFlagArg - Construct a new FlagArg for the given option <span class="doxyComputerOutput">Id</span>.</p>

<p>Declaration at line 528 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/arglist-h">ArgList.h</a>, definition at line 252 of file <a href="/web-llvm/docs/api/files/lib/lib/option/arglist-cpp">ArgList.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/opt/option/#acc97061b780820c39cc4afd878aec21b">llvm::opt::Option::getName</a>, <a href="/web-llvm/docs/api/classes/llvm/opt/option/#a6604b3e1abb2089b8fb2e1880a92daa6">llvm::opt::Option::getPrefix</a> and <a href="#a678763a7949f037831ab90dcea55a817">MakeArgString</a>.</p>


<p>Referenced by <a href="#a3a30886094ab508b4a00828729da9d55">AddFlagArg</a>.</p>

</div>
</div>

### MakeJoinedArg {#a5893f33295c921df5928e5ab9feb90cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Arg * DerivedArgList::MakeJoinedArg (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/opt/arg">Arg</a> * BaseArg, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/opt/option">Option</a> Opt, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Value)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>MakeJoinedArg - Construct a new Positional arg for the given option <span class="doxyComputerOutput">Id</span>, with the provided <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a></span>.</p>

<p>Declaration at line 542 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/arglist-h">ArgList.h</a>, definition at line 277 of file <a href="/web-llvm/docs/api/files/lib/lib/option/arglist-cpp">ArgList.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/opt/option/#acc97061b780820c39cc4afd878aec21b">llvm::opt::Option::getName</a>, <a href="/web-llvm/docs/api/classes/llvm/opt/option/#a6604b3e1abb2089b8fb2e1880a92daa6">llvm::opt::Option::getPrefix</a>, <a href="#a678763a7949f037831ab90dcea55a817">MakeArgString</a> and <a href="/web-llvm/docs/api/classes/llvm/stringref/#a5db9240c74644c67759dd0f901fc3c7d">llvm::StringRef::size</a>.</p>


<p>Referenced by <a href="#a07d2e877f7b7ac9f51686c52df637170">AddJoinedArg</a>.</p>

</div>
</div>

### MakePositionalArg {#a909c2fa4bf18ec1dbe50a77adf3f48a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Arg * DerivedArgList::MakePositionalArg (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/opt/arg">Arg</a> * BaseArg, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/opt/option">Option</a> Opt, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Value)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>MakePositionalArg - Construct a new Positional arg for the given option <span class="doxyComputerOutput">Id</span>, with the provided <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a></span>.</p>

<p>Declaration at line 532 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/arglist-h">ArgList.h</a>, definition at line 259 of file <a href="/web-llvm/docs/api/files/lib/lib/option/arglist-cpp">ArgList.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/opt/option/#acc97061b780820c39cc4afd878aec21b">llvm::opt::Option::getName</a>, <a href="/web-llvm/docs/api/classes/llvm/opt/option/#a6604b3e1abb2089b8fb2e1880a92daa6">llvm::opt::Option::getPrefix</a> and <a href="#a678763a7949f037831ab90dcea55a817">MakeArgString</a>.</p>


<p>Referenced by <a href="#a913fc3de04c49ef64ed77e50f0d5f7d9">AddPositionalArg</a>.</p>

</div>
</div>

### MakeSeparateArg {#a2afff7edd330e44f3f1814a6e364c081}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Arg * DerivedArgList::MakeSeparateArg (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/opt/arg">Arg</a> * BaseArg, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/opt/option">Option</a> Opt, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Value)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>MakeSeparateArg - Construct a new Positional arg for the given option <span class="doxyComputerOutput">Id</span>, with the provided <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a></span>.</p>

<p>Declaration at line 537 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/arglist-h">ArgList.h</a>, definition at line 268 of file <a href="/web-llvm/docs/api/files/lib/lib/option/arglist-cpp">ArgList.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/opt/option/#acc97061b780820c39cc4afd878aec21b">llvm::opt::Option::getName</a>, <a href="/web-llvm/docs/api/classes/llvm/opt/option/#a6604b3e1abb2089b8fb2e1880a92daa6">llvm::opt::Option::getPrefix</a> and <a href="#a678763a7949f037831ab90dcea55a817">MakeArgString</a>.</p>


<p>Referenced by <a href="#aca09243bbb137b7edf07ad9b20181bf4">AddSeparateArg</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/arglist-h">ArgList.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/option/arglist-cpp">ArgList.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>

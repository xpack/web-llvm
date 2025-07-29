---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/riscvattributeparser
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `RISCVAttributeParser` Class



## Declaration

<div class="doxyDeclaration">
class llvm::RISCVAttributeParser { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/riscvattributeparser-h">llvm/Support/RISCVAttributeParser.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/elfattributeparser">ELFAttributeParser</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0fc87f311de36e8b0566898d44951ff0">RISCVAttributeParser</a> (ScopedPrinter *sw)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab8e18d04814ec8608af0c5e45746c2b4">RISCVAttributeParser</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ca6a9d79abe284cdd4a3304f8c53872">handler</a> (uint64_t tag, bool &amp;handled) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a85236f43f4066eb510e1759ddb5cc25c">unalignedAccess</a> (unsigned tag)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2b8579c040ad093eeae6919e8cdf372d">stackAlign</a> (unsigned tag)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e0e0f2d86c21f79b1bc84f9d31b4982">atomicAbi</a> (unsigned tag)</td>
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

## Private Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> DisplayHandler</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a633c3f7c630a3b40a66cfb8a151042b9">displayRoutines</a>[] = ...</td>
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


<p>Definition at line 16 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/riscvattributeparser-h">RISCVAttributeParser.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### RISCVAttributeParser() {#a0fc87f311de36e8b0566898d44951ff0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::RISCVAttributeParser::RISCVAttributeParser (<a href="/web-llvm/docs/api/classes/llvm/scopedprinter">ScopedPrinter</a> * sw)</td>
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



<p>Definition at line 30 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/riscvattributeparser-h">RISCVAttributeParser.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/elfattributeparser/#a4e104d3bf9f32e68ed3dacf1c6092931">llvm::ELFAttributeParser::ELFAttributeParser</a> and <a href="/web-llvm/docs/api/classes/llvm/elfattributeparser/#a967d07f3cace8ee5af66bff6585e03e7">llvm::ELFAttributeParser::sw</a>.</p>

</div>
</div>

### RISCVAttributeParser() {#ab8e18d04814ec8608af0c5e45746c2b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::RISCVAttributeParser::RISCVAttributeParser ()</td>
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



<p>Definition at line 32 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/riscvattributeparser-h">RISCVAttributeParser.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/elfattributeparser/#a4e104d3bf9f32e68ed3dacf1c6092931">llvm::ELFAttributeParser::ELFAttributeParser</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### atomicAbi() {#a6e0e0f2d86c21f79b1bc84f9d31b4982}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error RISCVAttributeParser::atomicAbi (unsigned tag)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 27 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/riscvattributeparser-h">RISCVAttributeParser.h</a>, definition at line 46 of file <a href="/web-llvm/docs/api/files/lib/lib/support/riscvattributeparser-cpp">RISCVAttributeParser.cpp</a>.</p>

</div>
</div>

### handler() {#a8ca6a9d79abe284cdd4a3304f8c53872}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error RISCVAttributeParser::handler (uint64_t tag, bool &amp; handled)</td>
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



<p>Declaration at line 23 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/riscvattributeparser-h">RISCVAttributeParser.h</a>, definition at line 66 of file <a href="/web-llvm/docs/api/files/lib/lib/support/riscvattributeparser-cpp">RISCVAttributeParser.cpp</a>.</p>

</div>
</div>

### stackAlign() {#a2b8579c040ad093eeae6919e8cdf372d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error RISCVAttributeParser::stackAlign (unsigned tag)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 26 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/riscvattributeparser-h">RISCVAttributeParser.h</a>, definition at line 58 of file <a href="/web-llvm/docs/api/files/lib/lib/support/riscvattributeparser-cpp">RISCVAttributeParser.cpp</a>.</p>

</div>
</div>

### unalignedAccess() {#a85236f43f4066eb510e1759ddb5cc25c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error RISCVAttributeParser::unalignedAccess (unsigned tag)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 25 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/riscvattributeparser-h">RISCVAttributeParser.h</a>, definition at line 52 of file <a href="/web-llvm/docs/api/files/lib/lib/support/riscvattributeparser-cpp">RISCVAttributeParser.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Attributes

### displayRoutines {#a633c3f7c630a3b40a66cfb8a151042b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const RISCVAttributeParser::DisplayHandler RISCVAttributeParser::displayRoutines</td>
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



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= {
        {
            <a href="/web-llvm/docs/api/namespaces/llvm/riscvattrs/#ac0e6d65dbd5acd98356e49a2ea9c4e72a0100b4efc71f09c9d6a16d6f32ff9daa">RISCVAttrs::ARCH</a>,
            &amp;<a href="/web-llvm/docs/api/classes/llvm/elfattributeparser/#a8125ecaffe4cb18a746e29ec30bc74c5">ELFAttributeParser::stringAttribute</a>,
        },
        {
            <a href="/web-llvm/docs/api/namespaces/llvm/riscvattrs/#ac0e6d65dbd5acd98356e49a2ea9c4e72a8f3410f163016d35c79393fb044ed47b">RISCVAttrs::PRIV_SPEC</a>,
            &amp;<a href="/web-llvm/docs/api/classes/llvm/elfattributeparser/#a3e050c88f97b0583ca8a9ccb9df7f9af">ELFAttributeParser::integerAttribute</a>,
        },
        {
            <a href="/web-llvm/docs/api/namespaces/llvm/riscvattrs/#ac0e6d65dbd5acd98356e49a2ea9c4e72a042be5b3857670a0e3e0dace53a79601">RISCVAttrs::PRIV_SPEC_MINOR</a>,
            &amp;<a href="/web-llvm/docs/api/classes/llvm/elfattributeparser/#a3e050c88f97b0583ca8a9ccb9df7f9af">ELFAttributeParser::integerAttribute</a>,
        },
        {
            <a href="/web-llvm/docs/api/namespaces/llvm/riscvattrs/#ac0e6d65dbd5acd98356e49a2ea9c4e72af86ac73473544636443d9eb261b81911">RISCVAttrs::PRIV_SPEC_REVISION</a>,
            &amp;<a href="/web-llvm/docs/api/classes/llvm/elfattributeparser/#a3e050c88f97b0583ca8a9ccb9df7f9af">ELFAttributeParser::integerAttribute</a>,
        },
        {
            <a href="/web-llvm/docs/api/namespaces/llvm/riscvattrs/#ac0e6d65dbd5acd98356e49a2ea9c4e72a35adc9b32c5d6aafb557089b94f65405">RISCVAttrs::STACK_ALIGN</a>,
            &amp;RISCVAttributeParser::stackAlign,
        },
        {
            <a href="/web-llvm/docs/api/namespaces/llvm/riscvattrs/#ac0e6d65dbd5acd98356e49a2ea9c4e72ace72d01296c55f4885fbdefb87892871">RISCVAttrs::UNALIGNED_ACCESS</a>,
            &amp;RISCVAttributeParser::unalignedAccess,
        },
        {
            <a href="/web-llvm/docs/api/namespaces/llvm/riscvattrs/#ac0e6d65dbd5acd98356e49a2ea9c4e72a4794d2bd27775559be203df4503d3880">RISCVAttrs::ATOMIC_ABI</a>,
            &amp;RISCVAttributeParser::atomicAbi,
        },
}
</div>
</dd>
</dl>

<p>Definition at line 21 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/riscvattributeparser-h">RISCVAttributeParser.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/riscvattributeparser-h">RISCVAttributeParser.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/support/riscvattributeparser-cpp">RISCVAttributeParser.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>

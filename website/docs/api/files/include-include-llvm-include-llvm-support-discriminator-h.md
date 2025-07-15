---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/include/include/llvm/include/llvm/support/discriminator-h
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `Discriminator.h` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/error-h">llvm/Support/Error.h</a>"
#include &lt;assert.h&gt;
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm">llvm</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is an optimization pass for GlobalISel generic memory operations. <a href="/web-llvm/docs/api/namespaces/llvm/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/sampleprof">sampleprof</a></td>
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

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b7e579d8a9b891cdd4642852930d800">getPrefixEncodingFromUnsigned</a> (unsigned U)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>With a given unsigned int <span class="doxyComputerOutput">U</span>, use up to 13 bits to represent it. <a href="#a3b7e579d8a9b891cdd4642852930d800">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afcbeec35a76bf40fd2f359887365d593">getUnsignedFromPrefixEncoding</a> (unsigned U)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Reverse transformation as getPrefixEncodingFromUnsigned. <a href="#afcbeec35a76bf40fd2f359887365d593">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aae8162a5c7f4095424c29f4022786702">getNextComponentInDiscriminator</a> (unsigned D)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the next component stored in discriminator. <a href="#aae8162a5c7f4095424c29f4022786702">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaa01067fc8646aefc70f8e0d37abec00">encodeComponent</a> (unsigned C)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4e7d93c6d2b31e7fb8fae321702b88f7">encodingBits</a> (unsigned C)</td>
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


<div class="doxySectionDef">

## Functions

### encodeComponent() {#aaa01067fc8646aefc70f8e0d37abec00}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned encodeComponent (unsigned C)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 45 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/discriminator-h">Discriminator.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a1960c14773241d6a238d2db593abe552">C</a> and <a href="#a3b7e579d8a9b891cdd4642852930d800">getPrefixEncodingFromUnsigned</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dilocation/#a6878171e0bb76ddb464e30b5bad4952f">llvm::DILocation::encodeDiscriminator</a>.</p>

</div>
</div>

### encodingBits() {#a4e7d93c6d2b31e7fb8fae321702b88f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned encodingBits (unsigned C)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/discriminator-h">Discriminator.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a1960c14773241d6a238d2db593abe552">C</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dilocation/#a6878171e0bb76ddb464e30b5bad4952f">llvm::DILocation::encodeDiscriminator</a>.</p>

</div>
</div>

### getNextComponentInDiscriminator() {#aae8162a5c7f4095424c29f4022786702}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned getNextComponentInDiscriminator (unsigned D)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the next component stored in discriminator.</p>

<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/discriminator-h">Discriminator.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a6a9f043784cf87001c84980afa76da82">D</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dilocation/#a71afd3d2ac28f17a123c7a5e37822659">llvm::DILocation::decodeDiscriminator</a>, <a href="/web-llvm/docs/api/classes/llvm/dilocation/#abc03af4abcfe8d196600e2842ff416e6">llvm::DILocation::getCopyIdentifierFromDiscriminator</a> and <a href="/web-llvm/docs/api/classes/llvm/dilocation/#a19bf03e247a0e281b5f8179dc18fdb7f">llvm::DILocation::getDuplicationFactorFromDiscriminator</a>.</p>

</div>
</div>

### getPrefixEncodingFromUnsigned() {#a3b7e579d8a9b891cdd4642852930d800}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned getPrefixEncodingFromUnsigned (unsigned U)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>With a given unsigned int <span class="doxyComputerOutput">U</span>, use up to 13 bits to represent it.</p>


<p>old_bit 1~5 --&gt; new_bit 1~5 old_bit 6~12 --&gt; new_bit 7~13 new_bit_6 is 0 if higher bits (7~13) are all 0</p>


<p>Definition at line 24 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/discriminator-h">Discriminator.h</a>.</p>


<p>Referenced by <a href="#aaa01067fc8646aefc70f8e0d37abec00">encodeComponent</a>.</p>

</div>
</div>

### getUnsignedFromPrefixEncoding() {#afcbeec35a76bf40fd2f359887365d593}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned getUnsignedFromPrefixEncoding (unsigned U)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Reverse transformation as getPrefixEncodingFromUnsigned.</p>

<p>Definition at line 30 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/discriminator-h">Discriminator.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dilocation/#a71afd3d2ac28f17a123c7a5e37822659">llvm::DILocation::decodeDiscriminator</a>, <a href="/web-llvm/docs/api/classes/llvm/dilocation/#a98203aeac2bf8055f829ba0203e77665">llvm::DILocation::getBaseDiscriminatorFromDiscriminator</a>, <a href="/web-llvm/docs/api/classes/llvm/dilocation/#abc03af4abcfe8d196600e2842ff416e6">llvm::DILocation::getCopyIdentifierFromDiscriminator</a> and <a href="/web-llvm/docs/api/classes/llvm/dilocation/#a19bf03e247a0e281b5f8179dc18fdb7f">llvm::DILocation::getDuplicationFactorFromDiscriminator</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>

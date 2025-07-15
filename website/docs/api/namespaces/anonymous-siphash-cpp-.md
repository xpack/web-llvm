---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/anonymous-siphash-cpp-
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# The `anonymous{SipHash.cpp}` Namespace Reference



## Definition

<div class="doxyDefinition">
namespace anonymous{SipHash.cpp} { ... }
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;int cROUNDS, int dROUNDS, size_t outlen&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a159cdb1934bd81019941f78b393b0f0c">siphash</a> (const unsigned char *in, uint64_t inlen, const unsigned char(&amp;k)[16], unsigned char(&amp;out)[outlen])</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Computes a SipHash value. <a href="#a159cdb1934bd81019941f78b393b0f0c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<div class="doxySectionDef">

## Functions

### siphash() {#a159cdb1934bd81019941f78b393b0f0c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;int cROUNDS, int dROUNDS, size_t outlen&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{SipHash.cpp}::siphash (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned char * in, uint64_t inlen, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned char(&amp;) k=[16], unsigned char(&amp;) out=[outlen])</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Computes a SipHash value.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">in</td>
<td class="doxyParamItemDescription"><p>pointer to input data (read-only)</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">inlen</td>
<td class="doxyParamItemDescription"><p>input data length in bytes (any size_t value)</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">k</td>
<td class="doxyParamItemDescription"><p>reference to the key data 16-byte array (read-only)</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>output data, must be 8 or 16 bytes</p></dd>
</dl>


<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/lib/lib/support/siphash-cpp">SipHash.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#a9579881de06b1560d242d15171ca1b86">LLVM_FALLTHROUGH</a>, <a href="/web-llvm/docs/api/namespaces/llvm/support/endian/#a0fa2f859066acd16820ab083040158c9">llvm::support::endian::read64le</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/siphash-cpp/#abd545ba6d36990ee5903ff4d0e6edecf">SIPROUND</a> and <a href="/web-llvm/docs/api/namespaces/llvm/support/endian/#a46eee35129898d0466b2af97eacb19ee">llvm::support::endian::write64le</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#abc54d0205758f7b576ea87bd3ba70a5e">llvm::getSipHash_2_4_128</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a155c6d528429c339eb352bfe2a715fe7">llvm::getSipHash_2_4_64</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/support/siphash-cpp">SipHash.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>

---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/support/sha256-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `SHA256.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/sha256-h">llvm/Support/SHA256.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/arrayref-h">llvm/ADT/ArrayRef.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">llvm/ADT/StringRef.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/endian-h">llvm/Support/Endian.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/swapbyteorder-h">llvm/Support/SwapByteOrder.h</a>"
#include &lt;string.h&gt;
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

</table>

## Macro Definitions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a58cc3bd202b2a9a9f001602787d09191">SHR</a>(x, c)&nbsp;&nbsp;&nbsp;((x) &gt;&gt; (c))</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a47a06d6e229d50d2b1a326ec58123cae">ROTR</a>(x, n)&nbsp;&nbsp;&nbsp;(((x) &gt;&gt; n) | ((x) &lt;&lt; (32 - (n))))</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0ed6c9c714485592a8c317a8ad91c83b">CH</a>(x, y, z)&nbsp;&nbsp;&nbsp;(((x) &amp; (y)) ^ (~(x) &amp; (z)))</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae2f6c7a0b4fdb15387259356b16854c9">MAJ</a>(x, y, z)&nbsp;&nbsp;&nbsp;(((x) &amp; (y)) ^ ((x) &amp; (z)) ^ ((y) &amp; (z)))</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af6f8ea907d6e1eaf7212b320a684359c">SIGMA_0</a>(x)&nbsp;&nbsp;&nbsp;(<a href="#a47a06d6e229d50d2b1a326ec58123cae">ROTR</a>(x, 2) ^ <a href="#a47a06d6e229d50d2b1a326ec58123cae">ROTR</a>(x, 13) ^ <a href="#a47a06d6e229d50d2b1a326ec58123cae">ROTR</a>(x, 22))</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acca956ff58d18f854f26d73596c623b4">SIGMA_1</a>(x)&nbsp;&nbsp;&nbsp;(<a href="#a47a06d6e229d50d2b1a326ec58123cae">ROTR</a>(x, 6) ^ <a href="#a47a06d6e229d50d2b1a326ec58123cae">ROTR</a>(x, 11) ^ <a href="#a47a06d6e229d50d2b1a326ec58123cae">ROTR</a>(x, 25))</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad5ff5b580b47983582c354c7e8163df5">SIGMA_2</a>(x)&nbsp;&nbsp;&nbsp;(<a href="#a47a06d6e229d50d2b1a326ec58123cae">ROTR</a>(x, 17) ^ <a href="#a47a06d6e229d50d2b1a326ec58123cae">ROTR</a>(x, 19) ^ <a href="#a58cc3bd202b2a9a9f001602787d09191">SHR</a>(x, 10))</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4e0f165b74fc52c8677ac5bbac7dafc3">SIGMA_3</a>(x)&nbsp;&nbsp;&nbsp;(<a href="#a47a06d6e229d50d2b1a326ec58123cae">ROTR</a>(x, 7) ^ <a href="#a47a06d6e229d50d2b1a326ec58123cae">ROTR</a>(x, 18) ^ <a href="#a58cc3bd202b2a9a9f001602787d09191">SHR</a>(x, 3))</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4ff15a4a16b6a2663501deff5875442a">F_EXPAND</a>(A, B, C, D, E, F, G, H, M1, M2, M3, M4, k)&nbsp;&nbsp;&nbsp;...</td>
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

## Macro Definitions

### CH {#a0ed6c9c714485592a8c317a8ad91c83b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CH(x, y, z)&nbsp;&nbsp;&nbsp;(((x) &amp; (y)) ^ (~(x) &amp; (z)))</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 34 of file <a href="/web-llvm/docs/api/files/lib/lib/support/sha256-cpp">SHA256.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a27b344a283e0620f484144889fe32064">llvm::getX86SubSuperRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a5552c2fa1505412508e493149af31543">llvm::AMDGPULegalizerInfo::legalizeFExp</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a39adc1637ddc1df880ec4ab13529879e">llvm::AMDGPULegalizerInfo::legalizeFlogCommon</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a8b4d189fb624411d2c3e6d460da3796f">llvm::AMDGPUTargetLowering::lowerFEXP</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a984d43e3f7d19822c71c5dac6a9dd650">llvm::AMDGPUTargetLowering::LowerFLOGCommon</a> and <a href="/web-llvm/docs/api/classes/llvm/hexagondagtodagisel/#ac57730efce0c1f82628bcdeb5ae42ce9">llvm::HexagonDAGToDAGISel::SelectFrameIndex</a>.</p>

</div>
</div>

### F\_EXPAND {#a4ff15a4a16b6a2663501deff5875442a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define F_EXPAND(A, B, C, D, E, F, G, H, M1, M2, M3, M4, k)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  do {                                                                         \
    <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ae42219072d798876e6b08e6b78614ff6">H</a> += <a href="#acca956ff58d18f854f26d73596c623b4">SIGMA_1</a>(<a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>) + <a href="#a0ed6c9c714485592a8c317a8ad91c83b">CH</a>(<a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ad96b7cf3182ce2ba85e5a7a93b12c441">G</a>) + M1 + k;                                    \
    <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a6a9f043784cf87001c84980afa76da82">D</a> += <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ae42219072d798876e6b08e6b78614ff6">H</a>;                                                                    \
    <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ae42219072d798876e6b08e6b78614ff6">H</a> += <a href="#af6f8ea907d6e1eaf7212b320a684359c">SIGMA_0</a>(<a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>) + <a href="#ae2f6c7a0b4fdb15387259356b16854c9">MAJ</a>(<a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a1960c14773241d6a238d2db593abe552">C</a>);                                            \
    M1 += <a href="#ad5ff5b580b47983582c354c7e8163df5">SIGMA_2</a>(M2) + M3 + <a href="#a4e0f165b74fc52c8677ac5bbac7dafc3">SIGMA_3</a>(M4);                                      \
  } <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp/#a503c0214540e80733c0a0c53c067e6ee">while</a> (0);
</div>
</dd>
</dl>

<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/lib/lib/support/sha256-cpp">SHA256.cpp</a>.</p>

</div>
</div>

### MAJ {#ae2f6c7a0b4fdb15387259356b16854c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MAJ(x, y, z)&nbsp;&nbsp;&nbsp;(((x) &amp; (y)) ^ ((x) &amp; (z)) ^ ((y) &amp; (z)))</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/lib/lib/support/sha256-cpp">SHA256.cpp</a>.</p>

</div>
</div>

### ROTR {#a47a06d6e229d50d2b1a326ec58123cae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define ROTR(x, n)&nbsp;&nbsp;&nbsp;(((x) &gt;&gt; n) | ((x) &lt;&lt; (32 - (n))))</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 32 of file <a href="/web-llvm/docs/api/files/lib/lib/support/sha256-cpp">SHA256.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a773a46997cf1652b37f46af4c5cb598a">getRISCVVLOp</a>.</p>

</div>
</div>

### SHR {#a58cc3bd202b2a9a9f001602787d09191}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define SHR(x, c)&nbsp;&nbsp;&nbsp;((x) &gt;&gt; (c))</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 31 of file <a href="/web-llvm/docs/api/files/lib/lib/support/sha256-cpp">SHA256.cpp</a>.</p>

</div>
</div>

### SIGMA\_0 {#af6f8ea907d6e1eaf7212b320a684359c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define SIGMA_0(x)&nbsp;&nbsp;&nbsp;(<a href="#a47a06d6e229d50d2b1a326ec58123cae">ROTR</a>(x, 2) ^ <a href="#a47a06d6e229d50d2b1a326ec58123cae">ROTR</a>(x, 13) ^ <a href="#a47a06d6e229d50d2b1a326ec58123cae">ROTR</a>(x, 22))</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/lib/lib/support/sha256-cpp">SHA256.cpp</a>.</p>

</div>
</div>

### SIGMA\_1 {#acca956ff58d18f854f26d73596c623b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define SIGMA_1(x)&nbsp;&nbsp;&nbsp;(<a href="#a47a06d6e229d50d2b1a326ec58123cae">ROTR</a>(x, 6) ^ <a href="#a47a06d6e229d50d2b1a326ec58123cae">ROTR</a>(x, 11) ^ <a href="#a47a06d6e229d50d2b1a326ec58123cae">ROTR</a>(x, 25))</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/lib/lib/support/sha256-cpp">SHA256.cpp</a>.</p>

</div>
</div>

### SIGMA\_2 {#ad5ff5b580b47983582c354c7e8163df5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define SIGMA_2(x)&nbsp;&nbsp;&nbsp;(<a href="#a47a06d6e229d50d2b1a326ec58123cae">ROTR</a>(x, 17) ^ <a href="#a47a06d6e229d50d2b1a326ec58123cae">ROTR</a>(x, 19) ^ <a href="#a58cc3bd202b2a9a9f001602787d09191">SHR</a>(x, 10))</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 40 of file <a href="/web-llvm/docs/api/files/lib/lib/support/sha256-cpp">SHA256.cpp</a>.</p>

</div>
</div>

### SIGMA\_3 {#a4e0f165b74fc52c8677ac5bbac7dafc3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define SIGMA_3(x)&nbsp;&nbsp;&nbsp;(<a href="#a47a06d6e229d50d2b1a326ec58123cae">ROTR</a>(x, 7) ^ <a href="#a47a06d6e229d50d2b1a326ec58123cae">ROTR</a>(x, 18) ^ <a href="#a58cc3bd202b2a9a9f001602787d09191">SHR</a>(x, 3))</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 41 of file <a href="/web-llvm/docs/api/files/lib/lib/support/sha256-cpp">SHA256.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>

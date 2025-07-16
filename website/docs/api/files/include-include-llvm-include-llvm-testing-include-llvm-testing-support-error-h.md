---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/include/include/llvm/include/llvm/testing/include/llvm/testing/support/error-h
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `Error.h` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/error-h">llvm/Support/Error.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/testing/include/llvm/testing/support/supporthelpers-h">llvm/Testing/Support/SupportHelpers.h</a>"
#include "gmock/gmock.h"
#include &lt;ostream&gt;
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/detail">detail</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>These are wrappers over isa* function that allow them to be used in generic algorithms such as <span class="doxyComputerOutput">llvm:all_of</span>, <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#a7dc3069afa2ce5ea62ac2eb183e51c00">llvm::none_of</a></span>, etc. <a href="/web-llvm/docs/api/namespaces/llvm/detail/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/detail/valuematchesmono">ValueMatchesMono&lt;T&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/detail/valuematchespoly">ValueMatchesPoly&lt;M&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/detail/errormatchesmono">ErrorMatchesMono&lt;InfoT&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/detail/errormessagematches">ErrorMessageMatches</a></td>
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

## Macro Definitions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aba4537291f20e29f5eb603d4aa06443c">EXPECT_THAT_ERROR</a>(Err, Matcher)&nbsp;&nbsp;&nbsp;  EXPECT_THAT(<a href="/web-llvm/docs/api/namespaces/llvm/detail/#ab8899a2137a4effece5b068526f6d367">llvm::detail::TakeError</a>(Err), Matcher)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad7bc2bc11b917a1bb417405835893a67">ASSERT_THAT_ERROR</a>(Err, Matcher)&nbsp;&nbsp;&nbsp;  ASSERT_THAT(<a href="/web-llvm/docs/api/namespaces/llvm/detail/#ab8899a2137a4effece5b068526f6d367">llvm::detail::TakeError</a>(Err), Matcher)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad7631d96a0e84d84b35d854fdc88fd6f">EXPECT_THAT_EXPECTED</a>(Err, Matcher)&nbsp;&nbsp;&nbsp;  EXPECT_THAT(<a href="/web-llvm/docs/api/namespaces/llvm/detail/#a1d244748c7af3178b4d806e32db0410e">llvm::detail::TakeExpected</a>(Err), Matcher)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper macro for checking the result of an 'Expected&lt;T&gt;'. <a href="#ad7631d96a0e84d84b35d854fdc88fd6f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae499a548f28c1b29799aa10a45e57198">ASSERT_THAT_EXPECTED</a>(Err, Matcher)&nbsp;&nbsp;&nbsp;  ASSERT_THAT(<a href="/web-llvm/docs/api/namespaces/llvm/detail/#a1d244748c7af3178b4d806e32db0410e">llvm::detail::TakeExpected</a>(Err), Matcher)</td>
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

### ASSERT\_THAT\_ERROR {#ad7bc2bc11b917a1bb417405835893a67}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define ASSERT_THAT_ERROR(Err, Matcher)&nbsp;&nbsp;&nbsp;  ASSERT_THAT(<a href="/web-llvm/docs/api/namespaces/llvm/detail/#ab8899a2137a4effece5b068526f6d367">llvm::detail::TakeError</a>(Err), Matcher)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 165 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/testing/include/llvm/testing/support/error-h">Error.h</a>.</p>

</div>
</div>

### ASSERT\_THAT\_EXPECTED {#ae499a548f28c1b29799aa10a45e57198}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define ASSERT_THAT_EXPECTED(Err, Matcher)&nbsp;&nbsp;&nbsp;  ASSERT_THAT(<a href="/web-llvm/docs/api/namespaces/llvm/detail/#a1d244748c7af3178b4d806e32db0410e">llvm::detail::TakeExpected</a>(Err), Matcher)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 191 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/testing/include/llvm/testing/support/error-h">Error.h</a>.</p>

</div>
</div>

### EXPECT\_THAT\_ERROR {#aba4537291f20e29f5eb603d4aa06443c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define EXPECT_THAT_ERROR(Err, Matcher)&nbsp;&nbsp;&nbsp;  EXPECT_THAT(<a href="/web-llvm/docs/api/namespaces/llvm/detail/#ab8899a2137a4effece5b068526f6d367">llvm::detail::TakeError</a>(Err), Matcher)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 163 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/testing/include/llvm/testing/support/error-h">Error.h</a>.</p>

</div>
</div>

### EXPECT\_THAT\_EXPECTED {#ad7631d96a0e84d84b35d854fdc88fd6f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define EXPECT_THAT_EXPECTED(Err, Matcher)&nbsp;&nbsp;&nbsp;  EXPECT_THAT(<a href="/web-llvm/docs/api/namespaces/llvm/detail/#a1d244748c7af3178b4d806e32db0410e">llvm::detail::TakeExpected</a>(Err), Matcher)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Helper macro for checking the result of an 'Expected&lt;T&gt;'.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">// function to be tested</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">Expected&lt;int&gt; myDivide(</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">TEST(myDivideTests, GoodAndBad) {</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// test good case</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// if you only care about success or failure:</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#ad7631d96a0e84d84b35d854fdc88fd6f">EXPECT_THAT_EXPECTED</a>(myDivide(10, 5), Succeeded());</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// if you also care about the value:</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#ad7631d96a0e84d84b35d854fdc88fd6f">EXPECT_THAT_EXPECTED</a>(myDivide(10, 5), <a href="/web-llvm/docs/api/namespaces/llvm/#a79e64ef30db46c5331dc31759ebd8b9d">HasValue</a>(2));</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// test the error case</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#ad7631d96a0e84d84b35d854fdc88fd6f">EXPECT_THAT_EXPECTED</a>(myDivide(10, 0), <a href="/web-llvm/docs/api/namespaces/llvm/#a2cd7b2e49608a96ba42f59f642cf99ac">Failed</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// also check the error message</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#ad7631d96a0e84d84b35d854fdc88fd6f">EXPECT_THAT_EXPECTED</a>(myDivide(10, 0),</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-llvm/docs/api/namespaces/llvm/#a78f561c62fccdd3391f0652104b6681e">FailedWithMessage</a>(</span><span class="doxyHighlightStringLiteral">"B must not be zero!"</span><span class="doxyHighlight">));</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Definition at line 189 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/testing/include/llvm/testing/support/error-h">Error.h</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>

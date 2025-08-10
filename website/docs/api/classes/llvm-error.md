---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/error
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `Error` Class

<p>Lightweight error class with error context and mandatory checking. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::Error { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/error-h">llvm/Support/Error.h</a>"
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/errorsuccess">ErrorSuccess</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Subclass of <a href="/web-llvm/docs/api/classes/llvm/error">Error</a> for the sole purpose of identifying the success path in the type system. <a href="/web-llvm/docs/api/classes/llvm/errorsuccess/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/msvcperror">MSVCPError</a></td>
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

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af9853a913f7c3209c5076a66ebdee623">ErrorList</a></td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a815f6718ecaf8321aab0587f5e62d048">Expected</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename... HandlerTs&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a2c831eabfe62504c9cc0cc16e0799c44">handleErrors</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a> the ErrorInfo(s) contained in E to their respective handlers. <a href="#a2c831eabfe62504c9cc0cc16e0799c44">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename HandlerT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac1eaa283b96012bf2a0f2e05d04a952a">visitErrors</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Visit all the ErrorInfo(s) contained in E by passing them to the respective handler, without consuming the error. <a href="#ac1eaa283b96012bf2a0f2e05d04a952a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcerror/#gad81d81a316ef38888533a24b786a6605">LLVMErrorRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e40e583eb28c707523333b0e2c51cf9">wrap</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Conversion from <a href="/web-llvm/docs/api/classes/llvm/error">Error</a> to <a href="/web-llvm/docs/api/groups/llvmcerror/#gad81d81a316ef38888533a24b786a6605">LLVMErrorRef</a> for C error bindings. <a href="#a6e40e583eb28c707523333b0e2c51cf9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a9b19d1d78ce18abbe61fa475c9632c">operator&lt;&lt;</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab4f20eb017c74ffdac91daf5b5068a73">Error</a> (const Error &amp;Other)=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1c1f5fe40e458b271781c97954d518b6">Error</a> (Error &amp;&amp;Other)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Move-construct an error value. <a href="#a1c1f5fe40e458b271781c97954d518b6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a56f3ef0d501ed9a50b5f18075d97ca8d">Error</a> (std::unique_ptr&lt; ErrorInfoBase &gt; Payload)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create an error value. <a href="#a56f3ef0d501ed9a50b5f18075d97ca8d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7245b97586de88539c5dc656b6e7f38d">Error</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a success value. Prefer using '<a href="#a4dfd0813c3d0e0a30439b5a3e9196b59">Error::success()</a>' for readability. <a href="#a7245b97586de88539c5dc656b6e7f38d">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a31787a05ac40b00e24901840ee2c2f80">~Error</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Destroy a <a href="/web-llvm/docs/api/classes/llvm/error">Error</a>. <a href="#a31787a05ac40b00e24901840ee2c2f80">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c4d13d802bccdfc5b40bb1a2447db3b">operator=</a> (const Error &amp;Other)=delete</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae6cd5f6ac32dc47c9437c7315fb79444">operator=</a> (Error &amp;&amp;Other)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Move-assign an error value. <a href="#ae6cd5f6ac32dc47c9437c7315fb79444">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a981b4992a3b7cce718c7995a7d6193a0">operator bool</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Bool conversion. <a href="#a981b4992a3b7cce718c7995a7d6193a0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ErrT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#afbfea2fa926cd1894c74b44c79c75601">isA</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> whether one error is a subclass of another. <a href="#afbfea2fa926cd1894c74b44c79c75601">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> void *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3de0b5962983ce2a4ba1d258add13090">dynamicClassID</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the dynamic class id of this error, or null if this is a success value. <a href="#a3de0b5962983ce2a4ba1d258add13090">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa587182fe95c98389cf0a1d3a7b36998">assertIsChecked</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/errorinfobase">ErrorInfoBase</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a46c59098bb197526d18717f7a93eb008">getPtr</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af107ef6b1e97c2e0380a1bbc672d568b">setPtr</a> (ErrorInfoBase *EI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad04083f4dad76660e9727f50161878a6">getChecked</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5242c3ddc39c53d2dcbc30e95595ea25">setChecked</a> (bool V)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/errorinfobase">ErrorInfoBase</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad5906b457c7dbaa3720a0af85ff202a0">takePayload</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/errorinfobase">ErrorInfoBase</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aedadb805d1044a5f5e6261f24aa7c26b">Payload</a> = nullptr</td>
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

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/errorsuccess">ErrorSuccess</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4dfd0813c3d0e0a30439b5a3e9196b59">success</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a success value. <a href="#a4dfd0813c3d0e0a30439b5a3e9196b59">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Lightweight error class with error context and mandatory checking.</p>


<p>Instances of this class wrap a <a href="/web-llvm/docs/api/classes/llvm/errorinfobase">ErrorInfoBase</a> pointer. Failure states are represented by setting the pointer to a <a href="/web-llvm/docs/api/classes/llvm/errorinfobase">ErrorInfoBase</a> subclass instance containing information describing the failure. Success is represented by a null pointer value.</p>


<p>Instances of <a href="/web-llvm/docs/api/classes/llvm/error">Error</a> also contains a 'Checked' flag, which must be set before the destructor is called, otherwise the destructor will trigger a runtime error. This enforces at runtime the requirement that all <a href="/web-llvm/docs/api/classes/llvm/error">Error</a> instances be checked or returned to the caller.</p>


<p>There are two ways to set the checked flag, depending on what state the <a href="/web-llvm/docs/api/classes/llvm/error">Error</a> instance is in. For <a href="/web-llvm/docs/api/classes/llvm/error">Error</a> instances indicating success, it is sufficient to invoke the boolean conversion operator. E.g.:</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#a7245b97586de88539c5dc656b6e7f38d">Error</a> foo(&lt;...&gt;);</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a> = foo(&lt;...&gt;))</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>; </span><span class="doxyHighlightComment">// &lt;- Return E if it is in the error state.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">// We have verified that E was in the success state. It can now be safely</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">// destroyed.</span></span></div>

</div>


<p>A success value <em>can not</em> be dropped. For example, just calling 'foo(&lt;...&gt;)' without testing the return value will raise a runtime error, even if foo returns success.</p>


<p>For <a href="/web-llvm/docs/api/classes/llvm/error">Error</a> instances representing failure, you must use either the handleErrors or handleAllErrors function with a typed handler. E.g.:</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">class </span><span class="doxyHighlight">MyErrorInfo : </span><span class="doxyHighlightKeyword">public</span><span class="doxyHighlight"> ErrorInfo&lt;MyErrorInfo&gt; {</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// Custom error info.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">};</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#a7245b97586de88539c5dc656b6e7f38d">Error</a> foo(&lt;...&gt;) { </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">make_error&lt;MyErrorInfo&gt;</a>(...); }</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a> = foo(&lt;...&gt;); </span><span class="doxyHighlightComment">// &lt;- foo returns failure with MyErrorInfo.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> NewE =</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a2c831eabfe62504c9cc0cc16e0799c44">handleErrors</a>(std::move(<a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>),</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">    [](</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> MyErrorInfo &amp;M) {</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// Deal with the error.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">    },</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">    [](std::unique_ptr&lt;OtherError&gt; <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ac2456158e5acb44477d8ecfa2d04dbdea69691c7bdcc3ce6d5d8a1361f22d04ac">M</a>) -&gt; <a href="#a7245b97586de88539c5dc656b6e7f38d">Error</a> {</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (canHandle(*M)) {</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightComment">// handle error.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a4dfd0813c3d0e0a30439b5a3e9196b59">Error::success</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// Couldn't handle this error instance. Pass it up the stack.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a7245b97586de88539c5dc656b6e7f38d">Error</a>(std::move(M));</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  });</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">// Note - The error passed to handleErrors will be marked as checked. If</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">// there is no matched handler, a new error with the same payload is</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">// created and returned.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">// The handlers take the error checked by handleErrors as an argument,</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">// which can be used to retrieve more information. If a new error is</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">// created by a handler, it will be passed back to the caller of</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">// handleErrors and needs to be checked or return up to the stack.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">// Otherwise, the passed-in error is considered consumed.</span></span></div>

</div>


<p>The handleAllErrors function is identical to handleErrors, except that it has a void return type, and requires all errors to be handled and no new errors be returned. It prevents errors (assuming they can all be handled) from having to be bubbled all the way to the top-level.</p>


<p><em>All</em> <a href="/web-llvm/docs/api/classes/llvm/error">Error</a> instances must be checked before destruction, even if they're moved-assigned or constructed from Success values that have already been checked. This enforces checking through all levels of the call stack.</p>


<p>Definition at line 160 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/error-h">Error.h</a>.</p>


<div class="doxySectionDef">

## Friends

### ErrorList {#af9853a913f7c3209c5076a66ebdee623}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/errorlist">ErrorList</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 164 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/error-h">Error.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="#a7245b97586de88539c5dc656b6e7f38d">Error</a>, <a href="#af9853a913f7c3209c5076a66ebdee623">ErrorList</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ae42219072d798876e6b08e6b78614ff6">H</a>, <a href="#a2c831eabfe62504c9cc0cc16e0799c44">handleErrors</a> and <a href="#ac1eaa283b96012bf2a0f2e05d04a952a">visitErrors</a>.</p>


<p>Referenced by <a href="#af9853a913f7c3209c5076a66ebdee623">ErrorList</a>, <a href="#a2c831eabfe62504c9cc0cc16e0799c44">handleErrors</a> and <a href="#ac1eaa283b96012bf2a0f2e05d04a952a">visitErrors</a>.</p>

</div>
</div>

### Expected {#a815f6718ecaf8321aab0587f5e62d048}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 175 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/error-h">Error.h</a>.</p>


<p>References <a href="#a7245b97586de88539c5dc656b6e7f38d">Error</a> and <a href="#a815f6718ecaf8321aab0587f5e62d048">Expected</a>.</p>


<p>Referenced by <a href="#a815f6718ecaf8321aab0587f5e62d048">Expected</a>.</p>

</div>
</div>

### handleErrors {#a2c831eabfe62504c9cc0cc16e0799c44}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend <a href="/web-llvm/docs/api/classes/llvm/error">Error</a> <a href="/web-llvm/docs/api/classes/llvm/error">Error</a> E, HandlerTs &amp;&amp;... Handlers</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a> the ErrorInfo(s) contained in E to their respective handlers.</p>


<p><a href="/web-llvm/docs/api/classes/llvm/any">Any</a> unhandled errors (or Errors returned by handlers) are re-concatenated and returned. Because this function returns an error, its result must also be checked or returned. If you intend to handle all errors use handleAllErrors (which returns void, and will abort() on unhandled errors) instead.</p>


<p>Definition at line 168 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/error-h">Error.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="#a7245b97586de88539c5dc656b6e7f38d">Error</a>, <a href="#af9853a913f7c3209c5076a66ebdee623">ErrorList</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a947e7b03cb74733f890911af749384c1">llvm::handleErrorImpl</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acefe92adee8725ad904c7c43649790e8a4ee29ca12c7d126654bd0e5275de6135">llvm::List</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a> and <a href="#a4dfd0813c3d0e0a30439b5a3e9196b59">success</a>.</p>


<p>Referenced by <a href="#af9853a913f7c3209c5076a66ebdee623">ErrorList</a>.</p>

</div>
</div>

### operator&lt;&lt; {#a4a9b19d1d78ce18abbe61fa475c9632c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/error">Error</a> &amp; E</td>
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


<p>Definition at line 321 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/error-h">Error.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="#a7245b97586de88539c5dc656b6e7f38d">Error</a> and <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>.</p>

</div>
</div>

### visitErrors {#ac1eaa283b96012bf2a0f2e05d04a952a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend void <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/error">Error</a> &amp; E, HandlerT H</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Visit all the ErrorInfo(s) contained in E by passing them to the respective handler, without consuming the error.</p>

<p>Definition at line 171 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/error-h">Error.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="#a7245b97586de88539c5dc656b6e7f38d">Error</a>, <a href="#af9853a913f7c3209c5076a66ebdee623">ErrorList</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ae42219072d798876e6b08e6b78614ff6">H</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acefe92adee8725ad904c7c43649790e8a4ee29ca12c7d126654bd0e5275de6135">llvm::List</a> and <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>.</p>


<p>Referenced by <a href="#af9853a913f7c3209c5076a66ebdee623">ErrorList</a>.</p>

</div>
</div>

### wrap {#a6e40e583eb28c707523333b0e2c51cf9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend <a href="/web-llvm/docs/api/groups/llvmcerror/#gad81d81a316ef38888533a24b786a6605">LLVMErrorRef</a> <a href="/web-llvm/docs/api/classes/llvm/error">Error</a> Err</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Conversion from <a href="/web-llvm/docs/api/classes/llvm/error">Error</a> to <a href="/web-llvm/docs/api/groups/llvmcerror/#gad81d81a316ef38888533a24b786a6605">LLVMErrorRef</a> for C error bindings.</p>

<p>Definition at line 178 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/error-h">Error.h</a>.</p>


<p>References <a href="#a7245b97586de88539c5dc656b6e7f38d">Error</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a650dea4533083a886cec9f16d80356d9a123fead50246387983ee340507115ef4">llvm::release</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### Error() {#ab4f20eb017c74ffdac91daf5b5068a73}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::Error::Error (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/error">Error</a> &amp; Other)</td>
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



<p>Definition at line 192 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/error-h">Error.h</a>.</p>


<p>References <a href="#a7245b97586de88539c5dc656b6e7f38d">Error</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>.</p>

</div>
</div>

### Error() {#a1c1f5fe40e458b271781c97954d518b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::Error::Error (<a href="/web-llvm/docs/api/classes/llvm/error">Error</a> &amp;&amp; Other)</td>
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

<p>Move-construct an error value.</p>


<p>The newly constructed error is considered unchecked, even if the source error had been checked. The original error becomes a checked Success value, regardless of its original state.</p>


<p>Definition at line 197 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/error-h">Error.h</a>.</p>


<p>References <a href="#a7245b97586de88539c5dc656b6e7f38d">Error</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>.</p>

</div>
</div>

### Error() {#a56f3ef0d501ed9a50b5f18075d97ca8d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::Error::Error (std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/errorinfobase">ErrorInfoBase</a> &gt; Payload)</td>
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

<p>Create an error value.</p>


<p>Prefer using the 'make_error' function, but this constructor can be useful when "re-throwing" errors from handlers.</p>


<p>Definition at line 204 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/error-h">Error.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Constructors

### Error() {#a7245b97586de88539c5dc656b6e7f38d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::Error::Error ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create a success value. Prefer using '<a href="#a4dfd0813c3d0e0a30439b5a3e9196b59">Error::success()</a>' for readability.</p>

<p>Definition at line 182 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/error-h">Error.h</a>.</p>


<p>Referenced by <a href="#ab4f20eb017c74ffdac91daf5b5068a73">Error</a>, <a href="#a1c1f5fe40e458b271781c97954d518b6">Error</a>, <a href="#af9853a913f7c3209c5076a66ebdee623">ErrorList</a>, <a href="#a815f6718ecaf8321aab0587f5e62d048">Expected</a>, <a href="#a2c831eabfe62504c9cc0cc16e0799c44">handleErrors</a>, <a href="/web-llvm/docs/api/classes/llvm/msvcperror/#aa90dbef4e33bed1d05154b9750e9cee4">llvm::MSVCPError::MSVCPError</a>, <a href="/web-llvm/docs/api/classes/llvm/msvcperror/#a03686b2b8bd16702f23a4a8b2e6668c6">llvm::MSVCPError::MSVCPError</a>, <a href="#a4a9b19d1d78ce18abbe61fa475c9632c">operator&lt;&lt;</a>, <a href="#a6c4d13d802bccdfc5b40bb1a2447db3b">operator=</a>, <a href="#ae6cd5f6ac32dc47c9437c7315fb79444">operator=</a>, <a href="#ac1eaa283b96012bf2a0f2e05d04a952a">visitErrors</a> and <a href="#a6e40e583eb28c707523333b0e2c51cf9">wrap</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~Error() {#a31787a05ac40b00e24901840ee2c2f80}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::Error::~Error ()</td>
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

<p>Destroy a <a href="/web-llvm/docs/api/classes/llvm/error">Error</a>.</p>


<p>Fails with a call to abort() if the error is unchecked.</p>


<p>Definition at line 233 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/error-h">Error.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp/#a3d9162ba919b64a3930354acc96f098b">getPtr</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator bool() {#a981b4992a3b7cce718c7995a7d6193a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::Error::operator bool ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel explicit">explicit</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Bool conversion.</p>


<p>Returns true if this <a href="/web-llvm/docs/api/classes/llvm/error">Error</a> is in a failure state, and false if it is in an accept state. If the error is in a Success state it will be considered checked.</p>


<p>Definition at line 241 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/error-h">Error.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp/#a3d9162ba919b64a3930354acc96f098b">getPtr</a>.</p>

</div>
</div>

### operator=() {#a6c4d13d802bccdfc5b40bb1a2447db3b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error &amp; llvm::Error::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/error">Error</a> &amp; Other)</td>
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



<p>Definition at line 210 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/error-h">Error.h</a>.</p>


<p>References <a href="#a7245b97586de88539c5dc656b6e7f38d">Error</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/msvcperror/#aee9eecd822372aa7d1973d76830dba69">llvm::MSVCPError::operator=</a>.</p>

</div>
</div>

### operator=() {#ae6cd5f6ac32dc47c9437c7315fb79444}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error &amp; llvm::Error::operator= (<a href="/web-llvm/docs/api/classes/llvm/error">Error</a> &amp;&amp; Other)</td>
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

<p>Move-assign an error value.</p>


<p>The current error must represent success, you you cannot overwrite an unhandled error. The current error is then considered unchecked. The source error becomes a checked success value, regardless of its original state.</p>


<p>Definition at line 216 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/error-h">Error.h</a>.</p>


<p>References <a href="#a7245b97586de88539c5dc656b6e7f38d">Error</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### dynamicClassID() {#a3de0b5962983ce2a4ba1d258add13090}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const void * llvm::Error::dynamicClassID ()</td>
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

<p>Returns the dynamic class id of this error, or null if this is a success value.</p>

<p>Definition at line 253 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/error-h">Error.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp/#a3d9162ba919b64a3930354acc96f098b">getPtr</a>.</p>

</div>
</div>

### isA() {#afbfea2fa926cd1894c74b44c79c75601}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ErrT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Error::isA ()</td>
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

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> whether one error is a subclass of another.</p>

<p>Definition at line 247 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/error-h">Error.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp/#a3d9162ba919b64a3930354acc96f098b">getPtr</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### assertIsChecked() {#aa587182fe95c98389cf0a1d3a7b36998}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::Error::assertIsChecked ()</td>
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



<p>Definition at line 269 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/error-h">Error.h</a>.</p>

</div>
</div>

### getChecked() {#ad04083f4dad76660e9727f50161878a6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Error::getChecked ()</td>
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



<p>Definition at line 297 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/error-h">Error.h</a>.</p>

</div>
</div>

### getPtr() {#a46c59098bb197526d18717f7a93eb008}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ErrorInfoBase * llvm::Error::getPtr ()</td>
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



<p>Definition at line 276 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/error-h">Error.h</a>.</p>

</div>
</div>

### setChecked() {#a5242c3ddc39c53d2dcbc30e95595ea25}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::Error::setChecked (bool V)</td>
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



<p>Definition at line 305 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/error-h">Error.h</a>.</p>

</div>
</div>

### setPtr() {#af107ef6b1e97c2e0380a1bbc672d568b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::Error::setPtr (<a href="/web-llvm/docs/api/classes/llvm/errorinfobase">ErrorInfoBase</a> * EI)</td>
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



<p>Definition at line 286 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/error-h">Error.h</a>.</p>

</div>
</div>

### takePayload() {#ad5906b457c7dbaa3720a0af85ff202a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; ErrorInfoBase &gt; llvm::Error::takePayload ()</td>
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



<p>Definition at line 314 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/error-h">Error.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Payload {#aedadb805d1044a5f5e6261f24aa7c26b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ErrorInfoBase* llvm::Error::Payload = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 329 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/error-h">Error.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### success() {#a4dfd0813c3d0e0a30439b5a3e9196b59}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ErrorSuccess llvm::Error::success ()</td>
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

<p>Create a success value.</p>

<p>Definition at line 189 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/error-h">Error.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/jitlink/inprocessmemorymanager/ipinflightalloc/#a2306347d88aa77c28391f5ab7c0585f1">llvm::jitlink::InProcessMemoryManager::IPInFlightAlloc::abandon</a>, <a href="/web-llvm/docs/api/structs/llvm/overlapstats/#a1cc444c0141edfa6f0c92e71fa3d3dda">llvm::OverlapStats::accumulateCounts</a>, <a href="/web-llvm/docs/api/classes/llvm/lto/lto/#a0c3e8ed752bc7ef92ccb9edbd4bb014a">llvm::lto::LTO::add</a>, <a href="/web-llvm/docs/api/files/lib/lib/dwp/dwp-cpp/#af2db0d7fc3c09fcac8bfcc6bc3cdbd6c">addAllTypesFromDWP</a>, <a href="/web-llvm/docs/api/files/lib/lib/dwp/dwp-cpp/#a82237aa799c6a24c6bc9f95c01b137d4">addAllTypesFromTypesSection</a>, <a href="/web-llvm/docs/api/classes/llvm/jitlink/blockaddressmap/#a55383a369fc986bc7aa0d44c6aad2f86">llvm::jitlink::BlockAddressMap::addBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/xray/profile/#a90e702657e9bd42c6b4c4d1e79194ea4">llvm::xray::Profile::addBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/jitlink/blockaddressmap/#ac48cc8d59366ca40f92ef164d393f969">llvm::jitlink::BlockAddressMap::addBlocks</a>, <a href="/web-llvm/docs/api/classes/llvm/codegenpassbuilder/#a6def3ee2976adc8630894b508c7c7402">llvm::CodeGenPassBuilder&lt; DerivedT, TargetMachineT &gt;::addCoreISelPasses</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/dbistreambuilder/#ab0e928a8582cc80c0c1a801fbafe5e3f">llvm::pdb::DbiStreamBuilder::addDbgStream</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/synthetictypenamebuilder/#ac0f5b717fb77c6c02c668e29b9764c9e">llvm::dwarf_linker::parallel::SyntheticTypeNameBuilder::addDIETypeName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a86c56f594b268ffb1f273fc4bc0f140b">llvm::orc::addFunctionPointerRelocationsToCurrentSymbol</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcopy/coff/#ac26907ff1b30d1236b06e5880af523d2">llvm::objcopy::coff::addGnuDebugLink</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86codegenpassbuilder-cpp-/x86codegenpassbuilder/#abe84e25a51bebfa491736b36531c077a">anonymous{X86CodeGenPassBuilder.cpp}::X86CodeGenPassBuilder::addInstSelector</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpucodegenpassbuilder/#a16180e143d7be2ba583e5d9903361415">llvm::AMDGPUCodeGenPassBuilder::addInstSelector</a>, <a href="/web-llvm/docs/api/classes/llvm/r600codegenpassbuilder/#af02d63f3a8a5bf73ae45123521411860">llvm::R600CodeGenPassBuilder::addInstSelector</a>, <a href="/web-llvm/docs/api/classes/llvm/codegenpassbuilder/#aa3cda6e4a4f17e5759b544a4c7ec494c">llvm::CodeGenPassBuilder&lt; DerivedT, TargetMachineT &gt;::addMachinePasses</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/namematcher/#aec79fe06f3234497d78f290c50389b2f">llvm::objcopy::NameMatcher::addMatcher</a>, <a href="/web-llvm/docs/api/structs/anonymous-irsymtab-cpp-/builder/#a9e5d9d56a410f0bd58fa931731c9e644">anonymous{IRSymtab.cpp}::Builder::addModule</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/dbistreambuilder/#a2eefa19d8b34f07195f45aa3d8fee72a">llvm::pdb::DbiStreamBuilder::addModuleSourceFile</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/pdbfilebuilder/#a3bdb84d5b8360c8bf563aeea45a6e2e7">llvm::pdb::PDBFileBuilder::addNamedStream</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/object/#af0b046931b74ef054f7290e9ec6b64d7">llvm::objcopy::elf::Object::addNewSymbolTable</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/synthetictypenamebuilder/#a461535e36ca5b8a26e8fb2901a23941d">llvm::dwarf_linker::parallel::SyntheticTypeNameBuilder::addParamNames</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/synthetictypenamebuilder/#a1ead8e73f45a8c9a08f8ae11d89cfecb">llvm::dwarf_linker::parallel::SyntheticTypeNameBuilder::addParentName</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/synthetictypenamebuilder/#a0186dfd0c814155d8e6a9cab1969afdd">llvm::dwarf_linker::parallel::SyntheticTypeNameBuilder::addReferencedODRDies</a>, <a href="/web-llvm/docs/api/classes/llvm/codegenpassbuilder/#a1e77277704de3f76249f730ee55dc7b9">llvm::CodeGenPassBuilder&lt; DerivedT, TargetMachineT &gt;::addRegAssignmentFast</a>, <a href="/web-llvm/docs/api/classes/llvm/codegenpassbuilder/#a9b736691b65c34ed04d495d4e1166a39">llvm::CodeGenPassBuilder&lt; DerivedT, TargetMachineT &gt;::addRegAssignmentOptimized</a>, <a href="/web-llvm/docs/api/structs/llvm/lto/config/#a4395f06e55f4b727fe0b685074821644">llvm::lto::Config::addSaveTemps</a>, <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machoobjcopy-cpp/#aa6138676e4615546fc1c7d559029916a">addSection</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/synthetictypenamebuilder/#a3fa9676347c5ae75e905430f8e0897ea">llvm::dwarf_linker::parallel::SyntheticTypeNameBuilder::addSignature</a>, <a href="/web-llvm/docs/api/structs/anonymous-irsymtab-cpp-/builder/#a15ad3b408efc55e12e201e1cd1dfbc45">anonymous{IRSymtab.cpp}::Builder::addSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/instrprofsymtab/#a161861cead69eb257424d8e90d9bf26d">llvm::InstrProfSymtab::addSymbolName</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/synthetictypenamebuilder/#a086f090ebea74999eafa96dc69047a67">llvm::dwarf_linker::parallel::SyntheticTypeNameBuilder::addTemplateParamNames</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/synthetictypenamebuilder/#ae03fdc522b86805416485b83c76a27a3">llvm::dwarf_linker::parallel::SyntheticTypeNameBuilder::addTypeName</a>, <a href="/web-llvm/docs/api/classes/llvm/instrprofsymtab/#a6e42074180a160835f3222c6d6017fc1">llvm::InstrProfSymtab::addVTableName</a>, <a href="/web-llvm/docs/api/files/lib/lib/remarks/bitstreamremarkparser-cpp/#ae7a2a8c8926efbbd98b5e02b989d58bf">advanceToMetaBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/bitcodeanalyzer/#add391ff06a593c4b9cb8f05b23882a51">llvm::BitcodeAnalyzer::analyze</a>, <a href="/web-llvm/docs/api/files/lib/lib/tooldrivers/lib/tooldrivers/llvm-lib/libdriver-cpp/#ac22ea488f955382d30003c56202ef80d">appendFile</a>, <a href="/web-llvm/docs/api/classes/llvm/errorhandlertraits-9048b7cee5a4d973c6ab34be30e7b40d/#ab4dec53d31a55e5d06dd4c31e4149122">llvm::ErrorHandlerTraits&lt; void(&amp;)(ErrT &amp;)&gt;::apply</a>, <a href="/web-llvm/docs/api/classes/llvm/errorhandlertraits-7d948b2e862b83e2e5f4752fd75d3082/#a9695146c2a8b2f6d1581688a828504d8">llvm::ErrorHandlerTraits&lt; void(&amp;)(std::unique_ptr&lt; ErrT &gt;)&gt;::apply</a>, <a href="/web-llvm/docs/api/classes/llvm/filepermissionsapplier/#a958cd3b9790b98d062b8e5fb5ebc32e6">llvm::FilePermissionsApplier::apply</a>, <a href="/web-llvm/docs/api/classes/llvm/jitlink/basiclayout/#ac6118016e682bb76a031f3857dc3627f">llvm::jitlink::BasicLayout::apply</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/lljit/#ab837d755651a0abce336798a703de9e4">llvm::orc::LLJIT::applyDataLayout</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/aarch32/#a227cdc692d0608ba443b1ad47e97e3e9">llvm::jitlink::aarch32::applyFixup</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/aarch64/#a61310b6c90769dc38a55a4b84b1cc054">llvm::jitlink::aarch64::applyFixup</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/i386/#a1cf84875ae743236d8dd98fd56af9f7b">llvm::jitlink::i386::applyFixup</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/loongarch/#a9b4c142fe5b9d4d263bef7ff0132a9a3">llvm::jitlink::loongarch::applyFixup</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/ppc64/#a5a393f897c1439c03e7ef35e7874a8a1">llvm::jitlink::ppc64::applyFixup</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/x86-64/#a4640b55f4a0124796c017fc725e87add">llvm::jitlink::x86_64::applyFixup</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/aarch32/#a53f135c84cfb135c8e3f890659a3f782">llvm::jitlink::aarch32::applyFixupArm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/aarch32/#a2cc2e3fa12d8c5d0d37310647c9c3a4d">llvm::jitlink::aarch32::applyFixupData</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/aarch32/#a183363f7e8482b2c1e193956dea835ee">llvm::jitlink::aarch32::applyFixupThumb</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunitheader/#a6b65a6bda82f3e6edc3d4111d0a77a26">llvm::DWARFUnitHeader::applyIndexEntry</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#aff2debe7ce6146420630b0d2a102087a">llvm::jitlink::applyPACSigningToModInitPointers</a>, <a href="/web-llvm/docs/api/classes/llvm/object/archive/#a8ad341cb471333b07af638089e1dc7c9">llvm::object::Archive::Archive</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/synthetictypenamebuilder/#ac007678ea81a8e5ab91596fb0825513c">llvm::dwarf_linker::parallel::SyntheticTypeNameBuilder::assignName</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#a2ce07f2980494b70fbc5b5c8b7eac63a">llvm::dwarf_linker::parallel::CompileUnit::assignTypeNames</a>, <a href="/web-llvm/docs/api/classes/llvm/bitcodereadervaluelist/#aab54c009e65d26aaa3160eaa876c94e2">llvm::BitcodeReaderValueList::assignValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/lto/#a89ef034c1f3a70da2446c1af1d656dab">llvm::lto::backend</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/codeviewrecordio/#ae7a3a54117119fa0def504882d4fce23">llvm::codeview::CodeViewRecordIO::beginRecord</a>, <a href="/web-llvm/docs/api/classes/llvm/object/bigarchive/#ade18dcd47b2bf24e98be4745ef6139a9">llvm::object::BigArchive::BigArchive</a>, <a href="/web-llvm/docs/api/structs/anonymous-irsymtab-cpp-/builder/#a0b51b9342dd5e45edcbc6c7237cb1ca7">anonymous{IRSymtab.cpp}::Builder::build</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-macho-x86-64-cpp-/#a03ff5c07b06d927f6e7c5fe729e86156">anonymous{MachO_x86_64.cpp}::buildGOTAndStubs_MachO_x86_64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#ad1f844075d800fea3b14f40b2bb5715e">llvm::jitlink::buildTables_ELF_aarch32</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-elf-i386-cpp-/#aa270e923acb9966f2f2c8e401540e11a">anonymous{ELF_i386.cpp}::buildTables_ELF_i386</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-elf-ppc64-cpp-/#ad5e910e26ae63bcd0feb1845e85aa8ce">anonymous{ELF_ppc64.cpp}::buildTables_ELF_ppc64</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-elf-x86-64-cpp-/#af3f4172554843042d31bec78b73f1fc0">anonymous{ELF_x86_64.cpp}::buildTables_ELF_x86_64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#aa7fb22ff26ffdc811d76c1a0a7be758f">llvm::jitlink::buildTables_MachO_arm64</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/shared/wrapperfunction-cc5f507a6376a88c1d33fbec441bda7d/#a79573fb6786c83b72cf4c51ba2914aad">llvm::orc::shared::WrapperFunction&lt; SPSRetTagT(SPSTagTs...)&gt;::callAsync</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcontext/#a62e2d6aade48552d756381ef9336576a">llvm::DWARFContext::checkAddressSizeSupported</a>, <a href="/web-llvm/docs/api/namespaces/llvm/memprof/anonymous-memprofreader-cpp-/#a82b60c8deaa06915cacf9e571cb6f894">llvm::memprof::anonymous{MemProfReader.cpp}::checkBuffer</a>, <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobject-cpp/#a48aee64ef267e404f3579eb20f5c3e39">checkChars</a>, <a href="/web-llvm/docs/api/structs/llvm/filecheckstring/#ac71c43fb658be4df9989f55be8447e1d">llvm::FileCheckString::CheckDag</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp/#ae8d5d23303122b92e1b4a0afbdb9e656">checkDyldCommand</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp/#a4d955f22836e92a508b414d270041628">checkDyldInfoCommand</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp/#a29d1b39b4762b4de7a37817a3a01355f">checkDylibCommand</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp/#af5d5ac386b9d143dc66cbb3bdac42adf">checkDylibIdCommand</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp/#a21566fd3bc19b4348f0deed830e19199">checkDysymtabCommand</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp/#afbece8143fc21ed045b0d711c7103d17">checkEncryptCommand</a>, <a href="/web-llvm/docs/api/structs/llvm/gsym/header/#ae34d310282ea598de25cd12feb15d653">llvm::gsym::Header::checkForError</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/globalsstream-cpp/#ae26f9a8ac2ab2c64e019e7bf0db493b5">checkHashHdrVersion</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp/#abe7067ce0893d97940a85141e4c44776">checkLinkeditDataCommand</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp/#a77b750f0deb484099d9f4f3539bda353">checkLinkerOptCommand</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a93afe3b7548a63fa4d20b50bedb0a61a">llvm::orc::checkMachORelocatableObject</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp/#aedcf65b10ecb990ac021daf4f940a881">checkNoteCommand</a>, <a href="/web-llvm/docs/api/classes/llvm/object/binary/#afc55f34d54c38dcea2d603b5dd7c902f">llvm::object::Binary::checkOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/binarystream/#af20acc8b7134ce7ffa54c05a7f295fb6">llvm::BinaryStream::checkOffsetForRead</a>, <a href="/web-llvm/docs/api/classes/llvm/binarystreamrefbase/#a7b0ea3513329432068f5cca7d33e207a">llvm::BinaryStreamRefBase&lt; RefType, StreamType &gt;::checkOffsetForRead</a>, <a href="/web-llvm/docs/api/classes/llvm/writablebinarystream/#a054c634299df770d4d683d28e2b3cb7b">llvm::WritableBinaryStream::checkOffsetForWrite</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/aarch32/#a9c7b359f8ba0aa2c37bb009808262df7">llvm::jitlink::aarch32::checkOpcode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/aarch32/#ab081d8136bcb37bb0c6ab56a2714e308">llvm::jitlink::aarch32::checkOpcode</a>, <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/dwarfemitter-cpp/#a99fbec7515ca1c665315334c1a67d3a5">checkOperandCount</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp/#ad8413e5e66b80672de909764764faf7f">checkOverlappingElement</a>, <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobject-cpp/#acf0bc94655eb3c27e0fffcbfd4bc0c7b">checkRecord</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp/#a636124b5ffd9b1f64c447b5d79b385fc">checkRpathCommand</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/asciihexwriter/#a522931f04346e88ee1e60431d25bcc62">llvm::objcopy::elf::ASCIIHexWriter::checkSection</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp/#a6231d1eadcf7d5f81f417fdc5fa394fc">checkSubCommand</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a58bd45157985a622dba76ecef6375f4d">llvm::object::MachOObjectFile::checkSymbolTable</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp/#a197ed26dbc11fa1cf315ab378b657ec4">checkSymtabCommand</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp/#abc5ff59b8ea0a100389a37ea8ec40f9a">checkThreadCommand</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp/#a1a0d53be15e648f327c4292341fa7dad">checkTwoLevelHintsCommand</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp/#a0e53134a7b107f2a0f6213f2f5ed21e1">checkVersCommand</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib/#a25e558db9c4a9a9b6cbd5dc09a2b929b">llvm::orc::JITDylib::clear</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#ab33a7e6fdc362895e1b739081c1286ba">llvm::dwarf_linker::parallel::CompileUnit::cloneAndEmit</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/dwarflinkerimpl/linkcontext/#ac4560fb1d6b91d4ba6edb7e907573c1e">llvm::dwarf_linker::parallel::DWARFLinkerImpl::LinkContext::cloneAndEmitDebugFrame</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#a0b155dc5f7f9374eb06f7277da633577">llvm::dwarf_linker::parallel::CompileUnit::cloneAndEmitDebugLocations</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#aab5e3c8afd376c7fedfcd02a86d31540">llvm::dwarf_linker::parallel::CompileUnit::cloneAndEmitDebugMacro</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#a5d779ebf8d97beda3616fa4d7997e355">llvm::dwarf_linker::parallel::CompileUnit::cloneAndEmitLineTable</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#a67e7cb91f1de318011b4ad8f6453fa7a">llvm::dwarf_linker::parallel::CompileUnit::cloneAndEmitRanges</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-textstubv5-cpp-/#a454eefb23874609b98aa35d4d8cbfd38">anonymous{TextStubV5.cpp}::collectFromArray</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abe9c37f2ba2d21ae9e526ecec89d431d">llvm::collectGlobalObjectNameStrings</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-textstubv5-cpp-/stubparser/#ae8c8a237a39436fb25894d198668f88f">anonymous{TextStubV5.cpp}::StubParser::collectSymbolsFromSegment</a>, <a href="/web-llvm/docs/api/classes/anonymous-fileoutputbuffer-cpp-/inmemorybuffer/#aa633fcd4ff4b9eb332ba7f26d090c10a">anonymous{FileOutputBuffer.cpp}::InMemoryBuffer::commit</a>, <a href="/web-llvm/docs/api/classes/llvm/appendingbinarybytestream/#a834fc8773914333c0e716415df00b973">llvm::AppendingBinaryByteStream::commit</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/debugchecksumssubsection/#a2996e2aecee50f2379910db2fd0d357e">llvm::codeview::DebugChecksumsSubsection::commit</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/debugcrossmoduleexportssubsection/#a53282566910339ca555029c706ad38f8">llvm::codeview::DebugCrossModuleExportsSubsection::commit</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/debugcrossmoduleimportssubsection/#aebce5198b2ec2800c0f08a15e0dce8a6">llvm::codeview::DebugCrossModuleImportsSubsection::commit</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/debugframedatasubsection/#a77473ec3667f5e75068779bc16a3d882">llvm::codeview::DebugFrameDataSubsection::commit</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/debuginlineelinessubsection/#a771a583e046704fd7ec99603a9ae724f">llvm::codeview::DebugInlineeLinesSubsection::commit</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/debuglinessubsection/#a9e5e9c47e7c77bd4e56b89a218e88a19">llvm::codeview::DebugLinesSubsection::commit</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/debugstringtablesubsection/#ac47d08606b57a9fa3481222bbaf3219f">llvm::codeview::DebugStringTableSubsection::commit</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/debugsubsectionrecordbuilder/#a3b37d850ac5595f7549b90707d9b241f">llvm::codeview::DebugSubsectionRecordBuilder::commit</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/debugsymbolssubsection/#ad4d8120e6e6d45362656ef0be7837f7f">llvm::codeview::DebugSymbolsSubsection::commit</a>, <a href="/web-llvm/docs/api/classes/llvm/mutablebinarybytestream/#a72c644f63f931bdfd303e0f8c41a57e4">llvm::MutableBinaryByteStream::commit</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/hashtable/#a27e264b6aad589dd9c5013ca05d2fd55">llvm::pdb::const_iterator&lt; SrcHeaderBlockEntry &gt;::commit</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/dbimoduledescriptorbuilder/#a7df39993912ff56cb17c9f21d2a83455">llvm::pdb::DbiModuleDescriptorBuilder::commit</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/dbistreambuilder/#a8dbe73960ff993f556bc2b82131983fb">llvm::pdb::DbiStreamBuilder::commit</a>, <a href="/web-llvm/docs/api/structs/llvm/pdb/gsihashstreambuilder/#abdfe34c82754e6761b6a81728f151c2b">llvm::pdb::GSIHashStreamBuilder::commit</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/gsistreambuilder/#a76533b678e31f0285dc183e2378d39db">llvm::pdb::GSIStreamBuilder::commit</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/infostreambuilder/#a9f34ad484130077743940295c4ea4dc7">llvm::pdb::InfoStreamBuilder::commit</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/moduledebugstreamref/#a853d085c7c0b05c6da1e071413dd394e">llvm::pdb::ModuleDebugStreamRef::commit</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/namedstreammap/#a6253147b299d9a15f29775b79c273d3c">llvm::pdb::NamedStreamMap::commit</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/pdbstringtablebuilder/#a772f244f4c12e6fe2628dffb0d358025">llvm::pdb::PDBStringTableBuilder::commit</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/symbolstream/#a65bb7d1ddb0d5bf47c9645f925d5725b">llvm::pdb::SymbolStream::commit</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/tpistream/#a379d83e6e1bc1210c6542b71164467de">llvm::pdb::TpiStream::commit</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/tpistreambuilder/#a82a7a598a05d2c0e837d924da348c414">llvm::pdb::TpiStreamBuilder::commit</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/dbimoduledescriptorbuilder/#a76899fd759b150059d1a8d2b2b475c78">llvm::pdb::DbiModuleDescriptorBuilder::commitSymbolStream</a>, <a href="/web-llvm/docs/api/classes/anonymous-debuggersupportplugin-cpp-/machodebugobjectsynthesizer/#a21d1557ff7212b52d2935836c8619919">anonymous{DebuggerSupportPlugin.cpp}::MachODebugObjectSynthesizer&lt; MachOTraits &gt;::completeSynthesisAndRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldimpl/#af089befa203447cdf71f665a1993a997">llvm::RuntimeDyldImpl::computeTotalAllocSize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a1807c21ab0be67ec70499fe55532ac00">llvm::codeview::consume</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a810901bf1e6c5f3228de79e7a61ef36b">llvm::codeview::consume</a>, <a href="/web-llvm/docs/api/classes/llvm/xray/logbuilderconsumer/#a22404325e53349adcbded737fd5a4646">llvm::xray::LogBuilderConsumer::consume</a>, <a href="/web-llvm/docs/api/classes/llvm/xray/pipelineconsumer/#a27d508ca423034096797100c20dc9793">llvm::xray::PipelineConsumer::consume</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a0d46104eb6ba85dbd9788ff11e64aaa6">llvm::codeview::consume_numeric</a>, <a href="/web-llvm/docs/api/classes/llvm/gsym/dwarftransformer/#ab014307b03ade42770de6ed2f827630b">llvm::gsym::DwarfTransformer::convert</a>, <a href="/web-llvm/docs/api/classes/llvm/gsym/objectfiletransformer/#a9940b2d9a5f2a7de1dcfcdb970bf5e51">llvm::gsym::ObjectFileTransformer::convert</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/coffplatform/#a0ff140ec3eee8b9a860f3626b5640c04">llvm::orc::COFFPlatform::Create</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/elfnixplatform/#aa9a419d5abbdb82bc571c3867365716d">llvm::orc::ELFNixPlatform::Create</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/lazyreexportsmanager/#af7356741dd0185ed365b0cdfc7d96a14">llvm::orc::LazyReexportsManager::Create</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/localjitcompilecallbackmanager/#ae7bdf52c922cb43fa05939b10a64b2c6">llvm::orc::LocalJITCompileCallbackManager&lt; ORCABI &gt;::Create</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/localtrampolinepool/#adac5b0cfc4a4a3eab41ab72498e7d03c">llvm::orc::LocalTrampolinePool&lt; ORCABI &gt;::Create</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/machoplatform/#ad166f5736231229286c93cd8c6aa8b6d">llvm::orc::MachOPlatform::Create</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/staticlibrarydefinitiongenerator/#a6e910497d88200a16108f6849b074ab8">llvm::orc::StaticLibraryDefinitionGenerator::Create</a>, <a href="/web-llvm/docs/api/classes/llvm/coverage/binarycoveragereader/#a75f0ba2a248f2f7f77f477bfb8d6dab2">llvm::coverage::BinaryCoverageReader::create</a>, <a href="/web-llvm/docs/api/classes/llvm/instrprofsymtab/#a46c4a2e0de8a1253010e2a0221f4814a">llvm::InstrProfSymtab::create</a>, <a href="/web-llvm/docs/api/classes/llvm/instrprofsymtab/#a4e1b4f3ad8f68eee1a8bd258ca6487aa">llvm::InstrProfSymtab::create</a>, <a href="/web-llvm/docs/api/classes/llvm/instrprofsymtab/#a9d8ea668d32a807e0313e35e6c564a5d">llvm::InstrProfSymtab::create</a>, <a href="/web-llvm/docs/api/classes/llvm/instrprofsymtab/#aa4f8c9517d7d182974ce657311440a6b">llvm::InstrProfSymtab::create</a>, <a href="/web-llvm/docs/api/classes/llvm/instrprofsymtab/#a257438a6abdc8699555b7385b354922a">llvm::InstrProfSymtab::create</a>, <a href="/web-llvm/docs/api/structs/llvm/minidumpyaml/stream/#a7370b2f0babea4afada61ccc3b15c54e">llvm::MinidumpYAML::Stream::create</a>, <a href="/web-llvm/docs/api/classes/llvm/object/archive/#afff545dbbc7e3d85c4e6d914200747db">llvm::object::Archive::create</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a6456a8f4d04f36afe434911ec571ba3a">llvm::object::MachOObjectFile::create</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machouniversalbinary/#a094ea3b3b52a30341f589955d6076434">llvm::object::MachOUniversalBinary::create</a>, <a href="/web-llvm/docs/api/classes/llvm/object/slice/#adbb4dbd1eb3f1a9959da3bf6baf327e4">llvm::object::Slice::create</a>, <a href="/web-llvm/docs/api/classes/llvm/object/tapiuniversal/#afa519d925ed9fbfc79009532ec9ac123">llvm::object::TapiUniversal::create</a>, <a href="/web-llvm/docs/api/classes/llvm/object/tbvectorext/#a2a372f11249e08b3dea58aeb5eac2d58">llvm::object::TBVectorExt::create</a>, <a href="/web-llvm/docs/api/classes/llvm/object/xcofftracebacktable/#ad2c9fd0ee3e91f844a281fc9af7f57c9">llvm::object::XCOFFTracebackTable::create</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/lljitbuildersetters/#ac6e077456ace4ec4b9e0e79235dc2f52">llvm::orc::LLJITBuilderSetters&lt; JITType, SetterImpl, State &gt;::create</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a04285415a321e48322c08f3b9185540e">llvm::OpenMPIRBuilder::createCancel</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a40f4f75fb4f4f3a69abd8360d590c93a">llvm::createCtxProfFromYAML</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#a73308d92ed2cabd9d1f9e07ffaadf916">llvm::jitlink::createEHFrameRecorderPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/aarch64/#a8b6a1311d66ca584dd828968ec269156">llvm::jitlink::aarch64::createEmptyPointerSigningFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/diasession/#a2219741a985be587beb5e75fee1417f7">llvm::pdb::DIASession::createFromExe</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/nativesession/#a41e7e990ed77bc137febf6f0127ea8d0">llvm::pdb::NativeSession::createFromExe</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/diasession/#a7861193fc9b9776bd882bc12d58cb356">llvm::pdb::DIASession::createFromPdb</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/nativesession/#a40a2d747d45eb8ebf19defef962acdb6">llvm::pdb::NativeSession::createFromPdb</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/nativesession/#a8cf765bc037aeb5a285300d19ecc0235">llvm::pdb::NativeSession::createFromPdbPath</a>, <a href="/web-llvm/docs/api/classes/llvm/object/objectfile/#acc723cdaf6e00f67816de239cdaf82cb">llvm::object::ObjectFile::createGOFFObjectFile</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvbinaryreader/#adf2a6238adfb3ada928de5340d5298b6">llvm::logicalview::LVBinaryReader::createInstructions</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvbinaryreader/#ac378e86f9979cde149105568f10ee404">llvm::logicalview::LVBinaryReader::createInstructions</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvbinaryreader/#a6e3f70a5f3d1222550716fb9db632c6a">llvm::logicalview::LVBinaryReader::createInstructions</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcopy/#afb660c7a07ee04be6dac1b6ce20de6d6">llvm::objcopy::createNewArchiveMembers</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a4f81b9940e1869e146636dc533455929">llvm::OpenMPIRBuilder::createParallel</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvcodeviewreader/#ab2b600452f45c702aaffaaeb6c4182c0">llvm::logicalview::LVCodeViewReader::createScopes</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvdwarfreader/#abf565023d8f6916f29adcd9ac264400e">llvm::logicalview::LVDWARFReader::createScopes</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvreader/#af75cb2856d2563990ed489c38b63a5c3">llvm::logicalview::LVReader::createScopes</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#af36172c1f538b7305b44760997d5a3c2">llvm::OpenMPIRBuilder::createSections</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a3e1a0b27abb4d57e2293c46802eee89d">llvm::OpenMPIRBuilder::createSingle</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvsplitcontext/#abbd84c64887e4fc08cf9e7d5fe9d14a9">llvm::logicalview::LVSplitContext::createSplitFolder</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/localindirectstubsmanager/#a0a26a5a30aa699dce334f256f494134a">llvm::orc::LocalIndirectStubsManager&lt; TargetT &gt;::createStub</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/localindirectstubsmanager/#af3101c8f957177753c7df294cc43888e">llvm::orc::LocalIndirectStubsManager&lt; TargetT &gt;::createStubs</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#ae54a581ccf494afe52ae45af317bbd58">llvm::OpenMPIRBuilder::createTargetData</a>, <a href="/web-llvm/docs/api/classes/llvm/object/objectfile/#a920bb15c9298c61cbd6db1cef2394a82">llvm::object::ObjectFile::createWasmObjectFile</a>, <a href="/web-llvm/docs/api/classes/llvm/jitlink/inprocessmemorymanager/#a5599aaf8c94c775d12080e3401796fd2">llvm::jitlink::InProcessMemoryManager::deallocate</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/mapperjitlinkmemorymanager/#a16536e0ae009cb70f4440f6877828693">llvm::orc::MapperJITLinkMemoryManager::deallocate</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/rt-bootstrap/simpleexecutormemorymanager/#a62908f2339aa6c5e38aa862a69c7f14d">llvm::orc::rt_bootstrap::SimpleExecutorMemoryManager::deallocate</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8f189b42efc177f3903f6a69d1e0b404">llvm::decodeBase64</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/elf-cpp/#ab230da2e143b2070f404fea9287e4ed9">decodeBBAddrMapImpl</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcopy/#abe70653ea636e6b63159edf52d38afc5">llvm::objcopy::deepWriteArchive</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib/#a5ec8631eb0c37168d6f85c4ecad77747">llvm::orc::JITDylib::define</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib/#a557549c7b7f504a9c5a585512bf28a57">llvm::orc::JITDylib::define</a>, <a href="/web-llvm/docs/api/classes/llvm/filecheckpatterncontext/#a7137a381bae270178ff79807b1d096d3">llvm::FileCheckPatternContext::defineCmdlineVariables</a>, <a href="/web-llvm/docs/api/classes/anonymous-lljit-cpp-/genericllvmirplatformsupport/#a34baf0308ca340bbfb889e3fbc9a0930">anonymous{LLJIT.cpp}::GenericLLVMIRPlatformSupport::deinitialize</a>, <a href="/web-llvm/docs/api/classes/anonymous-lljit-cpp-/inactiveplatformsupport/#a555ccb90a15e09d459d0f4eb15c4b7f7">anonymous{LLJIT.cpp}::InactivePlatformSupport::deinitialize</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/inprocessmemorymapper/#ac501a4fc8b8826d6451a9ae117ca3e0b">llvm::orc::InProcessMemoryMapper::deinitialize</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/orcplatformsupport/#a270be4ebefb9040ed276a37b2ec3dcb8">llvm::orc::ORCPlatformSupport::deinitialize</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/rt-bootstrap/executorsharedmemorymapperservice/#a860b91123cbc492ac289fa52811dc84e">llvm::orc::rt_bootstrap::ExecutorSharedMemoryMapperService::deinitialize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#ac8aa9bd7dd3e90caa3b167ee0e2f736b">llvm::orc::deregisterFrameWrapper</a>, <a href="/web-llvm/docs/api/structs/llvm/codeview/serialize-conditional-impl/#ad78c001f2e5aab29f77102188c8c41bf">llvm::codeview::serialize_conditional_impl&lt; T, U &gt;::deserialize</a>, <a href="/web-llvm/docs/api/structs/llvm/codeview/serialize-vector-tail-impl/#ae99d0aac9a8dcb44986944245c335118">llvm::codeview::serialize_vector_tail_impl&lt; T &gt;::deserialize</a>, <a href="/web-llvm/docs/api/classes/llvm/indexedmemprofreader/#a7907bad312db28b49d4a53468ef4d0b1">llvm::IndexedMemProfReader::deserialize</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/shared/detail/resultdeserializer/#a20bdb21055af77d139f3963985886ed2">llvm::orc::shared::detail::ResultDeserializer&lt; SPSRetTagT, RetT &gt;::deserialize</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/shared/detail/resultdeserializer-8112f182ad5a7941abf9a1219f2005f7/#ad1ec100cb35b916e47eabbce788fdc30">llvm::orc::shared::detail::ResultDeserializer&lt; SPSError, Error &gt;::deserialize</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/shared/detail/resultdeserializer-163b48e70dbecc03c34344b5da8431c0/#aef3f4573c8640758eab5d0acea5eb549">llvm::orc::shared::detail::ResultDeserializer&lt; SPSExpected&lt; SPSTagT &gt;, Expected&lt; T &gt; &gt;::deserialize</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/symboldeserializer/#a4f31719a3302d53ef0f8ab28e7afc76e">llvm::codeview::SymbolDeserializer::deserializeAs</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/typedeserializer/#ad2afe9d87179bb184fd5f477db6e8509">llvm::codeview::TypeDeserializer::deserializeAs</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/selfexecutorprocesscontrol/#a70b5731dbe77edbd06e480a185fb9c6e">llvm::orc::SelfExecutorProcessControl::disconnect</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/unsupportedexecutorprocesscontrol/#a3437f73aea363bd0fa7085ff1535ad2f">llvm::orc::UnsupportedExecutorProcessControl::disconnect</a>, <a href="/web-llvm/docs/api/classes/llvm/telemetry/manager/#a9c3390e611720f9695e36e5c9a62aca2">llvm::telemetry::Manager::dispatch</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-dlltooldriver-cpp-/#a23cbef0272f92b38f3f6654ce8af1cfb">anonymous{DlltoolDriver.cpp}::doIdentify</a>, <a href="/web-llvm/docs/api/files/lib/lib/tooldrivers/lib/tooldrivers/llvm-lib/libdriver-cpp/#a80f5931fdc6db3599ee4309f5a62b917">doList</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvreader/#a8a15ec2eff468d1dc1137a8a8f20f525">llvm::logicalview::LVReader::doLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvobject/#a188ae80eca4861c8c577fa5e905d8129">llvm::logicalview::LVObject::doPrint</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvreader/#ab6198458ec732d8dff12eb1a80049ded">llvm::logicalview::LVReader::doPrint</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvscope/#aaeb4ea25f6bc1bbccd544d48f199f7b5">llvm::logicalview::LVScope::doPrint</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvscoperoot/#a6e726d8dda471e304170f6878ef09997">llvm::logicalview::LVScopeRoot::doPrintMatches</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcontext/#a872194924baf250829ba1b42a0b14105">llvm::DWARFContext::dump</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcopy/coff/#a81e88ae7d3e872ba0cdc367330b2974d">llvm::objcopy::coff::dumpSection</a>, <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobjcopy-cpp/#aa40e91285159d4c13a609b1810b19485">dumpSectionToFile</a>, <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machoobjcopy-cpp/#aa40e91285159d4c13a609b1810b19485">dumpSectionToFile</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcopy/wasm/#ab4c167a5e231ccb60ec1eb5552ca233b">llvm::objcopy::wasm::dumpSectionToFile</a>, <a href="/web-llvm/docs/api/classes/llvm/instrprofcorrelatorimpl/#ac405f176b874b2cd1972cce9e3dd7382">llvm::InstrProfCorrelatorImpl&lt; IntPtrT &gt;::dumpYaml</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/debuglinesectionemitter/#a81feed7a90b5abc9e58b574e7da2a360">llvm::dwarf_linker::parallel::DebugLineSectionEmitter::emit</a>, <a href="/web-llvm/docs/api/groups/methods/#ga9b4dbcbc740191455c092e2edd8afa51">llvm::dwarf_linker::parallel::DwarfUnit::emitAbbreviations</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a98b55a0d95b3926151545101e4f2aef9">llvm::OpenMPIRBuilder::emitCancelationCheckImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldimpl/#a7516dd41b3867b963148426688fe9ff3">llvm::RuntimeDyldImpl::emitCommonSymbols</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarfyaml/#a81600054c53c8bfe10547514c330a547">llvm::DWARFYAML::emitDebugAbbrev</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarfyaml/#aca49747266152cead6b515f84225e351">llvm::DWARFYAML::emitDebugAddr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarfyaml/#a2d42b869454e23ae5fcad0cd11719a30">llvm::DWARFYAML::emitDebugAranges</a>, <a href="/web-llvm/docs/api/groups/methods/#ga4353067d272bae6ec1a934e5ea39f924">llvm::dwarf_linker::parallel::DwarfUnit::emitDebugInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarfyaml/#a0aca0c593a4951ced7f067663729871a">llvm::DWARFYAML::emitDebugInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarfyaml/#ae91e1699c9c07514f5381a7d882f2ef0">llvm::DWARFYAML::emitDebugLine</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarfyaml/#ad1f7f7a8ed653ac5d4c9cf22992767ea">llvm::DWARFYAML::emitDebugNames</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarfyaml/#a258100c512356fe24a12a14fc7ad9d78">llvm::DWARFYAML::emitDebugRanges</a>, <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/dwarfemitter-cpp/#a1bf0b70372e2ca4b1e9540e9c4f8aa41">emitDebugSectionImpl</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarfyaml/#a9feb9f5ca88b1a9d4f6e702a39d35060">llvm::DWARFYAML::emitDebugSections</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarfyaml/#aac6c1a9a865304388a58f18a55a4a8f7">llvm::DWARFYAML::emitDebugStr</a>, <a href="/web-llvm/docs/api/groups/methods/#ga579ac60d76c4a3b6ca084238591d4437">llvm::dwarf_linker::parallel::DwarfUnit::emitDebugStringOffsetSection</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarfyaml/#a08aae9cc5950db0fa5c9a00e95a3492c">llvm::DWARFYAML::emitDebugStrOffsets</a>, <a href="/web-llvm/docs/api/classes/llvm/lto/thinbackendproc/#a319ef14c9ce4b7ca607149680d990477">llvm::lto::ThinBackendProc::emitFiles</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a39b12e3ad8afd4183a2cd63f1b1b8746">llvm::OpenMPIRBuilder::emitIfClause</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af1ad9f56998b03b32a1066b574125126">llvm::EmitImportsFiles</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/dwarflinkerimpl/linkcontext/#a5e9424dbd42c4c0b08ff61c556bd9aa1">llvm::dwarf_linker::parallel::DWARFLinkerImpl::LinkContext::emitInvariantSections</a>, <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/dwarfemitter-cpp/#aa371f7d58f8c4b09db71516e37bf45f4">emitPubSection</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a567502d7244077ed45e0c9471d31ba4c">llvm::OpenMPIRBuilder::emitTargetRegionFunction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#ad059d61cab7f6bc8ee555ae23acd7b52">llvm::orc::enableDebuggerSupport</a>, <a href="/web-llvm/docs/api/structs/llvm/gsym/callsiteinfo/#a04a75849a90c95c00d22f3894a196bc5">llvm::gsym::CallSiteInfo::encode</a>, <a href="/web-llvm/docs/api/structs/llvm/gsym/callsiteinfocollection/#a369566f0a63d8b39c91018ae3c9cf95d">llvm::gsym::CallSiteInfoCollection::encode</a>, <a href="/web-llvm/docs/api/structs/llvm/gsym/header/#a976c8e49991502be5186b73cdd2d3589">llvm::gsym::Header::encode</a>, <a href="/web-llvm/docs/api/structs/llvm/gsym/inlineinfo/#a942b72b4d473fa049b9e5f4fc1fce789">llvm::gsym::InlineInfo::encode</a>, <a href="/web-llvm/docs/api/classes/llvm/gsym/linetable/#a41c4a2acdbcfaf2a18a61b60d42a9dc4">llvm::gsym::LineTable::encode</a>, <a href="/web-llvm/docs/api/structs/llvm/gsym/mergedfunctionsinfo/#acf6e5aa620d3dbd266db4b6d03388ed7">llvm::gsym::MergedFunctionsInfo::encode</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/codeviewrecordio/#a5826f9d7fcd1bddfc2f4fa4ade543d70">llvm::codeview::CodeViewRecordIO::endRecord</a>, <a href="/web-llvm/docs/api/classes/llvm/bitstreamcursor/#a6ced3cd5539e8a620f270f3dbb0c48ab">llvm::BitstreamCursor::EnterSubBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/codegendatareader/#a4d9d859b066e0d93458a74c4763cf553">llvm::CodeGenDataReader::error</a>, <a href="/web-llvm/docs/api/classes/llvm/instrprofreader/#aedd4249ec00d14c5505207bd648514f0">llvm::InstrProfReader::error</a>, <a href="/web-llvm/docs/api/structs/llvm/remarks/yamlremarkparser/#a0fe1e5bb33e59ff69fdfadb26e53d6db">llvm::remarks::YAMLRemarkParser::error</a>, <a href="/web-llvm/docs/api/classes/llvm/binaryoperation/#ae881b7ad9c843880674599dbe5d85dd9">llvm::BinaryOperation::eval</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvcompare/#a7dd02cee213cf5ed75d6589b4771bb1f">llvm::logicalview::LVCompare::execute</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcopy/coff/#a03da0184bacf98a2a34f81413e7159b4">llvm::objcopy::coff::executeObjcopyOnBinary</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcopy/elf/#a55af853235c79ddae3c55b4670a825dd">llvm::objcopy::elf::executeObjcopyOnBinary</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcopy/wasm/#ae6098aac8d9341369e7479af43f3d1c2">llvm::objcopy::wasm::executeObjcopyOnBinary</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcopy/xcoff/#a7de8195508237e49f93b19619c37707b">llvm::objcopy::xcoff::executeObjcopyOnBinary</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcopy/macho/#af0902234f18e67e03ce4b3d4d8a6a273">llvm::objcopy::macho::executeObjcopyOnMachOUniversalBinary</a>, <a href="/web-llvm/docs/api/classes/llvm/cl/expansioncontext/#aebe5d0c3153807263988efc57d69a509">llvm::cl::ExpansionContext::expandResponseFiles</a>, <a href="/web-llvm/docs/api/classes/llvm/appleacceleratortable/#a03c6ddff22ebc41466903c966d7e7655">llvm::AppleAcceleratorTable::extract</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfabbreviationdeclaration/#a0eb41e4fd2f2686492e3aadaeb8b0617">llvm::DWARFAbbreviationDeclaration::extract</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfabbreviationdeclarationset/#a51185edea3b0246d3c37ee13b9553491">llvm::DWARFAbbreviationDeclarationSet::extract</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugarangeset/#a81576979ca20731e32ff1b245df0c5f3">llvm::DWARFDebugArangeSet::extract</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugnames/#ab6916b1dbe7cddf0de48fa60347a87c9">llvm::DWARFDebugNames::extract</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugnames/nameindex/#acce40431959421046e6a001a951e8dd9">llvm::DWARFDebugNames::NameIndex::extract</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugrangelist/#a25597c272c2c6da035416f2331dccfbd">llvm::DWARFDebugRangeList::extract</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarflisttablebase/#ae4e640d58b73a1ecf5b3c4a73a476806">llvm::DWARFListTableBase&lt; DWARFListType &gt;::extract</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarflisttableheader/#a1a4f52d08af4f50e2e5b0f2ea73fe12f">llvm::DWARFListTableHeader::extract</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarflisttype/#a5ce06b7e3524ccb5cde055c3cf596b10">llvm::DWARFListType&lt; ListEntryType &gt;::extract</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunitheader/#a528edf849dcc29ea39dcbd66bcf2ba7d">llvm::DWARFUnitHeader::extract</a>, <a href="/web-llvm/docs/api/structs/llvm/rangelistentry/#a02b8d98254f6a78f14c66d249db3bfc4">llvm::RangeListEntry::extract</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-offloadbinary-cpp-/#aa2f8f902ed35880d4ccb900b4ddbe2c1">anonymous{OffloadBinary.cpp}::extractFromArchive</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-offloadbinary-cpp-/#a0f076ea04eda5249d0527c704881cdf1">anonymous{OffloadBinary.cpp}::extractFromBitcode</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-offloadbinary-cpp-/#a426a48f358aaf6be7a95428dae0d4f31">anonymous{OffloadBinary.cpp}::extractFromObject</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#a214181fcdbdcdd2ce1d22fe395716abc">llvm::object::extractOffloadBinaries</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-offloadbinary-cpp-/#a67bf5d7f987fa670edc3e7948bac2a07">anonymous{OffloadBinary.cpp}::extractOffloadFiles</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugaddrtable/#a964dead7738d899e97cf1d3571e85aad">llvm::DWARFDebugAddrTable::extractV5</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfformvalue/#aa146755e2500aea560c4417a30c0b96b">llvm::DWARFFormValue::extractValue</a>, <a href="/web-llvm/docs/api/classes/llvm/simplebitstreamcursor/#ae3b93b659d4c4f5aeaaedc892916d1bf">llvm::SimpleBitstreamCursor::fillCurWord</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ifs/#ad3d6148db61bf742f0e6a2c6a0f43fd9">llvm::ifs::filterIFSSyms</a>, <a href="/web-llvm/docs/api/classes/llvm/gsym/gsymcreator/#abdaa5c17b22848e0de64e78984c8d07c">llvm::gsym::GsymCreator::finalize</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/asciihexwriter/#a6c8bb3c922ce45c595377546d41f1222">llvm::objcopy::elf::ASCIIHexWriter::finalize</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/binarywriter/#a5b9da0f3636f00c8eb9dca28bf21e606">llvm::objcopy::elf::BinaryWriter::finalize</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/elfwriter/#a96ec94d70c19707787f756fa97cc3467">llvm::objcopy::elf::ELFWriter&lt; ELFT &gt;::finalize</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/rt-bootstrap/simpleexecutormemorymanager/#a0c3a2679314fcbd29c249386447c8ba4">llvm::orc::rt_bootstrap::SimpleExecutorMemoryManager::finalize</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldimpl/#a6dfeef2ecf7ff9f91673432765f3b695">llvm::RuntimeDyldImpl::finalizeAsync</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldcoffx86-64/#a57f12f7f4831372682abeda7f9e23ab8">llvm::RuntimeDyldCOFFX86_64::finalizeLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldelf/#a34d452366da541e62d1f37b1f284800d">llvm::RuntimeDyldELF::finalizeLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldimpl/#a35ea08a2c201659672a5fc147bb4c03b">llvm::RuntimeDyldImpl::finalizeLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmachocrtpbase/#afdfe2cf5151ed6e7266417d9f1db5f80">llvm::RuntimeDyldMachOCRTPBase&lt; Impl &gt;::finalizeLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/epcgenericrtdyldmemorymanager/#a0db7d447f814afaee65a64c0419805dd">llvm::orc::EPCGenericRTDyldMemoryManager::finalizeMemory</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/dbimoduledescriptorbuilder/#a161421bb3fa6eba78090ad09df0b1c37">llvm::pdb::DbiModuleDescriptorBuilder::finalizeMsfLayout</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/dbistreambuilder/#a4dbf36873ea777c97316bb56cb47e78c">llvm::pdb::DbiStreamBuilder::finalizeMsfLayout</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/gsistreambuilder/#a5d9cf5b89c50f30cf3d85ec3331b270a">llvm::pdb::GSIStreamBuilder::finalizeMsfLayout</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/infostreambuilder/#a9958d0be3a7f37e338c886bf15c674ec">llvm::pdb::InfoStreamBuilder::finalizeMsfLayout</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/tpistreambuilder/#a65f27123f9333b3ee05446a346267d87">llvm::pdb::TpiStreamBuilder::finalizeMsfLayout</a>, <a href="/web-llvm/docs/api/namespaces/llvm/lto/#abf9cf61a64ab2f14496104cc59a28d22">llvm::lto::finalizeOptimizationRemarks</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmachoaarch64/#afd0e216bdcc14ae5d7982a3426ee09ad">llvm::RuntimeDyldMachOAArch64::finalizeSection</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmachoarm/#a13b4460b917f0cf9c592c8e343c0a9a7">llvm::RuntimeDyldMachOARM::finalizeSection</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmachoi386/#a2b1ab19add3fb382ab3fe720c594002f">llvm::RuntimeDyldMachOI386::finalizeSection</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmachox86-64/#af9ff3905023451c6ec3c0ffbf0ca2d06">llvm::RuntimeDyldMachOX86_64::finalizeSection</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#aab8397ea715fe1132418fcad480386db">llvm::DWARFUnit::findLoclistFromOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/typeunit/#a2de70543d073c4a85bf44c845b7305e9">llvm::dwarf_linker::parallel::TypeUnit::finishCloningAndEmit</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/cvsymbolvisitor-cpp/#a6087eb2848e529ac18b815211091ff27">finishVisitation</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvlogicalvisitor/#aeefe0bd6abc3bfcaa5c237bfa9c13011">llvm::logicalview::LVLogicalVisitor::finishVisitation</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a98a8554492a59019e487d750863f96f2">llvm::dwarf_linker::finiteLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/xray/blockindexer/#a6b7ee8c19837fb7c4c10a3bdf9d8667f">llvm::xray::BlockIndexer::flush</a>, <a href="/web-llvm/docs/api/classes/llvm/xray/traceexpander/#adcb69ec17bb48e6c745866009f2829e5">llvm::xray::TraceExpander::flush</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a38f536657a01f40d99f770fddee8e14a">llvm::codeview::forEachCodeViewRecord</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-dlltooldriver-cpp-/#ab09d28878031ffd0f73e46ea295c1e65">anonymous{DlltoolDriver.cpp}::forEachCoff</a>, <a href="/web-llvm/docs/api/classes/llvm/jitlink/elflinkgraphbuilder/#a3d2f87d599884cbc4bbdbd1fa68052f9">llvm::jitlink::ELFLinkGraphBuilder&lt; ELFType&lt; DataEndianness, false &gt; &gt;::forEachRelaRelocation</a>, <a href="/web-llvm/docs/api/classes/llvm/jitlink/cofflinkgraphbuilder/#a1408ab8cac30c08491c126a28e803a04">llvm::jitlink::COFFLinkGraphBuilder::forEachRelocation</a>, <a href="/web-llvm/docs/api/classes/llvm/jitlink/elflinkgraphbuilder/#a9b05ea912d8cd67c968c579e3d81cef7">llvm::jitlink::ELFLinkGraphBuilder&lt; ELFType&lt; DataEndianness, false &gt; &gt;::forEachRelRelocation</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/symbollookupset/#ad671f8407fb7c4b86f0cf23940304e9b">llvm::orc::SymbolLookupSet::forEachWithRemoval</a>, <a href="/web-llvm/docs/api/structs/llvm/codeviewyaml/detail/unknownsymbolrecord/#a20ab345d5cce9e08d1319607834b711f">llvm::CodeViewYAML::detail::UnknownSymbolRecord::fromCodeViewSymbol</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/shared/detail/#abba6e489c8732769239a8efbbf27364a">llvm::orc::shared::detail::fromSPSSerializable</a>, <a href="/web-llvm/docs/api/classes/llvm/httpserver/#a57df1a0b2431ed4c6afb10acfb6108d1">llvm::HTTPServer::get</a>, <a href="/web-llvm/docs/api/namespaces/llvm/offloading/amdgpu/#a658b1211d163ef9492d062d29de98201">llvm::offloading::amdgpu::getAMDGPUMetaDataFromImage</a>, <a href="/web-llvm/docs/api/classes/llvm/object/coffobjectfile/#a73121eb9b654794ad353cb23f6f02100">llvm::object::COFFObjectFile::getAuxSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/executorprocesscontrol/#a2dc8aa3190f19a2085f418b95cd8194a">llvm::orc::ExecutorProcessControl::getBootstrapMapValue</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/executorprocesscontrol/#aab12eb0f7563916a37da32e520dc1ecf">llvm::orc::ExecutorProcessControl::getBootstrapSymbols</a>, <a href="/web-llvm/docs/api/classes/llvm/object/elfobjectfile/#ad4f1deb260cb6fd64575135be5a3d25f">llvm::object::ELFObjectFile&lt; ELF32LE &gt;::getBuildAttributes</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-buildid-cpp-/#a10d49947a1b089d5ee06458bf8252a37">anonymous{BuildID.cpp}::getBuildID</a>, <a href="/web-llvm/docs/api/classes/llvm/object/record/#a68447fd5872ee1b7ff3b7bd7d39e0077">llvm::object::Record::getContinuousData</a>, <a href="/web-llvm/docs/api/classes/llvm/object/elffile/#aa1027abe2321f5eee653435e5305ddab">llvm::object::ELFFile&lt; ELFT &gt;::getCrelHeader</a>, <a href="/web-llvm/docs/api/classes/llvm/object/coffobjectfile/#a97ddeb77657c64ca7b6fa88ee659e76f">llvm::object::COFFObjectFile::getDebugPDBInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/object/coffobjectfile/#ae18b7d7be4354e3df59467ddf7d35c63">llvm::object::COFFObjectFile::getDebugPDBInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/object/delayimportdirectoryentryref/#aaf2735f72929179c60d3fa16c51eb758">llvm::object::DelayImportDirectoryEntryRef::getDelayImportTable</a>, <a href="/web-llvm/docs/api/classes/llvm/object/exportdirectoryentryref/#a198ceb1faa5b9ba441fdb2184694d7a2">llvm::object::ExportDirectoryEntryRef::getDllName</a>, <a href="/web-llvm/docs/api/classes/llvm/instrprofreader/#a52fa2464e6641c29b3a34dd839e715de">llvm::InstrProfReader::getError</a>, <a href="/web-llvm/docs/api/classes/llvm/object/exportdirectoryentryref/#a4c5d44309752d19a93f8fbd9af1d6323">llvm::object::ExportDirectoryEntryRef::getExportRVA</a>, <a href="/web-llvm/docs/api/files/lib/lib/targetparser/riscvisainfo-cpp/#ac69e7d445bf4af727118416d0ea36250">getExtensionVersion</a>, <a href="/web-llvm/docs/api/classes/llvm/object/exportdirectoryentryref/#ac2d1ed13c0944b547ff2384e84b2c068">llvm::object::ExportDirectoryEntryRef::getForwardTo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coverage/accessors/#ab6161a32808a77777e006ca358dac0b2">llvm::coverage::accessors::getFuncNameViaRef</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/archive-cpp/#a73d59676cde66e2b3b227b524b35f891">getGlobalSymtabLocAndSize</a>, <a href="/web-llvm/docs/api/classes/llvm/object/coffobjectfile/#a72ab1cfa75f161aac0286a7fa3e217b6">llvm::object::COFFObjectFile::getHintName</a>, <a href="/web-llvm/docs/api/classes/llvm/object/importedsymbolref/#a160b166d2d630dc56ce2a097e49e0fb9">llvm::object::ImportedSymbolRef::getHintNameRVA</a>, <a href="/web-llvm/docs/api/classes/llvm/binaryoperation/#a24d9325add2b388eebc0420cf6a0fdb4">llvm::BinaryOperation::getImplicitFormat</a>, <a href="/web-llvm/docs/api/classes/llvm/object/delayimportdirectoryentryref/#a977b5c7ce60ad8ed18d1d02fa8ff46c2">llvm::object::DelayImportDirectoryEntryRef::getImportAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/object/importdirectoryentryref/#ae510d996a6e43e59ecf4f44b4b75c28e">llvm::object::ImportDirectoryEntryRef::getImportAddressTableRVA</a>, <a href="/web-llvm/docs/api/classes/llvm/object/importdirectoryentryref/#a9174d69529a86d043fc0068feb9a1243">llvm::object::ImportDirectoryEntryRef::getImportLookupTableRVA</a>, <a href="/web-llvm/docs/api/classes/llvm/indexedinstrprofreader/#a8a83ecab002375cf09cf04f12470bf0e">llvm::IndexedInstrProfReader::getInstrProfRecord</a>, <a href="/web-llvm/docs/api/classes/llvm/object/archive/symbol/#aa53f9de42b9d8eeaf9af259f59f4a1be">llvm::object::Archive::Symbol::getMember</a>, <a href="/web-llvm/docs/api/classes/llvm/object/delayimportdirectoryentryref/#ae2efead10d8a729e090a8e18d225128f">llvm::object::DelayImportDirectoryEntryRef::getName</a>, <a href="/web-llvm/docs/api/classes/llvm/object/importdirectoryentryref/#afbebc5a804bd81020f96c3815ad2ea29">llvm::object::ImportDirectoryEntryRef::getName</a>, <a href="/web-llvm/docs/api/classes/llvm/object/archive/child/#a137ad5829c3f2470a0da63800c59385e">llvm::object::Archive::Child::getNext</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/coffobjectfile-cpp/#a270d895418a237eac4aacc08cf0db5b2">getObject</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a603eb2d37a31ea2c14318bedeecb8e3c">llvm::getOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/object/exportdirectoryentryref/#a674bb06bfaef392d28bfdcc50ea39033">llvm::object::ExportDirectoryEntryRef::getOrdinal</a>, <a href="/web-llvm/docs/api/classes/llvm/object/importedsymbolref/#a5b93079933a33ceb42801c670ac243a8">llvm::object::ImportedSymbolRef::getOrdinal</a>, <a href="/web-llvm/docs/api/classes/llvm/object/exportdirectoryentryref/#a542da0e37debb49b530daa17a3c18fea">llvm::object::ExportDirectoryEntryRef::getOrdinalBase</a>, <a href="/web-llvm/docs/api/classes/llvm/instrprofreaderindex/#aa91cc6c7a8c4c86a46bd7c76e0a01908">llvm::InstrProfReaderIndex&lt; HashTableImpl &gt;::getRecords</a>, <a href="/web-llvm/docs/api/classes/llvm/instrprofreaderindex/#a90eb11d63cde97e35fa0dd920561282a">llvm::InstrProfReaderIndex&lt; HashTableImpl &gt;::getRecords</a>, <a href="/web-llvm/docs/api/classes/llvm/instrprofreaderitaniumremapper/#ada5c91ffe6ce1366ef81b5cfea3c59fc">llvm::InstrProfReaderItaniumRemapper&lt; HashTableImpl &gt;::getRecords</a>, <a href="/web-llvm/docs/api/classes/llvm/object/baserelocref/#a8384ee5edfd6c329297f13ddef5b0411">llvm::object::BaseRelocRef::getRVA</a>, <a href="/web-llvm/docs/api/classes/llvm/object/coffobjectfile/#a8b53a54831e9ad9cb7fe4c06fef03c43">llvm::object::COFFObjectFile::getRvaAndSizeAsBytes</a>, <a href="/web-llvm/docs/api/classes/llvm/object/coffobjectfile/#ad35aa17b159b4fcc409db6230a7168a2">llvm::object::COFFObjectFile::getRvaPtr</a>, <a href="/web-llvm/docs/api/classes/llvm/object/elffile/#ac224640f48ef4ce451d49bbb1b68e9ca">llvm::object::ELFFile&lt; ELFT &gt;::getSectionAndRelocations</a>, <a href="/web-llvm/docs/api/classes/llvm/object/coffobjectfile/#ae94132813b134e3bca64884e6b6b3cd5">llvm::object::COFFObjectFile::getSectionContents</a>, <a href="/web-llvm/docs/api/classes/llvm/object/exportdirectoryentryref/#ae464313c6c88be306ef25e5a1493b906">llvm::object::ExportDirectoryEntryRef::getSymbolName</a>, <a href="/web-llvm/docs/api/classes/llvm/object/importedsymbolref/#a6c7690e5c614feb52bb05ba01b9d2f55">llvm::object::ImportedSymbolRef::getSymbolName</a>, <a href="/web-llvm/docs/api/classes/llvm/object/baserelocref/#a5351897341e0cf6015c6a6404466e09d">llvm::object::BaseRelocRef::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/jitlink/cofflinkgraphbuilder/#a366499688213f0b083c4653df7871b33">llvm::jitlink::COFFLinkGraphBuilder::graphifySections</a>, <a href="/web-llvm/docs/api/classes/llvm/jitlink/elflinkgraphbuilder/#af3ffb18516cfadbf9131f7d6b17fad71">llvm::jitlink::ELFLinkGraphBuilder&lt; ELFT &gt;::graphifySections</a>, <a href="/web-llvm/docs/api/classes/llvm/jitlink/cofflinkgraphbuilder/#a3f0c20754117c8457f8f5c469b8bd5e5">llvm::jitlink::COFFLinkGraphBuilder::graphifySymbols</a>, <a href="/web-llvm/docs/api/classes/llvm/jitlink/elflinkgraphbuilder/#a6cd958aefa56450fda2165d5a34886cf">llvm::jitlink::ELFLinkGraphBuilder&lt; ELFT &gt;::graphifySymbols</a>, <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobjcopy-cpp/#a1a0331e763d1ccb3e64db8de4d9791c8">handleArgs</a>, <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machoobjcopy-cpp/#a8fdf1b59602b3fa2d23286e468abb8a9">handleArgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcopy/coff/#aaa859579ac4adb9cbcebf0ddc98a085b">llvm::objcopy::coff::handleArgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcopy/wasm/#a42dbc5cc7c04f8d8738edf9699d75654">llvm::objcopy::wasm::handleArgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcopy/xcoff/#a7f486f006d0505392ba90851b51d3c99">llvm::objcopy::xcoff::handleArgs</a>, <a href="/web-llvm/docs/api/classes/llvm/anonymous-debuginfod-cpp-/streamedhttpresponsehandler/#ae3ec74d0da38e1e58d8c160075aaa17b">llvm::anonymous{Debuginfod.cpp}::StreamedHTTPResponseHandler::handleBodyChunk</a>, <a href="/web-llvm/docs/api/files/lib/lib/dwp/dwp-cpp/#a358c1febb02bfec774608e4761b27495">handleCompressedSection</a>, <a href="#a2c831eabfe62504c9cc0cc16e0799c44">handleErrors</a>, <a href="/web-llvm/docs/api/files/lib/lib/profiledata/lib/profiledata/coverage/coveragemapping-cpp/#a97d23912b5199996e91f0e6ecb977493">handleMaybeNoDataFoundError</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/lazyreexportsmanager/#a8e035d19beaac11de143eeeec21f646b">llvm::orc::LazyReexportsManager::handleRemoveResources</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/reoptimizelayer/#aacd0d657410c7bb991aeca1736fe82b3">llvm::orc::ReOptimizeLayer::handleRemoveResources</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9918786a0f26fa3b2f43f2a0fe626f7a">llvm::handleSection</a>, <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp/#a95e3a85203eeaf11c26b7161a4557934">hasInvalidBitcodeHeader</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/reoptimizelayer/#a1ca0a9a464229ad1ddfc9bae02574c6b">llvm::orc::ReOptimizeLayer::identity</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/coffobjectfile-cpp/#af41ee233472e39dff34fb42cccbc3121">ignoreStrippedErrors</a>, <a href="/web-llvm/docs/api/classes/llvm/object/archive/childfallibleiterator/#a6f288d7db159ee961152488ee73d263c">llvm::object::Archive::ChildFallibleIterator::inc</a>, <a href="/web-llvm/docs/api/classes/llvm/object/minidumpfile/memory64iterator/#ad39ec39419bdf09f905180dae5d93b8f">llvm::object::MinidumpFile::Memory64Iterator::inc</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/classic/dwarfstreamer/#a7472bfb367d052f75ef1e00fa660be70">llvm::dwarf_linker::classic::DwarfStreamer::init</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dwarfemitterimpl/#a66fa607c96a11d3a9e973d33e733ac37">llvm::dwarf_linker::parallel::DwarfEmitterImpl::init</a>, <a href="/web-llvm/docs/api/classes/llvm/object/binary/#a65f523352f45472b3b97f528a0bf5862">llvm::object::Binary::initContent</a>, <a href="/web-llvm/docs/api/classes/llvm/object/elfobjectfile/#abda9cbfc7a332979538e75a0d52f7fdc">llvm::object::ELFObjectFile&lt; ELFT &gt;::initContent</a>, <a href="/web-llvm/docs/api/classes/anonymous-lljit-cpp-/genericllvmirplatformsupport/#a58a2216ce778d24104e749383a9db34f">anonymous{LLJIT.cpp}::GenericLLVMIRPlatformSupport::initialize</a>, <a href="/web-llvm/docs/api/classes/anonymous-lljit-cpp-/inactiveplatformsupport/#a90736ad4fe74a2f1e39f967a61419326">anonymous{LLJIT.cpp}::InactivePlatformSupport::initialize</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/debugchecksumssubsectionref/#a5418329d4baefd380763f927734915ce">llvm::codeview::DebugChecksumsSubsectionRef::initialize</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/debugframedatasubsectionref/#a4be3e06f1f1b68440c1bb73617393f11">llvm::codeview::DebugFrameDataSubsectionRef::initialize</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/debuginlineelinessubsectionref/#ad817270ee6ed5e68b96642b3fddafa23">llvm::codeview::DebugInlineeLinesSubsectionRef::initialize</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/debuglinessubsectionref/#a5a4cbef7cf1ea9971675734047e5dde8">llvm::codeview::DebugLinesSubsectionRef::initialize</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/debugstringtablesubsectionref/#af981a356161e3b59a1f8a5bcaffaa2a4">llvm::codeview::DebugStringTableSubsectionRef::initialize</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/debugsubsectionrecord/#a2d6b180a6430d3f25c49ab5777d63d59">llvm::codeview::DebugSubsectionRecord::initialize</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/relocsectionwithsymtabbase/#a957eb6753673d0aa863ddb450a9fa424">llvm::objcopy::elf::RelocSectionWithSymtabBase&lt; SymTabType &gt;::initialize</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/section/#a3995c394cc393dfab7483f6a52f760ef">llvm::objcopy::elf::Section::initialize</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/sectionbase/#a31fcd24c8a2086eb186d3246a1bb4741">llvm::objcopy::elf::SectionBase::initialize</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/sectionindexsection/#ae4d186eb2f1484ef96545b5ba677d6b9">llvm::objcopy::elf::SectionIndexSection::initialize</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/symboltablesection/#ab5050a1b044f845cc9ce4a3d8b4597f5">llvm::objcopy::elf::SymbolTableSection::initialize</a>, <a href="/web-llvm/docs/api/classes/llvm/object/directx/signature/#a8f7cfbb475d2b81f3b1c99bb5e74e53d">llvm::object::DirectX::Signature::initialize</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/dbimoduledescriptor/#a8989add5b1e916623998fe78f3e003cb">llvm::pdb::DbiModuleDescriptor::initialize</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/dbimodulelist/#a29492b449dd27a4ee2e0d226cbb18079">llvm::pdb::DbiModuleList::initialize</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/pdbfilebuilder/#aa83f310901cbf7688e792d7b1dcbd58f">llvm::pdb::PDBFileBuilder::initialize</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/coffvcruntimebootstrapper/#ae44ab952b63e5c304c8ea532a7dd01b1">llvm::orc::COFFVCRuntimeBootstrapper::initializeStaticVCRuntime</a>, <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobject-cpp/#ad1b78430e677c5ac22430b0af1797615">initRelocations</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/basicelfbuilder/#ac573c6c02b8dea91c6c3831eac21b0ea">llvm::objcopy::elf::BasicELFBuilder::initSections</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvlogicalvisitor/#a68da2ce647c44cc62f321e770312a1ec">llvm::logicalview::LVLogicalVisitor::inlineSiteAnnotation</a>, <a href="/web-llvm/docs/api/classes/llvm/specialcaselist/matcher/#aeddf3282ade6b3f5d5bd98297ae8300a">llvm::SpecialCaseList::Matcher::insert</a>, <a href="/web-llvm/docs/api/classes/llvm/elfattributeparser/#a3e050c88f97b0583ca8a9ccb9df7f9af">llvm::ELFAttributeParser::integerAttribute</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6d6b4d712de56406cf2eb0387e61d380">llvm::interpretDecimal</a>, <a href="/web-llvm/docs/api/classes/llvm/object/exportdirectoryentryref/#a7bb9893cd1f48d6542cab3a80e093aa5">llvm::object::ExportDirectoryEntryRef::isForwarder</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#aa703d391c8bb63de65cf87f23ab451e0">llvm::object::isNotObjectErrorInvalidFileType</a>, <a href="/web-llvm/docs/api/classes/llvm/object/importedsymbolref/#afeac0ce65d178387472988e0bce40cca">llvm::object::ImportedSymbolRef::isOrdinal</a>, <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machoobjcopy-cpp/#a1d2a5be3f3c66e1c7670d490725af1d8">isValidMachOCannonicalName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a84874cd715d20419f7b484780ccddb9a">llvm::pdb::iterateModuleSubsections</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#affc029a083838b5b3e9c30c1facea952">llvm::pdb::iterateSymbolGroups</a>, <a href="/web-llvm/docs/api/classes/anonymous-elf-aarch64-cpp-/elfjitlinker-aarch64/#a98b89130c0705a77e1d728bf29c5f757">anonymous{ELF_aarch64.cpp}::ELFJITLinker_aarch64::JITLinker&lt; ELFJITLinker_aarch64 &gt;</a>, <a href="/web-llvm/docs/api/classes/anonymous-elf-loongarch-cpp-/elfjitlinker-loongarch/#a63ee231a7a6e2779894e6902ca3aacd6">anonymous{ELF_loongarch.cpp}::ELFJITLinker_loongarch::JITLinker&lt; ELFJITLinker_loongarch &gt;</a>, <a href="/web-llvm/docs/api/classes/llvm/simplebitstreamcursor/#a003287dcd6e4d73526b117b2709e2347">llvm::SimpleBitstreamCursor::JumpToBit</a>, <a href="/web-llvm/docs/api/classes/llvm/sys/fs/tempfile/#a218862a665465ddb719d8ac441e0b5ab">llvm::sys::fs::TempFile::keep</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/classic/dwarflinker/#af6caebcd7dc40dea28562fde4f260414">llvm::dwarf_linker::classic::DWARFLinker::link</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dwarflinkerimpl/#a42302ab883ef8ec7e51b00701d626ce4">llvm::dwarf_linker::parallel::DWARFLinkerImpl::link</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/dwarflinkerimpl/linkcontext/#ad06d8aa0d7980827ad6f0a8543657f73">llvm::dwarf_linker::parallel::DWARFLinkerImpl::LinkContext::link</a>, <a href="/web-llvm/docs/api/structs/llvm/remarks/remarklinker/#a2f0b07de873627d24a364adbc61b0da3">llvm::remarks::RemarkLinker::link</a>, <a href="/web-llvm/docs/api/structs/llvm/remarks/remarklinker/#ac548aeb7853ce7d7cd2a3b33fb761d1b">llvm::remarks::RemarkLinker::link</a>, <a href="/web-llvm/docs/api/classes/anonymous-irmover-cpp-/typemapty/#a9458e9521315cb278dee23c71634b48e">anonymous{IRMover.cpp}::TypeMapTy::linkDefinedTypeBodies</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/lljit/#aa7573528896e709770c5e31bdf597555">llvm::orc::LLJIT::linkStaticLibraryInto</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/lljit/#aaa681b188079626ba7d773d29128e3bf">llvm::orc::LLJIT::linkStaticLibraryInto</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/targetprocess/jitloadergdb-h/#aa179ff9a1e20ecc81138aaca91a0cfc9">llvm_orc_registerJITLoaderGDBAllocAction</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/targetprocess/jitloadergdb-h/#a0bce71a267532196975543a4ead461c1">llvm_orc_registerJITLoaderGDBWrapper</a>, <a href="/web-llvm/docs/api/classes/llvm/object/resourcesectionref/#a778c6e8a9d2903a6c5b0501015acd0e2">llvm::object::ResourceSectionRef::load</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/hashtable/#a0d7b4512480e721249639c7fa64636ce">llvm::pdb::const_iterator&lt; SrcHeaderBlockEntry &gt;::load</a>, <a href="/web-llvm/docs/api/files/lib/lib/textapi/lib/textapi/binaryreader/dylibreader-cpp/#a29e38c60d8641542f9d5e6fb9a282831">load</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/staticlibrarydefinitiongenerator/#a16a84f60ff615b07935df943c5f84a5e">llvm::orc::StaticLibraryDefinitionGenerator::loadAllObjectFileMembers</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/dwarflinkerimpl/linkcontext/#a21dc5ae67ffaf38250ef5b5d377b5358">llvm::dwarf_linker::parallel::DWARFLinkerImpl::LinkContext::loadClangModule</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/dia/diasession-cpp/#a79fc10fcf921644e9160676b6cbb6e81">LoadDIA</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-trace-cpp-/#a6b4f89ac434c992939934e78f19cd33e">anonymous{Trace.cpp}::loadFDRLog</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvbinaryreader/#ad1c77f840dadc1ffb03432c9e688e4c6">llvm::logicalview::LVBinaryReader::loadGenericTargetInfo</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-trace-cpp-/#ab12a9d7c65de7b4e040ca540157bf373">anonymous{Trace.cpp}::loadNaiveFormatLog</a>, <a href="/web-llvm/docs/api/files/lib/lib/xray/instrumentationmap-cpp/#a39d3991edccf18f18b801032e9ab89b5">loadObj</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/dbistream-cpp/#a0b78b1abf96c2d0e83ad6a5e5466ba59">loadSectionContribs</a>, <a href="/web-llvm/docs/api/files/lib/lib/xray/instrumentationmap-cpp/#a740748c1b9bf73c9456e1d823f34c5f2">loadYAML</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af73b4fcac77298355025a0e5975edcf0">llvm::localCache</a>, <a href="/web-llvm/docs/api/structs/llvm/gsym/inlineinfo/#a6f764edf4bf576f4e243188eb8fa5e0c">llvm::gsym::InlineInfo::lookup</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/executionsession/#adcd2edb47f46a28037d9f738f0cd1aa8">llvm::orc::ExecutionSession::lookup</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/executionsession/#a9260560ad3aaa612b92cff4bccd3c223">llvm::orc::ExecutionSession::lookup</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a578c0003fa8d6a75ea0e805e20104439">llvm::orc::lookupAndRecordAddrs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a8099b2810ee3dbc4cb1a1efdafcb4dfb">llvm::orc::lookupAndRecordAddrs</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/executionsession/#a081a578f073d014fe2b1ba2c15b8b5c2">llvm::orc::ExecutionSession::lookupFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/executionsession/#a432a464dcfc79515467f0ddefd78fc83">llvm::orc::ExecutionSession::lookupFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/platform/#aded9cbc2f7fa64fbbdf4f5ce8f826dd5">llvm::orc::Platform::lookupInitSymbols</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/platform/#a5f5de33429dae751bbf618940ff67e01">llvm::orc::Platform::lookupInitSymbolsAsync</a>, <a href="/web-llvm/docs/api/classes/anonymous-dxiloplowering-cpp-/oplowerer/#a4275af81cdeb1801deeae02ea2a0fb3b">anonymous{DXILOpLowering.cpp}::OpLowerer::lowerBufferStore</a>, <a href="/web-llvm/docs/api/classes/anonymous-dxiloplowering-cpp-/oplowerer/#a2fea5f04ff43df5b1fc0a4304b7362c2">anonymous{DXILOpLowering.cpp}::OpLowerer::lowerCtpopToCountBits</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/aarch64/#a92e5f360eac04874168e30f0df2bc5bb">llvm::jitlink::aarch64::lowerPointer64AuthEdgesToSigningFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-dxiloplowering-cpp-/oplowerer/#a30b2570b289c65776a16666bd087c988">anonymous{DXILOpLowering.cpp}::OpLowerer::lowerRawBufferLoad</a>, <a href="/web-llvm/docs/api/classes/anonymous-dxiloplowering-cpp-/oplowerer/#a4a42541fb66ae32c0c9f8deede2cc21e">anonymous{DXILOpLowering.cpp}::OpLowerer::lowerToBindAndAnnotateHandle</a>, <a href="/web-llvm/docs/api/classes/anonymous-dxiloplowering-cpp-/oplowerer/#a230768916fc2abaf5fb0f563654d2cc8">anonymous{DXILOpLowering.cpp}::OpLowerer::lowerToCreateHandle</a>, <a href="/web-llvm/docs/api/classes/anonymous-dxiloplowering-cpp-/oplowerer/#a70502c89919d53c74320c78b78d5c282">anonymous{DXILOpLowering.cpp}::OpLowerer::lowerTypedBufferLoad</a>, <a href="/web-llvm/docs/api/classes/anonymous-dxiloplowering-cpp-/oplowerer/#ab10e6ab2669a5c752426570de655e7ce">anonymous{DXILOpLowering.cpp}::OpLowerer::lowerUpdateCounter</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machouniversalbinary/#a66ced5c57cafe11823df6917a866b17f">llvm::object::MachOUniversalBinary::MachOUniversalBinary</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/shared/detail/resultdeserializer-8112f182ad5a7941abf9a1219f2005f7/#a593e21c13c3b9ca17b6202e8fcc70d4c">llvm::orc::shared::detail::ResultDeserializer&lt; SPSError, Error &gt;::makeValue</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/codeviewrecordio/#ae835f4af45721bc129de5e1447cfa4a6">llvm::codeview::CodeViewRecordIO::mapByteVectorTail</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/codeviewrecordio/#a97074acd3a969b0eb7a6a730c5a1c8f3">llvm::codeview::CodeViewRecordIO::mapByteVectorTail</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/codeviewrecordio/#a65d7ff22f925eb1f4893ea7634b7bf59">llvm::codeview::CodeViewRecordIO::mapEncodedInteger</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/codeviewrecordio/#ad866e9f32981e8b9748dc09079ec83ba">llvm::codeview::CodeViewRecordIO::mapEncodedInteger</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/codeviewrecordio/#afc358a57ed79d1e05a866b061027e61b">llvm::codeview::CodeViewRecordIO::mapEncodedInteger</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/codeviewrecordio/#ad7bb1a062512c8047c87486bd98481f2">llvm::codeview::CodeViewRecordIO::mapEnum</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/codeviewrecordio/#a62ff5ad430418e75c001811d0c3a976c">llvm::codeview::CodeViewRecordIO::mapGuid</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/codeviewrecordio/#a4d847b29ed4dbac6e63e1fb520b1f93c">llvm::codeview::CodeViewRecordIO::mapInteger</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/codeviewrecordio/#a5d36269fb288350b629675233d6bdf16">llvm::codeview::CodeViewRecordIO::mapInteger</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/symbolrecordmapping-cpp/#a024855fc9193609b0d2f21c414c99f16">mapLocalVariableAddrRange</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/typerecordmapping-cpp/#aee6196bb67ae710bbbd44101ea42fc62">mapNameAndUniqueName</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/codeviewrecordio/#ab5549dc57b435bb5b25ec67aa5785c54">llvm::codeview::CodeViewRecordIO::mapObject</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/codeviewrecordio/#aa488397718059fddf9d4e699e2de4678">llvm::codeview::CodeViewRecordIO::mapStringZ</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/codeviewrecordio/#a693b6f70fcd9bc58db0af0591dc16b83">llvm::codeview::CodeViewRecordIO::mapStringZVectorZ</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/codeviewrecordio/#a4d354d18453c112eec47c84ef03665e6">llvm::codeview::CodeViewRecordIO::mapVectorN</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/codeviewrecordio/#a433c3f29e1057eed4db6a888152dfc96">llvm::codeview::CodeViewRecordIO::mapVectorTail</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#a865b5baa2754c1ddeb497d1d2cbfbbe3">llvm::jitlink::markAllSymbolsLive</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/coff/object/#ae20d61d1b09ad5ca69701afe73043675">llvm::objcopy::coff::Object::markSymbols</a>, <a href="/web-llvm/docs/api/classes/llvm/pattern/#a23cdde8b9bdd40fd4a93d3635ca77dc6">llvm::Pattern::match</a>, <a href="/web-llvm/docs/api/classes/anonymous-bitcodereader-cpp-/bitcodereader/#a9154b11bdab240adc9c8acd18cf89717">anonymous{BitcodeReader.cpp}::BitcodeReader::materialize</a>, <a href="/web-llvm/docs/api/classes/anonymous-bitcodereader-cpp-/bitcodereader/#aa1cc88efb5daea0ae73b93eb7bc1ebd7">anonymous{BitcodeReader.cpp}::BitcodeReader::materializeForwardReferencedFunctions</a>, <a href="/web-llvm/docs/api/classes/anonymous-bitcodereader-cpp-/bitcodereader/#aefaf2c952edc95af7870970731295b45">anonymous{BitcodeReader.cpp}::BitcodeReader::materializeMetadata</a>, <a href="/web-llvm/docs/api/classes/anonymous-bitcodereader-cpp-/bitcodereader/#a9f4458f3a19b697e8e24c4ebd319b35b">anonymous{BitcodeReader.cpp}::BitcodeReader::materializeModule</a>, <a href="/web-llvm/docs/api/classes/llvm/codegendatareader/#ad41848e26234890d2d908a09f6709022">llvm::CodeGenDataReader::mergeFromObjectFile</a>, <a href="/web-llvm/docs/api/classes/llvm/instrprofwriter/#aa3bfb53fa787d3dbea88bc35f498e461">llvm::InstrProfWriter::mergeProfileKind</a>, <a href="/web-llvm/docs/api/classes/llvm/jitlink/jitlinkcontext/#a311bd3a401f79170b604b35e9b7b1613">llvm::jitlink::JITLinkContext::modifyPassConfig</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/debugobjectmanagerplugin/#abf15a05cfd44aa92db5db5251a6f3631">llvm::orc::DebugObjectManagerPlugin::modifyPassConfig</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/linkgraphlinkinglayer/jitlinkctx/#a9244565368ee4c5e1c2666b63b6af76d">llvm::orc::LinkGraphLinkingLayer::JITLinkCtx::modifyPassConfig</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/perfsupportplugin/#a0b1cb2049314feb0a29760c548a604af">llvm::orc::PerfSupportPlugin::modifyPassConfig</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/vtunesupportplugin/#a853290f0b4ae904b8ab68e6a06f8bab9">llvm::orc::VTuneSupportPlugin::modifyPassConfig</a>, <a href="/web-llvm/docs/api/classes/llvm/object/resourceentryref/#a456f2983ce9a68d7c4ae2728c2b5890f">llvm::object::ResourceEntryRef::moveNext</a>, <a href="/web-llvm/docs/api/classes/anonymous-lljit-cpp-/genericllvmirplatformsupport/#a7a6c3b4432af35ad1b0c9843105f5e4d">anonymous{LLJIT.cpp}::GenericLLVMIRPlatformSupport::notifyAdding</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/coffplatform/#a6ceb8793145f063bcb5e204c1251649e">llvm::orc::COFFPlatform::notifyAdding</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/elfnixplatform/#a454ad1d1eb28a3dfc9ed6383417df7bb">llvm::orc::ELFNixPlatform::notifyAdding</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/machoplatform/#a9933be5a0082912958e7328de0ca90e1">llvm::orc::MachOPlatform::notifyAdding</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/debugobjectmanagerplugin/#a778eb8f8c5516bfed164b60b1594d632">llvm::orc::DebugObjectManagerPlugin::notifyEmitted</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/ehframeregistrationplugin/#a7042ba17af30d341e89ed03d29324257">llvm::orc::EHFrameRegistrationPlugin::notifyEmitted</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/linkgraphlinkinglayer/jitlinkctx/#afd274aecaf8f78e9040be59dfe07874d">llvm::orc::LinkGraphLinkingLayer::JITLinkCtx::notifyEmitted</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/linkgraphlinkinglayer/plugin/#a2464ce56d0c64d6a188df9444001df7b">llvm::orc::LinkGraphLinkingLayer::Plugin::notifyEmitted</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/unwindinforegistrationplugin/#acb6c85331025888f0a7f7e68e4be6ba0">llvm::orc::UnwindInfoRegistrationPlugin::notifyEmitted</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/vtunesupportplugin/#a84d69d4d9a1eebe32eda1d8e7ed125cd">llvm::orc::VTuneSupportPlugin::notifyEmitted</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/debuginfopreservationplugin/#a1411630701e74f265f046bea00466007">llvm::orc::DebugInfoPreservationPlugin::notifyFailed</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/debugobjectmanagerplugin/#a5a24c1efd3e1604d378e7a1482bb6de3">llvm::orc::DebugObjectManagerPlugin::notifyFailed</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/ehframeregistrationplugin/#a89a35201fcc72e8ed52b1d47e3282169">llvm::orc::EHFrameRegistrationPlugin::notifyFailed</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/gdbjitdebuginforegistrationplugin/#af69a64d23d5294d5dcf5f5c51f72167f">llvm::orc::GDBJITDebugInfoRegistrationPlugin::notifyFailed</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/jitlinkreentrytrampolines/trampolineaddrscraperplugin/#a247dc8126abc6d5e6385ce2514d5810b">llvm::orc::JITLinkReentryTrampolines::TrampolineAddrScraperPlugin::notifyFailed</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/lazyobjectlinkinglayer/renamerplugin/#a56d98f9ca94fdd8f08790709d2798b35">llvm::orc::LazyObjectLinkingLayer::RenamerPlugin::notifyFailed</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/lazyreexportsmanager/plugin/#a8f62618df8074add58940fbdbd92a63a">llvm::orc::LazyReexportsManager::Plugin::notifyFailed</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/perfsupportplugin/#a05d49b9d98223cd33f875e338cf4b633">llvm::orc::PerfSupportPlugin::notifyFailed</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/unwindinforegistrationplugin/#ac2edc4249875e6b859f2e49b3d15a064">llvm::orc::UnwindInfoRegistrationPlugin::notifyFailed</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/vtunesupportplugin/#ab8634e926830f26883584017fe3f38d6">llvm::orc::VTuneSupportPlugin::notifyFailed</a>, <a href="/web-llvm/docs/api/classes/anonymous-lljit-cpp-/genericllvmirplatform/#a52966f88ef7682b8726e4f73ccf94941">anonymous{LLJIT.cpp}::GenericLLVMIRPlatform::notifyRemoving</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/debuginfopreservationplugin/#aa740956c7349774f16d0770061e88258">llvm::orc::DebugInfoPreservationPlugin::notifyRemovingResources</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/debugobjectmanagerplugin/#a08990f110a9a374bbac36366d6d8e320">llvm::orc::DebugObjectManagerPlugin::notifyRemovingResources</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/ehframeregistrationplugin/#ae7a38c2dad420b5d616cccc7625d68f5">llvm::orc::EHFrameRegistrationPlugin::notifyRemovingResources</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/gdbjitdebuginforegistrationplugin/#adb5825b90b4b59fa09cf30e42f294ddf">llvm::orc::GDBJITDebugInfoRegistrationPlugin::notifyRemovingResources</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/jitlinkreentrytrampolines/trampolineaddrscraperplugin/#a513872d058950efe1e372af8c7afdd17">llvm::orc::JITLinkReentryTrampolines::TrampolineAddrScraperPlugin::notifyRemovingResources</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/lazyobjectlinkinglayer/renamerplugin/#a6e4fa307ef292cfd88502145287f86c1">llvm::orc::LazyObjectLinkingLayer::RenamerPlugin::notifyRemovingResources</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/lazyreexportsmanager/plugin/#aa0c69d24578488218ea956a43854d301">llvm::orc::LazyReexportsManager::Plugin::notifyRemovingResources</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/perfsupportplugin/#ab05b5114b6398ef9309e31c2e662482e">llvm::orc::PerfSupportPlugin::notifyRemovingResources</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/unwindinforegistrationplugin/#a86f033479e153b8a7cfa73a61a3fbe28">llvm::orc::UnwindInfoRegistrationPlugin::notifyRemovingResources</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/vtunesupportplugin/#ae27797c86bd5fb476f34cc12bf4c2507">llvm::orc::VTuneSupportPlugin::notifyRemovingResources</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/lazycallthroughmanager/#a3906480964f9300b037da5786615559c">llvm::orc::LazyCallThroughManager::notifyResolved</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/linkgraphlinkinglayer/jitlinkctx/#a569ab99e0391c055c321e1088a303335">llvm::orc::LinkGraphLinkingLayer::JITLinkCtx::notifyResolved</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/simplelazyreexportsspeculator/#a0c161644231ad89726068271270734dd">llvm::orc::SimpleLazyReexportsSpeculator::onLazyReexportsRemoved</a>, <a href="/web-llvm/docs/api/classes/anonymous-coff-x86-64-cpp-/cofflinkgraphlowering-x86-64/#a4c3ad7e3022968cc44c435a1afa9c0a0">anonymous{COFF_x86_64.cpp}::COFFLinkGraphLowering_x86_64::operator()</a>, <a href="/web-llvm/docs/api/classes/anonymous-lljit-cpp-/globalctordtorscraper/#a5f8ea04329212b479fa473a5b324153c">anonymous{LLJIT.cpp}::GlobalCtorDtorScraper::operator()</a>, <a href="/web-llvm/docs/api/structs/anonymous-symbolrecordmapping-cpp-/mapgap/#a643b48d887def1d42e3e35ef38bf209c">anonymous{SymbolRecordMapping.cpp}::MapGap::operator()</a>, <a href="/web-llvm/docs/api/structs/anonymous-typerecordmapping-cpp-/maponemethodrecord/#a8512de7a16f0f4a4b44a94bd615e1c31">anonymous{TypeRecordMapping.cpp}::MapOneMethodRecord::operator()</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/linecolumnextractor/#ac30e456e648c6aa3b5de74279adbb0d5">llvm::codeview::LineColumnExtractor::operator()</a>, <a href="/web-llvm/docs/api/classes/llvm/jitlink/defineexternalsectionstartandendsymbols/#a9f3b33060063a6d8741d7fc489c68ab1">llvm::jitlink::DefineExternalSectionStartAndEndSymbols&lt; SymbolIdentifierFunction &gt;::operator()</a>, <a href="/web-llvm/docs/api/classes/llvm/jitlink/dwarfrecordsectionsplitter/#a9f2000bb8938fc279ffdff87d8136807">llvm::jitlink::DWARFRecordSectionSplitter::operator()</a>, <a href="/web-llvm/docs/api/classes/llvm/jitlink/ehframeedgefixer/#a2125616450a5d6ec41ab7f8f66abe40e">llvm::jitlink::EHFrameEdgeFixer::operator()</a>, <a href="/web-llvm/docs/api/classes/llvm/jitlink/ehframenullterminator/#a12449a776d8c693c8e57f3ddda44aeb5">llvm::jitlink::EHFrameNullTerminator::operator()</a>, <a href="/web-llvm/docs/api/classes/llvm/jitlink/sehframekeepalivepass/#a842a3aaddc602ed3b8d862d9738ef06e">llvm::jitlink::SEHFrameKeepAlivePass::operator()</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/forceloadmachoarchivemembers/#aafbc2404a509204e5983e140d1038581">llvm::orc::ForceLoadMachOArchiveMembers::operator()</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/loadandlinkdynlibrary/#a4c217254abc9687da4cb2c93308f09a7">llvm::orc::LoadAndLinkDynLibrary::operator()</a>, <a href="/web-llvm/docs/api/structs/llvm/varstreamarrayextractor/#a4e7a87abc173694df4fd4f9255636528">llvm::VarStreamArrayExtractor&lt; T &gt;::operator()</a>, <a href="/web-llvm/docs/api/structs/llvm/varstreamarrayextractor-587952ed1570bd373449cde4c653eb60/#a553b02696052cd684bfb05bbcca1e298">llvm::VarStreamArrayExtractor&lt; codeview::CVRecord&lt; Kind &gt; &gt;::operator()</a>, <a href="/web-llvm/docs/api/structs/llvm/varstreamarrayextractor-aa4cf4a73737d16d115dea80ff681a08/#a5245c9fad1a0cc1f3e4e9b1106fe9dc1">llvm::VarStreamArrayExtractor&lt; codeview::DebugSubsectionRecord &gt;::operator()</a>, <a href="/web-llvm/docs/api/structs/llvm/varstreamarrayextractor-4459a4f1e1f6940150dfae71388b4626/#a598d96531e2c247dfaa1b7ce4ca2c637">llvm::VarStreamArrayExtractor&lt; pdb::DbiModuleDescriptor &gt;::operator()</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/i386/#a877b3d728be6b7084aef27f92242f8bf">llvm::jitlink::i386::optimizeGOTAndStubAccesses</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/x86-64/#ac61404d428edea90fb2c5b180daf5361">llvm::jitlink::x86_64::optimizeGOTAndStubAccesses</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ifs/#afc18bf711d24e927808471ad016f02ec">llvm::ifs::overrideIFSTarget</a>, <a href="/web-llvm/docs/api/classes/llvm/binarystreamwriter/#afc0de5f4d1abba3ccf0d201137be8c6d">llvm::BinaryStreamWriter::padToAlignment</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae6c45e3e95dd28727729bc0b62b2434a">llvm::parallelForEachError</a>, <a href="/web-llvm/docs/api/classes/llvm/btfparser/#a4c7c5e28bb5767c6be05394c38ab0d21">llvm::BTFParser::parse</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugabbrev/#a3707401ae8d1122e7e114e166bbccf4a">llvm::DWARFDebugAbbrev::parse</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugframe/#a4f2d81fc8d21674863d5a753df3eed54">llvm::DWARFDebugFrame::parse</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarfdebugline/linetable/#a49eb2522e1fc6988c75f9936c3061bb6">llvm::DWARFDebugLine::LineTable::parse</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarfdebugline/prologue/#a5d63a698aa61a9d04d1826b1f91a0b43">llvm::DWARFDebugLine::Prologue::parse</a>, <a href="/web-llvm/docs/api/classes/llvm/object/directx/psvruntimeinfo/#ac30f90a499bf2baa821b2838a784b86b">llvm::object::DirectX::PSVRuntimeInfo::parse</a>, <a href="/web-llvm/docs/api/classes/llvm/object/windowsresourceparser/#aedf8841ba3ea93fe05f71cf444cc18fd">llvm::object::WindowsResourceParser::parse</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/linetable-cpp/#a45e99fb329714d8911cb5e116eb8a3bc">parse</a>, <a href="/web-llvm/docs/api/classes/llvm/passbuilder/#a1d4e2a477b2b896adfdec5e55638b725">llvm::PassBuilder::parseAAPipeline</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/datalayout-cpp/#a221bcb219fc93988419350acf03ac23d">parseAddrSpace</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/datalayout-cpp/#a352f4ca101ae014677dda708b07b98f7">parseAlignment</a>, <a href="/web-llvm/docs/api/classes/llvm/elfattributeparser/#aeb88a873af45ca9f6207336e0b468856">llvm::ELFAttributeParser::parseAttributeList</a>, <a href="/web-llvm/docs/api/files/lib/lib/remarks/bitstreamremarkparser-cpp/#a9e3af87f6a7494ee71b0cdbf0c4d153c">parseBlock</a>, <a href="/web-llvm/docs/api/structs/llvm/remarks/bitstreamparserhelper/#aef087e7464b791f0ab26613736065520">llvm::remarks::BitstreamParserHelper::parseBlockInfoBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp/#a1d797aa90eeef9897ebdcf1c8332441e">parseBuildVersionCommand</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/pdbfile/#aa8016724ba063de217ed1ccf4ddc095d">llvm::pdb::PDBFile::parseFileHeaders</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aca926e51a519a29293e7428001c79cef">llvm::parseInfoSectionUnitHeader</a>, <a href="/web-llvm/docs/api/classes/metadataloader/metadataloaderimpl/#ab5d5351419b40a9f891e4506bc2cae29">llvm::MetadataLoader::MetadataLoaderImpl::parseMetadata</a>, <a href="/web-llvm/docs/api/classes/metadataloader/metadataloaderimpl/#a4a81e1117a068de8d409b76e45c3e494">llvm::MetadataLoader::MetadataLoaderImpl::parseMetadataAttachment</a>, <a href="/web-llvm/docs/api/classes/metadataloader/metadataloaderimpl/#a71350293eab7be254484af9024a93da4">llvm::MetadataLoader::MetadataLoaderImpl::parseMetadataKinds</a>, <a href="/web-llvm/docs/api/classes/anonymous-bitcodereader-cpp-/modulesummaryindexbitcodereader/#ae9f86888a27590c2d447d2f98b5f7cf8">anonymous{BitcodeReader.cpp}::ModuleSummaryIndexBitcodeReader::parseModule</a>, <a href="/web-llvm/docs/api/classes/llvm/passbuilder/#a581197bc2dbbef326892f5ff08761f54">llvm::PassBuilder::parsePassPipeline</a>, <a href="/web-llvm/docs/api/classes/llvm/passbuilder/#ac3231081094bc7fdda779c6b73f9f706">llvm::PassBuilder::parsePassPipeline</a>, <a href="/web-llvm/docs/api/classes/llvm/passbuilder/#a2c60ec47f90dce41d2bbc71a913c696e">llvm::PassBuilder::parsePassPipeline</a>, <a href="/web-llvm/docs/api/classes/llvm/passbuilder/#a088814462db14cd89651bd90f390e30d">llvm::PassBuilder::parsePassPipeline</a>, <a href="/web-llvm/docs/api/classes/llvm/passbuilder/#a9ca0e57e6445ab2fe568e53ba29cc0fd">llvm::PassBuilder::parsePassPipeline</a>, <a href="/web-llvm/docs/api/files/lib/lib/remarks/bitstreamremarkparser-cpp/#a614e714a8963e8f854ecac210dde3125">parseRecord</a>, <a href="/web-llvm/docs/api/files/lib/lib/remarks/bitstreamremarkparser-cpp/#a384d242ae8d66e4ea84344784426e3a7">parseRecord</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsectionmacho/#a1ea0b527a25e96bb74c8217704b22a07">llvm::MCSectionMachO::ParseSectionSpecifier</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp/#a488ef72cdaf48278d8a1117a6833bad2">parseSegmentLoadCommand</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/datalayout-cpp/#a0106e369078637cf051ef66c829ad540">parseSize</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/pdbfile/#a0ccdac4b6ec6b7a67a2dc7e3bd83985b">llvm::pdb::PDBFile::parseStreamData</a>, <a href="/web-llvm/docs/api/classes/llvm/elfattributeparser/#abf992f403d584a1d6b24de79a3a658b5">llvm::ELFAttributeParser::parseStringAttribute</a>, <a href="/web-llvm/docs/api/classes/llvm/elfattributeparser/#a02d8a789e50e085fa66aac9180bb03f3">llvm::ELFAttributeParser::parseSubsection</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdebugline-cpp/#a28f2b75ae3485678ba907fd613f90317">parseV2DirFileTables</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdebugline-cpp/#a132fc2d4f9a680228706747b8608e269">parseV5DirFileTables</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdebugline-cpp/#a3c5f98145259c144797136c9e4d29af8">parseV5EntryFormat</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ifs/#af5cd925f6f6a963703c1fe6eb3335973">llvm::ifs::populateDynamic</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmacho/#ab606ca40d5870295837712aa2056f90e">llvm::RuntimeDyldMachO::populateIndirectSymbolPointersSection</a>, <a href="/web-llvm/docs/api/classes/llvm/instrprofreaderitaniumremapper/#a9b37c058778bd80dba88bef8fdad0802">llvm::InstrProfReaderItaniumRemapper&lt; HashTableImpl &gt;::populateRemappings</a>, <a href="/web-llvm/docs/api/classes/llvm/instrprofreaderremapper/#aed1ba031efeafd752d0336dba6d5de00">llvm::InstrProfReaderRemapper::populateRemappings</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ifs/#adfe6be0993129c864dc3047bd6dba156">llvm::ifs::populateSymbols</a>, <a href="/web-llvm/docs/api/classes/llvm/jitlink/elflinkgraphbuilder/#a634163eb7e686efd2bfb3cead4d5e362">llvm::jitlink::ELFLinkGraphBuilder&lt; ELFT &gt;::prepare</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/lljitbuilderstate/#a18ff6139760982f4640e0ea26da81ba4">llvm::orc::LLJITBuilderState::prepareForConstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/lllazyjitbuilderstate/#abc786ffa7a26833214aa650dea65e3a7">llvm::orc::LLLazyJITBuilderState::prepareForConstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/jitlink/compactunwindmanager/#ab91679cd4a3a613219f1835a2d25c3f1">llvm::jitlink::CompactUnwindManager&lt; CURecTraits &gt;::prepareForPrune</a>, <a href="/web-llvm/docs/api/classes/anonymous-debuggersupportplugin-cpp-/machodebugobjectsynthesizerbase/#a2e160e39a23517dff688b6bb5dfa1c06">anonymous{DebuggerSupportPlugin.cpp}::MachODebugObjectSynthesizerBase::preserveDebugSections</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a25efabd51a9526153bfc75c408671231">llvm::orc::preserveDebugSections</a>, <a href="/web-llvm/docs/api/classes/llvm/indexedinstrprofreader/#a1c1e6d976a2d84bb1967a42fa8c33896">llvm::IndexedInstrProfReader::printBinaryIds</a>, <a href="/web-llvm/docs/api/classes/llvm/rawinstrprofreader/#a102d6ce9027a0d9ba325417ce02d49ec">llvm::RawInstrProfReader&lt; IntPtrT &gt;::printBinaryIds</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvreader/#ae8f1aeb4ef8575cbc64f67508effbbb2">llvm::logicalview::LVReader::printScopes</a>, <a href="/web-llvm/docs/api/classes/llvm/object/coffimportfile/#ac68b1045f86cba91c3a222ea936595c5">llvm::object::COFFImportFile::printSymbolName</a>, <a href="/web-llvm/docs/api/classes/llvm/object/irobjectfile/#a2584de961c69042c7afb892ad5f76b1a">llvm::object::IRObjectFile::printSymbolName</a>, <a href="/web-llvm/docs/api/classes/llvm/object/objectfile/#a50eb735d1fb3b6f5cc988c6d7caf5aa5">llvm::object::ObjectFile::printSymbolName</a>, <a href="/web-llvm/docs/api/classes/llvm/object/tapifile/#adca4e4eb68596005a1a79bcd3ab94a8f">llvm::object::TapiFile::printSymbolName</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvreaderhandler/#a9e264d08d01c80cc51982befc59eb6c3">llvm::logicalview::LVReaderHandler::process</a>, <a href="/web-llvm/docs/api/classes/llvm/jitlink/compactunwindmanager/#ad17b2d982b9548edd3e533387aa216f9">llvm::jitlink::CompactUnwindManager&lt; CURecTraits &gt;::processAndReserveUnwindInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machoobjcopy-cpp/#a14dfead54615906a608b43ce6881920b">processLoadCommands</a>, <a href="/web-llvm/docs/api/classes/anonymous-utility-cpp-/kernelinforeader/#aa4be56491fd1f1bfc2d12285da64e4a0">anonymous{Utility.cpp}::KernelInfoReader::processNote</a>, <a href="/web-llvm/docs/api/files/lib/lib/remarks/bitstreamremarkparser-cpp/#a37c014ff1e40aad67d394566e65800bf">processRemarkVersion</a>, <a href="/web-llvm/docs/api/files/lib/lib/remarks/bitstreamremarkparser-cpp/#aab380b488629f55df87400a566043f37">processStrTab</a>, <a href="/web-llvm/docs/api/classes/llvm/coverage/rawcoveragemappingreader/#a6f328f5f8d7e388b876dc55edd2d7da8">llvm::coverage::RawCoverageMappingReader::read</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/gsihashtable/#a1c16e5706517a32b6050effc1cd6a7c6">llvm::pdb::GSIHashTable::read</a>, <a href="/web-llvm/docs/api/classes/llvm/symbolremappingreader/#a6b15e282ce11e66f93f7b1a22407547b">llvm::SymbolRemappingReader::read</a>, <a href="/web-llvm/docs/api/classes/llvm/textcodegendatareader/#a6a6f3695c97c301eee0369ec5e669c61">llvm::TextCodeGenDataReader::read</a>, <a href="/web-llvm/docs/api/classes/llvm/bitstreamcursor/#a18edc8cef7ae17b03b6d4f3ad2cda8b3">llvm::BitstreamCursor::ReadAbbrevRecord</a>, <a href="/web-llvm/docs/api/classes/llvm/binarystreamreader/#ab88a8b3835c1028f8fd6c2b23f396d30">llvm::BinaryStreamReader::readArray</a>, <a href="/web-llvm/docs/api/classes/llvm/binarystreamreader/#a24cb794c8858cc968924505f3a5ac37b">llvm::BinaryStreamReader::readArray</a>, <a href="/web-llvm/docs/api/classes/llvm/binarystreamreader/#adb4cfdc89c66954507c06d25ec1e267f">llvm::BinaryStreamReader::readArray</a>, <a href="/web-llvm/docs/api/classes/llvm/rawinstrprofreader/#a95a0de73ba5b9cfb2dd208d67fcbbdb8">llvm::RawInstrProfReader&lt; IntPtrT &gt;::readBinaryIds</a>, <a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprofreader-cpp/#aa883a589f91024d0a09d1b3c1821ec85">readBinaryIdsInternal</a>, <a href="/web-llvm/docs/api/classes/anonymous-bitcodereader-cpp-/bitcodereaderbase/#ad04f7d6a08ad25b673e16a64825f640c">anonymous{BitcodeReader.cpp}::BitcodeReaderBase::readBlockInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/appendingbinarybytestream/#acbb5be14a8102feef6f84e1d2adfaeb7">llvm::AppendingBinaryByteStream::readBytes</a>, <a href="/web-llvm/docs/api/classes/llvm/binarybytestream/#a4e42d67aeb85b158d2954d3eab60fdd6">llvm::BinaryByteStream::readBytes</a>, <a href="/web-llvm/docs/api/classes/llvm/binaryitemstream/#a6f2c735b75cbf7437533bbe15c76563a">llvm::BinaryItemStream&lt; T, Traits &gt;::readBytes</a>, <a href="/web-llvm/docs/api/classes/llvm/binarystreamreader/#a2d56063bcd6039c9372e485e609cf692">llvm::BinaryStreamReader::readBytes</a>, <a href="/web-llvm/docs/api/classes/llvm/msf/mappedblockstream/#a1a421432438b984e24590ea8169dc589">llvm::msf::MappedBlockStream::readBytes</a>, <a href="/web-llvm/docs/api/files/lib/lib/profiledata/lib/profiledata/coverage/coveragemappingreader-cpp/#a10b27eac23635b8f40370fe8a4d19967">readCoverageMappingData</a>, <a href="/web-llvm/docs/api/classes/llvm/binarystreamreader/#a1cbc5251f13ad42510760ed61c71e874">llvm::BinaryStreamReader::readCString</a>, <a href="/web-llvm/docs/api/classes/llvm/binarystreamreader/#a6a4349bd091677944d67764f80b6fbe0">llvm::BinaryStreamReader::readEnum</a>, <a href="/web-llvm/docs/api/classes/llvm/binarystreamreader/#aac42f02dfb2a8bbe2f6bedea0ff7b29c">llvm::BinaryStreamReader::readFixedString</a>, <a href="/web-llvm/docs/api/classes/anonymous-coveragemappingreader-cpp-/versionedcovmapfuncrecordreader/#a7e1679b2628896a1b7e2299c92776503">anonymous{CoverageMappingReader.cpp}::VersionedCovMapFuncRecordReader&lt; Version, IntPtrT, Endian &gt;::readFunctionRecords</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/globalsstream-cpp/#a47db0d3530f3a43617019d711cbae24f">readGSIHashBuckets</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/globalsstream-cpp/#a44dd8d2be786070c9fde64a4892d8044">readGSIHashHeader</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/globalsstream-cpp/#a5ae02ec2318ccbef9898227128b7320f">readGSIHashRecords</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/wasmobjectfile-cpp/#a45f478a3e04bfcd32b4db7f75fc94577">readInitExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/binarystreamreader/#a6bb348b0b716cb9d060ecaef7a49dcc6">llvm::BinaryStreamReader::readInteger</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/dxcontainer-cpp/#abc63df5c2aad9dab94dc1eeaa7ca4b57">readInteger</a>, <a href="/web-llvm/docs/api/classes/llvm/coverage/rawcoveragereader/#ac41bb2d81feba1123acffc3b1fbe9822">llvm::coverage::RawCoverageReader::readIntMax</a>, <a href="/web-llvm/docs/api/classes/llvm/appendingbinarybytestream/#acc2ef96d39a2d4d967fc235188ef4797">llvm::AppendingBinaryByteStream::readLongestContiguousChunk</a>, <a href="/web-llvm/docs/api/classes/llvm/binarybytestream/#a1d2da883a476269ff26f1963dcfa47e7">llvm::BinaryByteStream::readLongestContiguousChunk</a>, <a href="/web-llvm/docs/api/classes/llvm/binaryitemstream/#a6aaa0adb96626aa11c0b4519f8f44b36">llvm::BinaryItemStream&lt; T, Traits &gt;::readLongestContiguousChunk</a>, <a href="/web-llvm/docs/api/classes/llvm/binarystreamreader/#aa580bf8bd5d8f755f546fa9df986260b">llvm::BinaryStreamReader::readLongestContiguousChunk</a>, <a href="/web-llvm/docs/api/classes/llvm/binarystreamref/#a113ac5e2f45385477dca911a3830d801">llvm::BinaryStreamRef::readLongestContiguousChunk</a>, <a href="/web-llvm/docs/api/classes/llvm/msf/mappedblockstream/#a232c212f81250213c8bf658375e5aa3d">llvm::msf::MappedBlockStream::readLongestContiguousChunk</a>, <a href="/web-llvm/docs/api/files/lib/lib/textapi/lib/textapi/binaryreader/dylibreader-cpp/#a4f3081cf8f364816d9a91b6e24d10fba">readMachOHeader</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a25241903dcf363fdf53dc9e8f1037e7a">llvm::sys::fs::readNativeFileToEOF</a>, <a href="/web-llvm/docs/api/classes/llvm/coverage/binarycoveragereader/#ac034c383522d13dbaebea9e31b126649">llvm::coverage::BinaryCoverageReader::readNextRecord</a>, <a href="/web-llvm/docs/api/classes/llvm/memprof/memprofreader/#a7ebfa82e2e3b9ec55997fbad3f2a8e0c">llvm::memprof::MemProfReader::readNextRecord</a>, <a href="/web-llvm/docs/api/classes/llvm/binarystreamreader/#a07e25e055f92f545f94821c4a3cbded8">llvm::BinaryStreamReader::readObject</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/wasmobjectfile-cpp/#a67951f7188e316333fc6cf733db7f71f">readSection</a>, <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodeanalyzer-cpp/#aa5668bfbe38566ca0b785a2361a4dcf8">ReadSignature</a>, <a href="/web-llvm/docs/api/classes/llvm/coverage/rawcoveragereader/#a65df07e7c47afbd5567446dbf28b0d83">llvm::coverage::RawCoverageReader::readSize</a>, <a href="/web-llvm/docs/api/classes/llvm/binarystreamreader/#aa386dbcb508e02e5910438040aed2cac">llvm::BinaryStreamReader::readSLEB128</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#abb261b1e80159e16ee57e79ed2d77494">llvm::pdb::readSparseBitVector</a>, <a href="/web-llvm/docs/api/classes/llvm/binarystreamreader/#a4364664daec8a6dd65d2161b883cf5fc">llvm::BinaryStreamReader::readStreamRef</a>, <a href="/web-llvm/docs/api/classes/llvm/coverage/rawcoveragereader/#ad324d5af303f97b9842a951c98137931">llvm::coverage::RawCoverageReader::readString</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#acf48e185563b71d058905dfdad656cfd">llvm::object::readStringOrId</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/dxcontainer-cpp/#aa9e5fb5670969ca81a373909d83d51ae">readStruct</a>, <a href="/web-llvm/docs/api/files/lib/lib/textapi/lib/textapi/binaryreader/dylibreader-cpp/#a2ca546a54409cdfc98988096faaa1674">readSymbols</a>, <a href="/web-llvm/docs/api/classes/llvm/binarystreamreader/#ab9f41a80bcb29a219eff47dfac886cce">llvm::BinaryStreamReader::readULEB128</a>, <a href="/web-llvm/docs/api/classes/llvm/coverage/rawcoveragereader/#aca96acd10163f3b8e78eea75ba200fd1">llvm::coverage::RawCoverageReader::readULEB128</a>, <a href="/web-llvm/docs/api/classes/llvm/binarystreamreader/#a3228237a59c80b85e37a5180ff9a352c">llvm::BinaryStreamReader::readWideString</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/elfdebugobject/#a2bb25631b0620094ff871998ec28da02">llvm::orc::ELFDebugObject::recordSection</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/jitlinkreentrytrampolines/trampolineaddrscraperplugin/#ae019a851513a6e78d5f025247ef9b956">llvm::orc::JITLinkReentryTrampolines::TrampolineAddrScraperPlugin::recordTrampolineAddrs</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/indirectstubsmanager/#aee1502ca00cf56ad0572ff4aa196306e">llvm::orc::IndirectStubsManager::redirect</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a12f4e6d052ec7149056449a4476d6e0d">llvm::orc::registerFrameWrapper</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/executionsession/#a9af5ee3a848ca02c351ee7ffca01c3f0">llvm::orc::ExecutionSession::registerJITDispatchHandlers</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-elf-loongarch-cpp-/#a1f634192693b819a330b55739a08709d">anonymous{ELF_loongarch.cpp}::relax</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#a5a9a75388de39e0f0a13fedf7c9579ca">llvm::jitlink::relax</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/inprocessmemorymapper/#ae7b7c908c1016860ed8c53965f8f167a">llvm::orc::InProcessMemoryMapper::release</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/rt-bootstrap/executorsharedmemorymapperservice/#a917f3a8ccf396bf9c6aee999ce552f2e">llvm::orc::rt_bootstrap::ExecutorSharedMemoryMapperService::release</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/sharedmemorymapper/#ac8c1571f24dc447307937d7a1c82ee8b">llvm::orc::SharedMemoryMapper::release</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/dbistream/#a6f720d4ce41d82acda3ab73ee832ca34">llvm::pdb::DbiStream::reload</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/globalsstream/#a0b71210178832a9abc5e334d0e27f655">llvm::pdb::GlobalsStream::reload</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/infostream/#a8061dd23eb1daa95b6fca9bf53dad3a5">llvm::pdb::InfoStream::reload</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/injectedsourcestream/#a043e266ce01be332168911cd5805dee5">llvm::pdb::InjectedSourceStream::reload</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/moduledebugstreamref/#a0384c62524bcae12ec581fe7872a091a">llvm::pdb::ModuleDebugStreamRef::reload</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/pdbstringtable/#a354a564eed91819d8ebc8466a6123741">llvm::pdb::PDBStringTable::reload</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/publicsstream/#a621f37e5ea285041541ad8bcaa3dab0d">llvm::pdb::PublicsStream::reload</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/symbolstream/#a881bfdf4698e1253b2bbdf5ee9754708">llvm::pdb::SymbolStream::reload</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/tpistream/#a9ac5083ab574d806ebe0ccb7faec0fea">llvm::pdb::TpiStream::reload</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/ppc64/#a1b090e84230aaa1ea8df579d5ca9efcd">llvm::jitlink::ppc64::relocateHalf16</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib/#a22901ece72bc281bb4690fad971c4eb5">llvm::orc::JITDylib::remove</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/executionsession/#acfffb371a8a9e003f43cd5027cbea85d">llvm::orc::ExecutionSession::removeJITDylibs</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/macho/object/#a29234a4bcb1dca0dabae964f8eacb264">llvm::objcopy::macho::Object::removeLoadCommands</a>, <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobjcopy-cpp/#a06d536441c3553e3bc7639fdfb0fb45c">removeNotes</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/dynamicrelocationsection/#ae340c5fc4a8b0ced18faab32479843d0">llvm::objcopy::elf::DynamicRelocationSection::removeSectionReferences</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/groupsection/#a99b0c256b36c261eb440d1d44ea68dad">llvm::objcopy::elf::GroupSection::removeSectionReferences</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/section/#a16db01500a4e6c2dfb50f812a092f643">llvm::objcopy::elf::Section::removeSectionReferences</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/sectionbase/#a35cddb260afdaf5088e8686abf118b3d">llvm::objcopy::elf::SectionBase::removeSectionReferences</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/object/#a7ffd3f6642f3190ce71003bbe6500203">llvm::objcopy::elf::Object::removeSections</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/macho/object/#a47fbc494119ba51bed1e722d310bba1e">llvm::objcopy::macho::Object::removeSections</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/coff/object/#adb4129c7b7fb10fedccaaa668094cb31">llvm::objcopy::coff::Object::removeSymbols</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/groupsection/#accb463905d354a442ac7beb6d85b12a9">llvm::objcopy::elf::GroupSection::removeSymbols</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/object/#a6f5260724ddb92daec8287a2365ba36f">llvm::objcopy::elf::Object::removeSymbols</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/relocationsection/#ad393bb7849b7f179f5f1d649318d6204">llvm::objcopy::elf::RelocationSection::removeSymbols</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/sectionbase/#ade8c79ee3c79c98dd1ccb847018695f9">llvm::objcopy::elf::SectionBase::removeSymbols</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/symboltablesection/#aa2f765a7f0d42094f04d32ac60ddaad5">llvm::objcopy::elf::SymbolTableSection::removeSymbols</a>, <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobject-cpp/#ae4ba1a6e27314176648bc330ac6f90da">removeUnneededSections</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/reoptimizelayer/#aa1d94843d12c81b1eda3d646bb2ab38e">llvm::orc::ReOptimizeLayer::reoptimizeIfCallFrequent</a>, <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobjcopy-cpp/#a0caf08c068a9900ddcabffcf9f004b41">replaceAndRemoveSections</a>, <a href="/web-llvm/docs/api/classes/anonymous-dxiloplowering-cpp-/oplowerer/#a6300c8f1d33302d372c953398dd5f18c">anonymous{DXILOpLowering.cpp}::OpLowerer::replaceFunctionWithNamedStructOp</a>, <a href="/web-llvm/docs/api/classes/anonymous-dxiloplowering-cpp-/oplowerer/#ac54843966305eb21541468d352728681">anonymous{DXILOpLowering.cpp}::OpLowerer::replaceFunctionWithOp</a>, <a href="/web-llvm/docs/api/classes/anonymous-dxiloplowering-cpp-/oplowerer/#a583a2a6c920de4695807c6ad35c5e35d">anonymous{DXILOpLowering.cpp}::OpLowerer::replaceResRetUses</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/object/#afbae322db16142a85112d588abe56eb7">llvm::objcopy::elf::Object::replaceSections</a>, <a href="/web-llvm/docs/api/classes/anonymous-dxiloplowering-cpp-/oplowerer/#a87b0b481058d1def42e0b3a6564ed93d">anonymous{DXILOpLowering.cpp}::OpLowerer::replaceSplitDoubleCallUsages</a>, <a href="/web-llvm/docs/api/classes/llvm/errorreported/#a0412a33f257fe2933d2425c36d985bd3">llvm::ErrorReported::reportedOrSuccess</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldimpl/#aff5abd27370b46872f4470992413c91a">llvm::RuntimeDyldImpl::resolveExternalSymbols</a>, <a href="/web-llvm/docs/api/classes/llvm/jitlink/pergraphgotandpltstubsbuilder/#a35221f68863ee2705318594ad49fb5d7">llvm::jitlink::PerGraphGOTAndPLTStubsBuilder&lt; BuilderImplT &gt;::run</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/ctordtorrunner/#af8522f0385861838c0415533bf42bc2a">llvm::orc::CtorDtorRunner::run</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/lookuptask/#a1b98a3c75670cdfc1fb4bb13ebed9821">llvm::orc::LookupTask::run</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/shared/#a8263d385de2b406acf8dbef9b0993cc9">llvm::orc::shared::runDeallocActions</a>, <a href="/web-llvm/docs/api/classes/anonymous-lto-cpp-/firstroundthinbackend/#a2c2b73979dafe07afd42a1d790f7ed8c">anonymous{LTO.cpp}::FirstRoundThinBackend::runThinLTOBackendThread</a>, <a href="/web-llvm/docs/api/classes/anonymous-lto-cpp-/inprocessthinbackend/#af0f9c1c44f600c3385ef076febf8c440">anonymous{LTO.cpp}::InProcessThinBackend::runThinLTOBackendThread</a>, <a href="/web-llvm/docs/api/classes/anonymous-lto-cpp-/secondroundthinbackend/#ad3c878292daedae87b12a69a4a05c046">anonymous{LTO.cpp}::SecondRoundThinBackend::runThinLTOBackendThread</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/shared/wrapperfunctioncall/#a32bc5d50f34fe9e76fbb8014139aa934">llvm::orc::shared::WrapperFunctionCall::runWithSPSRet</a>, <a href="/web-llvm/docs/api/files/lib/lib/dwp/dwp-cpp/#a96eeab61680e6721ce83aee14fa6b3f2">sectionOverflowErrorOrWarning</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/fdsimpleremoteepctransport/#ac70eafd527c133cbc9773c9237179b17">llvm::orc::FDSimpleRemoteEPCTransport::sendMessage</a>, <a href="/web-llvm/docs/api/structs/llvm/remarks/remarklinker/#a520480e348343b25dce916ceca76dcd5">llvm::remarks::RemarkLinker::serialize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a3ff667d4f1513749fb128a62577a9b21">llvm::MachO::serializeInterfaceFileToJSON</a>, <a href="/web-llvm/docs/api/classes/llvm/msf/msfbuilder/#a1af64821af285e06f73d4f9bae60b68a">llvm::msf::MSFBuilder::setBlockMapAddr</a>, <a href="/web-llvm/docs/api/classes/llvm/msf/msfbuilder/#a3da93abaa67b0e96193734c8084fd3ce">llvm::msf::MSFBuilder::setDirectoryBlocksHint</a>, <a href="/web-llvm/docs/api/classes/llvm/remarks/remarkstreamer/#a1fb29ff297a87c4e95d366750079f525">llvm::remarks::RemarkStreamer::setFilter</a>, <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobjcopy-cpp/#af5bc7bb3463aa7528d85207065490482">setSectionFlagsAndType</a>, <a href="/web-llvm/docs/api/classes/llvm/msf/msfbuilder/#a66e6af17e700be6707740c63b7a6a63a">llvm::msf::MSFBuilder::setStreamSize</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/classic/dwarflinker/#aac36499d5ebb7dc9994adee56cf716c4">llvm::dwarf_linker::classic::DWARFLinker::setTargetDWARFVersion</a>, <a href="/web-llvm/docs/api/groups/methods/#ga2814e2cc1c4cb63b8f5cf54f16c2d5f7">llvm::dwarf_linker::parallel::DWARFLinkerImpl::setTargetDWARFVersion</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/coffplatform/#a0cd59afcda8972c7ffd9254da83b7d70">llvm::orc::COFFPlatform::setupJITDylib</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad89283f080890888a7101497fc0b9eec">llvm::setupLLVMOptimizationRemarks</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#abf6ef8f2c7e8631ff2a029a0bbf8e920">llvm::orc::setUpOrcPlatformManually</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/rt-bootstrap/executorsharedmemorymapperservice/#af35944202db51be01b3c6330c976f3a3">llvm::orc::rt_bootstrap::ExecutorSharedMemoryMapperService::shutdown</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/rt-bootstrap/simpleexecutordylibmanager/#a72c0576e51b80be8c74c6c4e8a88fc1c">llvm::orc::rt_bootstrap::SimpleExecutorDylibManager::shutdown</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/rt-bootstrap/simpleexecutormemorymanager/#a6a38733f598f1e702fa2956232e76d85">llvm::orc::rt_bootstrap::SimpleExecutorMemoryManager::shutdown</a>, <a href="/web-llvm/docs/api/classes/llvm/binarystreamreader/#abc2a22c2ff5b4d3254d0ac4c35797c97">llvm::BinaryStreamReader::skip</a>, <a href="/web-llvm/docs/api/classes/llvm/bitstreamcursor/#a73257c6f5ab8032f22e06c1da0bc109f">llvm::BitstreamCursor::SkipBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/codeviewrecordio/#aa2d1751bef14d06889c2bb97d44b8c70">llvm::codeview::CodeViewRecordIO::skipPadding</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#a6ac87d66a2396166f8ea3457900cb0df">llvm::jitlink::splitCompactUnwindBlocks</a>, <a href="/web-llvm/docs/api/classes/anonymous-lto-cpp-/inprocessthinbackend/#a5eaa0d8072fbaa8f8304a531ca7bc48e">anonymous{LTO.cpp}::InProcessThinBackend::start</a>, <a href="/web-llvm/docs/api/classes/anonymous-lto-cpp-/writeindexesthinbackend/#a55d36203adadf1f53c19463943f24196">anonymous{LTO.cpp}::WriteIndexesThinBackend::start</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/fdsimpleremoteepctransport/#a6e8f262aaaac4d6d07b00f3e16510383">llvm::orc::FDSimpleRemoteEPCTransport::start</a>, <a href="/web-llvm/docs/api/classes/anonymous-debuggersupportplugin-cpp-/machodebugobjectsynthesizer/#a59a5eeccde7b8eef0833cee7b914443b">anonymous{DebuggerSupportPlugin.cpp}::MachODebugObjectSynthesizer&lt; MachOTraits &gt;::startSynthesis</a>, <a href="/web-llvm/docs/api/classes/llvm/elfattributeparser/#a8125ecaffe4cb18a746e29ec30bc74c5">llvm::ELFAttributeParser::stringAttribute</a>, <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; std::unique_ptr&lt; InFlightAlloc &gt; &gt;::takeError</a>, <a href="/web-llvm/docs/api/classes/llvm/jitsymbol/#a356e8f8df07016fd4061857fb9df16d5">llvm::JITSymbol::takeError</a>, <a href="/web-llvm/docs/api/classes/anonymous-lljit-cpp-/genericllvmirplatform/#a5844f2265fa531c9825bcbc5360ff3cf">anonymous{LLJIT.cpp}::GenericLLVMIRPlatform::teardownJITDylib</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/coffplatform/#a1a257687b19260c45eb247fdf4e83af7">llvm::orc::COFFPlatform::teardownJITDylib</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/elfnixplatform/#ade8004825924463615a0f9e6f1ebc78d">llvm::orc::ELFNixPlatform::teardownJITDylib</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/machoplatform/#a2410f51d9f312b025f9a3307f63c7f6e">llvm::orc::MachOPlatform::teardownJITDylib</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a95dd9937c9f80f95b741b20bb45e8a33">llvm::timeTraceProfilerWrite</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a29eb6e9604006a962c4d3dc91c6b5c0f">llvm::DWARFUnit::tryExtractDIEsIfNeeded</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/dynamiclibrarysearchgenerator/#a6f48283edeff2b9dfa266043c7229d2f">llvm::orc::DynamicLibrarySearchGenerator::tryToGenerate</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/epcdynamiclibrarysearchgenerator/#acd769134fc784667d68b675ee79b609d">llvm::orc::EPCDynamicLibrarySearchGenerator::tryToGenerate</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/reexportsgenerator/#a9b1cc5b369f4fd3e04b66035eea7c481">llvm::orc::ReexportsGenerator::tryToGenerate</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/staticlibrarydefinitiongenerator/#a553c068fc6fde1b82ee28bbc7bd11a8f">llvm::orc::StaticLibraryDefinitionGenerator::tryToGenerate</a>, <a href="/web-llvm/docs/api/classes/llvm/debuginfodcollection/#a68a1fb7af3be229df5d6fa47b5ded6f5">llvm::DebuginfodCollection::update</a>, <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobjcopy-cpp/#a4a8b0267a862203c3082ed955abd326c">updateAndRemoveSymbols</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/localindirectstubsmanager/#acb10fef5b99a6616761ba72b5ec033f1">llvm::orc::LocalIndirectStubsManager&lt; TargetT &gt;::updatePointer</a>, <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machoobjcopy-cpp/#afcfed892d87764504587749693efe357">updateSection</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dwarflinkerimpl/#a49eedb8f4407a04a750f0b63384f8217">llvm::dwarf_linker::parallel::DWARFLinkerImpl::validateAndUpdateOptions</a>, <a href="/web-llvm/docs/api/classes/llvm/stackmapparser/#af470818b30d3fbef99dc8dc104d6039d">llvm::StackMapParser&lt; Endianness &gt;::validateHeader</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ifs/#a70275602a4d7dc80232bdb8f7964044e">llvm::ifs::validateIFSTarget</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/elfdebugobjectsection/#a33c62d0d0c29c96b7b48d9e416d655e8">llvm::orc::ELFDebugObjectSection&lt; ELFT &gt;::validateInBounds</a>, <a href="/web-llvm/docs/api/files/lib/lib/remarks/bitstreamremarkparser-cpp/#a6062a9632d9d9c4d35afd3e82970887e">validateMagicNumber</a>, <a href="/web-llvm/docs/api/classes/llvm/instrprofwriter/#af30e5f42e3c87128fe5530d937236c7b">llvm::InstrProfWriter::validateRecord</a>, <a href="/web-llvm/docs/api/namespaces/llvm/msf/#a06fa30876215b96491f3bb001755c3fa">llvm::msf::validateSuperBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/giselcseinfo/#ad59eed9a40a4f5cca48396538dcb9b13">llvm::GISelCSEInfo::verify</a>, <a href="/web-llvm/docs/api/classes/llvm/gsym/dwarftransformer/#ac40e6efe1caf07771eb6713f41db076b">llvm::gsym::DwarfTransformer::verify</a>, <a href="/web-llvm/docs/api/classes/llvm/inlineasm/#adfcd3a2486f54c348da1859c41f6cc09">llvm::InlineAsm::verify</a>, <a href="/web-llvm/docs/api/classes/llvm/xray/blockverifier/#a358157e2ac5a3e8e85ed759cec5e1798">llvm::xray::BlockVerifier::verify</a>, <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobjcopy-cpp/#a73b370d004cc941240050b8048fefb7e">verifyNoteSection</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/elfsectionsizer/#a2f6dc53f5bb121eaf858f18faea953b6">llvm::objcopy::elf::ELFSectionSizer&lt; ELFT &gt;::visit</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/elfsectionsizer/#ab75e5a02f1ae0cb82402f4851affd122">llvm::objcopy::elf::ELFSectionSizer&lt; ELFT &gt;::visit</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/elfsectionsizer/#a3a988e4045affd56b2fac3596d262f16">llvm::objcopy::elf::ELFSectionSizer&lt; ELFT &gt;::visit</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/elfsectionsizer/#a35de9bc5b6fa321f490053193312203f">llvm::objcopy::elf::ELFSectionSizer&lt; ELFT &gt;::visit</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/elfsectionsizer/#a6e78e218bde17021830b3f5e725977c6">llvm::objcopy::elf::ELFSectionSizer&lt; ELFT &gt;::visit</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/elfsectionsizer/#a3351813ccf2c6e76873b79e7882bdfdc">llvm::objcopy::elf::ELFSectionSizer&lt; ELFT &gt;::visit</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/elfsectionsizer/#ade8c40151bc04195d8172e6061b829a4">llvm::objcopy::elf::ELFSectionSizer&lt; ELFT &gt;::visit</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/elfsectionsizer/#a53ed609c26f8dcde61d70c4865e4b096">llvm::objcopy::elf::ELFSectionSizer&lt; ELFT &gt;::visit</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/elfsectionsizer/#a7a31b320b2eaacc1d7407309c05f4951">llvm::objcopy::elf::ELFSectionSizer&lt; ELFT &gt;::visit</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/elfsectionsizer/#ab767e6a686b13994eaa789e6355239e3">llvm::objcopy::elf::ELFSectionSizer&lt; ELFT &gt;::visit</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/elfsectionsizer/#adee90caa6f190b6af21934d33ae2c3e1">llvm::objcopy::elf::ELFSectionSizer&lt; ELFT &gt;::visit</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/elfsectionwriter/#a2337e506453c5ed1ec20ebabbafbc014">llvm::objcopy::elf::ELFSectionWriter&lt; ELFT &gt;::visit</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/elfsectionwriter/#a9c48163b33da5da66af7a1e8f4deb637">llvm::objcopy::elf::ELFSectionWriter&lt; ELFT &gt;::visit</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/elfsectionwriter/#a41e0e358ff2983c5554860ec6160dbcf">llvm::objcopy::elf::ELFSectionWriter&lt; ELFT &gt;::visit</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/elfsectionwriter/#ae3dbe560d017873ff39f9b760e59b0b2">llvm::objcopy::elf::ELFSectionWriter&lt; ELFT &gt;::visit</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/elfsectionwriter/#aa394fee185f6e8554b5cdb6ad6084394">llvm::objcopy::elf::ELFSectionWriter&lt; ELFT &gt;::visit</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/elfsectionwriter/#a09464493cae842182c7a9f6912c336e3">llvm::objcopy::elf::ELFSectionWriter&lt; ELFT &gt;::visit</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/elfsectionwriter/#ac3c2c72c0758eab93277f675bf83d8b4">llvm::objcopy::elf::ELFSectionWriter&lt; ELFT &gt;::visit</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/ihexsectionwriter/#ae2b4d52449259cb44c2e6a0b558ec9ee">llvm::objcopy::elf::IHexSectionWriter::visit</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/ihexsectionwriterbase/#a2069a948fa09c0faeb0b7c25b1e6221c">llvm::objcopy::elf::IHexSectionWriterBase::visit</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/ihexsectionwriterbase/#a1cbbb9c5032b95a46e4eb14745281b4e">llvm::objcopy::elf::IHexSectionWriterBase::visit</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/ihexsectionwriterbase/#a94349903cd4a44b599f5809cb95c589c">llvm::objcopy::elf::IHexSectionWriterBase::visit</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/ihexsectionwriterbase/#a4eacf10ebf949f25c6f0e1f1a0df6954">llvm::objcopy::elf::IHexSectionWriterBase::visit</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/sectionwriter/#a443459a435a2e50375d85f0b76530b4c">llvm::objcopy::elf::SectionWriter::visit</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/sectionwriter/#a026bbbadcf8a77ba4ede7ca80322e2dc">llvm::objcopy::elf::SectionWriter::visit</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/sectionwriter/#a76b5551d20e099e66e929c74f32469fe">llvm::objcopy::elf::SectionWriter::visit</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/srecsectionwriter/#a2c0bdb8c0a5dc11c8f200df17eb17df3">llvm::objcopy::elf::SRECSectionWriter::visit</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/srecsectionwriterbase/#aa094a065ac48a25297e4a7693f9acaaa">llvm::objcopy::elf::SRECSectionWriterBase::visit</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/srecsectionwriterbase/#a89318ac9c0907c43850b5b087bdd9731">llvm::objcopy::elf::SRECSectionWriterBase::visit</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/srecsectionwriterbase/#a7d8ee9a638fdb77252b1c3d5bf8bb3b0">llvm::objcopy::elf::SRECSectionWriterBase::visit</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/srecsectionwriterbase/#a725e0954ae2fcf7988f1baa0ef982313">llvm::objcopy::elf::SRECSectionWriterBase::visit</a>, <a href="/web-llvm/docs/api/classes/llvm/xray/blockindexer/#a17f3d2110e4a16c24aeeb816b490deed">llvm::xray::BlockIndexer::visit</a>, <a href="/web-llvm/docs/api/classes/llvm/xray/blockindexer/#ae22e733deffe118518c1e777f90baf6b">llvm::xray::BlockIndexer::visit</a>, <a href="/web-llvm/docs/api/classes/llvm/xray/blockindexer/#ac7fcb25dcf9e8f8e5b90e8137be66894">llvm::xray::BlockIndexer::visit</a>, <a href="/web-llvm/docs/api/classes/llvm/xray/blockindexer/#ae5f7e3012570a8d93b505c6a5f8af979">llvm::xray::BlockIndexer::visit</a>, <a href="/web-llvm/docs/api/classes/llvm/xray/blockindexer/#a9e5ec134e1b20b6b96c57df7eb5014f4">llvm::xray::BlockIndexer::visit</a>, <a href="/web-llvm/docs/api/classes/llvm/xray/blockindexer/#a8c1c952419da5e01a41f6184601df81c">llvm::xray::BlockIndexer::visit</a>, <a href="/web-llvm/docs/api/classes/llvm/xray/blockindexer/#ad1338d115a43395af7fa83f02f3e8f7b">llvm::xray::BlockIndexer::visit</a>, <a href="/web-llvm/docs/api/classes/llvm/xray/blockindexer/#a0fe904fb1961c501309b0724343d451f">llvm::xray::BlockIndexer::visit</a>, <a href="/web-llvm/docs/api/classes/llvm/xray/blockindexer/#aee2e6a9c3283f5d4bf635f34c880edc2">llvm::xray::BlockIndexer::visit</a>, <a href="/web-llvm/docs/api/classes/llvm/xray/blockindexer/#ab103bfb701087d03b3d41d72806faab5">llvm::xray::BlockIndexer::visit</a>, <a href="/web-llvm/docs/api/classes/llvm/xray/blockindexer/#a050e7d2275da820025454fce8901a50a">llvm::xray::BlockIndexer::visit</a>, <a href="/web-llvm/docs/api/classes/llvm/xray/blockindexer/#a96abbb2c11d9ec0595348d9fa373112a">llvm::xray::BlockIndexer::visit</a>, <a href="/web-llvm/docs/api/classes/llvm/xray/fdrtracewriter/#a153f2789b3e471dd26677f8b18c04cd7">llvm::xray::FDRTraceWriter::visit</a>, <a href="/web-llvm/docs/api/classes/llvm/xray/fdrtracewriter/#a1fa6ae68df15616203d9d75a0c4f6628">llvm::xray::FDRTraceWriter::visit</a>, <a href="/web-llvm/docs/api/classes/llvm/xray/fdrtracewriter/#a16853f5020e7da00cd98313b51964127">llvm::xray::FDRTraceWriter::visit</a>, <a href="/web-llvm/docs/api/classes/llvm/xray/fdrtracewriter/#a741f341e00d643549b71ef01ddd01c5d">llvm::xray::FDRTraceWriter::visit</a>, <a href="/web-llvm/docs/api/classes/llvm/xray/recordinitializer/#a3738e67e3d3845d96229a109745ab3f6">llvm::xray::RecordInitializer::visit</a>, <a href="/web-llvm/docs/api/classes/llvm/xray/recordinitializer/#a28a14e1d9e521fe1995be3c832514eed">llvm::xray::RecordInitializer::visit</a>, <a href="/web-llvm/docs/api/classes/llvm/xray/recordinitializer/#abbba96624ba61ef4143283ea7ddac207">llvm::xray::RecordInitializer::visit</a>, <a href="/web-llvm/docs/api/classes/llvm/xray/recordinitializer/#ac80b318f126108bc6630cc1f43ee3b46">llvm::xray::RecordInitializer::visit</a>, <a href="/web-llvm/docs/api/classes/llvm/xray/recordinitializer/#a0650edb26f68bb4ad7a2a298dc9df444">llvm::xray::RecordInitializer::visit</a>, <a href="/web-llvm/docs/api/classes/llvm/xray/recordinitializer/#ac94e2b1de03b3d07c74bedd8eee3c3d5">llvm::xray::RecordInitializer::visit</a>, <a href="/web-llvm/docs/api/classes/llvm/xray/recordinitializer/#a31a822a9aae29d7041f5dc7b1be05dec">llvm::xray::RecordInitializer::visit</a>, <a href="/web-llvm/docs/api/classes/llvm/xray/recordinitializer/#a76f028615969b9a6ece5443188b06e2b">llvm::xray::RecordInitializer::visit</a>, <a href="/web-llvm/docs/api/classes/llvm/xray/recordinitializer/#a400681f1492184c0d702ef102d054dbb">llvm::xray::RecordInitializer::visit</a>, <a href="/web-llvm/docs/api/classes/llvm/xray/recordinitializer/#a06c7d6221e6b07c833eeb8f24ef13a5b">llvm::xray::RecordInitializer::visit</a>, <a href="/web-llvm/docs/api/classes/llvm/xray/recordinitializer/#a0e0d591f4ae50de5ecc72ad08ac4ae65">llvm::xray::RecordInitializer::visit</a>, <a href="/web-llvm/docs/api/classes/llvm/xray/recordinitializer/#a9c1b0c1c9d8e1cb246f15f376199184a">llvm::xray::RecordInitializer::visit</a>, <a href="/web-llvm/docs/api/classes/llvm/xray/recordprinter/#a11147e5881cc66b3264ccb4effa4dbb5">llvm::xray::RecordPrinter::visit</a>, <a href="/web-llvm/docs/api/classes/llvm/xray/recordprinter/#a393a111c72f6fa44ce2a30241323d8eb">llvm::xray::RecordPrinter::visit</a>, <a href="/web-llvm/docs/api/classes/llvm/xray/recordprinter/#a519626f8208f0f3a3a20a83dced5af3f">llvm::xray::RecordPrinter::visit</a>, <a href="/web-llvm/docs/api/classes/llvm/xray/recordprinter/#a3fea5969ab695938c80b9e990f8c2e15">llvm::xray::RecordPrinter::visit</a>, <a href="/web-llvm/docs/api/classes/llvm/xray/recordprinter/#a6bc6a1e8a2eb8f5babe7b10ed4058395">llvm::xray::RecordPrinter::visit</a>, <a href="/web-llvm/docs/api/classes/llvm/xray/recordprinter/#abd65c601613bb0362dc6308776fc8675">llvm::xray::RecordPrinter::visit</a>, <a href="/web-llvm/docs/api/classes/llvm/xray/recordprinter/#a5ba1a81885c0b53c43ebe68eba6b6294">llvm::xray::RecordPrinter::visit</a>, <a href="/web-llvm/docs/api/classes/llvm/xray/recordprinter/#a8b8adcf388fec727cc53c3df97c8d082">llvm::xray::RecordPrinter::visit</a>, <a href="/web-llvm/docs/api/classes/llvm/xray/recordprinter/#a4a825861bb9b4773e4d771a74d932920">llvm::xray::RecordPrinter::visit</a>, <a href="/web-llvm/docs/api/classes/llvm/xray/recordprinter/#a82a05b58e28ad3b1768429caf8680a2f">llvm::xray::RecordPrinter::visit</a>, <a href="/web-llvm/docs/api/classes/llvm/xray/recordprinter/#a3775f1882c3c1e6470472aaad5214835">llvm::xray::RecordPrinter::visit</a>, <a href="/web-llvm/docs/api/classes/llvm/xray/recordprinter/#aa3cfef541bb41919b98c6372d695f088">llvm::xray::RecordPrinter::visit</a>, <a href="/web-llvm/docs/api/classes/llvm/xray/traceexpander/#a533e6b5733b685849a0e31250e3c7720">llvm::xray::TraceExpander::visit</a>, <a href="/web-llvm/docs/api/classes/llvm/xray/traceexpander/#aad5adad425da8e9ba16cee02eedc160e">llvm::xray::TraceExpander::visit</a>, <a href="/web-llvm/docs/api/classes/llvm/xray/traceexpander/#a998233c11fa306709edbce845076ce4e">llvm::xray::TraceExpander::visit</a>, <a href="/web-llvm/docs/api/classes/llvm/xray/traceexpander/#a4deb946010d71c120babc7a39bb0e514">llvm::xray::TraceExpander::visit</a>, <a href="/web-llvm/docs/api/classes/llvm/xray/traceexpander/#abdf89650155f26b79ea2f096ac9e8f2c">llvm::xray::TraceExpander::visit</a>, <a href="/web-llvm/docs/api/classes/llvm/xray/traceexpander/#ac253c770774248a61f9a38edc16da10e">llvm::xray::TraceExpander::visit</a>, <a href="/web-llvm/docs/api/classes/llvm/xray/traceexpander/#a5c124aa4f37f0b81f55ff85c9af17d6c">llvm::xray::TraceExpander::visit</a>, <a href="/web-llvm/docs/api/classes/llvm/xray/traceexpander/#ab8aca04847a1e7e2701e8c9c8c5ccebf">llvm::xray::TraceExpander::visit</a>, <a href="/web-llvm/docs/api/classes/llvm/xray/traceexpander/#a15f115232daa7adac4a083d8a47e3393">llvm::xray::TraceExpander::visit</a>, <a href="/web-llvm/docs/api/classes/llvm/xray/traceexpander/#a6f6e89f87c40eb647283d85f0976e0ca">llvm::xray::TraceExpander::visit</a>, <a href="/web-llvm/docs/api/classes/llvm/xray/traceexpander/#a3057671f15f29579f9aa77d290a7f8df">llvm::xray::TraceExpander::visit</a>, <a href="/web-llvm/docs/api/classes/llvm/xray/traceexpander/#ad8ee1423f94ae9b013a2195982b61797">llvm::xray::TraceExpander::visit</a>, <a href="/web-llvm/docs/api/structs/anonymous-codeviewyamldebugsections-cpp-/subsectionconversionvisitor/#af10fdcb5526a3924122ebfa4246d2de1">anonymous{CodeViewYAMLDebugSections.cpp}::SubsectionConversionVisitor::visitCOFFSymbolRVAs</a>, <a href="/web-llvm/docs/api/structs/anonymous-codeviewyamldebugsections-cpp-/subsectionconversionvisitor/#a9fbf9bc88c2dff15da11c242335b2769">anonymous{CodeViewYAMLDebugSections.cpp}::SubsectionConversionVisitor::visitCrossModuleExports</a>, <a href="/web-llvm/docs/api/structs/anonymous-codeviewyamldebugsections-cpp-/subsectionconversionvisitor/#a817662724fa3463e8dd93d42e17e3596">anonymous{CodeViewYAMLDebugSections.cpp}::SubsectionConversionVisitor::visitCrossModuleImports</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/detail/#a9ab010c07c69af2982cfe056789b6dc7">llvm::codeview::detail::visitDebugSubsections</a>, <a href="/web-llvm/docs/api/classes/anonymous-cvtypevisitor-cpp-/cvtypevisitor/#a100392649274fd023e5e2add981ca9a8">anonymous{CVTypeVisitor.cpp}::CVTypeVisitor::visitFieldListMemberStream</a>, <a href="/web-llvm/docs/api/structs/anonymous-codeviewyamldebugsections-cpp-/subsectionconversionvisitor/#ad6468d10b992a6ad6bb3908531839004">anonymous{CodeViewYAMLDebugSections.cpp}::SubsectionConversionVisitor::visitFileChecksums</a>, <a href="/web-llvm/docs/api/structs/anonymous-codeviewyamldebugsections-cpp-/subsectionconversionvisitor/#a59986054f1f5fed916f1e896ee9a2368">anonymous{CodeViewYAMLDebugSections.cpp}::SubsectionConversionVisitor::visitFrameData</a>, <a href="/web-llvm/docs/api/structs/anonymous-codeviewyamldebugsections-cpp-/subsectionconversionvisitor/#aed8c2f4079a6030f5f98ae798a374041">anonymous{CodeViewYAMLDebugSections.cpp}::SubsectionConversionVisitor::visitInlineeLines</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvlogicalvisitor/#a3cf4854b9700e7d9f6fa045c28c536a0">llvm::logicalview::LVLogicalVisitor::visitKnownMember</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvlogicalvisitor/#aa300b4d35c32e9fbd142578c447a556f">llvm::logicalview::LVLogicalVisitor::visitKnownMember</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvlogicalvisitor/#a6ddf6a3be3f9d8629ad887d3125ce0bb">llvm::logicalview::LVLogicalVisitor::visitKnownMember</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvlogicalvisitor/#af3229086e49b76d1dbdc7bd0e6300737">llvm::logicalview::LVLogicalVisitor::visitKnownMember</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvlogicalvisitor/#ae9aeda1f1736cdf67f11ea6f1c99b107">llvm::logicalview::LVLogicalVisitor::visitKnownMember</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvlogicalvisitor/#a9efe423cacffbe87239e1e0f556d6d86">llvm::logicalview::LVLogicalVisitor::visitKnownMember</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvlogicalvisitor/#a9d03e43695c8f8371c9c1fe4a6519ae6">llvm::logicalview::LVLogicalVisitor::visitKnownMember</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvlogicalvisitor/#ad006d3e6801c21a539ffc8b32d91a17d">llvm::logicalview::LVLogicalVisitor::visitKnownMember</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvlogicalvisitor/#aa4681071bf84200dace5251305a67a1c">llvm::logicalview::LVLogicalVisitor::visitKnownMember</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvlogicalvisitor/#a6ee2ae8a2caff14a0928ded0348efd8c">llvm::logicalview::LVLogicalVisitor::visitKnownMember</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvlogicalvisitor/#a37c4e4e6831c8f3f7304cdaf11060b0f">llvm::logicalview::LVLogicalVisitor::visitKnownMember</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/cvtypevisitor-cpp/#a618b2f5fcf74140acbf93e571a0c121b">visitKnownMember</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvlogicalvisitor/#a0015ff019ddc43f0e4840febaf74664d">llvm::logicalview::LVLogicalVisitor::visitKnownRecord</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvlogicalvisitor/#ac72c1663cfda32b4cb722e815b1ea005">llvm::logicalview::LVLogicalVisitor::visitKnownRecord</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvlogicalvisitor/#a37e81e85684fa7bde4a91f870f4c44b8">llvm::logicalview::LVLogicalVisitor::visitKnownRecord</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvlogicalvisitor/#ab7d42ec1825f9e56033a386b52d39337">llvm::logicalview::LVLogicalVisitor::visitKnownRecord</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvlogicalvisitor/#ade7088de2025cc1850af4e51e17c9255">llvm::logicalview::LVLogicalVisitor::visitKnownRecord</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvlogicalvisitor/#a8d47724a657b7c47da03316e855b9b48">llvm::logicalview::LVLogicalVisitor::visitKnownRecord</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvlogicalvisitor/#a9ca019e8fbb127c461eba43cb4649642">llvm::logicalview::LVLogicalVisitor::visitKnownRecord</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvlogicalvisitor/#a7f4808cdf082e92e24c882c5a00a0c93">llvm::logicalview::LVLogicalVisitor::visitKnownRecord</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvlogicalvisitor/#aef3473440a5ef85d0c44e95308f22a77">llvm::logicalview::LVLogicalVisitor::visitKnownRecord</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvlogicalvisitor/#acdb64629acda1a991247ba4c049c60c4">llvm::logicalview::LVLogicalVisitor::visitKnownRecord</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvlogicalvisitor/#a0d54e1dd5acde5b32e990f461bc2daa2">llvm::logicalview::LVLogicalVisitor::visitKnownRecord</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvlogicalvisitor/#afaa27f4570b743eb19adf1278056c387">llvm::logicalview::LVLogicalVisitor::visitKnownRecord</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvlogicalvisitor/#ac28d415acf28987bc11560889b9e76b1">llvm::logicalview::LVLogicalVisitor::visitKnownRecord</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvlogicalvisitor/#adbd431dc7da0c6db4b9987a3b85e4876">llvm::logicalview::LVLogicalVisitor::visitKnownRecord</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvlogicalvisitor/#ac6549e77fe8b0654042aa48cc785d3e7">llvm::logicalview::LVLogicalVisitor::visitKnownRecord</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvlogicalvisitor/#adb7f7308a370b9bb952aebfa8c04d585">llvm::logicalview::LVLogicalVisitor::visitKnownRecord</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvlogicalvisitor/#a47a421cf2ef2fc76b72f322783bfd9e3">llvm::logicalview::LVLogicalVisitor::visitKnownRecord</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvlogicalvisitor/#a3f8a4731c6b598189e6503052d277cf5">llvm::logicalview::LVLogicalVisitor::visitKnownRecord</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvlogicalvisitor/#a9ec578dadc7c4409612fdaf21e83dcec">llvm::logicalview::LVLogicalVisitor::visitKnownRecord</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvlogicalvisitor/#af11c2a836925d0e70268cb478d829473">llvm::logicalview::LVLogicalVisitor::visitKnownRecord</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvlogicalvisitor/#a978c30bae82893422130ec3bf98a56ce">llvm::logicalview::LVLogicalVisitor::visitKnownRecord</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvlogicalvisitor/#afe0bd76d0a524ced56b7dd7e10451ee8">llvm::logicalview::LVLogicalVisitor::visitKnownRecord</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvlogicalvisitor/#ab2bde320a72ca54870bb93585991de89">llvm::logicalview::LVLogicalVisitor::visitKnownRecord</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvlogicalvisitor/#a20ff4db3e31aae1d9b6ce04ad03c421d">llvm::logicalview::LVLogicalVisitor::visitKnownRecord</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvlogicalvisitor/#a0f7b86f4b3c852f56ca5abb71840a4d6">llvm::logicalview::LVLogicalVisitor::visitKnownRecord</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvlogicalvisitor/#ac1c5ef69da66ecc0e7a63e74252cbffe">llvm::logicalview::LVLogicalVisitor::visitKnownRecord</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvsymbolvisitor/#a72b73a81f4900e2beefee963a8856cc6">llvm::logicalview::LVSymbolVisitor::visitKnownRecord</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvsymbolvisitor/#a8ac911209abea3b815ff6f96fe71560b">llvm::logicalview::LVSymbolVisitor::visitKnownRecord</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvsymbolvisitor/#a89b27021a77eb70d0481da029751aebb">llvm::logicalview::LVSymbolVisitor::visitKnownRecord</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvsymbolvisitor/#a14292195c357c0ee1d3c90f8a92551e2">llvm::logicalview::LVSymbolVisitor::visitKnownRecord</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvsymbolvisitor/#a34d92f8e253ad8bb1bdb5e60f91c877d">llvm::logicalview::LVSymbolVisitor::visitKnownRecord</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvsymbolvisitor/#afc9a506692070b035881b1d548c87965">llvm::logicalview::LVSymbolVisitor::visitKnownRecord</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvsymbolvisitor/#a7715a3a87a83a23b15d67031e6855044">llvm::logicalview::LVSymbolVisitor::visitKnownRecord</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvsymbolvisitor/#ae901cd9487d3528e4305f60715aa53a4">llvm::logicalview::LVSymbolVisitor::visitKnownRecord</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvsymbolvisitor/#a2ec38ee744ebd39dd489b0d5f52ada00">llvm::logicalview::LVSymbolVisitor::visitKnownRecord</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvsymbolvisitor/#a0cc8f37b88434f493eb4cdf2c6596ba5">llvm::logicalview::LVSymbolVisitor::visitKnownRecord</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvsymbolvisitor/#ab7651adf465ecbe58fce9cb202391532">llvm::logicalview::LVSymbolVisitor::visitKnownRecord</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvsymbolvisitor/#a9722ed801caebb3a695ed7dfe0472d2a">llvm::logicalview::LVSymbolVisitor::visitKnownRecord</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvsymbolvisitor/#a4452fd8e79fab52e8fa7a243ad0ba3c9">llvm::logicalview::LVSymbolVisitor::visitKnownRecord</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvsymbolvisitor/#a6c8767d62827feb3a07578e10a648c8f">llvm::logicalview::LVSymbolVisitor::visitKnownRecord</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvsymbolvisitor/#ab6dce4234dfed467146522a0c820df35">llvm::logicalview::LVSymbolVisitor::visitKnownRecord</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvsymbolvisitor/#a8d35c98ac054e90008f7ccb2267aa147">llvm::logicalview::LVSymbolVisitor::visitKnownRecord</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvsymbolvisitor/#a10a5adea20fc95bb7884b808c62e58fa">llvm::logicalview::LVSymbolVisitor::visitKnownRecord</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvsymbolvisitor/#a28ec6a31deb35ac1cdeceb5d544fccce">llvm::logicalview::LVSymbolVisitor::visitKnownRecord</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvsymbolvisitor/#a5d1b660812c790e9e40def86f8f9b472">llvm::logicalview::LVSymbolVisitor::visitKnownRecord</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvsymbolvisitor/#ad346357982c3fcc064fa5e5b434233f3">llvm::logicalview::LVSymbolVisitor::visitKnownRecord</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvsymbolvisitor/#a5a5f40ab7232a3d65f93896104d82357">llvm::logicalview::LVSymbolVisitor::visitKnownRecord</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvsymbolvisitor/#ae84cd42c2c873ab9cd791ecd43b5d4e4">llvm::logicalview::LVSymbolVisitor::visitKnownRecord</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvsymbolvisitor/#a0634ef995ed734d9cc3f51484bd58a61">llvm::logicalview::LVSymbolVisitor::visitKnownRecord</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvsymbolvisitor/#ab82e6c167b5c0eb346bdf5125df2134e">llvm::logicalview::LVSymbolVisitor::visitKnownRecord</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvsymbolvisitor/#a81b76ca042deff17f9ea685d118012fd">llvm::logicalview::LVSymbolVisitor::visitKnownRecord</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvsymbolvisitor/#adf84d48048aee19abab732beff8318f6">llvm::logicalview::LVSymbolVisitor::visitKnownRecord</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvtypevisitor/#ada95daa8ff2aa618f03af9f15ff0e350">llvm::logicalview::LVTypeVisitor::visitKnownRecord</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvtypevisitor/#a84d11658a04c954d4bb01d9e3e03567d">llvm::logicalview::LVTypeVisitor::visitKnownRecord</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvtypevisitor/#a6a70a83c76ecce9b0b68bf8a613c7de3">llvm::logicalview::LVTypeVisitor::visitKnownRecord</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvtypevisitor/#a88db2a7912b801a504d6489abe2272aa">llvm::logicalview::LVTypeVisitor::visitKnownRecord</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvtypevisitor/#ab415d1ac60d902e4d177490728b563a2">llvm::logicalview::LVTypeVisitor::visitKnownRecord</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvtypevisitor/#a80774c35d4edb4a9f59c20e6619ecd38">llvm::logicalview::LVTypeVisitor::visitKnownRecord</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvtypevisitor/#a5de8780e1ef368142535d64f34425c32">llvm::logicalview::LVTypeVisitor::visitKnownRecord</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvtypevisitor/#a160247400b93a2e90ee8e88b75e5cc16">llvm::logicalview::LVTypeVisitor::visitKnownRecord</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/cvsymbolvisitor-cpp/#ad5efdd36be98503f918fde701e83b28b">visitKnownRecord</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/cvtypevisitor-cpp/#a20cd3fbdffee4e950383d5263b25f3d1">visitKnownRecord</a>, <a href="/web-llvm/docs/api/structs/anonymous-codeviewyamldebugsections-cpp-/subsectionconversionvisitor/#aa282429f771c1001960ab39ffe30ef28">anonymous{CodeViewYAMLDebugSections.cpp}::SubsectionConversionVisitor::visitLines</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugloc/#ae386da186965d9d9ce64e0cc1450814d">llvm::DWARFDebugLoc::visitLocationList</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugloclists/#a58e073f89252bbc940a641902a910eb6">llvm::DWARFDebugLoclists::visitLocationList</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/typedumpvisitor/#afa470e9dab06e163ce2b08a65ad83fc2">llvm::codeview::TypeDumpVisitor::visitMemberBegin</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/typerecordmapping/#a17748af8672ec69e3715d19c6f1d21c8">llvm::codeview::TypeRecordMapping::visitMemberBegin</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/typevisitorcallbackpipeline/#a1878097b8550030b2ee4ba60b73dd77a">llvm::codeview::TypeVisitorCallbackPipeline::visitMemberBegin</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/typevisitorcallbacks/#aed7f5f2d36484023b0c6c0d45b911100">llvm::codeview::TypeVisitorCallbacks::visitMemberBegin</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvtypevisitor/#aa8e4ad118c5a3cf5869292938b0f4316">llvm::logicalview::LVTypeVisitor::visitMemberBegin</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/fieldlistdeserializer/#a2e0dd7e8684fc28eaffa7465cfbb62cb">llvm::codeview::FieldListDeserializer::visitMemberEnd</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/typedumpvisitor/#a67448cf4a26f3f4eda72cd2bacdec169">llvm::codeview::TypeDumpVisitor::visitMemberEnd</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/typerecordmapping/#abacef635e983790e9987ec66c97741f9">llvm::codeview::TypeRecordMapping::visitMemberEnd</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/typevisitorcallbackpipeline/#aa89ee0856b5cadcc29c25792117f93e6">llvm::codeview::TypeVisitorCallbackPipeline::visitMemberEnd</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/typevisitorcallbacks/#aabb0d570b56d25c7bd534ad3ac109d19">llvm::codeview::TypeVisitorCallbacks::visitMemberEnd</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvtypevisitor/#a02e620704b6e7a2e72ccd04c30fd1ba6">llvm::logicalview::LVTypeVisitor::visitMemberEnd</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvlogicalvisitor/#a38aaf9af22e7aebd5e41ddb05c414922">llvm::logicalview::LVLogicalVisitor::visitMemberRecord</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/cvtypevisitor-cpp/#a98de0219e4f88afbde8f0a5c9124dae8">visitMemberRecord</a>, <a href="/web-llvm/docs/api/structs/anonymous-codeviewyamldebugsections-cpp-/subsectionconversionvisitor/#a25a4af68293ab58edcdd373776f70476">anonymous{CodeViewYAMLDebugSections.cpp}::SubsectionConversionVisitor::visitStringTable</a>, <a href="/web-llvm/docs/api/classes/anonymous-symboldumper-cpp-/cvsymboldumperimpl/#afdd17a4669d7d1cf98833763cfbb09c4">anonymous{SymbolDumper.cpp}::CVSymbolDumperImpl::visitSymbolBegin</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/symbolrecordmapping/#ac071b7f9eb995f4bbc5adde6f938b536">llvm::codeview::SymbolRecordMapping::visitSymbolBegin</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/symbolserializer/#a64c089c27247e588d3c57d6a772841d1">llvm::codeview::SymbolSerializer::visitSymbolBegin</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/symbolvisitorcallbackpipeline/#ac09b873932ddaddb27656cc957df61ea">llvm::codeview::SymbolVisitorCallbackPipeline::visitSymbolBegin</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/symbolvisitorcallbackpipeline/#aa9d686328418170654dd9849f8222323">llvm::codeview::SymbolVisitorCallbackPipeline::visitSymbolBegin</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/symbolvisitorcallbacks/#a5859a6c2f0d43c768b9dd22b7257ffc0">llvm::codeview::SymbolVisitorCallbacks::visitSymbolBegin</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/symbolvisitorcallbacks/#abab59833c100c59b3eac1b584c909257">llvm::codeview::SymbolVisitorCallbacks::visitSymbolBegin</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvsymbolvisitor/#a2bb63c1e53889580c2adff7d040b7620">llvm::logicalview::LVSymbolVisitor::visitSymbolBegin</a>, <a href="/web-llvm/docs/api/classes/anonymous-symboldumper-cpp-/cvsymboldumperimpl/#a4236f2c1eae2b4f515a4f75986e61b68">anonymous{SymbolDumper.cpp}::CVSymbolDumperImpl::visitSymbolEnd</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/symbolrecordmapping/#a1aae7efbe35d635a423c6459f25f5a04">llvm::codeview::SymbolRecordMapping::visitSymbolEnd</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/symbolserializer/#afee193832653eb3f696a5a71641ca8b0">llvm::codeview::SymbolSerializer::visitSymbolEnd</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/symbolvisitorcallbackpipeline/#aecb701cc0b6355f8384239fdd01d0a8c">llvm::codeview::SymbolVisitorCallbackPipeline::visitSymbolEnd</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/symbolvisitorcallbacks/#a3cf54df88b8d85b5f6d033cd671e1541">llvm::codeview::SymbolVisitorCallbacks::visitSymbolEnd</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvsymbolvisitor/#a1789b181a5b67fbf120a7338f5fd7340">llvm::logicalview::LVSymbolVisitor::visitSymbolEnd</a>, <a href="/web-llvm/docs/api/structs/anonymous-codeviewyamldebugsections-cpp-/subsectionconversionvisitor/#a167e306fc412a1eedbd1c70c7ed838bb">anonymous{CodeViewYAMLDebugSections.cpp}::SubsectionConversionVisitor::visitSymbols</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/cvsymbolvisitor/#ace5661625caed8c5d8e8a7d062742576">llvm::codeview::CVSymbolVisitor::visitSymbolStream</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/cvsymbolvisitor/#a7ad23d917b096777db5fc5911eb0fc13">llvm::codeview::CVSymbolVisitor::visitSymbolStream</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/cvsymbolvisitor/#a386edc0742a93b59caac3efd31876012">llvm::codeview::CVSymbolVisitor::visitSymbolStreamFiltered</a>, <a href="/web-llvm/docs/api/classes/anonymous-recordname-cpp-/typenamecomputer/#a9aeaed78ef52222a00e7a613302822f6">anonymous{RecordName.cpp}::TypeNameComputer::visitTypeBegin</a>, <a href="/web-llvm/docs/api/classes/anonymous-recordname-cpp-/typenamecomputer/#aff17088f0a5f5f37dbe952a47c9a3a5f">anonymous{RecordName.cpp}::TypeNameComputer::visitTypeBegin</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/typedumpvisitor/#a418b79f4288d791e538fa1cf1c4a6960">llvm::codeview::TypeDumpVisitor::visitTypeBegin</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/typerecordmapping/#a0b455766e2cade6732d4d6680e4512e4">llvm::codeview::TypeRecordMapping::visitTypeBegin</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/typevisitorcallbackpipeline/#ada1728cc0f7d1b909964bb740eed9f0c">llvm::codeview::TypeVisitorCallbackPipeline::visitTypeBegin</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/typevisitorcallbackpipeline/#a894c00ab1c942f767a687820577ee226">llvm::codeview::TypeVisitorCallbackPipeline::visitTypeBegin</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/typevisitorcallbacks/#af6871f9b4f3fa5eec1117b95cdd2892e">llvm::codeview::TypeVisitorCallbacks::visitTypeBegin</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/typevisitorcallbacks/#a3b220e2af3aa7c27170572ebdf2a4016">llvm::codeview::TypeVisitorCallbacks::visitTypeBegin</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvtypevisitor/#a4e9d41f4bd914db515078d9370caebc3">llvm::logicalview::LVTypeVisitor::visitTypeBegin</a>, <a href="/web-llvm/docs/api/classes/anonymous-recordname-cpp-/typenamecomputer/#a8614e72557e6d00c47fae620949b3596">anonymous{RecordName.cpp}::TypeNameComputer::visitTypeEnd</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/typedumpvisitor/#a390a4a6e3ed8fd6c7a8092c748bfc040">llvm::codeview::TypeDumpVisitor::visitTypeEnd</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/typerecordmapping/#ab16fc3b46e5820e7fa3fbcdc28fbe95c">llvm::codeview::TypeRecordMapping::visitTypeEnd</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/typevisitorcallbackpipeline/#a205bdaf8fd773ac18a4f03bd820b5266">llvm::codeview::TypeVisitorCallbackPipeline::visitTypeEnd</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/typevisitorcallbacks/#a96caf39612ba2a3816e048fc47389702">llvm::codeview::TypeVisitorCallbacks::visitTypeEnd</a>, <a href="/web-llvm/docs/api/classes/anonymous-cvtypevisitor-cpp-/cvtypevisitor/#a8da6ec8dbdfe73377ef30603014ec1b1">anonymous{CVTypeVisitor.cpp}::CVTypeVisitor::visitTypeStream</a>, <a href="/web-llvm/docs/api/classes/anonymous-cvtypevisitor-cpp-/cvtypevisitor/#a53f62b25c61a46d2ebdc8b20b609ed9b">anonymous{CVTypeVisitor.cpp}::CVTypeVisitor::visitTypeStream</a>, <a href="/web-llvm/docs/api/classes/anonymous-cvtypevisitor-cpp-/cvtypevisitor/#a2cc2e82b1121af75b758523e7881a77e">anonymous{CVTypeVisitor.cpp}::CVTypeVisitor::visitTypeStream</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/debugsubsectionvisitor/#a847b665b86858ee7a7e7d81ceeb7372d">llvm::codeview::DebugSubsectionVisitor::visitUnknown</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/typedumpvisitor/#a573db82ee8c5c16c37d3a3b0293920ea">llvm::codeview::TypeDumpVisitor::visitUnknownMember</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/typevisitorcallbackpipeline/#a9e3fd84a5b1ece3642a97168096d689e">llvm::codeview::TypeVisitorCallbackPipeline::visitUnknownMember</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/typevisitorcallbacks/#a0a6a92b5ee8fe2bcc2e6c2d0b08b8f10">llvm::codeview::TypeVisitorCallbacks::visitUnknownMember</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvlogicalvisitor/#a92e358bb94c8f56f008ff91345a9092e">llvm::logicalview::LVLogicalVisitor::visitUnknownMember</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvtypevisitor/#a3f18855e9d4c95bf6e60649c9fccbabb">llvm::logicalview::LVTypeVisitor::visitUnknownMember</a>, <a href="/web-llvm/docs/api/classes/anonymous-symboldumper-cpp-/cvsymboldumperimpl/#abd0a783cd91db1983a177bdfee26a6a9">anonymous{SymbolDumper.cpp}::CVSymbolDumperImpl::visitUnknownSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/symbolvisitorcallbackpipeline/#aa6f98ff554bf57718a815baeba48b3e8">llvm::codeview::SymbolVisitorCallbackPipeline::visitUnknownSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/symbolvisitorcallbacks/#ac59602cdb4f3167611a53762e255f777">llvm::codeview::SymbolVisitorCallbacks::visitUnknownSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvsymbolvisitor/#aff047591187b7be4e82469398177bd37">llvm::logicalview::LVSymbolVisitor::visitUnknownSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/typedumpvisitor/#a67c74870b34ef151a36efc97cddfaa03">llvm::codeview::TypeDumpVisitor::visitUnknownType</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/typevisitorcallbackpipeline/#af9df5631dcc1e605b5661ec9cd2f3def">llvm::codeview::TypeVisitorCallbackPipeline::visitUnknownType</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/typevisitorcallbacks/#a343e67d8d1d20c495ed3d575a5d9acf7">llvm::codeview::TypeVisitorCallbacks::visitUnknownType</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvlogicalvisitor/#aa583f2e4b792c5eadd2aecc04e1c2361">llvm::logicalview::LVLogicalVisitor::visitUnknownType</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvtypevisitor/#af1bc192b9d8d767a4c5fee8088e5880e">llvm::logicalview::LVTypeVisitor::visitUnknownType</a>, <a href="/web-llvm/docs/api/classes/llvm/lto/thinbackendproc/#a6ae1e279d2396c526f205fd7f593cbbc">llvm::lto::ThinBackendProc::wait</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#aec780866abec43baa4de787a2b8aa4fa">llvm::orc::walkLibunwindEHFrameSection</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/resourcetracker/#ac946e909dda8f139167b7d28956f1e51">llvm::orc::ResourceTracker::withResourceKeyDo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/offloading/#ae8476f6b1335517f24e2a9236806f425">llvm::offloading::wrapCudaBinary</a>, <a href="/web-llvm/docs/api/namespaces/llvm/offloading/#ad14a169be48a9fd66713e2d0a963223c">llvm::offloading::wrapHIPBinary</a>, <a href="/web-llvm/docs/api/namespaces/llvm/offloading/#a8acaeff0d5377d081e04c0f9c1a0726e">llvm::offloading::wrapOpenMPBinaries</a>, <a href="/web-llvm/docs/api/classes/anonymous-dxcontaineremitter-cpp-/dxcontainerwriter/#a2eaf28aa28d4a895154c853bf0c4480f">anonymous{DXContainerEmitter.cpp}::DXContainerWriter::write</a>, <a href="/web-llvm/docs/api/classes/anonymous-thinltocodegenerator-cpp-/modulecacheentry/#afc375cbf1e270a0914a82cba21fe3f10">anonymous{ThinLTOCodeGenerator.cpp}::ModuleCacheEntry::write</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/binarywriter/#ac4946ac3df4a88e078136a4444ef1185">llvm::objcopy::elf::BinaryWriter::write</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/elfwriter/#afba8988590ae275a08b0efd42c27d274">llvm::objcopy::elf::ELFWriter&lt; ELFT &gt;::write</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/ihexwriter/#a55b825280ca6a39c6efb5dbe112deb24">llvm::objcopy::elf::IHexWriter::write</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/srecwriter/#a7a24531cda5be105db8d81756a3a9705">llvm::objcopy::elf::SRECWriter::write</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/macho/machowriter/#a664a6fc223b56ef4fec7642360062ae0">llvm::objcopy::macho::MachOWriter::write</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/wasm/writer/#a0c6b0217a29520ff740cb32952eac94f">llvm::objcopy::wasm::Writer::write</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/xcoff/xcoffwriter/#af3adedc8850f537a3ba8e71bba9d9934">llvm::objcopy::xcoff::XCOFFWriter::write</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7363e46d4dd6c78affffabaea0de482b">llvm::write</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae80a7e9590f1bec7c0ca3b271e88a735">llvm::writeArchiveToStream</a>, <a href="/web-llvm/docs/api/classes/llvm/binarystreamwriter/#a1e5febb5c471f88c785519a211871b01">llvm::BinaryStreamWriter::writeArray</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/inprocessmemoryaccess/#a8c1c2aabe1be663366f019131541ee4b">llvm::orc::InProcessMemoryAccess::writeBuffersAsync</a>, <a href="/web-llvm/docs/api/classes/llvm/appendingbinarybytestream/#a5da8fa1c8cd50b1cccfb561b40d88532">llvm::AppendingBinaryByteStream::writeBytes</a>, <a href="/web-llvm/docs/api/classes/llvm/binarystreamwriter/#abb614d7e749a1af26c1d719b28ba4fb7">llvm::BinaryStreamWriter::writeBytes</a>, <a href="/web-llvm/docs/api/classes/llvm/msf/writablemappedblockstream/#abe3861e116c9da3ce15c4dd46a1bfaf7">llvm::msf::WritableMappedBlockStream::writeBytes</a>, <a href="/web-llvm/docs/api/classes/llvm/mutablebinarybytestream/#ab01e4768ed6edae5181351ec2fc8be15">llvm::MutableBinaryByteStream::writeBytes</a>, <a href="/web-llvm/docs/api/classes/llvm/binarystreamwriter/#a07608f1ac2a8045b1b72108b840a8ca3">llvm::BinaryStreamWriter::writeCString</a>, <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/dwarfemitter-cpp/#a27a0ea7c31356a5938a3fe32e8eb3103">writeDWARFLists</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ifs/#a101c2836638ffc1c34e2e502ad68d0da">llvm::ifs::writeELFBinaryToFile</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ifs/#ac489320a2b134dff19a7fc52f0544ec1">llvm::ifs::writeIFSToOutputStream</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#af9d2c5b5d2afb86f9cdaef1946b79f6c">llvm::object::writeImportLibrary</a>, <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/dwarfemitter-cpp/#a563a2cfcb7521ea43f914110e6336fc4">writeListEntry</a>, <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/dwarfemitter-cpp/#aea61050e03d2b5de9ef6621624e66122">writeListEntryAddress</a>, <a href="/web-llvm/docs/api/classes/anonymous-machoemitter-cpp-/machowriter/#a613e65e4ab9eafc574abffdbe4c1063a">anonymous{MachOEmitter.cpp}::MachOWriter::writeMachO</a>, <a href="/web-llvm/docs/api/classes/anonymous-machoemitter-cpp-/universalwriter/#a3e3da0c5ca6b6afd845ca7417bb1034e">anonymous{MachOEmitter.cpp}::UniversalWriter::writeMachO</a>, <a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprofwriter-cpp/#ac9e41242e334c46de6b89a79135b8ca3">writeMemProfV2</a>, <a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprofwriter-cpp/#a8cad3eb0bfb43723ba5976243ec78090">writeMemProfV3</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xray/anonymous-fdrtracewriter-cpp-/#a53787fd7c0f79784e176e673a77a071f">llvm::xray::anonymous{FDRTraceWriter.cpp}::writeMetadata</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/aarch64/#a1d7cfdefe09dc42a8d92cdf8e1ba7237">llvm::jitlink::aarch64::writeMovRegImm64Seq</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/aarch64/#a5c13edb875d691dffc20e456bdc41538">llvm::jitlink::aarch64::writeMovRegRegSeq</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/inprocessmemoryaccess/#a038b06a69e161afa168e0cf438dc9658">llvm::orc::InProcessMemoryAccess::writePointersAsync</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/gsistreambuilder-cpp/#aab81320800a686e576d9608a6bb470fe">writePublics</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#ae05f3870c8f629c981951b96ccbee160">llvm::pdb::writeSparseBitVector</a>, <a href="/web-llvm/docs/api/classes/llvm/binarystreamwriter/#a5e81cda2da9491cb31a8896967aafdfc">llvm::BinaryStreamWriter::writeStreamRef</a>, <a href="/web-llvm/docs/api/classes/llvm/codegendatawriter/#a3d66364f052981f528220d5580ad012f">llvm::CodeGenDataWriter::writeText</a>, <a href="/web-llvm/docs/api/classes/llvm/instrprofwriter/#a2a76e869a218e271ec68f8a68968fde2">llvm::InstrProfWriter::writeText</a>, <a href="/web-llvm/docs/api/classes/llvm/macho/textapiwriter/#a8c38bdeed4b96c01ab6e3f3368998030">llvm::MachO::TextAPIWriter::writeToStream</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/inprocessmemoryaccess/#a4b22da944d53023460365031a7525703">llvm::orc::InProcessMemoryAccess::writeUInt16sAsync</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/inprocessmemoryaccess/#a14b80e67313b27c06584797a360185bc">llvm::orc::InProcessMemoryAccess::writeUInt32sAsync</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/inprocessmemoryaccess/#aec0b68bda47368d41602d9f70834ba0e">llvm::orc::InProcessMemoryAccess::writeUInt64sAsync</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/inprocessmemoryaccess/#a14fa49b36b89bca87fb928aa64e76dbf">llvm::orc::InProcessMemoryAccess::writeUInt8sAsync</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/machouniversalwriter-cpp/#a9f26efe564d8f7f1afb5f3033156d58d">writeUniversalArchsToStream</a>, <a href="/web-llvm/docs/api/classes/llvm/jitlink/compactunwindmanager/#af022b036126d33df3324995c04b55864">llvm::jitlink::CompactUnwindManager&lt; CURecTraits &gt;::writeUnwindInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/dwarfemitter-cpp/#a5626523faa24e3e575e266f43be2a387">writeVariableSizedInteger</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#a1d0960c42dd4907d39ac227b8c3353c5">llvm::object::writeWindowsResourceCOFF</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/epcgenericrtdyldmemorymanager/#a484cb5a168161b0ae8fe06f025cacfc4">llvm::orc::EPCGenericRTDyldMemoryManager::~EPCGenericRTDyldMemoryManager</a> and <a href="/web-llvm/docs/api/classes/llvm/errorasoutparameter/#a765e53d971b833ce71bcf56164890eb4">llvm::ErrorAsOutParameter::~ErrorAsOutParameter</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/error-h">Error.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>

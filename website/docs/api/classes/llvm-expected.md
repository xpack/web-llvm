---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/expected
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `Expected` Class Template Reference

<p>Tagged union holding either a T or a <a href="/web-llvm/docs/api/classes/llvm/error">Error</a>. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;class T&gt;
class llvm::Expected&lt;T&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/error-h">llvm/Support/Error.h</a>"
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/msvcpexpected">MSVCPExpected&lt;T&gt;</a></td>
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

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ae0caa4f0cbab794b7671e670e9299be9">storage_type</a> = std::conditional_t&lt; isRef, <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">wrap</a>, T &gt;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af57dfa23e049f93c9b3e5b7d3435b259">value_type</a> = T</td>
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

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac62579b6082f2c37ef9cb67929128448">wrap</a> = std::reference_wrapper&lt; std::remove_reference_t&lt; T &gt; &gt;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a6c69668dea3ccb63e6972a051a254300">error_type</a> = std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/errorinfobase">ErrorInfoBase</a> &gt;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a3e3fd51921ba7d57c8d67a84612ce30d">reference</a> = std::remove_reference_t&lt; T &gt; &amp;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aaeb6a50e8da9bc4b8ee8ae92eec41daa">const_reference</a> = <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::remove_reference_t&lt; T &gt; &amp;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a37fce4288b48b9c0cb392ea13994786a">pointer</a> = std::remove_reference_t&lt; T &gt; *</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a3981d0952968bb1d08388abfb0803c83">const_pointer</a> = <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::remove_reference_t&lt; T &gt; *</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class T1&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ab847dec75020c9483d18247c4e79828e">ExpectedAsOutParameter</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class OtherT&gt;</div></td>
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

</table>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a88c9308b16c3935bc567d76748a30e05">Expected</a> (Error &amp;&amp;Err)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create an Expected&lt;T&gt; error value from the given <a href="/web-llvm/docs/api/classes/llvm/error">Error</a>. <a href="#a88c9308b16c3935bc567d76748a30e05">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a7b6348247ddfc0a62cc1a5870a22324e">Expected</a> (ErrorSuccess)=delete</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Forbid to convert from <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">Error::success()</a> implicitly, this avoids having Expected&lt;T&gt; foo() { return <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">Error::success()</a>; } which compiles otherwise but triggers the assertion above. <a href="#a7b6348247ddfc0a62cc1a5870a22324e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename OtherT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a4f8d24ff610fcb7ad32c767d167be350">Expected</a> (OtherT &amp;&amp;Val, std::enable_if_t&lt; std::is_convertible_v&lt; OtherT, T &gt; &gt; *=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create an Expected&lt;T&gt; success value from the given OtherT value, which must be convertible to T. <a href="#a4f8d24ff610fcb7ad32c767d167be350">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#aea407cbf7a3b1b6b0309dd655ffa8540">Expected</a> (Expected &amp;&amp;Other)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Move construct an Expected&lt;T&gt; value. <a href="#aea407cbf7a3b1b6b0309dd655ffa8540">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class OtherT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#af60344963e1b79ba78167575158f77b8">Expected</a> (Expected&lt; OtherT &gt; &amp;&amp;Other, std::enable_if_t&lt; std::is_convertible_v&lt; OtherT, T &gt; &gt; *=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Move construct an Expected&lt;T&gt; value from an Expected&lt;OtherT&gt;, where OtherT must be convertible to T. <a href="#af60344963e1b79ba78167575158f77b8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class OtherT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a171ff66f79ef0d183a947f7f7dc58256">Expected</a> (Expected&lt; OtherT &gt; &amp;&amp;Other, std::enable_if_t&lt;!std::is_convertible_v&lt; OtherT, T &gt; &gt; *=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Move construct an Expected&lt;T&gt; value from an Expected&lt;OtherT&gt;, where OtherT isn't convertible to T. <a href="#a171ff66f79ef0d183a947f7f7dc58256">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a561f9151de63b15145a997054e3bdadd">~Expected</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Destroy an Expected&lt;T&gt;. <a href="#a561f9151de63b15145a997054e3bdadd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad0b1ca9ab1d638ff26710baabe3a8d79">operator=</a> (Expected &amp;&amp;Other)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Move-assign from another Expected&lt;T&gt;. <a href="#ad0b1ca9ab1d638ff26710baabe3a8d79">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#abedc24a1407796eedbee8ba9786d0387">operator bool</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return false if there is an error. <a href="#abedc24a1407796eedbee8ba9786d0387">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">pointer</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a273e725e373dcdbdafea1c526c3eca76">operator-&gt;</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns a pointer to the stored T value. <a href="#a273e725e373dcdbdafea1c526c3eca76">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">const_pointer</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac854a40e2030f58580fbb9408120bb76">operator-&gt;</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns a const pointer to the stored T value. <a href="#ac854a40e2030f58580fbb9408120bb76">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">reference</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a3ec571223a5cb9d58e0f33b39eeb4fa5">operator*</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns a reference to the stored T value. <a href="#a3ec571223a5cb9d58e0f33b39eeb4fa5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">const_reference</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a048c528320b2cd7daab58c8305fbe1b4">operator*</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns a const reference to the stored T value. <a href="#a048c528320b2cd7daab58c8305fbe1b4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">reference</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad26ecbb6920f4ea55f5ed4f64e52342d">get</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns a reference to the stored T value. <a href="#ad26ecbb6920f4ea55f5ed4f64e52342d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">const_reference</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a5cabea6e703ddb31e0274415184cad60">get</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns a const reference to the stored T value. <a href="#a5cabea6e703ddb31e0274415184cad60">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class OtherT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a1b82a016e5720d46b0d2b5e26e80dd52">moveInto</a> (OtherT &amp;Value, std::enable_if_t&lt; std::is_assignable_v&lt; OtherT &amp;, T &amp;&amp; &gt; &gt; *=nullptr) &amp;&amp;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns <em><a href="#a94789df4ebd03dc008e8adebaa66ac1f">takeError()</a></em> after moving the held T (if any) into <span class="doxyComputerOutput">V</span>. <a href="#a1b82a016e5720d46b0d2b5e26e80dd52">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ErrT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a6fd0eefc5601ec69856713af5e06f270">errorIsA</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> that this Expected&lt;T&gt; is an error of type ErrT. <a href="#a6fd0eefc5601ec69856713af5e06f270">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a94789df4ebd03dc008e8adebaa66ac1f">takeError</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Take ownership of the stored error. <a href="#a94789df4ebd03dc008e8adebaa66ac1f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class OtherT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ae07f50012045d91158053277a40a6459">moveConstruct</a> (Expected&lt; OtherT &gt; &amp;&amp;Other)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class OtherT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a1dc1569ee8eab52e145e7bb4370e175b">moveAssign</a> (Expected&lt; OtherT &gt; &amp;&amp;Other)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">pointer</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ab58f17e0468d700f27c11fe9fcfca24e">toPointer</a> (pointer Val)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">const_pointer</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a118fc76ca1a4ec9f9c07479fcffa695a">toPointer</a> (const_pointer Val) const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">pointer</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aa9ee5143ca67da46a108d7a7c086b435">toPointer</a> (wrap *Val)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">const_pointer</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a9b2c629f7f4f1dc9ed36415e2ec64c8e">toPointer</a> (const wrap *Val) const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#ae0caa4f0cbab794b7671e670e9299be9">storage_type</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a32254986f7c30a662f89788d56599907">getStorage</a> ()</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#ae0caa4f0cbab794b7671e670e9299be9">storage_type</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aa823369a97c477133d2ace93beb63fe9">getStorage</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">error_type *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a657b2f9c2974428839e5fe9d9070ef6d">getErrorStorage</a> ()</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> error_type *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a8e978dc79354e3875c14d97998ddeec3">getErrorStorage</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aff4bdb1a95635f9f55912a08dd41303c">setUnchecked</a> ()</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a73d2ade4315308565b2eddabf24be3a1">assertIsChecked</a> () const</td>
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

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/alignedchararrayunion">AlignedCharArrayUnion</a>&lt; <a href="#ae0caa4f0cbab794b7671e670e9299be9">storage_type</a> &gt;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a8a3ea48fb65171db3c9261bd6b4fab0f">TStorage</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/alignedchararrayunion">AlignedCharArrayUnion</a>&lt; error_type &gt;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad408d863dd19f7d6d4eb1cac2d431797">ErrorStorage</a></td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">union <a href="/web-llvm/docs/api/classes/llvm/expected">llvm::Expected</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af531774e2bb69dc5963673b15a2cd1bc"></a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a533184e01e9f06afb38af85596ccb388">HasError</a></td>
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

## Private Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class T1&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a1f5100bf69cb7eef99923736da3a8c48">compareThisIfSameType</a> (const T1 &amp;a, const T1 &amp;b)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class T1, class T2&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a5c83150adf5fe34e625d766e93da26f6">compareThisIfSameType</a> (const T1 &amp;, const T2 &amp;)</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static constexpr bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aa48f5f75b32e872c95272cd904181c22">isRef</a> = std::is_reference_v&lt;T&gt;</td>
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

<p>Tagged union holding either a T or a <a href="/web-llvm/docs/api/classes/llvm/error">Error</a>.</p>


<p>This class parallels <a href="/web-llvm/docs/api/classes/llvm/erroror">ErrorOr</a>, but replaces error_code with <a href="/web-llvm/docs/api/classes/llvm/error">Error</a>. Since <a href="/web-llvm/docs/api/classes/llvm/error">Error</a> cannot be copied, this class replaces <a href="/web-llvm/docs/api/files/lib/lib/targetparser/riscvisainfo-cpp/#ad73113c3c3a7bfb64703238645f6fc1e">getError()</a> with <a href="#a94789df4ebd03dc008e8adebaa66ac1f">takeError()</a>. It also adds an bool <a href="#a6fd0eefc5601ec69856713af5e06f270">errorIsA&lt;ErrT&gt;()</a> method for testing the error class type.</p>


<p>Example usage of 'Expected&lt;T&gt;' as a function return type:</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#a815f6718ecaf8321aab0587f5e62d048">Expected&lt;int&gt;</a> myDivide(</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>) {</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a> == 0) {</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// return an Error</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-llvm/docs/api/namespaces/llvm/#a4d2fd926089a58d482fb67a362e11bad">createStringError</a>(<a href="/web-llvm/docs/api/namespaces/llvm/#a2b43c21951d0948b34bcf7019949032d">inconvertibleErrorCode</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">                             </span><span class="doxyHighlightStringLiteral">"B must not be zero!"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// return an integer</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a> / <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Checking the results of to a function returning 'Expected&lt;T&gt;':</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a> = <a href="/web-llvm/docs/api/namespaces/llvm/ms-demangle/#afb795990ffc0cb7321e7d1eacc246324a8eea62084ca7e541d918e823422bd82e">Result</a>.takeError()) {</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// We must consume the error. Typically one of:</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// - return the error to our caller</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// - toString(), when logging</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// - consumeError(), to silently swallow the error</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// - handleErrors(), to distinguish error types</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-llvm/docs/api/namespaces/llvm/#a9a7b5c68c90f85baaedaa854cc5002cc">errs</a>() &lt;&lt; </span><span class="doxyHighlightStringLiteral">"Problem with division "</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#aba83a013c55b19255697393a10d9165e">toString</a>(std::move(<a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>)) &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">// use the result</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-llvm/docs/api/namespaces/llvm/#a2d79a00fa7c56f57b87f2fe2a3f118c7">outs</a>() &lt;&lt; </span><span class="doxyHighlightStringLiteral">"The answer is "</span><span class="doxyHighlight"> &lt;&lt; *<a href="/web-llvm/docs/api/namespaces/llvm/ms-demangle/#afb795990ffc0cb7321e7d1eacc246324a8eea62084ca7e541d918e823422bd82e">Result</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n"</span><span class="doxyHighlight">;</span></span></div>

</div>


<p>For unit-testing a function returning an 'Expected&lt;T&gt;', see the 'EXPECT_THAT_EXPECTED' macros in <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/testing/include/llvm/testing/support/error-h">llvm/Testing/Support/Error.h</a></p>


<p>Definition at line 481 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/error-h">Error.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### storage\_type {#ae0caa4f0cbab794b7671e670e9299be9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::Expected&lt; T &gt;::storage_type =  std::conditional_t&lt;isRef, wrap, T&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 492 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/error-h">Error.h</a>.</p>

</div>
</div>

### value\_type {#af57dfa23e049f93c9b3e5b7d3435b259}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::Expected&lt; T &gt;::value_type =  T</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 493 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/error-h">Error.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Typedefs

### const\_pointer {#a3981d0952968bb1d08388abfb0803c83}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::Expected&lt; T &gt;::const_pointer =  const std::remove_reference_t&lt;T&gt; *</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 499 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/error-h">Error.h</a>.</p>

</div>
</div>

### const\_reference {#aaeb6a50e8da9bc4b8ee8ae92eec41daa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::Expected&lt; T &gt;::const_reference =  const std::remove_reference_t&lt;T&gt; &amp;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 497 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/error-h">Error.h</a>.</p>

</div>
</div>

### error\_type {#a6c69668dea3ccb63e6972a051a254300}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::Expected&lt; T &gt;::error_type =  std::unique_ptr&lt;ErrorInfoBase&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 489 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/error-h">Error.h</a>.</p>

</div>
</div>

### pointer {#a37fce4288b48b9c0cb392ea13994786a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::Expected&lt; T &gt;::pointer =  std::remove_reference_t&lt;T&gt; *</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 498 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/error-h">Error.h</a>.</p>

</div>
</div>

### reference {#a3e3fd51921ba7d57c8d67a84612ce30d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::Expected&lt; T &gt;::reference =  std::remove_reference_t&lt;T&gt; &amp;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 496 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/error-h">Error.h</a>.</p>

</div>
</div>

### wrap {#ac62579b6082f2c37ef9cb67929128448}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::Expected&lt; T &gt;::wrap =  std::reference_wrapper&lt;std::remove_reference_t&lt;T&gt;&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 487 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/error-h">Error.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Friends

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


<p>Definition at line 483 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/error-h">Error.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/msvcpexpected/#a01afd76b2f9a9da27b6a986c8106c6e1">llvm::MSVCPExpected&lt; T &gt;::MSVCPExpected</a>, <a href="/web-llvm/docs/api/classes/llvm/msvcpexpected/#ac45d99ddcd1ecfd3ca84b5525e5106b5">llvm::MSVCPExpected&lt; T &gt;::MSVCPExpected</a>, <a href="/web-llvm/docs/api/classes/llvm/msvcpexpected/#a39ac2df989cbd6e21ee1a317b2d1f4bc">llvm::MSVCPExpected&lt; T &gt;::MSVCPExpected</a>, <a href="/web-llvm/docs/api/classes/llvm/msvcpexpected/#a08cbf1b401596a713a9978b87dc4674d">llvm::MSVCPExpected&lt; T &gt;::MSVCPExpected</a>, <a href="/web-llvm/docs/api/classes/llvm/msvcpexpected/#a43963d042f4d7933cd2e4c1171b64c2e">llvm::MSVCPExpected&lt; T &gt;::MSVCPExpected</a> and <a href="/web-llvm/docs/api/classes/llvm/msvcpexpected/#a4ce3a612eef5e617120ab3f4c9f4a144">llvm::MSVCPExpected&lt; T &gt;::MSVCPExpected</a>.</p>

</div>
</div>

### ExpectedAsOutParameter {#ab847dec75020c9483d18247c4e79828e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/expectedasoutparameter">ExpectedAsOutParameter</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 482 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/error-h">Error.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### Expected() {#a88c9308b16c3935bc567d76748a30e05}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::Expected&lt; T &gt;::Expected (<a href="/web-llvm/docs/api/classes/llvm/error">Error</a> &amp;&amp; Err)</td>
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

<p>Create an Expected&lt;T&gt; error value from the given <a href="/web-llvm/docs/api/classes/llvm/error">Error</a>.</p>

<p>Definition at line 503 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/error-h">Error.h</a>.</p>

</div>
</div>

### Expected() {#a7b6348247ddfc0a62cc1a5870a22324e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::Expected&lt; T &gt;::Expected (<a href="/web-llvm/docs/api/classes/llvm/errorsuccess">ErrorSuccess</a>)</td>
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

<p>Forbid to convert from <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">Error::success()</a> implicitly, this avoids having Expected&lt;T&gt; foo() { return <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">Error::success()</a>; } which compiles otherwise but triggers the assertion above.</p>

<p>Definition at line 517 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/error-h">Error.h</a>.</p>

</div>
</div>

### Expected() {#a4f8d24ff610fcb7ad32c767d167be350}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename OtherT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::Expected&lt; T &gt;::Expected (OtherT &amp;&amp; Val, std::enable_if_t&lt; std::is_convertible_v&lt; OtherT, T &gt; &gt; *)</td>
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

<p>Create an Expected&lt;T&gt; success value from the given OtherT value, which must be convertible to T.</p>

<p>Definition at line 522 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/error-h">Error.h</a>.</p>

</div>
</div>

### Expected() {#aea407cbf7a3b1b6b0309dd655ffa8540}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::Expected&lt; T &gt;::Expected (<a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a> &amp;&amp; Other)</td>
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

<p>Move construct an Expected&lt;T&gt; value.</p>

<p>Definition at line 535 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/error-h">Error.h</a>.</p>

</div>
</div>

### Expected() {#af60344963e1b79ba78167575158f77b8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class OtherT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::Expected&lt; T &gt;::Expected (<a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; OtherT &gt; &amp;&amp; Other, std::enable_if_t&lt; std::is_convertible_v&lt; OtherT, T &gt; &gt; *)</td>
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

<p>Move construct an Expected&lt;T&gt; value from an Expected&lt;OtherT&gt;, where OtherT must be convertible to T.</p>

<p>Definition at line 540 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/error-h">Error.h</a>.</p>

</div>
</div>

### Expected() {#a171ff66f79ef0d183a947f7f7dc58256}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class OtherT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::Expected&lt; T &gt;::Expected (<a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; OtherT &gt; &amp;&amp; Other, std::enable_if_t&lt;!std::is_convertible_v&lt; OtherT, T &gt; &gt; *)</td>
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

<p>Move construct an Expected&lt;T&gt; value from an Expected&lt;OtherT&gt;, where OtherT isn't convertible to T.</p>

<p>Definition at line 548 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/error-h">Error.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~Expected() {#a561f9151de63b15145a997054e3bdadd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::Expected&lt; T &gt;::~Expected ()</td>
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

<p>Destroy an Expected&lt;T&gt;.</p>

<p>Definition at line 561 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/error-h">Error.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator bool() {#abedc24a1407796eedbee8ba9786d0387}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::Expected&lt; T &gt;::operator bool ()</td>
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

<p>Return false if there is an error.</p>

<p>Definition at line 570 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/error-h">Error.h</a>.</p>

</div>
</div>

### operator-&gt;() {#a273e725e373dcdbdafea1c526c3eca76}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">pointer llvm::Expected&lt; T &gt;::operator-&gt; ()</td>
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

<p>Returns a pointer to the stored T value.</p>

<p>Definition at line 616 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/error-h">Error.h</a>.</p>

</div>
</div>

### operator-&gt;() {#ac854a40e2030f58580fbb9408120bb76}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_pointer llvm::Expected&lt; T &gt;::operator-&gt; ()</td>
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

<p>Returns a const pointer to the stored T value.</p>

<p>Definition at line 622 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/error-h">Error.h</a>.</p>

</div>
</div>

### operator\*() {#a3ec571223a5cb9d58e0f33b39eeb4fa5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">reference llvm::Expected&lt; T &gt;::operator* ()</td>
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

<p>Returns a reference to the stored T value.</p>

<p>Definition at line 628 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/error-h">Error.h</a>.</p>

</div>
</div>

### operator\*() {#a048c528320b2cd7daab58c8305fbe1b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_reference llvm::Expected&lt; T &gt;::operator* ()</td>
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

<p>Returns a const reference to the stored T value.</p>

<p>Definition at line 634 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/error-h">Error.h</a>.</p>

</div>
</div>

### operator=() {#ad0b1ca9ab1d638ff26710baabe3a8d79}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected &amp; llvm::Expected&lt; T &gt;::operator= (<a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a> &amp;&amp; Other)</td>
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

<p>Move-assign from another Expected&lt;T&gt;.</p>

<p>Definition at line 555 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/error-h">Error.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/msvcpexpected/#a4fb52a47db5a326da0182976965bb721">llvm::MSVCPExpected&lt; T &gt;::operator=</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### errorIsA() {#a6fd0eefc5601ec69856713af5e06f270}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ErrT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Expected&lt; T &gt;::errorIsA ()</td>
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

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> that this Expected&lt;T&gt; is an error of type ErrT.</p>

<p>Definition at line 600 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/error-h">Error.h</a>.</p>

</div>
</div>

### get() {#ad26ecbb6920f4ea55f5ed4f64e52342d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">reference llvm::Expected&lt; T &gt;::get ()</td>
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

<p>Returns a reference to the stored T value.</p>

<p>Definition at line 578 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/error-h">Error.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/bitstreamcursor/#a49c750caac5ed5f8a5333e14ada8d5ed">llvm::BitstreamCursor::advance</a>, <a href="/web-llvm/docs/api/classes/llvm/bitstreamcursor/#a55da7252b067167e5ec22e4456503e6d">llvm::BitstreamCursor::advanceSkippingSubblocks</a>, <a href="/web-llvm/docs/api/classes/llvm/jitlink/jitlinkmemorymanager/#a1e12d4f3354f57e1f559b994e2bdd23c">llvm::jitlink::JITLinkMemoryManager::allocate</a>, <a href="/web-llvm/docs/api/classes/llvm/bitcodeanalyzer/#add391ff06a593c4b9cb8f05b23882a51">llvm::BitcodeAnalyzer::analyze</a>, <a href="/web-llvm/docs/api/classes/llvm/object/archive/#a8ad341cb471333b07af638089e1dc7c9">llvm::object::Archive::Archive</a>, <a href="/web-llvm/docs/api/classes/llvm/object/archivememberheader/#a0906254a905f4d1c0a68dd54c3eb65e8">llvm::object::ArchiveMemberHeader::ArchiveMemberHeader</a>, <a href="/web-llvm/docs/api/classes/llvm/object/archive/child/#a9537162135cca043a3b82f0df2816ed7">llvm::object::Archive::Child::Child</a>, <a href="/web-llvm/docs/api/classes/llvm/gsym/objectfiletransformer/#a9940b2d9a5f2a7de1dcfcdb970bf5e51">llvm::gsym::ObjectFileTransformer::convert</a>, <a href="/web-llvm/docs/api/classes/llvm/coverage/binarycoveragereader/#a75f0ba2a248f2f7f77f477bfb8d6dab2">llvm::coverage::BinaryCoverageReader::create</a>, <a href="/web-llvm/docs/api/classes/llvm/object/slice/#adbb4dbd1eb3f1a9959da3bf6baf327e4">llvm::object::Slice::create</a>, <a href="/web-llvm/docs/api/classes/llvm/object/slice/#abc9b876b08cdf5b2ec2c2bb13fbf4f65">llvm::object::Slice::create</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#a12fb918c70f7885e7a8286a74548d860">llvm::object::createBinary</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/nativesession/#a41e7e990ed77bc137febf6f0127ea8d0">llvm::pdb::NativeSession::createFromExe</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcopy/#afb660c7a07ee04be6dac1b6ce20de6d6">llvm::objcopy::createNewArchiveMembers</a>, <a href="/web-llvm/docs/api/classes/llvm/object/objectfile/#a926af6aca697fdbacb3e3ea1000f0ec4">llvm::object::ObjectFile::createObjectFile</a>, <a href="/web-llvm/docs/api/classes/llvm/object/symbolicfile/#a4ee418c47f5baa9b4b570371fc9630ce">llvm::object::SymbolicFile::createSymbolicFile</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/inlineinfo-cpp/#af862e87da17b134b4d6875d052bbbc88">decode</a>, <a href="/web-llvm/docs/api/files/lib/lib/tooldrivers/lib/tooldrivers/llvm-lib/libdriver-cpp/#a80f5931fdc6db3599ee4309f5a62b917">doList</a>, <a href="/web-llvm/docs/api/classes/llvm/bitstreamcursor/#a6ced3cd5539e8a620f270f3dbb0c48ab">llvm::BitstreamCursor::EnterSubBlock</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcopy/coff/#a03da0184bacf98a2a34f81413e7159b4">llvm::objcopy::coff::executeObjcopyOnBinary</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcopy/wasm/#ae6098aac8d9341369e7479af43f3d1c2">llvm::objcopy::wasm::executeObjcopyOnBinary</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcopy/xcoff/#a7de8195508237e49f93b19619c37707b">llvm::objcopy::xcoff::executeObjcopyOnBinary</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#a214181fcdbdcdd2ce1d22fe395716abc">llvm::object::extractOffloadBinaries</a>, <a href="/web-llvm/docs/api/classes/llvm/object/irobjectfile/#aeaceb8997142b34e42f329adfba36658">llvm::object::IRObjectFile::findBitcodeInMemBuffer</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/nativeinlinesitesymbol/#a2600af2572b1e6d73939dbb2c74e5822">llvm::pdb::NativeInlineSiteSymbol::findInlineeLinesByVA</a>, <a href="/web-llvm/docs/api/classes/llvm/mcjit/#ae7e58d02f5553c707ac40497b0e9cf26">llvm::MCJIT::findSymbol</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a98a8554492a59019e487d750863f96f2">llvm::dwarf_linker::finiteLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/mcjit/#a5236c37b672e45c22ef2ebb47518871e">llvm::MCJIT::generateCodeForModule</a>, <a href="/web-llvm/docs/api/classes/llvm/object/archive/child/#a7e08f334d391b4c5c327739f3e460465">llvm::object::Archive::Child::getAsBinary</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3a73888ec542d14d981f9b9c49c247fa">llvm::getBitcodeFileContents</a>, <a href="/web-llvm/docs/api/classes/llvm/object/archive/child/#a03bfd76bddfe1a42326e93dc3c131c8c">llvm::object::Archive::Child::getBuffer</a>, <a href="/web-llvm/docs/api/classes/llvm/object/xcoffobjectfile/#a69c221e2f2dc591094cf0b0d92fd42d3">llvm::object::XCOFFObjectFile::getCommonSymbolSizeImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/nativeexesymbol-cpp/#a60028c7e119776d3c849f7782e59661d">getDbiStreamPtr</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/nativesession-cpp/#a5ea8b61c9f761f9468bdc64078b62785">getDbiStreamPtr</a>, <a href="/web-llvm/docs/api/classes/anonymous-dwarfcontext-cpp-/threadunsafedwarfcontextstate/#a54233894e754c548da87c0d21d69003d">anonymous{DWARFContext.cpp}::ThreadUnsafeDWARFContextState::getDWOContext</a>, <a href="/web-llvm/docs/api/classes/llvm/object/elffile/#a8e0db63318e9923b354d95e0391c05db">llvm::object::ELFFile&lt; ELFT &gt;::getDynSymtabSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp/#a3d0c0fef256a92c13760a52971b805b5">getEnableSplitLTOUnitAndUnifiedFlag</a>, <a href="/web-llvm/docs/api/classes/llvm/object/xcoffobjectfile/#a81ef70b0779ce0c0e0f41c320c1f355a">llvm::object::XCOFFObjectFile::getImportFileTable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#afab90ce1024ba9b690f64237fa1a2b9b">llvm::getLazyIRModule</a>, <a href="/web-llvm/docs/api/classes/llvm/object/archive/child/#a7fa0bfbc8489a0b3472e2dd834e03c80">llvm::object::Archive::Child::getMemoryBufferRef</a>, <a href="/web-llvm/docs/api/classes/llvm/object/archive/child/#a3acd0fa308c00ead51dc16b4d46604bc">llvm::object::Archive::Child::getName</a>, <a href="/web-llvm/docs/api/classes/llvm/object/archivememberheader/#a940c0b94e9bb9dfdb69961d456b47b60">llvm::object::ArchiveMemberHeader::getName</a>, <a href="/web-llvm/docs/api/classes/llvm/object/archive/child/#a137ad5829c3f2470a0da63800c59385e">llvm::object::Archive::Child::getNext</a>, <a href="/web-llvm/docs/api/classes/llvm/object/archivememberheader/#ae1d86083ac823979ed30663f9d87118d">llvm::object::ArchiveMemberHeader::getNextChildLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/object/bigarchivememberheader/#a5ac0ddcf418dd66efde6cb208755629f">llvm::object::BigArchiveMemberHeader::getNextChildLoc</a>, <a href="/web-llvm/docs/api/structs/llvm/newarchivemember/#aadff13fd008345361aa920977e0c9e32">llvm::NewArchiveMember::getOldMember</a>, <a href="/web-llvm/docs/api/classes/llvm/object/bigarchivememberheader/#a1dee83379cd715e24ccdec554331a3cf">llvm::object::BigArchiveMemberHeader::getRawName</a>, <a href="/web-llvm/docs/api/classes/llvm/object/wasmobjectfile/#af2a2757f91471e6b80ccffa7840cb154">llvm::object::WasmObjectFile::getSymbolAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/object/xcoffobjectfile/#afba35271cc6fce891ce2bda4576c87d5">llvm::object::XCOFFObjectFile::getSymbolAlignment</a>, <a href="/web-llvm/docs/api/classes/llvm/object/xcoffobjectfile/#a26063993809b386ab934532d1af8b56c">llvm::object::XCOFFObjectFile::getSymbolFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/object/xcoffobjectfile/#af0d12d4046ba19c552b1e86fbe25abe9">llvm::object::XCOFFObjectFile::getSymbolSection</a>, <a href="/web-llvm/docs/api/classes/llvm/object/xcoffobjectfile/#a90303baf9d185097198f817b998136a6">llvm::object::XCOFFObjectFile::getSymbolSectionName</a>, <a href="/web-llvm/docs/api/classes/llvm/object/xcoffobjectfile/#ad6cf6760f283737b422b80253b8828d2">llvm::object::XCOFFObjectFile::getSymbolSize</a>, <a href="/web-llvm/docs/api/classes/llvm/object/xcoffobjectfile/#a606ab46a34eecd59e09198799a982dc4">llvm::object::XCOFFObjectFile::getSymbolType</a>, <a href="/web-llvm/docs/api/classes/llvm/bitcodereadervaluelist/#a46a07cf7b40536441b20f82ebf099e2f">llvm::BitcodeReaderValueList::getValueFwdRef</a>, <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp/#a62f979fde2fca6e52e8789ff96ad830e">hasObjCCategoryInModule</a>, <a href="/web-llvm/docs/api/classes/llvm/object/coffobjectfile/#a529853b2fbf4b976d4a99b8fa8a2f144">llvm::object::COFFObjectFile::isDebugSection</a>, <a href="/web-llvm/docs/api/classes/llvm/object/elfobjectfile/#ae62484c71e9b9ab034fe9a10717fa718">llvm::object::ELFObjectFile&lt; ELFT &gt;::isDebugSection</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a5d343559880ac878c6a999cd0e85517e">llvm::object::MachOObjectFile::isDebugSection</a>, <a href="/web-llvm/docs/api/classes/llvm/object/xcoffsymbolref/#a0b01026129dcc250501775442ac4b2e5">llvm::object::XCOFFSymbolRef::isFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/object/archivememberheader/#aa954ca2029479568fc22ecd2c427c4a2">llvm::object::ArchiveMemberHeader::isThin</a>, <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp/#a5fca99afcf20fdf62a04843e8825d03f">jumpToValueSymbolTable</a>, <a href="/web-llvm/docs/api/groups/llvmcobject/#gabe1e0252c6f4bc1b0b1b8b06f9df3546">LLVMCreateBinary</a>, <a href="/web-llvm/docs/api/groups/llvmcobject/#ga0fd9f7bc65117c049c14c047fb7907dc">LLVMCreateObjectFile</a>, <a href="/web-llvm/docs/api/groups/llvmcbitreader/#gad617205cd3fbbb1ad78e6f79f9ce0e4b">LLVMGetBitcodeModuleInContext</a>, <a href="/web-llvm/docs/api/groups/llvmcobject/#gab0bd1b18bfb07fa6d075f69f6c6dd62f">LLVMMachOUniversalBinaryCopyObjectForArch</a>, <a href="/web-llvm/docs/api/groups/llvmcbitreader/#ga668b459026b5a6c7f32325408265e616">LLVMParseBitcodeInContext</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a1307fe9528cee604862ce0966931dc6b">llvm::pdb::loadDataForEXE</a>, <a href="/web-llvm/docs/api/files/lib/lib/lto/thinltocodegenerator-cpp/#aeec26ce8d8be46abb3008a9a8e6e9107">loadModuleFromInput</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/executionsession/#a081a578f073d014fe2b1ba2c15b8b5c2">llvm::orc::ExecutionSession::lookupFlags</a>, <a href="/web-llvm/docs/api/structs/btfparser/parsecontext/#a657868ac1ec31f283f359d005dcdf905">llvm::BTFParser::ParseContext::makeExtractor</a>, <a href="/web-llvm/docs/api/namespaces/llvm/cgdata/#a05b4c070c172287759f5f2f437a3edcb">llvm::cgdata::mergeCodeGenData</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/dwarftransformer-cpp/#a254758a009a4c05dee5c67ee26e61529">parseInlineInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8b04365fc31f28e28e484d2f3cba05f1">llvm::parseIR</a>, <a href="/web-llvm/docs/api/classes/metadataloader/metadataloaderimpl/#ab5d5351419b40a9f891e4506bc2cae29">llvm::MetadataLoader::MetadataLoaderImpl::parseMetadata</a>, <a href="/web-llvm/docs/api/classes/metadataloader/metadataloaderimpl/#a4a81e1117a068de8d409b76e45c3e494">llvm::MetadataLoader::MetadataLoaderImpl::parseMetadataAttachment</a>, <a href="/web-llvm/docs/api/classes/metadataloader/metadataloaderimpl/#a71350293eab7be254484af9024a93da4">llvm::MetadataLoader::MetadataLoaderImpl::parseMetadataKinds</a>, <a href="/web-llvm/docs/api/classes/anonymous-bitcodereader-cpp-/modulesummaryindexbitcodereader/#ae9f86888a27590c2d447d2f98b5f7cf8">anonymous{BitcodeReader.cpp}::ModuleSummaryIndexBitcodeReader::parseModule</a>, <a href="/web-llvm/docs/api/classes/llvm/bitstreamcursor/#a18edc8cef7ae17b03b6d4f3ad2cda8b3">llvm::BitstreamCursor::ReadAbbrevRecord</a>, <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp/#ad3dcdf576f07a261c70f7eac121b3eec">readBlobInRecord</a>, <a href="/web-llvm/docs/api/classes/anonymous-bitcodereader-cpp-/bitcodereaderbase/#ad04f7d6a08ad25b673e16a64825f640c">anonymous{BitcodeReader.cpp}::BitcodeReaderBase::readBlockInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/bitstreamcursor/#aca82144243a4bbb08d09c0c72d636bd1">llvm::BitstreamCursor::ReadBlockInfoBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/profiledata/lib/profiledata/coverage/coveragemappingreader-cpp/#a10b27eac23635b8f40370fe8a4d19967">readCoverageMappingData</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ifs/#a6c7020c6d68f0a88ce9bf2265cc061c4">llvm::ifs::readELFFile</a>, <a href="/web-llvm/docs/api/classes/llvm/msgpack/document/#aa1132fee67332a4c0a707984b97f9b52">llvm::msgpack::Document::readFromBlob</a>, <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp/#adfdf631a8d0d417904f24c6ff6d9ed03">readIdentificationBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp/#afa9c01a1d03b3af4714df3976056d46b">readModuleTriple</a>, <a href="/web-llvm/docs/api/classes/llvm/bitstreamcursor/#a677592abe148dbc3de1ec00f3d9904c5">llvm::BitstreamCursor::readRecord</a>, <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp/#a42cc3ae15d37346d7ca743801b572770">readTriple</a>, <a href="/web-llvm/docs/api/classes/llvm/instrproflookuptrait/#ab946345c5c95f2318316edea199eaf39">llvm::InstrProfLookupTrait::readValueProfilingData</a>, <a href="/web-llvm/docs/api/classes/llvm/simplebitstreamcursor/#ae4203a4bfd3d7e5cc1a1e43a76dc4188">llvm::SimpleBitstreamCursor::ReadVBR</a>, <a href="/web-llvm/docs/api/classes/llvm/simplebitstreamcursor/#a24cc6d3ef39604b4b923083583efe349">llvm::SimpleBitstreamCursor::ReadVBR64</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lvreaderhandler-cpp/#af7b4a495780ab66e37af8b9881e7ad93">searchForExe</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/nativesession/#a10c66fa7ae2a9b589c8a2738661897ca">llvm::pdb::NativeSession::searchForPdb</a>, <a href="/web-llvm/docs/api/classes/llvm/bitstreamcursor/#a73257c6f5ab8032f22e06c1da0bc109f">llvm::BitstreamCursor::SkipBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/bitstreamcursor/#a8b13d5acaf9ffcc5a0f9969888a7db33">llvm::BitstreamCursor::skipRecord</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6d9c43797976f73bdbe0c75995f84865">llvm::SPIRVTranslate</a>, <a href="/web-llvm/docs/api/files/lib/lib/lto/ltobackend-cpp/#a2fad224b57541514de4fb5be6eb2e7f1">splitCodeGen</a>, <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#aa2807954a9bf3d29ba94545ebaa23584">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::tryEmitDwarfFileDirective</a> and <a href="/web-llvm/docs/api/files/lib/lib/object/irsymtab-cpp/#acfa5e41a619b2f37966fdc043ca96c09">upgrade</a>.</p>

</div>
</div>

### get() {#a5cabea6e703ddb31e0274415184cad60}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_reference llvm::Expected&lt; T &gt;::get ()</td>
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

<p>Returns a const reference to the stored T value.</p>

<p>Definition at line 584 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/error-h">Error.h</a>.</p>

</div>
</div>

### moveInto() {#a1b82a016e5720d46b0d2b5e26e80dd52}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class OtherT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::Expected&lt; T &gt;::moveInto (OtherT &amp; Value, std::enable_if_t&lt; std::is_assignable_v&lt; OtherT &amp;, T &amp;&amp; &gt; &gt; *)</td>
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

<p>Returns <em><a href="#a94789df4ebd03dc008e8adebaa66ac1f">takeError()</a></em> after moving the held T (if any) into <span class="doxyComputerOutput">V</span>.</p>

<p>Definition at line 591 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/error-h">Error.h</a>.</p>

</div>
</div>

### takeError() {#a94789df4ebd03dc008e8adebaa66ac1f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::Expected&lt; T &gt;::takeError ()</td>
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

<p>Take ownership of the stored error.</p>


<p>After calling this the Expected&lt;T&gt; is in an indeterminate state that can only be safely destructed. No further calls (beside the destructor) should be made on the Expected&lt;T&gt; value.</p>


<p>Definition at line 608 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/error-h">Error.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/textapi/lib/textapi/binaryreader/dylibreader-cpp/#a0bf6fb10c8a68470e3b84ab25d8e5c59">accumulateLocs</a>, <a href="/web-llvm/docs/api/classes/llvm/codegentargetmachineimpl/#acf14ffe7608cbfcc75f2858e0eaa38e7">llvm::CodeGenTargetMachineImpl::addAsmPrinter</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcopy/coff/#ac26907ff1b30d1236b06e5880af523d2">llvm::objcopy::coff::addGnuDebugLink</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/namematcher/#aec79fe06f3234497d78f290c50389b2f">llvm::objcopy::NameMatcher::addMatcher</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/pdbfilebuilder/#a3bdb84d5b8360c8bf563aeea45a6e2e7">llvm::pdb::PDBFileBuilder::addNamedStream</a>, <a href="/web-llvm/docs/api/structs/anonymous-irsymtab-cpp-/builder/#a15ad3b408efc55e12e201e1cd1dfbc45">anonymous{IRSymtab.cpp}::Builder::addSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/bitstreamcursor/#a49c750caac5ed5f8a5333e14ada8d5ed">llvm::BitstreamCursor::advance</a>, <a href="/web-llvm/docs/api/files/lib/lib/remarks/bitstreamremarkparser-cpp/#ae7a2a8c8926efbbd98b5e02b989d58bf">advanceToMetaBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/bitcodeanalyzer/#add391ff06a593c4b9cb8f05b23882a51">llvm::BitcodeAnalyzer::analyze</a>, <a href="/web-llvm/docs/api/classes/llvm/object/elffile/#a0752ad646759ea4a034a218da571ab8b">llvm::object::ELFFile&lt; ELFT &gt;::android_relas</a>, <a href="/web-llvm/docs/api/files/lib/lib/tooldrivers/lib/tooldrivers/llvm-lib/libdriver-cpp/#ac22ea488f955382d30003c56202ef80d">appendFile</a>, <a href="/web-llvm/docs/api/classes/llvm/object/archive/#a8ad341cb471333b07af638089e1dc7c9">llvm::object::Archive::Archive</a>, <a href="/web-llvm/docs/api/classes/llvm/object/archivememberheader/#a0906254a905f4d1c0a68dd54c3eb65e8">llvm::object::ArchiveMemberHeader::ArchiveMemberHeader</a>, <a href="/web-llvm/docs/api/namespaces/llvm/lto/#a89ef034c1f3a70da2446c1af1d656dab">llvm::lto::backend</a>, <a href="/web-llvm/docs/api/classes/llvm/object/bindrebaseseginfo/#aaaf6cee47713cc12a459bc779d459f13">llvm::object::BindRebaseSegInfo::BindRebaseSegInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/elfbuilder/#a519ecfe86aa85ba1247cd07c4e7c7822">llvm::objcopy::elf::ELFBuilder&lt; ELFT &gt;::build</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ifs/#ad4d4b1a08082a48e36079e1725005a2f">llvm::ifs::buildStub</a>, <a href="/web-llvm/docs/api/classes/llvm/object/archive/child/#a9537162135cca043a3b82f0df2816ed7">llvm::object::Archive::Child::Child</a>, <a href="/web-llvm/docs/api/files/lib/lib/lto/ltobackend-cpp/#a889b75e55af23f854f7f597b0e912b98">codegen</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/pdbfilebuilder/#ac8da698510d6ae1fafa8234b0c0b7b92">llvm::pdb::PDBFileBuilder::commit</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/archivewriter-cpp/#a98ad0137a31b38aa7b278f7cc52c4f3e">computeMemberData</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldimpl/#af12404037d26556e018e61366f026aaa">llvm::RuntimeDyldImpl::computeSectionStubBufSize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#acf228956812ef6e7722e8c114fe3b923">llvm::object::computeSymbolSizes</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldimpl/#af089befa203447cdf71f665a1993a997">llvm::RuntimeDyldImpl::computeTotalAllocSize</a>, <a href="/web-llvm/docs/api/classes/llvm/object/sectionref/#a9252daa21a3dd50c0c31a70c482a94a0">llvm::object::SectionRef::containsSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/gsym/objectfiletransformer/#a9940b2d9a5f2a7de1dcfcdb970bf5e51">llvm::gsym::ObjectFileTransformer::convert</a>, <a href="/web-llvm/docs/api/classes/llvm/jitlink/inprocessmemorymanager/#a4033076ae4631e6acd10a0d94e8307d1">llvm::jitlink::InProcessMemoryManager::Create</a>, <a href="/web-llvm/docs/api/classes/llvm/coverage/binarycoveragereader/#a75f0ba2a248f2f7f77f477bfb8d6dab2">llvm::coverage::BinaryCoverageReader::create</a>, <a href="/web-llvm/docs/api/classes/llvm/ifs/anonymous-elfobjhandler-cpp-/dynsym/#a96a6fbbfaf1e1d1ed2a55100142bbf28">llvm::ifs::anonymous{ELFObjHandler.cpp}::DynSym&lt; ELFT &gt;::create</a>, <a href="/web-llvm/docs/api/classes/llvm/instrprofsymtab/#aa4f8c9517d7d182974ce657311440a6b">llvm::InstrProfSymtab::create</a>, <a href="/web-llvm/docs/api/classes/llvm/lto/inputfile/#a1aa10be5e2a432c4ca74d5f70c0cd77c">llvm::lto::InputFile::create</a>, <a href="/web-llvm/docs/api/structs/llvm/minidumpyaml/stream/#a7370b2f0babea4afada61ccc3b15c54e">llvm::MinidumpYAML::Stream::create</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/nameorpattern/#ae26aada54fc59058d00a148699902f50">llvm::objcopy::NameOrPattern::create</a>, <a href="/web-llvm/docs/api/classes/llvm/object/irobjectfile/#afcce1b766f055cfac90081cebb14ad23">llvm::object::IRObjectFile::create</a>, <a href="/web-llvm/docs/api/classes/llvm/object/minidumpfile/#af4d4bfb09d6c352cfd4373d1e71ff8c8">llvm::object::MinidumpFile::create</a>, <a href="/web-llvm/docs/api/classes/llvm/object/slice/#adbb4dbd1eb3f1a9959da3bf6baf327e4">llvm::object::Slice::create</a>, <a href="/web-llvm/docs/api/classes/llvm/object/slice/#abc9b876b08cdf5b2ec2c2bb13fbf4f65">llvm::object::Slice::create</a>, <a href="/web-llvm/docs/api/classes/llvm/symbolize/symbolizableobjectfile/#a3ea94ca4d9dff028d5c6c11d8b045917">llvm::symbolize::SymbolizableObjectFile::create</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a6cc340cf5dc46cf45eb6f784577cadbd">llvm::OpenMPIRBuilder::createAtomicCapture</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#a12fb918c70f7885e7a8286a74548d860">llvm::object::createBinary</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a04285415a321e48322c08f3b9185540e">llvm::OpenMPIRBuilder::createCancel</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-runtimedyldelf-cpp-/#a4c89c8ae8b758aaf88cb3ddcb0a25c20">anonymous{RuntimeDyldELF.cpp}::createELFDebugObject</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/nativesession/#a41e7e990ed77bc137febf6f0127ea8d0">llvm::pdb::NativeSession::createFromExe</a>, <a href="/web-llvm/docs/api/structs/llvm/ltomodule/#aef913eed42f499b1e6ee98803c1976ab">llvm::LTOModule::createInputFile</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/instrbuilder/#afe394be08220c92f22489a0f952d39ee">llvm::mca::InstrBuilder::createInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvbinaryreader/#a6e3f70a5f3d1222550716fb9db632c6a">llvm::logicalview::LVBinaryReader::createInstructions</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#a4fbdc8f1be1bfc357861f63756755f65">llvm::jitlink::createLinkGraphFromELFObject</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/archive-cpp/#af194271b77c030b86d1f22f523e7f048">createMemberHeaderParseError</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcopy/#afb660c7a07ee04be6dac1b6ce20de6d6">llvm::objcopy::createNewArchiveMembers</a>, <a href="/web-llvm/docs/api/classes/llvm/object/objectfile/#a926af6aca697fdbacb3e3ea1000f0ec4">llvm::object::ObjectFile::createObjectFile</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/fileoutputbuffer-cpp/#a31b5a8b8b08e1fc483335974755720ed">createOnDiskBuffer</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#a3ea33750ee7de55492a5083c347e2ddb">createOutlinedFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a4f81b9940e1869e146636dc533455929">llvm::OpenMPIRBuilder::createParallel</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-runtimedyldelf-cpp-/#a65a5f8b0f9826efcc591765237e02b77">anonymous{RuntimeDyldELF.cpp}::createRTDyldELFObject</a>, <a href="/web-llvm/docs/api/classes/llvm/object/symbolicfile/#a4ee418c47f5baa9b4b570371fc9630ce">llvm::object::SymbolicFile::createSymbolicFile</a>, <a href="/web-llvm/docs/api/classes/llvm/listeningsocket/#a22cd57e089541409aa05153237a44729">llvm::ListeningSocket::createUnix</a>, <a href="/web-llvm/docs/api/namespaces/llvm/remarks/#ae465be28151991b2345f467899ddb5e5">llvm::remarks::createYAMLParserFromMeta</a>, <a href="/web-llvm/docs/api/classes/llvm/object/elffile/#ae2039f20cc8322c8af90fb0dec7bb772">llvm::object::ELFFile&lt; ELFT &gt;::crels</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/inlineinfo-cpp/#af862e87da17b134b4d6875d052bbbc88">decode</a>, <a href="/web-llvm/docs/api/structs/llvm/gsym/callsiteinfocollection/#ade8c3030c7854f2dce476b50e2102815">llvm::gsym::CallSiteInfoCollection::decode</a>, <a href="/web-llvm/docs/api/structs/llvm/gsym/mergedfunctionsinfo/#a3f8f8f0e7e46eb22afffe9c8c5dbe50e">llvm::gsym::MergedFunctionsInfo::decode</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/elf-cpp/#ab230da2e143b2070f404fea9287e4ed9">decodeBBAddrMapImpl</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcopy/#abe70653ea636e6b63159edf52d38afc5">llvm::objcopy::deepWriteArchive</a>, <a href="/web-llvm/docs/api/classes/llvm/filecheckpatterncontext/#a7137a381bae270178ff79807b1d096d3">llvm::FileCheckPatternContext::defineCmdlineVariables</a>, <a href="/web-llvm/docs/api/structs/llvm/newarchivemember/#a5b9ae09da2b1f1939e37ba537fdf9eb1">llvm::NewArchiveMember::detectKindFromObject</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/functionimport-cpp/#a2cdcb957bdfaac04b4bb110298fa7625">doImportingForModuleForTest</a>, <a href="/web-llvm/docs/api/files/lib/lib/tooldrivers/lib/tooldrivers/llvm-lib/libdriver-cpp/#a80f5931fdc6db3599ee4309f5a62b917">doList</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugnames/entry/#aeb639b3c403a927db9dd576cd989339d">llvm::DWARFDebugNames::Entry::dumpParentIdx</a>, <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobjcopy-cpp/#aa40e91285159d4c13a609b1810b19485">dumpSectionToFile</a>, <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machoobjcopy-cpp/#aa40e91285159d4c13a609b1810b19485">dumpSectionToFile</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcopy/wasm/#ab4c167a5e231ccb60ec1eb5552ca233b">llvm::objcopy::wasm::dumpSectionToFile</a>, <a href="/web-llvm/docs/api/classes/llvm/object/elffile/#aa438ee4f7cc143674ffb81a41c01fcb2">llvm::object::ELFFile&lt; ELFT &gt;::dynamicEntries</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/rtdyldobjectlinkinglayer/#a640efdfe6f9a9949a292dc894222e8f5">llvm::orc::RTDyldObjectLinkingLayer::emit</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarfyaml/#ad1f7f7a8ed653ac5d4c9cf22992767ea">llvm::DWARFYAML::emitDebugNames</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-dwarfemitter-cpp-/#aaace979016d4a76769f1fb2b49524361">anonymous{DWARFEmitter.cpp}::emitDebugNamesEntryPool</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldimpl/#a7dd171407e8c0e19195ea2039f3f83b6">llvm::RuntimeDyldImpl::emitSection</a>, <a href="/web-llvm/docs/api/structs/llvm/gsym/mergedfunctionsinfo/#acf6e5aa620d3dbd266db4b6d03388ed7">llvm::gsym::MergedFunctionsInfo::encode</a>, <a href="/web-llvm/docs/api/classes/llvm/bitstreamcursor/#a6ced3cd5539e8a620f270f3dbb0c48ab">llvm::BitstreamCursor::EnterSubBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/binaryoperation/#ae881b7ad9c843880674599dbe5d85dd9">llvm::BinaryOperation::eval</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcopy/#af5cb5b86f3ef0aa8fee5da90f3635bad">llvm::objcopy::executeObjcopyOnArchive</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcopy/coff/#a03da0184bacf98a2a34f81413e7159b4">llvm::objcopy::coff::executeObjcopyOnBinary</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcopy/elf/#a55af853235c79ddae3c55b4670a825dd">llvm::objcopy::elf::executeObjcopyOnBinary</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcopy/wasm/#ae6098aac8d9341369e7479af43f3d1c2">llvm::objcopy::wasm::executeObjcopyOnBinary</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcopy/xcoff/#a7de8195508237e49f93b19619c37707b">llvm::objcopy::xcoff::executeObjcopyOnBinary</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcopy/elf/#a19ff9cfed0ad17d7b4d3cde1c2b940f4">llvm::objcopy::elf::executeObjcopyOnIHex</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcopy/macho/#af0902234f18e67e03ce4b3d4d8a6a273">llvm::objcopy::macho::executeObjcopyOnMachOUniversalBinary</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcopy/elf/#ae86d4be0de6470d9b5ac070eaa69c41e">llvm::objcopy::elf::executeObjcopyOnRawBinary</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4891d521956b735baba56d4dc193f5cd">llvm::expectedToErrorOrAndEmitErrors</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfabbreviationdeclarationset/#a51185edea3b0246d3c37ee13b9553491">llvm::DWARFAbbreviationDeclarationSet::extract</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-offloadbinary-cpp-/#a426a48f358aaf6be7a95428dae0d4f31">anonymous{OffloadBinary.cpp}::extractFromObject</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#a214181fcdbdcdd2ce1d22fe395716abc">llvm::object::extractOffloadBinaries</a>, <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machoreader-cpp/#a3ebc7dd21b6e9c9781e5ac3e5d9b604e">extractSections</a>, <a href="/web-llvm/docs/api/classes/llvm/debuginfodfetcher/#a7a7fa59e9dd15a25a179bc1e05b2e270">llvm::DebuginfodFetcher::fetch</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ifs/#ad3d6148db61bf742f0e6a2c6a0f43fd9">llvm::ifs::filterIFSSyms</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/asciihexwriter/#a6c8bb3c922ce45c595377546d41f1222">llvm::objcopy::elf::ASCIIHexWriter::finalize</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/debugobject/#a4849769b779f202a7e8c0f62d9c39c4e">llvm::orc::DebugObject::finalizeAsync</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldcoffx86-64/#a57f12f7f4831372682abeda7f9e23ab8">llvm::RuntimeDyldCOFFX86_64::finalizeLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldelf/#a34d452366da541e62d1f37b1f284800d">llvm::RuntimeDyldELF::finalizeLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/gsistreambuilder/#a5d9cf5b89c50f30cf3d85ec3331b270a">llvm::pdb::GSIStreamBuilder::finalizeMsfLayout</a>, <a href="/web-llvm/docs/api/classes/llvm/debuginfodcollection/#a5c512cc4358cdcd16d9c633a4bb1a4ef">llvm::DebuginfodCollection::findBinaryPath</a>, <a href="/web-llvm/docs/api/classes/llvm/object/irobjectfile/#aeaceb8997142b34e42f329adfba36658">llvm::object::IRObjectFile::findBitcodeInMemBuffer</a>, <a href="/web-llvm/docs/api/classes/llvm/object/irobjectfile/#a803ed79cb2444088841a8c8618b21ab8">llvm::object::IRObjectFile::findBitcodeInObject</a>, <a href="/web-llvm/docs/api/classes/llvm/debuginfodcollection/#aada228a8f1796b1bb98030dc0bd3cc7c">llvm::DebuginfodCollection::findDebugBinaryPath</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/tpistream/#aab363a93f3751289108fdc859406dec4">llvm::pdb::TpiStream::findFullDeclForForwardRef</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/nativeinlinesitesymbol/#a2600af2572b1e6d73939dbb2c74e5822">llvm::pdb::NativeInlineSiteSymbol::findInlineeLinesByVA</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/nativefunctionsymbol/#a46cd97d4b03e3d554934be6b9083050b">llvm::pdb::NativeFunctionSymbol::findInlineFramesByVA</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/symbolcache/#a929ba7791d3d35e6660d8e04d3f0eb29">llvm::pdb::SymbolCache::findLineNumbersByVA</a>, <a href="/web-llvm/docs/api/classes/llvm/mcjit/#ae7e58d02f5553c707ac40497b0e9cf26">llvm::MCJIT::findSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/symbolcache/#a5ec9985ad0d83fa432f370483228cf7d">llvm::pdb::SymbolCache::findSymbolByTypeIndex</a>, <a href="/web-llvm/docs/api/namespaces/llvm/lto/#a740eafdbb24797d2db01e3d0ca05a89c">llvm::lto::findThinLTOModule</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a98a8554492a59019e487d750863f96f2">llvm::dwarf_linker::finiteLoop</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-dlltooldriver-cpp-/#ab09d28878031ffd0f73e46ea295c1e65">anonymous{DlltoolDriver.cpp}::forEachCoff</a>, <a href="/web-llvm/docs/api/classes/llvm/armjitsymbolflags/#a942d2281f1774d37e0225dfde4166ae4">llvm::ARMJITSymbolFlags::fromObjectSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/jitsymbolflags/#a6d8cec64deb620b732a8a6922c327cf7">llvm::JITSymbolFlags::fromObjectSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugaranges/#acc33f3dabfc507904e9fdfa7b0d81b51">llvm::DWARFDebugAranges::generate</a>, <a href="/web-llvm/docs/api/classes/llvm/mcjit/#a5236c37b672e45c22ef2ebb47518871e">llvm::MCJIT::generateCodeForModule</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a535b9e1cc27192f7a16a1459333b859c">llvm::DWARFUnit::getAbbreviations</a>, <a href="/web-llvm/docs/api/classes/llvm/object/abstractarchivememberheader/#a5b041d7f0753dfc105eec7d7a34d5bed">llvm::object::AbstractArchiveMemberHeader::getAccessMode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/offloading/amdgpu/#a658b1211d163ef9492d062d29de98201">llvm::offloading::amdgpu::getAMDGPUMetaDataFromImage</a>, <a href="/web-llvm/docs/api/classes/llvm/object/archive/child/#a7e08f334d391b4c5c327739f3e460465">llvm::object::Archive::Child::getAsBinary</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfformvalue/#ae6bcf159d6ccb3adb4f7409e3adbbb37">llvm::DWARFFormValue::getAsCString</a>, <a href="/web-llvm/docs/api/classes/llvm/object/coffobjectfile/#a73121eb9b654794ad353cb23f6f02100">llvm::object::COFFObjectFile::getAuxSymbol</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3a73888ec542d14d981f9b9c49c247fa">llvm::getBitcodeFileContents</a>, <a href="/web-llvm/docs/api/files/lib/lib/tooldrivers/lib/tooldrivers/llvm-lib/libdriver-cpp/#a22b51c9bbb1a0d8db169e6c766f92a78">getBitcodeFileMachine</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a85a0e09494dd27b580bd6100ffe1b39d">llvm::getBitcodeLTOInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6a08a94dbba4f43e928c1d2bff541529">llvm::getBitcodeProducerString</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a36ecc78d5979c7c250c9284a5211041d">llvm::getBitcodeTargetTriple</a>, <a href="/web-llvm/docs/api/classes/llvm/object/archive/child/#a03bfd76bddfe1a42326e93dc3c131c8c">llvm::object::Archive::Child::getBuffer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8689c14987df3736f60ec4216dedd765">llvm::getCachedOrDownloadArtifact</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a42f631dfb82c9318a72f2c1bdab57ad4">llvm::getCachedOrDownloadArtifact</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#aeeec63b61f99af14a9ca2c631e6b9cec">llvm::orc::getCOFFObjectFileSymbolInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/object/objectfile/#a0be1fdc703dfefdcd9298662351d5daf">llvm::object::ObjectFile::getCommonSymbolSize</a>, <a href="/web-llvm/docs/api/classes/llvm/object/xcoffobjectfile/#a69c221e2f2dc591094cf0b0d92fd42d3">llvm::object::XCOFFObjectFile::getCommonSymbolSizeImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/object/resourcesectionref/#acda81c3c28377b5e191fbfdd745d6644">llvm::object::ResourceSectionRef::getContents</a>, <a href="/web-llvm/docs/api/classes/llvm/object/sectionref/#a6342a1426bb80b6b762d4ec5e58f1ce4">llvm::object::SectionRef::getContents</a>, <a href="/web-llvm/docs/api/files/lib/lib/dwp/dwp-cpp/#a8bd04295f552ef30463ffb24174d649b">getCUIdentifiers</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/nativeexesymbol-cpp/#a60028c7e119776d3c849f7782e59661d">getDbiStreamPtr</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/nativesession-cpp/#a5ea8b61c9f761f9468bdc64078b62785">getDbiStreamPtr</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#a53949973d752a1d918687b758424714a">llvm::dwarf_linker::parallel::CompileUnit::getDirAndFilenameFromLineTable</a>, <a href="/web-llvm/docs/api/classes/anonymous-dwarfcontext-cpp-/threadunsafedwarfcontextstate/#a54233894e754c548da87c0d21d69003d">anonymous{DWARFContext.cpp}::ThreadUnsafeDWARFContextState::getDWOContext</a>, <a href="/web-llvm/docs/api/classes/llvm/ifs/anonymous-elfobjhandler-cpp-/dynsym/#a78651c9b5b2e9d67f3cb489c62ea28ab">llvm::ifs::anonymous{ELFObjHandler.cpp}::DynSym&lt; ELFT &gt;::getDynStr</a>, <a href="/web-llvm/docs/api/classes/llvm/object/elffile/#a8e0db63318e9923b354d95e0391c05db">llvm::object::ELFFile&lt; ELFT &gt;::getDynSymtabSize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#a329e7bf260cc55361a96c1ad5a332bb9">llvm::object::getELFAddend</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a5943e7713622fd9365b27abfefd1703f">llvm::orc::getELFObjectFileSymbolInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp/#a3d0c0fef256a92c13760a52971b805b5">getEnableSplitLTOUnitAndUnifiedFlag</a>, <a href="/web-llvm/docs/api/classes/llvm/object/elffile/#a98e19eaf03c9744a18996776d77d0ee1">llvm::object::ELFFile&lt; ELFT &gt;::getEntry</a>, <a href="/web-llvm/docs/api/classes/llvm/object/xcoffobjectfile/#a2171b8599a07a37e7a4f18b12d7ff312">llvm::object::XCOFFObjectFile::getExceptionEntries</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#a0123e359eccc453af98b12d2b5ce2516">llvm::object::getExtendedSymbolTableIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/memorybuffer/#a76b193577aa67b1fac72cdbb5343241a">llvm::MemoryBuffer::getFileAsStream</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/memorybuffer-cpp/#a4b1e92bf20cb54acca62efdbfdebad54">getFileAux</a>, <a href="/web-llvm/docs/api/classes/llvm/object/archive/child/#a22ece0b78ccffb215a68d44b94b46e2f">llvm::object::Archive::Child::getFullName</a>, <a href="/web-llvm/docs/api/classes/llvm/gsym/gsymreader/#af15b2b0c7e2abba2d3e36989685d800f">llvm::gsym::GsymReader::getFunctionInfoDataForAddress</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a46b8e71e338ddab38e9a33ed9502a3a2">llvm::orc::getGenericObjectFileSymbolInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/symbolize/anonymous-symbolize-cpp-/#aca915d08912b7239d76d1044c7a8a073">llvm::symbolize::anonymous{Symbolize.cpp}::getGNUDebuglinkContents</a>, <a href="/web-llvm/docs/api/classes/llvm/binaryoperation/#a24d9325add2b388eebc0420cf6a0fdb4">llvm::BinaryOperation::getImplicitFormat</a>, <a href="/web-llvm/docs/api/classes/llvm/object/xcoffobjectfile/#a81ef70b0779ce0c0e0f41c320c1f355a">llvm::object::XCOFFObjectFile::getImportFileTable</a>, <a href="/web-llvm/docs/api/classes/llvm/object/abstractarchivememberheader/#aa0994633a7dc598ab379d4dcfa99bb17">llvm::object::AbstractArchiveMemberHeader::getLastModified</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6b551037bf3f327d3c280b59de0cace1">llvm::getLazyBitcodeModule</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#afab90ce1024ba9b690f64237fa1a2b9b">llvm::getLazyIRModule</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcontext/#a6b034e23dde3985292359895c41c74f6">llvm::DWARFContext::getLineTableForUnit</a>, <a href="/web-llvm/docs/api/classes/llvm/object/elffile/#a0bbb4e885d31a6ae8eb4486532fb3108">llvm::object::ELFFile&lt; ELFT &gt;::getLinkAsStrtab</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp/#ada8e7ae873a0bd17132af43d3a128f8e">getLoadCommandInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a2143f8386a6b8bcb33011fdd240c38f1">llvm::orc::getMachOObjectFileSymbolInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/object/minidumpfile/#ad79b94d312ad221c9d2b49357633a223">llvm::object::MinidumpFile::getMemory64List</a>, <a href="/web-llvm/docs/api/classes/llvm/object/archive/child/#a7fa0bfbc8489a0b3472e2dd834e03c80">llvm::object::Archive::Child::getMemoryBufferRef</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a4ea0a9908bf44e213edb07fb04ab0240">llvm::pdb::getModuleDebugStream</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#af1896eb50b6f562b62e975912f7e146c">llvm::pdb::getModuleDebugStream</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a59316b66df2176ff19458e2d624b98ad">llvm::getModuleSummaryIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/object/archive/child/#a3acd0fa308c00ead51dc16b4d46604bc">llvm::object::Archive::Child::getName</a>, <a href="/web-llvm/docs/api/classes/llvm/object/archivememberheader/#a940c0b94e9bb9dfdb69961d456b47b60">llvm::object::ArchiveMemberHeader::getName</a>, <a href="/web-llvm/docs/api/classes/llvm/object/archive/child/#a137ad5829c3f2470a0da63800c59385e">llvm::object::Archive::Child::getNext</a>, <a href="/web-llvm/docs/api/classes/llvm/object/archivememberheader/#ae1d86083ac823979ed30663f9d87118d">llvm::object::ArchiveMemberHeader::getNextChildLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/object/bigarchivememberheader/#a5ac0ddcf418dd66efde6cb208755629f">llvm::object::BigArchiveMemberHeader::getNextChildLoc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a603eb2d37a31ea2c14318bedeecb8e3c">llvm::getOffset</a>, <a href="/web-llvm/docs/api/structs/llvm/newarchivemember/#aadff13fd008345361aa920977e0c9e32">llvm::NewArchiveMember::getOldMember</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/memorybuffer-cpp/#a7a23441815c1bba5006a34529e58aa86">getOpenFileImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/nativesession-cpp/#a6d532e2f19636873f69d5c0d7524dc38">getPdbPathFromExe</a>, <a href="/web-llvm/docs/api/classes/llvm/object/elfobjectfilebase/#ab5019ff9e3502f422f3d8668201f5756">llvm::object::ELFObjectFileBase::getPltEntries</a>, <a href="/web-llvm/docs/api/structs/llvm/ltomodule/#a969833caa131b8a26c7b12bf917294a7">llvm::LTOModule::getProducerString</a>, <a href="/web-llvm/docs/api/classes/llvm/object/bigarchivememberheader/#a1dee83379cd715e24ccdec554331a3cf">llvm::object::BigArchiveMemberHeader::getRawName</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/memorybuffer-cpp/#a61ce38671d4f07799441a502041db0ff">getReadWriteFile</a>, <a href="/web-llvm/docs/api/classes/llvm/object/elfobjectfile/#a9cb66c2081706fafa8bb7804d9c8b0b3">llvm::object::ELFObjectFile&lt; ELFT &gt;::getRelocatedSection</a>, <a href="/web-llvm/docs/api/namespaces/llvm/remarks/#aff5f4a955d855eddcf05807595306406">llvm::remarks::getRemarksSectionContents</a>, <a href="/web-llvm/docs/api/classes/llvm/numericsubstitution/#a0b2eec42e90409cf02bc131c0925d586">llvm::NumericSubstitution::getResult</a>, <a href="/web-llvm/docs/api/classes/llvm/stringsubstitution/#a5586c71b9d5f3470c0f260453969e5ca">llvm::StringSubstitution::getResult</a>, <a href="/web-llvm/docs/api/classes/llvm/object/elffile/#ac224640f48ef4ce451d49bbb1b68e9ca">llvm::object::ELFFile&lt; ELFT &gt;::getSectionAndRelocations</a>, <a href="/web-llvm/docs/api/classes/llvm/object/elffile/#afe8f1b1f8599971e74d71887513cfd60">llvm::object::ELFFile&lt; ELFT &gt;::getSectionIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/sectiontableref/#a1ede3cfcdfaccefa28d52e3e0bb13bda">llvm::objcopy::elf::SectionTableRef::getSectionOfType</a>, <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp/#aaa1a1464db1a7a577a3c9fb3e76e6f75">getSingleModule</a>, <a href="/web-llvm/docs/api/classes/llvm/object/bigarchivememberheader/#a19fbab288c38cba1ba49b9093ce87995">llvm::object::BigArchiveMemberHeader::getSize</a>, <a href="/web-llvm/docs/api/classes/llvm/object/elffile/#adfb3d16a4f2cb55b615809b97c5e6b13">llvm::object::ELFFile&lt; ELFT &gt;::getStringTableForSymtab</a>, <a href="/web-llvm/docs/api/classes/llvm/object/elfobjectfile/#a4f47a108418b742c0419cc238a0cdebb">llvm::object::ELFObjectFile&lt; ELFT &gt;::getSymbolAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/object/wasmobjectfile/#af2a2757f91471e6b80ccffa7840cb154">llvm::object::WasmObjectFile::getSymbolAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/object/elfobjectfile/#a784f287bf4c93da1cc4c455e4c41fd94">llvm::object::ELFObjectFile&lt; ELFT &gt;::getSymbolAlignment</a>, <a href="/web-llvm/docs/api/classes/llvm/object/xcoffobjectfile/#afba35271cc6fce891ce2bda4576c87d5">llvm::object::XCOFFObjectFile::getSymbolAlignment</a>, <a href="/web-llvm/docs/api/classes/llvm/object/elfobjectfile/#ac1c87c93f81427748d963d87ba65b21a">llvm::object::ELFObjectFile&lt; ELFT &gt;::getSymbolBinding</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/symboltablesection/#a1df7bc1b35a7ebee10e792e04e5dc86b">llvm::objcopy::elf::SymbolTableSection::getSymbolByIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/object/elfobjectfile/#a19c92b8d9a2449d3b8c4b3de8b5db326">llvm::object::ELFObjectFile&lt; ELFT &gt;::getSymbolELFType</a>, <a href="/web-llvm/docs/api/classes/llvm/object/elfobjectfile/#a6d7040098bbc2f04e4191b9991a769e3">llvm::object::ELFObjectFile&lt; ELFT &gt;::getSymbolFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/object/xcoffobjectfile/#a26063993809b386ab934532d1af8b56c">llvm::object::XCOFFObjectFile::getSymbolFlags</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp/#aaca2a6196a0b153d686419f0fd252e91">getSymbolInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/object/elfobjectfile/#ab82d11942ddc1cd6df695e3ec80ad39b">llvm::object::ELFObjectFile&lt; ELFT &gt;::getSymbolName</a>, <a href="/web-llvm/docs/api/classes/llvm/object/elfobjectfile/#a8794e158de6bc5ebb588198cdf868418">llvm::object::ELFObjectFile&lt; ELFT &gt;::getSymbolOther</a>, <a href="/web-llvm/docs/api/classes/llvm/object/coffobjectfile/#a2456423e9e3bb5ffdc0a75fa36dd16cf">llvm::object::COFFObjectFile::getSymbolSection</a>, <a href="/web-llvm/docs/api/classes/llvm/object/elfobjectfile/#a42018f438c55d2c9c83355e3a8c3cb94">llvm::object::ELFObjectFile&lt; ELFT &gt;::getSymbolSection</a>, <a href="/web-llvm/docs/api/classes/llvm/object/elfobjectfile/#a3859965ea1c713b4c1187bdafba6fa60">llvm::object::ELFObjectFile&lt; ELFT &gt;::getSymbolSection</a>, <a href="/web-llvm/docs/api/classes/llvm/object/xcoffobjectfile/#af0d12d4046ba19c552b1e86fbe25abe9">llvm::object::XCOFFObjectFile::getSymbolSection</a>, <a href="/web-llvm/docs/api/classes/llvm/object/xcoffobjectfile/#a90303baf9d185097198f817b998136a6">llvm::object::XCOFFObjectFile::getSymbolSectionName</a>, <a href="/web-llvm/docs/api/classes/llvm/object/xcoffobjectfile/#ad6cf6760f283737b422b80253b8828d2">llvm::object::XCOFFObjectFile::getSymbolSize</a>, <a href="/web-llvm/docs/api/classes/llvm/object/elfobjectfile/#ad38d33d56845066a2063cc3896329d03">llvm::object::ELFObjectFile&lt; ELFT &gt;::getSymbolType</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#abfea148e3e5693c88962ce5add39bf56">llvm::object::MachOObjectFile::getSymbolType</a>, <a href="/web-llvm/docs/api/classes/llvm/object/xcoffobjectfile/#a606ab46a34eecd59e09198799a982dc4">llvm::object::XCOFFObjectFile::getSymbolType</a>, <a href="/web-llvm/docs/api/classes/llvm/object/elfobjectfile/#a4b197578436993f9a0a9753d214822b4">llvm::object::ELFObjectFile&lt; ELFT &gt;::getSymbolValueImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/objectfiletransformer-cpp/#a675f0690b04eaa2c63f91d8e05c75106">getUUID</a>, <a href="/web-llvm/docs/api/classes/llvm/bitcodereadervaluelist/#a46a07cf7b40536441b20f82ebf099e2f">llvm::BitcodeReaderValueList::getValueFwdRef</a>, <a href="/web-llvm/docs/api/classes/llvm/object/elffile/#a20ac73b763595fb7dd3d76f6a221408c">llvm::object::ELFFile&lt; ELFT &gt;::getVersionDefinitions</a>, <a href="/web-llvm/docs/api/classes/llvm/object/elffile/#a6d7f36df9f1e78161aa1117443ec74e1">llvm::object::ELFFile&lt; ELFT &gt;::getVersionDependencies</a>, <a href="/web-llvm/docs/api/classes/llvm/object/xcoffsymbolref/#a046c53b9366f602644b022ee6e86c57e">llvm::object::XCOFFSymbolRef::getXCOFFCsectAuxRef</a>, <a href="/web-llvm/docs/api/classes/llvm/jitlink/cofflinkgraphbuilder/#a366499688213f0b083c4653df7871b33">llvm::jitlink::COFFLinkGraphBuilder::graphifySections</a>, <a href="/web-llvm/docs/api/classes/llvm/jitlink/cofflinkgraphbuilder/#a3f0c20754117c8457f8f5c469b8bd5e5">llvm::jitlink::COFFLinkGraphBuilder::graphifySymbols</a>, <a href="/web-llvm/docs/api/classes/llvm/anonymous-debuginfod-cpp-/streamedhttpresponsehandler/#ae3ec74d0da38e1e58d8c160075aaa17b">llvm::anonymous{Debuginfod.cpp}::StreamedHTTPResponseHandler::handleBodyChunk</a>, <a href="/web-llvm/docs/api/files/lib/lib/dwp/dwp-cpp/#a358c1febb02bfec774608e4761b27495">handleCompressedSection</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9918786a0f26fa3b2f43f2a0fe626f7a">llvm::handleSection</a>, <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp/#a62f979fde2fca6e52e8789ff96ad830e">hasObjCCategoryInModule</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/pdbfile/#a11b61afbe99759ecea582cdc4ff86573">llvm::pdb::PDBFile::hasPDBInjectedSourceStream</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/pdbfile/#ae075398bbc5665686e631d8bc1e3a190">llvm::pdb::PDBFile::hasPDBStringTable</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-dlltooldriver-cpp-/#ae6071096c441061cfc9f7b4cf8f4ec9e">anonymous{DlltoolDriver.cpp}::identifyImportName</a>, <a href="/web-llvm/docs/api/classes/llvm/functionimporter/#a293aab6abe312ff6dbe227a3bcde838c">llvm::FunctionImporter::importFunctions</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/relocsectionwithsymtabbase/#a957eb6753673d0aa863ddb450a9fa424">llvm::objcopy::elf::RelocSectionWithSymtabBase&lt; SymTabType &gt;::initialize</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/section/#a3995c394cc393dfab7483f6a52f760ef">llvm::objcopy::elf::Section::initialize</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/sectionindexsection/#ae4d186eb2f1484ef96545b5ba677d6b9">llvm::objcopy::elf::SectionIndexSection::initialize</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/symboltablesection/#ab5050a1b044f845cc9ce4a3d8b4597f5">llvm::objcopy::elf::SymbolTableSection::initialize</a>, <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobject-cpp/#ad1b78430e677c5ac22430b0af1797615">initRelocations</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/archivewriter-cpp/#a903f7954a46ba31474ad9e0c7ccfbed3">isArchiveSymbol</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a286038f4ba044b39a6bb7f86c4c1055c">llvm::isBitcodeContainingObjCCategory</a>, <a href="/web-llvm/docs/api/structs/llvm/ltomodule/#a18c6d81a89ce7251370098d5fca14eed">llvm::LTOModule::isBitcodeFile</a>, <a href="/web-llvm/docs/api/structs/llvm/ltomodule/#af8c1c55aabd3c2fe773936a5aeec05c8">llvm::LTOModule::isBitcodeFile</a>, <a href="/web-llvm/docs/api/structs/llvm/ltomodule/#aa9588be24002d2f7603334d8dd1846e7">llvm::LTOModule::isBitcodeForTarget</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/inputfile-cpp/#aae56fcb4a814efb5721c69338ad00a51">isCodeViewDebugSubsection</a>, <a href="/web-llvm/docs/api/classes/llvm/object/coffobjectfile/#a529853b2fbf4b976d4a99b8fa8a2f144">llvm::object::COFFObjectFile::isDebugSection</a>, <a href="/web-llvm/docs/api/classes/llvm/object/elfobjectfile/#ae62484c71e9b9ab034fe9a10717fa718">llvm::object::ELFObjectFile&lt; ELFT &gt;::isDebugSection</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a5d343559880ac878c6a999cd0e85517e">llvm::object::MachOObjectFile::isDebugSection</a>, <a href="/web-llvm/docs/api/classes/llvm/object/xcoffsymbolref/#a0b01026129dcc250501775442ac4b2e5">llvm::object::XCOFFSymbolRef::isFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/object/objectfile/#aed7ed4cb387ecbb7339ba44ff631ebf0">llvm::object::ObjectFile::isSectionBitcode</a>, <a href="/web-llvm/docs/api/classes/llvm/object/archivememberheader/#aa954ca2029479568fc22ecd2c427c4a2">llvm::object::ArchiveMemberHeader::isThin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abff0d6ad3853141a03b46790c091c8d1">llvm::isThumbFunc</a>, <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp/#a5fca99afcf20fdf62a04843e8825d03f">jumpToValueSymbolTable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1df6c429f484cbf4fd21a5d306f53671">llvm::libDriverMain</a>, <a href="/web-llvm/docs/api/structs/llvm/remarks/remarklinker/#a2f0b07de873627d24a364adbc61b0da3">llvm::remarks::RemarkLinker::link</a>, <a href="/web-llvm/docs/api/structs/llvm/remarks/remarklinker/#ac548aeb7853ce7d7cd2a3b33fb761d1b">llvm::remarks::RemarkLinker::link</a>, <a href="/web-llvm/docs/api/classes/llvm/jitlink/jitlinkerbase/#aa0e31635ad3d914185e2948291635e17">llvm::jitlink::JITLinkerBase::linkPhase2</a>, <a href="/web-llvm/docs/api/classes/llvm/jitlink/jitlinkerbase/#a37a9b50106a3f530a5dd73df78310f6b">llvm::jitlink::JITLinkerBase::linkPhase3</a>, <a href="/web-llvm/docs/api/classes/llvm/jitlink/jitlinkerbase/#a0693d115e111fac7e6d5258f51b10c4b">llvm::jitlink::JITLinkerBase::linkPhase4</a>, <a href="/web-llvm/docs/api/groups/llvmcobject/#gabe1e0252c6f4bc1b0b1b8b06f9df3546">LLVMCreateBinary</a>, <a href="/web-llvm/docs/api/groups/llvmcobject/#ga0fd9f7bc65117c049c14c047fb7907dc">LLVMCreateObjectFile</a>, <a href="/web-llvm/docs/api/groups/llvmcbitreader/#gad617205cd3fbbb1ad78e6f79f9ce0e4b">LLVMGetBitcodeModuleInContext</a>, <a href="/web-llvm/docs/api/groups/llvmcobject/#gab0bd1b18bfb07fa6d075f69f6c6dd62f">LLVMMachOUniversalBinaryCopyObjectForArch</a>, <a href="/web-llvm/docs/api/groups/llvmcobject/#gab7faf1f46a7fb022e21e792e0250709d">LLVMMoveToContainingSection</a>, <a href="/web-llvm/docs/api/groups/llvmcbitreader/#ga668b459026b5a6c7f32325408265e616">LLVMParseBitcodeInContext</a>, <a href="/web-llvm/docs/api/groups/llvmcremarks/#gada1d7ab2d57b735d67fa095bc099cc7f">LLVMRemarkParserGetNext</a>, <a href="/web-llvm/docs/api/classes/llvm/object/resourcesectionref/#a778c6e8a9d2903a6c5b0501015acd0e2">llvm::object::ResourceSectionRef::load</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a1307fe9528cee604862ce0966931dc6b">llvm::pdb::loadDataForEXE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xray/#aa457a825eb8236aa6f36de72e86109ca">llvm::xray::loadInstrumentationMap</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a1a325b7b8ec75f271d91355d4216b6c4">llvm::orc::loadLinkableFile</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#ae6cbf068071c82d07501b056bf146c3f">llvm::orc::loadMachORelocatableObject</a>, <a href="/web-llvm/docs/api/files/lib/lib/lto/thinltocodegenerator-cpp/#aeec26ce8d8be46abb3008a9a8e6e9107">loadModuleFromInput</a>, <a href="/web-llvm/docs/api/files/lib/lib/xray/instrumentationmap-cpp/#a39d3991edccf18f18b801032e9ab89b5">loadObj</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldimpl/#afe85af578989c7f3e9627866e7fa4962">llvm::RuntimeDyldImpl::loadObjectImpl</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xray/#ab67d7aaee3e9b7f980823af5cde41fcb">llvm::xray::loadProfile</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xray/#a6d387644a0d53428ceb3dfad35a51922">llvm::xray::loadTraceFile</a>, <a href="/web-llvm/docs/api/classes/llvm/object/elffile/#aeb221ffeffa3ec7eaaa8eecf37b0146d">llvm::object::ELFFile&lt; ELFT &gt;::loadVersionMap</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af73b4fcac77298355025a0e5975edcf0">llvm::localCache</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/lljit/#a7cdf02cb3498619dc90826ff5bf7b64f">llvm::orc::LLJIT::lookupLinkerMangled</a>, <a href="/web-llvm/docs/api/files/lib/lib/profiledata/lib/profiledata/coverage/coveragemappingreader-cpp/#a7d0e6c07b7e07a14b8006f915ceb6e6d">lookupSections</a>, <a href="/web-llvm/docs/api/classes/anonymous-dxiloplowering-cpp-/oplowerer/#a4275af81cdeb1801deeae02ea2a0fb3b">anonymous{DXILOpLowering.cpp}::OpLowerer::lowerBufferStore</a>, <a href="/web-llvm/docs/api/classes/anonymous-dxiloplowering-cpp-/oplowerer/#a2fea5f04ff43df5b1fc0a4304b7362c2">anonymous{DXILOpLowering.cpp}::OpLowerer::lowerCtpopToCountBits</a>, <a href="/web-llvm/docs/api/classes/anonymous-dxiloplowering-cpp-/oplowerer/#a30b2570b289c65776a16666bd087c988">anonymous{DXILOpLowering.cpp}::OpLowerer::lowerRawBufferLoad</a>, <a href="/web-llvm/docs/api/classes/anonymous-dxiloplowering-cpp-/oplowerer/#a4a42541fb66ae32c0c9f8deede2cc21e">anonymous{DXILOpLowering.cpp}::OpLowerer::lowerToBindAndAnnotateHandle</a>, <a href="/web-llvm/docs/api/classes/anonymous-dxiloplowering-cpp-/oplowerer/#a230768916fc2abaf5fb0f563654d2cc8">anonymous{DXILOpLowering.cpp}::OpLowerer::lowerToCreateHandle</a>, <a href="/web-llvm/docs/api/classes/anonymous-dxiloplowering-cpp-/oplowerer/#a70502c89919d53c74320c78b78d5c282">anonymous{DXILOpLowering.cpp}::OpLowerer::lowerTypedBufferLoad</a>, <a href="/web-llvm/docs/api/classes/anonymous-dxiloplowering-cpp-/oplowerer/#ab10e6ab2669a5c752426570de655e7ce">anonymous{DXILOpLowering.cpp}::OpLowerer::lowerUpdateCounter</a>, <a href="/web-llvm/docs/api/structs/btfparser/parsecontext/#a657868ac1ec31f283f359d005dcdf905">llvm::BTFParser::ParseContext::makeExtractor</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvbinaryreader/#a50b4341d651ea41cb74546557170ebaa">llvm::logicalview::LVBinaryReader::mapVirtualAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvbinaryreader/#a8f648767e6fee704685f85355aa7fa64">llvm::logicalview::LVBinaryReader::mapVirtualAddress</a>, <a href="/web-llvm/docs/api/classes/anonymous-irmover-cpp-/irlinker/#a22cba4a0f099e7731ad3db4f309e139e">anonymous{IRMover.cpp}::IRLinker::materialize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/cgdata/#a05b4c070c172287759f5f2f437a3edcb">llvm::cgdata::mergeCodeGenData</a>, <a href="/web-llvm/docs/api/classes/llvm/codegendatareader/#ad41848e26234890d2d908a09f6709022">llvm::CodeGenDataReader::mergeFromObjectFile</a>, <a href="/web-llvm/docs/api/classes/llvm/msvcpexpected/#a01afd76b2f9a9da27b6a986c8106c6e1">llvm::MSVCPExpected&lt; T &gt;::MSVCPExpected</a>, <a href="/web-llvm/docs/api/structs/llvm/remarks/yamlremarkparser/#acb5c8bd7367e9f8df487f08bdd08bc27">llvm::remarks::YAMLRemarkParser::next</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/debugobjectmanagerplugin/#a778eb8f8c5516bfed164b60b1594d632">llvm::orc::DebugObjectManagerPlugin::notifyEmitted</a>, <a href="/web-llvm/docs/api/classes/anonymous-inteljiteventlistener-cpp-/inteljiteventlistener/#a89cbcd5cb777a56db440c87f1ebffdb4">anonymous{IntelJITEventListener.cpp}::IntelJITEventListener::notifyObjectLoaded</a>, <a href="/web-llvm/docs/api/classes/anonymous-perfjiteventlistener-cpp-/perfjiteventlistener/#a502ebf0f061782cbcfa72244fbd0ec97">anonymous{PerfJITEventListener.cpp}::PerfJITEventListener::notifyObjectLoaded</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/inputfile/#a7b4528e86b5fa28d9fd927aa31a8fcd2">llvm::pdb::InputFile::open</a>, <a href="/web-llvm/docs/api/classes/llvm/btfparser/#a4c7c5e28bb5767c6be05394c38ab0d21">llvm::BTFParser::parse</a>, <a href="/web-llvm/docs/api/structs/llvm/remarks/yamlremarkparser/#abda1ebf8585492b9082471af74921703">llvm::remarks::YAMLRemarkParser::parseArg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a170525c5f5e06bd2555d40a0499b8b6d">llvm::parseBitcodeFile</a>, <a href="/web-llvm/docs/api/files/lib/lib/lto/ltomodule-cpp/#afc4790b3e3d093c39ef63dbf4f840b8f">parseBitcodeFileImpl</a>, <a href="/web-llvm/docs/api/structs/llvm/remarks/bitstreamparserhelper/#aef087e7464b791f0ab26613736065520">llvm::remarks::BitstreamParserHelper::parseBlockInfoBlock</a>, <a href="/web-llvm/docs/api/structs/llvm/remarks/yamlremarkparser/#a66625e87299e9c2a860b373e0f4d5b80">llvm::remarks::YAMLRemarkParser::parseDebugLoc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8b04365fc31f28e28e484d2f3cba05f1">llvm::parseIR</a>, <a href="/web-llvm/docs/api/classes/metadataloader/metadataloaderimpl/#ab5d5351419b40a9f891e4506bc2cae29">llvm::MetadataLoader::MetadataLoaderImpl::parseMetadata</a>, <a href="/web-llvm/docs/api/classes/metadataloader/metadataloaderimpl/#a4a81e1117a068de8d409b76e45c3e494">llvm::MetadataLoader::MetadataLoaderImpl::parseMetadataAttachment</a>, <a href="/web-llvm/docs/api/classes/metadataloader/metadataloaderimpl/#a71350293eab7be254484af9024a93da4">llvm::MetadataLoader::MetadataLoaderImpl::parseMetadataKinds</a>, <a href="/web-llvm/docs/api/classes/anonymous-bitcodereader-cpp-/modulesummaryindexbitcodereader/#ae9f86888a27590c2d447d2f98b5f7cf8">anonymous{BitcodeReader.cpp}::ModuleSummaryIndexBitcodeReader::parseModule</a>, <a href="/web-llvm/docs/api/classes/llvm/pattern/#a7d176c2f7da2816d871ca9dbecd13b7e">llvm::Pattern::parseNumericSubstitutionBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/pattern/#ae173fad50624dec05877e86be7b7e429">llvm::Pattern::parsePattern</a>, <a href="/web-llvm/docs/api/files/lib/lib/remarks/bitstreamremarkparser-cpp/#a614e714a8963e8f854ecac210dde3125">parseRecord</a>, <a href="/web-llvm/docs/api/files/lib/lib/remarks/bitstreamremarkparser-cpp/#a384d242ae8d66e4ea84344784426e3a7">parseRecord</a>, <a href="/web-llvm/docs/api/structs/llvm/remarks/yamlremarkparser/#ac4d29f90f81ea8264f49bb0736faf1d0">llvm::remarks::YAMLRemarkParser::parseRemark</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdebugline-cpp/#a132fc2d4f9a680228706747b8608e269">parseV5DirFileTables</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ifs/#adfe6be0993129c864dc3047bd6dba156">llvm::ifs::populateSymbols</a>, <a href="/web-llvm/docs/api/classes/llvm/pattern/#a3a4e8a88439506522a2a0f3850802d3f">llvm::Pattern::printSubstitutions</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldcoffaarch64/#a9114640d8c0477c8c9c502e8acd7cbf7">llvm::RuntimeDyldCOFFAArch64::processRelocationRef</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldcoffi386/#a47afe575c279c175037d664bde7e53a3">llvm::RuntimeDyldCOFFI386::processRelocationRef</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldcoffthumb/#a200d4c53b00f55a8d0911279bf576c18">llvm::RuntimeDyldCOFFThumb::processRelocationRef</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldcoffx86-64/#afcf3722d9ca669767870af1a84877924">llvm::RuntimeDyldCOFFX86_64::processRelocationRef</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldelf/#ad9cec5473cec6044442bceccc2fcee96">llvm::RuntimeDyldELF::processRelocationRef</a>, <a href="/web-llvm/docs/api/classes/llvm/bitstreamcursor/#a18edc8cef7ae17b03b6d4f3ad2cda8b3">llvm::BitstreamCursor::ReadAbbrevRecord</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/elfobjectfile-cpp/#a6264f8eee9db96846bfe5119e1ceb4ab">readBBAddrMapImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp/#ad3dcdf576f07a261c70f7eac121b3eec">readBlobInRecord</a>, <a href="/web-llvm/docs/api/classes/anonymous-bitcodereader-cpp-/bitcodereaderbase/#ad04f7d6a08ad25b673e16a64825f640c">anonymous{BitcodeReader.cpp}::BitcodeReaderBase::readBlockInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/bitstreamcursor/#aca82144243a4bbb08d09c0c72d636bd1">llvm::BitstreamCursor::ReadBlockInfoBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/profiledata/lib/profiledata/coverage/coveragemappingreader-cpp/#a10b27eac23635b8f40370fe8a4d19967">readCoverageMappingData</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/elfobjectfile-cpp/#afbf1738ff099ad1ac3079a05ae07ea35">readDynsymVersionsImpl</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ifs/#a6c7020c6d68f0a88ce9bf2265cc061c4">llvm::ifs::readELFFile</a>, <a href="/web-llvm/docs/api/classes/llvm/msgpack/document/#aa1132fee67332a4c0a707984b97f9b52">llvm::msgpack::Document::readFromBlob</a>, <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp/#adfdf631a8d0d417904f24c6ff6d9ed03">readIdentificationBlock</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#a01155893a99bd03c0b13bb52d2f7083e">llvm::object::readIRSymtab</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae368e17bfcc41a6bc7891c4c84224c9c">llvm::readModuleSummaryIndex</a>, <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp/#afa9c01a1d03b3af4714df3976056d46b">readModuleTriple</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a25241903dcf363fdf53dc9e8f1037e7a">llvm::sys::fs::readNativeFileToEOF</a>, <a href="/web-llvm/docs/api/classes/llvm/bitstreamcursor/#a677592abe148dbc3de1ec00f3d9904c5">llvm::BitstreamCursor::readRecord</a>, <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp/#a42cc3ae15d37346d7ca743801b572770">readTriple</a>, <a href="/web-llvm/docs/api/classes/llvm/instrproflookuptrait/#ab946345c5c95f2318316edea199eaf39">llvm::InstrProfLookupTrait::readValueProfilingData</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/coff/object/#adb4129c7b7fb10fedccaaa668094cb31">llvm::objcopy::coff::Object::removeSymbols</a>, <a href="/web-llvm/docs/api/classes/anonymous-dxiloplowering-cpp-/oplowerer/#a6300c8f1d33302d372c953398dd5f18c">anonymous{DXILOpLowering.cpp}::OpLowerer::replaceFunctionWithNamedStructOp</a>, <a href="/web-llvm/docs/api/classes/anonymous-dxiloplowering-cpp-/oplowerer/#ac54843966305eb21541468d352728681">anonymous{DXILOpLowering.cpp}::OpLowerer::replaceFunctionWithOp</a>, <a href="/web-llvm/docs/api/classes/anonymous-dxiloplowering-cpp-/oplowerer/#a583a2a6c920de4695807c6ad35c5e35d">anonymous{DXILOpLowering.cpp}::OpLowerer::replaceResRetUses</a>, <a href="/web-llvm/docs/api/classes/anonymous-lto-cpp-/firstroundthinbackend/#a2c2b73979dafe07afd42a1d790f7ed8c">anonymous{LTO.cpp}::FirstRoundThinBackend::runThinLTOBackendThread</a>, <a href="/web-llvm/docs/api/classes/anonymous-lto-cpp-/inprocessthinbackend/#af0f9c1c44f600c3385ef076febf8c440">anonymous{LTO.cpp}::InProcessThinBackend::runThinLTOBackendThread</a>, <a href="/web-llvm/docs/api/classes/anonymous-lto-cpp-/secondroundthinbackend/#ad3c878292daedae87b12a69a4a05c046">anonymous{LTO.cpp}::SecondRoundThinBackend::runThinLTOBackendThread</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/pdbfile/#ad8d09605c92ca75b5d451deb26ccd2be">llvm::pdb::PDBFile::safelyCreateNamedStream</a>, <a href="/web-llvm/docs/api/namespaces/llvm/cgdata/#aa073bf33e4e66824238bc510dcdf0f4e">llvm::cgdata::saveModuleForTwoRounds</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lvreaderhandler-cpp/#af7b4a495780ab66e37af8b9881e7ad93">searchForExe</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/nativesession/#a10c66fa7ae2a9b589c8a2738661897ca">llvm::pdb::NativeSession::searchForPdb</a>, <a href="/web-llvm/docs/api/structs/llvm/remarks/remarklinker/#a520480e348343b25dce916ceca76dcd5">llvm::remarks::RemarkLinker::serialize</a>, <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobjcopy-cpp/#af5bc7bb3463aa7528d85207065490482">setSectionFlagsAndType</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/sectiondescriptor/#a0756e89d8eafc4bc2503dd3976765f61">llvm::dwarf_linker::parallel::SectionDescriptor::setSizesForSectionCreatedByAsmPrinter</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad89283f080890888a7101497fc0b9eec">llvm::setupLLVMOptimizationRemarks</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a861311f8fc18e2eb0035cccb0b1acaac">llvm::setupLLVMOptimizationRemarks</a>, <a href="/web-llvm/docs/api/classes/llvm/bitstreamcursor/#a73257c6f5ab8032f22e06c1da0bc109f">llvm::BitstreamCursor::SkipBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/bitstreamcursor/#a8b13d5acaf9ffcc5a0f9969888a7db33">llvm::BitstreamCursor::skipRecord</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6d9c43797976f73bdbe0c75995f84865">llvm::SPIRVTranslate</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad7c58f347a240684b93eb7ee8bfd6824">llvm::streamFile</a>, <a href="/web-llvm/docs/api/namespaces/llvm/lto/#ae6ff75e89240b2f2c01d3be088ca6014">llvm::lto::thinBackend</a>, <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#aa2807954a9bf3d29ba94545ebaa23584">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::tryEmitDwarfFileDirective</a>, <a href="/web-llvm/docs/api/classes/anonymous-thinltocodegenerator-cpp-/modulecacheentry/#a024b9505d8018b5086d36b13c3af8232">anonymous{ThinLTOCodeGenerator.cpp}::ModuleCacheEntry::tryLoadingBuffer</a>, <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machoobjcopy-cpp/#afcfed892d87764504587749693efe357">updateSection</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/irsymtab-cpp/#acfa5e41a619b2f37966fdc043ca96c09">upgrade</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7363e46d4dd6c78affffabaea0de482b">llvm::write</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1437ccb0a1879b013ec4e26ed265bc4a">llvm::writeArchive</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae80a7e9590f1bec7c0ca3b271e88a735">llvm::writeArchiveToStream</a>, <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/dwarfemitter-cpp/#abe6559672807a3455fb24c680ac42dc6">writeDIE</a>, <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/dwarfemitter-cpp/#a27a0ea7c31356a5938a3fe32e8eb3103">writeDWARFLists</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ifs/#a101c2836638ffc1c34e2e502ad68d0da">llvm::ifs::writeELFBinaryToFile</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#af9d2c5b5d2afb86f9cdaef1946b79f6c">llvm::object::writeImportLibrary</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a80a1017cd2662da510365c7ee41a782a">llvm::writeToOutput</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/machouniversalwriter-cpp/#a9f26efe564d8f7f1afb5f3033156d58d">writeUniversalArchsToStream</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#a747323aef7153b9358ab839fdcfc4468">llvm::object::writeUniversalBinary</a> and <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#a995e3c2084bb6204a7496128e9562fc0">llvm::yaml::yaml2ObjectFile</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### assertIsChecked() {#a73d2ade4315308565b2eddabf24be3a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::Expected&lt; T &gt;::assertIsChecked ()</td>
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



<p>Definition at line 722 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/error-h">Error.h</a>.</p>

</div>
</div>

### getErrorStorage() {#a657b2f9c2974428839e5fe9d9070ef6d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">error_type * llvm::Expected&lt; T &gt;::getErrorStorage ()</td>
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



<p>Definition at line 691 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/error-h">Error.h</a>.</p>

</div>
</div>

### getErrorStorage() {#a8e978dc79354e3875c14d97998ddeec3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const error_type * llvm::Expected&lt; T &gt;::getErrorStorage ()</td>
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



<p>Definition at line 696 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/error-h">Error.h</a>.</p>

</div>
</div>

### getStorage() {#a32254986f7c30a662f89788d56599907}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">storage_type * llvm::Expected&lt; T &gt;::getStorage ()</td>
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



<p>Definition at line 681 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/error-h">Error.h</a>.</p>

</div>
</div>

### getStorage() {#aa823369a97c477133d2ace93beb63fe9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const storage_type * llvm::Expected&lt; T &gt;::getStorage ()</td>
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



<p>Definition at line 686 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/error-h">Error.h</a>.</p>

</div>
</div>

### moveAssign() {#a1dc1569ee8eab52e145e7bb4370e175b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class OtherT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::Expected&lt; T &gt;::moveAssign (<a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; OtherT &gt; &amp;&amp; Other)</td>
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



<p>Definition at line 663 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/error-h">Error.h</a>.</p>

</div>
</div>

### moveConstruct() {#ae07f50012045d91158053277a40a6459}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class OtherT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::Expected&lt; T &gt;::moveConstruct (<a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; OtherT &gt; &amp;&amp; Other)</td>
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



<p>Definition at line 650 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/error-h">Error.h</a>.</p>

</div>
</div>

### setUnchecked() {#aff4bdb1a95635f9f55912a08dd41303c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::Expected&lt; T &gt;::setUnchecked ()</td>
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



<p>Definition at line 702 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/error-h">Error.h</a>.</p>

</div>
</div>

### toPointer() {#ab58f17e0468d700f27c11fe9fcfca24e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">pointer llvm::Expected&lt; T &gt;::toPointer (pointer Val)</td>
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



<p>Definition at line 673 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/error-h">Error.h</a>.</p>

</div>
</div>

### toPointer() {#a118fc76ca1a4ec9f9c07479fcffa695a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_pointer llvm::Expected&lt; T &gt;::toPointer (const_pointer Val)</td>
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



<p>Definition at line 675 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/error-h">Error.h</a>.</p>

</div>
</div>

### toPointer() {#aa9ee5143ca67da46a108d7a7c086b435}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">pointer llvm::Expected&lt; T &gt;::toPointer (<a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">wrap</a> * Val)</td>
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



<p>Definition at line 677 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/error-h">Error.h</a>.</p>

</div>
</div>

### toPointer() {#a9b2c629f7f4f1dc9ed36415e2ec64c8e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_pointer llvm::Expected&lt; T &gt;::toPointer (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">wrap</a> * Val)</td>
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



<p>Definition at line 679 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/error-h">Error.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### ErrorStorage {#ad408d863dd19f7d6d4eb1cac2d431797}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AlignedCharArrayUnion&lt;error_type&gt; llvm::Expected&lt; T &gt;::ErrorStorage</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 731 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/error-h">Error.h</a>.</p>

</div>
</div>

### TStorage {#a8a3ea48fb65171db3c9261bd6b4fab0f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AlignedCharArrayUnion&lt;storage_type&gt; llvm::Expected&lt; T &gt;::TStorage</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 730 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/error-h">Error.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

###  {#af531774e2bb69dc5963673b15a2cd1bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">union llvm::Expected llvm::Expected&lt; T &gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 732 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/error-h">Error.h</a>.</p>

</div>
</div>

### HasError {#a533184e01e9f06afb38af85596ccb388}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Expected&lt; T &gt;::HasError</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 733 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/error-h">Error.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Functions

### compareThisIfSameType() {#a1f5100bf69cb7eef99923736da3a8c48}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T1&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Expected&lt; T &gt;::compareThisIfSameType (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#ac16509a75e3d3fc46b9df1726be486ec">T1</a> &amp; a, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#ac16509a75e3d3fc46b9df1726be486ec">T1</a> &amp; b)</td>
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



<p>Definition at line 641 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/error-h">Error.h</a>.</p>

</div>
</div>

### compareThisIfSameType() {#a5c83150adf5fe34e625d766e93da26f6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T1, class T2&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Expected&lt; T &gt;::compareThisIfSameType (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#ac16509a75e3d3fc46b9df1726be486ec">T1</a> &amp;, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> T2 &amp;)</td>
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



<p>Definition at line 646 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/error-h">Error.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Attributes

### isRef {#aa48f5f75b32e872c95272cd904181c22}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Expected&lt; T &gt;::isRef = std::is_reference_v&lt;T&gt;</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 485 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/error-h">Error.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/error-h">Error.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>

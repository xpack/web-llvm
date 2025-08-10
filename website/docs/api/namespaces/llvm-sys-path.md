---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/llvm/sys/path
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# `path` Namespace



## Definition

<div class="doxyDefinition">
namespace llvm::sys::path { ... }
</div>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sys/path/const-iterator">const_iterator</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Path iterator. <a href="/web-llvm/docs/api/classes/llvm/sys/path/const-iterator/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sys/path/reverse-iterator">reverse_iterator</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Reverse path iterator. <a href="/web-llvm/docs/api/classes/llvm/sys/path/reverse-iterator/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">Style { <a href="#a58cfd8a47c0ef96db27b451c2d6ec49f">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a8239d7a446775682284318d3c986ad">is_style_posix</a> (Style S)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if <span class="doxyComputerOutput">S</span> uses POSIX path rules. <a href="#a4a8239d7a446775682284318d3c986ad">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac533465ca310da3741ef2fb8794c0599">is_style_windows</a> (Style S)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if <span class="doxyComputerOutput">S</span> uses Windows path rules. <a href="#ac533465ca310da3741ef2fb8794c0599">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sys/path/reverse-iterator">reverse_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a728fc9f9b2d1a3a32b6fd2e785eb7b67">rbegin</a> (StringRef Path, Style style)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sys/path/reverse-iterator">reverse_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeec6efa9f64fb65e63600ebe128c2ebb">rend</a> (StringRef Path)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeaa763a458fd0b6a1f1b395784259de8">starts_with</a> (StringRef Path, StringRef Prefix, Style style=Style::native)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e2885e8a85c17ac8a95094c7b6bba2f">remove_leading_dotslash</a> (StringRef Path, Style style)</td>
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

## Lexical Component Iterator Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sys/path/const-iterator">const_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2798f80ce7d64ebc7049d1231e675137">begin</a> (StringRef path LLVM_LIFETIME_BOUND, Style style=Style::native)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get begin iterator over <em>path</em>. <a href="#a2798f80ce7d64ebc7049d1231e675137">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sys/path/const-iterator">const_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae6199e07e1f06cdaf0ad59b959045035">end</a> (StringRef path LLVM_LIFETIME_BOUND)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get end iterator over <em>path</em>. <a href="#ae6199e07e1f06cdaf0ad59b959045035">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sys/path/reverse-iterator">reverse_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae116bcdf5fac57d6da943935fb6c547a">rbegin</a> (StringRef path LLVM_LIFETIME_BOUND, Style style=Style::native)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get reverse begin iterator over <em>path</em>. <a href="#ae116bcdf5fac57d6da943935fb6c547a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sys/path/reverse-iterator">reverse_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2bc70cc8c5a83b940ed7c948b28dc512">rend</a> (StringRef path LLVM_LIFETIME_BOUND)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get reverse end iterator over <em>path</em>. <a href="#a2bc70cc8c5a83b940ed7c948b28dc512">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Lexical Modifiers Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a03907c7df68a93c377bf90c5bdd78ca3">remove_filename</a> (SmallVectorImpl&lt; char &gt; &amp;path, Style style=Style::native)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remove the last component from <em>path</em> unless it is the root dir. <a href="#a03907c7df68a93c377bf90c5bdd78ca3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1feb0e6007474c599ccfed65dad667c0">replace_extension</a> (SmallVectorImpl&lt; char &gt; &amp;path, const Twine &amp;extension, Style style=Style::native)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Replace the file extension of <em>path</em> with <em>extension</em>. <a href="#a1feb0e6007474c599ccfed65dad667c0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acb31f2db6f0fe5eaa5b28464141223aa">replace_path_prefix</a> (SmallVectorImpl&lt; char &gt; &amp;Path, StringRef OldPrefix, StringRef NewPrefix, Style style=Style::native)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Replace matching path prefix with another path. <a href="#acb31f2db6f0fe5eaa5b28464141223aa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6aa32b6763df05d8187ad5551533b567">remove_leading_dotslash</a> (StringRef path LLVM_LIFETIME_BOUND, Style style=Style::native)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remove redundant leading "./" pieces and consecutive separators. <a href="#a6aa32b6763df05d8187ad5551533b567">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a35c103b5fb70a66a1cb5da3b56f588a1">remove_dots</a> (SmallVectorImpl&lt; char &gt; &amp;path, bool remove_dot_dot=false, Style style=Style::native)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>In-place remove any '. <a href="#a35c103b5fb70a66a1cb5da3b56f588a1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acb80894344c78dacf8d5ff8c23be697d">append</a> (SmallVectorImpl&lt; char &gt; &amp;path, const Twine &amp;a, const Twine &amp;b="", const Twine &amp;c="", const Twine &amp;d="")</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Append to path. <a href="#acb80894344c78dacf8d5ff8c23be697d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b070d2edba351e90bf5a08b656895a5">append</a> (SmallVectorImpl&lt; char &gt; &amp;path, Style style, const Twine &amp;a, const Twine &amp;b="", const Twine &amp;c="", const Twine &amp;d="")</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4214dc81eb25ef3732b21822ee0e0563">append</a> (SmallVectorImpl&lt; char &gt; &amp;path, const_iterator begin, const_iterator end, Style style=Style::native)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Append to path. <a href="#a4214dc81eb25ef3732b21822ee0e0563">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Transforms (or some other better name) Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab071132a634a15df871b6901c1375c90">native</a> (const Twine &amp;path, SmallVectorImpl&lt; char &gt; &amp;result, Style style=Style::native)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Convert path to the native form. <a href="#ab071132a634a15df871b6901c1375c90">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2bfecff239f87c7bd19f128186b428a2">native</a> (SmallVectorImpl&lt; char &gt; &amp;path, Style style=Style::native)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Convert path to the native form in place. <a href="#a2bfecff239f87c7bd19f128186b428a2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a58dcbf859a69b30932a6ed45806f8a5b">make_preferred</a> (SmallVectorImpl&lt; char &gt; &amp;path, Style style=Style::native)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>For Windows path styles, convert path to use the preferred path separators. <a href="#a58dcbf859a69b30932a6ed45806f8a5b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa8749375717a95d086e49f655fa75046">convert_to_slash</a> (StringRef path, Style style=Style::native)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Replaces backslashes with slashes if Windows. <a href="#aa8749375717a95d086e49f655fa75046">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Lexical Observers Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac9c7e606723471849eec491d24e618c4">root_name</a> (StringRef path LLVM_LIFETIME_BOUND, Style style=Style::native)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get root name. <a href="#ac9c7e606723471849eec491d24e618c4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acb21fbbf512744e0346d8efc14ae4246">root_directory</a> (StringRef path LLVM_LIFETIME_BOUND, Style style=Style::native)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get root directory. <a href="#acb21fbbf512744e0346d8efc14ae4246">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a01ce989dcb8d95a2b5532357abc39096">root_path</a> (StringRef path LLVM_LIFETIME_BOUND, Style style=Style::native)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get root path. <a href="#a01ce989dcb8d95a2b5532357abc39096">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af426cbaa47678fc354ad421fb67e180e">relative_path</a> (StringRef path LLVM_LIFETIME_BOUND, Style style=Style::native)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get relative path. <a href="#af426cbaa47678fc354ad421fb67e180e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5326427c87607b2364a1fcdf13fa0eea">parent_path</a> (StringRef path LLVM_LIFETIME_BOUND, Style style=Style::native)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get parent path. <a href="#a5326427c87607b2364a1fcdf13fa0eea">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa56d25bb5127dd7a5831c25764f76cbe">filename</a> (StringRef path LLVM_LIFETIME_BOUND, Style style=Style::native)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get filename. <a href="#aa56d25bb5127dd7a5831c25764f76cbe">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1d074d016ff4ab25b0d504bf70a89059">stem</a> (StringRef path LLVM_LIFETIME_BOUND, Style style=Style::native)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get stem. <a href="#a1d074d016ff4ab25b0d504bf70a89059">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad1056825d31bf187d0be430c51aac281">extension</a> (StringRef path LLVM_LIFETIME_BOUND, Style style=Style::native)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get extension. <a href="#ad1056825d31bf187d0be430c51aac281">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aecbfb983627865ec98e96179df881e37">is_separator</a> (char value, Style style=Style::native)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> whether the given char is a path separator on the host OS. <a href="#aecbfb983627865ec98e96179df881e37">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a002a323feef10733642f9f92f6a94f1a">get_separator</a> (Style style=Style::native)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the preferred separator for this platform. <a href="#a002a323feef10733642f9f92f6a94f1a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa676374c59d0f44d25f9eab4bb824e5a">system_temp_directory</a> (bool erasedOnReboot, SmallVectorImpl&lt; char &gt; &amp;result)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the typical temporary directory for the system, e.g., "/var/tmp" or "C:/TEMP". <a href="#aa676374c59d0f44d25f9eab4bb824e5a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1286bcdea03c97a18eb1f41af524f3d3">home_directory</a> (SmallVectorImpl&lt; char &gt; &amp;result)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the user's home directory. <a href="#a1286bcdea03c97a18eb1f41af524f3d3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0e59c9239db6f8becab53eba0bc6d1f1">user_config_directory</a> (SmallVectorImpl&lt; char &gt; &amp;result)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the directory where packages should read user-specific configurations. <a href="#a0e59c9239db6f8becab53eba0bc6d1f1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c8daf95e53b1d17b5965a74533ca217">cache_directory</a> (SmallVectorImpl&lt; char &gt; &amp;result)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the directory where installed packages should put their machine-local cache, e.g. <a href="#a6c8daf95e53b1d17b5965a74533ca217">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1dae3a7c3f46eaa1201a537367693f11">has_root_name</a> (const Twine &amp;path, Style style=Style::native)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Has root name? <a href="#a1dae3a7c3f46eaa1201a537367693f11">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afbfbc19d8aa5dde440140c214c118516">has_root_directory</a> (const Twine &amp;path, Style style=Style::native)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Has root directory? <a href="#afbfbc19d8aa5dde440140c214c118516">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a42859e81c863cc365f29938285e98a68">has_root_path</a> (const Twine &amp;path, Style style=Style::native)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Has root path? <a href="#a42859e81c863cc365f29938285e98a68">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a111a7c3004bc8e2a53a501c70fd5f392">has_relative_path</a> (const Twine &amp;path, Style style=Style::native)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Has relative path? <a href="#a111a7c3004bc8e2a53a501c70fd5f392">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a532941f1ad0bf4dcc13beb5cd6d000d4">has_parent_path</a> (const Twine &amp;path, Style style=Style::native)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Has parent path? <a href="#a532941f1ad0bf4dcc13beb5cd6d000d4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad94879f2cf05db817fc49abbe50fbbb1">has_filename</a> (const Twine &amp;path, Style style=Style::native)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Has filename? <a href="#ad94879f2cf05db817fc49abbe50fbbb1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac4d78a6e97131191378aa1ca03a6c7f5">has_stem</a> (const Twine &amp;path, Style style=Style::native)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Has stem? <a href="#ac4d78a6e97131191378aa1ca03a6c7f5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a71f8caad22bde933605f9d1634f63288">has_extension</a> (const Twine &amp;path, Style style=Style::native)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Has extension? <a href="#a71f8caad22bde933605f9d1634f63288">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac35ec1dacb408d4c65d55249c0e02474">is_absolute</a> (const Twine &amp;path, Style style=Style::native)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Is path absolute? <a href="#ac35ec1dacb408d4c65d55249c0e02474">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a892ec9d16a6daa5ed0965c36fc1caff7">is_absolute_gnu</a> (const Twine &amp;path, Style style=Style::native)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Is path absolute using GNU rules? <a href="#a892ec9d16a6daa5ed0965c36fc1caff7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a59d172f36ecf079548e9c539ae54e5a4">is_relative</a> (const Twine &amp;path, Style style=Style::native)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Is path relative? <a href="#a59d172f36ecf079548e9c539ae54e5a4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<div class="doxySectionDef">

## Enumerations

### Style {#a58cfd8a47c0ef96db27b451c2d6ec49f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum class llvm::sys::path::Style </td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel strong">strong</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">native<a id="a58cfd8a47c0ef96db27b451c2d6ec49fa8e5f3adee38c8fccc13c1f3be0143796"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">posix<a id="a58cfd8a47c0ef96db27b451c2d6ec49fa950616e5405e4ef51a87d384180e7aa1"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">windows_slash<a id="a58cfd8a47c0ef96db27b451c2d6ec49fafad9c40f029f501b12446408f7ce41a3"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">windows_backslash<a id="a58cfd8a47c0ef96db27b451c2d6ec49fa20919b5752b40386cb56aff9b8f07723"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">windows<a id="a58cfd8a47c0ef96db27b451c2d6ec49fa0f4137ed1502b5045d6083aa258b5c42"></a></td>
<td class="doxyEnumItemDescription"> (= windows_backslash)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 27 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/path-h">Path.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### is\_style\_posix() {#a4a8239d7a446775682284318d3c986ad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sys::path::is_style_posix (<a href="#a58cfd8a47c0ef96db27b451c2d6ec49f">Style</a> S)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if <span class="doxyComputerOutput">S</span> uses POSIX path rules.</p>

<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/path-h">Path.h</a>.</p>


<p>References <a href="#a58cfd8a47c0ef96db27b451c2d6ec49fa8e5f3adee38c8fccc13c1f3be0143796">native</a> and <a href="#a58cfd8a47c0ef96db27b451c2d6ec49fa950616e5405e4ef51a87d384180e7aa1">posix</a>.</p>


<p>Referenced by <a href="#aa8749375717a95d086e49f655fa75046">convert_to_slash</a>, <a href="#ac35ec1dacb408d4c65d55249c0e02474">is_absolute</a> and <a href="#ac533465ca310da3741ef2fb8794c0599">is_style_windows</a>.</p>

</div>
</div>

### is\_style\_windows() {#ac533465ca310da3741ef2fb8794c0599}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sys::path::is_style_windows (<a href="#a58cfd8a47c0ef96db27b451c2d6ec49f">Style</a> S)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if <span class="doxyComputerOutput">S</span> uses Windows path rules.</p>

<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/path-h">Path.h</a>.</p>


<p>Reference <a href="#a4a8239d7a446775682284318d3c986ad">is_style_posix</a>.</p>


<p>Referenced by <a href="#a892ec9d16a6daa5ed0965c36fc1caff7">is_absolute_gnu</a>, <a href="#aecbfb983627865ec98e96179df881e37">is_separator</a>, <a href="#a58dcbf859a69b30932a6ed45806f8a5b">make_preferred</a>, <a href="#a2bfecff239f87c7bd19f128186b428a2">native</a>, <a href="/web-llvm/docs/api/classes/llvm/sys/path/const-iterator/#a147fd37ff13580e881af72fa45a16127">llvm::sys::path::const_iterator::operator++</a>, <a href="#acb21fbbf512744e0346d8efc14ae4246">root_directory</a>, <a href="#ac9c7e606723471849eec491d24e618c4">root_name</a>, <a href="#a01ce989dcb8d95a2b5532357abc39096">root_path</a> and <a href="#aeaa763a458fd0b6a1f1b395784259de8">starts_with</a>.</p>

</div>
</div>

### rbegin() {#a728fc9f9b2d1a3a32b6fd2e785eb7b67}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">reverse_iterator llvm::sys::path::rbegin (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Path, <a href="#a58cfd8a47c0ef96db27b451c2d6ec49f">Style</a> style)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 297 of file <a href="/web-llvm/docs/api/files/lib/lib/support/path-cpp">Path.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### remove\_leading\_dotslash() {#a7e2885e8a85c17ac8a95094c7b6bba2f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::sys::path::remove_leading_dotslash (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Path, <a href="#a58cfd8a47c0ef96db27b451c2d6ec49f">Style</a> style)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 703 of file <a href="/web-llvm/docs/api/files/lib/lib/support/path-cpp">Path.cpp</a>.</p>


<p>Reference <a href="#aecbfb983627865ec98e96179df881e37">is_separator</a>.</p>

</div>
</div>

### rend() {#aeec6efa9f64fb65e63600ebe128c2ebb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">reverse_iterator llvm::sys::path::rend (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Path)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 306 of file <a href="/web-llvm/docs/api/files/lib/lib/support/path-cpp">Path.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### starts\_with() {#aeaa763a458fd0b6a1f1b395784259de8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sys::path::starts_with (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Path, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Prefix, <a href="#a58cfd8a47c0ef96db27b451c2d6ec49f">Style</a> style=<a href="#a58cfd8a47c0ef96db27b451c2d6ec49fa8e5f3adee38c8fccc13c1f3be0143796">Style::native</a>)</td>
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



<p>Definition at line 499 of file <a href="/web-llvm/docs/api/files/lib/lib/support/path-cpp">Path.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#aecbfb983627865ec98e96179df881e37">is_separator</a>, <a href="#ac533465ca310da3741ef2fb8794c0599">is_style_windows</a> and <a href="#a58cfd8a47c0ef96db27b451c2d6ec49fa8e5f3adee38c8fccc13c1f3be0143796">native</a>.</p>


<p>Referenced by <a href="#acb31f2db6f0fe5eaa5b28464141223aa">replace_path_prefix</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Lexical Component Iterator

### begin {#a2798f80ce7d64ebc7049d1231e675137}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_iterator llvm::sys::path::begin (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> path LLVM_LIFETIME_BOUND, <a href="#a58cfd8a47c0ef96db27b451c2d6ec49f">Style</a> style=<a href="#a58cfd8a47c0ef96db27b451c2d6ec49fa8e5f3adee38c8fccc13c1f3be0143796">Style::native</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get begin iterator over <em>path</em>.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">path</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/classes/input">Input</a> path.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>Iterator initialized with the first component of <em>path</em>.</p></dd>
</dl>


<p>Definition at line 226 of file <a href="/web-llvm/docs/api/files/lib/lib/support/path-cpp">Path.cpp</a>.</p>


<p>Referenced by <a href="#a4214dc81eb25ef3732b21822ee0e0563">append</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aca0a563fd83342f33e00910843466946">llvm::computeArchiveRelativePath</a>, <a href="/web-llvm/docs/api/classes/llvm/vfs/redirectingfilesystem/#a1889d01b571d20008558e46cea63f435">llvm::vfs::RedirectingFileSystem::create</a>, <a href="/web-llvm/docs/api/classes/llvm/vfs/redirectingfilesystem/#a5f8600aa879b6d745a7f94e5b0ffaffd">llvm::vfs::RedirectingFileSystem::lookupPath</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a3197ec81e63f7894669273704bd132be">llvm::MachO::make_relative</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/virtualfilesystem-cpp/#a9717df28b0bbc67e6b6acc31f96b97df">pathHasTraversal</a>, <a href="#a6aa32b6763df05d8187ad5551533b567">remove_leading_dotslash</a>, <a href="#acb21fbbf512744e0346d8efc14ae4246">root_directory</a>, <a href="#ac9c7e606723471849eec491d24e618c4">root_name</a> and <a href="#a01ce989dcb8d95a2b5532357abc39096">root_path</a>.</p>

</div>
</div>

### end {#ae6199e07e1f06cdaf0ad59b959045035}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_iterator llvm::sys::path::end (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> path LLVM_LIFETIME_BOUND)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get end iterator over <em>path</em>.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">path</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/classes/input">Input</a> path.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>Iterator initialized to the end of <em>path</em>.</p></dd>
</dl>


<p>Definition at line 235 of file <a href="/web-llvm/docs/api/files/lib/lib/support/path-cpp">Path.cpp</a>.</p>


<p>Referenced by <a href="#a4214dc81eb25ef3732b21822ee0e0563">append</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aca0a563fd83342f33e00910843466946">llvm::computeArchiveRelativePath</a>, <a href="/web-llvm/docs/api/classes/llvm/vfs/redirectingfilesystem/#a1889d01b571d20008558e46cea63f435">llvm::vfs::RedirectingFileSystem::create</a>, <a href="/web-llvm/docs/api/classes/llvm/vfs/redirectingfilesystem/#a5f8600aa879b6d745a7f94e5b0ffaffd">llvm::vfs::RedirectingFileSystem::lookupPath</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a3197ec81e63f7894669273704bd132be">llvm::MachO::make_relative</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/virtualfilesystem-cpp/#a9717df28b0bbc67e6b6acc31f96b97df">pathHasTraversal</a>, <a href="#a6aa32b6763df05d8187ad5551533b567">remove_leading_dotslash</a>, <a href="#acb21fbbf512744e0346d8efc14ae4246">root_directory</a>, <a href="#ac9c7e606723471849eec491d24e618c4">root_name</a> and <a href="#a01ce989dcb8d95a2b5532357abc39096">root_path</a>.</p>

</div>
</div>

### rbegin {#ae116bcdf5fac57d6da943935fb6c547a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">reverse_iterator llvm::sys::path::rbegin (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> path LLVM_LIFETIME_BOUND, <a href="#a58cfd8a47c0ef96db27b451c2d6ec49f">Style</a> style=<a href="#a58cfd8a47c0ef96db27b451c2d6ec49fa8e5f3adee38c8fccc13c1f3be0143796">Style::native</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get reverse begin iterator over <em>path</em>.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">path</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/classes/input">Input</a> path.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>Iterator initialized with the first reverse component of <em>path</em>.</p></dd>
</dl>


<p>Definition at line 133 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/path-h">Path.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#aac3d0ea99ec07497e1d0fd0cdfc18040">LLVM_LIFETIME_BOUND</a> and <a href="#a58cfd8a47c0ef96db27b451c2d6ec49fa8e5f3adee38c8fccc13c1f3be0143796">native</a>.</p>


<p>Referenced by <a href="#aa56d25bb5127dd7a5831c25764f76cbe">filename</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5a9952645a56e841314d2b880bd31375">llvm::findVCToolChainViaEnvironment</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a0e06d133446b7cfbee6b1800f3d993f7">llvm::dwarf_linker::guessDeveloperDir</a> and <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a85aa80526a5484cfab745ec2440b1a9e">llvm::dwarf_linker::isInToolchainDir</a>.</p>

</div>
</div>

### rend {#a2bc70cc8c5a83b940ed7c948b28dc512}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">reverse_iterator llvm::sys::path::rend (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> path LLVM_LIFETIME_BOUND)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get reverse end iterator over <em>path</em>.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">path</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/classes/input">Input</a> path.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>Iterator initialized to the reverse end of <em>path</em>.</p></dd>
</dl>


<p>Definition at line 139 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/path-h">Path.h</a>.</p>


<p>References <a href="#ad1056825d31bf187d0be430c51aac281">extension</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#aac3d0ea99ec07497e1d0fd0cdfc18040">LLVM_LIFETIME_BOUND</a> and <a href="#a58cfd8a47c0ef96db27b451c2d6ec49fa8e5f3adee38c8fccc13c1f3be0143796">native</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a5a9952645a56e841314d2b880bd31375">llvm::findVCToolChainViaEnvironment</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a0e06d133446b7cfbee6b1800f3d993f7">llvm::dwarf_linker::guessDeveloperDir</a> and <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a85aa80526a5484cfab745ec2440b1a9e">llvm::dwarf_linker::isInToolchainDir</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Lexical Modifiers

### append {#acb80894344c78dacf8d5ff8c23be697d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::sys::path::append (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; char &gt; &amp; path, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; a, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; b="", <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; c="", <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; d="")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Append to path.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">/foo  + bar/f =&gt; /foo/bar/f</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">/foo/ + bar/f =&gt; /foo/bar/f</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">foo   + bar/f =&gt; foo/bar/f</span></span></div>

</div>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">path</td>
<td class="doxyParamItemDescription"><p>Set to <em>path</em> + <em>component</em>.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">a</td>
<td class="doxyParamItemDescription"><p>The component to be appended to <em>path</em>.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 456 of file <a href="/web-llvm/docs/api/files/lib/lib/support/path-cpp">Path.cpp</a>.</p>


<p>References <a href="#acb80894344c78dacf8d5ff8c23be697d">append</a> and <a href="#a58cfd8a47c0ef96db27b451c2d6ec49fa8e5f3adee38c8fccc13c1f3be0143796">native</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/filecollector/#ace0419c07a92964cb26904561edc7203">llvm::FileCollector::addFileImpl</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad1a874181e3007dcd2735f381c3db6d8">llvm::analyzeImportedModule</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#a188e713b7044fc7477fa27c6f4efc662">llvm::dwarf_linker::parallel::CompileUnit::analyzeImportedModule</a>, <a href="#acb80894344c78dacf8d5ff8c23be697d">append</a>, <a href="#a4214dc81eb25ef3732b21822ee0e0563">append</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae4bae58c61ecb36efa5d563c745b9d53">llvm::appendArchToWindowsSDKLibPath</a>, <a href="/web-llvm/docs/api/files/lib/lib/lto/ltobackend-cpp/#a889b75e55af23f854f7f597b0e912b98">codegen</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aca0a563fd83342f33e00910843466946">llvm::computeArchiveRelativePath</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvreader/#a53b8fdf818581607c61a5b0bdd3bf5ed">llvm::logicalview::LVReader::createAlternativePath</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#aa37537b95a42a73ea04d8dd2803378da">llvm::sys::fs::createUniquePath</a>, <a href="/web-llvm/docs/api/namespaces/llvm/remarks/#ae465be28151991b2345f467899ddb5e5">llvm::remarks::createYAMLParserFromMeta</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/commandline-cpp/#a3b32f7427a25293e5cb32d481a342ebc">ExpandBasePaths</a>, <a href="/web-llvm/docs/api/classes/llvm/cl/expansioncontext/#aebe5d0c3153807263988efc57d69a509">llvm::cl::ExpansionContext::expandResponseFiles</a>, <a href="/web-llvm/docs/api/classes/llvm/object/buildidfetcher/#a0b88868ad72597e4cc566ca26068dfc9">llvm::object::BuildIDFetcher::fetch</a>, <a href="/web-llvm/docs/api/classes/llvm/cl/expansioncontext/#aa1382b606ff796c22a7416ba7f6b856b">llvm::cl::ExpansionContext::findConfigFile</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a301ba38f5a267f3cf123d6a9f551e3fd">llvm::object::MachOObjectFile::findDsymObjectMembers</a>, <a href="/web-llvm/docs/api/classes/llvm/sys/process/#a2d23569135fe239b43594b6e8b99e67e">llvm::sys::Process::FindInEnvPath</a>, <a href="/web-llvm/docs/api/files/lib/lib/tooldrivers/lib/tooldrivers/llvm-lib/libdriver-cpp/#a570cb3a957fe20e3423fcdd5309a4e59">findInputFile</a>, <a href="/web-llvm/docs/api/files/lib/lib/testing/lib/testing/support/supporthelpers-cpp/#a8337121b3770210b77b84ed8bac1e71a">findSrcDirMap</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22439c20979b1335d2c672289f5a1d06">llvm::findVCToolChainViaCommandLine</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5a9952645a56e841314d2b880bd31375">llvm::findVCToolChainViaEnvironment</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aee9b1b3966b67cad2185aac5d1159358">llvm::findVCToolChainViaRegistry</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a79c3f6c8d0e321d8b23f365e485bfde7">llvm::findVCToolChainViaSetupConfig</a>, <a href="/web-llvm/docs/api/classes/llvm/diagnosticlocation/#a7ceb314d2d75df52466e0f586da8bd42">llvm::DiagnosticLocation::getAbsolutePath</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a42f631dfb82c9318a72f2c1bdab57ad4">llvm::getCachedOrDownloadArtifact</a>, <a href="/web-llvm/docs/api/namespaces/llvm/symbolize/anonymous-symbolize-cpp-/#a09ab439d0ecd05e649734000a3e35478">llvm::symbolize::anonymous{Symbolize.cpp}::getDarwinDWARFResourceForPath</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8a4c2b693d9663216a1952801598efad">llvm::getDebuginfodDebuginfoUrlPath</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a483d4e85c83df350bd6013d6f825d83e">llvm::getDebuginfodExecutableUrlPath</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a320dd800a37d3ce31b7d0b2c929e964e">llvm::getDebuginfodSourceUrlPath</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#afa783dbdf91c831ef800357855a3e66b">llvm::getDefaultDebuginfodCacheDirectory</a>, <a href="/web-llvm/docs/api/classes/llvm/lineeditor/#a6cf24dc9e2a09abc839f199155753e53">llvm::LineEditor::getDefaultHistoryPath</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#a53949973d752a1d918687b758424714a">llvm::dwarf_linker::parallel::CompileUnit::getDirAndFilenameFromLineTable</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/gcovprofiling-cpp/#ab5eafaf67b9a450116b00366916c375b">getFilename</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarfdebugline/prologue/#aa47cad32e9eb34704f1ce2ead863e518">llvm::DWARFDebugLine::Prologue::getFileNameByIndex</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-jmcinstrumenter-cpp-/#aaf0c2486053fb36198712fec3c354365">anonymous{JMCInstrumenter.cpp}::getFlagName</a>, <a href="/web-llvm/docs/api/classes/llvm/object/archive/child/#a22ece0b78ccffb215a68d44b94b46e2f">llvm::object::Archive::Child::getFullName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/unittest/#aa3aa8b23b1c244615ed10c125922fc05">llvm::unittest::getInputFileDirectory</a>, <a href="/web-llvm/docs/api/structs/llvm/vfs/redirectingfilesystem/lookupresult/#aaaa3106261fa4af53b07b638d39a1ae3">llvm::vfs::RedirectingFileSystem::LookupResult::getPath</a>, <a href="/web-llvm/docs/api/structs/llvm/gsym/lookupresult/#a4bf35524898c34b917e813177d64d735">llvm::gsym::LookupResult::getSourceFile</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abf156ed576f5bcdb93911b50b775c8ac">llvm::getSubDirectoryPath</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/virtualfilesystem-cpp/#a5193c36762bd45216d0e979c04df5d49">getVFSEntries</a>, <a href="/web-llvm/docs/api/files/lib/lib/windowsdriver/msvcpaths-cpp/#aaab71b93eca9d982bc9970e71076230f">getWindows10SDKVersionFromPath</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3f08996be2dce22d6d6777faaa4cbe41">llvm::getWindowsSDKDir</a>, <a href="/web-llvm/docs/api/files/lib/lib/windowsdriver/msvcpaths-cpp/#a8805ce08308a58e2e99c8ab39d4ebdc2">getWindowsSDKDirViaCommandLine</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/dwarflinkerimpl/linkcontext/#a21dc5ae67ffaf38250ef5b5d377b5358">llvm::dwarf_linker::parallel::DWARFLinkerImpl::LinkContext::loadClangModule</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af73b4fcac77298355025a0e5975edcf0">llvm::localCache</a>, <a href="/web-llvm/docs/api/structs/llvm/vfs/redirectingfilesystem/lookupresult/#aa3989e2bdf4525841695dae351252b79">llvm::vfs::RedirectingFileSystem::LookupResult::LookupResult</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a144ec9dcc77027317d16af9fc5fec1c8">llvm::sys::fs::make_absolute</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a3197ec81e63f7894669273704bd132be">llvm::MachO::make_relative</a>, <a href="/web-llvm/docs/api/classes/anonymous-thinltocodegenerator-cpp-/modulecacheentry/#aea61f7d56840b1a92477a55f4a526de0">anonymous{ThinLTOCodeGenerator.cpp}::ModuleCacheEntry::ModuleCacheEntry</a>, <a href="/web-llvm/docs/api/classes/llvm/sourcemgr/#a0c8517e1b412dcd4f30cdce1c9541cc9">llvm::SourceMgr::OpenIncludeFile</a>, <a href="/web-llvm/docs/api/classes/llvm/unittest/tempdir/#a4fedc9edca1b25db9e33f374756969d3">llvm::unittest::TempDir::path</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aabba6d27907082520ad2eb977c8e406b">llvm::pruneCache</a>, <a href="/web-llvm/docs/api/classes/llvm/sys/fs/directory-entry/#af74c609b9d0a0eba4ea8f416dc2b0f19">llvm::sys::fs::directory_entry::replace_filename</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/classic/cachedpathresolver/#a83dd2ec674ed050c3d4dd6f9541f8fd4">llvm::dwarf_linker::classic::CachedPathResolver::resolve</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a562e5e47a3837612432809e480b901e3">llvm::resolveRelativeObjectPath</a>, <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerimpl-cpp/#afe898cf0f66a7d6fe7193b5d7d70ac8e">resolveRelativeObjectPath</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpusplitmodulepass/#a5fdf4ead69288861f3151e0f035a9877">llvm::AMDGPUSplitModulePass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/nativesession/#a10c66fa7ae2a9b589c8a2738661897ca">llvm::pdb::NativeSession::searchForPdb</a>, <a href="/web-llvm/docs/api/classes/anonymous-virtualfilesystem-cpp-/redirectingfsdirremapiterimpl/#ad69a8251f6cfe071e414c7c3cf78cb9c">anonymous{VirtualFileSystem.cpp}::RedirectingFSDirRemapIterImpl::setCurrentEntry</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#ae44a97a569de65d01e1f80ae5261121b">llvm::MCContext::setGenDwarfRootFile</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a407d3b5b3a2a0c0a80e87d7b03b4b2e2">llvm::useUniversalCRT</a> and <a href="/web-llvm/docs/api/groups/set/#gacacf298ae33051bd387434c4ebdd2be7">llvm::ThinLTOCodeGenerator::writeGeneratedObject</a>.</p>

</div>
</div>

### append {#a1b070d2edba351e90bf5a08b656895a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::sys::path::append (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; char &gt; &amp; path, <a href="#a58cfd8a47c0ef96db27b451c2d6ec49f">Style</a> style, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; a, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; b="", <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; c="", <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; d="")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 418 of file <a href="/web-llvm/docs/api/files/lib/lib/support/path-cpp">Path.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringref/#a46f643f1eb1939362c7dd79361bcbd0e">llvm::StringRef::begin</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a996c7ca3dd6843ba5d55a7c217770270">llvm::StringRef::end</a>, <a href="#a1dae3a7c3f46eaa1201a537367693f11">has_root_name</a>, <a href="#aecbfb983627865ec98e96179df881e37">is_separator</a>, <a href="/web-llvm/docs/api/classes/llvm/twine/#a771462b870698fdc4c2484b78ce96f6d">llvm::Twine::isTriviallyEmpty</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a> and <a href="/web-llvm/docs/api/classes/llvm/twine/#ac521760e9a45f304a4cbe46ed4fff845">llvm::Twine::toStringRef</a>.</p>

</div>
</div>

### append {#a4214dc81eb25ef3732b21822ee0e0563}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::sys::path::append (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; char &gt; &amp; path, <a href="/web-llvm/docs/api/classes/llvm/sys/path/const-iterator">const_iterator</a> begin, <a href="/web-llvm/docs/api/classes/llvm/sys/path/const-iterator">const_iterator</a> end, <a href="#a58cfd8a47c0ef96db27b451c2d6ec49f">Style</a> style=<a href="#a58cfd8a47c0ef96db27b451c2d6ec49fa8e5f3adee38c8fccc13c1f3be0143796">Style::native</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Append to path.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">/foo  + [bar,f] =&gt; /foo/bar/f</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">/foo/ + [bar,f] =&gt; /foo/bar/f</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">foo   + [bar,f] =&gt; foo/bar/f</span></span></div>

</div>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">path</td>
<td class="doxyParamItemDescription"><p>Set to <em>path</em> + [<em>begin</em>, <em>end</em>).</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">begin</td>
<td class="doxyParamItemDescription"><p>Start of components to append.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">end</td>
<td class="doxyParamItemDescription"><p>One past the end of components to append.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 461 of file <a href="/web-llvm/docs/api/files/lib/lib/support/path-cpp">Path.cpp</a>.</p>


<p>References <a href="#acb80894344c78dacf8d5ff8c23be697d">append</a>, <a href="#a2798f80ce7d64ebc7049d1231e675137">begin</a> and <a href="#ae6199e07e1f06cdaf0ad59b959045035">end</a>.</p>

</div>
</div>

### remove\_dots {#a35c103b5fb70a66a1cb5da3b56f588a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sys::path::remove_dots (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; char &gt; &amp; path, bool remove_dot_dot=false, <a href="#a58cfd8a47c0ef96db27b451c2d6ec49f">Style</a> style=<a href="#a58cfd8a47c0ef96db27b451c2d6ec49fa8e5f3adee38c8fccc13c1f3be0143796">Style::native</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>In-place remove any '.</p>


<p>/' and optionally '../' components from a path.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">path</td>
<td class="doxyParamItemDescription"><p>processed path</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">remove_dot_dot</td>
<td class="doxyParamItemDescription"><p>specify if '../' (except for leading "../") should be removed</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>True if path was changed</p></dd>
</dl>


<p>Definition at line 715 of file <a href="/web-llvm/docs/api/files/lib/lib/support/path-cpp">Path.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ab9c6b351507d3c0730f4290919d43a12">llvm::ArrayRef</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#acd9e771a3296c6b24146955754620557">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::back</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a7b68be12c974b6b70bc86062f221a344">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::data</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a3fb2867a1e9fa36e135d9ee4dffb0167">llvm::StringRef::drop_front</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2dc80c585ad5882da8cae7b5968f7e74">llvm::StringRef::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a93b15a8c0022febbe39d17ab933737a8">llvm::StringRef::find_first_of</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a61364ca3a5ff90fb2aa0d5a371fd43f7">llvm::StringRef::front</a>, <a href="#a58dcbf859a69b30932a6ed45806f8a5b">make_preferred</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#ad0f54a163ac500b144590640c6f1eb6b">llvm::StringRef::npos</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#ad97688dfe9cd802e2a0691cbe620218a">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::pop_back</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="#a01ce989dcb8d95a2b5532357abc39096">root_path</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a5db9240c74644c67759dd0f901fc3c7d">llvm::StringRef::size</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#abd962b7b01f49ce61ea41ee10c49e313">llvm::SmallVectorImpl&lt; T &gt;::swap</a> and <a href="/web-llvm/docs/api/classes/llvm/stringref/#aa28286a33491b5d9a936fb6ae853baee">llvm::StringRef::take_front</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-virtualfilesystem-cpp-/#a40622597859734327699df418a4b686b">anonymous{VirtualFileSystem.cpp}::canonicalize</a>, <a href="/web-llvm/docs/api/classes/llvm/filecollector/pathcanonicalizer/#ac656bc9e1653748650e52573708cdf20">llvm::FileCollector::PathCanonicalizer::canonicalize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad391126f2a798e3a009cba7778d0c5ef">llvm::canonicalizePath</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a301ba38f5a267f3cf123d6a9f551e3fd">llvm::object::MachOObjectFile::findDsymObjectMembers</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-jmcinstrumenter-cpp-/#aaf0c2486053fb36198712fec3c354365">anonymous{JMCInstrumenter.cpp}::getFlagName</a>, <a href="/web-llvm/docs/api/classes/llvm/vfs/inmemoryfilesystem/#a29c7a2f361d2018ff1bae9ddc9d50cc1">llvm::vfs::InMemoryFileSystem::getRealPath</a> and <a href="/web-llvm/docs/api/classes/llvm/vfs/inmemoryfilesystem/#ac03492c3b5f13e9fcc7d28e9130902fe">llvm::vfs::InMemoryFileSystem::setCurrentWorkingDirectory</a>.</p>

</div>
</div>

### remove\_filename {#a03907c7df68a93c377bf90c5bdd78ca3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::sys::path::remove_filename (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; char &gt; &amp; path, <a href="#a58cfd8a47c0ef96db27b451c2d6ec49f">Style</a> style=<a href="#a58cfd8a47c0ef96db27b451c2d6ec49fa8e5f3adee38c8fccc13c1f3be0143796">Style::native</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Remove the last component from <em>path</em> unless it is the root dir.</p>


<p>Similar to the POSIX "dirname" utility.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">directory/<a href="#aa56d25bb5127dd7a5831c25764f76cbe">filename</a>.cpp =&gt; directory/</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">directory/             =&gt; directory</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#aa56d25bb5127dd7a5831c25764f76cbe">filename</a>.cpp           =&gt; &lt;empty&gt;</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">/                      =&gt; /</span></span></div>

</div>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">path</td>
<td class="doxyParamItemDescription"><p>A path that is modified to not have a file component.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 474 of file <a href="/web-llvm/docs/api/files/lib/lib/support/path-cpp">Path.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/stringref/#ad0f54a163ac500b144590640c6f1eb6b">llvm::StringRef::npos</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-jmcinstrumenter-cpp-/#aaf0c2486053fb36198712fec3c354365">anonymous{JMCInstrumenter.cpp}::getFlagName</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/nativesession/#a10c66fa7ae2a9b589c8a2738661897ca">llvm::pdb::NativeSession::searchForPdb</a> and <a href="/web-llvm/docs/api/classes/llvm/mccontext/#ae44a97a569de65d01e1f80ae5261121b">llvm::MCContext::setGenDwarfRootFile</a>.</p>

</div>
</div>

### remove\_leading\_dotslash {#a6aa32b6763df05d8187ad5551533b567}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::sys::path::remove_leading_dotslash (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> path LLVM_LIFETIME_BOUND, <a href="#a58cfd8a47c0ef96db27b451c2d6ec49f">Style</a> style=<a href="#a58cfd8a47c0ef96db27b451c2d6ec49fa8e5f3adee38c8fccc13c1f3be0143796">Style::native</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Remove redundant leading "./" pieces and consecutive separators.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">path</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/classes/input">Input</a> path.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The cleaned-up <em>path</em>.</p></dd>
</dl>


<p>Definition at line 204 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/path-h">Path.h</a>.</p>


<p>References <a href="#a2798f80ce7d64ebc7049d1231e675137">begin</a>, <a href="#ae6199e07e1f06cdaf0ad59b959045035">end</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#aac3d0ea99ec07497e1d0fd0cdfc18040">LLVM_LIFETIME_BOUND</a> and <a href="#a58cfd8a47c0ef96db27b451c2d6ec49fa8e5f3adee38c8fccc13c1f3be0143796">native</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-virtualfilesystem-cpp-/#a40622597859734327699df418a4b686b">anonymous{VirtualFileSystem.cpp}::canonicalize</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblocksectionsprofilereaderwrapperpass/#a065b76d17a91964a67b2e45dbc1db7a0">llvm::BasicBlockSectionsProfileReaderWrapperPass::doInitialization</a>, <a href="/web-llvm/docs/api/classes/llvm/diagnosticlocation/#a7ceb314d2d75df52466e0f586da8bd42">llvm::DiagnosticLocation::getAbsolutePath</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/filecollector-cpp/#a20bab096e3719810afee546ab46997c3">makeAbsolute</a>.</p>

</div>
</div>

### replace\_extension {#a1feb0e6007474c599ccfed65dad667c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::sys::path::replace_extension (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; char &gt; &amp; path, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; extension, <a href="#a58cfd8a47c0ef96db27b451c2d6ec49f">Style</a> style=<a href="#a58cfd8a47c0ef96db27b451c2d6ec49fa8e5f3adee38c8fccc13c1f3be0143796">Style::native</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Replace the file extension of <em>path</em> with <em>extension</em>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">./<a href="#aa56d25bb5127dd7a5831c25764f76cbe">filename</a>.cpp =&gt; ./<a href="#aa56d25bb5127dd7a5831c25764f76cbe">filename</a>.extension</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">./<a href="#aa56d25bb5127dd7a5831c25764f76cbe">filename</a>     =&gt; ./<a href="#aa56d25bb5127dd7a5831c25764f76cbe">filename</a>.extension</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">./             =&gt; ./.extension</span></span></div>

</div>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">path</td>
<td class="doxyParamItemDescription"><p>A path that has its extension replaced with <em>extension</em>.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">extension</td>
<td class="doxyParamItemDescription"><p>The extension to be added. It may be empty. It may also optionally start with a '.', if it does not, one will be prepended.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 480 of file <a href="/web-llvm/docs/api/files/lib/lib/support/path-cpp">Path.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringref/#a46f643f1eb1939362c7dd79361bcbd0e">llvm::StringRef::begin</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a996c7ca3dd6843ba5d55a7c217770270">llvm::StringRef::end</a>, <a href="#ad1056825d31bf187d0be430c51aac281">extension</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#ad0f54a163ac500b144590640c6f1eb6b">llvm::StringRef::npos</a> and <a href="/web-llvm/docs/api/classes/llvm/stringref/#a5db9240c74644c67759dd0f901fc3c7d">llvm::StringRef::size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/tooldrivers/lib/tooldrivers/llvm-lib/libdriver-cpp/#a3fd1142983d978a08b0fc7f697d6ca14">getDefaultOutputPath</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a4d93ac5ea92a45b0db717c12e522ed68">llvm::MachO::replace_extension</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lvreaderhandler-cpp/#af7b4a495780ab66e37af8b9881e7ad93">searchForExe</a> and <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lvreaderhandler-cpp/#ad69a1886cef737f69d223f2ffa24d35f">searchForObj</a>.</p>

</div>
</div>

### replace\_path\_prefix {#acb31f2db6f0fe5eaa5b28464141223aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sys::path::replace_path_prefix (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; char &gt; &amp; Path, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> OldPrefix, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> NewPrefix, <a href="#a58cfd8a47c0ef96db27b451c2d6ec49f">Style</a> style=<a href="#a58cfd8a47c0ef96db27b451c2d6ec49fa8e5f3adee38c8fccc13c1f3be0143796">Style::native</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Replace matching path prefix with another path.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">/foo, /old, /</span><span class="doxyHighlightKeyword">new</span><span class="doxyHighlight"> =&gt; /foo</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">/old, /old, /</span><span class="doxyHighlightKeyword">new</span><span class="doxyHighlight"> =&gt; /</span><span class="doxyHighlightKeyword">new</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">/old, /old/, /</span><span class="doxyHighlightKeyword">new</span><span class="doxyHighlight"> =&gt; /old</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">/old/foo, /old, /</span><span class="doxyHighlightKeyword">new</span><span class="doxyHighlight"> =&gt; /</span><span class="doxyHighlightKeyword">new</span><span class="doxyHighlight">/foo</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">/old/foo, /old/, /</span><span class="doxyHighlightKeyword">new</span><span class="doxyHighlight"> =&gt; /</span><span class="doxyHighlightKeyword">new</span><span class="doxyHighlight">/foo</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">/old/foo, /old/, /</span><span class="doxyHighlightKeyword">new</span><span class="doxyHighlight">/ =&gt; /</span><span class="doxyHighlightKeyword">new</span><span class="doxyHighlight">/foo</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">/oldfoo, /old, /</span><span class="doxyHighlightKeyword">new</span><span class="doxyHighlight"> =&gt; /oldfoo</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">/foo, &lt;empty&gt;, /</span><span class="doxyHighlightKeyword">new</span><span class="doxyHighlight"> =&gt; /</span><span class="doxyHighlightKeyword">new</span><span class="doxyHighlight">/foo</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">/foo, &lt;empty&gt;, </span><span class="doxyHighlightKeyword">new</span><span class="doxyHighlight"> =&gt; </span><span class="doxyHighlightKeyword">new</span><span class="doxyHighlight">/foo</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">/old/foo, /old, &lt;empty&gt; =&gt; /foo</span></span></div>

</div>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Path</td>
<td class="doxyParamItemDescription"><p>If <em>Path</em> starts with <em>OldPrefix</em> modify to instead start with <em>NewPrefix</em>.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">OldPrefix</td>
<td class="doxyParamItemDescription"><p>The path prefix to strip from <em>Path</em>.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">NewPrefix</td>
<td class="doxyParamItemDescription"><p>The path prefix to replace <em>NewPrefix</em> with.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">style</td>
<td class="doxyParamItemDescription"><p>The style used to match the prefix. Exact match using Posix style, case/separator insensitive match for Windows style.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if <em>Path</em> begins with OldPrefix</p></dd>
</dl>


<p>Definition at line 518 of file <a href="/web-llvm/docs/api/files/lib/lib/support/path-cpp">Path.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#abb650e853db0ddbb60411b885c499737">llvm::copy</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2dc80c585ad5882da8cae7b5968f7e74">llvm::StringRef::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a5db9240c74644c67759dd0f901fc3c7d">llvm::StringRef::size</a>, <a href="#aeaa763a458fd0b6a1f1b395784259de8">starts_with</a> and <a href="/web-llvm/docs/api/classes/llvm/stringref/#a25f1fd81f2132805676c82ab8ae0c109">llvm::StringRef::substr</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/lto/#a18eabcf596deec54ada617114b818baf">llvm::lto::getThinLTOOutputFile</a>, <a href="/web-llvm/docs/api/classes/anonymous-gcov-cpp-/context/#af21fe9969dd2d37f96a144b9d7376ffa">anonymous{GCOV.cpp}::Context::print</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#a01ecf33b3bb3331985f61bca570827d7">llvm::MCContext::remapDebugPath</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4b28795b9acd4cc2a5d8876f14b95d26">llvm::remapPath</a> and <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerimpl-cpp/#a99c13658bddbf20e00fa44fa66147d4f">remapPath</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Transforms (or some other better name)

### convert\_to\_slash {#aa8749375717a95d086e49f655fa75046}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::sys::path::convert_to_slash (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> path, <a href="#a58cfd8a47c0ef96db27b451c2d6ec49f">Style</a> style=<a href="#a58cfd8a47c0ef96db27b451c2d6ec49fa8e5f3adee38c8fccc13c1f3be0143796">Style::native</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Replaces backslashes with slashes if Windows.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">path</td>
<td class="doxyParamItemDescription"><p>processed path</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The result of replacing backslashes with forward slashes if Windows. On Unix, this function is a no-op because backslashes are valid path chracters.</p></dd>
</dl>


<p>Definition at line 568 of file <a href="/web-llvm/docs/api/files/lib/lib/support/path-cpp">Path.cpp</a>.</p>


<p>Reference <a href="#a4a8239d7a446775682284318d3c986ad">is_style_posix</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/tarwriter/#a75d868e42d390e529a8b7aa0d41362ed">llvm::TarWriter::append</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aca0a563fd83342f33e00910843466946">llvm::computeArchiveRelativePath</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvreader/#a53b8fdf818581607c61a5b0bdd3bf5ed">llvm::logicalview::LVReader::createAlternativePath</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a320dd800a37d3ce31b7d0b2c929e964e">llvm::getDebuginfodSourceUrlPath</a> and <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lvreaderhandler-cpp/#af7b4a495780ab66e37af8b9881e7ad93">searchForExe</a>.</p>

</div>
</div>

### make\_preferred {#a58dcbf859a69b30932a6ed45806f8a5b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::sys::path::make_preferred (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; char &gt; &amp; path, <a href="#a58cfd8a47c0ef96db27b451c2d6ec49f">Style</a> style=<a href="#a58cfd8a47c0ef96db27b451c2d6ec49fa8e5f3adee38c8fccc13c1f3be0143796">Style::native</a>)</td>
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

<p>For Windows path styles, convert path to use the preferred path separators.</p>


<p>For other styles, do nothing.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">path</td>
<td class="doxyParamItemDescription"><p>A path that is transformed to preferred format.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 272 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/path-h">Path.h</a>.</p>


<p>References <a href="#ac533465ca310da3741ef2fb8794c0599">is_style_windows</a> and <a href="#a58cfd8a47c0ef96db27b451c2d6ec49fa8e5f3adee38c8fccc13c1f3be0143796">native</a>.</p>


<p>Referenced by <a href="#a35c103b5fb70a66a1cb5da3b56f588a1">remove_dots</a>.</p>

</div>
</div>

### native {#ab071132a634a15df871b6901c1375c90}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::sys::path::native (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; path, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; char &gt; &amp; result, <a href="#a58cfd8a47c0ef96db27b451c2d6ec49f">Style</a> style=Style::native)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Convert path to the native form.</p>


<p>This is used to give paths to users and operating system calls in the platform's normal way. For example, on Windows all '/' are converted to '\'. On Unix, it converts all '\' to '/'.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">path</td>
<td class="doxyParamItemDescription"><p>A path that is transformed to native format.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">result</td>
<td class="doxyParamItemDescription"><p>Holds the result of the transformation.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 540 of file <a href="/web-llvm/docs/api/files/lib/lib/support/path-cpp">Path.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#aac0ea55010b7b1a301e65a0baea057aa">llvm::SmallVectorImpl&lt; T &gt;::clear</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a7b68be12c974b6b70bc86062f221a344">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::data</a> and <a href="#a58cfd8a47c0ef96db27b451c2d6ec49fa8e5f3adee38c8fccc13c1f3be0143796">native</a>.</p>

</div>
</div>

### native {#a2bfecff239f87c7bd19f128186b428a2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::sys::path::native (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; char &gt; &amp; path, <a href="#a58cfd8a47c0ef96db27b451c2d6ec49f">Style</a> style=Style::native)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Convert path to the native form in place.</p>


<p>This is used to give paths to users and operating system calls in the platform's normal way. For example, on Windows all '/' are converted to '\'.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">path</td>
<td class="doxyParamItemDescription"><p>A path that is transformed to native format.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 550 of file <a href="/web-llvm/docs/api/files/lib/lib/support/path-cpp">Path.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallstring/#ac22cf1a1c08b7ccaefc51508536312a4">llvm::SmallString&lt; InternalLen &gt;::append</a>, <a href="#a1286bcdea03c97a18eb1f41af524f3d3">home_directory</a>, <a href="#aecbfb983627865ec98e96179df881e37">is_separator</a> and <a href="#ac533465ca310da3741ef2fb8794c0599">is_style_windows</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Lexical Observers

### cache\_directory {#a6c8daf95e53b1d17b5965a74533ca217}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sys::path::cache_directory (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; char &gt; &amp; result)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the directory where installed packages should put their machine-local cache, e.g.</p>


<p>$XDG_CACHE_HOME.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">result</td>
<td class="doxyParamItemDescription"><p>Holds the resulting path name.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>True if the appropriate path was determined, it need not exist.</p></dd>
</dl>


<p>Definition at line 443 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/path-h">Path.h</a>.</p>


<p>Reference <a href="#a58cfd8a47c0ef96db27b451c2d6ec49fa8e5f3adee38c8fccc13c1f3be0143796">native</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#afa783dbdf91c831ef800357855a3e66b">llvm::getDefaultDebuginfodCacheDirectory</a>.</p>

</div>
</div>

### extension {#ad1056825d31bf187d0be430c51aac281}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::sys::path::extension (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> path LLVM_LIFETIME_BOUND, <a href="#a58cfd8a47c0ef96db27b451c2d6ec49f">Style</a> style=<a href="#a58cfd8a47c0ef96db27b451c2d6ec49fa8e5f3adee38c8fccc13c1f3be0143796">Style::native</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get extension.</p>


<p>If filename contains a dot but not solely one or two dots, result is the substring of filename starting at (and including) the last dot, and ending at the end of <em>path</em>. Otherwise "".</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">/foo/bar.txt =&gt; .txt</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">/foo/bar     =&gt; &lt;empty&gt;</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">/foo/.txt    =&gt; .txt</span></span></div>

</div>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">path</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/classes/input">Input</a> path.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The extension of <em>path</em>.</p></dd>
</dl>


<p>Definition at line 590 of file <a href="/web-llvm/docs/api/files/lib/lib/support/path-cpp">Path.cpp</a>.</p>


<p>References <a href="#aa56d25bb5127dd7a5831c25764f76cbe">filename</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a7a7c222449f3208a532168c90bfb654d">llvm::StringRef::find_last_of</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#ad0f54a163ac500b144590640c6f1eb6b">llvm::StringRef::npos</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a5db9240c74644c67759dd0f901fc3c7d">llvm::StringRef::size</a> and <a href="/web-llvm/docs/api/classes/llvm/stringref/#a25f1fd81f2132805676c82ab8ae0c109">llvm::StringRef::substr</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfcontext/#a872194924baf250829ba1b42a0b14105">llvm::DWARFContext::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a301ba38f5a267f3cf123d6a9f551e3fd">llvm::object::MachOObjectFile::findDsymObjectMembers</a>, <a href="/web-llvm/docs/api/namespaces/llvm/symbolize/anonymous-symbolize-cpp-/#a09ab439d0ecd05e649734000a3e35478">llvm::symbolize::anonymous{Symbolize.cpp}::getDarwinDWARFResourceForPath</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/pdbsymbolcompiland/#a10cadbc43e6950a1500f1308cb931c2d">llvm::pdb::PDBSymbolCompiland::getSourceFileFullPath</a>, <a href="#a71f8caad22bde933605f9d1634f63288">has_extension</a>, <a href="#a2bc70cc8c5a83b940ed7c948b28dc512">rend</a> and <a href="#a1feb0e6007474c599ccfed65dad667c0">replace_extension</a>.</p>

</div>
</div>

### filename {#aa56d25bb5127dd7a5831c25764f76cbe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::sys::path::filename (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> path LLVM_LIFETIME_BOUND, <a href="#a58cfd8a47c0ef96db27b451c2d6ec49f">Style</a> style=<a href="#a58cfd8a47c0ef96db27b451c2d6ec49fa8e5f3adee38c8fccc13c1f3be0143796">Style::native</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get filename.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">/foo.txt    =&gt; foo.txt</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">.          =&gt; .</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">..         =&gt; ..</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">/          =&gt; /</span></span></div>

</div>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">path</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/classes/input">Input</a> path.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The filename part of <em>path</em>. This is defined as the last component of <em>path</em>. Similar to the POSIX "basename" utility.</p></dd>
</dl>


<p>Definition at line 577 of file <a href="/web-llvm/docs/api/files/lib/lib/support/path-cpp">Path.cpp</a>.</p>


<p>Reference <a href="#ae116bcdf5fac57d6da943935fb6c547a">rbegin</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/vfs/redirectingfilesystem/#a1889d01b571d20008558e46cea63f435">llvm::vfs::RedirectingFileSystem::create</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvreader/#a53b8fdf818581607c61a5b0bdd3bf5ed">llvm::logicalview::LVReader::createAlternativePath</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcopy/coff/#afdcc3a66137dcf1fb3dbdc7adaedc26c">llvm::objcopy::coff::createGnuDebugLinkSectionContents</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a7cd6d58462a0ebf3fa2c3d1423b0e2c6">llvm::AsmPrinter::doInitialization</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6c0d4726ea833a35fd64d21ea9964d33">llvm::emitSourceFileHeader</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcopy/macho/#ad23f6403620ffb61f8c0e1f006f6ea66">llvm::objcopy::macho::executeObjcopyOnBinary</a>, <a href="/web-llvm/docs/api/classes/llvm/modulesummaryindex/#aba8001b30fa09b1b983c01fb4f4f76f5">llvm::ModuleSummaryIndex::exportToDot</a>, <a href="#ad1056825d31bf187d0be430c51aac281">extension</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5a9952645a56e841314d2b880bd31375">llvm::findVCToolChainViaEnvironment</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarfdebugline/prologue/#aa47cad32e9eb34704f1ce2ead863e518">llvm::DWARFDebugLine::Prologue::getFileNameByIndex</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-jmcinstrumenter-cpp-/#aaf0c2486053fb36198712fec3c354365">anonymous{JMCInstrumenter.cpp}::getFlagName</a>, <a href="/web-llvm/docs/api/files/lib/lib/windowsdriver/msvcpaths-cpp/#aceedb180a9ae58c316577d97c5850392">getHighestNumericTupleInDirectory</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/pdbsymbolcompiland/#a09a8cb81d55088ca26ab8918686e217b">llvm::pdb::PDBSymbolCompiland::getSourceFileName</a>, <a href="#ad94879f2cf05db817fc49abbe50fbbb1">has_filename</a>, <a href="/web-llvm/docs/api/classes/llvm/gsym/gsymcreator/#ac9372d27c9fb107c96a7b241848d05ed">llvm::gsym::GsymCreator::insertFile</a>, <a href="/web-llvm/docs/api/namespaces/llvm/memprof/anonymous-memprofreader-cpp-/#ab59efd858858b779261e5cfa73384673">llvm::memprof::anonymous{MemProfReader.cpp}::isRuntimePath</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/classic/dwarflinker/#af6caebcd7dc40dea28562fde4f260414">llvm::dwarf_linker::classic::DWARFLinker::link</a>, <a href="/web-llvm/docs/api/files/lib/lib/profiledata/gcov-cpp/#a9dc80501043000f0bf75820ebfef69c4">mangleCoveragePath</a>, <a href="/web-llvm/docs/api/classes/anonymous-commandline-cpp-/commandlineparser/#a8ff4dbfdf39c7f753e0258704d834879">anonymous{CommandLine.cpp}::CommandLineParser::ParseCommandLineOptions</a>, <a href="/web-llvm/docs/api/classes/anonymous-gcov-cpp-/context/#af21fe9969dd2d37f96a144b9d7376ffa">anonymous{GCOV.cpp}::Context::print</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dwarflinkerimpl/#a557d8187b93bd54d7263d4755c5e99e5">llvm::dwarf_linker::parallel::DWARFLinkerImpl::printStatistic</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aabba6d27907082520ad2eb977c8e406b">llvm::pruneCache</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a4d93ac5ea92a45b0db717c12e522ed68">llvm::MachO::replace_extension</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/classic/cachedpathresolver/#a83dd2ec674ed050c3d4dd6f9541f8fd4">llvm::dwarf_linker::classic::CachedPathResolver::resolve</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/nativesession/#a10c66fa7ae2a9b589c8a2738661897ca">llvm::pdb::NativeSession::searchForPdb</a>, <a href="/web-llvm/docs/api/classes/anonymous-virtualfilesystem-cpp-/redirectingfsdirremapiterimpl/#ad69a8251f6cfe071e414c7c3cf78cb9c">anonymous{VirtualFileSystem.cpp}::RedirectingFSDirRemapIterImpl::setCurrentEntry</a>, <a href="#a1d074d016ff4ab25b0d504bf70a89059">stem</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a69b4f7af261bc6ace511b775a3cb41f6">llvm::timeTraceProfilerInitialize</a>, <a href="/web-llvm/docs/api/structs/llvm/mcdwarflinetableheader/#af400fb04adbd61dff400a8a4a756aff9">llvm::MCDwarfLineTableHeader::tryGetFile</a>, <a href="/web-llvm/docs/api/classes/anonymous-virtualfilesystem-cpp-/jsonwriter/#a1b1532a2254d760451e96bf7b299943b">anonymous{VirtualFileSystem.cpp}::JSONWriter::write</a> and <a href="/web-llvm/docs/api/namespaces/llvm/object/#af9d2c5b5d2afb86f9cdaef1946b79f6c">llvm::object::writeImportLibrary</a>.</p>

</div>
</div>

### get\_separator {#a002a323feef10733642f9f92f6a94f1a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::sys::path::get_separator (<a href="#a58cfd8a47c0ef96db27b451c2d6ec49f">Style</a> style=<a href="#a58cfd8a47c0ef96db27b451c2d6ec49fa8e5f3adee38c8fccc13c1f3be0143796">Style::native</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the preferred separator for this platform.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> of the preferred separator, null-terminated.</p></dd>
</dl>


<p>Definition at line 609 of file <a href="/web-llvm/docs/api/files/lib/lib/support/path-cpp">Path.cpp</a>.</p>


<p>Reference <a href="#a58cfd8a47c0ef96db27b451c2d6ec49fa0f4137ed1502b5045d6083aa258b5c42">windows</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp/#a8ecc921219ca991a8cd7607227646ccf">EmitGenDwarfInfo</a>.</p>

</div>
</div>

### has\_extension {#a71f8caad22bde933605f9d1634f63288}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sys::path::has_extension (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; path, <a href="#a58cfd8a47c0ef96db27b451c2d6ec49f">Style</a> style=<a href="#a58cfd8a47c0ef96db27b451c2d6ec49fa8e5f3adee38c8fccc13c1f3be0143796">Style::native</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Has extension?</p>


<p>extension != ""</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">path</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/classes/input">Input</a> path.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>True if the path has a extension, false otherwise.</p></dd>
</dl>


<p>Definition at line 664 of file <a href="/web-llvm/docs/api/files/lib/lib/support/path-cpp">Path.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2dc80c585ad5882da8cae7b5968f7e74">llvm::StringRef::empty</a> and <a href="#ad1056825d31bf187d0be430c51aac281">extension</a>.</p>

</div>
</div>

### has\_filename {#ad94879f2cf05db817fc49abbe50fbbb1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sys::path::has_filename (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; path, <a href="#a58cfd8a47c0ef96db27b451c2d6ec49f">Style</a> style=<a href="#a58cfd8a47c0ef96db27b451c2d6ec49fa8e5f3adee38c8fccc13c1f3be0143796">Style::native</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Has filename?</p>


<p>filename != ""</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">path</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/classes/input">Input</a> path.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>True if the path has a filename, false otherwise.</p></dd>
</dl>


<p>Definition at line 643 of file <a href="/web-llvm/docs/api/files/lib/lib/support/path-cpp">Path.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2dc80c585ad5882da8cae7b5968f7e74">llvm::StringRef::empty</a> and <a href="#aa56d25bb5127dd7a5831c25764f76cbe">filename</a>.</p>

</div>
</div>

### has\_parent\_path {#a532941f1ad0bf4dcc13beb5cd6d000d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sys::path::has_parent_path (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; path, <a href="#a58cfd8a47c0ef96db27b451c2d6ec49f">Style</a> style=<a href="#a58cfd8a47c0ef96db27b451c2d6ec49fa8e5f3adee38c8fccc13c1f3be0143796">Style::native</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Has parent path?</p>


<p>parent_path != ""</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">path</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/classes/input">Input</a> path.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>True if the path has a parent path, false otherwise.</p></dd>
</dl>


<p>Definition at line 650 of file <a href="/web-llvm/docs/api/files/lib/lib/support/path-cpp">Path.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2dc80c585ad5882da8cae7b5968f7e74">llvm::StringRef::empty</a> and <a href="#a5326427c87607b2364a1fcdf13fa0eea">parent_path</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/cl/expansioncontext/#aa1382b606ff796c22a7416ba7f6b856b">llvm::cl::ExpansionContext::findConfigFile</a>.</p>

</div>
</div>

### has\_relative\_path {#a111a7c3004bc8e2a53a501c70fd5f392}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sys::path::has_relative_path (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; path, <a href="#a58cfd8a47c0ef96db27b451c2d6ec49f">Style</a> style=<a href="#a58cfd8a47c0ef96db27b451c2d6ec49fa8e5f3adee38c8fccc13c1f3be0143796">Style::native</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Has relative path?</p>


<p>relative_path != ""</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">path</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/classes/input">Input</a> path.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>True if the path has a relative path, false otherwise.</p></dd>
</dl>


<p>Definition at line 636 of file <a href="/web-llvm/docs/api/files/lib/lib/support/path-cpp">Path.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2dc80c585ad5882da8cae7b5968f7e74">llvm::StringRef::empty</a> and <a href="#af426cbaa47678fc354ad421fb67e180e">relative_path</a>.</p>

</div>
</div>

### has\_root\_directory {#afbfbc19d8aa5dde440140c214c118516}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sys::path::has_root_directory (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; path, <a href="#a58cfd8a47c0ef96db27b451c2d6ec49f">Style</a> style=<a href="#a58cfd8a47c0ef96db27b451c2d6ec49fa8e5f3adee38c8fccc13c1f3be0143796">Style::native</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Has root directory?</p>


<p>root_directory != ""</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">path</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/classes/input">Input</a> path.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>True if the path has a root directory, false otherwise.</p></dd>
</dl>


<p>Definition at line 622 of file <a href="/web-llvm/docs/api/files/lib/lib/support/path-cpp">Path.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2dc80c585ad5882da8cae7b5968f7e74">llvm::StringRef::empty</a> and <a href="#acb21fbbf512744e0346d8efc14ae4246">root_directory</a>.</p>


<p>Referenced by <a href="#ac35ec1dacb408d4c65d55249c0e02474">is_absolute</a> and <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a144ec9dcc77027317d16af9fc5fec1c8">llvm::sys::fs::make_absolute</a>.</p>

</div>
</div>

### has\_root\_name {#a1dae3a7c3f46eaa1201a537367693f11}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sys::path::has_root_name (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; path, <a href="#a58cfd8a47c0ef96db27b451c2d6ec49f">Style</a> style=<a href="#a58cfd8a47c0ef96db27b451c2d6ec49fa8e5f3adee38c8fccc13c1f3be0143796">Style::native</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Has root name?</p>


<p>root_name != ""</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">path</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/classes/input">Input</a> path.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>True if the path has a root name, false otherwise.</p></dd>
</dl>


<p>Definition at line 615 of file <a href="/web-llvm/docs/api/files/lib/lib/support/path-cpp">Path.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2dc80c585ad5882da8cae7b5968f7e74">llvm::StringRef::empty</a> and <a href="#ac9c7e606723471849eec491d24e618c4">root_name</a>.</p>


<p>Referenced by <a href="#a1b070d2edba351e90bf5a08b656895a5">append</a>, <a href="#ac35ec1dacb408d4c65d55249c0e02474">is_absolute</a> and <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a144ec9dcc77027317d16af9fc5fec1c8">llvm::sys::fs::make_absolute</a>.</p>

</div>
</div>

### has\_root\_path {#a42859e81c863cc365f29938285e98a68}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sys::path::has_root_path (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; path, <a href="#a58cfd8a47c0ef96db27b451c2d6ec49f">Style</a> style=<a href="#a58cfd8a47c0ef96db27b451c2d6ec49fa8e5f3adee38c8fccc13c1f3be0143796">Style::native</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Has root path?</p>


<p>root_path != ""</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">path</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/classes/input">Input</a> path.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>True if the path has a root path, false otherwise.</p></dd>
</dl>


<p>Definition at line 629 of file <a href="/web-llvm/docs/api/files/lib/lib/support/path-cpp">Path.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2dc80c585ad5882da8cae7b5968f7e74">llvm::StringRef::empty</a> and <a href="#a01ce989dcb8d95a2b5532357abc39096">root_path</a>.</p>

</div>
</div>

### has\_stem {#ac4d78a6e97131191378aa1ca03a6c7f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sys::path::has_stem (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; path, <a href="#a58cfd8a47c0ef96db27b451c2d6ec49f">Style</a> style=<a href="#a58cfd8a47c0ef96db27b451c2d6ec49fa8e5f3adee38c8fccc13c1f3be0143796">Style::native</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Has stem?</p>


<p>stem != ""</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">path</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/classes/input">Input</a> path.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>True if the path has a stem, false otherwise.</p></dd>
</dl>


<p>Definition at line 657 of file <a href="/web-llvm/docs/api/files/lib/lib/support/path-cpp">Path.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2dc80c585ad5882da8cae7b5968f7e74">llvm::StringRef::empty</a> and <a href="#a1d074d016ff4ab25b0d504bf70a89059">stem</a>.</p>

</div>
</div>

### home\_directory {#a1286bcdea03c97a18eb1f41af524f3d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sys::path::home_directory (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; char &gt; &amp; result)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the user's home directory.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">result</td>
<td class="doxyParamItemDescription"><p>Holds the resulting path name.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>True if a home directory is set, false otherwise.</p></dd>
</dl>


<p>Definition at line 429 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/path-h">Path.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/lineeditor/#a6cf24dc9e2a09abc839f199155753e53">llvm::LineEditor::getDefaultHistoryPath</a> and <a href="#a2bfecff239f87c7bd19f128186b428a2">native</a>.</p>

</div>
</div>

### is\_absolute {#ac35ec1dacb408d4c65d55249c0e02474}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sys::path::is_absolute (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; path, <a href="#a58cfd8a47c0ef96db27b451c2d6ec49f">Style</a> style=<a href="#a58cfd8a47c0ef96db27b451c2d6ec49fa8e5f3adee38c8fccc13c1f3be0143796">Style::native</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Is path absolute?</p>


<p>According to cppreference.com, C++17 states: "An absolute path is a path
that unambiguously identifies the location of a file without reference to
an additional starting location."</p>


<p>In other words, the rules are: 1) POSIX style paths with nonempty root directory are absolute. 2) Windows style paths with nonempty root name and root directory are absolute. 3) No other paths are absolute.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="#a1dae3a7c3f46eaa1201a537367693f11">has_root_name</a></p></dd>
</dl>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="#afbfbc19d8aa5dde440140c214c118516">has_root_directory</a></p></dd>
</dl>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">path</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/classes/input">Input</a> path.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>True if the path is absolute, false if it is not.</p></dd>
</dl>


<p>Definition at line 671 of file <a href="/web-llvm/docs/api/files/lib/lib/support/path-cpp">Path.cpp</a>.</p>


<p>References <a href="#afbfbc19d8aa5dde440140c214c118516">has_root_directory</a>, <a href="#a1dae3a7c3f46eaa1201a537367693f11">has_root_name</a> and <a href="#a4a8239d7a446775682284318d3c986ad">is_style_posix</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#aa37537b95a42a73ea04d8dd2803378da">llvm::sys::fs::createUniquePath</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/commandline-cpp/#a3b32f7427a25293e5cb32d481a342ebc">ExpandBasePaths</a>, <a href="/web-llvm/docs/api/classes/llvm/filecollector/#a2da94c8c4b02f2361f1add04a67b0a47">llvm::FileCollector::FileCollector</a>, <a href="/web-llvm/docs/api/classes/llvm/sys/process/#a2d23569135fe239b43594b6e8b99e67e">llvm::sys::Process::FindInEnvPath</a>, <a href="/web-llvm/docs/api/classes/llvm/diagnosticlocation/#a7ceb314d2d75df52466e0f586da8bd42">llvm::DiagnosticLocation::getAbsolutePath</a>, <a href="/web-llvm/docs/api/classes/llvm/object/archive/child/#a22ece0b78ccffb215a68d44b94b46e2f">llvm::object::Archive::Child::getFullName</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/pdbsymbolcompiland/#a10cadbc43e6950a1500f1308cb931c2d">llvm::pdb::PDBSymbolCompiland::getSourceFileFullPath</a>, <a href="#a59d172f36ecf079548e9c539ae54e5a4">is_relative</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdebugline-cpp/#a594bed02e2581f6d5fc775acdeeec6a3">isPathAbsoluteOnWindowsOrPosix</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#aba60ebbb0330f9e5e713c887d90a40ea">llvm::dwarf_linker::isPathAbsoluteOnWindowsOrPosix</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#ab6c14b25e5233330251efa8e8ca0c212">llvm::sys::fs::make_absolute</a>, <a href="/web-llvm/docs/api/classes/llvm/vfs/filesystem/#a4181855db0a672fd3271cf9f867b58b4">llvm::vfs::FileSystem::makeAbsolute</a>, <a href="/web-llvm/docs/api/classes/llvm/vfs/redirectingfilesystem/#a34121aca2e132eb1499ce67598c87c1b">llvm::vfs::RedirectingFileSystem::makeAbsolute</a> and <a href="/web-llvm/docs/api/classes/anonymous-gcov-cpp-/context/#af21fe9969dd2d37f96a144b9d7376ffa">anonymous{GCOV.cpp}::Context::print</a>.</p>

</div>
</div>

### is\_absolute\_gnu {#a892ec9d16a6daa5ed0965c36fc1caff7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sys::path::is_absolute_gnu (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; path, <a href="#a58cfd8a47c0ef96db27b451c2d6ec49f">Style</a> style=<a href="#a58cfd8a47c0ef96db27b451c2d6ec49fa8e5f3adee38c8fccc13c1f3be0143796">Style::native</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Is path absolute using GNU rules?</p>


<p>GNU rules are: 1) Paths starting with a path separator are absolute. 2) Windows style paths are also absolute if they start with a character followed by ':'. 3) No other paths are absolute.</p>


<p>On Windows style the path "C:\Users\Default" has "C:" as root name and "\"
as root directory.

Hence "C:" on Windows is absolute under GNU rules and not absolute under
C++17 because it has no root directory. Likewise "/" and "" on Windows are absolute under GNU and are not absolute under C++17 due to empty root name.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="#a1dae3a7c3f46eaa1201a537367693f11">has_root_name</a></p></dd>
</dl>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="#afbfbc19d8aa5dde440140c214c118516">has_root_directory</a></p></dd>
</dl>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">path</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/classes/input">Input</a> path.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">style</td>
<td class="doxyParamItemDescription"><p>The style of <span class="doxyComputerOutput">path</span> (e.g. Windows or POSIX). "native" style means to derive the style from the host.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>True if the path is absolute following GNU rules, false if it is not.</p></dd>
</dl>


<p>Definition at line 681 of file <a href="/web-llvm/docs/api/files/lib/lib/support/path-cpp">Path.cpp</a>.</p>


<p>References <a href="#aecbfb983627865ec98e96179df881e37">is_separator</a> and <a href="#ac533465ca310da3741ef2fb8794c0599">is_style_windows</a>.</p>

</div>
</div>

### is\_relative {#a59d172f36ecf079548e9c539ae54e5a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sys::path::is_relative (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; path, <a href="#a58cfd8a47c0ef96db27b451c2d6ec49f">Style</a> style=<a href="#a58cfd8a47c0ef96db27b451c2d6ec49fa8e5f3adee38c8fccc13c1f3be0143796">Style::native</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Is path relative?</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">path</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/classes/input">Input</a> path.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>True if the path is relative, false if it is not.</p></dd>
</dl>


<p>Definition at line 699 of file <a href="/web-llvm/docs/api/files/lib/lib/support/path-cpp">Path.cpp</a>.</p>


<p>Reference <a href="#ac35ec1dacb408d4c65d55249c0e02474">is_absolute</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#ad1a874181e3007dcd2735f381c3db6d8">llvm::analyzeImportedModule</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#a188e713b7044fc7477fa27c6f4efc662">llvm::dwarf_linker::parallel::CompileUnit::analyzeImportedModule</a>, <a href="/web-llvm/docs/api/classes/llvm/cl/expansioncontext/#aebe5d0c3153807263988efc57d69a509">llvm::cl::ExpansionContext::expandResponseFiles</a>, <a href="/web-llvm/docs/api/classes/llvm/cl/expansioncontext/#aa1382b606ff796c22a7416ba7f6b856b">llvm::cl::ExpansionContext::findConfigFile</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1df6c429f484cbf4fd21a5d306f53671">llvm::libDriverMain</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/dwarflinkerimpl/linkcontext/#a21dc5ae67ffaf38250ef5b5d377b5358">llvm::dwarf_linker::parallel::DWARFLinkerImpl::LinkContext::loadClangModule</a> and <a href="/web-llvm/docs/api/classes/llvm/cl/expansioncontext/#af5cd2f517db910af1c9fd3c0cb03161c">llvm::cl::ExpansionContext::readConfigFile</a>.</p>

</div>
</div>

### is\_separator {#aecbfb983627865ec98e96179df881e37}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sys::path::is_separator (char value, <a href="#a58cfd8a47c0ef96db27b451c2d6ec49f">Style</a> style=<a href="#a58cfd8a47c0ef96db27b451c2d6ec49fa8e5f3adee38c8fccc13c1f3be0143796">Style::native</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> whether the given char is a path separator on the host OS.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">value</td>
<td class="doxyParamItemDescription"><p>a character</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if <em>value</em> is a path separator character on the host OS</p></dd>
</dl>


<p>Definition at line 601 of file <a href="/web-llvm/docs/api/files/lib/lib/support/path-cpp">Path.cpp</a>.</p>


<p>Reference <a href="#ac533465ca310da3741ef2fb8794c0599">is_style_windows</a>.</p>


<p>Referenced by <a href="#a1b070d2edba351e90bf5a08b656895a5">append</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/dumpobjects/#afcdecffed69334cfd8fc517836656751">llvm::orc::DumpObjects::DumpObjects</a>, <a href="#a892ec9d16a6daa5ed0965c36fc1caff7">is_absolute_gnu</a>, <a href="#a2bfecff239f87c7bd19f128186b428a2">native</a>, <a href="/web-llvm/docs/api/classes/llvm/sys/path/const-iterator/#a147fd37ff13580e881af72fa45a16127">llvm::sys::path::const_iterator::operator++</a>, <a href="/web-llvm/docs/api/classes/llvm/sys/path/reverse-iterator/#a6dc88450dbd179d88fc0b3c9e8fdbda4">llvm::sys::path::reverse_iterator::operator++</a>, <a href="/web-llvm/docs/api/classes/anonymous-gcov-cpp-/context/#af21fe9969dd2d37f96a144b9d7376ffa">anonymous{GCOV.cpp}::Context::print</a>, <a href="#a7e2885e8a85c17ac8a95094c7b6bba2f">remove_leading_dotslash</a>, <a href="#acb21fbbf512744e0346d8efc14ae4246">root_directory</a>, <a href="#ac9c7e606723471849eec491d24e618c4">root_name</a>, <a href="#a01ce989dcb8d95a2b5532357abc39096">root_path</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#ae44a97a569de65d01e1f80ae5261121b">llvm::MCContext::setGenDwarfRootFile</a>, <a href="#aeaa763a458fd0b6a1f1b395784259de8">starts_with</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ae16a5e96f09ffb2af4badfc60223f631">llvm::stripDirPrefix</a>.</p>

</div>
</div>

### parent\_path {#a5326427c87607b2364a1fcdf13fa0eea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::sys::path::parent_path (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> path LLVM_LIFETIME_BOUND, <a href="#a58cfd8a47c0ef96db27b451c2d6ec49f">Style</a> style=<a href="#a58cfd8a47c0ef96db27b451c2d6ec49fa8e5f3adee38c8fccc13c1f3be0143796">Style::native</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get parent path.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">/          =&gt; &lt;empty&gt;</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">/foo       =&gt; /</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">foo/../bar =&gt; foo/..</span></span></div>

</div>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">path</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/classes/input">Input</a> path.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The parent path of <em>path</em> if one exists, otherwise "".</p></dd>
</dl>


<p>Definition at line 467 of file <a href="/web-llvm/docs/api/files/lib/lib/support/path-cpp">Path.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/stringref/#ad0f54a163ac500b144590640c6f1eb6b">llvm::StringRef::npos</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#aca0a563fd83342f33e00910843466946">llvm::computeArchiveRelativePath</a>, <a href="/web-llvm/docs/api/classes/llvm/filecollector/#a71730785a9649e84e7680eaf77d0095c">llvm::FileCollector::copyFiles</a>, <a href="/web-llvm/docs/api/classes/llvm/vfs/redirectingfilesystem/#a1889d01b571d20008558e46cea63f435">llvm::vfs::RedirectingFileSystem::create</a>, <a href="/web-llvm/docs/api/classes/llvm/vfs/redirectingfilesystem/#a9f274211d8e2baf7f13ec1e030e09de6">llvm::vfs::RedirectingFileSystem::create</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#ab0231205adf0a10ac89540dbcfdcd2d7">llvm::sys::fs::create_directories</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvreader/#a53b8fdf818581607c61a5b0bdd3bf5ed">llvm::logicalview::LVReader::createAlternativePath</a>, <a href="/web-llvm/docs/api/files/lib/lib/testing/lib/testing/support/supporthelpers-cpp/#a8337121b3770210b77b84ed8bac1e71a">findSrcDirMap</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5a9952645a56e841314d2b880bd31375">llvm::findVCToolChainViaEnvironment</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/pdbfile/#a6f2d70febeee0249977e5f6801ed32aa">llvm::pdb::PDBFile::getFileDirectory</a>, <a href="/web-llvm/docs/api/classes/llvm/object/archive/child/#a22ece0b78ccffb215a68d44b94b46e2f">llvm::object::Archive::Child::getFullName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/lto/#a18eabcf596deec54ada617114b818baf">llvm::lto::getThinLTOOutputFile</a>, <a href="#a532941f1ad0bf4dcc13beb5cd6d000d4">has_parent_path</a>, <a href="/web-llvm/docs/api/classes/llvm/gsym/gsymcreator/#ac9372d27c9fb107c96a7b241848d05ed">llvm::gsym::GsymCreator::insertFile</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a3197ec81e63f7894669273704bd132be">llvm::MachO::make_relative</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/standardinstrumentations-cpp/#aa6094eefcebc8e861eeec90f2c1b935c">prepareDumpIRFileDescriptor</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/signals-cpp/#a1c25905ebd1d19c4d5c4e2ca86cdb1f2">printSymbolizedStackTrace</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a4d93ac5ea92a45b0db717c12e522ed68">llvm::MachO::replace_extension</a>, <a href="/web-llvm/docs/api/classes/llvm/sys/fs/directory-entry/#af74c609b9d0a0eba4ea8f416dc2b0f19">llvm::sys::fs::directory_entry::replace_filename</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/classic/cachedpathresolver/#a83dd2ec674ed050c3d4dd6f9541f8fd4">llvm::dwarf_linker::classic::CachedPathResolver::resolve</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ace7305e89af1fe5485e070f9b0187805">llvm::MachO::shouldSkipSymLink</a>, <a href="/web-llvm/docs/api/structs/llvm/mcdwarflinetableheader/#af400fb04adbd61dff400a8a4a756aff9">llvm::MCDwarfLineTableHeader::tryGetFile</a> and <a href="/web-llvm/docs/api/classes/anonymous-virtualfilesystem-cpp-/jsonwriter/#a1b1532a2254d760451e96bf7b299943b">anonymous{VirtualFileSystem.cpp}::JSONWriter::write</a>.</p>

</div>
</div>

### relative\_path {#af426cbaa47678fc354ad421fb67e180e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::sys::path::relative_path (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> path LLVM_LIFETIME_BOUND, <a href="#a58cfd8a47c0ef96db27b451c2d6ec49f">Style</a> style=<a href="#a58cfd8a47c0ef96db27b451c2d6ec49fa8e5f3adee38c8fccc13c1f3be0143796">Style::native</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get relative path.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">C</a>:\hello\world =&gt; hello\world</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">foo/bar        =&gt; foo/bar</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">/foo/bar       =&gt; foo/bar</span></span></div>

</div>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">path</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/classes/input">Input</a> path.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The path starting after root_path if one exists, otherwise "".</p></dd>
</dl>


<p>Definition at line 413 of file <a href="/web-llvm/docs/api/files/lib/lib/support/path-cpp">Path.cpp</a>.</p>


<p>References <a href="#a01ce989dcb8d95a2b5532357abc39096">root_path</a> and <a href="/web-llvm/docs/api/classes/llvm/stringref/#a5db9240c74644c67759dd0f901fc3c7d">llvm::StringRef::size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/filecollector/#ace0419c07a92964cb26904561edc7203">llvm::FileCollector::addFileImpl</a>, <a href="#a111a7c3004bc8e2a53a501c70fd5f392">has_relative_path</a> and <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a144ec9dcc77027317d16af9fc5fec1c8">llvm::sys::fs::make_absolute</a>.</p>

</div>
</div>

### root\_directory {#acb21fbbf512744e0346d8efc14ae4246}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::sys::path::root_directory (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> path LLVM_LIFETIME_BOUND, <a href="#a58cfd8a47c0ef96db27b451c2d6ec49f">Style</a> style=<a href="#a58cfd8a47c0ef96db27b451c2d6ec49fa8e5f3adee38c8fccc13c1f3be0143796">Style::native</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get root directory.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">/goo/hello =&gt; /</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">c:/hello   =&gt; /</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">d/<a href="/web-llvm/docs/api/files/lib/lib/analysis/regionprinter-cpp/#a79dce2d3eafaf25bf0df59f56caf9712">file</a>.txt =&gt; &lt;empty&gt;</span></span></div>

</div>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">path</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/classes/input">Input</a> path.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The root directory of <em>path</em> if it has one, otherwise "".</p></dd>
</dl>


<p>Definition at line 390 of file <a href="/web-llvm/docs/api/files/lib/lib/support/path-cpp">Path.cpp</a>.</p>


<p>References <a href="#a2798f80ce7d64ebc7049d1231e675137">begin</a>, <a href="#ae6199e07e1f06cdaf0ad59b959045035">end</a>, <a href="#aecbfb983627865ec98e96179df881e37">is_separator</a> and <a href="#ac533465ca310da3741ef2fb8794c0599">is_style_windows</a>.</p>


<p>Referenced by <a href="#afbfbc19d8aa5dde440140c214c118516">has_root_directory</a> and <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a144ec9dcc77027317d16af9fc5fec1c8">llvm::sys::fs::make_absolute</a>.</p>

</div>
</div>

### root\_name {#ac9c7e606723471849eec491d24e618c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::sys::path::root_name (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> path LLVM_LIFETIME_BOUND, <a href="#a58cfd8a47c0ef96db27b451c2d6ec49f">Style</a> style=<a href="#a58cfd8a47c0ef96db27b451c2d6ec49fa8e5f3adee38c8fccc13c1f3be0143796">Style::native</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get root name.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">//net/hello =&gt; //net</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">c:/hello    =&gt; c: (on Windows, on other platforms nothing)</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">/hello      =&gt; &lt;empty&gt;</span></span></div>

</div>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">path</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/classes/input">Input</a> path.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The root name of <em>path</em> if it has one, otherwise "".</p></dd>
</dl>


<p>Definition at line 373 of file <a href="/web-llvm/docs/api/files/lib/lib/support/path-cpp">Path.cpp</a>.</p>


<p>References <a href="#a2798f80ce7d64ebc7049d1231e675137">begin</a>, <a href="#ae6199e07e1f06cdaf0ad59b959045035">end</a>, <a href="#aecbfb983627865ec98e96179df881e37">is_separator</a> and <a href="#ac533465ca310da3741ef2fb8794c0599">is_style_windows</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#aca0a563fd83342f33e00910843466946">llvm::computeArchiveRelativePath</a>, <a href="#a1dae3a7c3f46eaa1201a537367693f11">has_root_name</a> and <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a144ec9dcc77027317d16af9fc5fec1c8">llvm::sys::fs::make_absolute</a>.</p>

</div>
</div>

### root\_path {#a01ce989dcb8d95a2b5532357abc39096}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::sys::path::root_path (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> path LLVM_LIFETIME_BOUND, <a href="#a58cfd8a47c0ef96db27b451c2d6ec49f">Style</a> style=<a href="#a58cfd8a47c0ef96db27b451c2d6ec49fa8e5f3adee38c8fccc13c1f3be0143796">Style::native</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get root path.</p>


<p>Equivalent to root_name + root_directory.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">path</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/classes/input">Input</a> path.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The root path of <em>path</em> if it has one, otherwise "".</p></dd>
</dl>


<p>Definition at line 348 of file <a href="/web-llvm/docs/api/files/lib/lib/support/path-cpp">Path.cpp</a>.</p>


<p>References <a href="#a2798f80ce7d64ebc7049d1231e675137">begin</a>, <a href="#ae6199e07e1f06cdaf0ad59b959045035">end</a>, <a href="#aecbfb983627865ec98e96179df881e37">is_separator</a> and <a href="#ac533465ca310da3741ef2fb8794c0599">is_style_windows</a>.</p>


<p>Referenced by <a href="#a42859e81c863cc365f29938285e98a68">has_root_path</a>, <a href="#af426cbaa47678fc354ad421fb67e180e">relative_path</a> and <a href="#a35c103b5fb70a66a1cb5da3b56f588a1">remove_dots</a>.</p>

</div>
</div>

### stem {#a1d074d016ff4ab25b0d504bf70a89059}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::sys::path::stem (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> path LLVM_LIFETIME_BOUND, <a href="#a58cfd8a47c0ef96db27b451c2d6ec49f">Style</a> style=<a href="#a58cfd8a47c0ef96db27b451c2d6ec49fa8e5f3adee38c8fccc13c1f3be0143796">Style::native</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get stem.</p>


<p>If filename contains a dot but not solely one or two dots, result is the substring of filename ending at (but not including) the last dot. Otherwise it is filename.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">/foo/bar.txt =&gt; bar</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">/foo/bar     =&gt; bar</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">/foo/.txt    =&gt; &lt;empty&gt;</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">/foo/.       =&gt; .</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">/foo/..      =&gt; ..</span></span></div>

</div>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">path</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/classes/input">Input</a> path.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The stem of <em>path</em>.</p></dd>
</dl>


<p>Definition at line 579 of file <a href="/web-llvm/docs/api/files/lib/lib/support/path-cpp">Path.cpp</a>.</p>


<p>References <a href="#aa56d25bb5127dd7a5831c25764f76cbe">filename</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a7a7c222449f3208a532168c90bfb654d">llvm::StringRef::find_last_of</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#ad0f54a163ac500b144590640c6f1eb6b">llvm::StringRef::npos</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a5db9240c74644c67759dd0f901fc3c7d">llvm::StringRef::size</a> and <a href="/web-llvm/docs/api/classes/llvm/stringref/#a25f1fd81f2132805676c82ab8ae0c109">llvm::StringRef::substr</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-dlltooldriver-cpp-/#a0c85406f393901169b49e3d7a27527e0">anonymous{DlltoolDriver.cpp}::getPrefix</a> and <a href="#ac4d78a6e97131191378aa1ca03a6c7f5">has_stem</a>.</p>

</div>
</div>

### system\_temp\_directory {#aa676374c59d0f44d25f9eab4bb824e5a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::sys::path::system_temp_directory (bool erasedOnReboot, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; char &gt; &amp; result)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the typical temporary directory for the system, e.g., "/var/tmp" or "C:/TEMP".</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">erasedOnReboot</td>
<td class="doxyParamItemDescription"><p>Whether to favor a path that is erased on reboot rather than one that potentially persists longer. This parameter will be ignored if the user or system has set the typical environment variable (e.g., TEMP on Windows, TMPDIR on *nix) to specify a temporary directory.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">result</td>
<td class="doxyParamItemDescription"><p>Holds the resulting path name.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 423 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/path-h">Path.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#aa37537b95a42a73ea04d8dd2803378da">llvm::sys::fs::createUniquePath</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpusplitmodulepass/#a5fdf4ead69288861f3151e0f035a9877">llvm::AMDGPUSplitModulePass::run</a>.</p>

</div>
</div>

### user\_config\_directory {#a0e59c9239db6f8becab53eba0bc6d1f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sys::path::user_config_directory (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; char &gt; &amp; result)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the directory where packages should read user-specific configurations.</p>


<p>e.g. $XDG_CONFIG_HOME.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">result</td>
<td class="doxyParamItemDescription"><p>Holds the resulting path name.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>True if the appropriate path was determined, it need not exist.</p></dd>
</dl>


<p>Definition at line 436 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/path-h">Path.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/path-h">Path.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/support/path-cpp">Path.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>

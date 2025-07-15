---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/json/ostream
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `OStream` Class Reference

<p><a href="/web-llvm/docs/api/classes/llvm/json/ostream">json::OStream</a> allows writing well-formed JSON without materializing all structures as <a href="/web-llvm/docs/api/classes/llvm/json/value">json::Value</a> ahead of time. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::json::OStream { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/json-h">llvm/Support/JSON.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae5c537c76bd3b93f03bf4bbbbc489280">Block</a> = <a href="/web-llvm/docs/api/classes/llvm/function-ref">llvm::function_ref</a>&lt; void()&gt;</td>
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

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">Context { <a href="#ae4b2f9a526f86b52da896e665428cfce">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2601b35821c232bc7f2e68f7db52fdbb">OStream</a> (llvm::raw_ostream &amp;OS, unsigned IndentSize=0)</td>
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

## Public Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae9b7de561c6d433f9123cbed7b3380da">~OStream</a> ()</td>
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

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4d07484a9d134e2f4e50f22039fdc5b0">flush</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Flushes the underlying ostream. <a href="/web-llvm/docs/api/classes/llvm/json/ostream">OStream</a> does not buffer internally. <a href="#a4d07484a9d134e2f4e50f22039fdc5b0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad132dccf457f071b5854a8c94135e7c2">value</a> (const Value &amp;V)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit a self-contained value (number, string, vector&lt;string&gt; etc). <a href="#ad132dccf457f071b5854a8c94135e7c2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a91056cd37dda55d4b00d69b6361641e4">array</a> (Block Contents)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit an array whose elements are emitted in the provided <a href="#ae5c537c76bd3b93f03bf4bbbbc489280">Block</a>. <a href="#a91056cd37dda55d4b00d69b6361641e4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a06d556674c46c15e5906f2f645f4fbe5">object</a> (Block Contents)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit an object whose elements are emitted in the provided <a href="#ae5c537c76bd3b93f03bf4bbbbc489280">Block</a>. <a href="#a06d556674c46c15e5906f2f645f4fbe5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a08ce52de11e54269aeba894fcb72bb7a">rawValue</a> (llvm::function_ref&lt; void(raw_ostream &amp;)&gt; Contents)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit an externally-serialized value. <a href="#a08ce52de11e54269aeba894fcb72bb7a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe988728690935fad7313244c2f4a772">rawValue</a> (llvm::StringRef Contents)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8d6140131d6891e8ca8c134b889b8ec8">comment</a> (llvm::StringRef)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit a JavaScript comment associated with the next printed value. <a href="#a8d6140131d6891e8ca8c134b889b8ec8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4754bca88e59468dba45df18b849920a">attribute</a> (llvm::StringRef Key, const Value &amp;Contents)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit an attribute whose value is self-contained (number, vector&lt;int&gt; etc). <a href="#a4754bca88e59468dba45df18b849920a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ff67320cc541a438d8fc170124af74f">attributeArray</a> (llvm::StringRef Key, Block Contents)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit an attribute whose value is an array with elements from the <a href="#ae5c537c76bd3b93f03bf4bbbbc489280">Block</a>. <a href="#a7ff67320cc541a438d8fc170124af74f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0e888ce91e1087ca58869357b718fd38">attributeObject</a> (llvm::StringRef Key, Block Contents)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit an attribute whose value is an object with attributes from the <a href="#ae5c537c76bd3b93f03bf4bbbbc489280">Block</a>. <a href="#a0e888ce91e1087ca58869357b718fd38">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5741cf7e48bbab22369fa2aa8c9e151f">arrayBegin</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa4ef0d3ce12400b17d9f9a5cd028a211">arrayEnd</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f20bfc936e2aaf698df6de5b3a0c397">objectBegin</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af9928f1fc2112c92546d8e31ced97033">objectEnd</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a39613bf6aa1a8059a4dd25d57c7fd1e5">attributeBegin</a> (llvm::StringRef Key)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aacce5798acdb34154adce0318fdfdaf8">attributeEnd</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a792749e73c83a275ccff99e769c64569">rawValueBegin</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad3381dc4020a5d5353451a2348e3ec24">rawValueEnd</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac2218cffea84ee2b2ae4a43110007039">attributeImpl</a> (llvm::StringRef Key, Block Contents)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a45304e4252c69789af45c95e7f12ce0f">valueBegin</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af1e16a477be6820f1946bcd40a62a2ed">flushComment</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a31470c2c8a2c1073d844aec2c10802ba">newline</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">llvm::SmallVector</a>&lt; State, 16 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a404b8fd2af15380167c133d4cb87c285">Stack</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">llvm::StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad5b9e5ede5b59ce11a9e7fab5bec8cad">PendingComment</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/raw-ostream">llvm::raw_ostream</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af15c422eb2d5b0f5db9c555ee5c1465e">OS</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e2a6e8553a2600bf63521c30287f697">IndentSize</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a643f54799425b5182abe0ca5b8ebd4ae">Indent</a> = 0</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/json/ostream">json::OStream</a> allows writing well-formed JSON without materializing all structures as <a href="/web-llvm/docs/api/classes/llvm/json/value">json::Value</a> ahead of time.</p>


<p>It's faster, lower-level, and less safe than OS &lt;&lt; <a href="/web-llvm/docs/api/classes/llvm/json/value">json::Value</a>. It also allows emitting more constructs, such as comments.</p>


<p>Only one "top-level" object can be written to a stream. Simplest usage involves passing lambdas (Blocks) to fill in containers:</p>


<p><a href="/web-llvm/docs/api/classes/llvm/json/ostream">json::OStream</a> J(OS); J.array([&amp;]{ for (const Event &amp;E : Events) J.object([&amp;] { J.attribute("timestamp", int64_t(E.Time)); J.attributeArray("participants", [&amp;] { for (const Participant &amp;P : E.Participants) J.value(P.toString()); }); }); });</p>


<p>This would produce JSON like:</p>


<p>[ { "timestamp": 19287398741, "participants": [ "King Kong", "Miley Cyrus", "Cleopatra" ] }, ... ]</p>


<p>The lower level begin/end methods (<a href="#a5741cf7e48bbab22369fa2aa8c9e151f">arrayBegin()</a>) are more flexible but care must be taken to pair them correctly:</p>


<p><a href="/web-llvm/docs/api/classes/llvm/json/ostream">json::OStream</a> J(OS); for (const Event &amp;E : Events) { J.objectBegin(); J.attribute("timestamp", int64_t(E.Time)); J.attributeBegin("participants"); for (const Participant &amp;P : E.Participants) J.value(P.toString()); J.attributeEnd(); J.objectEnd(); } J.arrayEnd();</p>


<p>If the call sequence isn't valid JSON, asserts will fire in debug mode. This can be mismatched begin()/end() pairs, trying to emit attributes inside an array, and so on. With asserts disabled, this is undefined behavior.</p>


<p>Definition at line 979 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/json-h">JSON.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### Block {#ae5c537c76bd3b93f03bf4bbbbc489280}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::json::OStream::Block =  llvm::function_ref&lt;void()&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 981 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/json-h">JSON.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Enumerations

### Context {#ae4b2f9a526f86b52da896e665428cfce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::json::OStream::Context </td>
</tr>
</table>
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
<td class="doxyEnumItemName">Singleton<a id="ae4b2f9a526f86b52da896e665428cfcea2054207610f595ba37117d0fd0aa0180"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Array<a id="ae4b2f9a526f86b52da896e665428cfceadc83d9c006f81d88f05548518e8c43f1"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Object<a id="ae4b2f9a526f86b52da896e665428cfcea929cdb9ce3e4853e0c930ef11978c7ec"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RawValue<a id="ae4b2f9a526f86b52da896e665428cfcea49425f005062878dbc6dfc7226b907fa"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 1069 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/json-h">JSON.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### OStream() {#a2601b35821c232bc7f2e68f7db52fdbb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::json::OStream::OStream (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">llvm::raw_ostream</a> &amp; OS, unsigned IndentSize=0)</td>
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



<p>Definition at line 983 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/json-h">JSON.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~OStream() {#ae9b7de561c6d433f9123cbed7b3380da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::json::OStream::~OStream ()</td>
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



<p>Definition at line 987 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/json-h">JSON.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### array() {#a91056cd37dda55d4b00d69b6361641e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::json::OStream::array (<a href="#ae5c537c76bd3b93f03bf4bbbbc489280">Block</a> Contents)</td>
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

<p>Emit an array whose elements are emitted in the provided <a href="#ae5c537c76bd3b93f03bf4bbbbc489280">Block</a>.</p>

<p>Definition at line 1003 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/json-h">JSON.h</a>.</p>


<p>References <a href="#a5741cf7e48bbab22369fa2aa8c9e151f">arrayBegin</a> and <a href="#aa4ef0d3ce12400b17d9f9a5cd028a211">arrayEnd</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/json/#a0cff3f49083a4dfc91368979f818f297">llvm::json::abbreviateChildren</a>, <a href="#a7ff67320cc541a438d8fc170124af74f">attributeArray</a>, <a href="/web-llvm/docs/api/classes/llvm/json/path/root/#a064c6a4f075f7dbdbdc16e791de1168a">llvm::json::Path::Root::printErrorContext</a> and <a href="#ad132dccf457f071b5854a8c94135e7c2">value</a>.</p>

</div>
</div>

### arrayBegin() {#a5741cf7e48bbab22369fa2aa8c9e151f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::json::OStream::arrayBegin ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1049 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/json-h">JSON.h</a>, definition at line 840 of file <a href="/web-llvm/docs/api/files/lib/lib/support/json-cpp">JSON.cpp</a>.</p>


<p>Referenced by <a href="#a91056cd37dda55d4b00d69b6361641e4">array</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereader/#ad1a3cf9f9ad94831f204a4654a423906">llvm::sampleprof::SampleProfileReader::dumpJson</a> and <a href="/web-llvm/docs/api/structs/llvm/timetraceprofiler/#a0a693558700fd7f79d6ba0313d9139f9">llvm::TimeTraceProfiler::write</a>.</p>

</div>
</div>

### arrayEnd() {#aa4ef0d3ce12400b17d9f9a5cd028a211}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::json::OStream::arrayEnd ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1050 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/json-h">JSON.h</a>, definition at line 848 of file <a href="/web-llvm/docs/api/files/lib/lib/support/json-cpp">JSON.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>


<p>Referenced by <a href="#a91056cd37dda55d4b00d69b6361641e4">array</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereader/#ad1a3cf9f9ad94831f204a4654a423906">llvm::sampleprof::SampleProfileReader::dumpJson</a> and <a href="/web-llvm/docs/api/structs/llvm/timetraceprofiler/#a0a693558700fd7f79d6ba0313d9139f9">llvm::TimeTraceProfiler::write</a>.</p>

</div>
</div>

### attribute() {#a4754bca88e59468dba45df18b849920a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::json::OStream::attribute (<a href="/web-llvm/docs/api/classes/llvm/stringref">llvm::StringRef</a> Key, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/json/value">Value</a> &amp; Contents)</td>
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

<p>Emit an attribute whose value is self-contained (number, vector&lt;int&gt; etc).</p>

<p>Definition at line 1034 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/json-h">JSON.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a98c6256d0644613c6b5b3e2ef06ef5ce">llvm::InnerAnalysisManagerProxy&lt; AnalysisManagerT, IRUnitT, ExtraArgTs... &gt;::Key</a> and <a href="#ad132dccf457f071b5854a8c94135e7c2">value</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/profiledata/sampleprofreader-cpp/#a3f66983ff782c5a6bc67a19058c7ea6b">dumpFunctionProfileJson</a>, <a href="/web-llvm/docs/api/classes/llvm/logger/#a6ca977785c8d33e0e44f0b25d3756f74">llvm::Logger::startObservation</a>, <a href="/web-llvm/docs/api/classes/llvm/logger/#a9be20507499a9a17d9e77ce1ba2cf330">llvm::Logger::switchContext</a>, <a href="/web-llvm/docs/api/classes/llvm/tensorspec/#af36eb781aacdcc18a3199433080245bb">llvm::TensorSpec::toJSON</a>, <a href="#ad132dccf457f071b5854a8c94135e7c2">value</a> and <a href="/web-llvm/docs/api/structs/llvm/timetraceprofiler/#a0a693558700fd7f79d6ba0313d9139f9">llvm::TimeTraceProfiler::write</a>.</p>

</div>
</div>

### attributeArray() {#a7ff67320cc541a438d8fc170124af74f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::json::OStream::attributeArray (<a href="/web-llvm/docs/api/classes/llvm/stringref">llvm::StringRef</a> Key, <a href="#ae5c537c76bd3b93f03bf4bbbbc489280">Block</a> Contents)</td>
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

<p>Emit an attribute whose value is an array with elements from the <a href="#ae5c537c76bd3b93f03bf4bbbbc489280">Block</a>.</p>

<p>Definition at line 1038 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/json-h">JSON.h</a>.</p>


<p>References <a href="#a91056cd37dda55d4b00d69b6361641e4">array</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a98c6256d0644613c6b5b3e2ef06ef5ce">llvm::InnerAnalysisManagerProxy&lt; AnalysisManagerT, IRUnitT, ExtraArgTs... &gt;::Key</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/profiledata/sampleprofreader-cpp/#a3f66983ff782c5a6bc67a19058c7ea6b">dumpFunctionProfileJson</a> and <a href="/web-llvm/docs/api/classes/llvm/tensorspec/#af36eb781aacdcc18a3199433080245bb">llvm::TensorSpec::toJSON</a>.</p>

</div>
</div>

### attributeBegin() {#a39613bf6aa1a8059a4dd25d57c7fd1e5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::json::OStream::attributeBegin (<a href="/web-llvm/docs/api/classes/llvm/stringref">llvm::StringRef</a> Key)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1053 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/json-h">JSON.h</a>, definition at line 878 of file <a href="/web-llvm/docs/api/files/lib/lib/support/json-cpp">JSON.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/json/#ab64ede9b347ffd8eb32ed5e05f2520f4">llvm::json::fixUTF8</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a98c6256d0644613c6b5b3e2ef06ef5ce">llvm::InnerAnalysisManagerProxy&lt; AnalysisManagerT, IRUnitT, ExtraArgTs... &gt;::Key</a>, <a href="/web-llvm/docs/api/namespaces/llvm/json/#a385765e73480a0f2d49dcc84a8fb70da">llvm::json::isUTF8</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#ae5b35beb6f127e5f47269e9124b886fb">LLVM_LIKELY</a> and <a href="/web-llvm/docs/api/namespaces/llvm/json/#a5e191005830159035ac7f4e4a0d51b4d">llvm::json::quote</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/json/#a0cff3f49083a4dfc91368979f818f297">llvm::json::abbreviateChildren</a>, <a href="/web-llvm/docs/api/classes/llvm/json/path/root/#a064c6a4f075f7dbdbdc16e791de1168a">llvm::json::Path::Root::printErrorContext</a> and <a href="/web-llvm/docs/api/structs/llvm/timetraceprofiler/#a0a693558700fd7f79d6ba0313d9139f9">llvm::TimeTraceProfiler::write</a>.</p>

</div>
</div>

### attributeEnd() {#aacce5798acdb34154adce0318fdfdaf8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::json::OStream::attributeEnd ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1054 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/json-h">JSON.h</a>, definition at line 898 of file <a href="/web-llvm/docs/api/files/lib/lib/support/json-cpp">JSON.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/json/#a0cff3f49083a4dfc91368979f818f297">llvm::json::abbreviateChildren</a>, <a href="/web-llvm/docs/api/classes/llvm/json/path/root/#a064c6a4f075f7dbdbdc16e791de1168a">llvm::json::Path::Root::printErrorContext</a> and <a href="/web-llvm/docs/api/structs/llvm/timetraceprofiler/#a0a693558700fd7f79d6ba0313d9139f9">llvm::TimeTraceProfiler::write</a>.</p>

</div>
</div>

### attributeObject() {#a0e888ce91e1087ca58869357b718fd38}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::json::OStream::attributeObject (<a href="/web-llvm/docs/api/classes/llvm/stringref">llvm::StringRef</a> Key, <a href="#ae5c537c76bd3b93f03bf4bbbbc489280">Block</a> Contents)</td>
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

<p>Emit an attribute whose value is an object with attributes from the <a href="#ae5c537c76bd3b93f03bf4bbbbc489280">Block</a>.</p>

<p>Definition at line 1042 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/json-h">JSON.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a98c6256d0644613c6b5b3e2ef06ef5ce">llvm::InnerAnalysisManagerProxy&lt; AnalysisManagerT, IRUnitT, ExtraArgTs... &gt;::Key</a> and <a href="#a06d556674c46c15e5906f2f645f4fbe5">object</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/timetraceprofiler/#a0a693558700fd7f79d6ba0313d9139f9">llvm::TimeTraceProfiler::write</a>.</p>

</div>
</div>

### comment() {#a8d6140131d6891e8ca8c134b889b8ec8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::json::OStream::comment (<a href="/web-llvm/docs/api/classes/llvm/stringref">llvm::StringRef</a> Comment)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit a JavaScript comment associated with the next printed value.</p>


<p>The string must be valid until the next attribute or value is emitted. Comments are not part of standard JSON, and many parsers reject them!</p>


<p>Declaration at line 1028 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/json-h">JSON.h</a>, definition at line 803 of file <a href="/web-llvm/docs/api/files/lib/lib/support/json-cpp">JSON.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/json/path/root/#a064c6a4f075f7dbdbdc16e791de1168a">llvm::json::Path::Root::printErrorContext</a>.</p>

</div>
</div>

### flush() {#a4d07484a9d134e2f4e50f22039fdc5b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::json::OStream::flush ()</td>
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

<p>Flushes the underlying ostream. <a href="/web-llvm/docs/api/classes/llvm/json/ostream">OStream</a> does not buffer internally.</p>

<p>Definition at line 994 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/json-h">JSON.h</a>.</p>

</div>
</div>

### object() {#a06d556674c46c15e5906f2f645f4fbe5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::json::OStream::object (<a href="#ae5c537c76bd3b93f03bf4bbbbc489280">Block</a> Contents)</td>
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

<p>Emit an object whose elements are emitted in the provided <a href="#ae5c537c76bd3b93f03bf4bbbbc489280">Block</a>.</p>

<p>Definition at line 1009 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/json-h">JSON.h</a>.</p>


<p>References <a href="#a5f20bfc936e2aaf698df6de5b3a0c397">objectBegin</a> and <a href="#af9928f1fc2112c92546d8e31ced97033">objectEnd</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/json/#a0cff3f49083a4dfc91368979f818f297">llvm::json::abbreviateChildren</a>, <a href="#a0e888ce91e1087ca58869357b718fd38">attributeObject</a>, <a href="/web-llvm/docs/api/files/lib/lib/profiledata/sampleprofreader-cpp/#a3f66983ff782c5a6bc67a19058c7ea6b">dumpFunctionProfileJson</a>, <a href="/web-llvm/docs/api/classes/llvm/json/path/root/#a064c6a4f075f7dbdbdc16e791de1168a">llvm::json::Path::Root::printErrorContext</a>, <a href="/web-llvm/docs/api/classes/llvm/logger/#a6ca977785c8d33e0e44f0b25d3756f74">llvm::Logger::startObservation</a>, <a href="/web-llvm/docs/api/classes/llvm/logger/#a9be20507499a9a17d9e77ce1ba2cf330">llvm::Logger::switchContext</a>, <a href="/web-llvm/docs/api/classes/llvm/tensorspec/#af36eb781aacdcc18a3199433080245bb">llvm::TensorSpec::toJSON</a>, <a href="#ad132dccf457f071b5854a8c94135e7c2">value</a> and <a href="/web-llvm/docs/api/structs/llvm/timetraceprofiler/#a0a693558700fd7f79d6ba0313d9139f9">llvm::TimeTraceProfiler::write</a>.</p>

</div>
</div>

### objectBegin() {#a5f20bfc936e2aaf698df6de5b3a0c397}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::json::OStream::objectBegin ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1051 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/json-h">JSON.h</a>, definition at line 859 of file <a href="/web-llvm/docs/api/files/lib/lib/support/json-cpp">JSON.cpp</a>.</p>


<p>Referenced by <a href="#a06d556674c46c15e5906f2f645f4fbe5">object</a> and <a href="/web-llvm/docs/api/structs/llvm/timetraceprofiler/#a0a693558700fd7f79d6ba0313d9139f9">llvm::TimeTraceProfiler::write</a>.</p>

</div>
</div>

### objectEnd() {#af9928f1fc2112c92546d8e31ced97033}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::json::OStream::objectEnd ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1052 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/json-h">JSON.h</a>, definition at line 867 of file <a href="/web-llvm/docs/api/files/lib/lib/support/json-cpp">JSON.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>


<p>Referenced by <a href="#a06d556674c46c15e5906f2f645f4fbe5">object</a> and <a href="/web-llvm/docs/api/structs/llvm/timetraceprofiler/#a0a693558700fd7f79d6ba0313d9139f9">llvm::TimeTraceProfiler::write</a>.</p>

</div>
</div>

### rawValue() {#a08ce52de11e54269aeba894fcb72bb7a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::json::OStream::rawValue (<a href="/web-llvm/docs/api/classes/llvm/function-ref">llvm::function_ref</a>&lt; void(<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp;)&gt; Contents)</td>
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

<p>Emit an externally-serialized value.</p>


<p>The caller must write exactly one valid JSON value to the provided stream. No validation or formatting of this value occurs.</p>


<p>Definition at line 1017 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/json-h">JSON.h</a>.</p>


<p>References <a href="#a792749e73c83a275ccff99e769c64569">rawValueBegin</a> and <a href="#ad3381dc4020a5d5353451a2348e3ec24">rawValueEnd</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/json/#a3251137d4e13982c711221d45fff9a09">llvm::json::abbreviate</a> and <a href="#abe988728690935fad7313244c2f4a772">rawValue</a>.</p>

</div>
</div>

### rawValue() {#abe988728690935fad7313244c2f4a772}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::json::OStream::rawValue (<a href="/web-llvm/docs/api/classes/llvm/stringref">llvm::StringRef</a> Contents)</td>
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



<p>Definition at line 1022 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/json-h">JSON.h</a>.</p>


<p>Reference <a href="#a08ce52de11e54269aeba894fcb72bb7a">rawValue</a>.</p>

</div>
</div>

### rawValueBegin() {#a792749e73c83a275ccff99e769c64569}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">raw_ostream &amp; llvm::json::OStream::rawValueBegin ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1055 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/json-h">JSON.h</a>, definition at line 906 of file <a href="/web-llvm/docs/api/files/lib/lib/support/json-cpp">JSON.cpp</a>.</p>


<p>Referenced by <a href="#a08ce52de11e54269aeba894fcb72bb7a">rawValue</a>.</p>

</div>
</div>

### rawValueEnd() {#ad3381dc4020a5d5353451a2348e3ec24}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::json::OStream::rawValueEnd ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1056 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/json-h">JSON.h</a>, definition at line 913 of file <a href="/web-llvm/docs/api/files/lib/lib/support/json-cpp">JSON.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>


<p>Referenced by <a href="#a08ce52de11e54269aeba894fcb72bb7a">rawValue</a>.</p>

</div>
</div>

### value() {#ad132dccf457f071b5854a8c94135e7c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::json::OStream::value (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/json/value">Value</a> &amp; V)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit a self-contained value (number, string, vector&lt;string&gt; etc).</p>

<p>Declaration at line 1001 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/json-h">JSON.h</a>, definition at line 754 of file <a href="/web-llvm/docs/api/files/lib/lib/support/json-cpp">JSON.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/json/value/#ae5050cd67e450419cf638e2a09bf11c9">llvm::json::Value::Array</a>, <a href="#a91056cd37dda55d4b00d69b6361641e4">array</a>, <a href="#a4754bca88e59468dba45df18b849920a">attribute</a>, <a href="/web-llvm/docs/api/classes/llvm/json/value/#ad10d8b22abefa6faed2bdc37463da8b5a0185c7ad51f75621f32a6ed346d4a56a">llvm::json::Value::Boolean</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a939bc2108d47080767f0c06ba56caec7">llvm::format</a>, <a href="/web-llvm/docs/api/classes/llvm/json/value/#ad10d8b22abefa6faed2bdc37463da8b5aea36c73e7e63de0c6fef578490a4e449">llvm::json::Value::Null</a>, <a href="/web-llvm/docs/api/classes/llvm/json/value/#ad10d8b22abefa6faed2bdc37463da8b5ad22dcab1996d111071600507eff3fbfc">llvm::json::Value::Number</a>, <a href="/web-llvm/docs/api/classes/llvm/json/value/#a0720b5f434e636e22a3ed34f847eec57">llvm::json::Value::Object</a>, <a href="#a06d556674c46c15e5906f2f645f4fbe5">object</a>, <a href="/web-llvm/docs/api/namespaces/llvm/json/#a5e191005830159035ac7f4e4a0d51b4d">llvm::json::quote</a>, <a href="/web-llvm/docs/api/namespaces/llvm/json/#a4821bec148e6c1fb582ae15d760d116c">llvm::json::sortedElements</a>, <a href="/web-llvm/docs/api/classes/llvm/json/value/#ad10d8b22abefa6faed2bdc37463da8b5a5ce030d664a66bc0d280f1231ff2cc5b">llvm::json::Value::String</a> and <a href="#ad132dccf457f071b5854a8c94135e7c2">value</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/json/#a3251137d4e13982c711221d45fff9a09">llvm::json::abbreviate</a>, <a href="/web-llvm/docs/api/namespaces/llvm/json/#a0cff3f49083a4dfc91368979f818f297">llvm::json::abbreviateChildren</a>, <a href="#a4754bca88e59468dba45df18b849920a">attribute</a>, <a href="/web-llvm/docs/api/structs/llvm/format-provider-df0cd734ece492f0149be4ce4c8d5fd4/#a190aff78bb7ee7618b561151f06dd5cd">llvm::format_provider&lt; llvm::json::Value &gt;::format</a>, <a href="/web-llvm/docs/api/namespaces/llvm/json/#a5ac7cb89caebd966eb95a5cf81142409">llvm::json::operator&lt;&lt;</a>, <a href="/web-llvm/docs/api/classes/llvm/tensorspec/#af36eb781aacdcc18a3199433080245bb">llvm::TensorSpec::toJSON</a> and <a href="#ad132dccf457f071b5854a8c94135e7c2">value</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### attributeImpl() {#ac2218cffea84ee2b2ae4a43110007039}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::json::OStream::attributeImpl (<a href="/web-llvm/docs/api/classes/llvm/stringref">llvm::StringRef</a> Key, <a href="#ae5c537c76bd3b93f03bf4bbbbc489280">Block</a> Contents)</td>
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



<p>Definition at line 1059 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/json-h">JSON.h</a>.</p>

</div>
</div>

### flushComment() {#af1e16a477be6820f1946bcd40a62a2ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::json::OStream::flushComment ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1066 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/json-h">JSON.h</a>, definition at line 808 of file <a href="/web-llvm/docs/api/files/lib/lib/support/json-cpp">JSON.cpp</a>.</p>

</div>
</div>

### newline() {#a31470c2c8a2c1073d844aec2c10802ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::json::OStream::newline ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1067 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/json-h">JSON.h</a>, definition at line 833 of file <a href="/web-llvm/docs/api/files/lib/lib/support/json-cpp">JSON.cpp</a>.</p>

</div>
</div>

### valueBegin() {#a45304e4252c69789af45c95e7f12ce0f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::json::OStream::valueBegin ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1065 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/json-h">JSON.h</a>, definition at line 791 of file <a href="/web-llvm/docs/api/files/lib/lib/support/json-cpp">JSON.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Indent {#a643f54799425b5182abe0ca5b8ebd4ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::json::OStream::Indent = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1083 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/json-h">JSON.h</a>.</p>

</div>
</div>

### IndentSize {#a2e2a6e8553a2600bf63521c30287f697}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::json::OStream::IndentSize</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1082 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/json-h">JSON.h</a>.</p>

</div>
</div>

### OS {#af15c422eb2d5b0f5db9c555ee5c1465e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::raw_ostream&amp; llvm::json::OStream::OS</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1081 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/json-h">JSON.h</a>.</p>

</div>
</div>

### PendingComment {#ad5b9e5ede5b59ce11a9e7fab5bec8cad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::StringRef llvm::json::OStream::PendingComment</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1080 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/json-h">JSON.h</a>.</p>

</div>
</div>

### Stack {#a404b8fd2af15380167c133d4cb87c285}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::SmallVector&lt;State, 16&gt; llvm::json::OStream::Stack</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1079 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/json-h">JSON.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/json-h">JSON.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/support/json-cpp">JSON.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>

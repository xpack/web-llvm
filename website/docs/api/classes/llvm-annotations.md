---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/annotations
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `Annotations` Class

<p><a href="/web-llvm/docs/api/classes/llvm/annotations">Annotations</a> lets you mark points and ranges inside source code, for tests: <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::Annotations { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/testing/include/llvm/testing/annotations/annotations-h">llvm/Testing/Annotations/Annotations.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0ac05d465c3984a3a3fe146902cf3759">Annotations</a> (llvm::StringRef Text)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parses the annotations from Text. Crashes if it's malformed. <a href="#a0ac05d465c3984a3a3fe146902cf3759">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">llvm::StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af1328f94ed0737dc650cb35b50b4c850">code</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The input text with all annotations stripped. <a href="#af1328f94ed0737dc650cb35b50b4c850">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a42b915e89f7fd192619acba583ca3852">point</a> (llvm::StringRef Name="") const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the position of the point marked by ^ (or $name^) in the text. <a href="#a42b915e89f7fd192619acba583ca3852">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::pair&lt; size_t, <a href="/web-llvm/docs/api/classes/llvm/stringref">llvm::StringRef</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a485a64dfa1a7552e15848e40cf73e9ab">pointWithPayload</a> (llvm::StringRef Name="") const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the position of the point with <span class="doxyComputerOutput">Name</span> and its payload (if any). <a href="#a485a64dfa1a7552e15848e40cf73e9ab">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; size_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab1335a2c7dcf591c0105a3cfca7f175a">points</a> (llvm::StringRef Name="") const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the position of all points marked by ^ (or $name^) in the text. <a href="#ab1335a2c7dcf591c0105a3cfca7f175a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; std::pair&lt; size_t, <a href="/web-llvm/docs/api/classes/llvm/stringref">llvm::StringRef</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0ea3e0653753ce329def33d16faaf4d8">pointsWithPayload</a> (llvm::StringRef Name="") const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the positions and payloads (if any) of all points named <span class="doxyComputerOutput">Name</span>. <a href="#a0ea3e0653753ce329def33d16faaf4d8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringmap">llvm::StringMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/smallvector">llvm::SmallVector</a>&lt; size_t, 1 &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a590f64db035dd168d54db413db5c8d4d">all_points</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the mapping of all names of points marked in the text to their position. <a href="#a590f64db035dd168d54db413db5c8d4d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/annotations/range">Range</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a166ba4b3d7ad48c9d15b73f375d258f9">range</a> (llvm::StringRef Name="") const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the location of the range marked by [[ ]] (or $name[[ ]]). <a href="#a166ba4b3d7ad48c9d15b73f375d258f9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::pair&lt; <a href="/web-llvm/docs/api/structs/llvm/annotations/range">Range</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref">llvm::StringRef</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8c95845d9f1a25591c241754c276c6b1">rangeWithPayload</a> (llvm::StringRef Name="") const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the location and payload of the range marked by [[ ]] (or $name(payload)[[ ]]). <a href="#a8c95845d9f1a25591c241754c276c6b1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/annotations/range">Range</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8d08fb0ae76344ab542c85fbffc171a2">ranges</a> (llvm::StringRef Name="") const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the location of all ranges marked by [[ ]] (or $name[[ ]]). <a href="#a8d08fb0ae76344ab542c85fbffc171a2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; std::pair&lt; <a href="/web-llvm/docs/api/structs/llvm/annotations/range">Range</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref">llvm::StringRef</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a2018d860f9aaf21ad7e92def28aba9">rangesWithPayload</a> (llvm::StringRef Name="") const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the location of all ranges marked by [[ ]] (or $name(payload)[[ ]]). <a href="#a9a2018d860f9aaf21ad7e92def28aba9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringmap">llvm::StringMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/smallvector">llvm::SmallVector</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/annotations/range">Range</a>, 1 &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9dade19ba5252869f09cd1fa3d4a84fa">all_ranges</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the mapping of all names of ranges marked in the text to their location. <a href="#a9dade19ba5252869f09cd1fa3d4a84fa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab253b4b683175b4053ebf256733d1ff5">Code</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; Annotation &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0291b15c27a52e9ed08a4e5f800e70a7">All</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringmap">llvm::StringMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/smallvector">llvm::SmallVector</a>&lt; size_t, 1 &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a46a409c1416ca44be91f4458292e2cbe">Points</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringmap">llvm::StringMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/smallvector">llvm::SmallVector</a>&lt; size_t, 1 &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa7a6f54aac95a440fa3260494ae3b67e">Ranges</a></td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/annotations">Annotations</a> lets you mark points and ranges inside source code, for tests:</p>


<p><a href="/web-llvm/docs/api/classes/llvm/annotations">Annotations</a> Example(R"cpp(
      int complete() { x.pri^ }         // ^ indicates a point
      void err() { [["hello" == 42]]; } // [[this is a range]]
      $definition^class Foo{};          // points can be named: "definition"
      $(foo)^class Foo{};               // ...or have a payload: "foo"
      $definition(foo)^class Foo{};     // ...or both
      $fail(runtime)[[assert(false)]]   // ranges can have names/payloads too
   )cpp");</p>


<p><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Code = Example.code(); // annotations stripped. std::vector&lt;size_t&gt; PP = Example.points(); // all unnamed points size_t P = Example.point(); // there must be exactly one llvm::Range R = Example.range("fail"); // find named ranges</p>


<p>Points/ranges are coordinated into <span class="doxyComputerOutput"><a href="#af1328f94ed0737dc650cb35b50b4c850">code()</a></span> which is stripped of annotations.</p>


<p>Names consist of only alphanumeric characters or '_'. Payloads can contain any character expect '(' and ')'.</p>


<p>Ranges may be nested (and points can be inside ranges), but there's no way to define general overlapping ranges.</p>


<p>FIXME: the choice of the marking syntax makes it impossible to represent some of the C++ and Objective C constructs (including common ones like C++ attributes). We can fix this by:</p>


<ol class="doxyList" type="1">
<li>introducing an escaping mechanism for the special characters,</li>
<li>making characters for marking points and ranges configurable,</li>
<li>changing the syntax to something less commonly used,</li>
<li>...</li>
</ol>

<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/testing/include/llvm/testing/annotations/annotations-h">Annotations.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### Annotations() {#a0ac05d465c3984a3a3fe146902cf3759}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Annotations::Annotations (<a href="/web-llvm/docs/api/classes/llvm/stringref">llvm::StringRef</a> Text)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Parses the annotations from Text. Crashes if it's malformed.</p>

<p>Declaration at line 68 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/testing/include/llvm/testing/annotations/annotations-h">Annotations.h</a>, definition at line 26 of file <a href="/web-llvm/docs/api/files/lib/lib/testing/lib/testing/annotations/annotations-cpp">Annotations.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#acd9e771a3296c6b24146955754620557">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::back</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#ad97688dfe9cd802e2a0691cbe620218a">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::pop_back</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/files/lib/lib/testing/lib/testing/annotations/annotations-cpp/#a6bc1d3d16b23b6d89409993bd75f495d">require</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a499ea32ca1b8d16cedfe01d1e5b08f29">llvm::SmallVectorImpl&lt; T &gt;::reserve</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### all\_points() {#a590f64db035dd168d54db413db5c8d4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::StringMap&lt; llvm::SmallVector&lt; size_t, 1 &gt; &gt; Annotations::all_points ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the mapping of all names of points marked in the text to their position.</p>


<p>Unnamed points are mapped to the empty string. The positions are sorted. FIXME Remove this and expose <span class="doxyComputerOutput">All</span> directly (currently used out-of-tree)</p>


<p>Declaration at line 90 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/testing/include/llvm/testing/annotations/annotations-h">Annotations.h</a>, definition at line 119 of file <a href="/web-llvm/docs/api/files/lib/lib/testing/lib/testing/annotations/annotations-cpp">Annotations.cpp</a>.</p>


<p>Reference <a href="#ab1335a2c7dcf591c0105a3cfca7f175a">points</a>.</p>

</div>
</div>

### all\_ranges() {#a9dade19ba5252869f09cd1fa3d4a84fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::StringMap&lt; llvm::SmallVector&lt; Annotations::Range, 1 &gt; &gt; Annotations::all_ranges ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the mapping of all names of ranges marked in the text to their location.</p>


<p>Unnamed ranges are mapped to the empty string. The ranges are sorted by their start position.</p>


<p>Declaration at line 110 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/testing/include/llvm/testing/annotations/annotations-h">Annotations.h</a>, definition at line 166 of file <a href="/web-llvm/docs/api/files/lib/lib/testing/lib/testing/annotations/annotations-cpp">Annotations.cpp</a>.</p>


<p>Reference <a href="#a8d08fb0ae76344ab542c85fbffc171a2">ranges</a>.</p>

</div>
</div>

### code() {#af1328f94ed0737dc650cb35b50b4c850}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::StringRef llvm::Annotations::code ()</td>
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

<p>The input text with all annotations stripped.</p>


<p>All points and ranges are relative to this stripped text.</p>


<p>Definition at line 72 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/testing/include/llvm/testing/annotations/annotations-h">Annotations.h</a>.</p>

</div>
</div>

### point() {#a42b915e89f7fd192619acba583ca3852}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t Annotations::point (<a href="/web-llvm/docs/api/classes/llvm/stringref">llvm::StringRef</a> Name="")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the position of the point marked by ^ (or $name^) in the text.</p>


<p>Crashes if there isn't exactly one.</p>


<p>Declaration at line 76 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/testing/include/llvm/testing/annotations/annotations-h">Annotations.h</a>, definition at line 83 of file <a href="/web-llvm/docs/api/files/lib/lib/testing/lib/testing/annotations/annotations-cpp">Annotations.cpp</a>.</p>


<p>Reference <a href="#a485a64dfa1a7552e15848e40cf73e9ab">pointWithPayload</a>.</p>

</div>
</div>

### points() {#ab1335a2c7dcf591c0105a3cfca7f175a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt; size_t &gt; Annotations::points (<a href="/web-llvm/docs/api/classes/llvm/stringref">llvm::StringRef</a> Name="")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the position of all points marked by ^ (or $name^) in the text.</p>


<p>Order matches the order within the text.</p>


<p>Declaration at line 82 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/testing/include/llvm/testing/annotations/annotations-h">Annotations.h</a>, definition at line 96 of file <a href="/web-llvm/docs/api/files/lib/lib/testing/lib/testing/annotations/annotations-cpp">Annotations.cpp</a>.</p>


<p>Reference <a href="#a0ea3e0653753ce329def33d16faaf4d8">pointsWithPayload</a>.</p>


<p>Referenced by <a href="#a590f64db035dd168d54db413db5c8d4d">all_points</a>.</p>

</div>
</div>

### pointsWithPayload() {#a0ea3e0653753ce329def33d16faaf4d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt; std::pair&lt; size_t, llvm::StringRef &gt; &gt; Annotations::pointsWithPayload (<a href="/web-llvm/docs/api/classes/llvm/stringref">llvm::StringRef</a> Name="")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the positions and payloads (if any) of all points named <span class="doxyComputerOutput">Name</span>.</p>

<p>Declaration at line 85 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/testing/include/llvm/testing/annotations/annotations-h">Annotations.h</a>, definition at line 106 of file <a href="/web-llvm/docs/api/files/lib/lib/testing/lib/testing/annotations/annotations-cpp">Annotations.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>


<p>Referenced by <a href="#ab1335a2c7dcf591c0105a3cfca7f175a">points</a>.</p>

</div>
</div>

### pointWithPayload() {#a485a64dfa1a7552e15848e40cf73e9ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; size_t, llvm::StringRef &gt; Annotations::pointWithPayload (<a href="/web-llvm/docs/api/classes/llvm/stringref">llvm::StringRef</a> Name="")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the position of the point with <span class="doxyComputerOutput">Name</span> and its payload (if any).</p>

<p>Declaration at line 79 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/testing/include/llvm/testing/annotations/annotations-h">Annotations.h</a>, definition at line 88 of file <a href="/web-llvm/docs/api/files/lib/lib/testing/lib/testing/annotations/annotations-cpp">Annotations.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a> and <a href="/web-llvm/docs/api/files/lib/lib/testing/lib/testing/annotations/annotations-cpp/#a6bc1d3d16b23b6d89409993bd75f495d">require</a>.</p>


<p>Referenced by <a href="#a42b915e89f7fd192619acba583ca3852">point</a>.</p>

</div>
</div>

### range() {#a166ba4b3d7ad48c9d15b73f375d258f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Annotations::Range Annotations::range (<a href="/web-llvm/docs/api/classes/llvm/stringref">llvm::StringRef</a> Name="")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the location of the range marked by [[ ]] (or $name[[ ]]).</p>


<p>Crashes if there isn't exactly one.</p>


<p>Declaration at line 94 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/testing/include/llvm/testing/annotations/annotations-h">Annotations.h</a>, definition at line 128 of file <a href="/web-llvm/docs/api/files/lib/lib/testing/lib/testing/annotations/annotations-cpp">Annotations.cpp</a>.</p>


<p>Reference <a href="#a8c95845d9f1a25591c241754c276c6b1">rangeWithPayload</a>.</p>

</div>
</div>

### ranges() {#a8d08fb0ae76344ab542c85fbffc171a2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt; Annotations::Range &gt; Annotations::ranges (<a href="/web-llvm/docs/api/classes/llvm/stringref">llvm::StringRef</a> Name="")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the location of all ranges marked by [[ ]] (or $name[[ ]]).</p>


<p>They are ordered by start position within the text.</p>


<p>Declaration at line 101 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/testing/include/llvm/testing/annotations/annotations-h">Annotations.h</a>, definition at line 142 of file <a href="/web-llvm/docs/api/files/lib/lib/testing/lib/testing/annotations/annotations-cpp">Annotations.cpp</a>.</p>


<p>Reference <a href="#a9a2018d860f9aaf21ad7e92def28aba9">rangesWithPayload</a>.</p>


<p>Referenced by <a href="#a9dade19ba5252869f09cd1fa3d4a84fa">all_ranges</a>.</p>

</div>
</div>

### rangesWithPayload() {#a9a2018d860f9aaf21ad7e92def28aba9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt; std::pair&lt; Annotations::Range, llvm::StringRef &gt; &gt; Annotations::rangesWithPayload (<a href="/web-llvm/docs/api/classes/llvm/stringref">llvm::StringRef</a> Name="")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the location of all ranges marked by [[ ]] (or $name(payload)[[ ]]).</p>


<p>They are ordered by start position within the text.</p>


<p>Declaration at line 106 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/testing/include/llvm/testing/annotations/annotations-h">Annotations.h</a>, definition at line 151 of file <a href="/web-llvm/docs/api/files/lib/lib/testing/lib/testing/annotations/annotations-cpp">Annotations.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>


<p>Referenced by <a href="#a8d08fb0ae76344ab542c85fbffc171a2">ranges</a>.</p>

</div>
</div>

### rangeWithPayload() {#a8c95845d9f1a25591c241754c276c6b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; Annotations::Range, llvm::StringRef &gt; Annotations::rangeWithPayload (<a href="/web-llvm/docs/api/classes/llvm/stringref">llvm::StringRef</a> Name="")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the location and payload of the range marked by [[ ]] (or $name(payload)[[ ]]).</p>


<p>Crashes if there isn't exactly one.</p>


<p>Declaration at line 98 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/testing/include/llvm/testing/annotations/annotations-h">Annotations.h</a>, definition at line 133 of file <a href="/web-llvm/docs/api/files/lib/lib/testing/lib/testing/annotations/annotations-cpp">Annotations.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/files/lib/lib/testing/lib/testing/annotations/annotations-cpp/#a6bc1d3d16b23b6d89409993bd75f495d">require</a>.</p>


<p>Referenced by <a href="#a166ba4b3d7ad48c9d15b73f375d258f9">range</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### All {#a0291b15c27a52e9ed08a4e5f800e70a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;Annotation&gt; llvm::Annotations::All</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 122 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/testing/include/llvm/testing/annotations/annotations-h">Annotations.h</a>.</p>

</div>
</div>

### Code {#ab253b4b683175b4053ebf256733d1ff5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::Annotations::Code</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 113 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/testing/include/llvm/testing/annotations/annotations-h">Annotations.h</a>.</p>

</div>
</div>

### Points {#a46a409c1416ca44be91f4458292e2cbe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::StringMap&lt;llvm::SmallVector&lt;size_t, 1&gt; &gt; llvm::Annotations::Points</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 124 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/testing/include/llvm/testing/annotations/annotations-h">Annotations.h</a>.</p>

</div>
</div>

### Ranges {#aa7a6f54aac95a440fa3260494ae3b67e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::StringMap&lt;llvm::SmallVector&lt;size_t, 1&gt; &gt; llvm::Annotations::Ranges</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 125 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/testing/include/llvm/testing/annotations/annotations-h">Annotations.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/testing/include/llvm/testing/annotations/annotations-h">Annotations.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/testing/lib/testing/annotations/annotations-cpp">Annotations.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>

---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/jitlink/aarch32/anonymous-aarch32-cpp-/thumbrelocation
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `ThumbRelocation` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct llvm::jitlink::aarch32::anonymous{aarch32.cpp}::ThumbRelocation { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab0298428d998a704d58710e2b3b7e77f">ThumbRelocation</a> (const char *FixupPtr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a read-only reference to a Thumb32 fixup. <a href="#ab0298428d998a704d58710e2b3b7e77f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3255b61f14f2a64fadabf417c7e1665c">ThumbRelocation</a> (WritableThumbRelocation &amp;Writable)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a read-only Thumb32 fixup from a writeable one. <a href="#a3255b61f14f2a64fadabf417c7e1665c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/support/#a4e29b3df92632c930b82161555c3b8d6">support::ulittle16_t</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a60521cdd6d0623d99e4607dd2f44487c">Hi</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/support/#a4e29b3df92632c930b82161555c3b8d6">support::ulittle16_t</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a092072eacfb077013d773c06057d8ecb">Lo</a></td>
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


<p>Definition at line 207 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/aarch32-cpp">aarch32.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### ThumbRelocation() {#ab0298428d998a704d58710e2b3b7e77f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::jitlink::aarch32::anonymous{aarch32.cpp}::ThumbRelocation::ThumbRelocation (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * FixupPtr)</td>
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

<p>Create a read-only reference to a Thumb32 fixup.</p>

<p>Definition at line 209 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/aarch32-cpp">aarch32.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a>, <a href="#a60521cdd6d0623d99e4607dd2f44487c">Hi</a> and <a href="#a092072eacfb077013d773c06057d8ecb">Lo</a>.</p>

</div>
</div>

### ThumbRelocation() {#a3255b61f14f2a64fadabf417c7e1665c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::jitlink::aarch32::anonymous{aarch32.cpp}::ThumbRelocation::ThumbRelocation (<a href="/web-llvm/docs/api/structs/llvm/jitlink/aarch32/anonymous-aarch32-cpp-/writablethumbrelocation">WritableThumbRelocation</a> &amp; Writable)</td>
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

<p>Create a read-only Thumb32 fixup from a writeable one.</p>

<p>Definition at line 214 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/aarch32-cpp">aarch32.cpp</a>.</p>


<p>References <a href="#a60521cdd6d0623d99e4607dd2f44487c">Hi</a> and <a href="#a092072eacfb077013d773c06057d8ecb">Lo</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Hi {#a60521cdd6d0623d99e4607dd2f44487c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const support::ulittle16_t&amp; llvm::jitlink::aarch32::anonymous{aarch32.cpp}::ThumbRelocation::Hi</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 217 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/aarch32-cpp">aarch32.cpp</a>.</p>


<p>Referenced by <a href="#ab0298428d998a704d58710e2b3b7e77f">ThumbRelocation</a> and <a href="#a3255b61f14f2a64fadabf417c7e1665c">ThumbRelocation</a>.</p>

</div>
</div>

### Lo {#a092072eacfb077013d773c06057d8ecb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const support::ulittle16_t&amp; llvm::jitlink::aarch32::anonymous{aarch32.cpp}::ThumbRelocation::Lo</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 218 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/aarch32-cpp">aarch32.cpp</a>.</p>


<p>Referenced by <a href="#ab0298428d998a704d58710e2b3b7e77f">ThumbRelocation</a> and <a href="#a3255b61f14f2a64fadabf417c7e1665c">ThumbRelocation</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/aarch32-cpp">aarch32.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>

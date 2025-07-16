---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/dynamiclibrary/handleset
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `HandleSet` Class Reference



## Declaration

<div class="doxyDeclaration">
class DynamicLibrary::HandleSet { ... }
</div>

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">std::vector&lt; void * &gt; <a href="#a5b5025e7a54d0e6b8642134dbb4d90b8">HandleList</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a777bb13433fdb558cb3817e3f4ce441c">HandleSet</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac812445033afca9d6ebe400399b4830">~HandleSet</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">HandleList::iterator</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a877c633db7115d78879906125c5a2d35">Find</a> (void *Handle)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7aae8e8aa49a578f9ee990ba6ac5c59f">Contains</a> (void *Handle)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a57e48229c8cea2a8adee11137875503f">AddLibrary</a> (void *Handle, bool IsProcess=false, bool CanClose=true, bool AllowDuplicates=false)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afdf806f09f0e9c8f46b2af3e7671008b">CloseLibrary</a> (void *Handle)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aacb1203f411484794ada2f3e9556ef63">LibLookup</a> (const char *Symbol, DynamicLibrary::SearchOrdering Order)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a69d9a9e69fed62d0f6edd6aa1eb77d95">Lookup</a> (const char *Symbol, DynamicLibrary::SearchOrdering Order)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">HandleList</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ed7e25a60280aa79aaee97e30b5f2b4">Handles</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abec4fb8aa1a9b564577c12e62fed3269">Process</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9df2a55f4a1ee34610802540457f3fab">DLOpen</a> (const char *Filename, std::string *Err)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae7a8e4c562fe12a27adea30aba533254">DLClose</a> (void *Handle)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaea4161534624cd91cd5404b6f25291c">DLSym</a> (void *Handle, const char *Symbol)</td>
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


<p>Definition at line 25 of file <a href="/web-llvm/docs/api/files/lib/lib/support/dynamiclibrary-cpp">DynamicLibrary.cpp</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### HandleList {#a5b5025e7a54d0e6b8642134dbb4d90b8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef std::vector&lt;void *&gt; llvm::sys::DynamicLibrary::HandleSet::HandleList</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 26 of file <a href="/web-llvm/docs/api/files/lib/lib/support/dynamiclibrary-cpp">DynamicLibrary.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### HandleSet() {#a777bb13433fdb558cb3817e3f4ce441c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::sys::DynamicLibrary::HandleSet::HandleSet ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/lib/lib/support/dynamiclibrary-cpp">DynamicLibrary.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~HandleSet() {#aac812445033afca9d6ebe400399b4830}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::sys::DynamicLibrary::HandleSet::~HandleSet ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/lib/lib/support/dynamiclibrary-cpp">DynamicLibrary.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### AddLibrary() {#a57e48229c8cea2a8adee11137875503f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sys::DynamicLibrary::HandleSet::AddLibrary (void * Handle, bool IsProcess=false, bool CanClose=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>, bool AllowDuplicates=false)</td>
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



<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/lib/lib/support/dynamiclibrary-cpp">DynamicLibrary.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ae7a8e4c562fe12a27adea30aba533254">llvm::sys::DynamicLibrary::HandleSet::DLClose</a>, <a href="#a877c633db7115d78879906125c5a2d35">llvm::sys::DynamicLibrary::HandleSet::Find</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#ae5b35beb6f127e5f47269e9124b886fb">LLVM_LIKELY</a>.</p>

</div>
</div>

### CloseLibrary() {#afdf806f09f0e9c8f46b2af3e7671008b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::sys::DynamicLibrary::HandleSet::CloseLibrary (void * Handle)</td>
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



<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/lib/lib/support/dynamiclibrary-cpp">DynamicLibrary.cpp</a>.</p>


<p>References <a href="#ae7a8e4c562fe12a27adea30aba533254">llvm::sys::DynamicLibrary::HandleSet::DLClose</a> and <a href="#a877c633db7115d78879906125c5a2d35">llvm::sys::DynamicLibrary::HandleSet::Find</a>.</p>

</div>
</div>

### Contains() {#a7aae8e8aa49a578f9ee990ba6ac5c59f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sys::DynamicLibrary::HandleSet::Contains (void * Handle)</td>
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



<p>Definition at line 40 of file <a href="/web-llvm/docs/api/files/lib/lib/support/dynamiclibrary-cpp">DynamicLibrary.cpp</a>.</p>


<p>Reference <a href="#a877c633db7115d78879906125c5a2d35">llvm::sys::DynamicLibrary::HandleSet::Find</a>.</p>

</div>
</div>

### Find() {#a877c633db7115d78879906125c5a2d35}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">HandleList::iterator llvm::sys::DynamicLibrary::HandleSet::Find (void * Handle)</td>
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



<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/lib/lib/support/dynamiclibrary-cpp">DynamicLibrary.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a086e9fbdb06276db7753101a08a63adf">llvm::find</a>.</p>


<p>Referenced by <a href="#a57e48229c8cea2a8adee11137875503f">llvm::sys::DynamicLibrary::HandleSet::AddLibrary</a>, <a href="#afdf806f09f0e9c8f46b2af3e7671008b">llvm::sys::DynamicLibrary::HandleSet::CloseLibrary</a> and <a href="#a7aae8e8aa49a578f9ee990ba6ac5c59f">llvm::sys::DynamicLibrary::HandleSet::Contains</a>.</p>

</div>
</div>

### LibLookup() {#aacb1203f411484794ada2f3e9556ef63}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void * llvm::sys::DynamicLibrary::HandleSet::LibLookup (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Symbol, <a href="/web-llvm/docs/api/classes/llvm/sys/dynamiclibrary/#a5e198e8003db7c5e9f35ee98a5897e59">DynamicLibrary::SearchOrdering</a> Order)</td>
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



<p>Definition at line 81 of file <a href="/web-llvm/docs/api/files/lib/lib/support/dynamiclibrary-cpp">DynamicLibrary.cpp</a>.</p>


<p>References <a href="#aaea4161534624cd91cd5404b6f25291c">llvm::sys::DynamicLibrary::HandleSet::DLSym</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6b0ac1fa4f05de76413c5e0ca6334035">llvm::reverse</a> and <a href="/web-llvm/docs/api/classes/llvm/sys/dynamiclibrary/#a5e198e8003db7c5e9f35ee98a5897e59a766335f02cb77f4bea92f2212f65c0b5">llvm::sys::DynamicLibrary::SO_LoadOrder</a>.</p>


<p>Referenced by <a href="#a69d9a9e69fed62d0f6edd6aa1eb77d95">llvm::sys::DynamicLibrary::HandleSet::Lookup</a>.</p>

</div>
</div>

### Lookup() {#a69d9a9e69fed62d0f6edd6aa1eb77d95}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void * llvm::sys::DynamicLibrary::HandleSet::Lookup (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Symbol, <a href="/web-llvm/docs/api/classes/llvm/sys/dynamiclibrary/#a5e198e8003db7c5e9f35ee98a5897e59">DynamicLibrary::SearchOrdering</a> Order)</td>
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



<p>Definition at line 96 of file <a href="/web-llvm/docs/api/files/lib/lib/support/dynamiclibrary-cpp">DynamicLibrary.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#aaea4161534624cd91cd5404b6f25291c">llvm::sys::DynamicLibrary::HandleSet::DLSym</a>, <a href="#aacb1203f411484794ada2f3e9556ef63">llvm::sys::DynamicLibrary::HandleSet::LibLookup</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a>, <a href="/web-llvm/docs/api/classes/llvm/sys/dynamiclibrary/#a5e198e8003db7c5e9f35ee98a5897e59a8e941223db97baefe656ec0adc0d78ab">llvm::sys::DynamicLibrary::SO_LoadedFirst</a> and <a href="/web-llvm/docs/api/classes/llvm/sys/dynamiclibrary/#a5e198e8003db7c5e9f35ee98a5897e59a455bb962eea2904a7faa441d04b59946">llvm::sys::DynamicLibrary::SO_LoadedLast</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Handles {#a1ed7e25a60280aa79aaee97e30b5f2b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">HandleList llvm::sys::DynamicLibrary::HandleSet::Handles</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 27 of file <a href="/web-llvm/docs/api/files/lib/lib/support/dynamiclibrary-cpp">DynamicLibrary.cpp</a>.</p>

</div>
</div>

### Process {#abec4fb8aa1a9b564577c12e62fed3269}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void* llvm::sys::DynamicLibrary::HandleSet::Process = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 28 of file <a href="/web-llvm/docs/api/files/lib/lib/support/dynamiclibrary-cpp">DynamicLibrary.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### DLClose() {#ae7a8e4c562fe12a27adea30aba533254}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::sys::DynamicLibrary::HandleSet::DLClose (void * Handle)</td>
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



<p>Definition at line 32 of file <a href="/web-llvm/docs/api/files/lib/lib/support/dynamiclibrary-cpp">DynamicLibrary.cpp</a>.</p>


<p>Referenced by <a href="#a57e48229c8cea2a8adee11137875503f">llvm::sys::DynamicLibrary::HandleSet::AddLibrary</a> and <a href="#afdf806f09f0e9c8f46b2af3e7671008b">llvm::sys::DynamicLibrary::HandleSet::CloseLibrary</a>.</p>

</div>
</div>

### DLOpen() {#a9df2a55f4a1ee34610802540457f3fab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void * llvm::sys::DynamicLibrary::HandleSet::DLOpen (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Filename, std::string * Err)</td>
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



<p>Definition at line 31 of file <a href="/web-llvm/docs/api/files/lib/lib/support/dynamiclibrary-cpp">DynamicLibrary.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sys/dynamiclibrary/#a1222f2fb8f4a8b093d6419c74ff30e1e">llvm::sys::DynamicLibrary::getLibrary</a> and <a href="/web-llvm/docs/api/classes/llvm/sys/dynamiclibrary/#a5fe607fc919d5fcd00bdfded75f46643">llvm::sys::DynamicLibrary::getPermanentLibrary</a>.</p>

</div>
</div>

### DLSym() {#aaea4161534624cd91cd5404b6f25291c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void * llvm::sys::DynamicLibrary::HandleSet::DLSym (void * Handle, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Symbol)</td>
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



<p>Definition at line 33 of file <a href="/web-llvm/docs/api/files/lib/lib/support/dynamiclibrary-cpp">DynamicLibrary.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sys/dynamiclibrary/#aba426dbb54c99f3421554c5087c91f85">llvm::sys::DynamicLibrary::getAddressOfSymbol</a>, <a href="#aacb1203f411484794ada2f3e9556ef63">llvm::sys::DynamicLibrary::HandleSet::LibLookup</a> and <a href="#a69d9a9e69fed62d0f6edd6aa1eb77d95">llvm::sys::DynamicLibrary::HandleSet::Lookup</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/support/dynamiclibrary-cpp">DynamicLibrary.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>

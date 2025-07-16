---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/orc/simpleremoteepc/setup
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `Setup` Struct Reference

<p>A setup object containing callbacks to construct a memory manager and memory access object. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::orc::SimpleRemoteEPC::Setup { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/simpleremoteepc-h">llvm/ExecutionEngine/Orc/SimpleRemoteEPC.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a86d7307c7a5c1c898db82e89e8f4e5b5">CreateMemoryManagerFn</a> = <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/jitlink/jitlinkmemorymanager">jitlink::JITLinkMemoryManager</a> &gt; &gt;( <a href="/web-llvm/docs/api/classes/llvm/orc/simpleremoteepc">SimpleRemoteEPC</a> &amp;)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2044fd8d0e68df68dfe74163015d0d60">CreateMemoryAccessFn</a> = <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/executorprocesscontrol/memoryaccess">MemoryAccess</a> &gt; &gt;(<a href="/web-llvm/docs/api/classes/llvm/orc/simpleremoteepc">SimpleRemoteEPC</a> &amp;)</td>
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

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/unique-function">unique_function</a>&lt; <a href="#a86d7307c7a5c1c898db82e89e8f4e5b5">CreateMemoryManagerFn</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac379be9cb92b0f9eab27345c4dcb5d94">CreateMemoryManager</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/unique-function">unique_function</a>&lt; <a href="#a2044fd8d0e68df68dfe74163015d0d60">CreateMemoryAccessFn</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af80917e4f0dfa92e4eba14cc2655c9bc">CreateMemoryAccess</a></td>
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

<p>A setup object containing callbacks to construct a memory manager and memory access object.</p>


<p>Both are optional. If not specified, <a href="/web-llvm/docs/api/classes/llvm/orc/epcgenericjitlinkmemorymanager">EPCGenericJITLinkMemoryManager</a> and <a href="/web-llvm/docs/api/classes/llvm/orc/epcgenericmemoryaccess">EPCGenericMemoryAccess</a> will be used.</p>


<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/simpleremoteepc-h">SimpleRemoteEPC.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### CreateMemoryAccessFn {#a2044fd8d0e68df68dfe74163015d0d60}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::orc::SimpleRemoteEPC::Setup::CreateMemoryAccessFn = 
        Expected&lt;std::unique_ptr&lt;MemoryAccess&gt;&gt;(SimpleRemoteEPC &amp;)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/simpleremoteepc-h">SimpleRemoteEPC.h</a>.</p>

</div>
</div>

### CreateMemoryManagerFn {#a86d7307c7a5c1c898db82e89e8f4e5b5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::orc::SimpleRemoteEPC::Setup::CreateMemoryManagerFn = 
        Expected&lt;std::unique_ptr&lt;jitlink::JITLinkMemoryManager&gt;&gt;(
            SimpleRemoteEPC &amp;)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 39 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/simpleremoteepc-h">SimpleRemoteEPC.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### CreateMemoryAccess {#af80917e4f0dfa92e4eba14cc2655c9bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unique_function&lt;CreateMemoryAccessFn&gt; llvm::orc::SimpleRemoteEPC::Setup::CreateMemoryAccess</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/simpleremoteepc-h">SimpleRemoteEPC.h</a>.</p>

</div>
</div>

### CreateMemoryManager {#ac379be9cb92b0f9eab27345c4dcb5d94}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unique_function&lt;CreateMemoryManagerFn&gt; llvm::orc::SimpleRemoteEPC::Setup::CreateMemoryManager</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 45 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/simpleremoteepc-h">SimpleRemoteEPC.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/simpleremoteepc-h">SimpleRemoteEPC.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>

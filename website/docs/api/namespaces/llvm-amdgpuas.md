---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/llvm/amdgpuas
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# `AMDGPUAS` Namespace

<p>OpenCL uses address spaces to differentiate between various memory regions on the hardware. <a href="#details">More...</a></p>

## Definition

<div class="doxyDefinition">
namespace llvm::AMDGPUAS { ... }
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">anonymous enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"> : unsigned { <a href="#a899ad5bfccfc22965a6714929a3dfae1">...</a> }</td>
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

<p>OpenCL uses address spaces to differentiate between various memory regions on the hardware.</p>


<p>On the CPU all of the address spaces point to the same memory, however on the GPU, each address space points to a separate piece of memory that is unique from other memory locations.</p>


<div class="doxySectionDef">

## Enumerations

### anonymous enum  {#a899ad5bfccfc22965a6714929a3dfae1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous enum : unsigned</td>
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
<td class="doxyEnumItemName">MAX_AMDGPU_ADDRESS<a id="a899ad5bfccfc22965a6714929a3dfae1a1b0f93bdf84751537afc22e8e8c58f31"></a></td>
<td class="doxyEnumItemDescription"> (= 9)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FLAT_ADDRESS<a id="a899ad5bfccfc22965a6714929a3dfae1aaa1e27e4fc68e5706a4b7bbaed447c14"></a></td>
<td class="doxyEnumItemDescription">Address space for flat memory (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">GLOBAL_ADDRESS<a id="a899ad5bfccfc22965a6714929a3dfae1abf4559ef958a13c33f6ec7ed13fd44e5"></a></td>
<td class="doxyEnumItemDescription">Address space for global memory (RAT0, VTX0) (= 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">REGION_ADDRESS<a id="a899ad5bfccfc22965a6714929a3dfae1a5b71ba6fa435ec288aba849e113721a7"></a></td>
<td class="doxyEnumItemDescription">Address space for region memory. (GDS) (= 2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CONSTANT_ADDRESS<a id="a899ad5bfccfc22965a6714929a3dfae1aa6d3112da64eecbdbb50aacb5f8251e8"></a></td>
<td class="doxyEnumItemDescription">Address space for constant memory (VTX2) (= 4)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LOCAL_ADDRESS<a id="a899ad5bfccfc22965a6714929a3dfae1a77b1c964e2ff99057bf5e75140457abe"></a></td>
<td class="doxyEnumItemDescription">Address space for local memory (= 3)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PRIVATE_ADDRESS<a id="a899ad5bfccfc22965a6714929a3dfae1aec164f45437d8827346f2d8ec645479a"></a></td>
<td class="doxyEnumItemDescription">Address space for private memory (= 5)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CONSTANT_ADDRESS_32BIT<a id="a899ad5bfccfc22965a6714929a3dfae1a1caf1e287a5fe7250388d66ed72aa0c1"></a></td>
<td class="doxyEnumItemDescription">Address space for 32-bit constant memory (= 6)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BUFFER_FAT_POINTER<a id="a899ad5bfccfc22965a6714929a3dfae1ae0523ec09f17ea21ac251db04f249f13"></a></td>
<td class="doxyEnumItemDescription">Address space for 160-bit buffer fat pointers (= 7)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BUFFER_RESOURCE<a id="a899ad5bfccfc22965a6714929a3dfae1af3a547aa91b97183a165b876de8e24d8"></a></td>
<td class="doxyEnumItemDescription">Address space for 128-bit buffer resources (= 8)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BUFFER_STRIDED_POINTER<a id="a899ad5bfccfc22965a6714929a3dfae1a3f428ecb6bd1846dcc64d491627bf34c"></a></td>
<td class="doxyEnumItemDescription">Address space for 192-bit fat buffer pointers with an additional index (= 9)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">STREAMOUT_REGISTER<a id="a899ad5bfccfc22965a6714929a3dfae1a7e7e8d1de429748a8994d6e65aad8058"></a></td>
<td class="doxyEnumItemDescription">Internal address spaces. Can be freely renumbered (= 128)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PARAM_D_ADDRESS<a id="a899ad5bfccfc22965a6714929a3dfae1a4da965819228912d2be72bf34ace8ac7"></a></td>
<td class="doxyEnumItemDescription">end Internal address spaces (= 6)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PARAM_I_ADDRESS<a id="a899ad5bfccfc22965a6714929a3dfae1aa03e3cb93fc64ad53958ab0a2ff22f3a"></a></td>
<td class="doxyEnumItemDescription">Address space for indirect addressable parameter memory (VTX1) (= 7)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CONSTANT_BUFFER_0<a id="a899ad5bfccfc22965a6714929a3dfae1a68e5b0cf4fb0f4c890718e035b0bda43"></a></td>
<td class="doxyEnumItemDescription"> (= 8)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CONSTANT_BUFFER_1<a id="a899ad5bfccfc22965a6714929a3dfae1a64d1b03730a1b8b4aca40e84e63eea6b"></a></td>
<td class="doxyEnumItemDescription"> (= 9)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CONSTANT_BUFFER_2<a id="a899ad5bfccfc22965a6714929a3dfae1a5b84435a1d1c1f75607fad4546dc5bea"></a></td>
<td class="doxyEnumItemDescription"> (= 10)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CONSTANT_BUFFER_3<a id="a899ad5bfccfc22965a6714929a3dfae1a975ff96a4b32b329ca86775d461904f2"></a></td>
<td class="doxyEnumItemDescription"> (= 11)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CONSTANT_BUFFER_4<a id="a899ad5bfccfc22965a6714929a3dfae1a8cba8deb8ceec63630ba784bb676033a"></a></td>
<td class="doxyEnumItemDescription"> (= 12)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CONSTANT_BUFFER_5<a id="a899ad5bfccfc22965a6714929a3dfae1a05a0bd0e4d5cf5666b2f45a4bb35885b"></a></td>
<td class="doxyEnumItemDescription"> (= 13)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CONSTANT_BUFFER_6<a id="a899ad5bfccfc22965a6714929a3dfae1a49a82d15569ccc59a2ad8e8f429b3f56"></a></td>
<td class="doxyEnumItemDescription"> (= 14)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CONSTANT_BUFFER_7<a id="a899ad5bfccfc22965a6714929a3dfae1ad10671f6761c2f072e653640bba0eb02"></a></td>
<td class="doxyEnumItemDescription"> (= 15)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CONSTANT_BUFFER_8<a id="a899ad5bfccfc22965a6714929a3dfae1a878edbfb8d3ec011facbc2edbc7a59f7"></a></td>
<td class="doxyEnumItemDescription"> (= 16)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CONSTANT_BUFFER_9<a id="a899ad5bfccfc22965a6714929a3dfae1ac4eeef2485d218014b9dea8864648a70"></a></td>
<td class="doxyEnumItemDescription"> (= 17)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CONSTANT_BUFFER_10<a id="a899ad5bfccfc22965a6714929a3dfae1aa028984da110ed34209bbbe761c1fef3"></a></td>
<td class="doxyEnumItemDescription"> (= 18)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CONSTANT_BUFFER_11<a id="a899ad5bfccfc22965a6714929a3dfae1a3ab680d1e90b790940d9fb3c8fdd028b"></a></td>
<td class="doxyEnumItemDescription"> (= 19)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CONSTANT_BUFFER_12<a id="a899ad5bfccfc22965a6714929a3dfae1a4ad480e24dd594269af987200c07ea96"></a></td>
<td class="doxyEnumItemDescription"> (= 20)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CONSTANT_BUFFER_13<a id="a899ad5bfccfc22965a6714929a3dfae1ade7a111702bb4e8a074c9eb060b87655"></a></td>
<td class="doxyEnumItemDescription"> (= 21)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CONSTANT_BUFFER_14<a id="a899ad5bfccfc22965a6714929a3dfae1ac0e10a01fda68f0b5fee55ca2dbc8452"></a></td>
<td class="doxyEnumItemDescription"> (= 22)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CONSTANT_BUFFER_15<a id="a899ad5bfccfc22965a6714929a3dfae1a1ae19b57472eec1e951506094d92a411"></a></td>
<td class="doxyEnumItemDescription"> (= 23)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UNKNOWN_ADDRESS_SPACE<a id="a899ad5bfccfc22965a6714929a3dfae1aa7cd1e9c7b1298036f590733360da0a8"></a></td>
<td class="doxyEnumItemDescription"> (= ~0u)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 26 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/amdgpuaddrspace-h">AMDGPUAddrSpace.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/amdgpuaddrspace-h">AMDGPUAddrSpace.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>

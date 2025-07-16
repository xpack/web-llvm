---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/include/include/llvm-c/target-h
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `Target.h` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm-c/externc-h">llvm-c/ExternC.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm-c/types-h">llvm-c/Types.h</a>"
#include "llvm/Config/llvm-config.h"
#include "llvm/Config/Targets.def"
#include "llvm/Config/AsmPrinters.def"
#include "llvm/Config/AsmParsers.def"
#include "llvm/Config/Disassemblers.def"
</div>

## Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">struct LLVMOpaqueTargetData * <a href="/web-llvm/docs/api/groups/llvmctarget/#gace7868f675950a8dfc3338b14652c686">LLVMTargetDataRef</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">struct LLVMOpaqueTargetLibraryInfotData * <a href="/web-llvm/docs/api/groups/llvmctarget/#gab4742784b68fa3a7fc1b0f176a750d0d">LLVMTargetLibraryInfoRef</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">LLVMByteOrdering { <a href="/web-llvm/docs/api/groups/llvmctarget/#ga443555ba81225bf4cc1b617194b49f3b">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmctarget/#ga40188f383ddf8774ede38e8098da9a9a">LLVMInitializeAllTargetInfos</a> (void)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>LLVMInitializeAllTargetInfos - The main program should call this function if it wants access to all available targets that LLVM is configured to support. <a href="/web-llvm/docs/api/groups/llvmctarget/#ga40188f383ddf8774ede38e8098da9a9a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmctarget/#gace43bdd15ad030e38c41ae1cb43a2539">LLVMInitializeAllTargets</a> (void)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>LLVMInitializeAllTargets - The main program should call this function if it wants to link in all available targets that LLVM is configured to support. <a href="/web-llvm/docs/api/groups/llvmctarget/#gace43bdd15ad030e38c41ae1cb43a2539">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmctarget/#ga750b05e81ab9a921bb6d2e9b912e66eb">LLVMInitializeAllTargetMCs</a> (void)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>LLVMInitializeAllTargetMCs - The main program should call this function if it wants access to all available target MC that LLVM is configured to support. <a href="/web-llvm/docs/api/groups/llvmctarget/#ga750b05e81ab9a921bb6d2e9b912e66eb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmctarget/#gadcbb41ca7051aca660022e70ee62dd7f">LLVMInitializeAllAsmPrinters</a> (void)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>LLVMInitializeAllAsmPrinters - The main program should call this function if it wants all asm printers that LLVM is configured to support, to make them available via the TargetRegistry. <a href="/web-llvm/docs/api/groups/llvmctarget/#gadcbb41ca7051aca660022e70ee62dd7f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmctarget/#gac1bf201af65b31cc658ce3e465ad1f9d">LLVMInitializeAllAsmParsers</a> (void)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>LLVMInitializeAllAsmParsers - The main program should call this function if it wants all asm parsers that LLVM is configured to support, to make them available via the TargetRegistry. <a href="/web-llvm/docs/api/groups/llvmctarget/#gac1bf201af65b31cc658ce3e465ad1f9d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmctarget/#gae83d422c3f9503c4f3a389cc60f1e00d">LLVMInitializeAllDisassemblers</a> (void)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>LLVMInitializeAllDisassemblers - The main program should call this function if it wants all disassemblers that LLVM is configured to support, to make them available via the TargetRegistry. <a href="/web-llvm/docs/api/groups/llvmctarget/#gae83d422c3f9503c4f3a389cc60f1e00d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga209de0bceb13179a973c6a45211617bd">LLVMBool</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmctarget/#gac9550ed1ea52fa14c3b2ac408ed3b600">LLVMInitializeNativeTarget</a> (void)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>LLVMInitializeNativeTarget - The main program should call this function to initialize the native target corresponding to the host. <a href="/web-llvm/docs/api/groups/llvmctarget/#gac9550ed1ea52fa14c3b2ac408ed3b600">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga209de0bceb13179a973c6a45211617bd">LLVMBool</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmctarget/#ga00b903f987b38dd7db92c3e99787ed60">LLVMInitializeNativeAsmParser</a> (void)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>LLVMInitializeNativeTargetAsmParser - The main program should call this function to initialize the parser for the native target corresponding to the host. <a href="/web-llvm/docs/api/groups/llvmctarget/#ga00b903f987b38dd7db92c3e99787ed60">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga209de0bceb13179a973c6a45211617bd">LLVMBool</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmctarget/#ga6a7ac402bbacb455b7c468e5ee340910">LLVMInitializeNativeAsmPrinter</a> (void)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>LLVMInitializeNativeTargetAsmPrinter - The main program should call this function to initialize the printer for the native target corresponding to the host. <a href="/web-llvm/docs/api/groups/llvmctarget/#ga6a7ac402bbacb455b7c468e5ee340910">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga209de0bceb13179a973c6a45211617bd">LLVMBool</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmctarget/#ga6d1237e061210640b9e9c66b552abcd0">LLVMInitializeNativeDisassembler</a> (void)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>LLVMInitializeNativeTargetDisassembler - The main program should call this function to initialize the disassembler for the native target corresponding to the host. <a href="/web-llvm/docs/api/groups/llvmctarget/#ga6d1237e061210640b9e9c66b552abcd0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmctarget/#gace7868f675950a8dfc3338b14652c686">LLVMTargetDataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmctarget/#ga0b1cfce31433d9948825ed2e2e203830">LLVMGetModuleDataLayout</a> (LLVMModuleRef M)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Obtain the data layout for a module. <a href="/web-llvm/docs/api/groups/llvmctarget/#ga0b1cfce31433d9948825ed2e2e203830">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmctarget/#ga0943c2380edf6ce67d22ea757b2fec26">LLVMSetModuleDataLayout</a> (LLVMModuleRef M, LLVMTargetDataRef DL)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the data layout for a module. <a href="/web-llvm/docs/api/groups/llvmctarget/#ga0943c2380edf6ce67d22ea757b2fec26">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmctarget/#gace7868f675950a8dfc3338b14652c686">LLVMTargetDataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmctarget/#gac888ac3cfbfa7c2f48bca52006e81c91">LLVMCreateTargetData</a> (const char *StringRep)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Creates target data from a target layout string. <a href="/web-llvm/docs/api/groups/llvmctarget/#gac888ac3cfbfa7c2f48bca52006e81c91">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmctarget/#ga241569a7413b926f68263b3f0a8222a2">LLVMDisposeTargetData</a> (LLVMTargetDataRef TD)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Deallocates a TargetData. <a href="/web-llvm/docs/api/groups/llvmctarget/#ga241569a7413b926f68263b3f0a8222a2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmctarget/#gaaa147db9ad85da0e0a4011c736e18a26">LLVMAddTargetLibraryInfo</a> (LLVMTargetLibraryInfoRef TLI, LLVMPassManagerRef PM)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Adds target library information to a pass manager. <a href="/web-llvm/docs/api/groups/llvmctarget/#gaaa147db9ad85da0e0a4011c736e18a26">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmctarget/#ga31a8ce880612fa3fd6b3d5b81913c695">LLVMCopyStringRepOfTargetData</a> (LLVMTargetDataRef TD)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Converts target data to a target layout string. <a href="/web-llvm/docs/api/groups/llvmctarget/#ga31a8ce880612fa3fd6b3d5b81913c695">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum <a href="/web-llvm/docs/api/groups/llvmctarget/#ga443555ba81225bf4cc1b617194b49f3b">LLVMByteOrdering</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmctarget/#ga58db6dd95139ba45cf1512fa84611112">LLVMByteOrder</a> (LLVMTargetDataRef TD)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the byte order of a target, either LLVMBigEndian or LLVMLittleEndian. <a href="/web-llvm/docs/api/groups/llvmctarget/#ga58db6dd95139ba45cf1512fa84611112">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmctarget/#gab6ea442091017ffe1677f0720cc5aa7a">LLVMPointerSize</a> (LLVMTargetDataRef TD)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the pointer size in bytes for a target. <a href="/web-llvm/docs/api/groups/llvmctarget/#gab6ea442091017ffe1677f0720cc5aa7a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmctarget/#ga8eb45b6eaa0a48a4faef81f37ca64d40">LLVMPointerSizeForAS</a> (LLVMTargetDataRef TD, unsigned AS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the pointer size in bytes for a target for a specified address space. <a href="/web-llvm/docs/api/groups/llvmctarget/#ga8eb45b6eaa0a48a4faef81f37ca64d40">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab81b4df33167d47174f9b86a75e3be88">LLVMTypeRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmctarget/#ga677f27475a01ec69c1e63abd8fdd6f32">LLVMIntPtrType</a> (LLVMTargetDataRef TD)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the integer type that is the same size as a pointer on a target. <a href="/web-llvm/docs/api/groups/llvmctarget/#ga677f27475a01ec69c1e63abd8fdd6f32">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab81b4df33167d47174f9b86a75e3be88">LLVMTypeRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmctarget/#gabfa6b072ee3eca67aa93c59888d75f8d">LLVMIntPtrTypeForAS</a> (LLVMTargetDataRef TD, unsigned AS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the integer type that is the same size as a pointer on a target. <a href="/web-llvm/docs/api/groups/llvmctarget/#gabfa6b072ee3eca67aa93c59888d75f8d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab81b4df33167d47174f9b86a75e3be88">LLVMTypeRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmctarget/#ga377860a95fee357d990609debb150f94">LLVMIntPtrTypeInContext</a> (LLVMContextRef C, LLVMTargetDataRef TD)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the integer type that is the same size as a pointer on a target. <a href="/web-llvm/docs/api/groups/llvmctarget/#ga377860a95fee357d990609debb150f94">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab81b4df33167d47174f9b86a75e3be88">LLVMTypeRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmctarget/#gad659b1030acb5eb9c6ad6cf467a7339f">LLVMIntPtrTypeForASInContext</a> (LLVMContextRef C, LLVMTargetDataRef TD, unsigned AS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the integer type that is the same size as a pointer on a target. <a href="/web-llvm/docs/api/groups/llvmctarget/#gad659b1030acb5eb9c6ad6cf467a7339f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned long long</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmctarget/#gaa29cd97b498d32b9c5663574bd2659d7">LLVMSizeOfTypeInBits</a> (LLVMTargetDataRef TD, LLVMTypeRef Ty)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Computes the size of a type in bits for a target. <a href="/web-llvm/docs/api/groups/llvmctarget/#gaa29cd97b498d32b9c5663574bd2659d7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned long long</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmctarget/#ga4e44ae680973209dbcb915d7239518fe">LLVMStoreSizeOfType</a> (LLVMTargetDataRef TD, LLVMTypeRef Ty)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Computes the storage size of a type in bytes for a target. <a href="/web-llvm/docs/api/groups/llvmctarget/#ga4e44ae680973209dbcb915d7239518fe">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned long long</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmctarget/#gac457451d818eb0bf7c2f30fe2683536f">LLVMABISizeOfType</a> (LLVMTargetDataRef TD, LLVMTypeRef Ty)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Computes the ABI size of a type in bytes for a target. <a href="/web-llvm/docs/api/groups/llvmctarget/#gac457451d818eb0bf7c2f30fe2683536f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmctarget/#ga474ae58c596b5cb5c197a3f540479135">LLVMABIAlignmentOfType</a> (LLVMTargetDataRef TD, LLVMTypeRef Ty)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Computes the ABI alignment of a type in bytes for a target. <a href="/web-llvm/docs/api/groups/llvmctarget/#ga474ae58c596b5cb5c197a3f540479135">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmctarget/#ga90346e4b2e6c4e46ead5a75717c1adf6">LLVMCallFrameAlignmentOfType</a> (LLVMTargetDataRef TD, LLVMTypeRef Ty)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Computes the call frame alignment of a type in bytes for a target. <a href="/web-llvm/docs/api/groups/llvmctarget/#ga90346e4b2e6c4e46ead5a75717c1adf6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmctarget/#gaf1b1eb29d68cf85fea159a4bc6125176">LLVMPreferredAlignmentOfType</a> (LLVMTargetDataRef TD, LLVMTypeRef Ty)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Computes the preferred alignment of a type in bytes for a target. <a href="/web-llvm/docs/api/groups/llvmctarget/#gaf1b1eb29d68cf85fea159a4bc6125176">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmctarget/#ga0e8da4e06e8503aa8f887d16f23d5eba">LLVMPreferredAlignmentOfGlobal</a> (LLVMTargetDataRef TD, LLVMValueRef GlobalVar)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Computes the preferred alignment of a global variable in bytes for a target. <a href="/web-llvm/docs/api/groups/llvmctarget/#ga0e8da4e06e8503aa8f887d16f23d5eba">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmctarget/#gaea687102374386eb3181083ed00a8700">LLVMElementAtOffset</a> (LLVMTargetDataRef TD, LLVMTypeRef StructTy, unsigned long long Offset)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Computes the structure element that contains the byte offset for a target. <a href="/web-llvm/docs/api/groups/llvmctarget/#gaea687102374386eb3181083ed00a8700">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned long long</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmctarget/#ga9971347f4072d348862519bbacbd71a7">LLVMOffsetOfElement</a> (LLVMTargetDataRef TD, LLVMTypeRef StructTy, unsigned Element)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Computes the byte offset of the indexed struct element for a target. <a href="/web-llvm/docs/api/groups/llvmctarget/#ga9971347f4072d348862519bbacbd71a7">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmctarget/#ga59ebd56af9d9a81e25690bfb8f503bd5">LLVM_TARGET</a>(TargetName)&nbsp;&nbsp;&nbsp;  void LLVMInitialize##TargetName##TargetInfo(void);</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmctarget/#ga1de0387eb53605e1052ac1bcb626cdcf">LLVM_TARGET</a>(TargetName)&nbsp;&nbsp;&nbsp;void LLVMInitialize##TargetName##Target(void);</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmctarget/#ga2cc27018eb70489bb3b43c3fdcefd9c3">LLVM_TARGET</a>(TargetName)&nbsp;&nbsp;&nbsp;  void LLVMInitialize##TargetName##TargetMC(void);</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmctarget/#gad1184b0ccd804ec381a8740ff580103b">LLVM_ASM_PRINTER</a>(TargetName)&nbsp;&nbsp;&nbsp;  void LLVMInitialize##TargetName##AsmPrinter(void);</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmctarget/#ga9b8ec1332a57ea67e49ca9475785d829">LLVM_ASM_PARSER</a>(TargetName)&nbsp;&nbsp;&nbsp;  void LLVMInitialize##TargetName##AsmParser(void);</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmctarget/#gabc2ca2130e75e7cf2a0bb5884505fa39">LLVM_DISASSEMBLER</a>(TargetName)&nbsp;&nbsp;&nbsp;  void LLVMInitialize##TargetName##Disassembler(void);</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmctarget/#ga3d7be98af2b886dc6d207dd4d6762b84">LLVM_TARGET</a>(TargetName)&nbsp;&nbsp;&nbsp;LLVMInitialize##TargetName##TargetInfo();</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmctarget/#gac9146c0c56e5bc711f516707403f212f">LLVM_TARGET</a>(TargetName)&nbsp;&nbsp;&nbsp;LLVMInitialize##TargetName##Target();</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmctarget/#gaa11659625d0ab517c9b62232b2800977">LLVM_TARGET</a>(TargetName)&nbsp;&nbsp;&nbsp;LLVMInitialize##TargetName##TargetMC();</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmctarget/#ga99b4afe22867ba61e4698768c7db68f5">LLVM_ASM_PRINTER</a>(TargetName)&nbsp;&nbsp;&nbsp;LLVMInitialize##TargetName##AsmPrinter();</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmctarget/#ga4ba11ec1fed6f535a618118dfc4d929d">LLVM_ASM_PARSER</a>(TargetName)&nbsp;&nbsp;&nbsp;LLVMInitialize##TargetName##AsmParser();</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmctarget/#gad8d8ed18edf413a96aca4416779f970b">LLVM_DISASSEMBLER</a>(TargetName)&nbsp;&nbsp;&nbsp;  LLVMInitialize##TargetName##Disassembler();</td>
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


<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>

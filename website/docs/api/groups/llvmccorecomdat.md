---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/groups/llvmccorecomdat
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - group

---

<div class="doxyPage">

# The Comdats Reference



## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">LLVMComdatSelectionKind { <a href="#ga80b57e9f148541803b3ed1169528187e">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gaa91542000fd23d2eeebf64a25bdc66b3">LLVMComdatRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga2c1696880a604332d967f41fa93b524a">LLVMGetOrInsertComdat</a> (LLVMModuleRef M, const char *Name)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the Comdat in the module with the specified name. <a href="#ga2c1696880a604332d967f41fa93b524a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gaa91542000fd23d2eeebf64a25bdc66b3">LLVMComdatRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gaa0aa7ad46539182dec109edc141c870d">LLVMGetComdat</a> (LLVMValueRef V)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the Comdat assigned to the given global object. <a href="#gaa0aa7ad46539182dec109edc141c870d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga3f947a7b8327e41221592d6a0da3d595">LLVMSetComdat</a> (LLVMValueRef V, LLVMComdatRef C)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Assign the Comdat to the given global object. <a href="#ga3f947a7b8327e41221592d6a0da3d595">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ga80b57e9f148541803b3ed1169528187e">LLVMComdatSelectionKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga24a9af9f9933c9ab3cbfa8a87e7ab5de">LLVMGetComdatSelectionKind</a> (LLVMComdatRef C)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga770da47f1db21be71881a94b5842a808">LLVMSetComdatSelectionKind</a> (LLVMComdatRef C, LLVMComdatSelectionKind Kind)</td>
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


<div class="doxySectionDef">

## Enumerations

### LLVMComdatSelectionKind {#ga80b57e9f148541803b3ed1169528187e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum LLVMComdatSelectionKind </td>
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
<td class="doxyEnumItemName">LLVMAnyComdatSelectionKind<a id="gga80b57e9f148541803b3ed1169528187ea907a8ef93233960f2907f075f39f46a5"></a></td>
<td class="doxyEnumItemDescription">The linker may choose any COMDAT</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LLVMExactMatchComdatSelectionKind<a id="gga80b57e9f148541803b3ed1169528187ea7e01f8f80d4b35b6495a603c8fd945c9"></a></td>
<td class="doxyEnumItemDescription">The data referenced by the COMDAT must be the same</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LLVMLargestComdatSelectionKind<a id="gga80b57e9f148541803b3ed1169528187ea147027adebf8f8011d33067dad285752"></a></td>
<td class="doxyEnumItemDescription">The linker will choose the largest COMDAT</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LLVMNoDeduplicateComdatSelectionKind<a id="gga80b57e9f148541803b3ed1169528187eac4adb55c2b9f3cb601b7603d86498066"></a></td>
<td class="doxyEnumItemDescription">No deduplication is performed</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LLVMSameSizeComdatSelectionKind<a id="gga80b57e9f148541803b3ed1169528187ea6d981d6944206f7c5d34671b4a061fa2"></a></td>
<td class="doxyEnumItemDescription">The data referenced by the COMDAT must be the same size</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 29 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/comdat-h">Comdat.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### LLVMGetComdat() {#gaa0aa7ad46539182dec109edc141c870d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMComdatRef LLVMGetComdat (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga113ce952344691b8304a43a314f8be17">LLVMValueRef</a> V)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the Comdat assigned to the given global object.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="/web-llvm/docs/api/classes/llvm/globalobject/#a09422787da7c96e7bc582e606489fe4a">llvm::GlobalObject::getComdat()</a></p></dd>
</dl>


<p>Declaration at line 53 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/comdat-h">Comdat.h</a>, definition at line 38 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/comdat-cpp">Comdat.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ad96b7cf3182ce2ba85e5a7a93b12c441">G</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

### LLVMGetComdatSelectionKind() {#ga24a9af9f9933c9ab3cbfa8a87e7ab5de}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMComdatSelectionKind LLVMGetComdatSelectionKind (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gaa91542000fd23d2eeebf64a25bdc66b3">LLVMComdatRef</a> C)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 67 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/comdat-h">Comdat.h</a>, definition at line 48 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/comdat-cpp">Comdat.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/comdat/#ab40cbf8243fad70968f9ecf82f48a035a8c4ae4df3d085db275a58182612ff3be">llvm::Comdat::Any</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/classes/llvm/comdat/#ab40cbf8243fad70968f9ecf82f48a035acceb065ea69a5e06e80bd6ceddd7b9a7">llvm::Comdat::ExactMatch</a>, <a href="/web-llvm/docs/api/classes/llvm/comdat/#ab40cbf8243fad70968f9ecf82f48a035a2444b05a47619decc80c2ce0cc224dc8">llvm::Comdat::Largest</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="#gga80b57e9f148541803b3ed1169528187ea907a8ef93233960f2907f075f39f46a5">LLVMAnyComdatSelectionKind</a>, <a href="#gga80b57e9f148541803b3ed1169528187ea7e01f8f80d4b35b6495a603c8fd945c9">LLVMExactMatchComdatSelectionKind</a>, <a href="#gga80b57e9f148541803b3ed1169528187ea147027adebf8f8011d33067dad285752">LLVMLargestComdatSelectionKind</a>, <a href="#gga80b57e9f148541803b3ed1169528187eac4adb55c2b9f3cb601b7603d86498066">LLVMNoDeduplicateComdatSelectionKind</a>, <a href="#gga80b57e9f148541803b3ed1169528187ea6d981d6944206f7c5d34671b4a061fa2">LLVMSameSizeComdatSelectionKind</a>, <a href="/web-llvm/docs/api/classes/llvm/comdat/#ab40cbf8243fad70968f9ecf82f48a035ab2d0d4bc9ba11b7324f5ffc20a9dc37a">llvm::Comdat::NoDeduplicate</a>, <a href="/web-llvm/docs/api/classes/llvm/comdat/#ab40cbf8243fad70968f9ecf82f48a035a8b148d3d05688ddb23b7abb81527b7ce">llvm::Comdat::SameSize</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>.</p>

</div>
</div>

### LLVMGetOrInsertComdat() {#ga2c1696880a604332d967f41fa93b524a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMComdatRef LLVMGetOrInsertComdat (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gad1d1bb5f901c903a0cf09c5a053c9c56">LLVMModuleRef</a> M, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Name)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the Comdat in the module with the specified name.</p>


<p>It is created if it didn't already exist.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="/web-llvm/docs/api/classes/llvm/module/#ab83085f68d866564c5dd63143c8cac2e">llvm::Module::getOrInsertComdat()</a></p></dd>
</dl>


<p>Declaration at line 46 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/comdat-h">Comdat.h</a>, definition at line 34 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/comdat-cpp">Comdat.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

### LLVMSetComdat() {#ga3f947a7b8327e41221592d6a0da3d595}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LLVMSetComdat (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga113ce952344691b8304a43a314f8be17">LLVMValueRef</a> V, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gaa91542000fd23d2eeebf64a25bdc66b3">LLVMComdatRef</a> C)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Assign the Comdat to the given global object.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="/web-llvm/docs/api/classes/llvm/globalobject/#a800a5183372ed37a74be5cddf5df325c">llvm::GlobalObject::setComdat()</a></p></dd>
</dl>


<p>Declaration at line 60 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/comdat-h">Comdat.h</a>, definition at line 43 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/comdat-cpp">Comdat.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ad96b7cf3182ce2ba85e5a7a93b12c441">G</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>.</p>

</div>
</div>

### LLVMSetComdatSelectionKind() {#ga770da47f1db21be71881a94b5842a808}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LLVMSetComdatSelectionKind (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gaa91542000fd23d2eeebf64a25bdc66b3">LLVMComdatRef</a> C, <a href="#ga80b57e9f148541803b3ed1169528187e">LLVMComdatSelectionKind</a> Kind)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 74 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/comdat-h">Comdat.h</a>, definition at line 64 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/comdat-cpp">Comdat.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/comdat/#ab40cbf8243fad70968f9ecf82f48a035a8c4ae4df3d085db275a58182612ff3be">llvm::Comdat::Any</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/classes/llvm/comdat/#ab40cbf8243fad70968f9ecf82f48a035acceb065ea69a5e06e80bd6ceddd7b9a7">llvm::Comdat::ExactMatch</a>, <a href="/web-llvm/docs/api/classes/llvm/comdat/#ab40cbf8243fad70968f9ecf82f48a035a2444b05a47619decc80c2ce0cc224dc8">llvm::Comdat::Largest</a>, <a href="#gga80b57e9f148541803b3ed1169528187ea907a8ef93233960f2907f075f39f46a5">LLVMAnyComdatSelectionKind</a>, <a href="#gga80b57e9f148541803b3ed1169528187ea7e01f8f80d4b35b6495a603c8fd945c9">LLVMExactMatchComdatSelectionKind</a>, <a href="#gga80b57e9f148541803b3ed1169528187ea147027adebf8f8011d33067dad285752">LLVMLargestComdatSelectionKind</a>, <a href="#gga80b57e9f148541803b3ed1169528187eac4adb55c2b9f3cb601b7603d86498066">LLVMNoDeduplicateComdatSelectionKind</a>, <a href="#gga80b57e9f148541803b3ed1169528187ea6d981d6944206f7c5d34671b4a061fa2">LLVMSameSizeComdatSelectionKind</a>, <a href="/web-llvm/docs/api/classes/llvm/comdat/#ab40cbf8243fad70968f9ecf82f48a035ab2d0d4bc9ba11b7324f5ffc20a9dc37a">llvm::Comdat::NoDeduplicate</a>, <a href="/web-llvm/docs/api/classes/llvm/comdat/#ab40cbf8243fad70968f9ecf82f48a035a8b148d3d05688ddb23b7abb81527b7ce">llvm::Comdat::SameSize</a>, <a href="/web-llvm/docs/api/classes/llvm/comdat/#ad8e5834e05be0104c4d64a3b4edeb51b">llvm::Comdat::setSelectionKind</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>

---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-linkmodules-cpp-/modulelinker
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `ModuleLinker` Class

<p>This is an implementation class for the LinkModules function, which is the entrypoint for this file. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class anonymous{LinkModules.cpp}::ModuleLinker { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac4d2ce992948fafa2cb9120381bcde7f">ModuleLinker</a> (IRMover &amp;Mover, std::unique_ptr&lt; Module &gt; SrcM, unsigned Flags, std::function&lt; void(Module &amp;, const StringSet&lt;&gt; &amp;)&gt; InternalizeCallback={})</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a589fd28f47f98110e06d544523d59977">run</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aff7e850bd462a13125000c2990fee1e5">addLazyFor</a> (GlobalValue &amp;GV, const IRMover::ValueAdder &amp;Add)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Used as the callback for lazy linking. <a href="#aff7e850bd462a13125000c2990fee1e5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a038cfc175841fec10e9ea26622312c3a">shouldOverrideFromSrc</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0672b66d91acfa88c285cbfd2122cbef">shouldLinkOnlyNeeded</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a300893a1b9662192f3a88bdced3a1d43">shouldLinkFromSource</a> (bool &amp;LinkFromSrc, const GlobalValue &amp;Dest, const GlobalValue &amp;Src)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#add888e61a2d0e71897391dd8d876489a">emitError</a> (const Twine &amp;Message)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Should we have mover and linker error diag info? <a href="#add888e61a2d0e71897391dd8d876489a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acbbd459153e352c3bc54968fd8c8f70c">getComdatLeader</a> (Module &amp;M, StringRef ComdatName, const GlobalVariable *&amp;GVar)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a79017f3f5cea345bcbd8a55b75d4b260">computeResultingSelectionKind</a> (StringRef ComdatName, Comdat::SelectionKind Src, Comdat::SelectionKind Dst, Comdat::SelectionKind &amp;Result, LinkFrom &amp;From)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a78071d618f4843432787d6712dbb43bd">getComdatResult</a> (const Comdat *SrcC, Comdat::SelectionKind &amp;SK, LinkFrom &amp;From)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a46029265c6fd11818e09bd23428c773b">getLinkedToGlobal</a> (const GlobalValue *SrcGV)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given a global in the source module, return the global in the destination module that is being linked to, if any. <a href="#a46029265c6fd11818e09bd23428c773b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a07de33af35c97a9216d51b0d820e527f">dropReplacedComdat</a> (GlobalValue &amp;GV, const DenseSet&lt; const Comdat * &gt; &amp;ReplacedDstComdats)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Drop GV if it is a member of a comdat that we are dropping. <a href="#a07de33af35c97a9216d51b0d820e527f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea544ef602b78cfd850d90c1045a3e30">linkIfNeeded</a> (GlobalValue &amp;GV, SmallVectorImpl&lt; GlobalValue * &gt; &amp;GVToClone)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/irmover">IRMover</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b0fee53afb3c553779bd32ef30f826e">Mover</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae2fad6c05cee0fe1cae6c2d911dc37ff">SrcM</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/setvector">SetVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a10a160a855d72c90ce373badf7145c4e">ValuesToLink</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9479128495328cf56f532fff716aaf6d">Flags</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>For symbol clashes, prefer those from Src. <a href="#a9479128495328cf56f532fff716aaf6d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringset">StringSet</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a059f4801214b7a13d6ff5acce14e49e3">Internalize</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>List of global value names that should be internalized. <a href="#a059f4801214b7a13d6ff5acce14e49e3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::function&lt; void(<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp;, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/stringset">StringSet</a>&lt;&gt; &amp;)&gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a03f44d3f56a41943e704671440442c47">InternalizeCallback</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> that will perform the actual internalization. <a href="#a03f44d3f56a41943e704671440442c47">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/comdat">Comdat</a> *, std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/comdat/#ab40cbf8243fad70968f9ecf82f48a035">Comdat::SelectionKind</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-linkmodules-cpp-/#ab56eb2027bc9c069aa696e54de8b4298">LinkFrom</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a05e5e3c46ffaf9332808e8edd2240506">ComdatsChosen</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/comdat">Comdat</a> *, std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> * &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade720e80aca8161eab16f7eaa8a12202">LazyComdatMembers</a></td>
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

<p>This is an implementation class for the LinkModules function, which is the entrypoint for this file.</p>

<p>Definition at line 30 of file <a href="/web-llvm/docs/api/files/lib/lib/linker/linkmodules-cpp">LinkModules.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### ModuleLinker() {#ac4d2ce992948fafa2cb9120381bcde7f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{LinkModules.cpp}::ModuleLinker::ModuleLinker (<a href="/web-llvm/docs/api/classes/llvm/irmover">IRMover</a> &amp; Mover, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &gt; SrcM, unsigned Flags, std::function&lt; void(<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp;, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/stringset">StringSet</a>&lt;&gt; &amp;)&gt; InternalizeCallback={})</td>
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



<p>Definition at line 110 of file <a href="/web-llvm/docs/api/files/lib/lib/linker/linkmodules-cpp">LinkModules.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### run() {#a589fd28f47f98110e06d544523d59977}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ModuleLinker::run ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 116 of file <a href="/web-llvm/docs/api/files/lib/lib/linker/linkmodules-cpp">LinkModules.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830eaec211f7c20af43e742bf2570c3cb84f9">llvm::Add</a>, <a href="/web-llvm/docs/api/classes/llvm/module/#a696e00bbe45dcea703f433de7b38f699">llvm::Module::aliases</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57caa67f293befacbbf974525116ccf2ff42">llvm::GlobalValue::AvailableExternallyLinkage</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/densesetimpl/#ad409c2de8502b94c8a0b1193307c63b6">llvm::detail::DenseSetImpl&lt; ValueT, MapTy, ValueInfoT &gt;::contains</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a9141f967188383108a69cc1b8ed3c195a2491e41d821f1d8fd3958ce3df2fddb2">llvm::GlobalValue::DefaultVisibility</a>, <a href="/web-llvm/docs/api/classes/llvm/llvmcontext/#aad03ef5cfbe6e7cad076d9e45ba06592">llvm::LLVMContext::diagnose</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abfcab32516704f11d146c757f402ad5caa73815097c71f15fe54ab447a7ff00ba">llvm::DS_Error</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-linkmodules-cpp-/#ab56eb2027bc9c069aa696e54de8b4298a1448a68418666ed85e07646744af82ef">anonymous{LinkModules.cpp}::Dst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/densesetimpl/#a9a3c9d867ff6bde97841c2b7983f5c70">llvm::detail::DenseSetImpl&lt; ValueT, MapTy, ValueInfoT &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/stringmap/#a16e5eaf2df56249e87019be23ee07695">llvm::StringMap&lt; ValueTy, AllocatorTy &gt;::end</a>, <a href="/web-llvm/docs/api/classes/llvm/stringmap/#a49e68e4c86fe0b96c633adea0c366d74">llvm::StringMap&lt; ValueTy, AllocatorTy &gt;::find</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a788ede5201dc9b44e419e9fd2fbb38bf">llvm::GlobalValue::getAliaseeObject</a>, <a href="/web-llvm/docs/api/classes/llvm/globalobject/#a98140bed34afff96a44ab31ef977f5ec">llvm::GlobalObject::getComdat</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a43721e1e88567116e8fca545125d86bf">llvm::GlobalValue::getComdat</a>, <a href="/web-llvm/docs/api/classes/llvm/module/#a1759adeccb706c96a44484dd01bdf0de">llvm::Module::getComdatSymbolTable</a>, <a href="/web-llvm/docs/api/classes/llvm/module/#a0beddb53641a541e2238617c5fac4be7">llvm::Module::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#adb5c319f5905c1d3ca9eb5df546388c5">llvm::Value::getName</a>, <a href="/web-llvm/docs/api/classes/llvm/module/#a8c41c9882546676724cb151c9ff8723e">llvm::Module::globals</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2aa0f5c36ac6291f5d5f2b4efd9ffe70">llvm::handleAllErrors</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a091e6599599c4e668373e0feefa92c01">llvm::GlobalValue::hasLinkOnceLinkage</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/densesetimpl/#a1b0f3ebdced8fce4b22c6a63b25d9525">llvm::detail::DenseSetImpl&lt; ValueT, MapTy, ValueInfoT &gt;::insert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3d2cdc4a0db233678e7141c9d6ea3419">llvm::make_early_inc_range</a>, <a href="/web-llvm/docs/api/classes/llvm/errorinfobase/#a2b75e20ae30dbb4d4d96486653a9b710">llvm::ErrorInfoBase::message</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57ca04ed141708c0fd16723d212502b046ae">llvm::GlobalValue::PrivateLinkage</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-linkmodules-cpp-/#ab56eb2027bc9c069aa696e54de8b4298a276e79316561733d64abdf00f8e8ae48">anonymous{LinkModules.cpp}::Src</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### addLazyFor() {#aff7e850bd462a13125000c2990fee1e5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ModuleLinker::addLazyFor (<a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> &amp; GV, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/irmover/#a8533211312d3dd54fbe98b80c635e7d4">IRMover::ValueAdder</a> &amp; Add)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Used as the callback for lazy linking.</p>


<p>The mover has just hit GV and we have to decide if it, and other members of the same comdat, should be linked. Every member to be linked is passed to Add.</p>


<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/lib/lib/linker/linkmodules-cpp">LinkModules.cpp</a>.</p>

</div>
</div>

### computeResultingSelectionKind() {#a79017f3f5cea345bcbd8a55b75d4b260}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ModuleLinker::computeResultingSelectionKind (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> ComdatName, <a href="/web-llvm/docs/api/classes/llvm/comdat/#ab40cbf8243fad70968f9ecf82f48a035">Comdat::SelectionKind</a> Src, <a href="/web-llvm/docs/api/classes/llvm/comdat/#ab40cbf8243fad70968f9ecf82f48a035">Comdat::SelectionKind</a> Dst, <a href="/web-llvm/docs/api/classes/llvm/comdat/#ab40cbf8243fad70968f9ecf82f48a035">Comdat::SelectionKind</a> &amp; Result, <a href="/web-llvm/docs/api/namespaces/anonymous-linkmodules-cpp-/#ab56eb2027bc9c069aa696e54de8b4298">LinkFrom</a> &amp; From)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/lib/lib/linker/linkmodules-cpp">LinkModules.cpp</a>.</p>

</div>
</div>

### dropReplacedComdat() {#a07de33af35c97a9216d51b0d820e527f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ModuleLinker::dropReplacedComdat (<a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> &amp; GV, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/denseset">DenseSet</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/comdat">Comdat</a> * &gt; &amp; ReplacedDstComdats)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Drop GV if it is a member of a comdat that we are dropping.</p>


<p>This can happen with <a href="/web-llvm/docs/api/namespaces/llvm/coff">COFF</a>'s largest selection kind.</p>


<p>Definition at line 104 of file <a href="/web-llvm/docs/api/files/lib/lib/linker/linkmodules-cpp">LinkModules.cpp</a>.</p>

</div>
</div>

### emitError() {#add888e61a2d0e71897391dd8d876489a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{LinkModules.cpp}::ModuleLinker::emitError (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Message)</td>
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

<p>Should we have mover and linker error diag info?</p>

<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/lib/lib/linker/linkmodules-cpp">LinkModules.cpp</a>.</p>

</div>
</div>

### getComdatLeader() {#acbbd459153e352c3bc54968fd8c8f70c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ModuleLinker::getComdatLeader (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> ComdatName, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalvariable">GlobalVariable</a> *&amp; GVar)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/lib/lib/linker/linkmodules-cpp">LinkModules.cpp</a>.</p>

</div>
</div>

### getComdatResult() {#a78071d618f4843432787d6712dbb43bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ModuleLinker::getComdatResult (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/comdat">Comdat</a> * SrcC, <a href="/web-llvm/docs/api/classes/llvm/comdat/#ab40cbf8243fad70968f9ecf82f48a035">Comdat::SelectionKind</a> &amp; SK, <a href="/web-llvm/docs/api/namespaces/anonymous-linkmodules-cpp-/#ab56eb2027bc9c069aa696e54de8b4298">LinkFrom</a> &amp; From)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 74 of file <a href="/web-llvm/docs/api/files/lib/lib/linker/linkmodules-cpp">LinkModules.cpp</a>.</p>

</div>
</div>

### getLinkedToGlobal() {#a46029265c6fd11818e09bd23428c773b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GlobalValue * anonymous{LinkModules.cpp}::ModuleLinker::getLinkedToGlobal (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> * SrcGV)</td>
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

<p>Given a global in the source module, return the global in the destination module that is being linked to, if any.</p>

<p>Definition at line 81 of file <a href="/web-llvm/docs/api/files/lib/lib/linker/linkmodules-cpp">LinkModules.cpp</a>.</p>

</div>
</div>

### linkIfNeeded() {#aea544ef602b78cfd850d90c1045a3e30}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ModuleLinker::linkIfNeeded (<a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> &amp; GV, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> * &gt; &amp; GVToClone)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 107 of file <a href="/web-llvm/docs/api/files/lib/lib/linker/linkmodules-cpp">LinkModules.cpp</a>.</p>

</div>
</div>

### shouldLinkFromSource() {#a300893a1b9662192f3a88bdced3a1d43}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ModuleLinker::shouldLinkFromSource (bool &amp; LinkFromSrc, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> &amp; Dest, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> &amp; Src)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 56 of file <a href="/web-llvm/docs/api/files/lib/lib/linker/linkmodules-cpp">LinkModules.cpp</a>.</p>

</div>
</div>

### shouldLinkOnlyNeeded() {#a0672b66d91acfa88c285cbfd2122cbef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{LinkModules.cpp}::ModuleLinker::shouldLinkOnlyNeeded ()</td>
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



<p>Definition at line 54 of file <a href="/web-llvm/docs/api/files/lib/lib/linker/linkmodules-cpp">LinkModules.cpp</a>.</p>

</div>
</div>

### shouldOverrideFromSrc() {#a038cfc175841fec10e9ea26622312c3a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{LinkModules.cpp}::ModuleLinker::shouldOverrideFromSrc ()</td>
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



<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/lib/lib/linker/linkmodules-cpp">LinkModules.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### ComdatsChosen {#a05e5e3c46ffaf9332808e8edd2240506}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;const Comdat *, std::pair&lt;Comdat::SelectionKind, LinkFrom&gt; &gt; anonymous{LinkModules.cpp}::ModuleLinker::ComdatsChosen</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/lib/lib/linker/linkmodules-cpp">LinkModules.cpp</a>.</p>

</div>
</div>

### Flags {#a9479128495328cf56f532fff716aaf6d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{LinkModules.cpp}::ModuleLinker::Flags</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>For symbol clashes, prefer those from Src.</p>

<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/lib/lib/linker/linkmodules-cpp">LinkModules.cpp</a>.</p>

</div>
</div>

### Internalize {#a059f4801214b7a13d6ff5acce14e49e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringSet anonymous{LinkModules.cpp}::ModuleLinker::Internalize</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>List of global value names that should be internalized.</p>

<p>Definition at line 40 of file <a href="/web-llvm/docs/api/files/lib/lib/linker/linkmodules-cpp">LinkModules.cpp</a>.</p>

</div>
</div>

### InternalizeCallback {#a03f44d3f56a41943e704671440442c47}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::function&lt;void(Module &amp;, const StringSet&lt;&gt; &amp;)&gt; anonymous{LinkModules.cpp}::ModuleLinker::InternalizeCallback</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> that will perform the actual internalization.</p>


<p>The reason for a callback is that the linker cannot call internalizeModule without creating a circular dependency between IPO and the linker.</p>


<p>Definition at line 45 of file <a href="/web-llvm/docs/api/files/lib/lib/linker/linkmodules-cpp">LinkModules.cpp</a>.</p>

</div>
</div>

### LazyComdatMembers {#ade720e80aca8161eab16f7eaa8a12202}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;const Comdat *, std::vector&lt;GlobalValue *&gt; &gt; anonymous{LinkModules.cpp}::ModuleLinker::LazyComdatMembers</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 77 of file <a href="/web-llvm/docs/api/files/lib/lib/linker/linkmodules-cpp">LinkModules.cpp</a>.</p>

</div>
</div>

### Mover {#a6b0fee53afb3c553779bd32ef30f826e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IRMover&amp; anonymous{LinkModules.cpp}::ModuleLinker::Mover</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 31 of file <a href="/web-llvm/docs/api/files/lib/lib/linker/linkmodules-cpp">LinkModules.cpp</a>.</p>

</div>
</div>

### SrcM {#ae2fad6c05cee0fe1cae6c2d911dc37ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;Module&gt; anonymous{LinkModules.cpp}::ModuleLinker::SrcM</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 32 of file <a href="/web-llvm/docs/api/files/lib/lib/linker/linkmodules-cpp">LinkModules.cpp</a>.</p>

</div>
</div>

### ValuesToLink {#a10a160a855d72c90ce373badf7145c4e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SetVector&lt;GlobalValue *&gt; anonymous{LinkModules.cpp}::ModuleLinker::ValuesToLink</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 34 of file <a href="/web-llvm/docs/api/files/lib/lib/linker/linkmodules-cpp">LinkModules.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/linker/linkmodules-cpp">LinkModules.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>

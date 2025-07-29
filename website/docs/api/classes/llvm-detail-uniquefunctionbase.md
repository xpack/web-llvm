---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/detail/uniquefunctionbase
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `UniqueFunctionBase` Class Template



## Declaration

<div class="doxyDeclaration">
template &lt;typename ReturnT, typename... ParamTs&gt;
class llvm::detail::UniqueFunctionBase&lt;ReturnT, ParamTs&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/functionextras-h">llvm/ADT/FunctionExtras.h</a>"
</div>

## Protected Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a48a0a275097ce59913ed5df50a7d1c1c">AdjustedParamT</a> = typename <a href="/web-llvm/docs/api/structs/llvm/detail/uniquefunctionbase/adjustedparamtbase">AdjustedParamTBase</a>&lt; T &gt;::type</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ReturnT, typename... ParamTs&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad288286dc47ebc0627a959b0b73b4f07">CallPtrT</a> = ReturnT(*)(void *CallableAddr, <a href="#a48a0a275097ce59913ed5df50a7d1c1c">AdjustedParamT</a>&lt; ParamTs &gt;... Params)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ReturnT, typename... ParamTs&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a1301d4dd2580808c59e79c5ee0582139">MovePtrT</a> = void(*)(void *LHSCallableAddr, void *RHSCallableAddr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ReturnT, typename... ParamTs&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad1d1a8b2b0bb45c115e6df518cfb1d6d">DestroyPtrT</a> = void(*)(void *CallableAddr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ReturnT, typename... ParamTs&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a5a117f4a6c4ab48db3c863271438cf3c">CallbackPointerUnionT</a> = <a href="/web-llvm/docs/api/classes/llvm/pointerunion">PointerUnion</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/detail/uniquefunctionbase/trivialcallback">TrivialCallback</a> *, <a href="/web-llvm/docs/api/structs/llvm/detail/uniquefunctionbase/nontrivialcallbacks">NonTrivialCallbacks</a> * &gt;</td>
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

## Protected Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename CallableT, typename CalledAsT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a74463d3b6e49c6e6be3baf812d3f2699">UniqueFunctionBase</a> (CallableT Callable, CalledAs&lt; CalledAsT &gt;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ReturnT, typename... ParamTs&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#ad6d450e33cf5fff1101a1e8daabcd2b3">UniqueFunctionBase</a> (UniqueFunctionBase &amp;&amp;RHS) noexcept</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ReturnT, typename... ParamTs&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a2701d4eee17002ff6595f7fcd47d9aef">UniqueFunctionBase</a> ()=default</td>
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

## Protected Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ReturnT, typename... ParamTs&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a288074261a390b844e1bb895827aae96">~UniqueFunctionBase</a> ()</td>
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

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ReturnT, typename... ParamTs&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a5d8012ddf85c38c162988f27aff7bc7f">operator bool</a> () const</td>
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

## Protected Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ReturnT, typename... ParamTs&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/detail/uniquefunctionbase">UniqueFunctionBase</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a47f73fbd1efbe4f17c278a82c5f28e8d">operator=</a> (UniqueFunctionBase &amp;&amp;RHS) noexcept</td>
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

## Protected Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ReturnT, typename... ParamTs&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aa0e63512735510d16776a2747b1e7e58">isInlineStorage</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ReturnT, typename... ParamTs&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#add06faf52c862048cf73fdb69d5a8a97">isTrivialCallback</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ReturnT, typename... ParamTs&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#ad288286dc47ebc0627a959b0b73b4f07">CallPtrT</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a21bddfacfc9707c63b8e8595730595c8">getTrivialCallback</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ReturnT, typename... ParamTs&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/detail/uniquefunctionbase/nontrivialcallbacks">NonTrivialCallbacks</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a4c502742d2060acc8ee77cc68a2324d8">getNonTrivialCallbacks</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ReturnT, typename... ParamTs&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#ad288286dc47ebc0627a959b0b73b4f07">CallPtrT</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a0166f36c59bf23f7a969796f3b160120">getCallPtr</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ReturnT, typename... ParamTs&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ab1b846b46f27397e229a73d8bcc3d28c">getCalleePtr</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ReturnT, typename... ParamTs&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a19bc9c6c7407013b940e368a7a5b47d7">getInlineStorage</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ReturnT, typename... ParamTs&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a35fd24c31e8311559a92502bf1167af9">getOutOfLineStorage</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ReturnT, typename... ParamTs&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aa45b5add274f23456e6abc4451798225">getOutOfLineStorageSize</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ReturnT, typename... ParamTs&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac2ee20db0af7f93b577dddb3e9637478">getOutOfLineStorageAlignment</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ReturnT, typename... ParamTs&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a3f042ddd5a6cb8e0cee6575743d53ef7">setOutOfLineStorage</a> (void *Ptr, size_t Size, size_t Alignment)</td>
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

## Protected Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ReturnT, typename... ParamTs&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">union <a href="/web-llvm/docs/api/unions/llvm/detail/uniquefunctionbase/storageuniont">llvm::detail::UniqueFunctionBase::StorageUnionT</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac79f48e58c05b98b47f3a87b53033f87">StorageUnion</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ReturnT, typename... ParamTs&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/pointerintpair">PointerIntPair</a>&lt; <a href="#a5a117f4a6c4ab48db3c863271438cf3c">CallbackPointerUnionT</a>, 1, bool &gt;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a2545f78baa20bc8bf79b87b4bcb0aa4a">CallbackAndInlineFlag</a></td>
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

## Protected Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename CalledAsT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static ReturnT</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aae031d43fe520ab13f26ed4e64d322fc">CallImpl</a> (void *CallableAddr, AdjustedParamT&lt; ParamTs &gt;... Params)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename CallableT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a7d9ae43014e0a34731a02793bae511d2">MoveImpl</a> (void *LHSCallableAddr, void *RHSCallableAddr) noexcept</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename CallableT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a849a2dcfcd3f773ce640d6a1c1df3f5f">DestroyImpl</a> (void *CallableAddr) noexcept</td>
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

## Protected Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ReturnT, typename... ParamTs&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static constexpr size_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#afc8bea8bffe6f12ac46e3a44352f75eb">InlineStorageSize</a> = sizeof(void *) * 3</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ReturnT, typename... ParamTs&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static constexpr size_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#abfd1a5354df0a9dd26a4d41e071595ef">InlineStorageAlign</a> = alignof(void *)</td>
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


<p>Definition at line 80 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/functionextras-h">FunctionExtras.h</a>.</p>


<div class="doxySectionDef">

## Protected Member Typedefs

### AdjustedParamT {#a48a0a275097ce59913ed5df50a7d1c1c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::detail::UniqueFunctionBase&lt; ReturnT, ParamTs &gt;::AdjustedParamT =  typename AdjustedParamTBase&lt;T&gt;::type</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 118 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/functionextras-h">FunctionExtras.h</a>.</p>

</div>
</div>

### CallbackPointerUnionT {#a5a117f4a6c4ab48db3c863271438cf3c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ReturnT, typename... ParamTs&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::detail::UniqueFunctionBase&lt; ReturnT, ParamTs &gt;::CallbackPointerUnionT = 
      PointerUnion&lt;TrivialCallback *, NonTrivialCallbacks *&gt;</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 144 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/functionextras-h">FunctionExtras.h</a>.</p>

</div>
</div>

### CallPtrT {#ad288286dc47ebc0627a959b0b73b4f07}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ReturnT, typename... ParamTs&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::detail::UniqueFunctionBase&lt; ReturnT, ParamTs &gt;::CallPtrT =  ReturnT (*)(void *CallableAddr,
                               AdjustedParamT&lt;ParamTs&gt;... Params)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 122 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/functionextras-h">FunctionExtras.h</a>.</p>

</div>
</div>

### DestroyPtrT {#ad1d1a8b2b0bb45c115e6df518cfb1d6d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ReturnT, typename... ParamTs&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::detail::UniqueFunctionBase&lt; ReturnT, ParamTs &gt;::DestroyPtrT =  void (*)(void *CallableAddr)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 125 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/functionextras-h">FunctionExtras.h</a>.</p>

</div>
</div>

### MovePtrT {#a1301d4dd2580808c59e79c5ee0582139}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ReturnT, typename... ParamTs&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::detail::UniqueFunctionBase&lt; ReturnT, ParamTs &gt;::MovePtrT =  void (*)(void *LHSCallableAddr, void *RHSCallableAddr)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 124 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/functionextras-h">FunctionExtras.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Constructors

### UniqueFunctionBase() {#a74463d3b6e49c6e6be3baf812d3f2699}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename CallableT, typename CalledAsT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::detail::UniqueFunctionBase&lt; ReturnT, ParamTs &gt;::UniqueFunctionBase (CallableT Callable, <a href="/web-llvm/docs/api/structs/llvm/detail/uniquefunctionbase/calledas">CalledAs</a>&lt; CalledAsT &gt;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 263 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/functionextras-h">FunctionExtras.h</a>.</p>

</div>
</div>

### UniqueFunctionBase() {#ad6d450e33cf5fff1101a1e8daabcd2b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ReturnT, typename... ParamTs&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::detail::UniqueFunctionBase&lt; ReturnT, ParamTs &gt;::UniqueFunctionBase (<a href="/web-llvm/docs/api/classes/llvm/detail/uniquefunctionbase">UniqueFunctionBase</a> &amp;&amp; RHS)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel noexcept">noexcept</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 299 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/functionextras-h">FunctionExtras.h</a>.</p>

</div>
</div>

### UniqueFunctionBase() {#a2701d4eee17002ff6595f7fcd47d9aef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ReturnT, typename... ParamTs&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::detail::UniqueFunctionBase&lt; ReturnT, ParamTs &gt;::UniqueFunctionBase ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 343 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/functionextras-h">FunctionExtras.h</a>.</p>


<p>Referenced by <a href="#a47f73fbd1efbe4f17c278a82c5f28e8d">llvm::detail::UniqueFunctionBase&lt; R, P... &gt;::operator=</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Destructor

### \~UniqueFunctionBase() {#a288074261a390b844e1bb895827aae96}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ReturnT, typename... ParamTs&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::detail::UniqueFunctionBase&lt; ReturnT, ParamTs &gt;::~UniqueFunctionBase ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 283 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/functionextras-h">FunctionExtras.h</a>.</p>


<p>Referenced by <a href="#a47f73fbd1efbe4f17c278a82c5f28e8d">llvm::detail::UniqueFunctionBase&lt; R, P... &gt;::operator=</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator bool() {#a5d8012ddf85c38c162988f27aff7bc7f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ReturnT, typename... ParamTs&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::detail::UniqueFunctionBase&lt; ReturnT, ParamTs &gt;::operator bool ()</td>
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



<p>Definition at line 346 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/functionextras-h">FunctionExtras.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Operators

### operator=() {#a47f73fbd1efbe4f17c278a82c5f28e8d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ReturnT, typename... ParamTs&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">UniqueFunctionBase &amp; llvm::detail::UniqueFunctionBase&lt; ReturnT, ParamTs &gt;::operator= (<a href="/web-llvm/docs/api/classes/llvm/detail/uniquefunctionbase">UniqueFunctionBase</a> &amp;&amp; RHS)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel noexcept">noexcept</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 331 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/functionextras-h">FunctionExtras.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### getCalleePtr() {#ab1b846b46f27397e229a73d8bcc3d28c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ReturnT, typename... ParamTs&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void * llvm::detail::UniqueFunctionBase&lt; ReturnT, ParamTs &gt;::getCalleePtr ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 199 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/functionextras-h">FunctionExtras.h</a>.</p>

</div>
</div>

### getCallPtr() {#a0166f36c59bf23f7a969796f3b160120}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ReturnT, typename... ParamTs&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CallPtrT llvm::detail::UniqueFunctionBase&lt; ReturnT, ParamTs &gt;::getCallPtr ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 188 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/functionextras-h">FunctionExtras.h</a>.</p>

</div>
</div>

### getInlineStorage() {#a19bc9c6c7407013b940e368a7a5b47d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ReturnT, typename... ParamTs&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void * llvm::detail::UniqueFunctionBase&lt; ReturnT, ParamTs &gt;::getInlineStorage ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 202 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/functionextras-h">FunctionExtras.h</a>.</p>


<p>Referenced by <a href="#ab1b846b46f27397e229a73d8bcc3d28c">llvm::detail::UniqueFunctionBase&lt; R, P... &gt;::getCalleePtr</a>, <a href="#a74463d3b6e49c6e6be3baf812d3f2699">llvm::detail::UniqueFunctionBase&lt; R, P... &gt;::UniqueFunctionBase</a>, <a href="#ad6d450e33cf5fff1101a1e8daabcd2b3">llvm::detail::UniqueFunctionBase&lt; R, P... &gt;::UniqueFunctionBase</a> and <a href="#a288074261a390b844e1bb895827aae96">llvm::detail::UniqueFunctionBase&lt; R, P... &gt;::~UniqueFunctionBase</a>.</p>

</div>
</div>

### getNonTrivialCallbacks() {#a4c502742d2060acc8ee77cc68a2324d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ReturnT, typename... ParamTs&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NonTrivialCallbacks * llvm::detail::UniqueFunctionBase&lt; ReturnT, ParamTs &gt;::getNonTrivialCallbacks ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 184 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/functionextras-h">FunctionExtras.h</a>.</p>


<p>Referenced by <a href="#a0166f36c59bf23f7a969796f3b160120">llvm::detail::UniqueFunctionBase&lt; R, P... &gt;::getCallPtr</a>, <a href="#ad6d450e33cf5fff1101a1e8daabcd2b3">llvm::detail::UniqueFunctionBase&lt; R, P... &gt;::UniqueFunctionBase</a> and <a href="#a288074261a390b844e1bb895827aae96">llvm::detail::UniqueFunctionBase&lt; R, P... &gt;::~UniqueFunctionBase</a>.</p>

</div>
</div>

### getOutOfLineStorage() {#a35fd24c31e8311559a92502bf1167af9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ReturnT, typename... ParamTs&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void * llvm::detail::UniqueFunctionBase&lt; ReturnT, ParamTs &gt;::getOutOfLineStorage ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 203 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/functionextras-h">FunctionExtras.h</a>.</p>


<p>Referenced by <a href="#ab1b846b46f27397e229a73d8bcc3d28c">llvm::detail::UniqueFunctionBase&lt; R, P... &gt;::getCalleePtr</a> and <a href="#a288074261a390b844e1bb895827aae96">llvm::detail::UniqueFunctionBase&lt; R, P... &gt;::~UniqueFunctionBase</a>.</p>

</div>
</div>

### getOutOfLineStorageAlignment() {#ac2ee20db0af7f93b577dddb3e9637478}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ReturnT, typename... ParamTs&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::detail::UniqueFunctionBase&lt; ReturnT, ParamTs &gt;::getOutOfLineStorageAlignment ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 210 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/functionextras-h">FunctionExtras.h</a>.</p>


<p>Referenced by <a href="#a288074261a390b844e1bb895827aae96">llvm::detail::UniqueFunctionBase&lt; R, P... &gt;::~UniqueFunctionBase</a>.</p>

</div>
</div>

### getOutOfLineStorageSize() {#aa45b5add274f23456e6abc4451798225}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ReturnT, typename... ParamTs&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::detail::UniqueFunctionBase&lt; ReturnT, ParamTs &gt;::getOutOfLineStorageSize ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 207 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/functionextras-h">FunctionExtras.h</a>.</p>


<p>Referenced by <a href="#a288074261a390b844e1bb895827aae96">llvm::detail::UniqueFunctionBase&lt; R, P... &gt;::~UniqueFunctionBase</a>.</p>

</div>
</div>

### getTrivialCallback() {#a21bddfacfc9707c63b8e8595730595c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ReturnT, typename... ParamTs&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CallPtrT llvm::detail::UniqueFunctionBase&lt; ReturnT, ParamTs &gt;::getTrivialCallback ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 180 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/functionextras-h">FunctionExtras.h</a>.</p>


<p>Referenced by <a href="#a0166f36c59bf23f7a969796f3b160120">llvm::detail::UniqueFunctionBase&lt; R, P... &gt;::getCallPtr</a>.</p>

</div>
</div>

### isInlineStorage() {#aa0e63512735510d16776a2747b1e7e58}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ReturnT, typename... ParamTs&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::detail::UniqueFunctionBase&lt; ReturnT, ParamTs &gt;::isInlineStorage ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 174 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/functionextras-h">FunctionExtras.h</a>.</p>


<p>Referenced by <a href="#ab1b846b46f27397e229a73d8bcc3d28c">llvm::detail::UniqueFunctionBase&lt; R, P... &gt;::getCalleePtr</a>, <a href="#ad6d450e33cf5fff1101a1e8daabcd2b3">llvm::detail::UniqueFunctionBase&lt; R, P... &gt;::UniqueFunctionBase</a> and <a href="#a288074261a390b844e1bb895827aae96">llvm::detail::UniqueFunctionBase&lt; R, P... &gt;::~UniqueFunctionBase</a>.</p>

</div>
</div>

### isTrivialCallback() {#add06faf52c862048cf73fdb69d5a8a97}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ReturnT, typename... ParamTs&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::detail::UniqueFunctionBase&lt; ReturnT, ParamTs &gt;::isTrivialCallback ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 176 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/functionextras-h">FunctionExtras.h</a>.</p>


<p>Referenced by <a href="#a0166f36c59bf23f7a969796f3b160120">llvm::detail::UniqueFunctionBase&lt; R, P... &gt;::getCallPtr</a>, <a href="#ad6d450e33cf5fff1101a1e8daabcd2b3">llvm::detail::UniqueFunctionBase&lt; R, P... &gt;::UniqueFunctionBase</a> and <a href="#a288074261a390b844e1bb895827aae96">llvm::detail::UniqueFunctionBase&lt; R, P... &gt;::~UniqueFunctionBase</a>.</p>

</div>
</div>

### setOutOfLineStorage() {#a3f042ddd5a6cb8e0cee6575743d53ef7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ReturnT, typename... ParamTs&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::detail::UniqueFunctionBase&lt; ReturnT, ParamTs &gt;::setOutOfLineStorage (void * Ptr, size_t Size, size_t Alignment)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 214 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/functionextras-h">FunctionExtras.h</a>.</p>


<p>Referenced by <a href="#a74463d3b6e49c6e6be3baf812d3f2699">llvm::detail::UniqueFunctionBase&lt; R, P... &gt;::UniqueFunctionBase</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### CallbackAndInlineFlag {#a2545f78baa20bc8bf79b87b4bcb0aa4a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ReturnT, typename... ParamTs&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PointerIntPair&lt;CallbackPointerUnionT, 1, bool&gt; llvm::detail::UniqueFunctionBase&lt; ReturnT, ParamTs &gt;::CallbackAndInlineFlag</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 172 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/functionextras-h">FunctionExtras.h</a>.</p>

</div>
</div>

### StorageUnion {#ac79f48e58c05b98b47f3a87b53033f87}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ReturnT, typename... ParamTs&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">union llvm::detail::UniqueFunctionBase::StorageUnionT llvm::detail::UniqueFunctionBase&lt; ReturnT, ParamTs &gt;::StorageUnion</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 167 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/functionextras-h">FunctionExtras.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Static Functions

### CallImpl() {#aae031d43fe520ab13f26ed4e64d322fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename CalledAsT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ReturnT llvm::detail::UniqueFunctionBase&lt; ReturnT, ParamTs &gt;::CallImpl (void * CallableAddr, <a href="#a48a0a275097ce59913ed5df50a7d1c1c">AdjustedParamT</a>&lt; ParamTs &gt;... Params)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 219 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/functionextras-h">FunctionExtras.h</a>.</p>

</div>
</div>

### DestroyImpl() {#a849a2dcfcd3f773ce640d6a1c1df3f5f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename CallableT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::detail::UniqueFunctionBase&lt; ReturnT, ParamTs &gt;::DestroyImpl (void * CallableAddr)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel noexcept">noexcept</span>
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 232 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/functionextras-h">FunctionExtras.h</a>.</p>

</div>
</div>

### MoveImpl() {#a7d9ae43014e0a34731a02793bae511d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename CallableT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::detail::UniqueFunctionBase&lt; ReturnT, ParamTs &gt;::MoveImpl (void * LHSCallableAddr, void * RHSCallableAddr)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel noexcept">noexcept</span>
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 226 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/functionextras-h">FunctionExtras.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Static Attributes

### InlineStorageAlign {#abfd1a5354df0a9dd26a4d41e071595ef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ReturnT, typename... ParamTs&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::detail::UniqueFunctionBase&lt; ReturnT, ParamTs &gt;::InlineStorageAlign = alignof(void *)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 83 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/functionextras-h">FunctionExtras.h</a>.</p>

</div>
</div>

### InlineStorageSize {#afc8bea8bffe6f12ac46e3a44352f75eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ReturnT, typename... ParamTs&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::detail::UniqueFunctionBase&lt; ReturnT, ParamTs &gt;::InlineStorageSize = sizeof(void *) * 3</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/functionextras-h">FunctionExtras.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/functionextras-h">FunctionExtras.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>

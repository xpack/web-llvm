---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/macho/interfacefile
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `InterfaceFile` Class

<p>Defines the interface file. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::MachO::InterfaceFile { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/interfacefile-h">llvm/TextAPI/InterfaceFile.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af9082a5ea0482378b2d9996ece0051a2">const_target_iterator</a> = <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#aa11b903431c1931920939bac6b5293a2">TargetList::const_iterator</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4dc05f5e2bcc9083d06b684e1ae7c960">const_target_range</a> = <a href="/web-llvm/docs/api/classes/llvm/iterator-range">llvm::iterator_range</a>&lt; <a href="#af9082a5ea0482378b2d9996ece0051a2">const_target_iterator</a> &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a610788071fe52b44e928c301c45d96b3">const_filtered_target_iterator</a> = <a href="/web-llvm/docs/api/namespaces/llvm/#a34dde99f929971dfc4e50bb63dd7aecb">llvm::filter_iterator</a>&lt; <a href="#af9082a5ea0482378b2d9996ece0051a2">const_target_iterator</a>, std::function&lt; bool(<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/macho/target">Target</a> &amp;)&gt; &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a27aec5ac89334c4b4849c0bbd0d233f5">const_filtered_target_range</a> = <a href="/web-llvm/docs/api/classes/llvm/iterator-range">llvm::iterator_range</a>&lt; <a href="#a610788071fe52b44e928c301c45d96b3">const_filtered_target_iterator</a> &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3e956c7afe3025fd4b8ad1f898907ef7">const_symbol_range</a> = <a href="/web-llvm/docs/api/classes/llvm/macho/symbolset/#a761ef39a1239ea5f7ddd9d61bcbd7584">SymbolSet::const_symbol_range</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a08c0390d48d2e6447439775d28bea407">const_filtered_symbol_range</a> = <a href="/web-llvm/docs/api/classes/llvm/macho/symbolset/#a20d58047c7be09072ab7f8f3687ec35f">SymbolSet::const_filtered_symbol_range</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8fc9b068b6725661514ff08ec9aa6d39">InterfaceFile</a> (std::unique_ptr&lt; SymbolSet &gt; &amp;&amp;InputSymbols)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a06d5c814691fff5dfc42fe691f03fef6">InterfaceFile</a> ()</td>
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

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a354ab3d4434a65e99fcd8ecb96723950">operator==</a> (const InterfaceFile &amp;O) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The equality is determined by attributes that impact linking compatibilities. <a href="#a354ab3d4434a65e99fcd8ecb96723950">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a428254166d8607c377a0260aa002d2af">operator!=</a> (const InterfaceFile &amp;O) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0d3208f90e8517ef50529430ff911303">setPath</a> (StringRef Path_)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the path from which this file was generated (if applicable). <a href="#a0d3208f90e8517ef50529430ff911303">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0bc7a0b2fd5b9cfd672f5d8a2bf8ddab">getPath</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the path from which this file was generated (if applicable). <a href="#a0bc7a0b2fd5b9cfd672f5d8a2bf8ddab">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa1565e93199222dbc57edcd154e71544">setFileType</a> (FileType Kind)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the file type. <a href="#aa1565e93199222dbc57edcd154e71544">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/macho/#a11849daa1b55a8c00390b349546112e7">FileType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adb0e69a16886a4856bf6da9409aec647">getFileType</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the file type. <a href="#adb0e69a16886a4856bf6da9409aec647">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/macho/architectureset">ArchitectureSet</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac0a60b329ea5a64524cb7edb95bedb99">getArchitectures</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the architectures. <a href="#ac0a60b329ea5a64524cb7edb95bedb99">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/macho/#a69bfa13e6b39228d219413d8fb5f46a2">PlatformSet</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e8933855d98c8bef04806286d21563a">getPlatforms</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the platforms. <a href="#a6e8933855d98c8bef04806286d21563a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a520ae87f35ac8dc8997924c93ff8cde9">addTarget</a> (const Target &amp;Target)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set and add target. <a href="#a520ae87f35ac8dc8997924c93ff8cde9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af0b854c3c50d9b9a18e279c02fe256dc">hasTarget</a> (const Target &amp;Targ) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine if target triple slice exists in file. <a href="#af0b854c3c50d9b9a18e279c02fe256dc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename RangeT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a81441b0bd773a170569f45c0a76f01b7">addTargets</a> (RangeT &amp;&amp;Targets)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set and add targets. <a href="#a81441b0bd773a170569f45c0a76f01b7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a4dc05f5e2bcc9083d06b684e1ae7c960">const_target_range</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a12654c31fc2d200850640a4fb56e706d">targets</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a27aec5ac89334c4b4849c0bbd0d233f5">const_filtered_target_range</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c83b0802e079f9409f0fd4a18a8a3bf">targets</a> (ArchitectureSet Archs) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a80b675b948ed798d4692a7d49d64667d">setInstallName</a> (StringRef InstallName_)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the install name of the library. <a href="#a80b675b948ed798d4692a7d49d64667d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac0d2ccdc079762d27dae1db4358addfa">getInstallName</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the install name of the library. <a href="#ac0d2ccdc079762d27dae1db4358addfa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af36fb2b04b898a3d3a7a1a2db9695d4d">setCurrentVersion</a> (PackedVersion Version)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the current version of the library. <a href="#af36fb2b04b898a3d3a7a1a2db9695d4d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/macho/packedversion">PackedVersion</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa829ad103f7159cab0d31d4490875873">getCurrentVersion</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the current version of the library. <a href="#aa829ad103f7159cab0d31d4490875873">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abeb5e47810569f23338adf0da743b1f1">setCompatibilityVersion</a> (PackedVersion Version)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the compatibility version of the library. <a href="#abeb5e47810569f23338adf0da743b1f1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/macho/packedversion">PackedVersion</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a376081d40831f5188814d7fc16387f53">getCompatibilityVersion</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the compatibility version of the library. <a href="#a376081d40831f5188814d7fc16387f53">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af25936eff97be417dd5f71cdf27fec40">setSwiftABIVersion</a> (uint8_t Version)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the Swift ABI version of the library. <a href="#af25936eff97be417dd5f71cdf27fec40">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint8_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa39943e16ea52fe661e90acd86babaf1">getSwiftABIVersion</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the Swift ABI version of the library. <a href="#aa39943e16ea52fe661e90acd86babaf1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb57d90918d99db12adf2ff372a22421">setTwoLevelNamespace</a> (bool V=true)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Specify if the library uses two-level namespace (or flat namespace). <a href="#afb57d90918d99db12adf2ff372a22421">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a32e6dd694bee297f18ea6a44986ccdf2">isTwoLevelNamespace</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if the library uses two-level namespace. <a href="#a32e6dd694bee297f18ea6a44986ccdf2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a144e94258fe8e42f94d0e25f32d7593e">setOSLibNotForSharedCache</a> (bool V=true)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Specify if the library is an OS library but not shared cache eligible. <a href="#a144e94258fe8e42f94d0e25f32d7593e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e9361c8cba82e446b6666ab0d7bb15e">isOSLibNotForSharedCache</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if the library is an OS library that is not shared cache eligible. <a href="#a2e9361c8cba82e446b6666ab0d7bb15e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adfb121513dcfcacd2834889925802886">setApplicationExtensionSafe</a> (bool V=true)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Specify if the library is application extension safe (or not). <a href="#adfb121513dcfcacd2834889925802886">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a57e27bfd3da85dee8ba0237ec9a2a8d6">isApplicationExtensionSafe</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if the library is application extension safe. <a href="#a57e27bfd3da85dee8ba0237ec9a2a8d6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afc58e0ebbd1c932a41057b129c21a8e9">hasSimulatorSupport</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if the library has simulator support. <a href="#afc58e0ebbd1c932a41057b129c21a8e9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6342a9ea65ca71aa6512b9138a070f90">setSimulatorSupport</a> (bool V=true)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Specify if the library has simulator support. <a href="#a6342a9ea65ca71aa6512b9138a070f90">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3217a2e4d9b7e6850b8db5174e4a42e6">setObjCConstraint</a> (ObjCConstraintType Constraint)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the Objective-C constraint. <a href="#a3217a2e4d9b7e6850b8db5174e4a42e6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/macho/#a6ce55ac03358478c63eaefb8578a7a31">ObjCConstraintType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad8f2ab00f73f81a10d62d08476bfe9fa">getObjCConstraint</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the Objective-C constraint. <a href="#ad8f2ab00f73f81a10d62d08476bfe9fa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a10941e3dbc58d66b627ca35bd19c57e5">addParentUmbrella</a> (const Target &amp;Target_, StringRef Parent)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the parent umbrella frameworks. <a href="#a10941e3dbc58d66b627ca35bd19c57e5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::vector&lt; std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/macho/target">Target</a>, std::string &gt; &gt; &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8a6f031b2ccfdf3c35165c3b70621a69">umbrellas</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the list of Parent Umbrella frameworks. <a href="#a8a6f031b2ccfdf3c35165c3b70621a69">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae36a717235cff5fcda53c3f918cb1309">addAllowableClient</a> (StringRef InstallName, const Target &amp;Target)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add an allowable client. <a href="#ae36a717235cff5fcda53c3f918cb1309">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/macho/interfacefileref">InterfaceFileRef</a> &gt; &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a737a15dbe6f65d3cf626bc14c7237517">allowableClients</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the list of allowable clients. <a href="#a737a15dbe6f65d3cf626bc14c7237517">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0d170d1bef2de5f595849d43fe151a72">addReexportedLibrary</a> (StringRef InstallName, const Target &amp;Target)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add a re-exported library. <a href="#a0d170d1bef2de5f595849d43fe151a72">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/macho/interfacefileref">InterfaceFileRef</a> &gt; &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a92274909dd6de751a00cc114bbd43d23">reexportedLibraries</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the list of re-exported libraries. <a href="#a92274909dd6de751a00cc114bbd43d23">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a02018aeb18e5ddc987320e7dd6200559">addDocument</a> (std::shared_ptr&lt; InterfaceFile &gt; &amp;&amp;Document)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add a library for inlining to top level library. <a href="#a02018aeb18e5ddc987320e7dd6200559">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/macho/interfacefile">InterfaceFile</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a927023e7eeec2359a9925a6c5f489f1c">getParent</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the pointer to parent document if exists or nullptr otherwise. <a href="#a927023e7eeec2359a9925a6c5f489f1c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::vector&lt; std::shared_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/macho/interfacefile">InterfaceFile</a> &gt; &gt; &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a85714260cd0ffc7ada7c34ba55817ac5">documents</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the list of inlined libraries. <a href="#a85714260cd0ffc7ada7c34ba55817ac5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab76b5e3aa3f400f3bbe3dbdd876149d8">addRPath</a> (StringRef RPath, const Target &amp;InputTarget)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the runpath search paths. <a href="#ab76b5e3aa3f400f3bbe3dbdd876149d8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::vector&lt; std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/macho/target">Target</a>, std::string &gt; &gt; &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a708eaed3491ddeed16e480266efcb15b">rpaths</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the list of runpath search paths. <a href="#a708eaed3491ddeed16e480266efcb15b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/macho/symbol">Symbol</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a00d49600189cb1e9273b79f30bdb410d">getSymbol</a> (EncodeKind Kind, StringRef Name, ObjCIFSymbolKind ObjCIF=ObjCIFSymbolKind::None) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get symbol if exists in file. <a href="#a00d49600189cb1e9273b79f30bdb410d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a7b74e1866e47a4fd8b2b2e110563f50a">addSymbol</a> (EncodeKind Kind, StringRef Name, RangeT &amp;&amp;Targets, SymbolFlags Flags=SymbolFlags::None)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add a symbol to the symbols list or extend an existing one. <a href="#a7b74e1866e47a4fd8b2b2e110563f50a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f7a0d2cf23ec22dadab0f748ab2f547">addSymbol</a> (EncodeKind Kind, StringRef Name, TargetList &amp;&amp;Targets, SymbolFlags Flags=SymbolFlags::None)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add <a href="/web-llvm/docs/api/classes/llvm/macho/symbol">Symbol</a> with multiple targets. <a href="#a5f7a0d2cf23ec22dadab0f748ab2f547">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac682fd25615abcfd3f83719dc3f5a79">addSymbol</a> (EncodeKind Kind, StringRef Name, Target &amp;Target, SymbolFlags Flags=SymbolFlags::None)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add <a href="/web-llvm/docs/api/classes/llvm/macho/symbol">Symbol</a> with single target. <a href="#aac682fd25615abcfd3f83719dc3f5a79">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3ef30ff9af67c641afbe1188bafda172">symbolsCount</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get size of symbol set. <a href="#a3ef30ff9af67c641afbe1188bafda172">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a3e956c7afe3025fd4b8ad1f898907ef7">const_symbol_range</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa0ab6da7a2a23d9ba2af198def5921d2">symbols</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a08c0390d48d2e6447439775d28bea407">const_filtered_symbol_range</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54ddf1f9d25541051d221c909aabb697">exports</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a08c0390d48d2e6447439775d28bea407">const_filtered_symbol_range</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a304563f018bdfa8e3c5557022eda7dbd">reexports</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a08c0390d48d2e6447439775d28bea407">const_filtered_symbol_range</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aba35d7a6ac48695eb407bd729e6152dc">undefineds</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">llvm::Expected</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/macho/interfacefile">InterfaceFile</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af93c3d5e4065c12400adea999f45dd63">extract</a> (Architecture Arch) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Extract architecture slice from Interface. <a href="#af93c3d5e4065c12400adea999f45dd63">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">llvm::Expected</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/macho/interfacefile">InterfaceFile</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a310e207bf104197229a0a5789e294389">remove</a> (Architecture Arch) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remove architecture slice from Interface. <a href="#a310e207bf104197229a0a5789e294389">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">llvm::Expected</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/macho/interfacefile">InterfaceFile</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac6fa009bd0125df8ab474fca27e70c3d">merge</a> (const InterfaceFile *O) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Merge Interfaces for the same library. <a href="#ac6fa009bd0125df8ab474fca27e70c3d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae8b1c0fe1bc3272483c0700c4236e5e3">inlineLibrary</a> (std::shared_ptr&lt; InterfaceFile &gt; Library, bool Overwrite=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Inline reexported library into Interface. <a href="#ae8b1c0fe1bc3272483c0700c4236e5e3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0fb71da1c873d2aedfa32922154d7d39">setFromBinaryAttrs</a> (const RecordsSlice::BinaryAttrs &amp;BA, const Target &amp;Targ)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set <a href="/web-llvm/docs/api/classes/llvm/macho/interfacefile">InterfaceFile</a> properties from pre-gathered binary attributes, if they are not set already. <a href="#a0fb71da1c873d2aedfa32922154d7d39">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4cb6f61f5abe000a534de6ccb531ce8f">copyString</a> (StringRef String)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a8e612822d4ba7bb36c9c79582a567108">llvm::BumpPtrAllocator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a954857c3e9fd5edc3950c9469d132a1d">Allocator</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/macho/#ac089ad7e9e01c5183ce6ba196ed6a9ba">TargetList</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6af9cb4415df3cd43ee70c4e38934bbc">Targets</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaf52107f123a1232284c99e33dea71ba">Path</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/macho/#a11849daa1b55a8c00390b349546112e7">FileType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae9cdd04f98f330c297eeb3bfb7e31af4">FileKind</a> {<a href="/web-llvm/docs/api/namespaces/llvm/macho/#a11849daa1b55a8c00390b349546112e7a48d53340ae80e1c1862548611e92c864">FileType::Invalid</a>}</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa38539afd0fa8488cb6b432c2b17906c">InstallName</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/macho/packedversion">PackedVersion</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa1f3314f32e6f7231270cbb0d70818ad">CurrentVersion</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/macho/packedversion">PackedVersion</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a61b40526ddfb90eb60b615e6b8c9700e">CompatibilityVersion</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint8_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad9f9841301e73d846d7df906e19257ba">SwiftABIVersion</a> {0}</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e82837afa80e65dbd79b08330f64198">IsTwoLevelNamespace</a> {false}</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c23387c41b4ee30eef28c0ab8892b73">IsOSLibNotForSharedCache</a> {false}</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac44924bc55af463164dc4e1828ed78a">IsAppExtensionSafe</a> {false}</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7020feb2b0c3d943eda3e09314452600">HasSimSupport</a> {false}</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/macho/#a6ce55ac03358478c63eaefb8578a7a31">ObjCConstraintType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#add1f89225244516f029f81265ba6df1d">ObjcConstraint</a> = <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a6ce55ac03358478c63eaefb8578a7a31a6adf97f83acf6453d4a6a4b1070f3754">ObjCConstraintType::None</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/macho/target">Target</a>, std::string &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ef5832419dc272a19e95fdaaa39b41c">ParentUmbrellas</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/macho/interfacefileref">InterfaceFileRef</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b98dbc5c173e4e7891d000d67b71f06">AllowableClients</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/macho/interfacefileref">InterfaceFileRef</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9991b254c878fd373fac608799450969">ReexportedLibraries</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; std::shared_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/macho/interfacefile">InterfaceFile</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a15c8559c794df56109190c7a4d17446c">Documents</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/macho/target">Target</a>, std::string &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b4e88a025841c069a83e2e31872aab9">RPaths</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/macho/symbolset">SymbolSet</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a511122c64d266d086c2abfca3e54789b">SymbolsSet</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/macho/interfacefile">InterfaceFile</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a28fa462d0789a0d561326f1a8ea6ae46">Parent</a> = nullptr</td>
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

<p>Defines the interface file.</p>

<p>Definition at line 105 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/interfacefile-h">InterfaceFile.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### const\_filtered\_symbol\_range {#a08c0390d48d2e6447439775d28bea407}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::MachO::InterfaceFile::const_filtered_symbol_range =  SymbolSet::const_filtered_symbol_range</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 361 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/interfacefile-h">InterfaceFile.h</a>.</p>

</div>
</div>

### const\_filtered\_target\_iterator {#a610788071fe52b44e928c301c45d96b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::MachO::InterfaceFile::const_filtered_target_iterator = 
      llvm::filter_iterator&lt;const_target_iterator,
                            std::function&lt;bool(const Target &amp;)&gt;&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 172 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/interfacefile-h">InterfaceFile.h</a>.</p>

</div>
</div>

### const\_filtered\_target\_range {#a27aec5ac89334c4b4849c0bbd0d233f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::MachO::InterfaceFile::const_filtered_target_range = 
      llvm::iterator_range&lt;const_filtered_target_iterator&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 175 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/interfacefile-h">InterfaceFile.h</a>.</p>

</div>
</div>

### const\_symbol\_range {#a3e956c7afe3025fd4b8ad1f898907ef7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::MachO::InterfaceFile::const_symbol_range =  SymbolSet::const_symbol_range</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 360 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/interfacefile-h">InterfaceFile.h</a>.</p>

</div>
</div>

### const\_target\_iterator {#af9082a5ea0482378b2d9996ece0051a2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::MachO::InterfaceFile::const_target_iterator =  TargetList::const_iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 168 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/interfacefile-h">InterfaceFile.h</a>.</p>

</div>
</div>

### const\_target\_range {#a4dc05f5e2bcc9083d06b684e1ae7c960}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::MachO::InterfaceFile::const_target_range =  llvm::iterator_range&lt;const_target_iterator&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 169 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/interfacefile-h">InterfaceFile.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### InterfaceFile() {#a8fc9b068b6725661514ff08ec9aa6d39}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MachO::InterfaceFile::InterfaceFile (std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/macho/symbolset">SymbolSet</a> &gt; &amp;&amp; InputSymbols)</td>
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



<p>Definition at line 107 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/interfacefile-h">InterfaceFile.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a>.</p>


<p>Referenced by <a href="#a927023e7eeec2359a9925a6c5f489f1c">getParent</a>, <a href="#ac6fa009bd0125df8ab474fca27e70c3d">merge</a>, <a href="#a428254166d8607c377a0260aa002d2af">operator!=</a> and <a href="#a354ab3d4434a65e99fcd8ecb96723950">operator==</a>.</p>

</div>
</div>

### InterfaceFile() {#a06d5c814691fff5dfc42fe691f03fef6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MachO::InterfaceFile::InterfaceFile ()</td>
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



<p>Definition at line 110 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/interfacefile-h">InterfaceFile.h</a>.</p>


<p>Referenced by <a href="#af93c3d5e4065c12400adea999f45dd63">extract</a>, <a href="#ac6fa009bd0125df8ab474fca27e70c3d">merge</a> and <a href="#a310e207bf104197229a0a5789e294389">remove</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator!=() {#a428254166d8607c377a0260aa002d2af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachO::InterfaceFile::operator!= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/macho/interfacefile">InterfaceFile</a> &amp; O)</td>
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



<p>Definition at line 417 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/interfacefile-h">InterfaceFile.h</a>.</p>


<p>Reference <a href="#a8fc9b068b6725661514ff08ec9aa6d39">InterfaceFile</a>.</p>

</div>
</div>

### operator==() {#a354ab3d4434a65e99fcd8ecb96723950}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool InterfaceFile::operator== (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/macho/interfacefile">InterfaceFile</a> &amp; O)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The equality is determined by attributes that impact linking compatibilities.</p>


<p>Path, &amp; FileKind are irrelevant since these by itself should not impact linking. This is an expensive operation.</p>


<p>Declaration at line 415 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/interfacefile-h">InterfaceFile.h</a>, definition at line 395 of file <a href="/web-llvm/docs/api/files/lib/lib/textapi/interfacefile-cpp">InterfaceFile.cpp</a>.</p>


<p>References <a href="#a8fc9b068b6725661514ff08ec9aa6d39">InterfaceFile</a>, <a href="/web-llvm/docs/api/files/lib/lib/textapi/interfacefile-cpp/#a798ac21e4c1530b1d89f3230118589e2">isYAMLTextStub</a> and <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a831b4360f0de17f260ef2423128e570c">llvm::MachO::mapToPlatformVersionSet</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addAllowableClient() {#ae36a717235cff5fcda53c3f918cb1309}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void InterfaceFile::addAllowableClient (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> InstallName, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/macho/target">Target</a> &amp; Target)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add an allowable client.</p>


<p>Mach-O Dynamic libraries have the concept of allowable clients that are checked during static link time. The name of the application or library that is being generated needs to match one of the allowable clients or the linker refuses to link this library.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">InstallName</td>
<td class="doxyParamItemDescription"><p>The name of the client that is allowed to link this library.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/classes/llvm/macho/target"&gt;Target&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>The target triple for which this applies.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 264 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/interfacefile-h">InterfaceFile.h</a>, definition at line 26 of file <a href="/web-llvm/docs/api/files/lib/lib/textapi/interfacefile-cpp">InterfaceFile.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a30589972136a4ca44da46ea0045de43d">llvm::MachO::addEntry</a>.</p>


<p>Referenced by <a href="#a0fb71da1c873d2aedfa32922154d7d39">setFromBinaryAttrs</a>.</p>

</div>
</div>

### addDocument() {#a02018aeb18e5ddc987320e7dd6200559}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void InterfaceFile::addDocument (std::shared_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/macho/interfacefile">InterfaceFile</a> &gt; &amp;&amp; Document)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add a library for inlining to top level library.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Document</td>
<td class="doxyParamItemDescription"><p>The library to inline with top level library.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 289 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/interfacefile-h">InterfaceFile.h</a>, definition at line 84 of file <a href="/web-llvm/docs/api/files/lib/lib/textapi/interfacefile-cpp">InterfaceFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aa81eb67f09ee4944eaeeddbc54c0c0de">llvm::lower_bound</a>.</p>

</div>
</div>

### addParentUmbrella() {#a10941e3dbc58d66b627ca35bd19c57e5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void InterfaceFile::addParentUmbrella (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/macho/target">Target</a> &amp; Target_, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Parent)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set the parent umbrella frameworks.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Target_</td>
<td class="doxyParamItemDescription"><p>The target applicable to Parent</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Parent</td>
<td class="doxyParamItemDescription"><p>The name of Parent</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 244 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/interfacefile-h">InterfaceFile.h</a>, definition at line 42 of file <a href="/web-llvm/docs/api/files/lib/lib/textapi/interfacefile-cpp">InterfaceFile.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#aa81eb67f09ee4944eaeeddbc54c0c0de">llvm::lower_bound</a>.</p>


<p>Referenced by <a href="#a0fb71da1c873d2aedfa32922154d7d39">setFromBinaryAttrs</a>.</p>

</div>
</div>

### addReexportedLibrary() {#a0d170d1bef2de5f595849d43fe151a72}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void InterfaceFile::addReexportedLibrary (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> InstallName, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/macho/target">Target</a> &amp; Target)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add a re-exported library.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">InstallName</td>
<td class="doxyParamItemDescription"><p>The name of the library to re-export.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/classes/llvm/macho/target"&gt;Target&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>The target triple for which this applies.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 277 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/interfacefile-h">InterfaceFile.h</a>, definition at line 34 of file <a href="/web-llvm/docs/api/files/lib/lib/textapi/interfacefile-cpp">InterfaceFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a30589972136a4ca44da46ea0045de43d">llvm::MachO::addEntry</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a372f87e2cac1c83389c98554dc44806da043d23e54edc5360a7785ae212d1b806">llvm::Lib</a>.</p>


<p>Referenced by <a href="#a0fb71da1c873d2aedfa32922154d7d39">setFromBinaryAttrs</a>.</p>

</div>
</div>

### addRPath() {#ab76b5e3aa3f400f3bbe3dbdd876149d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void InterfaceFile::addRPath (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> RPath, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/macho/target">Target</a> &amp; InputTarget)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set the runpath search paths.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">RPath</td>
<td class="doxyParamItemDescription"><p>The name of runpath.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">InputTarget</td>
<td class="doxyParamItemDescription"><p>The target applicable to runpath search path.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 304 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/interfacefile-h">InterfaceFile.h</a>, definition at line 57 of file <a href="/web-llvm/docs/api/files/lib/lib/textapi/interfacefile-cpp">InterfaceFile.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#aa81eb67f09ee4944eaeeddbc54c0c0de">llvm::lower_bound</a>.</p>

</div>
</div>

### addSymbol() {#a7b74e1866e47a4fd8b2b2e110563f50a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename RangeT, typename ElT = std::remove_reference_t&lt;                                 decltype(*std::begin(std::declval&lt;RangeT&gt;()))&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MachO::InterfaceFile::addSymbol (<a href="/web-llvm/docs/api/namespaces/llvm/macho/#aaa6d69f240a43a0024742035255f09ad">EncodeKind</a> Kind, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, RangeT &amp;&amp; Targets, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#abf69d7d02356968b4f36bc37bcbfe5b4">SymbolFlags</a> Flags=<a href="/web-llvm/docs/api/namespaces/llvm/macho/#abf69d7d02356968b4f36bc37bcbfe5b4a6adf97f83acf6453d4a6a4b1070f3754">SymbolFlags::None</a>)</td>
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

<p>Add a symbol to the symbols list or extend an existing one.</p>

<p>Definition at line 329 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/interfacefile-h">InterfaceFile.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/macho/#abf69d7d02356968b4f36bc37bcbfe5b4a6adf97f83acf6453d4a6a4b1070f3754">llvm::MachO::None</a>.</p>

</div>
</div>

### addSymbol() {#a5f7a0d2cf23ec22dadab0f748ab2f547}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MachO::InterfaceFile::addSymbol (<a href="/web-llvm/docs/api/namespaces/llvm/macho/#aaa6d69f240a43a0024742035255f09ad">EncodeKind</a> Kind, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ac089ad7e9e01c5183ce6ba196ed6a9ba">TargetList</a> &amp;&amp; Targets, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#abf69d7d02356968b4f36bc37bcbfe5b4">SymbolFlags</a> Flags=<a href="/web-llvm/docs/api/namespaces/llvm/macho/#abf69d7d02356968b4f36bc37bcbfe5b4a6adf97f83acf6453d4a6a4b1070f3754">SymbolFlags::None</a>)</td>
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

<p>Add <a href="/web-llvm/docs/api/classes/llvm/macho/symbol">Symbol</a> with multiple targets.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Kind</td>
<td class="doxyParamItemDescription"><p>The kind of global symbol to record.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Name</td>
<td class="doxyParamItemDescription"><p>The name of the symbol.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Targets</td>
<td class="doxyParamItemDescription"><p>The list of targets the symbol is defined in.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Flags</td>
<td class="doxyParamItemDescription"><p>The properties the symbol holds.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 340 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/interfacefile-h">InterfaceFile.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/macho/#abf69d7d02356968b4f36bc37bcbfe5b4a6adf97f83acf6453d4a6a4b1070f3754">llvm::MachO::None</a>.</p>

</div>
</div>

### addSymbol() {#aac682fd25615abcfd3f83719dc3f5a79}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MachO::InterfaceFile::addSymbol (<a href="/web-llvm/docs/api/namespaces/llvm/macho/#aaa6d69f240a43a0024742035255f09ad">EncodeKind</a> Kind, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/classes/llvm/macho/target">Target</a> &amp; Target, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#abf69d7d02356968b4f36bc37bcbfe5b4">SymbolFlags</a> Flags=<a href="/web-llvm/docs/api/namespaces/llvm/macho/#abf69d7d02356968b4f36bc37bcbfe5b4a6adf97f83acf6453d4a6a4b1070f3754">SymbolFlags::None</a>)</td>
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

<p>Add <a href="/web-llvm/docs/api/classes/llvm/macho/symbol">Symbol</a> with single target.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Kind</td>
<td class="doxyParamItemDescription"><p>The kind of global symbol to record.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Name</td>
<td class="doxyParamItemDescription"><p>The name of the symbol.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/classes/llvm/macho/target"&gt;Target&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>The target the symbol is defined in.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Flags</td>
<td class="doxyParamItemDescription"><p>The properties the symbol holds.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 351 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/interfacefile-h">InterfaceFile.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/macho/#abf69d7d02356968b4f36bc37bcbfe5b4a6adf97f83acf6453d4a6a4b1070f3754">llvm::MachO::None</a>.</p>

</div>
</div>

### addTarget() {#a520ae87f35ac8dc8997924c93ff8cde9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void InterfaceFile::addTarget (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/macho/target">Target</a> &amp; Target)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set and add target.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/classes/llvm/macho/target"&gt;Target&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>the target to add into.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 149 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/interfacefile-h">InterfaceFile.h</a>, definition at line 72 of file <a href="/web-llvm/docs/api/files/lib/lib/textapi/interfacefile-cpp">InterfaceFile.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a30589972136a4ca44da46ea0045de43d">llvm::MachO::addEntry</a>.</p>


<p>Referenced by <a href="#a81441b0bd773a170569f45c0a76f01b7">addTargets</a>.</p>

</div>
</div>

### addTargets() {#a81441b0bd773a170569f45c0a76f01b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename RangeT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MachO::InterfaceFile::addTargets (RangeT &amp;&amp; Targets)</td>
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

<p>Set and add targets.</p>


<p>Add the subset of llvm::triples that is supported by Tapi</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Targets</td>
<td class="doxyParamItemDescription"><p>the collection of targets.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 163 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/interfacefile-h">InterfaceFile.h</a>.</p>


<p>Reference <a href="#a520ae87f35ac8dc8997924c93ff8cde9">addTarget</a>.</p>

</div>
</div>

### allowableClients() {#a737a15dbe6f65d3cf626bc14c7237517}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const std::vector&lt; InterfaceFileRef &gt; &amp; llvm::MachO::InterfaceFile::allowableClients ()</td>
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

<p>Get the list of allowable clients.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>Returns a list of allowable clients.</p></dd>
</dl>


<p>Definition at line 269 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/interfacefile-h">InterfaceFile.h</a>.</p>


<p>Referenced by <a href="#af93c3d5e4065c12400adea999f45dd63">extract</a>, <a href="#ac6fa009bd0125df8ab474fca27e70c3d">merge</a> and <a href="#a310e207bf104197229a0a5789e294389">remove</a>.</p>

</div>
</div>

### documents() {#a85714260cd0ffc7ada7c34ba55817ac5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const std::vector&lt; std::shared_ptr&lt; InterfaceFile &gt; &gt; &amp; llvm::MachO::InterfaceFile::documents ()</td>
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

<p>Get the list of inlined libraries.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>Returns a list of the inlined frameworks.</p></dd>
</dl>


<p>Definition at line 297 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/interfacefile-h">InterfaceFile.h</a>.</p>

</div>
</div>

### exports() {#a54ddf1f9d25541051d221c909aabb697}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_filtered_symbol_range llvm::MachO::InterfaceFile::exports ()</td>
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



<p>Definition at line 364 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/interfacefile-h">InterfaceFile.h</a>.</p>

</div>
</div>

### extract() {#af93c3d5e4065c12400adea999f45dd63}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; std::unique_ptr&lt; InterfaceFile &gt; &gt; InterfaceFile::extract (<a href="/web-llvm/docs/api/namespaces/llvm/macho/#a70477e3fc02b7dbfd59604af47d88397">Architecture</a> Arch)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Extract architecture slice from Interface.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Arch</td>
<td class="doxyParamItemDescription"><p>architecture to extract from.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>New <a href="/web-llvm/docs/api/classes/llvm/macho/interfacefile">InterfaceFile</a> with extracted architecture slice.</p></dd>
</dl>


<p>Declaration at line 377 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/interfacefile-h">InterfaceFile.h</a>, definition at line 306 of file <a href="/web-llvm/docs/api/files/lib/lib/textapi/interfacefile-cpp">InterfaceFile.cpp</a>.</p>


<p>References <a href="#a737a15dbe6f65d3cf626bc14c7237517">allowableClients</a>, <a href="/web-llvm/docs/api/classes/llvm/macho/target/#aee9dc737c9effa286ef632263cd45696">llvm::MachO::Target::Arch</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a2a0395d53f0485827bc5782c0b64a4e8">llvm::MachO::getArchitectureName</a>, <a href="#ac0a60b329ea5a64524cb7edb95bedb99">getArchitectures</a>, <a href="#a376081d40831f5188814d7fc16387f53">getCompatibilityVersion</a>, <a href="#aa829ad103f7159cab0d31d4490875873">getCurrentVersion</a>, <a href="#adb0e69a16886a4856bf6da9409aec647">getFileType</a>, <a href="#ac0d2ccdc079762d27dae1db4358addfa">getInstallName</a>, <a href="#a0bc7a0b2fd5b9cfd672f5d8a2bf8ddab">getPath</a>, <a href="#aa39943e16ea52fe661e90acd86babaf1">getSwiftABIVersion</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2b43c21951d0948b34bcf7019949032d">llvm::inconvertibleErrorCode</a>, <a href="#a06d5c814691fff5dfc42fe691f03fef6">InterfaceFile</a>, <a href="#a57e27bfd3da85dee8ba0237ec9a2a8d6">isApplicationExtensionSafe</a>, <a href="#a2e9361c8cba82e446b6666ab0d7bb15e">isOSLibNotForSharedCache</a>, <a href="#a32e6dd694bee297f18ea6a44986ccdf2">isTwoLevelNamespace</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a372f87e2cac1c83389c98554dc44806da043d23e54edc5360a7785ae212d1b806">llvm::Lib</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a>, <a href="#a92274909dd6de751a00cc114bbd43d23">reexportedLibraries</a>, <a href="#a708eaed3491ddeed16e480266efcb15b">rpaths</a>, <a href="#aa0ab6da7a2a23d9ba2af198def5921d2">symbols</a>, <a href="#a12654c31fc2d200850640a4fb56e706d">targets</a> and <a href="#a8a6f031b2ccfdf3c35165c3b70621a69">umbrellas</a>.</p>

</div>
</div>

### getArchitectures() {#ac0a60b329ea5a64524cb7edb95bedb99}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArchitectureSet llvm::MachO::InterfaceFile::getArchitectures ()</td>
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

<p>Get the architectures.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The applicable architectures.</p></dd>
</dl>


<p>Definition at line 137 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/interfacefile-h">InterfaceFile.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ae7b7b478eaa922bb6b4e353e02beb273">llvm::MachO::mapToArchitectureSet</a>.</p>


<p>Referenced by <a href="#af93c3d5e4065c12400adea999f45dd63">extract</a> and <a href="#a310e207bf104197229a0a5789e294389">remove</a>.</p>

</div>
</div>

### getCompatibilityVersion() {#a376081d40831f5188814d7fc16387f53}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PackedVersion llvm::MachO::InterfaceFile::getCompatibilityVersion ()</td>
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

<p>Get the compatibility version of the library.</p>

<p>Definition at line 199 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/interfacefile-h">InterfaceFile.h</a>.</p>


<p>Referenced by <a href="#af93c3d5e4065c12400adea999f45dd63">extract</a>, <a href="#ac6fa009bd0125df8ab474fca27e70c3d">merge</a>, <a href="#a310e207bf104197229a0a5789e294389">remove</a> and <a href="#a0fb71da1c873d2aedfa32922154d7d39">setFromBinaryAttrs</a>.</p>

</div>
</div>

### getCurrentVersion() {#aa829ad103f7159cab0d31d4490875873}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PackedVersion llvm::MachO::InterfaceFile::getCurrentVersion ()</td>
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

<p>Get the current version of the library.</p>

<p>Definition at line 191 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/interfacefile-h">InterfaceFile.h</a>.</p>


<p>Referenced by <a href="#af93c3d5e4065c12400adea999f45dd63">extract</a>, <a href="#ac6fa009bd0125df8ab474fca27e70c3d">merge</a>, <a href="#a310e207bf104197229a0a5789e294389">remove</a> and <a href="#a0fb71da1c873d2aedfa32922154d7d39">setFromBinaryAttrs</a>.</p>

</div>
</div>

### getFileType() {#adb0e69a16886a4856bf6da9409aec647}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FileType llvm::MachO::InterfaceFile::getFileType ()</td>
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

<p>Get the file type.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The file type.</p></dd>
</dl>


<p>Definition at line 132 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/interfacefile-h">InterfaceFile.h</a>.</p>


<p>Referenced by <a href="#af93c3d5e4065c12400adea999f45dd63">extract</a>, <a href="#ac6fa009bd0125df8ab474fca27e70c3d">merge</a>, <a href="#a310e207bf104197229a0a5789e294389">remove</a> and <a href="#a0fb71da1c873d2aedfa32922154d7d39">setFromBinaryAttrs</a>.</p>

</div>
</div>

### getInstallName() {#ac0d2ccdc079762d27dae1db4358addfa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::MachO::InterfaceFile::getInstallName ()</td>
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

<p>Get the install name of the library.</p>

<p>Definition at line 185 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/interfacefile-h">InterfaceFile.h</a>.</p>


<p>Referenced by <a href="#af93c3d5e4065c12400adea999f45dd63">extract</a>, <a href="#ac6fa009bd0125df8ab474fca27e70c3d">merge</a>, <a href="#a310e207bf104197229a0a5789e294389">remove</a> and <a href="#a0fb71da1c873d2aedfa32922154d7d39">setFromBinaryAttrs</a>.</p>

</div>
</div>

### getObjCConstraint() {#ad8f2ab00f73f81a10d62d08476bfe9fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ObjCConstraintType llvm::MachO::InterfaceFile::getObjCConstraint ()</td>
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

<p>Get the Objective-C constraint.</p>

<p>Definition at line 239 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/interfacefile-h">InterfaceFile.h</a>.</p>

</div>
</div>

### getParent() {#a927023e7eeec2359a9925a6c5f489f1c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InterfaceFile * llvm::MachO::InterfaceFile::getParent ()</td>
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

<p>Returns the pointer to parent document if exists or nullptr otherwise.</p>

<p>Definition at line 292 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/interfacefile-h">InterfaceFile.h</a>.</p>


<p>Reference <a href="#a8fc9b068b6725661514ff08ec9aa6d39">InterfaceFile</a>.</p>

</div>
</div>

### getPath() {#a0bc7a0b2fd5b9cfd672f5d8a2bf8ddab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::MachO::InterfaceFile::getPath ()</td>
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

<p>Get the path from which this file was generated (if applicable).</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The path to the source file or empty.</p></dd>
</dl>


<p>Definition at line 119 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/interfacefile-h">InterfaceFile.h</a>.</p>


<p>Referenced by <a href="#af93c3d5e4065c12400adea999f45dd63">extract</a>, <a href="#ac6fa009bd0125df8ab474fca27e70c3d">merge</a>, <a href="#a310e207bf104197229a0a5789e294389">remove</a> and <a href="#a0fb71da1c873d2aedfa32922154d7d39">setFromBinaryAttrs</a>.</p>

</div>
</div>

### getPlatforms() {#a6e8933855d98c8bef04806286d21563a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PlatformSet llvm::MachO::InterfaceFile::getPlatforms ()</td>
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

<p>Get the platforms.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The applicable platforms.</p></dd>
</dl>


<p>Definition at line 144 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/interfacefile-h">InterfaceFile.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a62095b1729447a66edb49f9be4d3c38a">llvm::MachO::mapToPlatformSet</a>.</p>

</div>
</div>

### getSwiftABIVersion() {#aa39943e16ea52fe661e90acd86babaf1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t llvm::MachO::InterfaceFile::getSwiftABIVersion ()</td>
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

<p>Get the Swift ABI version of the library.</p>

<p>Definition at line 205 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/interfacefile-h">InterfaceFile.h</a>.</p>


<p>Referenced by <a href="#af93c3d5e4065c12400adea999f45dd63">extract</a>, <a href="#ac6fa009bd0125df8ab474fca27e70c3d">merge</a>, <a href="#a310e207bf104197229a0a5789e294389">remove</a> and <a href="#a0fb71da1c873d2aedfa32922154d7d39">setFromBinaryAttrs</a>.</p>

</div>
</div>

### getSymbol() {#a00d49600189cb1e9273b79f30bdb410d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; const Symbol * &gt; llvm::MachO::InterfaceFile::getSymbol (<a href="/web-llvm/docs/api/namespaces/llvm/macho/#aaa6d69f240a43a0024742035255f09ad">EncodeKind</a> Kind, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#aa4226b11d55677efb52ce9ab18742568">ObjCIFSymbolKind</a> ObjCIF=<a href="/web-llvm/docs/api/namespaces/llvm/macho/#aa4226b11d55677efb52ce9ab18742568a6adf97f83acf6453d4a6a4b1070f3754">ObjCIFSymbolKind::None</a>)</td>
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

<p>Get symbol if exists in file.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Kind</td>
<td class="doxyParamItemDescription"><p>The kind of global symbol to record.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Name</td>
<td class="doxyParamItemDescription"><p>The name of the symbol.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">ObjCIF</td>
<td class="doxyParamItemDescription"><p>The ObjCInterface symbol type, if applicable.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 319 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/interfacefile-h">InterfaceFile.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/macho/#aa4226b11d55677efb52ce9ab18742568a6adf97f83acf6453d4a6a4b1070f3754">llvm::MachO::None</a>.</p>

</div>
</div>

### hasSimulatorSupport() {#afc58e0ebbd1c932a41057b129c21a8e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachO::InterfaceFile::hasSimulatorSupport ()</td>
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

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if the library has simulator support.</p>

<p>Definition at line 228 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/interfacefile-h">InterfaceFile.h</a>.</p>

</div>
</div>

### hasTarget() {#af0b854c3c50d9b9a18e279c02fe256dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachO::InterfaceFile::hasTarget (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/macho/target">Target</a> &amp; Targ)</td>
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

<p>Determine if target triple slice exists in file.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Targ</td>
<td class="doxyParamItemDescription"><p>the value to find.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 154 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/interfacefile-h">InterfaceFile.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#acd1cd968cb420c82d70926920fcdc7d7">llvm::is_contained</a>.</p>

</div>
</div>

### inlineLibrary() {#ae8b1c0fe1bc3272483c0700c4236e5e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void InterfaceFile::inlineLibrary (std::shared_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/macho/interfacefile">InterfaceFile</a> &gt; Library, bool Overwrite=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Inline reexported library into Interface.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Library</td>
<td class="doxyParamItemDescription"><p>Interface of reexported library.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Overwrite</td>
<td class="doxyParamItemDescription"><p>Whether to overwrite preexisting inlined library.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 400 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/interfacefile-h">InterfaceFile.h</a>, definition at line 97 of file <a href="/web-llvm/docs/api/files/lib/lib/textapi/interfacefile-cpp">InterfaceFile.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#aa81eb67f09ee4944eaeeddbc54c0c0de">llvm::lower_bound</a>.</p>

</div>
</div>

### isApplicationExtensionSafe() {#a57e27bfd3da85dee8ba0237ec9a2a8d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachO::InterfaceFile::isApplicationExtensionSafe ()</td>
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

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if the library is application extension safe.</p>

<p>Definition at line 225 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/interfacefile-h">InterfaceFile.h</a>.</p>


<p>Referenced by <a href="#af93c3d5e4065c12400adea999f45dd63">extract</a>, <a href="#ac6fa009bd0125df8ab474fca27e70c3d">merge</a>, <a href="#a310e207bf104197229a0a5789e294389">remove</a> and <a href="#a0fb71da1c873d2aedfa32922154d7d39">setFromBinaryAttrs</a>.</p>

</div>
</div>

### isOSLibNotForSharedCache() {#a2e9361c8cba82e446b6666ab0d7bb15e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachO::InterfaceFile::isOSLibNotForSharedCache ()</td>
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

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if the library is an OS library that is not shared cache eligible.</p>

<p>Definition at line 219 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/interfacefile-h">InterfaceFile.h</a>.</p>


<p>Referenced by <a href="#af93c3d5e4065c12400adea999f45dd63">extract</a>, <a href="#ac6fa009bd0125df8ab474fca27e70c3d">merge</a>, <a href="#a310e207bf104197229a0a5789e294389">remove</a> and <a href="#a0fb71da1c873d2aedfa32922154d7d39">setFromBinaryAttrs</a>.</p>

</div>
</div>

### isTwoLevelNamespace() {#a32e6dd694bee297f18ea6a44986ccdf2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachO::InterfaceFile::isTwoLevelNamespace ()</td>
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

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if the library uses two-level namespace.</p>

<p>Definition at line 211 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/interfacefile-h">InterfaceFile.h</a>.</p>


<p>Referenced by <a href="#af93c3d5e4065c12400adea999f45dd63">extract</a>, <a href="#ac6fa009bd0125df8ab474fca27e70c3d">merge</a>, <a href="#a310e207bf104197229a0a5789e294389">remove</a> and <a href="#a0fb71da1c873d2aedfa32922154d7d39">setFromBinaryAttrs</a>.</p>

</div>
</div>

### merge() {#ac6fa009bd0125df8ab474fca27e70c3d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; std::unique_ptr&lt; InterfaceFile &gt; &gt; InterfaceFile::merge (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/macho/interfacefile">InterfaceFile</a> * O)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Merge Interfaces for the same library.</p>


<p>The following library attributes must match.</p>


<ul class="doxyList ">
<li>Install name, Current &amp; Compatibility version,</li>
<li>Two-level namespace enablement, and App extension enablement.</li>
</ul>

<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">O</td>
<td class="doxyParamItemDescription"><p>The Interface to merge.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>New Interface File that was merged.</p></dd>
</dl>


<p>Declaration at line 394 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/interfacefile-h">InterfaceFile.h</a>, definition at line 127 of file <a href="/web-llvm/docs/api/files/lib/lib/textapi/interfacefile-cpp">InterfaceFile.cpp</a>.</p>


<p>References <a href="#a737a15dbe6f65d3cf626bc14c7237517">allowableClients</a>, <a href="#a376081d40831f5188814d7fc16387f53">getCompatibilityVersion</a>, <a href="#aa829ad103f7159cab0d31d4490875873">getCurrentVersion</a>, <a href="#adb0e69a16886a4856bf6da9409aec647">getFileType</a>, <a href="#ac0d2ccdc079762d27dae1db4358addfa">getInstallName</a>, <a href="#a0bc7a0b2fd5b9cfd672f5d8a2bf8ddab">getPath</a>, <a href="#aa39943e16ea52fe661e90acd86babaf1">getSwiftABIVersion</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2b43c21951d0948b34bcf7019949032d">llvm::inconvertibleErrorCode</a>, <a href="#a06d5c814691fff5dfc42fe691f03fef6">InterfaceFile</a>, <a href="#a8fc9b068b6725661514ff08ec9aa6d39">InterfaceFile</a>, <a href="#a57e27bfd3da85dee8ba0237ec9a2a8d6">isApplicationExtensionSafe</a>, <a href="#a2e9361c8cba82e446b6666ab0d7bb15e">isOSLibNotForSharedCache</a>, <a href="#a32e6dd694bee297f18ea6a44986ccdf2">isTwoLevelNamespace</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a372f87e2cac1c83389c98554dc44806da043d23e54edc5360a7785ae212d1b806">llvm::Lib</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a>, <a href="#a92274909dd6de751a00cc114bbd43d23">reexportedLibraries</a>, <a href="#a708eaed3491ddeed16e480266efcb15b">rpaths</a>, <a href="#aa0ab6da7a2a23d9ba2af198def5921d2">symbols</a>, <a href="#a12654c31fc2d200850640a4fb56e706d">targets</a> and <a href="#a8a6f031b2ccfdf3c35165c3b70621a69">umbrellas</a>.</p>

</div>
</div>

### reexportedLibraries() {#a92274909dd6de751a00cc114bbd43d23}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const std::vector&lt; InterfaceFileRef &gt; &amp; llvm::MachO::InterfaceFile::reexportedLibraries ()</td>
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

<p>Get the list of re-exported libraries.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>Returns a list of re-exported libraries.</p></dd>
</dl>


<p>Definition at line 282 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/interfacefile-h">InterfaceFile.h</a>.</p>


<p>Referenced by <a href="#af93c3d5e4065c12400adea999f45dd63">extract</a>, <a href="#ac6fa009bd0125df8ab474fca27e70c3d">merge</a> and <a href="#a310e207bf104197229a0a5789e294389">remove</a>.</p>

</div>
</div>

### reexports() {#a304563f018bdfa8e3c5557022eda7dbd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_filtered_symbol_range llvm::MachO::InterfaceFile::reexports ()</td>
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



<p>Definition at line 365 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/interfacefile-h">InterfaceFile.h</a>.</p>

</div>
</div>

### remove() {#a310e207bf104197229a0a5789e294389}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; std::unique_ptr&lt; InterfaceFile &gt; &gt; InterfaceFile::remove (<a href="/web-llvm/docs/api/namespaces/llvm/macho/#a70477e3fc02b7dbfd59604af47d88397">Architecture</a> Arch)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Remove architecture slice from Interface.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Arch</td>
<td class="doxyParamItemDescription"><p>architecture to remove.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>New Interface File with removed architecture slice.</p></dd>
</dl>


<p>Declaration at line 384 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/interfacefile-h">InterfaceFile.h</a>, definition at line 223 of file <a href="/web-llvm/docs/api/files/lib/lib/textapi/interfacefile-cpp">InterfaceFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/macho/architectureset/#a0a93b211f78eb5c97ccc38db119ded83">llvm::MachO::ArchitectureSet::All</a>, <a href="#a737a15dbe6f65d3cf626bc14c7237517">allowableClients</a>, <a href="/web-llvm/docs/api/classes/llvm/macho/target/#aee9dc737c9effa286ef632263cd45696">llvm::MachO::Target::Arch</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a2a0395d53f0485827bc5782c0b64a4e8">llvm::MachO::getArchitectureName</a>, <a href="#ac0a60b329ea5a64524cb7edb95bedb99">getArchitectures</a>, <a href="#a376081d40831f5188814d7fc16387f53">getCompatibilityVersion</a>, <a href="#aa829ad103f7159cab0d31d4490875873">getCurrentVersion</a>, <a href="#adb0e69a16886a4856bf6da9409aec647">getFileType</a>, <a href="#ac0d2ccdc079762d27dae1db4358addfa">getInstallName</a>, <a href="#a0bc7a0b2fd5b9cfd672f5d8a2bf8ddab">getPath</a>, <a href="#aa39943e16ea52fe661e90acd86babaf1">getSwiftABIVersion</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2b43c21951d0948b34bcf7019949032d">llvm::inconvertibleErrorCode</a>, <a href="#a06d5c814691fff5dfc42fe691f03fef6">InterfaceFile</a>, <a href="#a57e27bfd3da85dee8ba0237ec9a2a8d6">isApplicationExtensionSafe</a>, <a href="#a2e9361c8cba82e446b6666ab0d7bb15e">isOSLibNotForSharedCache</a>, <a href="#a32e6dd694bee297f18ea6a44986ccdf2">isTwoLevelNamespace</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a372f87e2cac1c83389c98554dc44806da043d23e54edc5360a7785ae212d1b806">llvm::Lib</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a915d40ccd86e41a5ffd31c941a9f566bad344345f7bda569a935ca90209857a5e">llvm::MachO::NoSuchArchitecture</a>, <a href="#a92274909dd6de751a00cc114bbd43d23">reexportedLibraries</a>, <a href="#aa0ab6da7a2a23d9ba2af198def5921d2">symbols</a>, <a href="#a12654c31fc2d200850640a4fb56e706d">targets</a> and <a href="#a8a6f031b2ccfdf3c35165c3b70621a69">umbrellas</a>.</p>

</div>
</div>

### rpaths() {#a708eaed3491ddeed16e480266efcb15b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const std::vector&lt; std::pair&lt; Target, std::string &gt; &gt; &amp; llvm::MachO::InterfaceFile::rpaths ()</td>
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

<p>Get the list of runpath search paths.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>Returns a list of the rpaths per target.</p></dd>
</dl>


<p>Definition at line 309 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/interfacefile-h">InterfaceFile.h</a>.</p>


<p>Referenced by <a href="#af93c3d5e4065c12400adea999f45dd63">extract</a> and <a href="#ac6fa009bd0125df8ab474fca27e70c3d">merge</a>.</p>

</div>
</div>

### setApplicationExtensionSafe() {#adfb121513dcfcacd2834889925802886}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MachO::InterfaceFile::setApplicationExtensionSafe (bool V=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
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

<p>Specify if the library is application extension safe (or not).</p>

<p>Definition at line 222 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/interfacefile-h">InterfaceFile.h</a>.</p>


<p>Referenced by <a href="#a0fb71da1c873d2aedfa32922154d7d39">setFromBinaryAttrs</a>.</p>

</div>
</div>

### setCompatibilityVersion() {#abeb5e47810569f23338adf0da743b1f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MachO::InterfaceFile::setCompatibilityVersion (<a href="/web-llvm/docs/api/classes/llvm/macho/packedversion">PackedVersion</a> Version)</td>
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

<p>Set the compatibility version of the library.</p>

<p>Definition at line 194 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/interfacefile-h">InterfaceFile.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a689a023f54d38d41f6d952cac41ee538">llvm::Version</a>.</p>


<p>Referenced by <a href="#a0fb71da1c873d2aedfa32922154d7d39">setFromBinaryAttrs</a>.</p>

</div>
</div>

### setCurrentVersion() {#af36fb2b04b898a3d3a7a1a2db9695d4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MachO::InterfaceFile::setCurrentVersion (<a href="/web-llvm/docs/api/classes/llvm/macho/packedversion">PackedVersion</a> Version)</td>
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

<p>Set the current version of the library.</p>

<p>Definition at line 188 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/interfacefile-h">InterfaceFile.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a689a023f54d38d41f6d952cac41ee538">llvm::Version</a>.</p>


<p>Referenced by <a href="#a0fb71da1c873d2aedfa32922154d7d39">setFromBinaryAttrs</a>.</p>

</div>
</div>

### setFileType() {#aa1565e93199222dbc57edcd154e71544}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MachO::InterfaceFile::setFileType (<a href="/web-llvm/docs/api/namespaces/llvm/macho/#a11849daa1b55a8c00390b349546112e7">FileType</a> Kind)</td>
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

<p>Set the file type.</p>


<p>This is used by the YAML writer to identify the specification it should use for writing the file.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Kind</td>
<td class="doxyParamItemDescription"><p>The file type.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 127 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/interfacefile-h">InterfaceFile.h</a>.</p>


<p>Referenced by <a href="#a0fb71da1c873d2aedfa32922154d7d39">setFromBinaryAttrs</a>.</p>

</div>
</div>

### setFromBinaryAttrs() {#a0fb71da1c873d2aedfa32922154d7d39}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void InterfaceFile::setFromBinaryAttrs (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/macho/recordsslice/binaryattrs">RecordsSlice::BinaryAttrs</a> &amp; BA, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/macho/target">Target</a> &amp; Targ)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set <a href="/web-llvm/docs/api/classes/llvm/macho/interfacefile">InterfaceFile</a> properties from pre-gathered binary attributes, if they are not set already.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">BA</td>
<td class="doxyParamItemDescription"><p>Attributes typically represented in load commands.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Targ</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/namespaces/llvm/macho">MachO</a> <a href="/web-llvm/docs/api/classes/llvm/macho/target">Target</a> slice to add attributes to.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 408 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/interfacefile-h">InterfaceFile.h</a>, definition at line 363 of file <a href="/web-llvm/docs/api/files/lib/lib/textapi/interfacefile-cpp">InterfaceFile.cpp</a>.</p>


<p>References <a href="#ae36a717235cff5fcda53c3f918cb1309">addAllowableClient</a>, <a href="#a10941e3dbc58d66b627ca35bd19c57e5">addParentUmbrella</a>, <a href="#a0d170d1bef2de5f595849d43fe151a72">addReexportedLibrary</a>, <a href="/web-llvm/docs/api/structs/llvm/macho/recordsslice/binaryattrs/#a81024cbf017dab2d6a48b216ab5edc25">llvm::MachO::RecordsSlice::BinaryAttrs::AllowableClients</a>, <a href="/web-llvm/docs/api/structs/llvm/macho/recordsslice/binaryattrs/#af4a0ccfae081ac901add6ef73c7eb0aa">llvm::MachO::RecordsSlice::BinaryAttrs::AppExtensionSafe</a>, <a href="/web-llvm/docs/api/structs/llvm/macho/recordsslice/binaryattrs/#aad321229637913933a45aa02617e62e0">llvm::MachO::RecordsSlice::BinaryAttrs::CompatVersion</a>, <a href="/web-llvm/docs/api/structs/llvm/macho/recordsslice/binaryattrs/#ad5cee5a9fb49a5867fcd54ee7e88e548">llvm::MachO::RecordsSlice::BinaryAttrs::CurrentVersion</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2dc80c585ad5882da8cae7b5968f7e74">llvm::StringRef::empty</a>, <a href="/web-llvm/docs/api/structs/llvm/macho/recordsslice/binaryattrs/#a7290eabd65ce37b00b32ce88ef3d3aca">llvm::MachO::RecordsSlice::BinaryAttrs::File</a>, <a href="#a376081d40831f5188814d7fc16387f53">getCompatibilityVersion</a>, <a href="#aa829ad103f7159cab0d31d4490875873">getCurrentVersion</a>, <a href="#adb0e69a16886a4856bf6da9409aec647">getFileType</a>, <a href="#ac0d2ccdc079762d27dae1db4358addfa">getInstallName</a>, <a href="#a0bc7a0b2fd5b9cfd672f5d8a2bf8ddab">getPath</a>, <a href="#aa39943e16ea52fe661e90acd86babaf1">getSwiftABIVersion</a>, <a href="/web-llvm/docs/api/structs/llvm/macho/recordsslice/binaryattrs/#a434332d2b7a638eca4c5671fca0ccf00">llvm::MachO::RecordsSlice::BinaryAttrs::InstallName</a>, <a href="#a57e27bfd3da85dee8ba0237ec9a2a8d6">isApplicationExtensionSafe</a>, <a href="#a2e9361c8cba82e446b6666ab0d7bb15e">isOSLibNotForSharedCache</a>, <a href="#a32e6dd694bee297f18ea6a44986ccdf2">isTwoLevelNamespace</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a372f87e2cac1c83389c98554dc44806da043d23e54edc5360a7785ae212d1b806">llvm::Lib</a>, <a href="/web-llvm/docs/api/structs/llvm/macho/recordsslice/binaryattrs/#af3aef3a142360fab348e7c211311fdd0">llvm::MachO::RecordsSlice::BinaryAttrs::OSLibNotForSharedCache</a>, <a href="/web-llvm/docs/api/structs/llvm/macho/recordsslice/binaryattrs/#aef0f8473b37cf4b687994e8e5cbe8310">llvm::MachO::RecordsSlice::BinaryAttrs::ParentUmbrella</a>, <a href="/web-llvm/docs/api/structs/llvm/macho/recordsslice/binaryattrs/#afb4e6117247bb52327a93a1f37ca5920">llvm::MachO::RecordsSlice::BinaryAttrs::Path</a>, <a href="/web-llvm/docs/api/structs/llvm/macho/recordsslice/binaryattrs/#a59dd0fb10857db0b4b2f4b9ef08326f4">llvm::MachO::RecordsSlice::BinaryAttrs::RexportedLibraries</a>, <a href="#adfb121513dcfcacd2834889925802886">setApplicationExtensionSafe</a>, <a href="#abeb5e47810569f23338adf0da743b1f1">setCompatibilityVersion</a>, <a href="#af36fb2b04b898a3d3a7a1a2db9695d4d">setCurrentVersion</a>, <a href="#aa1565e93199222dbc57edcd154e71544">setFileType</a>, <a href="#a80b675b948ed798d4692a7d49d64667d">setInstallName</a>, <a href="#a144e94258fe8e42f94d0e25f32d7593e">setOSLibNotForSharedCache</a>, <a href="#a0d3208f90e8517ef50529430ff911303">setPath</a>, <a href="#af25936eff97be417dd5f71cdf27fec40">setSwiftABIVersion</a>, <a href="#afb57d90918d99db12adf2ff372a22421">setTwoLevelNamespace</a>, <a href="/web-llvm/docs/api/structs/llvm/macho/recordsslice/binaryattrs/#a1b414f2228c9a046c8ec214fc511cdb9">llvm::MachO::RecordsSlice::BinaryAttrs::SwiftABI</a> and <a href="/web-llvm/docs/api/structs/llvm/macho/recordsslice/binaryattrs/#aa5506576ce91b6671af573954ad09609">llvm::MachO::RecordsSlice::BinaryAttrs::TwoLevelNamespace</a>.</p>

</div>
</div>

### setInstallName() {#a80b675b948ed798d4692a7d49d64667d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MachO::InterfaceFile::setInstallName (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> InstallName_)</td>
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

<p>Set the install name of the library.</p>

<p>Definition at line 180 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/interfacefile-h">InterfaceFile.h</a>.</p>


<p>Referenced by <a href="#a0fb71da1c873d2aedfa32922154d7d39">setFromBinaryAttrs</a>.</p>

</div>
</div>

### setObjCConstraint() {#a3217a2e4d9b7e6850b8db5174e4a42e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MachO::InterfaceFile::setObjCConstraint (<a href="/web-llvm/docs/api/namespaces/llvm/macho/#a6ce55ac03358478c63eaefb8578a7a31">ObjCConstraintType</a> Constraint)</td>
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

<p>Set the Objective-C constraint.</p>

<p>Definition at line 234 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/interfacefile-h">InterfaceFile.h</a>.</p>

</div>
</div>

### setOSLibNotForSharedCache() {#a144e94258fe8e42f94d0e25f32d7593e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MachO::InterfaceFile::setOSLibNotForSharedCache (bool V=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
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

<p>Specify if the library is an OS library but not shared cache eligible.</p>

<p>Definition at line 214 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/interfacefile-h">InterfaceFile.h</a>.</p>


<p>Referenced by <a href="#a0fb71da1c873d2aedfa32922154d7d39">setFromBinaryAttrs</a>.</p>

</div>
</div>

### setPath() {#a0d3208f90e8517ef50529430ff911303}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MachO::InterfaceFile::setPath (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Path_)</td>
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

<p>Set the path from which this file was generated (if applicable).</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Path_</td>
<td class="doxyParamItemDescription"><p>The path to the source file.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 114 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/interfacefile-h">InterfaceFile.h</a>.</p>


<p>Referenced by <a href="#a0fb71da1c873d2aedfa32922154d7d39">setFromBinaryAttrs</a>.</p>

</div>
</div>

### setSimulatorSupport() {#a6342a9ea65ca71aa6512b9138a070f90}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MachO::InterfaceFile::setSimulatorSupport (bool V=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
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

<p>Specify if the library has simulator support.</p>

<p>Definition at line 231 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/interfacefile-h">InterfaceFile.h</a>.</p>

</div>
</div>

### setSwiftABIVersion() {#af25936eff97be417dd5f71cdf27fec40}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MachO::InterfaceFile::setSwiftABIVersion (uint8_t Version)</td>
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

<p>Set the Swift ABI version of the library.</p>

<p>Definition at line 202 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/interfacefile-h">InterfaceFile.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a689a023f54d38d41f6d952cac41ee538">llvm::Version</a>.</p>


<p>Referenced by <a href="#a0fb71da1c873d2aedfa32922154d7d39">setFromBinaryAttrs</a>.</p>

</div>
</div>

### setTwoLevelNamespace() {#afb57d90918d99db12adf2ff372a22421}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MachO::InterfaceFile::setTwoLevelNamespace (bool V=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
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

<p>Specify if the library uses two-level namespace (or flat namespace).</p>

<p>Definition at line 208 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/interfacefile-h">InterfaceFile.h</a>.</p>


<p>Referenced by <a href="#a0fb71da1c873d2aedfa32922154d7d39">setFromBinaryAttrs</a>.</p>

</div>
</div>

### symbols() {#aa0ab6da7a2a23d9ba2af198def5921d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_symbol_range llvm::MachO::InterfaceFile::symbols ()</td>
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



<p>Definition at line 363 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/interfacefile-h">InterfaceFile.h</a>.</p>


<p>Referenced by <a href="#af93c3d5e4065c12400adea999f45dd63">extract</a>, <a href="#ac6fa009bd0125df8ab474fca27e70c3d">merge</a> and <a href="#a310e207bf104197229a0a5789e294389">remove</a>.</p>

</div>
</div>

### symbolsCount() {#a3ef30ff9af67c641afbe1188bafda172}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::MachO::InterfaceFile::symbolsCount ()</td>
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

<p>Get size of symbol set.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The number of symbols the file holds.</p></dd>
</dl>


<p>Definition at line 358 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/interfacefile-h">InterfaceFile.h</a>.</p>

</div>
</div>

### targets() {#a12654c31fc2d200850640a4fb56e706d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_target_range llvm::MachO::InterfaceFile::targets ()</td>
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



<p>Definition at line 170 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/interfacefile-h">InterfaceFile.h</a>.</p>


<p>Referenced by <a href="#af93c3d5e4065c12400adea999f45dd63">extract</a>, <a href="#ac6fa009bd0125df8ab474fca27e70c3d">merge</a> and <a href="#a310e207bf104197229a0a5789e294389">remove</a>.</p>

</div>
</div>

### targets() {#a0c83b0802e079f9409f0fd4a18a8a3bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InterfaceFile::const_filtered_target_range InterfaceFile::targets (<a href="/web-llvm/docs/api/classes/llvm/macho/architectureset">ArchitectureSet</a> Archs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 177 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/interfacefile-h">InterfaceFile.h</a>, definition at line 77 of file <a href="/web-llvm/docs/api/files/lib/lib/textapi/interfacefile-cpp">InterfaceFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/macho/architectureset/#a76b67e4256ae13907721adbb0762ab78">llvm::MachO::ArchitectureSet::has</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a898e9304cf2baf908f4e9b8e32a5f6c3">llvm::make_filter_range</a>.</p>

</div>
</div>

### umbrellas() {#a8a6f031b2ccfdf3c35165c3b70621a69}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const std::vector&lt; std::pair&lt; Target, std::string &gt; &gt; &amp; llvm::MachO::InterfaceFile::umbrellas ()</td>
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

<p>Get the list of Parent Umbrella frameworks.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>Returns a list of target information and install name of parent umbrellas.</p></dd>
</dl>


<p>Definition at line 250 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/interfacefile-h">InterfaceFile.h</a>.</p>


<p>Referenced by <a href="#af93c3d5e4065c12400adea999f45dd63">extract</a>, <a href="#ac6fa009bd0125df8ab474fca27e70c3d">merge</a> and <a href="#a310e207bf104197229a0a5789e294389">remove</a>.</p>

</div>
</div>

### undefineds() {#aba35d7a6ac48695eb407bd729e6152dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_filtered_symbol_range llvm::MachO::InterfaceFile::undefineds ()</td>
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



<p>Definition at line 368 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/interfacefile-h">InterfaceFile.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### copyString() {#a4cb6f61f5abe000a534de6ccb531ce8f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::MachO::InterfaceFile::copyString (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> String)</td>
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



<p>Definition at line 421 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/interfacefile-h">InterfaceFile.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Allocator {#a954857c3e9fd5edc3950c9469d132a1d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::BumpPtrAllocator llvm::MachO::InterfaceFile::Allocator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 420 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/interfacefile-h">InterfaceFile.h</a>.</p>

</div>
</div>

### AllowableClients {#a8b98dbc5c173e4e7891d000d67b71f06}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;InterfaceFileRef&gt; llvm::MachO::InterfaceFile::AllowableClients</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 443 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/interfacefile-h">InterfaceFile.h</a>.</p>

</div>
</div>

### CompatibilityVersion {#a61b40526ddfb90eb60b615e6b8c9700e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PackedVersion llvm::MachO::InterfaceFile::CompatibilityVersion</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 435 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/interfacefile-h">InterfaceFile.h</a>.</p>

</div>
</div>

### CurrentVersion {#aa1f3314f32e6f7231270cbb0d70818ad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PackedVersion llvm::MachO::InterfaceFile::CurrentVersion</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 434 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/interfacefile-h">InterfaceFile.h</a>.</p>

</div>
</div>

### Documents {#a15c8559c794df56109190c7a4d17446c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;std::shared_ptr&lt;InterfaceFile&gt; &gt; llvm::MachO::InterfaceFile::Documents</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 445 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/interfacefile-h">InterfaceFile.h</a>.</p>

</div>
</div>

### FileKind {#ae9cdd04f98f330c297eeb3bfb7e31af4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FileType llvm::MachO::InterfaceFile::FileKind {<a href="/web-llvm/docs/api/namespaces/llvm/macho/#a11849daa1b55a8c00390b349546112e7a48d53340ae80e1c1862548611e92c864">FileType::Invalid</a>}</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 432 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/interfacefile-h">InterfaceFile.h</a>.</p>

</div>
</div>

### HasSimSupport {#a7020feb2b0c3d943eda3e09314452600}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachO::InterfaceFile::HasSimSupport {false}</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 440 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/interfacefile-h">InterfaceFile.h</a>.</p>

</div>
</div>

### InstallName {#aa38539afd0fa8488cb6b432c2b17906c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::MachO::InterfaceFile::InstallName</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 433 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/interfacefile-h">InterfaceFile.h</a>.</p>

</div>
</div>

### IsAppExtensionSafe {#aac44924bc55af463164dc4e1828ed78a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachO::InterfaceFile::IsAppExtensionSafe {false}</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 439 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/interfacefile-h">InterfaceFile.h</a>.</p>

</div>
</div>

### IsOSLibNotForSharedCache {#a0c23387c41b4ee30eef28c0ab8892b73}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachO::InterfaceFile::IsOSLibNotForSharedCache {false}</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 438 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/interfacefile-h">InterfaceFile.h</a>.</p>

</div>
</div>

### IsTwoLevelNamespace {#a7e82837afa80e65dbd79b08330f64198}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachO::InterfaceFile::IsTwoLevelNamespace {false}</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 437 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/interfacefile-h">InterfaceFile.h</a>.</p>

</div>
</div>

### ObjcConstraint {#add1f89225244516f029f81265ba6df1d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ObjCConstraintType llvm::MachO::InterfaceFile::ObjcConstraint = <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a6ce55ac03358478c63eaefb8578a7a31a6adf97f83acf6453d4a6a4b1070f3754">ObjCConstraintType::None</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 441 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/interfacefile-h">InterfaceFile.h</a>.</p>

</div>
</div>

### Parent {#a28fa462d0789a0d561326f1a8ea6ae46}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InterfaceFile* llvm::MachO::InterfaceFile::Parent = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 448 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/interfacefile-h">InterfaceFile.h</a>.</p>

</div>
</div>

### ParentUmbrellas {#a8ef5832419dc272a19e95fdaaa39b41c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;std::pair&lt;Target, std::string&gt; &gt; llvm::MachO::InterfaceFile::ParentUmbrellas</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 442 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/interfacefile-h">InterfaceFile.h</a>.</p>

</div>
</div>

### Path {#aaf52107f123a1232284c99e33dea71ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::MachO::InterfaceFile::Path</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 431 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/interfacefile-h">InterfaceFile.h</a>.</p>

</div>
</div>

### ReexportedLibraries {#a9991b254c878fd373fac608799450969}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;InterfaceFileRef&gt; llvm::MachO::InterfaceFile::ReexportedLibraries</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 444 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/interfacefile-h">InterfaceFile.h</a>.</p>

</div>
</div>

### RPaths {#a8b4e88a025841c069a83e2e31872aab9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;std::pair&lt;Target, std::string&gt; &gt; llvm::MachO::InterfaceFile::RPaths</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 446 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/interfacefile-h">InterfaceFile.h</a>.</p>

</div>
</div>

### SwiftABIVersion {#ad9f9841301e73d846d7df906e19257ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t llvm::MachO::InterfaceFile::SwiftABIVersion {0}</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 436 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/interfacefile-h">InterfaceFile.h</a>.</p>

</div>
</div>

### SymbolsSet {#a511122c64d266d086c2abfca3e54789b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;SymbolSet&gt; llvm::MachO::InterfaceFile::SymbolsSet</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 447 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/interfacefile-h">InterfaceFile.h</a>.</p>

</div>
</div>

### Targets {#a6af9cb4415df3cd43ee70c4e38934bbc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TargetList llvm::MachO::InterfaceFile::Targets</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 430 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/interfacefile-h">InterfaceFile.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/interfacefile-h">InterfaceFile.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/textapi/interfacefile-cpp">InterfaceFile.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>

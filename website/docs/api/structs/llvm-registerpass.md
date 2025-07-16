---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/registerpass
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `RegisterPass` Struct Template Reference

<p>RegisterPass&lt;t&gt; template - This template class is used to notify the system that a <a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a> is available for use, and registers it into the internal database maintained by the <a href="/web-llvm/docs/api/classes/llvm/passmanager">PassManager</a>. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;typename passName&gt;
struct llvm::RegisterPass&lt;passName&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/passsupport-h">llvm/PassSupport.h</a>"
</div>

## Base struct

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/passinfo">PassInfo</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/passinfo">PassInfo</a> class - An instance of this class exists for every pass known by the system, and can be obtained from a live <a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a> by calling its <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetpassconfig-cpp/#a8fd5fd11f1d85fee7e28a197e915aa0d">getPassInfo()</a> method. <a href="/web-llvm/docs/api/classes/llvm/passinfo/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename passName&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#aee30bf48a272c4267cd3606e047aa3e8">RegisterPass</a> (StringRef PassArg, StringRef Name, bool CFGOnly=false, bool is_analysis=false)</td>
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

<p>RegisterPass&lt;t&gt; template - This template class is used to notify the system that a <a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a> is available for use, and registers it into the internal database maintained by the <a href="/web-llvm/docs/api/classes/llvm/passmanager">PassManager</a>.</p>


<p>Unless this template is used, opt, for example will not be able to see the pass and attempts to create the pass will fail. This template is used in the follow manner (at global scope, in your .cpp file):</p>


<p>static RegisterPass&lt;YourPassClassName&gt; tmp("passopt", "My Pass Name");</p>


<p>This statement will cause your pass to be created by calling the default constructor exposed by the pass.</p>


<p>Definition at line 107 of file <a href="/web-llvm/docs/api/files/include/include/llvm/passsupport-h">PassSupport.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### RegisterPass() {#aee30bf48a272c4267cd3606e047aa3e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename passName&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::RegisterPass&lt; passName &gt;::RegisterPass (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> PassArg, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, bool CFGOnly=false, bool is_analysis=false)</td>
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



<p>Definition at line 109 of file <a href="/web-llvm/docs/api/files/include/include/llvm/passsupport-h">PassSupport.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a1722ea06b072db7df9423d31e810c455">llvm::callDefaultCtor</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinecfgprinter-cpp/#af50584ae7dcdfb215af187e3e0ea8680">CFGOnly</a>, <a href="/web-llvm/docs/api/classes/llvm/passregistry/#a05a729900b76c89e808c6c3094921b2f">llvm::PassRegistry::getPassRegistry</a>, <a href="/web-llvm/docs/api/classes/llvm/passinfo/#a9120a17cdcf88826fb07b59bc7db1b20">llvm::PassInfo::PassInfo</a> and <a href="/web-llvm/docs/api/classes/llvm/passregistry/#a1c6b1d7b3e51a4eeefbf90b25edaf708">llvm::PassRegistry::registerPass</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/passsupport-h">PassSupport.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>

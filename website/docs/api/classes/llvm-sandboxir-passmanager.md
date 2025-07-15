---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/sandboxir/passmanager
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `PassManager` Class Template Reference

<p>Base class. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;typename ParentPass, typename ContainedPass&gt;
class llvm::sandboxir::PassManager&lt;ParentPass, ContainedPass&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/passmanager-h">llvm/SandboxIR/PassManager.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/parentpass">ParentPass</a></td>
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

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ParentPass, typename ContainedPass&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a49776eae204190a6aeb2bae228f7d938">CreatePassFunc</a> = std::function&lt; std::unique_ptr&lt; ContainedPass &gt;(<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>)&gt;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ParentPass, typename ContainedPass&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a1e1411cecb7e848d94591dcc1b4c0c32">PassManager</a> (StringRef Name)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ParentPass, typename ContainedPass&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a840acc6600293ce7ac61da15c04c8088">PassManager</a> (StringRef Name, StringRef Pipeline, CreatePassFunc CreatePass)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ParentPass, typename ContainedPass&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a0406ea6998638c6c2fc1bfc5230df6ef">PassManager</a> (const PassManager &amp;)=delete</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ParentPass, typename ContainedPass&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a36fee23bc35b918efea4b2a615e3806b">PassManager</a> (PassManager &amp;&amp;)=default</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ParentPass, typename ContainedPass&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#ab5f267eceaad4661b6282bc5b6eb7f29">~PassManager</a> ()=default</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ParentPass, typename ContainedPass&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sandboxir/passmanager">PassManager</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a89f83b2f0032472696778d0af69cb1ff">operator=</a> (const PassManager &amp;)=delete</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ParentPass, typename ContainedPass&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a12103f1e78c61332519f7a1b1c5e23d5">addPass</a> (std::unique_ptr&lt; ContainedPass &gt; Pass)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Adds <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/sandboxir/pass">Pass</a></span> to the pass pipeline. <a href="#a12103f1e78c61332519f7a1b1c5e23d5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ParentPass, typename ContainedPass&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a25d8acedc0fc6a1fbd8a2eea6dcd0f4c">setPassPipeline</a> (StringRef Pipeline, CreatePassFunc CreatePass)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parses <span class="doxyComputerOutput">Pipeline</span> as a comma-separated sequence of pass names and sets the pass pipeline, using <span class="doxyComputerOutput">CreatePass</span> to instantiate passes by name. <a href="#a25d8acedc0fc6a1fbd8a2eea6dcd0f4c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ParentPass, typename ContainedPass&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a3f75ee2e53d1aab594375a3345fbddea">print</a> (raw_ostream &amp;OS) const override</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ParentPass, typename ContainedPass&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#aa863693eef567397d9c292da5bf22d34">LLVM_DUMP_METHOD</a> void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a8f5329d9d97273a1c50798ccb215d519">dump</a> () const override</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ParentPass, typename ContainedPass&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a14ca239a766dfe1029be1c5838a13ffb">printPipeline</a> (raw_ostream &amp;OS) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Similar to <a href="#a3f75ee2e53d1aab594375a3345fbddea">print()</a> but prints one pass per line. Used for testing. <a href="#a14ca239a766dfe1029be1c5838a13ffb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ParentPass, typename ContainedPass&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; std::unique_ptr&lt; ContainedPass &gt; &gt;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac6205116f9e954e988534ec98b459ff4">Passes</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The list of passes that this pass manager will run. <a href="#ac6205116f9e954e988534ec98b459ff4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Base class.</p>

<p>Definition at line 34 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/passmanager-h">PassManager.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### CreatePassFunc {#a49776eae204190a6aeb2bae228f7d938}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ParentPass, typename ContainedPass&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::sandboxir::PassManager&lt; ParentPass, ContainedPass &gt;::CreatePassFunc = 
      std::function&lt;std::unique_ptr&lt;ContainedPass&gt;(StringRef, StringRef)&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/passmanager-h">PassManager.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Constructors

### PassManager() {#a1e1411cecb7e848d94591dcc1b4c0c32}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ParentPass, typename ContainedPass&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::sandboxir::PassManager&lt; ParentPass, ContainedPass &gt;::PassManager (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name)</td>
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



<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/passmanager-h">PassManager.h</a>.</p>


<p>Referenced by <a href="#a89f83b2f0032472696778d0af69cb1ff">llvm::sandboxir::PassManager&lt; ParentPass, ContainedPass &gt;::operator=</a>, <a href="#a0406ea6998638c6c2fc1bfc5230df6ef">llvm::sandboxir::PassManager&lt; ParentPass, ContainedPass &gt;::PassManager</a> and <a href="#a36fee23bc35b918efea4b2a615e3806b">llvm::sandboxir::PassManager&lt; ParentPass, ContainedPass &gt;::PassManager</a>.</p>

</div>
</div>

### PassManager() {#a840acc6600293ce7ac61da15c04c8088}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ParentPass, typename ContainedPass&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::sandboxir::PassManager&lt; ParentPass, ContainedPass &gt;::PassManager (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Pipeline, <a href="#a49776eae204190a6aeb2bae228f7d938">CreatePassFunc</a> CreatePass)</td>
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



<p>Definition at line 45 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/passmanager-h">PassManager.h</a>.</p>


<p>Reference <a href="#a25d8acedc0fc6a1fbd8a2eea6dcd0f4c">llvm::sandboxir::PassManager&lt; ParentPass, ContainedPass &gt;::setPassPipeline</a>.</p>

</div>
</div>

### PassManager() {#a0406ea6998638c6c2fc1bfc5230df6ef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ParentPass, typename ContainedPass&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::sandboxir::PassManager&lt; ParentPass, ContainedPass &gt;::PassManager (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sandboxir/passmanager">PassManager</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/passmanager-h">PassManager.h</a>.</p>


<p>Reference <a href="#a1e1411cecb7e848d94591dcc1b4c0c32">llvm::sandboxir::PassManager&lt; ParentPass, ContainedPass &gt;::PassManager</a>.</p>

</div>
</div>

### PassManager() {#a36fee23bc35b918efea4b2a615e3806b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ParentPass, typename ContainedPass&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::sandboxir::PassManager&lt; ParentPass, ContainedPass &gt;::PassManager (<a href="/web-llvm/docs/api/classes/llvm/sandboxir/passmanager">PassManager</a> &amp;&amp;)</td>
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



<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/passmanager-h">PassManager.h</a>.</p>


<p>Reference <a href="#a1e1411cecb7e848d94591dcc1b4c0c32">llvm::sandboxir::PassManager&lt; ParentPass, ContainedPass &gt;::PassManager</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Destructor

### \~PassManager() {#ab5f267eceaad4661b6282bc5b6eb7f29}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ParentPass, typename ContainedPass&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual llvm::sandboxir::PassManager&lt; ParentPass, ContainedPass &gt;::~PassManager ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/passmanager-h">PassManager.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Operators

### operator=() {#a89f83b2f0032472696778d0af69cb1ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ParentPass, typename ContainedPass&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PassManager &amp; llvm::sandboxir::PassManager&lt; ParentPass, ContainedPass &gt;::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sandboxir/passmanager">PassManager</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/passmanager-h">PassManager.h</a>.</p>


<p>Reference <a href="#a1e1411cecb7e848d94591dcc1b4c0c32">llvm::sandboxir::PassManager&lt; ParentPass, ContainedPass &gt;::PassManager</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addPass() {#a12103f1e78c61332519f7a1b1c5e23d5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ParentPass, typename ContainedPass&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::sandboxir::PassManager&lt; ParentPass, ContainedPass &gt;::addPass (std::unique_ptr&lt; ContainedPass &gt; Pass)</td>
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

<p>Adds <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/sandboxir/pass">Pass</a></span> to the pass pipeline.</p>

<p>Definition at line 56 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/passmanager-h">PassManager.h</a>.</p>


<p>Reference <a href="#ac6205116f9e954e988534ec98b459ff4">llvm::sandboxir::PassManager&lt; ParentPass, ContainedPass &gt;::Passes</a>.</p>


<p>Referenced by <a href="#a25d8acedc0fc6a1fbd8a2eea6dcd0f4c">llvm::sandboxir::PassManager&lt; ParentPass, ContainedPass &gt;::setPassPipeline</a>.</p>

</div>
</div>

### dump() {#a8f5329d9d97273a1c50798ccb215d519}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ParentPass, typename ContainedPass&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_DUMP_METHOD void llvm::sandboxir::PassManager&lt; ParentPass, ContainedPass &gt;::dump ()</td>
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



<p>Definition at line 191 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/passmanager-h">PassManager.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#aa863693eef567397d9c292da5bf22d34">LLVM_DUMP_METHOD</a> and <a href="#a3f75ee2e53d1aab594375a3345fbddea">llvm::sandboxir::PassManager&lt; ParentPass, ContainedPass &gt;::print</a>.</p>

</div>
</div>

### print() {#a3f75ee2e53d1aab594375a3345fbddea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ParentPass, typename ContainedPass&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::sandboxir::PassManager&lt; ParentPass, ContainedPass &gt;::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
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



<p>Definition at line 184 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/passmanager-h">PassManager.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/provenanceanalysisevaluator-cpp/#a2ee79648e8bce3ddbb26358ff10e3e82">getName</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/pass/#afd425fe36e3defee0e95b3b52cac0ae6">llvm::sandboxir::Pass::getName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2145da5bde7663d745e9c3ade392809f">llvm::interleave</a> and <a href="#ac6205116f9e954e988534ec98b459ff4">llvm::sandboxir::PassManager&lt; ParentPass, ContainedPass &gt;::Passes</a>.</p>


<p>Referenced by <a href="#a8f5329d9d97273a1c50798ccb215d519">llvm::sandboxir::PassManager&lt; ParentPass, ContainedPass &gt;::dump</a>.</p>

</div>
</div>

### printPipeline() {#a14ca239a766dfe1029be1c5838a13ffb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ParentPass, typename ContainedPass&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::sandboxir::PassManager&lt; ParentPass, ContainedPass &gt;::printPipeline (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
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

<p>Similar to <a href="#a3f75ee2e53d1aab594375a3345fbddea">print()</a> but prints one pass per line. Used for testing.</p>

<p>Definition at line 197 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/passmanager-h">PassManager.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/provenanceanalysisevaluator-cpp/#a2ee79648e8bce3ddbb26358ff10e3e82">getName</a> and <a href="#ac6205116f9e954e988534ec98b459ff4">llvm::sandboxir::PassManager&lt; ParentPass, ContainedPass &gt;::Passes</a>.</p>

</div>
</div>

### setPassPipeline() {#a25d8acedc0fc6a1fbd8a2eea6dcd0f4c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ParentPass, typename ContainedPass&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::sandboxir::PassManager&lt; ParentPass, ContainedPass &gt;::setPassPipeline (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Pipeline, <a href="#a49776eae204190a6aeb2bae228f7d938">CreatePassFunc</a> CreatePass)</td>
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

<p>Parses <span class="doxyComputerOutput">Pipeline</span> as a comma-separated sequence of pass names and sets the pass pipeline, using <span class="doxyComputerOutput">CreatePass</span> to instantiate passes by name.</p>


<p>Passes can have arguments, for example: "pass1&lt;arg1,arg2&gt;,pass2,pass3&lt;arg3,arg4&gt;"</p>


<p>The arguments between angle brackets are treated as a mostly opaque string and each pass is responsible for parsing its arguments. The exception to this are nested angle brackets, which must match pair-wise to allow arguments to contain nested pipelines, like:</p>


<p>"pass1&lt;subpass1,subpass2&lt;arg1,arg2&gt;,subpass3&gt;"</p>


<p>An empty args string is treated the same as no args, so "pass" and "pass&lt;&gt;" are equivalent.</p>


<p>Definition at line 76 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/passmanager-h">PassManager.h</a>.</p>


<p>References <a href="#a12103f1e78c61332519f7a1b1c5e23d5">llvm::sandboxir::PassManager&lt; ParentPass, ContainedPass &gt;::addPass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2dc80c585ad5882da8cae7b5968f7e74">llvm::StringRef::empty</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a206e2134ddd2312c3488d0632d98f554">llvm::enumerate</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9a7b5c68c90f85baaedaa854cc5002cc">llvm::errs</a>, <a href="#ac6205116f9e954e988534ec98b459ff4">llvm::sandboxir::PassManager&lt; ParentPass, ContainedPass &gt;::Passes</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86loweramxintrinsics-cpp/#adb9257105a403ef9d0773b87693f7779">PassName</a> and <a href="/web-llvm/docs/api/classes/llvm/stringref/#a5d4c961b9b6f1da17df74b4496ecb30e">llvm::StringRef::slice</a>.</p>


<p>Referenced by <a href="#a840acc6600293ce7ac61da15c04c8088">llvm::sandboxir::PassManager&lt; ParentPass, ContainedPass &gt;::PassManager</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### Passes {#ac6205116f9e954e988534ec98b459ff4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ParentPass, typename ContainedPass&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;std::unique_ptr&lt;ContainedPass&gt; &gt; llvm::sandboxir::PassManager&lt; ParentPass, ContainedPass &gt;::Passes</td>
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

<p>The list of passes that this pass manager will run.</p>

<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/passmanager-h">PassManager.h</a>.</p>


<p>Referenced by <a href="#a12103f1e78c61332519f7a1b1c5e23d5">llvm::sandboxir::PassManager&lt; ParentPass, ContainedPass &gt;::addPass</a>, <a href="#a3f75ee2e53d1aab594375a3345fbddea">llvm::sandboxir::PassManager&lt; ParentPass, ContainedPass &gt;::print</a>, <a href="#a14ca239a766dfe1029be1c5838a13ffb">llvm::sandboxir::PassManager&lt; ParentPass, ContainedPass &gt;::printPipeline</a> and <a href="#a25d8acedc0fc6a1fbd8a2eea6dcd0f4c">llvm::sandboxir::PassManager&lt; ParentPass, ContainedPass &gt;::setPassPipeline</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/passmanager-h">PassManager.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>

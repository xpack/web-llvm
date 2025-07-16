---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/orc/executionsession
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `ExecutionSession` Class Reference

<p>An <a href="/web-llvm/docs/api/classes/llvm/orc/executionsession">ExecutionSession</a> represents a running JIT program. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::orc::ExecutionSession { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">llvm/ExecutionEngine/Orc/Core.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adba3b8e588f1c96678fa1c9a328a4b74">ErrorReporter</a> = <a href="/web-llvm/docs/api/classes/llvm/unique-function">unique_function</a>&lt; void(<a href="/web-llvm/docs/api/classes/llvm/error">Error</a>)&gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>For reporting errors. <a href="#adba3b8e588f1c96678fa1c9a328a4b74">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a17aab624111677f277ae5a453930e29d">SendResultFunction</a> = <a href="/web-llvm/docs/api/classes/llvm/unique-function">unique_function</a>&lt; void(<a href="/web-llvm/docs/api/classes/llvm/orc/shared/wrapperfunctionresult">shared::WrapperFunctionResult</a>)&gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Send a result to the remote. <a href="#a17aab624111677f277ae5a453930e29d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abff481078830fef075c962a19f926952">JITDispatchHandlerFunction</a> = <a href="/web-llvm/docs/api/classes/llvm/unique-function">unique_function</a>&lt; void( <a href="#a17aab624111677f277ae5a453930e29d">SendResultFunction</a> SendResult, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *ArgData, size_t ArgSize)&gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>An asynchronous wrapper-function callable from the executor via jit-dispatch. <a href="#abff481078830fef075c962a19f926952">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af7397131e1a9a35a7ccdf6254f6684dd">JITDispatchHandlerAssociationMap</a> = <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/symbolstringptr">SymbolStringPtr</a>, <a href="#abff481078830fef075c962a19f926952">JITDispatchHandlerFunction</a> &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A map associating tag names with asynchronous wrapper function implementations in the JIT. <a href="#af7397131e1a9a35a7ccdf6254f6684dd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e912f178543507fa641c4e68831b30d">EDUInfosMap</a> = <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; JITDylib::EmissionDepUnit *, JITDylib::EmissionDepUnitInfo &gt;</td>
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

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2490f3ae1d2c04b177884d5a9a167085">InProgressLookupFlagsState</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a83e0fa43f3d1f4a81deb4e8d29faf856">InProgressFullLookupState</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a235f764fe0f700836f89667ef5a0033b">JITDylib</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5dc61279f468c59f8d437c4961c396aa">LookupState</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c1590c98c2c00498468ad2f4bf8a86f">MaterializationResponsibility</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac41884bafc8fcccbf1ae580e5df35921">ResourceTracker</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab90eb7cd1f407e51a5c2d3ab2c81c9ab">ExecutionSession</a> (std::unique_ptr&lt; ExecutorProcessControl &gt; EPC)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct an <a href="/web-llvm/docs/api/classes/llvm/orc/executionsession">ExecutionSession</a> with the given <a href="/web-llvm/docs/api/classes/llvm/orc/executorprocesscontrol">ExecutorProcessControl</a> object. <a href="#ab90eb7cd1f407e51a5c2d3ab2c81c9ab">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaaec6d074ca64a0e04bd16dd1a338d2c">~ExecutionSession</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Destroy an <a href="/web-llvm/docs/api/classes/llvm/orc/executionsession">ExecutionSession</a>. <a href="#aaaec6d074ca64a0e04bd16dd1a338d2c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0e640a50cc22c6992dca0f54a167e67e">endSession</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>End the session. <a href="#a0e640a50cc22c6992dca0f54a167e67e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/executorprocesscontrol">ExecutorProcessControl</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a128c42c13c6cee5b388a8748e6a0a797">getExecutorProcessControl</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the <a href="/web-llvm/docs/api/classes/llvm/orc/executorprocesscontrol">ExecutorProcessControl</a> object associated with this <a href="/web-llvm/docs/api/classes/llvm/orc/executionsession">ExecutionSession</a>. <a href="#a128c42c13c6cee5b388a8748e6a0a797">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2f7fe16eea49478485f19ab0d096b257">getTargetTriple</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the triple for the executor. <a href="#a2f7fe16eea49478485f19ab0d096b257">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad55bb8cab312328752988e3e109a2d8e">getPageSize</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::shared_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/symbolstringpool">SymbolStringPool</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7a0ff5426c14f13472ac39f815ad4206">getSymbolStringPool</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the <a href="/web-llvm/docs/api/classes/llvm/orc/symbolstringpool">SymbolStringPool</a> for this instance. <a href="#a7a0ff5426c14f13472ac39f815ad4206">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/symbolstringptr">SymbolStringPtr</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a6187a7b7e11faffbcb0f788bd2543c">intern</a> (StringRef SymName)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add a symbol name to the <a href="/web-llvm/docs/api/classes/llvm/orc/symbolstringpool">SymbolStringPool</a> and return a pointer to it. <a href="#a4a6187a7b7e11faffbcb0f788bd2543c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ed4129361eccda71fea45447353df4a">setPlatform</a> (std::unique_ptr&lt; Platform &gt; P)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the <a href="/web-llvm/docs/api/classes/llvm/orc/platform">Platform</a> for this <a href="/web-llvm/docs/api/classes/llvm/orc/executionsession">ExecutionSession</a>. <a href="#a2ed4129361eccda71fea45447353df4a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/platform">Platform</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f4ecf8a077b821bd46887808f10fa6f">getPlatform</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the <a href="/web-llvm/docs/api/classes/llvm/orc/platform">Platform</a> for this session. <a href="#a3f4ecf8a077b821bd46887808f10fa6f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Func&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ab9ce518e73ce35d17cd88e873776d51e">runSessionLocked</a> (Func &amp;&amp;F) -&gt; decltype(auto)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Run the given lambda with the session mutex locked. <a href="#ab9ce518e73ce35d17cd88e873776d51e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa00c8d49e29326e8271a16b3f782b8a4">registerResourceManager</a> (ResourceManager &amp;RM)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/register">Register</a> the given <a href="/web-llvm/docs/api/classes/llvm/orc/resourcemanager">ResourceManager</a> with this <a href="/web-llvm/docs/api/classes/llvm/orc/executionsession">ExecutionSession</a>. <a href="#aa00c8d49e29326e8271a16b3f782b8a4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab58270d4adca4a62c6721739e0f4c725">deregisterResourceManager</a> (ResourceManager &amp;RM)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Deregister the given <a href="/web-llvm/docs/api/classes/llvm/orc/resourcemanager">ResourceManager</a> with this <a href="/web-llvm/docs/api/classes/llvm/orc/executionsession">ExecutionSession</a>. <a href="#ab58270d4adca4a62c6721739e0f4c725">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4b12643704d05845fd7e0be447203a80">getJITDylibByName</a> (StringRef Name)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a pointer to the "name" <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a>. <a href="#a4b12643704d05845fd7e0be447203a80">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6576b19a186104b0ee0d910ea472cab2">createBareJITDylib</a> (std::string Name)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add a new bare <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> to this <a href="/web-llvm/docs/api/classes/llvm/orc/executionsession">ExecutionSession</a>. <a href="#a6576b19a186104b0ee0d910ea472cab2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> &amp; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad60342bc09c0803c78f4c085df792378">createJITDylib</a> (std::string Name)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add a new <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> to this <a href="/web-llvm/docs/api/classes/llvm/orc/executionsession">ExecutionSession</a>. <a href="#ad60342bc09c0803c78f4c085df792378">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acfffb371a8a9e003f43cd5027cbea85d">removeJITDylibs</a> (std::vector&lt; JITDylibSP &gt; JDsToRemove)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Removes the given JITDylibs from the <a href="/web-llvm/docs/api/classes/llvm/orc/executionsession">ExecutionSession</a>. <a href="#acfffb371a8a9e003f43cd5027cbea85d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea3c986d513f0b7352d5494f36f2cf23">removeJITDylib</a> (JITDylib &amp;JD)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Calls removeJTIDylibs on the gives <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a>. <a href="#aea3c986d513f0b7352d5494f36f2cf23">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/executionsession">ExecutionSession</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac50b6783239033bb5f3a8ca749d361a9">setErrorReporter</a> (ErrorReporter ReportError)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the error reporter function. <a href="#ac50b6783239033bb5f3a8ca749d361a9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1c47ed6ddfb6770f1a432af1c9acdc44">reportError</a> (Error Err)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Report a error for this execution session. <a href="#a1c47ed6ddfb6770f1a432af1c9acdc44">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a432a464dcfc79515467f0ddefd78fc83">lookupFlags</a> (LookupKind K, JITDylibSearchOrder SearchOrder, SymbolLookupSet Symbols, unique_function&lt; void(Expected&lt; SymbolFlagsMap &gt;)&gt; OnComplete)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Search the given JITDylibs to find the flags associated with each of the given symbols. <a href="#a432a464dcfc79515467f0ddefd78fc83">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/orc/#afd6431981e7fdfd4b5d2794f04d7d913">SymbolFlagsMap</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a081a578f073d014fe2b1ba2c15b8b5c2">lookupFlags</a> (LookupKind K, JITDylibSearchOrder SearchOrder, SymbolLookupSet Symbols)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Blocking version of lookupFlags. <a href="#a081a578f073d014fe2b1ba2c15b8b5c2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9260560ad3aaa612b92cff4bccd3c223">lookup</a> (LookupKind K, const JITDylibSearchOrder &amp;SearchOrder, SymbolLookupSet Symbols, SymbolState RequiredState, SymbolsResolvedCallback NotifyComplete, RegisterDependenciesFunction RegisterDependencies)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Search the given JITDylibs for the given symbols. <a href="#a9260560ad3aaa612b92cff4bccd3c223">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a8ab9a099de556e888c5f92a4fe49d2fa">SymbolMap</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adcd2edb47f46a28037d9f738f0cd1aa8">lookup</a> (const JITDylibSearchOrder &amp;SearchOrder, SymbolLookupSet Symbols, LookupKind K=LookupKind::Static, SymbolState RequiredState=SymbolState::Ready, RegisterDependenciesFunction RegisterDependencies=NoDependenciesToRegister)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Blocking version of lookup above. <a href="#adcd2edb47f46a28037d9f738f0cd1aa8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/executorsymboldef">ExecutorSymbolDef</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7492b1c8aaacb6f0dd1d30a0823d7bc2">lookup</a> (const JITDylibSearchOrder &amp;SearchOrder, SymbolStringPtr Symbol, SymbolState RequiredState=SymbolState::Ready)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Convenience version of blocking lookup. <a href="#a7492b1c8aaacb6f0dd1d30a0823d7bc2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/executorsymboldef">ExecutorSymbolDef</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad174864e2ec81bda9cbcb1c18eeab3cd">lookup</a> (ArrayRef&lt; JITDylib * &gt; SearchOrder, SymbolStringPtr Symbol, SymbolState RequiredState=SymbolState::Ready)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Convenience version of blocking lookup. <a href="#ad174864e2ec81bda9cbcb1c18eeab3cd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/executorsymboldef">ExecutorSymbolDef</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a82b549cec73af340fdd4b80c97b43c74">lookup</a> (ArrayRef&lt; JITDylib * &gt; SearchOrder, StringRef Symbol, SymbolState RequiredState=SymbolState::Ready)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Convenience version of blocking lookup. <a href="#a82b549cec73af340fdd4b80c97b43c74">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad8bfb5f058b029cbcac70d97ed165b14">dispatchTask</a> (std::unique_ptr&lt; Task &gt; T)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Materialize the given unit. <a href="#ad8bfb5f058b029cbcac70d97ed165b14">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/stringmap">StringMap</a>&lt; std::vector&lt; char &gt; &gt; &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8f9d8fde3719e8c1a7fcc4526a9029d2">getBootstrapMap</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the bootstrap map. <a href="#a8f9d8fde3719e8c1a7fcc4526a9029d2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, typename SPSTagT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a7dc6e2659a199f1f2061aa6d2a4facc0">getBootstrapMapValue</a> (StringRef Key, std::optional&lt; T &gt; &amp;Val) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Look up and SPS-deserialize a bootstrap map value. <a href="#a7dc6e2659a199f1f2061aa6d2a4facc0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/stringmap">StringMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">ExecutorAddr</a> &gt; &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e1f82feebf8b9217a8c84c204d75df0">getBootstrapSymbolsMap</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the bootstrap symbol map. <a href="#a2e1f82feebf8b9217a8c84c204d75df0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8d329fd9929dbb94bef42bb0c63b2057">getBootstrapSymbols</a> (ArrayRef&lt; std::pair&lt; ExecutorAddr &amp;, StringRef &gt; &gt; Pairs) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>For each (<a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">ExecutorAddr</a>&amp;, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>) pair, looks up the string in the bootstrap symbols map and writes its address to the <a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">ExecutorAddr</a> if found. <a href="#a8d329fd9929dbb94bef42bb0c63b2057">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename... ArgTs&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a51c585632c0a11d1ea133e2a7ef7b077">callWrapperAsync</a> (ArgTs &amp;&amp;... Args)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Run a wrapper function in the executor. <a href="#a51c585632c0a11d1ea133e2a7ef7b077">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/shared/wrapperfunctionresult">shared::WrapperFunctionResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a474e1b9a90bedfd471bbeb6df55d8888">callWrapper</a> (ExecutorAddr WrapperFnAddr, ArrayRef&lt; char &gt; ArgBuffer)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Run a wrapper function in the executor. <a href="#a474e1b9a90bedfd471bbeb6df55d8888">More...</a></p>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a7277d033c10b765e9ea3898e4492c890">callSPSWrapperAsync</a> (ExecutorAddr WrapperFnAddr, SendResultT &amp;&amp;SendResult, const ArgTs &amp;...Args)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Run a wrapper function using SPS to serialize the arguments and deserialize the results. <a href="#a7277d033c10b765e9ea3898e4492c890">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SPSSignature, typename... WrapperCallArgTs&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a40315a5f3623ac6408b49e0ee164ad67">callSPSWrapper</a> (ExecutorAddr WrapperFnAddr, WrapperCallArgTs &amp;&amp;...WrapperCallArgs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Run a wrapper function using SPS to serialize the arguments and deserialize the results. <a href="#a40315a5f3623ac6408b49e0ee164ad67">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9af5ee3a848ca02c351ee7ffca01c3f0">registerJITDispatchHandlers</a> (JITDylib &amp;JD, JITDispatchHandlerAssociationMap WFs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>For each tag symbol name, associate the corresponding AsyncHandlerWrapperFunction with the address of that symbol. <a href="#a9af5ee3a848ca02c351ee7ffca01c3f0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab04dd8530994d3914c2398c5105bd74b">runJITDispatchHandler</a> (SendResultFunction SendResult, ExecutorAddr HandlerFnTagAddr, ArrayRef&lt; char &gt; ArgBuffer)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Run a registered jit-side wrapper function. <a href="#ab04dd8530994d3914c2398c5105bd74b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac2f08336aef2526b897c029a94a2e054">dump</a> (raw_ostream &amp;OS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Dump the state of all the JITDylibs in this session. <a href="#ac2f08336aef2526b897c029a94a2e054">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aca1b144fe5a6bca1ddf699fc0b0c9536">dispatchOutstandingMUs</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a22f3f6c6c7b2b325a558c7091bd57a23">removeResourceTracker</a> (ResourceTracker &amp;RT)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7bcefb22f2ce0c0e25768f2d1f6353eb">transferResourceTracker</a> (ResourceTracker &amp;DstRT, ResourceTracker &amp;SrcRT)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a269ff1140f5ab89e15cc12de1a3774db">destroyResourceTracker</a> (ResourceTracker &amp;RT)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae2148bb327434662fa22d80ac9f597cc">IL_updateCandidatesFor</a> (JITDylib &amp;JD, JITDylibLookupFlags JDLookupFlags, SymbolLookupSet &amp;Candidates, SymbolLookupSet *NonCandidates)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>IL_updateCandidatesFor is called to remove already-defined symbols that match a given query from the set of candidate symbols to generate definitions for (no need to generate a definition if one already exists). <a href="#ae2148bb327434662fa22d80ac9f597cc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b1b5182ef79919f97f373d3530de3ce">OL_resumeLookupAfterGeneration</a> (InProgressLookupState &amp;IPLS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Handle resumption of a lookup after entering a generator. <a href="#a5b1b5182ef79919f97f373d3530de3ce">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0e8b7e68830d4b07218b212ae1726f9b">OL_applyQueryPhase1</a> (std::unique_ptr&lt; InProgressLookupState &gt; IPLS, Error Err)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>OL_applyQueryPhase1 is an optionally re-startable loop for triggering definition generation. <a href="#a0e8b7e68830d4b07218b212ae1726f9b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a72aa0428f1be4bec174659b6a4223243">OL_completeLookup</a> (std::unique_ptr&lt; InProgressLookupState &gt; IPLS, std::shared_ptr&lt; AsynchronousSymbolQuery &gt; Q, RegisterDependenciesFunction RegisterDependencies)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>OL_completeLookup is run once phase 1 successfully completes for a lookup call. <a href="#a72aa0428f1be4bec174659b6a4223243">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acda211f1192be4f99cec578358c4330b">OL_completeLookupFlags</a> (std::unique_ptr&lt; InProgressLookupState &gt; IPLS, unique_function&lt; void(Expected&lt; SymbolFlagsMap &gt;)&gt; OnComplete)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>OL_completeLookupFlags is run once phase 1 successfully completes for a lookupFlags call. <a href="#acda211f1192be4f99cec578358c4330b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1419ca3ed095c6d3628e17889b954302">OL_destroyMaterializationResponsibility</a> (MaterializationResponsibility &amp;MR)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/orc/#ada98b2ca88b7bc4b65b62e3269fdade7">SymbolNameSet</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afcebe1dd3ded04d8461c2b8f452f1b38">OL_getRequestedSymbols</a> (const MaterializationResponsibility &amp;MR)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8365b2bcd03a5a91b23c0a73ecd9db40">OL_notifyResolved</a> (MaterializationResponsibility &amp;MR, const SymbolMap &amp;Symbols)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename HandleNewDepFn&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a187cf981731ec3d4005d80f5d6554ae3">propagateExtraEmitDeps</a> (std::deque&lt; JITDylib::EmissionDepUnit * &gt; Worklist, EDUInfosMap &amp;EDUInfos, HandleNewDepFn HandleNewDep)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">EDUInfosMap</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac50770cf172ef50d861837f00de2eda4">simplifyDepGroups</a> (MaterializationResponsibility &amp;MR, ArrayRef&lt; SymbolDependenceGroup &gt; EmittedDeps)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a08b0690d6869653e86b27b2c463fa69e">IL_makeEDUReady</a> (std::shared_ptr&lt; JITDylib::EmissionDepUnit &gt; EDU, JITDylib::AsynchronousSymbolQuerySet &amp;Queries)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9bc9002a9763b7f22513b5b05d6a8b9c">IL_makeEDUEmitted</a> (std::shared_ptr&lt; JITDylib::EmissionDepUnit &gt; EDU, JITDylib::AsynchronousSymbolQuerySet &amp;Queries)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad4e4077c95ffd2509d58fac2e016da9f">IL_removeEDUDependence</a> (JITDylib::EmissionDepUnit &amp;EDU, JITDylib &amp;DepJD, NonOwningSymbolStringPtr DepSym, EDUInfosMap &amp;EDUInfos)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Removes the given dependence from EDU. <a href="#ad4e4077c95ffd2509d58fac2e016da9f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; JITDylib::AsynchronousSymbolQuerySet &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6fa69b39d88044cabe30f83ea6cd87b1">IL_emit</a> (MaterializationResponsibility &amp;MR, EDUInfosMap EDUInfos)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad324fd8a995fae88a5f35e9113754ddd">OL_notifyEmitted</a> (MaterializationResponsibility &amp;MR, ArrayRef&lt; SymbolDependenceGroup &gt; EmittedDeps)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a1cd2d300724b17a4e153521018a569">OL_defineMaterializing</a> (MaterializationResponsibility &amp;MR, SymbolFlagsMap SymbolFlags)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::pair&lt; JITDylib::AsynchronousSymbolQuerySet, std::shared_ptr&lt; <a href="/web-llvm/docs/api/namespaces/llvm/orc/#ad4c600dd1184757dace1280e114f5b15">SymbolDependenceMap</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a417dd9ff3ab2220247d409664474dfd4">IL_failSymbols</a> (JITDylib &amp;JD, const SymbolNameVector &amp;SymbolsToFail)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae332efd0c821345a2d951d5c2ae15831">OL_notifyFailed</a> (MaterializationResponsibility &amp;MR)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac158c16aadd06901bf857d1063e6b4f4">OL_replace</a> (MaterializationResponsibility &amp;MR, std::unique_ptr&lt; MaterializationUnit &gt; MU)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/materializationresponsibility">MaterializationResponsibility</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac007e3f39220799f76fdde09edbfdedf">OL_delegate</a> (MaterializationResponsibility &amp;MR, const SymbolNameSet &amp;Symbols)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1a043f02f0755d5d449a6c928347e79b">dumpDispatchInfo</a> (Task &amp;T)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::recursive_mutex</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a03d0c8408c48080eafd72195d0252640">SessionMutex</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a788b6c6d8b62ec8e2abca5e71fa93fc0">SessionOpen</a> = <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/executorprocesscontrol">ExecutorProcessControl</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab5ce937f24141009d7b826ce6ab71ba">EPC</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/platform">Platform</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0bf25e78e013a2ac7d597663c1782c2a">P</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#adba3b8e588f1c96678fa1c9a328a4b74">ErrorReporter</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad3fcbd5f8f63ca4ad5e34875430923d6">ReportError</a> = logErrorsToStdErr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/resourcemanager">ResourceManager</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a49d7523a5c241742909ee74e12398d6b">ResourceManagers</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a1baadbec01aced37be13a1b86c76397e">JITDylibSP</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a32f1ca23e658d79234809d3783a7a7d0">JDs</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::recursive_mutex</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac316d06356b878c9bd194880990fbccc">OutstandingMUsMutex</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; std::pair&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/materializationunit">MaterializationUnit</a> &gt;, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/materializationresponsibility">MaterializationResponsibility</a> &gt; &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a520545ed5ee04051b38d3db356996550">OutstandingMUs</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::mutex</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a62203943e11b4460cb9e963a814c0a71">JITDispatchHandlersMutex</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">ExecutorAddr</a>, std::shared_ptr&lt; <a href="#abff481078830fef075c962a19f926952">JITDispatchHandlerFunction</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#add5f7dbbb57e094b32d6671c0e7f4955">JITDispatchHandlers</a></td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SPSSignature, typename HandlerT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static <a href="#abff481078830fef075c962a19f926952">JITDispatchHandlerFunction</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a6d161dc24753bbe3581c27a63c8be151">wrapAsyncWithSPS</a> (HandlerT &amp;&amp;H)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Wrap a handler that takes concrete argument types (and a sender for a concrete return type) to produce an AsyncHandlerWrapperFunction. <a href="#a6d161dc24753bbe3581c27a63c8be151">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static <a href="#abff481078830fef075c962a19f926952">JITDispatchHandlerFunction</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a5b938a04fc3a8b890dd28a52603549c7">wrapAsyncWithSPS</a> (ClassT *Instance, void(ClassT::*Method)(MethodArgTs...))</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Wrap a class method that takes concrete argument types (and a sender for a concrete return type) to produce an AsyncHandlerWrapperFunction. <a href="#a5b938a04fc3a8b890dd28a52603549c7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b8d10c807c75d7006cca54132ef1816">logErrorsToStdErr</a> (Error Err)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> the internal consistency of <a href="/web-llvm/docs/api/classes/llvm/orc/executionsession">ExecutionSession</a> data structures. <a href="#a0b8d10c807c75d7006cca54132ef1816">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/materializationresponsibility">MaterializationResponsibility</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a594d054bdaa56e1ba7ad7eb984eae408">createMaterializationResponsibility</a> (ResourceTracker &amp;RT, SymbolFlagsMap Symbols, SymbolStringPtr InitSymbol)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a295917f758bb479917f96d055ed2c2a0">makeJDClosedError</a> (JITDylib::EmissionDepUnit &amp;EDU, JITDylib &amp;ClosedJD)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac29b8c6dde2f59637c683058f5b498c2">makeUnsatisfiedDepsError</a> (JITDylib::EmissionDepUnit &amp;EDU, JITDylib &amp;BadJD, SymbolNameSet BadDeps)</td>
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

<p>An <a href="/web-llvm/docs/api/classes/llvm/orc/executionsession">ExecutionSession</a> represents a running JIT program.</p>

<p>Definition at line 1345 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### ErrorReporter {#adba3b8e588f1c96678fa1c9a328a4b74}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::orc::ExecutionSession::ErrorReporter =  unique_function&lt;void(Error)&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>For reporting errors.</p>

<p>Definition at line 1355 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>.</p>

</div>
</div>

### JITDispatchHandlerAssociationMap {#af7397131e1a9a35a7ccdf6254f6684dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::orc::ExecutionSession::JITDispatchHandlerAssociationMap = 
      DenseMap&lt;SymbolStringPtr, JITDispatchHandlerFunction&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A map associating tag names with asynchronous wrapper function implementations in the JIT.</p>

<p>Definition at line 1368 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>.</p>

</div>
</div>

### JITDispatchHandlerFunction {#abff481078830fef075c962a19f926952}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::orc::ExecutionSession::JITDispatchHandlerFunction =  unique_function&lt;void(
      SendResultFunction SendResult,
      const char *ArgData, size_t ArgSize)&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>An asynchronous wrapper-function callable from the executor via jit-dispatch.</p>

<p>Definition at line 1362 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>.</p>

</div>
</div>

### SendResultFunction {#a17aab624111677f277ae5a453930e29d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::orc::ExecutionSession::SendResultFunction =  unique_function&lt;void(shared::WrapperFunctionResult)&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Send a result to the remote.</p>

<p>Definition at line 1358 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Typedefs

### EDUInfosMap {#a9e912f178543507fa641c4e68831b30d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::orc::ExecutionSession::EDUInfosMap = 
      DenseMap&lt;JITDylib::EmissionDepUnit *, JITDylib::EmissionDepUnitInfo&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1751 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Friends

### InProgressFullLookupState {#a83e0fa43f3d1f4a81deb4e8d29faf856}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/orc/inprogressfulllookupstate">InProgressFullLookupState</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 1347 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>.</p>


<p>Reference <a href="#a83e0fa43f3d1f4a81deb4e8d29faf856">InProgressFullLookupState</a>.</p>


<p>Referenced by <a href="#a83e0fa43f3d1f4a81deb4e8d29faf856">InProgressFullLookupState</a>.</p>

</div>
</div>

### InProgressLookupFlagsState {#a2490f3ae1d2c04b177884d5a9a167085}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/orc/inprogresslookupflagsstate">InProgressLookupFlagsState</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 1346 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>.</p>


<p>Reference <a href="#a2490f3ae1d2c04b177884d5a9a167085">InProgressLookupFlagsState</a>.</p>


<p>Referenced by <a href="#a2490f3ae1d2c04b177884d5a9a167085">InProgressLookupFlagsState</a>.</p>

</div>
</div>

### JITDylib {#a235f764fe0f700836f89667ef5a0033b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 1348 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>.</p>


<p>Reference <a href="#a235f764fe0f700836f89667ef5a0033b">JITDylib</a>.</p>


<p>Referenced by <a href="#a6576b19a186104b0ee0d910ea472cab2">createBareJITDylib</a>, <a href="#a4b12643704d05845fd7e0be447203a80">getJITDylibByName</a>, <a href="#a235f764fe0f700836f89667ef5a0033b">JITDylib</a>, <a href="#a9af5ee3a848ca02c351ee7ffca01c3f0">registerJITDispatchHandlers</a> and <a href="#aea3c986d513f0b7352d5494f36f2cf23">removeJITDylib</a>.</p>

</div>
</div>

### LookupState {#a5dc61279f468c59f8d437c4961c396aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/orc/lookupstate">LookupState</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 1349 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>.</p>


<p>Reference <a href="#a5dc61279f468c59f8d437c4961c396aa">LookupState</a>.</p>


<p>Referenced by <a href="#a5dc61279f468c59f8d437c4961c396aa">LookupState</a>.</p>

</div>
</div>

### MaterializationResponsibility {#a9c1590c98c2c00498468ad2f4bf8a86f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/orc/materializationresponsibility">MaterializationResponsibility</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 1350 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>.</p>


<p>Reference <a href="#a9c1590c98c2c00498468ad2f4bf8a86f">MaterializationResponsibility</a>.</p>


<p>Referenced by <a href="#a9c1590c98c2c00498468ad2f4bf8a86f">MaterializationResponsibility</a>.</p>

</div>
</div>

### ResourceTracker {#ac41884bafc8fcccbf1ae580e5df35921}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/orc/resourcetracker">ResourceTracker</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 1351 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>.</p>


<p>Reference <a href="#ac41884bafc8fcccbf1ae580e5df35921">ResourceTracker</a>.</p>


<p>Referenced by <a href="#ac41884bafc8fcccbf1ae580e5df35921">ResourceTracker</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### ExecutionSession() {#ab90eb7cd1f407e51a5c2d3ab2c81c9ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::orc::ExecutionSession::ExecutionSession (std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/executorprocesscontrol">ExecutorProcessControl</a> &gt; EPC)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Construct an <a href="/web-llvm/docs/api/classes/llvm/orc/executionsession">ExecutionSession</a> with the given <a href="/web-llvm/docs/api/classes/llvm/orc/executorprocesscontrol">ExecutorProcessControl</a> object.</p>

<p>Declaration at line 1373 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>, definition at line 1607 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/core-cpp">Core.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a>.</p>


<p>Referenced by <a href="#ac50b6783239033bb5f3a8ca749d361a9">setErrorReporter</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~ExecutionSession() {#aaaec6d074ca64a0e04bd16dd1a338d2c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::orc::ExecutionSession::~ExecutionSession ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Destroy an <a href="/web-llvm/docs/api/classes/llvm/orc/executionsession">ExecutionSession</a>.</p>


<p>Verifies that endSession was called prior to destruction.</p>


<p>Declaration at line 1377 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>, definition at line 1613 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/core-cpp">Core.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### callSPSWrapper() {#a40315a5f3623ac6408b49e0ee164ad67}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SPSSignature, typename... WrapperCallArgTs&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::orc::ExecutionSession::callSPSWrapper (<a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">ExecutorAddr</a> WrapperFnAddr, WrapperCallArgTs &amp;&amp;... WrapperCallArgs)</td>
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

<p>Run a wrapper function using SPS to serialize the arguments and deserialize the results.</p>


<p>If SPSSignature is a non-void function signature then the second argument (the first in the Args list) should be a reference to a return value.</p>


<p>Definition at line 1623 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>.</p>

</div>
</div>

### callSPSWrapperAsync() {#a7277d033c10b765e9ea3898e4492c890}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SPSSignature, typename SendResultT, typename... ArgTs&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::orc::ExecutionSession::callSPSWrapperAsync (<a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">ExecutorAddr</a> WrapperFnAddr, SendResultT &amp;&amp; SendResult, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> ArgTs &amp;... Args)</td>
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

<p>Run a wrapper function using SPS to serialize the arguments and deserialize the results.</p>

<p>Definition at line 1611 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>.</p>

</div>
</div>

### callWrapper() {#a474e1b9a90bedfd471bbeb6df55d8888}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">shared::WrapperFunctionResult llvm::orc::ExecutionSession::callWrapper (<a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">ExecutorAddr</a> WrapperFnAddr, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; char &gt; ArgBuffer)</td>
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

<p>Run a wrapper function in the executor.</p>


<p>The wrapper function should be callable as:</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">CWrapperFunctionResult fn(uint8_t *<a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">Data</a>, uint64_t <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>);</span></span></div>

</div>


<p>{.cpp}</p>


<p>Definition at line 1603 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>.</p>

</div>
</div>

### callWrapperAsync() {#a51c585632c0a11d1ea133e2a7ef7b077}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename... ArgTs&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::orc::ExecutionSession::callWrapperAsync (ArgTs &amp;&amp;... Args)</td>
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

<p>Run a wrapper function in the executor.</p>


<p>The wrapper function should be callable as:</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">CWrapperFunctionResult fn(uint8_t *<a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">Data</a>, uint64_t <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>);</span></span></div>

</div>


<p>{.cpp}</p>


<p>The given OnComplete function will be called to return the result.</p>


<p>Definition at line 1593 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>.</p>

</div>
</div>

### createBareJITDylib() {#a6576b19a186104b0ee0d910ea472cab2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">JITDylib &amp; llvm::orc::ExecutionSession::createBareJITDylib (std::string Name)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add a new bare <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> to this <a href="/web-llvm/docs/api/classes/llvm/orc/executionsession">ExecutionSession</a>.</p>


<p>The <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> Name is required to be unique. Clients should verify that names are not being re-used (E.g. by calling getJITDylibByName) if names are based on user input.</p>


<p>This call does not install any library code or symbols into the newly created <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a>. The client is responsible for all configuration.</p>


<p>Declaration at line 1434 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>, definition at line 1667 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/core-cpp">Core.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a4b12643704d05845fd7e0be447203a80">getJITDylibByName</a>, <a href="#a235f764fe0f700836f89667ef5a0033b">JITDylib</a> and <a href="#ab9ce518e73ce35d17cd88e873776d51e">runSessionLocked</a>.</p>


<p>Referenced by <a href="#ad60342bc09c0803c78f4c085df792378">createJITDylib</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/executornativeplatform/#aa1bd92add845031ceeaab24c2c25c275">llvm::orc::ExecutorNativePlatform::operator()</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/lljitbuilderstate/#a18ff6139760982f4640e0ea26da81ba4">llvm::orc::LLJITBuilderState::prepareForConstruction</a> and <a href="/web-llvm/docs/api/classes/llvm/orc/lljit/#a392f906e72c6fa022d871e028e6f34b9">llvm::orc::LLJIT::setUpGenericLLVMIRPlatform</a>.</p>

</div>
</div>

### createJITDylib() {#ad60342bc09c0803c78f4c085df792378}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; JITDylib &amp; &gt; llvm::orc::ExecutionSession::createJITDylib (std::string Name)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add a new <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> to this <a href="/web-llvm/docs/api/classes/llvm/orc/executionsession">ExecutionSession</a>.</p>


<p>The <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> Name is required to be unique. Clients should verify that names are not being re-used (e.g. by calling getJITDylibByName) if names are based on user input.</p>


<p>If a <a href="/web-llvm/docs/api/classes/llvm/orc/platform">Platform</a> is attached then <a href="/web-llvm/docs/api/classes/llvm/orc/platform/#af83795e97281d33db2882a003b2c7545">Platform::setupJITDylib</a> will be called to install standard platform symbols (e.g. standard library interposes). If no <a href="/web-llvm/docs/api/classes/llvm/orc/platform">Platform</a> is attached this call is equivalent to createBareJITDylib.</p>


<p>Declaration at line 1445 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>, definition at line 1676 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/core-cpp">Core.cpp</a>.</p>


<p>Reference <a href="#a6576b19a186104b0ee0d910ea472cab2">createBareJITDylib</a>.</p>

</div>
</div>

### deregisterResourceManager() {#ab58270d4adca4a62c6721739e0f4c725}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::orc::ExecutionSession::deregisterResourceManager (<a href="/web-llvm/docs/api/classes/llvm/orc/resourcemanager">ResourceManager</a> &amp; RM)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Deregister the given <a href="/web-llvm/docs/api/classes/llvm/orc/resourcemanager">ResourceManager</a> with this <a href="/web-llvm/docs/api/classes/llvm/orc/executionsession">ExecutionSession</a>.</p>


<p>Manager must have been previously registered.</p>


<p>Declaration at line 1420 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>, definition at line 1645 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/core-cpp">Core.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a086e9fbdb06276db7753101a08a63adf">llvm::find</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="#ab9ce518e73ce35d17cd88e873776d51e">runSessionLocked</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/orc/linkgraphlinkinglayer/#ac0523d9701683387ed51c9121d81bb14">llvm::orc::LinkGraphLinkingLayer::~LinkGraphLinkingLayer</a>.</p>

</div>
</div>

### dispatchTask() {#ad8bfb5f058b029cbcac70d97ed165b14}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::orc::ExecutionSession::dispatchTask (std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/task">Task</a> &gt; T)</td>
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

<p>Materialize the given unit.</p>

<p>Definition at line 1553 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a3fcdc9f30e5e8b9ea4da99868a8ae4a9">DEBUG_WITH_TYPE</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>

</div>
</div>

### dump() {#ac2f08336aef2526b897c029a94a2e054}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::orc::ExecutionSession::dump (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Dump the state of all the JITDylibs in this session.</p>

<p>Declaration at line 1682 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>, definition at line 1960 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/core-cpp">Core.cpp</a>.</p>


<p>Reference <a href="#ab9ce518e73ce35d17cd88e873776d51e">runSessionLocked</a>.</p>

</div>
</div>

### endSession() {#a0e640a50cc22c6992dca0f54a167e67e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::orc::ExecutionSession::endSession ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>End the session.</p>


<p>Closes all JITDylibs and disconnects from the executor. Clients must call this method before destroying the session.</p>


<p>Declaration at line 1381 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>, definition at line 1619 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/core-cpp">Core.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a71210b99d2ef87236d8505c1771a7ab1">llvm::joinErrors</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="#acfffb371a8a9e003f43cd5027cbea85d">removeJITDylibs</a> and <a href="#ab9ce518e73ce35d17cd88e873776d51e">runSessionLocked</a>.</p>

</div>
</div>

### getBootstrapMap() {#a8f9d8fde3719e8c1a7fcc4526a9029d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const StringMap&lt; std::vector&lt; char &gt; &gt; &amp; llvm::orc::ExecutionSession::getBootstrapMap ()</td>
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

<p>Returns the bootstrap map.</p>

<p>Definition at line 1560 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>.</p>

</div>
</div>

### getBootstrapMapValue() {#a7dc6e2659a199f1f2061aa6d2a4facc0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, typename SPSTagT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::orc::ExecutionSession::getBootstrapMapValue (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Key, std::optional&lt; T &gt; &amp; Val)</td>
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

<p>Look up and SPS-deserialize a bootstrap map value.</p>

<p>Definition at line 1566 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a98c6256d0644613c6b5b3e2ef06ef5ce">llvm::InnerAnalysisManagerProxy&lt; AnalysisManagerT, IRUnitT, ExtraArgTs... &gt;::Key</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/orc/lljit/#a392f906e72c6fa022d871e028e6f34b9">llvm::orc::LLJIT::setUpGenericLLVMIRPlatform</a>.</p>

</div>
</div>

### getBootstrapSymbols() {#a8d329fd9929dbb94bef42bb0c63b2057}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::orc::ExecutionSession::getBootstrapSymbols (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">ExecutorAddr</a> &amp;, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt; &gt; Pairs)</td>
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

<p>For each (<a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">ExecutorAddr</a>&amp;, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>) pair, looks up the string in the bootstrap symbols map and writes its address to the <a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">ExecutorAddr</a> if found.</p>


<p>If any symbol is not found then the function returns an error.</p>


<p>Definition at line 1578 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>.</p>

</div>
</div>

### getBootstrapSymbolsMap() {#a2e1f82feebf8b9217a8c84c204d75df0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const StringMap&lt; ExecutorAddr &gt; &amp; llvm::orc::ExecutionSession::getBootstrapSymbolsMap ()</td>
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

<p>Returns the bootstrap symbol map.</p>

<p>Definition at line 1571 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>.</p>

</div>
</div>

### getExecutorProcessControl() {#a128c42c13c6cee5b388a8748e6a0a797}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ExecutorProcessControl &amp; llvm::orc::ExecutionSession::getExecutorProcessControl ()</td>
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

<p>Get the <a href="/web-llvm/docs/api/classes/llvm/orc/executorprocesscontrol">ExecutorProcessControl</a> object associated with this <a href="/web-llvm/docs/api/classes/llvm/orc/executionsession">ExecutionSession</a>.</p>

<p>Definition at line 1385 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/orc/epcindirectionutils/#a2d4d7f7525cb9afe6a7f1c767e5f2599">llvm::orc::EPCIndirectionUtils::Create</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#ae53a8455d8df0ace36f281ea470736c6">llvm::orc::createJITLoaderGDBRegistrar</a> and <a href="/web-llvm/docs/api/classes/llvm/orc/epcdynamiclibrarysearchgenerator/#a0be4b6ee27375703c0be30f0b730d0ba">llvm::orc::EPCDynamicLibrarySearchGenerator::Load</a>.</p>

</div>
</div>

### getJITDylibByName() {#a4b12643704d05845fd7e0be447203a80}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">JITDylib * llvm::orc::ExecutionSession::getJITDylibByName (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return a pointer to the "name" <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a>.</p>


<p>Ownership of <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> remains within Execution Session</p>


<p>Declaration at line 1424 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>, definition at line 1658 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/core-cpp">Core.cpp</a>.</p>


<p>References <a href="#a235f764fe0f700836f89667ef5a0033b">JITDylib</a> and <a href="#ab9ce518e73ce35d17cd88e873776d51e">runSessionLocked</a>.</p>


<p>Referenced by <a href="#a6576b19a186104b0ee0d910ea472cab2">createBareJITDylib</a>.</p>

</div>
</div>

### getPageSize() {#ad55bb8cab312328752988e3e109a2d8e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::orc::ExecutionSession::getPageSize ()</td>
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



<p>Definition at line 1391 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>.</p>

</div>
</div>

### getPlatform() {#a3f4ecf8a077b821bd46887808f10fa6f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Platform * llvm::orc::ExecutionSession::getPlatform ()</td>
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

<p>Get the <a href="/web-llvm/docs/api/classes/llvm/orc/platform">Platform</a> for this session.</p>


<p>Will return null if no <a href="/web-llvm/docs/api/classes/llvm/orc/platform">Platform</a> has been set for this <a href="/web-llvm/docs/api/classes/llvm/orc/executionsession">ExecutionSession</a>.</p>


<p>Definition at line 1406 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>.</p>

</div>
</div>

### getSymbolStringPool() {#a7a0ff5426c14f13472ac39f815ad4206}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::shared_ptr&lt; SymbolStringPool &gt; llvm::orc::ExecutionSession::getSymbolStringPool ()</td>
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

<p>Get the <a href="/web-llvm/docs/api/classes/llvm/orc/symbolstringpool">SymbolStringPool</a> for this instance.</p>

<p>Definition at line 1394 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>.</p>

</div>
</div>

### getTargetTriple() {#a2f7fe16eea49478485f19ab0d096b257}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Triple &amp; llvm::orc::ExecutionSession::getTargetTriple ()</td>
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

<p>Return the triple for the executor.</p>

<p>Definition at line 1388 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/orc/#ab3b175f40b07ac581cc42fc835420d25">llvm::orc::createHeaderBlock</a>.</p>

</div>
</div>

### intern() {#a4a6187a7b7e11faffbcb0f788bd2543c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SymbolStringPtr llvm::orc::ExecutionSession::intern (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> SymName)</td>
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

<p>Add a symbol name to the <a href="/web-llvm/docs/api/classes/llvm/orc/symbolstringpool">SymbolStringPool</a> and return a pointer to it.</p>

<p>Definition at line 1399 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a82f74a53afe9225468960223f8d96c46">llvm::orc::addAliases</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a1f5a1bc60c220cdccbab0f26b2a425e1">llvm::orc::addInitSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/gdbjitdebuginforegistrationplugin/#a2868e0d3f63a589a13f32d7ab7d90150">llvm::orc::GDBJITDebugInfoRegistrationPlugin::Create</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#aeeec63b61f99af14a9ca2c631e6b9cec">llvm::orc::getCOFFObjectFileSymbolInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a5943e7713622fd9365b27abfefd1703f">llvm::orc::getELFObjectFileSymbolInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a46b8e71e338ddab38e9a33ed9502a3a2">llvm::orc::getGenericObjectFileSymbolInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a2143f8386a6b8bcb33011fdd240c38f1">llvm::orc::getMachOObjectFileSymbolInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/irmaterializationunit/#a6ba5ee0773bcb7bf0614f9ae9f010198">llvm::orc::IRMaterializationUnit::IRMaterializationUnit</a> and <a href="#a82b549cec73af340fdd4b80c97b43c74">lookup</a>.</p>

</div>
</div>

### lookup() {#a9260560ad3aaa612b92cff4bccd3c223}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::orc::ExecutionSession::lookup (<a href="/web-llvm/docs/api/namespaces/llvm/orc/#ac17672ae6b70c781cc77713e88d698eb">LookupKind</a> K, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a1a2b573da544cf233d62075a16146245">JITDylibSearchOrder</a> &amp; SearchOrder, <a href="/web-llvm/docs/api/classes/llvm/orc/symbollookupset">SymbolLookupSet</a> Symbols, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#adac25fca9fb14b1defe43d18a81c16e8">SymbolState</a> RequiredState, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#af196a28010b167850a05fc95aa763418">SymbolsResolvedCallback</a> NotifyComplete, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a417b487970e79367118330a5587c8775">RegisterDependenciesFunction</a> RegisterDependencies)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Search the given JITDylibs for the given symbols.</p>


<p>SearchOrder lists the JITDylibs to search. For each dylib, the associated boolean indicates whether the search should match against non-exported (hidden visibility) symbols in that dylib (true means match against non-exported symbols, false means do not match).</p>


<p>The NotifyComplete callback will be called once all requested symbols reach the required state.</p>


<p>If all symbols are found, the RegisterDependencies function will be called while the session lock is held. This gives clients a chance to register dependencies for on the queried symbols for any symbols they are materializing (if a <a href="/web-llvm/docs/api/classes/llvm/orc/materializationresponsibility">MaterializationResponsibility</a> instance is present, this can be implemented by calling MaterializationResponsibility::addDependencies). If there are no dependenant symbols for this query (e.g. it is being made by a top level client to get an address to call) then the value NoDependenciesToRegister can be used.</p>


<p>Declaration at line 1512 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>, definition at line 1805 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/core-cpp">Core.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="#ab9ce518e73ce35d17cd88e873776d51e">runSessionLocked</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/orc/gdbjitdebuginforegistrationplugin/#a2868e0d3f63a589a13f32d7ab7d90150">llvm::orc::GDBJITDebugInfoRegistrationPlugin::Create</a>, <a href="#a82b549cec73af340fdd4b80c97b43c74">lookup</a>, <a href="#ad174864e2ec81bda9cbcb1c18eeab3cd">lookup</a>, <a href="#adcd2edb47f46a28037d9f738f0cd1aa8">lookup</a>, <a href="#a7492b1c8aaacb6f0dd1d30a0823d7bc2">lookup</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a8099b2810ee3dbc4cb1a1efdafcb4dfb">llvm::orc::lookupAndRecordAddrs</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/platform/#aded9cbc2f7fa64fbbdf4f5ce8f826dd5">llvm::orc::Platform::lookupInitSymbols</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/platform/#a5f5de33429dae751bbf618940ff67e01">llvm::orc::Platform::lookupInitSymbolsAsync</a> and <a href="#a9af5ee3a848ca02c351ee7ffca01c3f0">registerJITDispatchHandlers</a>.</p>

</div>
</div>

### lookup() {#adcd2edb47f46a28037d9f738f0cd1aa8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; SymbolMap &gt; llvm::orc::ExecutionSession::lookup (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a1a2b573da544cf233d62075a16146245">JITDylibSearchOrder</a> &amp; SearchOrder, <a href="/web-llvm/docs/api/classes/llvm/orc/symbollookupset">SymbolLookupSet</a> Symbols, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#ac17672ae6b70c781cc77713e88d698eb">LookupKind</a> K=<a href="/web-llvm/docs/api/namespaces/llvm/orc/#ac17672ae6b70c781cc77713e88d698eba84a8921b25f505d0d2077aeb5db4bc16">LookupKind::Static</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#adac25fca9fb14b1defe43d18a81c16e8">SymbolState</a> RequiredState=<a href="/web-llvm/docs/api/namespaces/llvm/orc/#adac25fca9fb14b1defe43d18a81c16e8ae7d31fc0602fb2ede144d18cdffd816b">SymbolState::Ready</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a417b487970e79367118330a5587c8775">RegisterDependenciesFunction</a> RegisterDependencies=<a href="/web-llvm/docs/api/namespaces/llvm/orc/#ac8dd8c429957b970e617afb500775d99">NoDependenciesToRegister</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Blocking version of lookup above.</p>


<p>Returns the resolved symbol map. If WaitUntilReady is true (the default), will not return until all requested symbols are ready (or an error occurs). If WaitUntilReady is false, will return as soon as all requested symbols are resolved, or an error occurs. If WaitUntilReady is false and an error occurs after resolution, the function will return a success value, but the error will be reported via reportErrors.</p>


<p>Declaration at line 1524 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>, definition at line 1835 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/core-cpp">Core.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmccodeemitter-cpp/#ae4dfd7b0d66121016d6466d2ff10e8ba">_</a>, <a href="#a9260560ad3aaa612b92cff4bccd3c223">lookup</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a1448b52253eb43f8f07b7f5d94336a47a8eea62084ca7e541d918e823422bd82e">llvm::orc::Result</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

### lookup() {#a7492b1c8aaacb6f0dd1d30a0823d7bc2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; ExecutorSymbolDef &gt; llvm::orc::ExecutionSession::lookup (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a1a2b573da544cf233d62075a16146245">JITDylibSearchOrder</a> &amp; SearchOrder, <a href="/web-llvm/docs/api/classes/llvm/orc/symbolstringptr">SymbolStringPtr</a> Symbol, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#adac25fca9fb14b1defe43d18a81c16e8">SymbolState</a> RequiredState=<a href="/web-llvm/docs/api/namespaces/llvm/orc/#adac25fca9fb14b1defe43d18a81c16e8ae7d31fc0602fb2ede144d18cdffd816b">SymbolState::Ready</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Convenience version of blocking lookup.</p>


<p>Searches each of the JITDylibs in the search order in turn for the given symbol.</p>


<p>Declaration at line 1535 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>, definition at line 1875 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/core-cpp">Core.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a9260560ad3aaa612b92cff4bccd3c223">lookup</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#ac8dd8c429957b970e617afb500775d99">llvm::orc::NoDependenciesToRegister</a> and <a href="/web-llvm/docs/api/namespaces/llvm/orc/#ac17672ae6b70c781cc77713e88d698eba84a8921b25f505d0d2077aeb5db4bc16">llvm::orc::Static</a>.</p>

</div>
</div>

### lookup() {#ad174864e2ec81bda9cbcb1c18eeab3cd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; ExecutorSymbolDef &gt; llvm::orc::ExecutionSession::lookup (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> * &gt; SearchOrder, <a href="/web-llvm/docs/api/classes/llvm/orc/symbolstringptr">SymbolStringPtr</a> Symbol, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#adac25fca9fb14b1defe43d18a81c16e8">SymbolState</a> RequiredState=<a href="/web-llvm/docs/api/namespaces/llvm/orc/#adac25fca9fb14b1defe43d18a81c16e8ae7d31fc0602fb2ede144d18cdffd816b">SymbolState::Ready</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Convenience version of blocking lookup.</p>


<p>Searches each of the JITDylibs in the search order in turn for the given symbol. The search will not find non-exported symbols.</p>


<p>Declaration at line 1542 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>, definition at line 1889 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/core-cpp">Core.cpp</a>.</p>


<p>References <a href="#a9260560ad3aaa612b92cff4bccd3c223">lookup</a> and <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a14f663a8d190b740cfb9cbf0d88a7619">llvm::orc::makeJITDylibSearchOrder</a>.</p>

</div>
</div>

### lookup() {#a82b549cec73af340fdd4b80c97b43c74}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; ExecutorSymbolDef &gt; llvm::orc::ExecutionSession::lookup (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> * &gt; SearchOrder, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Symbol, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#adac25fca9fb14b1defe43d18a81c16e8">SymbolState</a> RequiredState=<a href="/web-llvm/docs/api/namespaces/llvm/orc/#adac25fca9fb14b1defe43d18a81c16e8ae7d31fc0602fb2ede144d18cdffd816b">SymbolState::Ready</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Convenience version of blocking lookup.</p>


<p>Searches each of the JITDylibs in the search order in turn for the given symbol. The search will not find non-exported symbols.</p>


<p>Declaration at line 1549 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>, definition at line 1895 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/core-cpp">Core.cpp</a>.</p>


<p>References <a href="#a4a6187a7b7e11faffbcb0f788bd2543c">intern</a> and <a href="#a9260560ad3aaa612b92cff4bccd3c223">lookup</a>.</p>

</div>
</div>

### lookupFlags() {#a432a464dcfc79515467f0ddefd78fc83}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::orc::ExecutionSession::lookupFlags (<a href="/web-llvm/docs/api/namespaces/llvm/orc/#ac17672ae6b70c781cc77713e88d698eb">LookupKind</a> K, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a1a2b573da544cf233d62075a16146245">JITDylibSearchOrder</a> SearchOrder, <a href="/web-llvm/docs/api/classes/llvm/orc/symbollookupset">SymbolLookupSet</a> Symbols, <a href="/web-llvm/docs/api/classes/llvm/unique-function">unique_function</a>&lt; void(<a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/orc/#afd6431981e7fdfd4b5d2794f04d7d913">SymbolFlagsMap</a> &gt;)&gt; OnComplete)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Search the given JITDylibs to find the flags associated with each of the given symbols.</p>

<p>Declaration at line 1484 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>, definition at line 1779 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/core-cpp">Core.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/orc/#afbfe38269b7efe5437ce0b6b9dfea10e">llvm::orc::buildSimpleReexportsAliasMap</a> and <a href="/web-llvm/docs/api/classes/llvm/orc/reexportsgenerator/#a9b1cc5b369f4fd3e04b66035eea7c481">llvm::orc::ReexportsGenerator::tryToGenerate</a>.</p>

</div>
</div>

### lookupFlags() {#a081a578f073d014fe2b1ba2c15b8b5c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; SymbolFlagsMap &gt; llvm::orc::ExecutionSession::lookupFlags (<a href="/web-llvm/docs/api/namespaces/llvm/orc/#ac17672ae6b70c781cc77713e88d698eb">LookupKind</a> K, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a1a2b573da544cf233d62075a16146245">JITDylibSearchOrder</a> SearchOrder, <a href="/web-llvm/docs/api/classes/llvm/orc/symbollookupset">SymbolLookupSet</a> Symbols)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Blocking version of lookupFlags.</p>

<p>Declaration at line 1489 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>, definition at line 1790 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/core-cpp">Core.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/expected/#ad26ecbb6920f4ea55f5ed4f64e52342d">llvm::Expected&lt; T &gt;::get</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a1448b52253eb43f8f07b7f5d94336a47a8eea62084ca7e541d918e823422bd82e">llvm::orc::Result</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

### registerJITDispatchHandlers() {#a9af5ee3a848ca02c351ee7ffca01c3f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::orc::ExecutionSession::registerJITDispatchHandlers (<a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> &amp; JD, <a href="#af7397131e1a9a35a7ccdf6254f6684dd">JITDispatchHandlerAssociationMap</a> WFs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>For each tag symbol name, associate the corresponding AsyncHandlerWrapperFunction with the address of that symbol.</p>


<p>The handler becomes callable from the executor using the ORC runtime __orc_rt_jit_dispatch function and the given tag.</p>


<p>Tag symbols will be looked up in JD using <a href="/web-llvm/docs/api/namespaces/llvm/orc/#ac17672ae6b70c781cc77713e88d698eba84a8921b25f505d0d2077aeb5db4bc16">LookupKind::Static</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a7cb1d8cb0ab2329f032d69d79498c81da5fa8627bea3ff4b720673b9a298caf2d">JITDylibLookupFlags::MatchAllSymbols</a> (hidden tags will be found), and LookupFlags::WeaklyReferencedSymbol. Missing tag definitions will not cause an error, the handler will simply be dropped.</p>


<p>Declaration at line 1671 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>, definition at line 1900 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/core-cpp">Core.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a65520b9c67759099e313d0f4e7b5ff9e">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::end</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a0c047f127ed4380a6f383d70bec4eb94">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::find</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a653cce37b80c03eebe7a00520a8eabb6">llvm::formatv</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/symbollookupset/#a6629c18fc56cc2897b069edcdd23f35d">llvm::orc::SymbolLookupSet::fromMapKeys</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2b43c21951d0948b34bcf7019949032d">llvm::inconvertibleErrorCode</a>, <a href="#a235f764fe0f700836f89667ef5a0033b">JITDylib</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="#a9260560ad3aaa612b92cff4bccd3c223">lookup</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a7cb1d8cb0ab2329f032d69d79498c81da5fa8627bea3ff4b720673b9a298caf2d">llvm::orc::MatchAllSymbols</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a> and <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a69e9511c04540297d2cff38f4645a9aba26a03cdefe35519715a4b6d564c9c9c7">llvm::orc::WeaklyReferencedSymbol</a>.</p>

</div>
</div>

### registerResourceManager() {#aa00c8d49e29326e8271a16b3f782b8a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::orc::ExecutionSession::registerResourceManager (<a href="/web-llvm/docs/api/classes/llvm/orc/resourcemanager">ResourceManager</a> &amp; RM)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/register">Register</a> the given <a href="/web-llvm/docs/api/classes/llvm/orc/resourcemanager">ResourceManager</a> with this <a href="/web-llvm/docs/api/classes/llvm/orc/executionsession">ExecutionSession</a>.</p>


<p>Managers will be notified of events in reverse order of registration.</p>


<p>Declaration at line 1416 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>, definition at line 1641 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/core-cpp">Core.cpp</a>.</p>


<p>Reference <a href="#ab9ce518e73ce35d17cd88e873776d51e">runSessionLocked</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/orc/rtdyldobjectlinkinglayer/#a265854b41dc442be1d29e1a5b7043cc4">llvm::orc::RTDyldObjectLinkingLayer::RTDyldObjectLinkingLayer</a>.</p>

</div>
</div>

### removeJITDylib() {#aea3c986d513f0b7352d5494f36f2cf23}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::orc::ExecutionSession::removeJITDylib (<a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> &amp; JD)</td>
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

<p>Calls removeJTIDylibs on the gives <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a>.</p>

<p>Definition at line 1467 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>.</p>


<p>References <a href="#a235f764fe0f700836f89667ef5a0033b">JITDylib</a> and <a href="#acfffb371a8a9e003f43cd5027cbea85d">removeJITDylibs</a>.</p>

</div>
</div>

### removeJITDylibs() {#acfffb371a8a9e003f43cd5027cbea85d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::orc::ExecutionSession::removeJITDylibs (std::vector&lt; <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a1baadbec01aced37be13a1b86c76397e">JITDylibSP</a> &gt; JDsToRemove)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Removes the given JITDylibs from the <a href="/web-llvm/docs/api/classes/llvm/orc/executionsession">ExecutionSession</a>.</p>


<p>This method clears all resources held for the JITDylibs, puts them in the closed state, and clears all references to them that are held by the <a href="/web-llvm/docs/api/classes/llvm/orc/executionsession">ExecutionSession</a> or other JITDylibs. No further code can be added to the removed JITDylibs, and the <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> objects will be freed once any remaining JITDylibSPs pointing to them are destroyed.</p>


<p>This method does <em>not</em> run static destructors for code contained in the JITDylibs, and each <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> can only be removed once.</p>


<p>JITDylibs will be removed in the order given. Teardown is usually independent for each <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a>, but not always. In particular, where the ORC runtime is used it is expected that teardown off all JITDylibs will depend on it, so the <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> containing the ORC runtime must be removed last. If the client has introduced any other dependencies they should be accounted for in the removal order too.</p>


<p>Declaration at line 1464 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>, definition at line 1684 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/core-cpp">Core.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a086e9fbdb06276db7753101a08a63adf">llvm::find</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a71210b99d2ef87236d8505c1771a7ab1">llvm::joinErrors</a>, <a href="#ab9ce518e73ce35d17cd88e873776d51e">runSessionLocked</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>


<p>Referenced by <a href="#a0e640a50cc22c6992dca0f54a167e67e">endSession</a> and <a href="#aea3c986d513f0b7352d5494f36f2cf23">removeJITDylib</a>.</p>

</div>
</div>

### reportError() {#a1c47ed6ddfb6770f1a432af1c9acdc44}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::orc::ExecutionSession::reportError (<a href="/web-llvm/docs/api/classes/llvm/error">Error</a> Err)</td>
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

<p>Report a error for this execution session.</p>


<p>Unhandled errors can be sent here to log them.</p>


<p>Definition at line 1480 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/orc/compileondemandlayer/#a58cc5a656f5d4cc0a32d58494dcb860b">llvm::orc::CompileOnDemandLayer::emit</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/ircompilelayer/#a176fd0ce1f0e28e675e04c05c7716a03">llvm::orc::IRCompileLayer::emit</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/irtransformlayer/#a6f4ae51591df573638504e97f54a5321">llvm::orc::IRTransformLayer::emit</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-perfsupportplugin-cpp-/#a55e3f6a5c003de75eabd889a24709857">anonymous{PerfSupportPlugin.cpp}::getRecords</a> and <a href="/web-llvm/docs/api/classes/llvm/orc/speculator/#ad197c9995bf568c245d6f7e753320f64">llvm::orc::Speculator::registerSymbols</a>.</p>

</div>
</div>

### runJITDispatchHandler() {#ab04dd8530994d3914c2398c5105bd74b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::orc::ExecutionSession::runJITDispatchHandler (<a href="#a17aab624111677f277ae5a453930e29d">SendResultFunction</a> SendResult, <a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">ExecutorAddr</a> HandlerFnTagAddr, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; char &gt; ArgBuffer)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Run a registered jit-side wrapper function.</p>


<p>This should be called by the <a href="/web-llvm/docs/api/classes/llvm/orc/executorprocesscontrol">ExecutorProcessControl</a> instance in response to incoming jit-dispatch requests from the executor.</p>


<p>Declaration at line 1677 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>, definition at line 1939 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/core-cpp">Core.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/orc/shared/wrapperfunctionresult/#ae0a341aa5651a0e6b296119ad73cdef5">llvm::orc::shared::WrapperFunctionResult::createOutOfBandError</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#adb9cab4abca6bf2855c882dcf79fb1cb">llvm::ArrayRef&lt; T &gt;::data</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a653cce37b80c03eebe7a00520a8eabb6">llvm::formatv</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a>.</p>

</div>
</div>

### runSessionLocked() {#ab9ce518e73ce35d17cd88e873776d51e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Func&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">decltype(auto) llvm::orc::ExecutionSession::runSessionLocked (Func &amp;&amp; F)</td>
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

<p>Run the given lambda with the session mutex locked.</p>

<p>Definition at line 1409 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>.</p>


<p>Referenced by <a href="#a6576b19a186104b0ee0d910ea472cab2">createBareJITDylib</a>, <a href="#ab58270d4adca4a62c6721739e0f4c725">deregisterResourceManager</a>, <a href="#ac2f08336aef2526b897c029a94a2e054">dump</a>, <a href="#a0e640a50cc22c6992dca0f54a167e67e">endSession</a>, <a href="#a4b12643704d05845fd7e0be447203a80">getJITDylibByName</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/lazyreexportsmanager/#a8e035d19beaac11de143eeeec21f646b">llvm::orc::LazyReexportsManager::handleRemoveResources</a>, <a href="#a9260560ad3aaa612b92cff4bccd3c223">lookup</a>, <a href="#aa00c8d49e29326e8271a16b3f782b8a4">registerResourceManager</a>, <a href="#acfffb371a8a9e003f43cd5027cbea85d">removeJITDylibs</a> and <a href="/web-llvm/docs/api/classes/llvm/orc/resourcetracker/#ac946e909dda8f139167b7d28956f1e51">llvm::orc::ResourceTracker::withResourceKeyDo</a>.</p>

</div>
</div>

### setErrorReporter() {#ac50b6783239033bb5f3a8ca749d361a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ExecutionSession &amp; llvm::orc::ExecutionSession::setErrorReporter (<a href="#adba3b8e588f1c96678fa1c9a328a4b74">ErrorReporter</a> ReportError)</td>
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

<p>Set the error reporter function.</p>

<p>Definition at line 1472 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>.</p>


<p>Reference <a href="#ab90eb7cd1f407e51a5c2d3ab2c81c9ab">ExecutionSession</a>.</p>

</div>
</div>

### setPlatform() {#a2ed4129361eccda71fea45447353df4a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::orc::ExecutionSession::setPlatform (std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/platform">Platform</a> &gt; P)</td>
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

<p>Set the <a href="/web-llvm/docs/api/classes/llvm/orc/platform">Platform</a> for this <a href="/web-llvm/docs/api/classes/llvm/orc/executionsession">ExecutionSession</a>.</p>

<p>Definition at line 1402 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/orc/executornativeplatform/#aa1bd92add845031ceeaab24c2c25c275">llvm::orc::ExecutorNativePlatform::operator()</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### destroyResourceTracker() {#a269ff1140f5ab89e15cc12de1a3774db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::orc::ExecutionSession::destroyResourceTracker (<a href="/web-llvm/docs/api/classes/llvm/orc/resourcetracker">ResourceTracker</a> &amp; RT)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1710 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>, definition at line 2240 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/core-cpp">Core.cpp</a>.</p>

</div>
</div>

### dispatchOutstandingMUs() {#aca1b144fe5a6bca1ddf699fc0b0c9536}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::orc::ExecutionSession::dispatchOutstandingMUs ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1694 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>, definition at line 2157 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/core-cpp">Core.cpp</a>.</p>

</div>
</div>

### dumpDispatchInfo() {#a1a043f02f0755d5d449a6c928347e79b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::orc::ExecutionSession::dumpDispatchInfo (<a href="/web-llvm/docs/api/classes/llvm/orc/task">Task</a> &amp; T)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1791 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>, definition at line 3775 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/core-cpp">Core.cpp</a>.</p>

</div>
</div>

### IL\_emit() {#a6fa69b39d88044cabe30f83ea6cd87b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; JITDylib::AsynchronousSymbolQuerySet &gt; llvm::orc::ExecutionSession::IL_emit (<a href="/web-llvm/docs/api/classes/llvm/orc/materializationresponsibility">MaterializationResponsibility</a> &amp; MR, <a href="/web-llvm/docs/api/classes/llvm/densemap">EDUInfosMap</a> EDUInfos)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1774 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>, definition at line 3273 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/core-cpp">Core.cpp</a>.</p>

</div>
</div>

### IL\_failSymbols() {#a417dd9ff3ab2220247d409664474dfd4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; JITDylib::AsynchronousSymbolQuerySet, std::shared_ptr&lt; SymbolDependenceMap &gt; &gt; llvm::orc::ExecutionSession::IL_failSymbols (<a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> &amp; JD, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/orc/#ac98d5bff2f1ce6c3ce250c347f7b86ee">SymbolNameVector</a> &amp; SymbolsToFail)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1783 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>, definition at line 3532 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/core-cpp">Core.cpp</a>.</p>

</div>
</div>

### IL\_makeEDUEmitted() {#a9bc9002a9763b7f22513b5b05d6a8b9c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::orc::ExecutionSession::IL_makeEDUEmitted (std::shared_ptr&lt; JITDylib::EmissionDepUnit &gt; EDU, JITDylib::AsynchronousSymbolQuerySet &amp; Queries)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1762 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>, definition at line 3152 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/core-cpp">Core.cpp</a>.</p>

</div>
</div>

### IL\_makeEDUReady() {#a08b0690d6869653e86b27b2c463fa69e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::orc::ExecutionSession::IL_makeEDUReady (std::shared_ptr&lt; JITDylib::EmissionDepUnit &gt; EDU, JITDylib::AsynchronousSymbolQuerySet &amp; Queries)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1760 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>, definition at line 3112 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/core-cpp">Core.cpp</a>.</p>

</div>
</div>

### IL\_removeEDUDependence() {#ad4e4077c95ffd2509d58fac2e016da9f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::orc::ExecutionSession::IL_removeEDUDependence (JITDylib::EmissionDepUnit &amp; EDU, <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> &amp; DepJD, <a href="/web-llvm/docs/api/classes/llvm/orc/nonowningsymbolstringptr">NonOwningSymbolStringPtr</a> DepSym, <a href="/web-llvm/docs/api/classes/llvm/densemap">EDUInfosMap</a> &amp; EDUInfos)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Removes the given dependence from EDU.</p>


<p>If EDU's dependence set becomes empty then this function adds an entry for it to the EDUInfos map. Returns true if a new EDUInfosMap entry is added.</p>


<p>Declaration at line 1764 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>, definition at line 3210 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/core-cpp">Core.cpp</a>.</p>

</div>
</div>

### IL\_updateCandidatesFor() {#ae2148bb327434662fa22d80ac9f597cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::orc::ExecutionSession::IL_updateCandidatesFor (<a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> &amp; JD, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a7cb1d8cb0ab2329f032d69d79498c81d">JITDylibLookupFlags</a> JDLookupFlags, <a href="/web-llvm/docs/api/classes/llvm/orc/symbollookupset">SymbolLookupSet</a> &amp; Candidates, <a href="/web-llvm/docs/api/classes/llvm/orc/symbollookupset">SymbolLookupSet</a> * NonCandidates)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>IL_updateCandidatesFor is called to remove already-defined symbols that match a given query from the set of candidate symbols to generate definitions for (no need to generate a definition if one already exists).</p>

<p>Declaration at line 1717 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>, definition at line 2252 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/core-cpp">Core.cpp</a>.</p>

</div>
</div>

### OL\_applyQueryPhase1() {#a0e8b7e68830d4b07218b212ae1726f9b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::orc::ExecutionSession::OL_applyQueryPhase1 (std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/inprogresslookupstate">InProgressLookupState</a> &gt; IPLS, <a href="/web-llvm/docs/api/classes/llvm/error">Error</a> Err)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>OL_applyQueryPhase1 is an optionally re-startable loop for triggering definition generation.</p>


<p>It is called when a lookup is performed, and again each time that <a href="/web-llvm/docs/api/classes/llvm/orc/lookupstate/#a41c2b3ba48abc4a30b5c005b6ce97c18">LookupState::continueLookup</a> is called.</p>


<p>Declaration at line 1727 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>, definition at line 2331 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/core-cpp">Core.cpp</a>.</p>

</div>
</div>

### OL\_completeLookup() {#a72aa0428f1be4bec174659b6a4223243}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::orc::ExecutionSession::OL_completeLookup (std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/inprogresslookupstate">InProgressLookupState</a> &gt; IPLS, std::shared_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/asynchronoussymbolquery">AsynchronousSymbolQuery</a> &gt; Q, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a417b487970e79367118330a5587c8775">RegisterDependenciesFunction</a> RegisterDependencies)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>OL_completeLookup is run once phase 1 successfully completes for a lookup call.</p>


<p>It attempts to attach the symbol to all symbol table entries and collect all MaterializationUnits to dispatch. If this method fails then all MaterializationUnits will be left un-materialized.</p>


<p>Declaration at line 1734 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>, definition at line 2553 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/core-cpp">Core.cpp</a>.</p>

</div>
</div>

### OL\_completeLookupFlags() {#acda211f1192be4f99cec578358c4330b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::orc::ExecutionSession::OL_completeLookupFlags (std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/inprogresslookupstate">InProgressLookupState</a> &gt; IPLS, <a href="/web-llvm/docs/api/classes/llvm/unique-function">unique_function</a>&lt; void(<a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/orc/#afd6431981e7fdfd4b5d2794f04d7d913">SymbolFlagsMap</a> &gt;)&gt; OnComplete)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>OL_completeLookupFlags is run once phase 1 successfully completes for a lookupFlags call.</p>

<p>Declaration at line 1740 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>, definition at line 2800 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/core-cpp">Core.cpp</a>.</p>

</div>
</div>

### OL\_defineMaterializing() {#a4a1cd2d300724b17a4e153521018a569}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::orc::ExecutionSession::OL_defineMaterializing (<a href="/web-llvm/docs/api/classes/llvm/orc/materializationresponsibility">MaterializationResponsibility</a> &amp; MR, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#afd6431981e7fdfd4b5d2794f04d7d913">SymbolFlagsMap</a> SymbolFlags)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1778 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>, definition at line 3513 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/core-cpp">Core.cpp</a>.</p>

</div>
</div>

### OL\_delegate() {#ac007e3f39220799f76fdde09edbfdedf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; std::unique_ptr&lt; MaterializationResponsibility &gt; &gt; llvm::orc::ExecutionSession::OL_delegate (<a href="/web-llvm/docs/api/classes/llvm/orc/materializationresponsibility">MaterializationResponsibility</a> &amp; MR, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/orc/#ada98b2ca88b7bc4b65b62e3269fdade7">SymbolNameSet</a> &amp; Symbols)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1788 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>, definition at line 3751 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/core-cpp">Core.cpp</a>.</p>

</div>
</div>

### OL\_destroyMaterializationResponsibility() {#a1419ca3ed095c6d3628e17889b954302}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::orc::ExecutionSession::OL_destroyMaterializationResponsibility (<a href="/web-llvm/docs/api/classes/llvm/orc/materializationresponsibility">MaterializationResponsibility</a> &amp; MR)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1745 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>, definition at line 2881 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/core-cpp">Core.cpp</a>.</p>

</div>
</div>

### OL\_getRequestedSymbols() {#afcebe1dd3ded04d8461c2b8f452f1b38}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SymbolNameSet llvm::orc::ExecutionSession::OL_getRequestedSymbols (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/orc/materializationresponsibility">MaterializationResponsibility</a> &amp; MR)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1747 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>, definition at line 2889 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/core-cpp">Core.cpp</a>.</p>

</div>
</div>

### OL\_notifyEmitted() {#ad324fd8a995fae88a5f35e9113754ddd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::orc::ExecutionSession::OL_notifyEmitted (<a href="/web-llvm/docs/api/classes/llvm/orc/materializationresponsibility">MaterializationResponsibility</a> &amp; MR, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/orc/symboldependencegroup">SymbolDependenceGroup</a> &gt; EmittedDeps)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1775 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>, definition at line 3449 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/core-cpp">Core.cpp</a>.</p>

</div>
</div>

### OL\_notifyFailed() {#ae332efd0c821345a2d951d5c2ae15831}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::orc::ExecutionSession::OL_notifyFailed (<a href="/web-llvm/docs/api/classes/llvm/orc/materializationresponsibility">MaterializationResponsibility</a> &amp; MR)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1784 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>, definition at line 3700 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/core-cpp">Core.cpp</a>.</p>

</div>
</div>

### OL\_notifyResolved() {#a8365b2bcd03a5a91b23c0a73ecd9db40}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::orc::ExecutionSession::OL_notifyResolved (<a href="/web-llvm/docs/api/classes/llvm/orc/materializationresponsibility">MaterializationResponsibility</a> &amp; MR, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a8ab9a099de556e888c5f92a4fe49d2fa">SymbolMap</a> &amp; Symbols)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1748 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>, definition at line 2894 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/core-cpp">Core.cpp</a>.</p>

</div>
</div>

### OL\_replace() {#ac158c16aadd06901bf857d1063e6b4f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::orc::ExecutionSession::OL_replace (<a href="/web-llvm/docs/api/classes/llvm/orc/materializationresponsibility">MaterializationResponsibility</a> &amp; MR, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/materializationunit">MaterializationUnit</a> &gt; MU)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1785 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>, definition at line 3731 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/core-cpp">Core.cpp</a>.</p>

</div>
</div>

### OL\_resumeLookupAfterGeneration() {#a5b1b5182ef79919f97f373d3530de3ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::orc::ExecutionSession::OL_resumeLookupAfterGeneration (<a href="/web-llvm/docs/api/classes/llvm/orc/inprogresslookupstate">InProgressLookupState</a> &amp; IPLS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Handle resumption of a lookup after entering a generator.</p>

<p>Declaration at line 1722 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>, definition at line 2300 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/core-cpp">Core.cpp</a>.</p>

</div>
</div>

### propagateExtraEmitDeps() {#a187cf981731ec3d4005d80f5d6554ae3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename HandleNewDepFn&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::orc::ExecutionSession::propagateExtraEmitDeps (std::deque&lt; JITDylib::EmissionDepUnit * &gt; Worklist, <a href="/web-llvm/docs/api/classes/llvm/densemap">EDUInfosMap</a> &amp; EDUInfos, HandleNewDepFn HandleNewDep)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1755 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>, definition at line 2923 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/core-cpp">Core.cpp</a>.</p>

</div>
</div>

### removeResourceTracker() {#a22f3f6c6c7b2b325a558c7091bd57a23}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::orc::ExecutionSession::removeResourceTracker (<a href="/web-llvm/docs/api/classes/llvm/orc/resourcetracker">ResourceTracker</a> &amp; RT)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1708 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>, definition at line 2183 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/core-cpp">Core.cpp</a>.</p>

</div>
</div>

### simplifyDepGroups() {#ac50770cf172ef50d861837f00de2eda4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ExecutionSession::EDUInfosMap llvm::orc::ExecutionSession::simplifyDepGroups (<a href="/web-llvm/docs/api/classes/llvm/orc/materializationresponsibility">MaterializationResponsibility</a> &amp; MR, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/orc/symboldependencegroup">SymbolDependenceGroup</a> &gt; EmittedDeps)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1758 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>, definition at line 2974 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/core-cpp">Core.cpp</a>.</p>

</div>
</div>

### transferResourceTracker() {#a7bcefb22f2ce0c0e25768f2d1f6353eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::orc::ExecutionSession::transferResourceTracker (<a href="/web-llvm/docs/api/classes/llvm/orc/resourcetracker">ResourceTracker</a> &amp; DstRT, <a href="/web-llvm/docs/api/classes/llvm/orc/resourcetracker">ResourceTracker</a> &amp; SrcRT)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1709 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>, definition at line 2215 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/core-cpp">Core.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### EPC {#aab5ce937f24141009d7b826ce6ab71ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;ExecutorProcessControl&gt; llvm::orc::ExecutionSession::EPC</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1796 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>.</p>

</div>
</div>

### JDs {#a32f1ca23e658d79234809d3783a7a7d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;JITDylibSP&gt; llvm::orc::ExecutionSession::JDs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1802 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>.</p>

</div>
</div>

### JITDispatchHandlers {#add5f7dbbb57e094b32d6671c0e7f4955}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;ExecutorAddr, std::shared_ptr&lt;JITDispatchHandlerFunction&gt; &gt; llvm::orc::ExecutionSession::JITDispatchHandlers</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1813 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>.</p>

</div>
</div>

### JITDispatchHandlersMutex {#a62203943e11b4460cb9e963a814c0a71}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::mutex llvm::orc::ExecutionSession::JITDispatchHandlersMutex</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel mutable">mutable</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1811 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>.</p>

</div>
</div>

### OutstandingMUs {#a520545ed5ee04051b38d3db356996550}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;std::pair&lt;std::unique_ptr&lt;MaterializationUnit&gt;, std::unique_ptr&lt;MaterializationResponsibility&gt; &gt; &gt; llvm::orc::ExecutionSession::OutstandingMUs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1809 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>.</p>

</div>
</div>

### OutstandingMUsMutex {#ac316d06356b878c9bd194880990fbccc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::recursive_mutex llvm::orc::ExecutionSession::OutstandingMUsMutex</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel mutable">mutable</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1806 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>.</p>

</div>
</div>

### P {#a0bf25e78e013a2ac7d597663c1782c2a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;Platform&gt; llvm::orc::ExecutionSession::P</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1797 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>.</p>

</div>
</div>

### ReportError {#ad3fcbd5f8f63ca4ad5e34875430923d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ErrorReporter llvm::orc::ExecutionSession::ReportError = logErrorsToStdErr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1798 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>.</p>

</div>
</div>

### ResourceManagers {#a49d7523a5c241742909ee74e12398d6b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;ResourceManager *&gt; llvm::orc::ExecutionSession::ResourceManagers</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1800 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>.</p>

</div>
</div>

### SessionMutex {#a03d0c8408c48080eafd72195d0252640}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::recursive_mutex llvm::orc::ExecutionSession::SessionMutex</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel mutable">mutable</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1794 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>.</p>

</div>
</div>

### SessionOpen {#a788b6c6d8b62ec8e2abca5e71fa93fc0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::orc::ExecutionSession::SessionOpen = <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1795 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### wrapAsyncWithSPS() {#a6d161dc24753bbe3581c27a63c8be151}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SPSSignature, typename HandlerT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">JITDispatchHandlerFunction llvm::orc::ExecutionSession::wrapAsyncWithSPS (HandlerT &amp;&amp; H)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Wrap a handler that takes concrete argument types (and a sender for a concrete return type) to produce an AsyncHandlerWrapperFunction.</p>


<p>Uses SPS to unpack the arguments and pack the result.</p>


<p>This function is intended to support easy construction of AsyncHandlerWrapperFunctions that can be associated with a tag (using registerJITDispatchHandler) and called from the executor.</p>


<p>Definition at line 1637 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ae42219072d798876e6b08e6b78614ff6">H</a>.</p>


<p>Referenced by <a href="#a5b938a04fc3a8b890dd28a52603549c7">wrapAsyncWithSPS</a>.</p>

</div>
</div>

### wrapAsyncWithSPS() {#a5b938a04fc3a8b890dd28a52603549c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SPSSignature, typename ClassT, typename... MethodArgTs&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">JITDispatchHandlerFunction llvm::orc::ExecutionSession::wrapAsyncWithSPS (ClassT * Instance, void(ClassT::*)(MethodArgTs...) Method)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Wrap a class method that takes concrete argument types (and a sender for a concrete return type) to produce an AsyncHandlerWrapperFunction.</p>


<p>Uses SPS to unpack the arguments and pack the result.</p>


<p>This function is intended to support easy construction of AsyncHandlerWrapperFunctions that can be associated with a tag (using registerJITDispatchHandler) and called from the executor.</p>


<p>Definition at line 1655 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a8cf1abfcc22cc04521e19405a53783b8">llvm::orc::Instance</a> and <a href="#a6d161dc24753bbe3581c27a63c8be151">wrapAsyncWithSPS</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Functions

### createMaterializationResponsibility() {#a594d054bdaa56e1ba7ad7eb984eae408}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; MaterializationResponsibility &gt; llvm::orc::ExecutionSession::createMaterializationResponsibility (<a href="/web-llvm/docs/api/classes/llvm/orc/resourcetracker">ResourceTracker</a> &amp; RT, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#afd6431981e7fdfd4b5d2794f04d7d913">SymbolFlagsMap</a> Symbols, <a href="/web-llvm/docs/api/classes/llvm/orc/symbolstringptr">SymbolStringPtr</a> InitSymbol)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1697 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>.</p>

</div>
</div>

### logErrorsToStdErr() {#a0b8d10c807c75d7006cca54132ef1816}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::orc::ExecutionSession::logErrorsToStdErr (<a href="/web-llvm/docs/api/classes/llvm/error">Error</a> Err)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> the internal consistency of <a href="/web-llvm/docs/api/classes/llvm/orc/executionsession">ExecutionSession</a> data structures.</p>

<p>Definition at line 1690 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>.</p>

</div>
</div>

### makeJDClosedError() {#a295917f758bb479917f96d055ed2c2a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::orc::ExecutionSession::makeJDClosedError (JITDylib::EmissionDepUnit &amp; EDU, <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> &amp; ClosedJD)</td>
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



<p>Declaration at line 1768 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>, definition at line 3244 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/core-cpp">Core.cpp</a>.</p>

</div>
</div>

### makeUnsatisfiedDepsError() {#ac29b8c6dde2f59637c683058f5b498c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::orc::ExecutionSession::makeUnsatisfiedDepsError (JITDylib::EmissionDepUnit &amp; EDU, <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> &amp; BadJD, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#ada98b2ca88b7bc4b65b62e3269fdade7">SymbolNameSet</a> BadDeps)</td>
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



<p>Declaration at line 1770 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>, definition at line 3258 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/core-cpp">Core.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/core-cpp">Core.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>

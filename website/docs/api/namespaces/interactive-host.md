---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/interactive-host
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# `interactive_host` Namespace



## Definition

<div class="doxyDefinition">
namespace interactive_host { ... }
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af0b6c53060991a300bbffea33a67a8aa">send</a> (io.BufferedWriter f, Union[int, float] value, log_reader.TensorSpec spec)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0eded48c2eef46879e2f4d0fd284238b">run_interactive</a> (str temp_rootname, Callable[[List[log_reader.TensorValue]], Union[int, float]] make_response, List[str] process_and_args)</td>
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




<pre><code>Utility for testing InteractiveModelRunner.

Use it from pass-specific tests by providing a main .py which calls this library's
`run_interactive` with an appropriate callback to provide advice.

From .ll tests, just call the above-mentioned main as a prefix to the opt/llc
invocation (with the appropriate flags enabling the interactive mode)

Examples:
test/Transforms/Inline/ML/interactive-mode.ll
test/CodeGen/MLRegAlloc/interactive-mode.ll
</code></pre>


<div class="doxySectionDef">

## Functions

### run\_interactive() {#a0eded48c2eef46879e2f4d0fd284238b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">interactive_host.run_interactive (str temp_rootname, Callable] make_response=[[List[log_reader.TensorValue], Union] process_and_args=[int, float], List process_and_args=[str])</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">





<pre><code>Host the compiler.
Args:
  temp_rootname: the base file name from which to construct the 2 pipes for
  communicating with the compiler.
  make_response: a function that, given the current tensor values, provides a
  response.
  process_and_args: the full commandline for the compiler. It it assumed it
  contains a flag poiting to `temp_rootname` so that the InteractiveModeRunner
  would attempt communication on the same pair as this function opens.

This function sets up the communication with the compiler - via 2 files named
`temp_rootname`.in and `temp_rootname`.out - prints out the received features,
and sends back to the compiler an advice (which it gets from `make_response`).
It's used for testing, and also to showcase how to set up communication in an
interactive ML ("gym") environment.
</code></pre>


<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/lib/analysis/models/interactive-host-py">interactive_host.py</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/log-reader/#a14b90855a54de6f662b45732cb262314">log_reader.pretty_print_tensor_value</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/archivewriter-cpp/#aa9f638c7ae7fdd206a6c60e26bef9751">print</a>, <a href="/web-llvm/docs/api/namespaces/log-reader/#ab40242c357e077a78fbfb8fd4a61cf90">log_reader.read_header</a>, <a href="/web-llvm/docs/api/namespaces/log-reader/#a224d6d585cf78a7b3baeaa7474fffc13">log_reader.read_one_observation</a> and <a href="#af0b6c53060991a300bbffea33a67a8aa">send</a>.</p>

</div>
</div>

### send() {#af0b6c53060991a300bbffea33a67a8aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">interactive_host.send (io.BufferedWriter f, Union value=[int, float], <a href="/web-llvm/docs/api/classes/log-reader/tensorspec">log_reader.TensorSpec</a> spec)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">





<pre><code>Send the `value` - currently just a scalar - formatted as per `spec`.
</code></pre>


<p>Definition at line 23 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/lib/analysis/models/interactive-host-py">interactive_host.py</a>.</p>


<p>Referenced by <a href="#a0eded48c2eef46879e2f4d0fd284238b">run_interactive</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/analysis/lib/analysis/models/interactive-host-py">interactive_host.py</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>

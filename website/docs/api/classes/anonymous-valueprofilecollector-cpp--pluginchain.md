---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-valueprofilecollector-cpp-/pluginchain
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `PluginChain` Class Template Reference

<p>A plugin-based class that takes an arbitrary number of Plugin types. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;class... Ts&gt;
class anonymous{ValueProfileCollector.cpp}::PluginChain&lt;Ts&gt; { ... }
</div>

## Description {#details}

<p>A plugin-based class that takes an arbitrary number of Plugin types.</p>


<p>Each plugin type must satisfy the following API: 1) the constructor must take a <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp;f</span>. Typically, the plugin would scan the function looking for candidates. 2) contain a member function with the following signature and name: void run(std::vector&lt;CandidateInfo&gt; &amp;Candidates); such that the plugin would append its result into the vector parameter.</p>


<p>Plugins are defined in <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/valueprofileplugins-inc">ValueProfilePlugins.inc</a></p>


<p>Definition at line 30 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/valueprofilecollector-cpp">ValueProfileCollector.cpp</a>.</p>


<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>

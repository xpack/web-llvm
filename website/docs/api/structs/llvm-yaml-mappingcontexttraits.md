---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/yaml/mappingcontexttraits
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `MappingContextTraits` Struct Template

<p>This class is similar to <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits">MappingTraits&lt;T&gt;</a> but allows you to pass in additional context for each map operation. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;class T, class Context&gt;
struct llvm::yaml::MappingContextTraits&lt;T, Context&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamltraits-h">llvm/Support/YAMLTraits.h</a>"
</div>

## Description {#details}

<p>This class is similar to <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits">MappingTraits&lt;T&gt;</a> but allows you to pass in additional context for each map operation.</p>


<p>For example:</p>



<pre><code>struct MappingContextTraits&lt;MyStruct, MyContext&gt; {
  static void mapping(IO &amp;io, MyStruct &amp;s, MyContext &amp;c) {
    io.mapRequired("name", s.name);
    io.mapRequired("size", s.size);
    io.mapOptional("age",  s.age);
    ++c.TimesMapped;
  }
};
</code></pre>


<p>Definition at line 85 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamltraits-h">YAMLTraits.h</a>.</p>


<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>

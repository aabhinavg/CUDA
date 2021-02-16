## What is CUDA </br>
[CUDA](https://en.wikipedia.org/wiki/CUDA) is a [parallel processing](https://searchdatacenter.techtarget.com/definition/parallel-processing#:~:text=Parallel%20processing%20is%20a%20method,time%20to%20run%20a%20program.) platform model developed by NVIDIA developer for performing general computing operation on their GPU.
- CUDA abbrevation is <b>Compute Unified Device Architecture</b>
- CUDA platform provide a software layer which give access to the GPU's virtual instruction set along with parallel computing element for execution of computer kernel.
- This platform is designed to work with programming language such as [C](https://en.wikipedia.org/wiki/C_(programming_language)),[C++](https://en.wikipedia.org/wiki/C%2B%2B) and [Fortan](https://en.wikipedia.org/wiki/Fortran)

</p><p>CUDA 8.0 comes with the following libraries (for compilation &amp; runtime, in alphabetical order):
</p>
<ul><li>cuBLAS – CUDA Basic Linear Algebra Subroutines library</li>
<li>CUDART – CUDA Runtime library</li>
<li>cuFFT – CUDA Fast Fourier Transform library</li>
<li>cuRAND – CUDA Random Number Generation library</li>
<li>cuSOLVER – CUDA based collection of dense and sparse direct solvers</li>
<li>cuSPARSE – CUDA Sparse Matrix library</li>
<li>NPP – NVIDIA Performance Primitives library</li>
<li>nvGRAPH – NVIDIA Graph Analytics library</li>
<li>NVML – NVIDIA Management Library</li>
<li>NVRTC – NVIDIA Runtime Compilation library for CUDA C++</li></ul>
<p>CUDA 8.0 comes with these other software components:
</p>
<ul><li>nView – NVIDIA nView Desktop Management Software</li>
<li>NVWMI – NVIDIA Enterprise Management Toolkit</li>
<li>GameWorks <a href="/wiki/PhysX" title="PhysX">PhysX</a> – is a multi-platform game physics engine</li></ul>
<p>CUDA 9.0–9.2 comes with these other components:
</p>
<ul><li>CUTLASS 1.0 – custom linear algebra algorithms,</li>
<li><del>NVCUVID</del> – NVIDIA Video Decoder was deprecated in CUDA 9.2; it is now available in NVIDIA Video Codec SDK</li></ul>
<p>CUDA 10 comes with these other components:
</p>
<ul><li>nvJPEG – Hybrid (CPU and GPU) JPEG processing</li></ul>
<h2><span class="mw-headline" id="Advantages">Advantages</span><span class="mw-editsection"><span class="mw-editsection-bracket">[</span><a href="/w/index.php?title=CUDA&amp;action=edit&amp;section=3" title="Edit section: Advantages">edit</a><span class="mw-editsection-bracket">]</span></span></h2>
<p>CUDA has several advantages over traditional general-purpose computation on GPUs (GPGPU) using graphics APIs:
</p>
<ul><li>Scattered reads&#160;&#8211;&#32; code can read from arbitrary addresses in memory.</li>
<li>Unified virtual memory (CUDA&#160;4.0 and above)</li>
<li>Unified memory (CUDA&#160;6.0 and above)</li>
<li><a href="/wiki/Shared_memory_(interprocess_communication)" class="mw-redirect" title="Shared memory (interprocess communication)">Shared memory</a>&#160;&#8211;&#32; CUDA exposes a fast <a href="/wiki/Scratchpad_RAM" class="mw-redirect" title="Scratchpad RAM">shared memory</a> region that can be shared among threads. This can be used as a user-managed cache, enabling higher bandwidth than is possible using texture lookups.<sup id="cite_ref-16" class="reference"><a href="#cite_note-16">&#91;16&#93;</a></sup></li>
<li>Faster downloads and readbacks to and from the GPU</li>
<li>Full support for integer and bitwise operations, including integer texture lookups</li>
<li>On RTX 20 and 30 series cards, the CUDA cores are used for a feature called "RTX IO" Which is where the CUDA cores dramatically decrease game-loading times.</li></ul>
<h2><span class="mw-headline" 

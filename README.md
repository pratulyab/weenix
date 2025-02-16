# Weenix OS
- This repository is a placeholder for Weenix Operating System which I implemented as part of the graduate level course, CSCI 402 (Spring 2021), taught at USC by Prof. Bill Cheng.
- The end "product" of the working Weenix OS is a user-space terminal (like any other OS), behind which all the magic happens!

**Note:** The actual repository, which contains the source code, has been made private so as to honour the code of conduct of the University. It will only be available to potential employers who want to assess my capabilities in similar domains (and also who will agree not to share it with anyone else too). If you want to look at the code, contact me at https://pratulyab.github.io
<br>For more info about the instructor, see: http://merlot.usc.edu/william/usc/</p>

- The goal of the course was to familiarise students with the internals of operating system - starting from the abstractions of processes and threads, to all the way up to virtual memory. (course website: http://merlot.usc.edu/cs402-s21/)


<img src="os.png" />
<img src="weenix.png" />

<h2>Project Goals, Concepts, Challenges and Learnings</h2>
<ul>
  <li>Abstraction of threads, processes, and mutex</li>
  <li>Context switching</li>
  <li>Interrupts</li>
  <li>Understanding the boot process of the kernel</li>
  <li>Reference counting in the file system</li>
  <li>System call wrapper</li>
  <li>Case study of S5FS (system V file system)</li>
  <li>Demand paging</li>
  <li>Virtual memory map and the address space representation of a process</li>
  <li>Copy on write mechanism and shadow objects</li>
  <li>
    Memory allocation strategies
    <ul>
      <li>First fit & Best fit (both of which suffer from external fragmentation)</li>
      <li>Buddy system (which is relatively new and chooses internal fragmentation as its design strategy)</li>
      <li>Slab allocation (for pre-defined storage requirements)</li>
    </ul>
  </li>
  <li>Memory layout of a program (text, data, stack and heap sections)</li>
  <li>Write through and write back caches</li>
  <li>Benfits of log structured file system</li>
  <li>File system consistency/fault tolerance: Soft updates vs Shadow paging</li>
  <li>And much more...! (in private repository)</li>
</ul>

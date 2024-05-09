---
hide:
  - navigation
---

# Scientific software consulting services offered by Dr. Vedran Miletic

My name is Dr. Vedran Miletic and I am the [principal investigator](https://group.miletic.net/en/people/principal-investigator/) of [GASERI](https://group.miletic.net/en/), a research group working in the fields of computational biochemistry and high-performance computing.

![Vedran Miletic](https://vedran.miletic.net/images/vm.jpg)

Based on the knowledge and experience I gathered in my group's [research](https://group.miletic.net/en/projects/) [work](https://group.miletic.net/en/publications/), I offer consulting services for scientific software, including **development**, **testing**, **writing of documentation**, **porting**, and **deployment** for academic and industrial needs.

## Scientific software development and maintenance

I offer development and maintenance services for open-source or in-house developed scientific software. For example, [GROMACS](https://www.gromacs.org/), the open-source molecular dynamics simulation software my group uses, [customizes, and maintains](https://group.miletic.net/en/people/principal-investigator/#gromacs), and [LLVM](https://llvm.org/), the collection of modular and reusable compiler and toolchain technologies I [patched to improve AMD Radeon support](https://group.miletic.net/en/people/principal-investigator/#llvm), can also be extended to fit your needs. The software development services I offer include, but are not limited to:

- adding a new feature, for example, developing a new module that implements a particular method,
- improving existing functionality, for example, customizing the existing code for solving a particular problem,
- refactoring and modernizing code, for example, evolving from C++98 with dependency on legacy libraries and build systems to [C++17](https://en.cppreference.com/w/cpp/17)/[C++20](https://en.cppreference.com/w/cpp/20) with modern [open-source libraries](https://en.cppreference.com/w/cpp/links/libs) and [build](https://cmake.org/) [systems](https://mesonbuild.com/),
- extending the application programming interface (API) for your particular requirements, and
- fixing a particular issue as soon as possible.

## Scientific software testing and documentation writing

I offer writing new and improving existing unit and system tests for existing scientific software. I also offer testing pipeline design for various software as a service (SaaS) and self-hosted continuous integration (CI) tools.

I offer writing user- or developer-oriented documentation for existing scientific software, including the documentation of application programming interfaces (APIs). I also offer setup of the documentation build process for producing printable and web-friendly output from the common source.

## Scientific software cross-platform porting

I offer software porting of existing scientific applications and libraries from and to Linux, [FreeBSD](https://www.freebsd.org/)/[DragonFly BSD](https://www.dragonflybsd.org/), Solaris/[illumos](https://illumos.org/), macOS, and Windows, including [MSVC](https://visualstudio.microsoft.com/vs/features/cplusplus/), [Cygwin](https://www.cygwin.com/), [MSYS2](https://www.msys2.org/)/[Mingw-w64](https://www.mingw-w64.org/), and [WSL](https://apps.microsoft.com/store/detail/windows-subsystem-for-linux/9P9TQF7MRM4R). For example, my [portfolio](https://group.miletic.net/en/people/principal-investigator/#open-source-software-contributions) contains fixes to numerous issues related to porting GNU/Linux- and x86/AMD64-focused open-source scientific software such as [GROMACS](https://www.gromacs.org/), [ns-3](https://www.nsnam.org/), and [RxDock](https://rxdock.gitlab.io/) to various other operating systems, compilers, and platforms.

## Scientific software integration and deployment; workflow design and automation

I offer integration of existing open-source applications and libraries into your workflow, including deployment of server-side software on your on-premise or cloud infrastructure. I also offer assistance in choosing specific open-source software for your scientific workflow and workflow design and automation.

## Portfolio

Dr. Miletic's portfolio of [contributions to open-source software](https://group.miletic.net/en/people/principal-investigator/#open-source-software-contributions) contains detailed listing of prior work.

## Contact

If you are an academic or industrial subject that is interested in my services, please get in touch with me. You can reach me by sending an e-mail to <info@miletic.net> or via the following contact form and I will get back to you as soon as possible.

<form action="https://formspree.io/f/xdovkkwr" method="POST">
    <p>
        <label for="name">Name</label><br>
        <input type="text" name="name" class="md-input md-input--stretch" style="color: var(--md-default-fg-color); background-color: var(--md-default-bg-color)" required>
    </p>
    <p>
        <label for="email">Email</label><br>
        <input type="email" name="email" class="md-input md-input--stretch" style="color: var(--md-default-fg-color); background-color: var(--md-default-bg-color)" required>
    </p>
    <p>
        <label for="subject">Subject</label><br>
        <input type="text" name="subject" class="md-input md-input--stretch" style="color: var(--md-default-fg-color); background-color: var(--md-default-bg-color)" required>
    </p>
    <p>
        <label for="message">Message</label><br>
        <textarea name="message" class="md-input md-input--stretch" style="color: var(--md-default-fg-color); background-color: var(--md-default-bg-color); height: 7rem; outline: none; resize: none" required></textarea>
    </p>
    <input type="text" name="_gotcha" style="display: none">
    <button type="submit" class="md-button md-button--primary">Send</button>
</form>

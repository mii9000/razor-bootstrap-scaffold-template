[ASP.NET MVC Scaffolding](https://mvcscaffolding.codeplex.com) project has not been updated for quite a while now. But I have the privilege of using it now and it does not generate Views with Bootstrap classes and that does not work for me. So, I took Steven Sanderson's [tutorial](http://blog.stevensanderson.com/2011/04/06/mvcscaffolding-overriding-the-t4-templates) to make override T4 templates to be able to generate Views similar to what current default ASP.NET MVC scaffolders does.

How to use:
===========
1. Install from [NuGet](https://www.nuget.org/packages/MvcScaffolding)
2. Run `Scaffold CustomTemplate View Index` which will create the directory structure for you to the override templates
3. Copy paste and replace T4 templates from the repo into the directory with any existing and then start generating like before

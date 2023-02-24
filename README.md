


# Mastering C++ Multithreading
This is the code repository for [Mastering C++ Multithreading](https://www.packtpub.com/application-development/mastering-c-multithreading?utm_source=github&utm_medium=repository&utm_campaign=9781787121706), published by [Packt](https://www.packtpub.com/?utm_source=github). It contains all the supporting project files necessary to work through the book from start to finish.
## About the Book
Multithreaded applications execute multiple threads in a single processor environment, allowing developers achieve concurrency. This book will teach you the finer points of multithreading and concurrency concepts and how to apply them efficiently in C++.
## Instructions and Navigation
All of the code is organized into folders. Each folder starts with a number followed by the application name. For example, Chapter02.



The code will look like the following:
```
cout_mtx.lock();
cout << "Thread " << tid << " adding " << rval << ". New value: " << val
<< ".\n";
cout_mtx.unlock();
values_mtx.lock();
values.push_back(val);
values_mtx.unlock();
}
```

To follow the instructions in this book, you will need any OS (Windows, Linux, or macOS) and any C++ compiler installed on your systems.

## Example Code

From the `github` repository the code examples are as follows. Note that a
lot of the files have the same name, in particular `ch01_mt_example.cpp`
or `code1.cpp`.
Not all of the code examples in the book are present.

```
Directory           Description
-------------       -------------------------------------------------------------------
├── Chapter01       Simple C++ thread plus mutex example
├── Chapter02       (same example)
├── Chapter03       (windows and Qt thread examples from book are missing)
│   ├── 1           Non-function pthread skeleton
│   ├── 2           More fleshed out pthread example
│   ├── 3           Skeleton making use of "Poco"
│   └── 4           Skeleton making use of "Poco"
├── Chapter04       C++ threading example with synchronization and condition variables
├── Chapter05       C++11 threading:
│   ├── 1           Thread ID
│   ├── 2           Thread sleep
│   ├── 3           Thread swap
│   ├── 4           Simplitic std::out from thread
│   ├── 5           Globale mutex std::cout
│   ├── 6           Shared/exclusive example
│   ├── 7           std::lock_guard example
│   ├── 8           packaged_task example
│   └── 9           future example
├── Chapter06       Debugging, based off Chapter04 scheduler code
├── Chapter07       Best practices, based off Chapter04 scheduler code
├── Chapter08
│   ├── 1           Simple atomic operation example with c++11 threading
│   └── 2           <atomic> non-member functions example
├── Chapter09
│   └── 1
│       ├── 1       C-based MPI hello world
│       └── 2       C-based MPI + OpenMP hybrid hello world example
└── Chapter10
    └── 1           OpenCL example

```


## Related Products
* [Mastering C++ Programming](https://www.packtpub.com/application-development/mastering-c-programming?utm_source=github&utm_medium=repository&utm_campaign=9781786461629)

* [Mastering C++ Game Development](https://www.packtpub.com/game-development/mastering-c-game-development?utm_source=github&utm_medium=repository&utm_campaign=9781785885808)

* [C++ Machine Learning](https://www.packtpub.com/big-data-and-business-intelligence/c-machine-learning?utm_source=github&utm_medium=repository&utm_campaign=9781786468406)

### Suggestions and Feedback
[Click here](https://docs.google.com/forms/d/e/1FAIpQLSe5qwunkGf6PUvzPirPDtuy1Du5Rlzew23UBp2S-P3wB-GcwQ/viewform) if you have any feedback or suggestions.
### Download a free PDF

 <i>If you have already purchased a print or Kindle version of this book, you can get a DRM-free PDF version at no cost.<br>Simply click on the link to claim your free PDF.</i>
<p align="center"> <a href="https://packt.link/free-ebook/9781787121706">https://packt.link/free-ebook/9781787121706 </a> </p>

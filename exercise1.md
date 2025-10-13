Some common steps in a CI setup include linting, testing, and building. What are the specific tools for taking care of these steps in the ecosystem of the language you picked? You can search for the answers by Google.

I chose to look at c++. For linting clang-tidy is one possible solution it performs static analysis and lints the code and is build for c++. For testing we could use gtest that is built in Cmake, it provides a rich testing framework for c++ code. For building our best choice could be CMake that offers build automation, testing and packaging for our code. These previous tools are designed to be integrated with CMake so they work perfectly together.

What alternatives are there to set up the CI besides Jenkins and GitHub Actions? Again, you can ask Google!

Besides Jenkins and GitHub Actions other choices are GitLab which provides docker-based CI/CD pipeline. CircleCI is also one possible choice that works great for more complex workflows.

Would this setup be better in a self-hosted or a cloud-based environment? Why? What information would you need to make that decision?

It depends on many things which approach is better sometimes event a hybrid of the both works the best. Things to take into consideration are how large the project is, how hard is it to setup on your own and is it worth it. Also do you want to have full control of the project and how should it scale in the future. These are just some of the things to consider but let's say our project is just one persons single hobby project so in this case we should definately just use cloud-based environment for its simpler setup and hosting configurations.
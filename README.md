# EFI opencore with FakeCPU

This is an efi folder that i made to run my hackintosh using a confidential intel haswell(4th gen) i7

## Getting Started
First make sure if you can install your macOS without any patch, try differents EFI folders (i recommend searching in Olarila, it is a great hackintosh forum with an amazing amount of content and EFI folders)before using mine, maybe you don't need these patches.
I used some kernel patches and a fakeCPU ID to successfully boot.

### Prerequisites

Unsupported intel CPUs like Ivy Bridge, server CPUs some xeon and high-end processors like Haswell-E.
Remember that nvidia gpu's are only supported on macOS 10.13.x. Mojave, Catalina and Big Sur you won't be able to use your gpu.


### Installing

Just paste my EFI folder in your EFI partition. Please check the config.plist and kext folders before booting, this EFI folder are injecting nvidia web drivers and Realtek8111g network controller

Say what the step will be

```
Give the example
```

And repeat

```
until finished
```

End with an example of getting some data out of the system or using it for a little demo

## Running the tests

Explain how to run the automated tests for this system

### Break down into end to end tests

Explain what these tests test and why

```
Give an example
```

### And coding style tests

Explain what these tests test and why

```
Give an example
```

## Deployment

Add additional notes about how to deploy this on a live system

## Built With

* [Dropwizard](http://www.dropwizard.io/1.0.2/docs/) - The web framework used
* [Maven](https://maven.apache.org/) - Dependency Management
* [ROME](https://rometools.github.io/rome/) - Used to generate RSS Feeds

## Contributing

Please read [CONTRIBUTING.md](https://gist.github.com/PurpleBooth/b24679402957c63ec426) for details on our code of conduct, and the process for submitting pull requests to us.

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/your/project/tags). 

## Authors

* **Billie Thompson** - *Initial work* - [PurpleBooth](https://github.com/PurpleBooth)

See also the list of [contributors](https://github.com/your/project/contributors) who participated in this project.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Hat tip to anyone whose code was used
* Inspiration
* etc


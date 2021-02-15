## Robinhood Policy Engine RPM Repo

Hosted to make things easier with the Docker image [cfultz/robinhood:latest](https://github.com/cfultz/robinhood-docker)'s installation process of the RPM files. This also will assist in keeping them up-to-date instead of having to update with a new image everytime a release occures.

### Repo File

You are free to utilize this same repo file for your bare metal installations as well.

```RPM Repo
[robinhood]
name=Robinhood Policy Engine
baseurl=https://fultz.dev/repo/rhel/7
enabled=1
gpgcheck=0
```
#### Reason for 'gpgcheck=0'

The RPM files found on SourceForge were not signed by cea it seems. This will smooth the installation process a bit. Perhaps in the future I will compile/sign them myself.


### Contact

[@cfultz](https://github.com/cfultz/) hosts this repo based on the RPM files from [@cea-hpc](https://github.com/cea-hpc)'s SourceForge page [located here](https://sourceforge.net/projects/robinhood/). If you have questions regardin the repo, please contact him. If you have issues/questions with/about the RPM files themselves or the source code, contact [@cea-hpc](https://github.com/cea-hpc) directly.

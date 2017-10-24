# Brundle
Brundle is an R package that provides a series of functions for the normalisation of ChIP-Seq data
to internal or external controls. It can be installed using the [Brundle package on CRAN](https://cran.r-project.org/web/packages/Brundle/index.html).

It is supported by the data package [BrudleData](https://github.com/andrewholding/BrundleData).

[Brundle_Example](https://github.com/andrewholding/Brundle_Example) provides worked examples and preprocessing scripts for people who want to use Brundle in their own research. The examples are also packaged as a [Docker Container](http://dockerhub.com/andrewholding/brundle) pre-installed with all the tools to run the examples and pipeline. You can find [instructions on running the container](https://github.com/andrewholding/Brundle_Example/blob/master/README.md#using-docker-container) in the [Brundle_Example](https://github.com/andrewholding/Brundle_Example/blob/master/README.md) readme. The Dockerfile and other relavent code for generating the container can be found in the [BrundleDocker](https://github.com/andrewholding/BrundleDocker) repository. 

## Workflow

![Workflow](https://cdn.rawgit.com/andrewholding/Brundle_Example/master/images/workflow.svg)

## Example Data on UCSC Gene Browser
[CTCF Spike in-data](http://genome.ucsc.edu/cgi-bin/hgTracks?hgS_doOtherUser=submit&hgS_otherUserName=andrewholding&hgS_otherUserSessionName=Brundle)

[H2Av Spike in-data - Human](https://genome.ucsc.edu/cgi-bin/hgTracks?hgS_doOtherUser=submit&hgS_otherUserName=andrewholding&hgS_otherUserSessionName=ER%2FH2av)

[H2Av Spike in-data -Drosophilia](https://genome.ucsc.edu/cgi-bin/hgTracks?hgS_doOtherUser=submit&hgS_otherUserName=andrewholding&hgS_otherUserSessionName=ER%2FH2av%20dm3)

[hsER/mmER Spike-in data - Human](https://genome.ucsc.edu/cgi-bin/hgTracks?hgS_doOtherUser=submit&hgS_otherUserName=andrewholding&hgS_otherUserSessionName=hsER%2FmmER)

[hsER/mmER Spike-in data - Mouse](https://genome.ucsc.edu/cgi-bin/hgTracks?hgS_doOtherUser=submit&hgS_otherUserName=andrewholding&hgS_otherUserSessionName=HsER%2FmmER%20mm9)

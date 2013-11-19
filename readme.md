#ian's resume (forked from harperreed)

##Harper's explanation and docs:

I authored my resume in HTML around 2002. It wasn't out of date, but I wasn't satisfied with how the data was stored. I needed something that allowed me to generate multiple versions without effort. I also wanted to be able to curate my resume the same way that I curate the rest of my data. 

The first time I thought about doing this was after seeing my friend [Anders' resume in yaml](http://anders.conbere.org/resume/resume.yaml) (his [brother Morgan's resume is in protobufs](https://raw.github.com/mconbere/Resume/master/mconbere/mconbere.ptxt) (they are a crazy family)). Anders' resume made sense. And reading about Morgan's [thoughts behind his protobuf resume](https://github.com/mconbere/Resume/) made me think of converting my resume to yaml. 

I then ran into [Ming-Ho Yee](http://mhyee.com/)'s [repo](https://github.com/mhyee/resume) that had a [nice ruby script](https://github.com/mhyee/resume/blob/master/generate.rb) to generate HTML and TEX from yaml.  I "forked" the repo, built my resume in yaml and migrated my old HTML resume to the ERB template.  

A couple of notes:

 * I really liked how Ming-Ho Yee separated out the private data into its own yaml file. 
 * When using LaTeX, I have no idea what I am doing. Apparently I need to figure that out if i want to generate PDF files.
 * I currently only need HTML and Markdown

####That is it. 

* [Anders' resume in yaml](http://anders.conbere.org/resume/resume.yaml)
* [Morgan's resume in protobufs](https://github.com/mconbere/Resume/)
* [Ming-Ho Yee](http://mhyee.com/)'s [YAML resume](https://github.com/mhyee/resume)
* [David Hu's resume in YAML](https://github.com/divad12/resume) - python generation scripts

#### Obviously
This is not the resume of Harper Reed, but despite that, If you use any of this - please remove my identity from your resume.yaml.


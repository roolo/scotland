# Scotland
## Purpose
Just another template for running [YARD documentation tool](http://yardoc.org/) Server as an [Rack](http://rack.rubyforge.org/) App. For me it's running it on [pow server](http://pow.cx/).

## Using

1. Clone this repo
2. Go to the new directory of this repo
2. Duplicate `config.ru.tmp` file and rename it to `config.ru`
3. Fill `config.ru` along with examples in file and according to code documentations which you would like to have served by rack server

### In case of using pow and powder

5. Link directory by [powder](https://github.com/Rodreegez/powder) or simply [ln](http://unixhelp.ed.ac.uk/CGI/man-cgi?ln)

    #using powder
    powder link
    
    #using ln
    ln -s . ~/.pow/scotland

6. Open it in web browser -- `powder open`
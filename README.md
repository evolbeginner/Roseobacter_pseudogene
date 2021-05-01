# Roseobacter_pseudogene

# It's strongly recommended to install ruby https://www.ruby-lang.org/en/documentation/installation/ before using the scripts. The reason is because I have prepared the scripts written in Ruby for some simple data processing and related stuff. Of cours, it is possible to write your own scripts instead of using my Ruby scripts.

# After installation of Ruby, do the following in bash.
export RUBYLIB=$RUBYLIB:$PWD/scripts/prepare_scripts/lib
gem install bio parallel

# Make sure that the installation of these packages is successfull.
ruby scripts/checkRubyPackages.rb

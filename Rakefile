require 'pry'

desc 'loads pry console'
task :pry do
  binding.pry
end
namespace :greeting do 
  desc 'outputs hello to the terminal'
  task :hello do
    puts "hello from Rake!"
  end
  namespace :greeting do 
  desc 'outputs hola to the terminal'
  task :hola do
    puts "hola de Rake!"
  end
end

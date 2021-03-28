namespace :greeting do
  desc 'outputs hello to the terminal'
  task :hello do
    puts "hello from Rake!"
  end
  
  task :hola do
    puts "hola de Rake!"
  end
end

namespace :db do
  desc 'migrate changes to your database'
  task :migrate => :environment do
    Student.create_table
  end
end

task :environment do
  require_relative './config/environment'
end


desc 'drop into the Pry console'
task :console do #=> :environment do
  #Pry.start
end




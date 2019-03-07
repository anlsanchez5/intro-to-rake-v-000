desc 'outputs hello to the terminal'
task :hello do
  puts "hello from Rake!"
end

namespace :db do 
  des 'migrate changes to database'
  task :migrate => :environment do 
    Student.create_table 
  end
end

namespace :greeting do

    desc 'outputs hello to the terminal'
    task :hello do
      puts "hello from Rake!"
    end

    desc 'outputs hola to the terminal'
    task :hola do
      puts "hola de Rake!"
    end
end

task :enviroment do
    require_relative './config/enviroment'
end

namespace :db do
    desc 'migrates the database.'
    task :seed => 'db/seed.rb' do
    end
end

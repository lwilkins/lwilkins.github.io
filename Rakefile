namespace :sass do

    paths = 'static/sass/:static/css'

    task :compile do
      sh "sass --update --force --style compressed #{paths}"
    end

    task :watch_dist do
      sh "sass --watch --style compressed #{paths}"
    end

    task :watch do
      sh "sass --watch #{paths}"
    end
end

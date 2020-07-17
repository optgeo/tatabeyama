desc 'download DEM'
task :download do
  url = "https://www.geospatial.jp/ckan/dataset/148368e9-3312-48bf-96d0-0ec83fc0989e/resource/61441db9-2ddf-4fb1-b3fc-c56b927ca88c/download/05of79.zip"
  sh "curl -O #{url}"
  sh "cd src; unzip ../05of79.zip"
end

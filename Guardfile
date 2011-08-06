# A sample Guardfile
# More info at https://github.com/guard/guard#readme
guard 'livereload' do
  # watch(/^.+(\.html\.haml)/)
  watch(/^.+\.html/)
end

guard 'haml', :input => 'views' do
  watch(/^.+(\.html\.haml)/)
end

guard 'sass', :input => 'views', :output => 'styles' do
  watch(%r{.+\.s[ac]ss})
end
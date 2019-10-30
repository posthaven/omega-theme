
SCSS_OPTS = 'compass', 'compile', 'src/stylesheets/blog.scss', '--no-sourcemap'
WATCH_OPTS = 'compass', 'watch', 'src/stylesheets/blog.scss', '--no-sourcemap'

desc 'Compile the SCSS'
task(:compile) { exec(*SCSS_OPTS) }

desc 'Watch the SCSS files and compile on change'
task(:watch) { exec(*WATCH_OPTS) }

task default: :compile

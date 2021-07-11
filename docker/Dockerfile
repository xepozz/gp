FROM jekyll/jekyll:latest

COPY Gemfile* ./
RUN bundle install

EXPOSE 4000
ENTRYPOINT bundle exec jekyll serve --livereload --host 0.0.0.0


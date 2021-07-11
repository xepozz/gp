FROM jekyll/jekyll:latest

COPY Gemfile Gemfile.lock ./
RUN bundle instal

EXPOSE 4000
ENTRYPOINT jekyll serve --livereload


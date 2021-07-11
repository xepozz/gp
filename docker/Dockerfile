FROM jekyll/jekyll:latest

COPY Gemfile* ./
RUN bundle instal

EXPOSE 4000
ENTRYPOINT jekyll serve --livereload


MUXI
===
![muxi](http://7xj431.com1.z0.glb.clouddn.com/111)

                                        ~木muxi犀~

                                  a python web framework
                                     simple & powerful

                                        introduce:
                 muxi is a ~simple python web framework~ written by ~python~,
                 based on:
                      ~werkzeug~: https://github.com/mitsuhiko/werkzeug
                      ~jinja2~: https://github.com/mitsuhiko/jinja2
                      ~mana~: https://github.com/neo1218/mana
                               ~some certain flask extensions~


                                        principle:
                                     ~on top of flask~
                  we all like ~flask~, because of ~werkzeug & jinja2~, but
              we must admit, when we use flask to deal with some ~big project~,
                                 it looks very complicated:
                      we need to create the project directory manually,
                      import and init some certain extensions(
                                flask-wtf, flask-sqlalchemy,
                                flask-admin,  ......
                                ),
                      create and register a blueprint by hand,
                      and use flask-admin to create admin site,
                                          ......
                                          I think
                               ~it is not a good experience~~


                                           muxi
                                     ~ the specific ~
          muxi has it own ~command system~(see: muxi --help) which based on ~mana~
          to generate your muxi project. you can use ~muxi command~ to:
          init(which suport a flexible options), register,deploy and manage your project.

            muxi use ~sqlalchemy~ as database orm and integrated flask-sqlalchemy to
            provide a high level api, so, you can just ~from muxi import db~
                                        and coding

            muxi use ~jinja2~ as front-end template, and use a very flexible way
            to add jinja templates: the view decorator, which can import from muxi

                well, when you use muxi command to create muxi project, it will
                            automatically generate ~admin site~


                                         LICENSE:
                                  MIT license is great~~


                                      About::Name
         the original meaning of 木犀(muxi) is {{ a sweet-scented osmanthus }} and
                          used as my :team name ~ MuxiStudio:
            beacause I love my team, so I chose muxi as this web framework's name


                                       Quick Start
                 https://github.com/neo1218/muxi/blob/master/doc/start.md


                              ~~~muxi is under development~~~

# Projeto lúdico para estudos O guia DEFINITIVO de relacionamentos no Ruby on Rails - Live #04

Canal - Invenio Tech - Professor Daniel Denis Moreira - Setembro 2024.

Assista:  https://www.youtube.com/watch?v=xL5nE7HP2B0

Things you may want to cover:

* Ruby version ruby 3.3.1, Rails 7.2.1

* class AddPlanetToAlien < ActiveRecord::Migration[7.2]
  def change
    add_reference :aliens, :planet, null: TRUE, foreign_key: true   <------ null: false trocar para true. E logo depois de todos selecionados retornei FALSE.
  end
end

* Configuration Postgresql app/config/database.yml

* host: localhost username: postgres password:

* Database initialization

* Relation power Alien with yours powers

  # AlienPower é a TABELA ASSOCIATIVA (muitos para muitos) no banco de dados onde um Alien terá muitos poderes e um Power poderá pertencer a muitos Aliens. 

* Relation local Alien with the Planet

* Deployment instructions

* ...
# inveniospacerails

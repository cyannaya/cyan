class AddEmailUniquenessIndex < ActiveRecord::Migration
  def up
    add_index :users, :email, :unique => ture
  end

  def down
    remove_index :users, :email
  end
end

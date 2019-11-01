class Anagram

  attr_accessor :name 

  def initialize(word)
    @name = word  # #should take a word on initialization, #and instances should respond to a match method that #takes an array of possible anagrams.
  end   


  def match(array)
    array.select {|x| x.split("").sort == @name.split("").sort}
  end   

end 
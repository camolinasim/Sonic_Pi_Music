use_synth  :chipbass
use_bpm 130

loop do
  #first question
  1.times do
    play :as2,  sustain: 1.5
    sleep 0.5
    
    play :as3,  sustain: 1.5
    sleep 0.5
    
    play :d4,  sustain: 1.5
    sleep 0.5
    
    play :a4,  sustain: 1.5
    sleep 0.5
  end
  
  #first response
  1.times do
    sleep 2.5
    play :d4, sustain: 1
    sleep 0.5
    
    play :a4, sustain: 1
    sleep 0.5
    
    play :g4, sustain: 1
    sleep 0.5
    
    play :c5, sustain: 1
    sleep 0.5
    
    play :a4, sustain: 0.5
    sleep 0.5
    
    play :g4, sustain: 0.5
    sleep 0.5
    
    play :e4, sustain: 0.5
    sleep 0.5
  end
  
  
  #second question
  1.times do
    
    
    play :a2, amp: 2, sustain: 1
    sleep 0.5
    
    play :a3, amp: 2, sustain: 1
    sleep 0.5
    
    play :c4, amp: 2, sustain: 1
    sleep 0.5
    
    play :g4, amp: 2, sustain: 1
    
    
  end
  
  #second response
  1.times do
    sleep 2.5
    play :a2, amp: 2, sustain: 1
    sleep 0.5
    
    play :c4, amp: 2,  sustain: 1
    sleep 0.5
    
    play :g4, amp: 2,  sustain: 1
    sleep 0.5
    
    play :f4, amp: 2,  sustain: 1
    sleep 0.5
    
    play :c5, amp: 2,  sustain: 1
    sleep 0.5
    
    play :g4, amp: 2,  sustain: 1
    sleep 0.5
    
    play :f4, amp: 2,  sustain: 1
    sleep 0.5
    
    play :c4, amp: 2,  sustain: 1
    sleep 0.5
  end
  
  
  #third question
  1.times do
    
    play :g2, amp: 2,  sustain: 1
    sleep 0.5
    
    play :g3, amp: 2,  sustain: 1
    sleep 0.5
    
    play :as3, amp: 2,  sustain: 1
    sleep 0.5
    
    play :f4, amp: 2,  sustain: 1
    sleep 0.5
  end
  
  #third response
  1.times do
    
    sleep 2.0
    
    play :g2, amp: 2,  sustain: 1
    sleep 0.5
    
    play :E4, amp: 2,  sustain: 1
    sleep 0.5
    
    play :f4, amp: 2,  sustain: 1
    sleep 0.5
    
    play :E4, amp: 2,  sustain: 1
    sleep 0.5
    
    play :g4, amp: 2,  sustain: 1
    sleep 0.5
    
    play :E4, amp: 2,  sustain: 1
    sleep 0.5
    
    play :c4, amp: 2,  sustain: 1
    sleep 0.5
    
    play :a3, amp: 2, sustain: 1
    sleep 0.5
    
  end
  #fourth question
  1.times do
    play :f2, amp: 2,  sustain: 1
    sleep 0.5
    
    play :f3, amp: 2, sustain: 1
    sleep 0.5
    
    play :a3, amp: 2,  sustain: 1
    sleep 0.5
    
    play :e4, amp: 2, sustain: 1
    sleep 0.5
  end
  
  #fourth response
  1.times do
    
    sleep 2
    play :f2, amp: 2,  sustain: 2
    sleep 0.5
    
    play :f3, amp: 2, sustain: 1
    sleep 0.5
    
    play :e4, amp: 2, sustain: 1
    sleep 0.5
    
    play :d4, amp: 2, sustain: 1
    sleep 0.5
    
    play :g4, amp: 2,  sustain: 1
    sleep 0.5
    
    play :f4, amp: 2,  sustain: 1
    sleep 0.5
    
    play :c5, amp: 2,  sustain: 1
    sleep 0.5
    
    play :as4, amp: 2, sustain: 1
    sleep 0.5
  end
end
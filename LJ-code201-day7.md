repo - create branch for each day

Lessons learned:
* both of these will add values to an array, use either
array.push(<value>)

-or-

array[i] = <value[i]>

randomNumber: function(){
    for(var i = 0; i < hours.length; i++){
      this.customers.push( Math.floor(Math.random() * (this.maxCust - this.minCust)) + this.minCust);
    }
  },

  sales: function(){
    for(var i = 0; i < hours.length; i++){
      this.hourlySales[i] = Math.floor(this.customers[i] * this.avgSale);
    }
  },

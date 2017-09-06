function reverbProfit(p){
  if(p > 0){
    console.log("If you sell this item on Reverb, you will make $" + p +".");
  }
  else {
    console.log("You should not sell this item on Reverb, you will lose $" + p + "!");
  }
}

function craigslistProfit(c){
  console.log("If you sell this item on Craigslist, you will make $" + c +".");
}

function compareProfit (price, box, shipping) {
  var sellingPrice = price;
  var boxCost = box;
  var shippingCost = shipping;
  var trainTicket = 2.75 * 2;
  var reverbCommission = sellingPrice * 0.035;
  var reverbExpenseses = boxCost + shippingCost  + reverbCommission;
  var profit = sellingPrice - reverbExpenseses;
  reverbProfit(profit);
  craigslistProfit(sellingPrice - trainTicket);
}


// compareProfit(Selling Price, Box Cost, Shipping Cost)
compareProfit(100, 5, 15);

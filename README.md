describe('Tutorialspoint', function () {
    
    it('Scenario 1', function (){
       
       cy.visit("https://www.lambdatest.com/automation-demos")
       cy.get('#username').type ('lambda')
       cy.get('#password').type ('lambda123')
       cy.get('.applynow').click ()
       cy.viewport('iphone-6')

       
    })


    it('Scenario 2', function (){
       
      cy.visit("https://www.lambdatest.com/selenium-automation")
      

      
   })
 })

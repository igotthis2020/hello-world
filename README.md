# hello-world
Deploying an ERC20 Contract
contract TokenERC20

{
address public owner;

function owned() {
owner = 0x231dA89BeE05CEAFB9eAaD96CEf4163a442d7639;
        }

modifier onlyOwner {
require(0x231dA89BeE05CEAFB9eAaD96CEf4163a442d7639 == owner);
            _;
        }

{
if(centralMinter != 0 ) owner = centralMinter;
}


Function TransferOwnership

{
owner = newOwner;
        }
    }



{
public name : Master of All Insurance Token;
public symbol : MIT;
public decimals : 18;
totalSupply : 10000000000000000;

Balance
mapping (address => uint256) public balanceOf;
mapping (address => mapping (address => uint256)) public allowance;

transfer  tokenERC20
{

symbol : MIT; 

name = Master of All Insurance Token; 

decimals = 18; 

uint public _totalSupply = 1000000000000000000; 


balancesOf[0x231dA89BeE05CEAFB9eAaD96CEf4163a442d7639] = safeSub(balances[0x231dA89BeE05CEAFB9eAaD96CEf4163a442d7639], tokens); 

balances[to] = safeAdd(balances[to], tokens); 

Transfer(0x231dA89BeE05CEAFB9eAaD96CEf4163a442d7639, to, tokens); 

return true; 
}
Function Approve
{ 

allowed[0x231dA89BeE05CEAFB9eAaD96CEf4163a442d7639][spender] = tokens; 

Approval(0x231dA89BeE05CEAFB9eAaD96CEf4163a442d7639, spender, tokens); 

return true; 

} 


contract SafeMath 

{ 

function safeAdd(uint a, uint b) public pure returns (uint c) { 

c = a + b; 

require(c >= a); 

} 

function safeSub(uint a, uint b) public pure returns (uint c) { 

require(b <= a); 

c = a - b; 

} 

function safeMul(uint a, uint b) public pure returns (uint c) { 

c = a * b; 

require(a == 0 || c / a == b); 

} 

function safeDiv(uint a, uint b) public pure returns (uint c) { 

require(b > 0); 

c = a / b; 

} 

} 

Function TransferFROM
{ 

balances[from] = safeSub(balances[from], tokens); 

allowed[from][0x231dA89BeE05CEAFB9eAaD96CEf4163a442d7639] = safeSub(allowed[from][0x231dA89BeE05CEAFB9eAaD96CEf4163a442d7639], tokens); 

balances[to] = safeAdd(balances[to], tokens); 

Transfer(from, to, tokens); 

return true; 

} 


Function Allowance
{
return allowed[tokenOwner][spender]; 

} 

Function ApproveAndCall
{
allowed[0x231dA89BeE05CEAFB9eAaD96CEf4163a442d7639][spender] = tokens; 

Approval(0x231dA89BeE05CEAFB9eAaD96CEf4163a442d7639, spender, tokens); 

ApproveAndCallFallBack(spender).receiveApproval(msg.sender, tokens, this, data); 

return true; 

} 


Function transferAnyERC20Token
{
return ERC20Interface(0x231dA89BeE05CEAFB9eAaD96CEf4163a442d7639).transfer(owner, tokens); 

} 

Function SetPrices
{
sellPrice = newSellPrice;
buyPrice = newBuyPrice;
    }


Function FreezeAccount
{
frozenAccount[target] = freeze;
emit FrozenFunds(target, freeze);
    }

{
require(!frozenAccount[0x231dA89BeE05CEAFB9eAaD96CEf4163a442d7639]);
require(approvedAccount[0x231dA89BeE05CEAFB9eAaD96CEf4163a442d7639]);
    }

